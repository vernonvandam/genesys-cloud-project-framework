# Layer 10 — Spreadsheet Model — Calculation Model

## Purpose

This document defines the calculations required to convert the Layer 10 source models into project estimates, resource requirements, durations, schedules, forecasts and management metrics.

The calculation model must remain aligned with:

```text
03-estimation-model/
05-dependency-model/
06-project-schedule-model/
```

---

# 1. Calculation Principles

The workbook shall:

1. Preserve baseline values.
2. Apply project-specific adjustments separately.
3. Keep effort and duration separate.
4. Keep cost and effort separate.
5. Keep baseline and actual values separate.
6. Keep actual and forecast values separate.
7. Preserve dependency-driven sequencing.
8. Avoid hidden calculations.
9. Document material formulas.
10. Make calculations auditable.

---

# 2. Baseline Effort

Baseline effort is sourced from the Estimation Model.

```text
Baseline Effort
=
Authoritative Layer 10 Baseline
```

The workbook must not alter the baseline value merely because project conditions change.

---

# 3. Project Adjusted Effort

Project effort is calculated by applying approved project-specific factors.

A generic model is:

```text
Project Effort
=
Baseline Effort
× Complexity Factor
× Volume Factor
× Integration Factor
× Customer Factor
× Reuse Factor
× Risk Factor
```

Not every factor must apply to every task.

Inactive factors should default to:

```text
1.00
```

---

# 4. Adjustment Factor

Adjustment factors should be explicitly visible.

Example:

```text
Baseline Effort       8.0 h
Complexity Factor     1.25
Volume Factor         1.00
Integration Factor    1.10
Risk Factor           1.00

Project Effort
= 8 × 1.25 × 1.10
= 11.0 h
```

---

# 5. Effort Confidence

Estimates should carry a confidence classification.

Recommended values:

```text
LOW
MEDIUM
HIGH
```

Confidence should not automatically alter effort unless the Estimation Model explicitly defines a contingency mechanism.

---

# 6. Contingency

Where contingency is used, it must be separately represented.

```text
Base Project Effort
        +
Contingency
        =
Forecast Effort
```

Contingency must not be hidden inside baseline effort.

---

# 7. Resource Capacity

Resource capacity can be represented as:

```text
Available Hours
=
Working Hours
× Allocation %
× Availability %
```

Example:

```text
40 hours
× 50%
× 80%
=
16 available hours
```

---

# 8. Resource Utilisation

```text
Utilisation
=
Assigned Effort
÷
Available Capacity
```

Example:

```text
Assigned = 24 h
Available = 32 h

Utilisation = 75%
```

Recommended thresholds should be configurable rather than hard-coded.

---

# 9. Task Duration

Task duration must remain separate from effort.

A basic calculation is:

```text
Duration
=
Project Effort
÷
Daily Available Capacity
```

Example:

```text
Project Effort = 16 h
Daily Capacity = 8 h

Duration = 2 days
```

---

# 10. Dependency Scheduling

Task dates must respect predecessor relationships.

For a Finish-to-Start dependency:

```text
Successor Start
=
Predecessor Finish
+
Lag
```

The workbook must support at least:

```text
FS
SS
FF
SF
```

---

# 11. Critical Path

Critical path should be calculated from:

- task durations
- dependencies
- milestones
- schedule constraints

Where the workbook implements critical-path calculations, it must align with the authoritative Dependency Model.

The workbook must not introduce a conflicting critical-path definition.

---

# 12. Float

Total float may be calculated as:

```text
Latest Start
-
Earliest Start
```

or:

```text
Latest Finish
-
Earliest Finish
```

depending on the scheduling implementation.

Tasks with zero or negative float should be identified as critical or schedule-risk tasks according to the approved dependency methodology.

---

# 13. Project Effort

Project total effort:

```text
Total Project Effort
=
SUM(Project Effort for all included tasks)
```

Reports should allow filtering by:

- phase
- domain
- capability
- workstream
- role
- environment
- customer responsibility

---

# 14. Delivery Effort

```text
Delivery Effort
=
SUM(Project Effort where Customer Responsibility = NO)
```

---

# 15. Customer Effort

```text
Customer Effort
=
SUM(Project Effort where Customer Responsibility = YES)
```

Joint tasks should be split where separate delivery and customer effort is material.

---

# 16. Workstream Effort

```text
Workstream Effort
=
SUM(Project Effort for Workstream)
```

---

# 17. Phase Effort

```text
Phase Effort
=
SUM(Project Effort for Layer 1 Phase)
```

This supports phase-level planning and reporting.

---

# 18. Domain Effort

```text
Domain Effort
=
SUM(Project Effort for Layer 2 Domain)
```

This supports capability-domain estimation.

---

# 19. Role Effort

```text
Role Effort
=
SUM(Project Effort assigned to Role)
```

This supports resource planning.

---

# 20. Cost Calculation

Where role rates are available:

```text
Task Cost
=
Project Effort
×
Role Rate
```

Total cost:

```text
Project Cost
=
SUM(Task Cost)
```

Where a task uses multiple roles, effort should be split by role before cost is calculated.

---

# 21. Actual Effort

Actual effort is accumulated independently:

```text
Actual Effort
=
SUM(Recorded Actual Effort)
```

Actual effort must not overwrite baseline or project estimate values.

---

# 22. Estimate at Completion

```text
EAC
=
Actual Effort
+
Remaining Forecast Effort
```

---

# 23. Effort Variance

```text
Effort Variance
=
EAC
-
Baseline Effort
```

A percentage variance can be calculated as:

```text
Variance %
=
(EAC - Baseline Effort)
÷
Baseline Effort
```

---

# 24. Schedule Variance

Schedule variance should compare baseline and current forecast dates.

Example:

```text
Finish Variance
=
Forecast Finish
-
Baseline Finish
```

Positive values indicate delay when using a forward calendar model.

---

# 25. Task Completion

Task completion may be represented as:

```text
0%
25%
50%
75%
100%
```

or a more granular percentage.

The project should use one standard approach.

---

# 26. Remaining Effort

```text
Remaining Effort
=
EAC
-
Actual Effort
```

Alternatively, if the forecast model directly estimates remaining effort:

```text
Remaining Effort
=
Forecast Remaining
```

The workbook must not calculate both independently without defining which is authoritative.

---

# 27. Forecast Finish

Forecast finish should be derived from:

- remaining effort
- resource availability
- dependencies
- schedule constraints

Example:

```text
Remaining Effort
       ↓
Available Capacity
       ↓
Remaining Duration
       ↓
Dependencies
       ↓
Forecast Finish
```

---

# 28. Milestone Variance

```text
Milestone Variance
=
Forecast Milestone Date
-
Baseline Milestone Date
```

Milestones at risk should be surfaced on reporting dashboards.

---

# 29. Phase Gate Readiness

Phase gate readiness should consider:

```text
Entry Criteria
    +
Required Tasks
    +
Required Evidence
    +
Outstanding Risks
    +
Outstanding Customer Actions
    +
Approvals
```

A gate should not be automatically marked complete solely because all tasks are complete.

---

# 30. Resource Overload

A resource should be flagged when:

```text
Assigned Capacity
>
Available Capacity
```

The threshold must be configurable.

---

# 31. Schedule Health

Recommended calculation inputs:

```text
Overdue Tasks
Blocked Tasks
Critical Tasks At Risk
Milestone Variance
Resource Overload
Outstanding Customer Actions
Outstanding Dependencies
```

The workbook may derive:

```text
ON TRACK
AT RISK
DELAYED
BLOCKED
COMPLETE
```

---

# 32. Calculation Controls

Calculated values should be visually distinguishable from editable inputs.

The workbook should identify:

```text
SOURCE
INPUT
CALCULATED
OVERRIDE
```

---

# 33. Manual Overrides

Manual overrides should be permitted only where project-specific conditions require them.

An override should contain:

- original value
- override value
- reason
- requested by
- approved by
- date

---

# 34. Formula Protection

Core formulas should be protected against accidental modification.

Examples:

- total effort
- project effort
- utilisation
- variance
- EAC
- schedule calculations
- critical-path calculations

---

# 35. Definition of Done

The Calculation Model is complete when:

- baseline effort calculation is defined
- project adjustments are defined
- contingency treatment is defined
- resource capacity is defined
- resource utilisation is defined
- duration calculation is defined
- dependency calculations are defined
- critical-path integration is defined
- float is defined
- project totals are defined
- role totals are defined
- cost calculations are defined
- actuals are defined
- EAC is defined
- variance calculations are defined
- milestone variance is defined
- phase-gate readiness is defined
- manual override controls are defined
- calculation protection is defined
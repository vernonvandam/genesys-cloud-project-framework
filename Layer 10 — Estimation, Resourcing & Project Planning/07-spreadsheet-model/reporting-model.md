# Layer 10 — Spreadsheet Model — Reporting Model

## Purpose

The Reporting Model defines how project estimation, schedule, resource, dependency and delivery data is presented to project stakeholders.

The reporting model must support different levels of project governance without creating separate sources of truth.

---

# 1. Reporting Principles

Reports shall:

1. Use authoritative workbook data.
2. Avoid manually duplicated figures.
3. Clearly distinguish baseline, current forecast and actuals.
4. Support drill-down from summary to task.
5. Identify exceptions.
6. Highlight customer dependencies.
7. Highlight critical-path risks.
8. Highlight schedule variance.
9. Highlight resource constraints.
10. Support project governance meetings.

---

# 2. Reporting Hierarchy

Reports should support:

```text
Project
    ↓
Phase
    ↓
Workstream
    ↓
Domain
    ↓
Capability
    ↓
Task
```

---

# 3. Executive Dashboard

The executive dashboard should show:

```text
Project Status
Overall Schedule Status
Overall Effort Status
Go-Live Date
Critical Path Status
Milestone Status
Phase Gate Status
Top Risks
Top Issues
Customer Actions
```

---

# 4. Project Summary

The project summary should include:

| Metric | Baseline | Current | Actual |
|---|---:|---:|---:|
| Effort | | | |
| Duration | | | |
| Cost | | | |
| Tasks | | | |
| Milestones | | | |

---

# 5. Task Status Report

The task status report should provide:

- Task ID
- Task
- Phase
- Domain
- Role
- Status
- Planned Finish
- Forecast Finish
- Variance
- Critical Path
- Customer Dependency

Recommended filters:

```text
Phase
Domain
Workstream
Role
Status
Environment
Critical Path
Customer Responsibility
```

---

# 6. Effort Report

The effort report should show:

```text
Baseline Effort
Project Effort
Actual Effort
Remaining Effort
Forecast Effort
Variance
```

It should support aggregation by:

- phase
- domain
- capability
- workstream
- role
- resource
- customer responsibility

---

# 7. Resource Report

The resource report should show:

```text
Role
Resource
Available Capacity
Assigned Effort
Actual Effort
Remaining Effort
Utilisation
Overload
```

---

# 8. Workstream Report

The workstream report should show:

- total tasks
- completed tasks
- remaining tasks
- baseline effort
- project effort
- actual effort
- forecast effort
- schedule variance
- risks
- issues

---

# 9. Layer 1 Phase Report

The Layer 1 report should show:

```text
P01
P02
P03
...
P12
```

For each phase:

- task count
- effort
- duration
- completion
- status
- critical tasks
- milestones
- phase gate
- customer actions

---

# 10. Layer 2 Domain Report

The Layer 2 report should show:

- domain
- capability count
- task count
- baseline effort
- project effort
- actual effort
- forecast effort
- completion
- status

This allows management to see which Genesys Cloud capability domains are driving project effort.

---

# 11. Capability Report

Capability-level reporting should show:

```text
Capability ID
Capability Name
Task Count
Baseline Effort
Project Effort
Actual Effort
Remaining Effort
Status
```

---

# 12. Critical Path Report

The critical-path report should identify:

- critical tasks
- critical milestones
- current status
- planned finish
- forecast finish
- float
- dependency
- risk

Recommended categories:

```text
CRITICAL
NEAR CRITICAL
NON-CRITICAL
```

---

# 13. Customer Dependency Report

The customer report should show:

```text
Customer Action
Owner
Due Date
Status
Impact
Dependency
Escalation
```

This report should identify overdue customer actions separately.

---

# 14. Milestone Report

Milestone reporting should show:

| Field | Description |
|---|---|
| Milestone | Milestone name |
| Baseline Date | Original date |
| Forecast Date | Current date |
| Variance | Date variance |
| Status | Current status |
| Owner | Responsible owner |
| Risk | Associated risk |

---

# 15. Phase Gate Report

The phase-gate report should show:

```text
Gate
Phase
Readiness
Entry Criteria
Exit Criteria
Outstanding Actions
Approvals
Decision
```

Recommended decisions:

```text
GO
GO WITH CONDITIONS
NO-GO
PENDING
```

---

# 16. Actual vs Baseline

The workbook should provide comparison between:

```text
Baseline
    vs
Actual
```

for:

- effort
- cost
- schedule
- task completion
- milestones

---

# 17. Forecast vs Baseline

The workbook should also provide:

```text
Baseline
    vs
Current Forecast
```

This is distinct from actual-vs-baseline reporting.

---

# 18. Forecast vs Actual

The workbook should support:

```text
Forecast
    vs
Actual
```

This supports forecasting accuracy during delivery.

---

# 19. Project Health

Project health should be calculated using configurable indicators.

Possible indicators:

```text
Effort
Schedule
Resources
Dependencies
Customer Actions
Testing
Migration
Go-Live
Risks
Issues
```

Overall health:

```text
GREEN
AMBER
RED
```

The scoring rules must be documented and configurable.

---

# 20. Management Reporting

Management reports should answer:

### Are we on schedule

```text
Schedule Variance
Critical Path
Milestone Variance
```

### Are we within effort

```text
Baseline
Forecast
Actual
Variance
```

### Do we have enough resources

```text
Capacity
Allocation
Utilisation
Overload
```

### What is blocking us

```text
Blocked Tasks
Dependencies
Customer Actions
Risks
Issues
```

### Are we ready for the next phase

```text
Phase Gate
Entry Criteria
Exit Criteria
Outstanding Actions
Approval
```

---

# 21. Reporting Refresh

Reports should be refreshable from the underlying data without manually re-entering figures.

Where automated workbook technology is used, reporting should be driven from:

- tables
- structured references
- formulas
- pivots
- queries
- scripts
- controlled data transformations

---

# 22. Reporting Filters

The workbook should support filters for:

```text
Project
Phase
Domain
Capability
Workstream
Role
Resource
Environment
Task Type
Status
Critical Path
Customer Responsibility
```

---

# 23. Drill-Down

Summary reports should allow users to move from:

```text
Project
    ↓
Phase
    ↓
Domain
    ↓
Capability
    ↓
Task
```

This is critical for explaining project estimates and schedule variance.

---

# 24. Reporting Definition of Done

The Reporting Model is complete when:

- executive reporting is defined
- project summary is defined
- task reporting is defined
- effort reporting is defined
- resource reporting is defined
- workstream reporting is defined
- Layer 1 reporting is defined
- Layer 2 reporting is defined
- capability reporting is defined
- critical-path reporting is defined
- customer dependency reporting is defined
- milestone reporting is defined
- phase-gate reporting is defined
- baseline vs actual reporting is defined
- baseline vs forecast reporting is defined
- forecast vs actual reporting is defined
- project health reporting is defined
- reporting filters are defined
- drill-down requirements are defined
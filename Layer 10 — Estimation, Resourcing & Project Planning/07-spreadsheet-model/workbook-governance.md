# Layer 10 — Spreadsheet Model — Workbook Governance

## Purpose

This document defines the governance controls for the Layer 10 project workbook.

The workbook is a controlled project-management artefact and must not become an uncontrolled collection of manually modified estimates and schedules.

---

# 1. Governance Principles

The workbook shall:

1. Preserve source traceability.
2. Protect authoritative framework values.
3. Clearly identify project-specific changes.
4. Maintain version information.
5. Maintain change history.
6. Protect formulas.
7. Control reference values.
8. Separate baseline from actuals.
9. Separate baseline from project overrides.
10. Support auditability.
11. Support controlled recalculation.
12. Support model calibration.

---

# 2. Source-of-Truth Hierarchy

The authoritative hierarchy is:

```text
Layer 1
    ↓
Layer 2
    ↓
Layer 10 Task Catalogue
    ↓
Task Standards
    ↓
Estimation Model
    ↓
Role Catalogue
    ↓
Dependency Model
    ↓
Schedule Model
    ↓
Spreadsheet Model
```

The workbook is the operational representation.

It must not redefine the framework.

---

# 3. Workbook Ownership

The workbook should have clearly assigned owners.

Typical roles:

| Responsibility | Owner |
|---|---|
| Framework owner | Methodology Owner |
| Workbook owner | Project Controls / PMO |
| Estimation owner | Estimation Lead |
| Schedule owner | Project Manager |
| Resource owner | Resource Manager |
| Technical task owner | Solution Architect |
| Customer input owner | Customer Project Manager |

---

# 4. Versioning

The workbook should use:

```text
Framework Version
Workbook Version
Baseline Version
```

Example:

```text
Framework Version: 1.0
Workbook Version: 1.3
Baseline Version: BL-02
```

---

# 5. Baseline Control

The approved project baseline must be preserved.

Baseline values include:

- task population
- baseline effort
- approved project effort
- roles
- dependencies
- planned dates
- milestones
- phase gates
- planned go-live

Baseline changes must be controlled.

---

# 6. Change Categories

Changes should be classified.

```text
FRAMEWORK CHANGE
PROJECT CHANGE
ESTIMATION CHANGE
SCHEDULE CHANGE
RESOURCE CHANGE
TASK CHANGE
CUSTOMER CHANGE
```

---

# 7. Change Control

Material changes should record:

```text
Change ID
Date
Change Type
Affected Task
Affected Field
Original Value
New Value
Reason
Requested By
Approved By
Approval Date
Impact
```

---

# 8. Protected Data

The following should generally be protected:

- Task IDs
- capability IDs
- Layer 1 phase IDs
- baseline effort
- reference values
- formulas
- dependency calculations
- calculated reporting
- critical-path calculations

---

# 9. Editable Data

Project teams may edit approved project fields such as:

- resource assignment
- project adjustment factors
- planned dates
- actual effort
- task status
- customer owner
- forecast
- risks
- issues
- notes

Where appropriate, edits should require controlled input values.

---

# 10. Formula Governance

Formulas should:

- use consistent patterns
- avoid hidden hard-coded values
- use reference tables
- be protected
- be documented where complex
- be tested after structural changes

---

# 11. Data Validation

Controlled fields should use validation.

Examples:

```text
Phase
Domain
Role
Environment
Task Type
Status
Dependency Type
Critical Path
Customer Responsibility
Automation Method
```

---

# 12. Workbook Integrity

The workbook should be checked for:

- duplicate Task IDs
- missing Task IDs
- invalid references
- broken formulas
- invalid dependencies
- circular dependencies
- missing roles
- invalid dates
- negative effort
- missing acceptance criteria
- missing deliverables
- invalid phase mappings

---

# 13. Circular Dependency Control

The workbook must detect circular task dependencies.

Example:

```text
Task A
 ↓
Task B
 ↓
Task C
 ↓
Task A
```

This must be flagged as an error.

---

# 14. Baseline vs Project Values

The workbook should clearly distinguish:

```text
BASELINE
PROJECT
ACTUAL
FORECAST
```

For example:

| Value | Baseline | Project | Actual | Forecast |
|---|---:|---:|---:|---:|
| Effort | 8h | 10h | 7h | 11h |

---

# 15. Workbook Security

Where project information is sensitive, workbook access should be controlled.

Sensitive information may include:

- customer information
- security architecture
- project pricing
- resource rates
- customer contacts
- production information
- migration information
- integration information

---

# 16. Distribution

Controlled workbook copies should be distributed using approved project repositories or collaboration platforms.

The workbook should not be treated as an unmanaged email attachment where version confusion can occur.

---

# 17. Backup

The workbook should be backed up according to the project's document-management requirements.

At minimum, retain:

```text
Current Working Version
Approved Baseline
Previous Approved Baseline
Final Project Version
```

---

# 18. Workbook Freeze

Before major project events, the workbook should be frozen or baselined.

Examples:

```text
Project Baseline
UAT Start
Go-Live Readiness
Go-Live
Project Closure
```

---

# 19. Calibration Capture

At project closure, the workbook should preserve actual delivery data required for calibration.

Required information may include:

- baseline effort
- project-adjusted effort
- actual effort
- baseline duration
- actual duration
- planned resources
- actual resources
- task completion
- schedule variance
- major assumptions
- major deviations

This information feeds:

```text
08 — Calibration
```

---

# 20. Model Change vs Project Change

A critical distinction must be maintained.

### Project Change

Affects one project.

Example:

```text
Customer has unusually complex routing.
```

This should normally result in a project-specific adjustment.

### Model Change

Changes the reusable framework.

Example:

```text
Baseline effort for queue configuration
is consistently underestimated.
```

This should be captured for calibration and potential future model revision.

---

# 21. Workbook Auditability

A reviewer should be able to determine:

```text
Where did this task come from?
        ↓
Layer 2 Capability

Why is this task required?
        ↓
Implementation Activity

Where did the effort come from?
        ↓
Estimation Model

Why is this role assigned?
        ↓
Role Catalogue

Why is this task scheduled here?
        ↓
Dependency + Schedule Model

Why has the estimate changed?
        ↓
Project Adjustment / Change Log
```

---

# 22. Workbook QA

Before a workbook is issued as a baseline, validate:

### Structure

- required sheets exist
- required columns exist
- reference data is loaded

### Task Data

- no duplicate Task IDs
- no missing required fields
- Layer 1 mapping valid
- Layer 2 mapping valid

### Estimation

- baseline effort populated
- project factors valid
- project effort calculated
- cost calculated where applicable

### Dependencies

- predecessors valid
- dependency types valid
- no circular dependencies

### Schedule

- dates valid
- duration valid
- milestones valid
- critical path valid

### Reporting

- totals reconcile
- dashboard values reconcile
- baseline and forecast values reconcile

---

# 23. Reconciliation

The workbook should support reconciliation between:

```text
Task Catalogue
        ↕
Estimation
        ↕
Schedule
        ↕
Actuals
        ↕
Reporting
```

For example:

```text
Total Task Effort
=
Total Estimation Effort
=
Total Schedule Effort
```

unless an explicitly documented reason exists for a difference.

---

# 24. Workbook Release Status

Recommended workbook states:

```text
DRAFT
IN REVIEW
BASELINE
ACTIVE
FROZEN
CLOSED
ARCHIVED
```

---

# 25. Workbook Closure

At project closure:

1. Final actuals are captured.
2. Final forecast is recorded.
3. Final schedule is recorded.
4. Final milestone status is recorded.
5. Final phase-gate status is recorded.
6. Outstanding tasks are resolved or formally transferred.
7. Outstanding risks are transferred.
8. Outstanding customer actions are resolved or transferred.
9. Final baseline variance is calculated.
10. Calibration data is captured.
11. Final workbook version is frozen.
12. Workbook is archived.

---

# 26. Definition of Done

Workbook Governance is complete when:

- ownership is defined
- versioning is defined
- baseline control is defined
- change control is defined
- protected data is defined
- editable data is defined
- formula governance is defined
- validation is defined
- integrity checks are defined
- circular dependency control is defined
- security requirements are defined
- distribution rules are defined
- backup requirements are defined
- workbook freeze points are defined
- calibration capture is defined
- auditability is defined
- QA requirements are defined
- reconciliation requirements are defined
- release states are defined
- closure requirements are defined
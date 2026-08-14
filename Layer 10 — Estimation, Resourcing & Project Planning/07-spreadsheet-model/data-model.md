# Layer 10 — Spreadsheet Model — Data Model

## Purpose

This document defines the logical data model used by the Layer 10 project workbook.

The data model establishes the relationships between:

- project
- phase
- workstream
- domain
- capability
- implementation activity
- task
- role
- resource
- dependency
- schedule
- milestone
- phase gate
- actual
- forecast

---

# 1. Data Model Principle

The workbook must preserve the hierarchy:

```text
Project
    ↓
Layer 1 Phase
    ↓
Workstream
    ↓
Layer 2 Domain
    ↓
Capability
    ↓
Implementation Activity
    ↓
Task
```

Supporting relationships are:

```text
Task
 ├── Role
 ├── Resource
 ├── Dependency
 ├── Estimate
 ├── Schedule
 ├── Actual
 ├── Forecast
 └── Deliverable
```

---

# 2. Project Entity

| Field | Type | Required |
|---|---|---|
| Project ID | Text | YES |
| Customer | Text | YES |
| Project Name | Text | YES |
| Project Manager | Text | YES |
| Start Date | Date | YES |
| Target Go-Live | Date | YES |
| Framework Version | Text | YES |
| Workbook Version | Text | YES |
| Status | Controlled | YES |

---

# 3. Phase Entity

Each task must reference one primary Layer 1 phase.

| Field | Description |
|---|---|
| Phase ID | P01–P12 |
| Phase Name | Authoritative phase name |
| Sequence | Lifecycle sequence |
| Start Date | Planned start |
| Finish Date | Planned finish |
| Status | Phase status |

---

# 4. Domain Entity

Layer 2 domains are represented using the authoritative domain IDs.

Example:

```text
01 — Core Platform
02 — Identity & Access
03 — Voice & Telephony
...
15 — Optimisation, Continuous Improvement & Platform Evolution
```

The workbook must not create alternate domain numbering.

---

# 5. Capability Entity

Capability fields:

| Field | Description |
|---|---|
| Capability ID | Layer 2 capability ID |
| Capability Name | Authoritative name |
| Domain ID | Parent domain |
| Classification | Required / Conditional / Optional / N/A |
| Description | Capability summary |

---

# 6. Implementation Activity Entity

Implementation Activity fields:

| Field | Description |
|---|---|
| Activity ID | Activity identifier |
| Capability ID | Parent capability |
| Activity Name | Activity name |
| Activity Description | Activity definition |
| Layer 1 Phase | Primary phase |
| Classification | Activity classification |

---

# 7. Task Entity

The task is the primary delivery entity.

Minimum task fields:

```text
Task ID
Layer 1 Phase
Layer 2 Domain
Capability ID
Capability
Implementation Activity
Task
Description
Task Type
Primary Role
Supporting Role
Customer Responsibility
Environment
Automation
Baseline Effort
Deliverable
Acceptance Criteria
Critical Path
```

---

# 8. Task ID

Task IDs follow:

```text
L10-DD.CC-TTT
```

Example:

```text
L10-01.01-001
```

Task IDs must remain immutable once published unless the task is formally replaced.

---

# 9. Role Entity

Role information is sourced from:

```text
04-role-catalogue/
```

Minimum fields:

| Field | Description |
|---|---|
| Role ID | Unique role |
| Role Name | Role name |
| Role Category | Delivery category |
| Default Rate | Default cost rate |
| Capacity | Available capacity |
| Notes | Role assumptions |

---

# 10. Resource Entity

Resources represent actual people or project resource allocations.

Fields include:

- Resource ID
- Resource Name
- Role ID
- Capacity
- Availability
- Start Date
- End Date
- Allocation percentage
- Cost Rate

---

# 11. Dependency Entity

Minimum dependency fields:

| Field | Description |
|---|---|
| Dependency ID | Unique identifier |
| Predecessor Task | Predecessor |
| Successor Task | Successor |
| Type | FS / SS / FF / SF |
| Lag | Calendar/workday lag |
| Source | Task / Customer / External / Environment |
| Status | Dependency status |

---

# 12. Estimate Entity

Estimate data must distinguish:

```text
Baseline Estimate
        ↓
Project Adjustment
        ↓
Project Estimate
```

Fields include:

- Task ID
- Baseline Effort
- Complexity Factor
- Volume Factor
- Integration Factor
- Customer Factor
- Reuse Factor
- Risk Factor
- Project Effort
- Confidence
- Notes

---

# 13. Schedule Entity

Schedule fields include:

```text
Task ID
Baseline Start
Baseline Finish
Current Start
Current Finish
Duration
Predecessor
Status
Critical Path
Float
```

---

# 14. Actual Entity

Actual effort must be stored independently.

Fields:

- Task ID
- Resource
- Role
- Date
- Actual Effort
- Completion %
- Status
- Notes

---

# 15. Forecast Entity

Forecast fields:

- Task ID
- Actual Effort
- Remaining Effort
- Estimate at Completion
- Variance
- Forecast Finish
- Forecast Status

---

# 16. Milestone Entity

Milestones must be uniquely identified.

Fields:

```text
Milestone ID
Milestone Name
Phase
Planned Date
Current Date
Status
Owner
Dependencies
Acceptance Criteria
```

---

# 17. Phase Gate Entity

Fields:

```text
Gate ID
Phase
Gate Name
Entry Criteria
Exit Criteria
Evidence
Approver
Approval Status
Approval Date
Outstanding Actions
```

---

# 18. Customer Action Entity

Customer actions are modelled as first-class schedule items where they affect project delivery.

Fields:

- Action ID
- Task ID
- Customer Owner
- Action
- Due Date
- Status
- Dependency
- Impact
- Escalation

---

# 19. Data Relationships

The core relationships are:

```text
Project
    │
    ├── Phase
    │
    ├── Workstream
    │
    └── Task
          │
          ├── Domain
          ├── Capability
          ├── Activity
          ├── Role
          ├── Resource
          ├── Estimate
          ├── Dependency
          ├── Schedule
          ├── Actual
          └── Forecast
```

---

# 20. Authoritative vs Calculated Data

The workbook must distinguish between source and calculated values.

### Authoritative

Examples:

- Task ID
- Capability ID
- Capability name
- baseline effort
- role catalogue values
- dependency definitions

### Project Input

Examples:

- project adjustment
- resource assignment
- planned date
- customer owner
- project status

### Calculated

Examples:

- project effort
- duration
- utilisation
- variance
- forecast
- schedule health

Calculated values must not be manually overwritten.

---

# 21. Data Validation

The workbook should validate:

- Task IDs
- Capability IDs
- Domain IDs
- Phase IDs
- Role IDs
- Task Types
- Environment values
- Automation values
- Status values
- Dependency types
- dates
- effort values
- percentages

Invalid values should be rejected or clearly flagged.

---

# 22. Traceability

Every task must be traceable:

```text
Task ID
   ↓
Capability
   ↓
Layer 2 Domain
   ↓
Layer 1 Phase
```

The workbook should also allow reverse reporting:

```text
Layer 1 Phase
    ↓
Domain
    ↓
Capability
    ↓
Task
```

---

# 23. Definition of Done

The data model is complete when:

- all major entities are defined
- task relationships are defined
- authoritative fields are identified
- calculated fields are identified
- project inputs are identified
- reference values are controlled
- task traceability is maintained
- dependency relationships are represented
- schedule relationships are represented
- actuals are separated from baseline
- forecasts are separated from actuals
- validation rules are defined
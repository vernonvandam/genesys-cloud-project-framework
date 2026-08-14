# Layer 10 — Spreadsheet Model — Workbook Structure

## Purpose

This document defines the standard workbook structure for the Genesys Cloud Project Framework.

The workbook is the operational representation of the Layer 10 models.

It must provide a clear separation between:

- reference data
- task catalogue data
- estimation data
- project planning data
- schedule data
- actuals
- reporting
- governance

---

# 1. Workbook Architecture

The standard workbook should use the following logical sheet structure.

```text
01 — README
02 — Project Setup
03 — Reference Data
04 — Task Catalogue
05 — Estimation
06 — Resource Plan
07 — Dependencies
08 — Schedule
09 — Milestones
10 — Phase Gates
11 — Actuals
12 — Forecast
13 — Risks & Issues
14 — Customer Actions
15 — Reporting
16 — Dashboard
17 — Change Log
```

The exact workbook implementation may use fewer physical sheets where appropriate, but the logical data domains must remain represented.

---

# 2. Sheet Catalogue

| Sheet | Purpose | Primary Source |
|---|---|---|
| `01-README` | Workbook instructions and metadata | Framework |
| `02-Project-Setup` | Project-specific settings | Project |
| `03-Reference-Data` | Controlled values and lookup data | Framework |
| `04-Task-Catalogue` | Authoritative project task set | Task Catalogue |
| `05-Estimation` | Baseline and adjusted estimates | Estimation Model |
| `06-Resource-Plan` | Resource allocation and capacity | Role Catalogue |
| `07-Dependencies` | Task relationships | Dependency Model |
| `08-Schedule` | Planned task dates and sequence | Schedule Model |
| `09-Milestones` | Project milestones | Schedule Model |
| `10-Phase-Gates` | Phase entry and exit controls | Schedule Model |
| `11-Actuals` | Actual effort and progress | Project |
| `12-Forecast` | Forecast-to-complete and variance | Calculated |
| `13-Risks-Issues` | Delivery risks and issues | Project |
| `14-Customer-Actions` | Customer-owned activities | Task Catalogue |
| `15-Reporting` | Operational reports | Calculated |
| `16-Dashboard` | Management summary | Calculated |
| `17-Change-Log` | Workbook and baseline changes | Governance |

---

# 3. README Sheet

The README sheet should contain:

- workbook name
- project name
- customer
- framework version
- workbook version
- generated date
- project start date
- planned go-live
- model owner
- workbook owner
- workbook status
- instructions
- key assumptions
- revision history

Example:

```text
Genesys Cloud Project Estimation & Delivery Workbook

Customer:
Project:
Framework Version:
Workbook Version:
Prepared By:
Prepared Date:
Planned Go-Live:
Status:
```

---

# 4. Project Setup

The Project Setup sheet contains project-specific configuration.

Required values include:

| Field | Description |
|---|---|
| Project ID | Unique project identifier |
| Customer | Customer name |
| Project Name | Project name |
| Project Manager | Project owner |
| Solution Architect | Architecture owner |
| Start Date | Project start |
| Target Go-Live | Planned go-live |
| Working Calendar | Working-day calendar |
| Default Currency | Project currency |
| Default Time Zone | Project time zone |
| Estimation Version | Estimation model version |
| Framework Version | Framework version |
| Workbook Version | Workbook version |
| Schedule Status | Current schedule status |

---

# 5. Reference Data

Reference Data contains controlled values.

Examples:

```text
Layer 1 Phases
Layer 2 Domains
Task Types
Roles
Workstreams
Environments
Automation Methods
Statuses
Risk Categories
Issue Categories
Milestone Types
Phase Gate Types
Critical Path Values
Customer Responsibility Values
```

Reference data should be protected from casual editing.

---

# 6. Task Catalogue Sheet

The Task Catalogue sheet contains the project task population.

Minimum columns:

| Field | Requirement |
|---|---|
| Task ID | REQUIRED |
| Layer 1 Phase | REQUIRED |
| Layer 2 Domain | REQUIRED |
| Capability ID | REQUIRED |
| Capability | REQUIRED |
| Implementation Activity | REQUIRED |
| Task | REQUIRED |
| Description | REQUIRED |
| Task Type | REQUIRED |
| Primary Role | REQUIRED |
| Customer Responsibility | REQUIRED |
| Environment | REQUIRED |
| Automation | REQUIRED |
| Baseline Effort | REQUIRED |
| Deliverable | REQUIRED |
| Acceptance Criteria | REQUIRED |
| Critical Path | REQUIRED |

The Task Catalogue is the authoritative task definition.

---

# 7. Estimation Sheet

The Estimation sheet adds project-specific estimation values.

It should distinguish:

```text
Baseline
    ↓
Project Adjustment
    ↓
Project Estimate
```

Minimum fields:

| Field | Description |
|---|---|
| Task ID | Task reference |
| Baseline Effort | Framework baseline |
| Complexity Factor | Project adjustment |
| Volume Factor | Project adjustment |
| Integration Factor | Project adjustment |
| Customer Factor | Project adjustment |
| Reuse Factor | Project adjustment |
| Risk Factor | Project adjustment |
| Project Effort | Adjusted effort |
| Effort Confidence | Confidence level |
| Estimation Notes | Assumptions |

---

# 8. Resource Plan

The Resource Plan should identify:

- role
- resource
- capacity
- allocation
- planned effort
- available effort
- utilisation
- start date
- end date
- workstream

Example:

```text
Role
    ↓
Resource
    ↓
Available Capacity
    ↓
Assigned Tasks
    ↓
Planned Effort
    ↓
Utilisation
```

---

# 9. Dependencies

The Dependencies sheet should represent:

- predecessor
- successor
- dependency type
- dependency source
- lag
- lead
- dependency owner
- dependency status

Standard dependency types:

```text
FS — Finish to Start
SS — Start to Start
FF — Finish to Finish
SF — Start to Finish
```

External dependencies should be separately identified.

---

# 10. Schedule

The Schedule sheet should contain:

- Task ID
- task name
- phase
- role
- predecessor
- planned start
- planned finish
- duration
- baseline dates
- current dates
- status
- critical path
- float

The schedule must remain traceable to the Project Schedule Model.

---

# 11. Milestones

Milestones should include:

| Field | Requirement |
|---|---|
| Milestone ID | REQUIRED |
| Milestone Name | REQUIRED |
| Phase | REQUIRED |
| Planned Date | REQUIRED |
| Current Date | REQUIRED |
| Status | REQUIRED |
| Owner | REQUIRED |
| Entry Criteria | REQUIRED |
| Exit Criteria | REQUIRED |
| Dependency | REQUIRED where applicable |

---

# 12. Phase Gates

Phase gates should represent controlled lifecycle transitions.

Example:

```text
P01
   ↓
Gate 01
   ↓
P02
   ↓
Gate 02
   ↓
P03
```

A phase gate should contain:

- gate ID
- phase
- gate name
- entry criteria
- exit criteria
- evidence required
- approver
- approval status
- approval date
- outstanding actions

---

# 13. Actuals

Actuals should capture:

- task ID
- resource
- role
- date
- actual effort
- actual status
- completion percentage
- notes

Actuals must never overwrite baseline effort.

---

# 14. Forecast

Forecast should calculate:

```text
Actual Effort
+
Remaining Forecast Effort
=
Estimate at Completion
```

The forecast should support:

- task-level forecast
- role-level forecast
- workstream forecast
- phase forecast
- project forecast

---

# 15. Risks and Issues

The workbook may include delivery risks and issues where they affect:

- task completion
- effort
- schedule
- resources
- dependencies
- milestones
- go-live

---

# 16. Customer Actions

Customer actions should include:

- action ID
- task ID
- customer owner
- action
- due date
- dependency
- status
- impact
- escalation status

Customer-owned work must remain visible in the project schedule.

---

# 17. Reporting

Reporting should support:

- project effort
- project duration
- phase effort
- domain effort
- workstream effort
- role effort
- customer effort
- task status
- schedule status
- critical path
- milestone status
- phase gate status
- actual vs baseline
- forecast vs baseline

---

# 18. Dashboard

The dashboard should provide an executive summary.

Recommended metrics:

```text
Total Tasks
Completed Tasks
Tasks In Progress
Blocked Tasks
Critical Tasks
Total Baseline Effort
Current Forecast Effort
Actual Effort
Remaining Effort
Schedule Variance
Milestones At Risk
Phase Gates At Risk
Customer Actions Outstanding
```

---

# 19. Change Log

Every material workbook change should be traceable.

Minimum fields:

| Field | Description |
|---|---|
| Change ID | Unique identifier |
| Date | Change date |
| Sheet | Affected sheet |
| Field | Affected field |
| Original Value | Previous value |
| New Value | New value |
| Reason | Change rationale |
| Requested By | Requestor |
| Approved By | Approver |

---

# 20. Workbook Navigation

The workbook should allow users to navigate from:

```text
Dashboard
    ↓
Reporting
    ↓
Project Schedule
    ↓
Task
    ↓
Capability
    ↓
Layer 2
```

Where feasible, hyperlinks or structured references should provide direct navigation.

---

# 21. Definition of Done

The workbook structure is complete when:

- all required logical data domains are represented
- task catalogue data is represented
- estimation data is represented
- resource data is represented
- dependencies are represented
- schedule data is represented
- milestones are represented
- phase gates are represented
- actuals are represented
- forecast is represented
- customer actions are represented
- reporting is represented
- dashboard requirements are defined
- governance controls are represented
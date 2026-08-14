# Layer 10 — 07 Spreadsheet Model

## Purpose

The Spreadsheet Model defines the standard workbook structure used by the Genesys Cloud Project Framework to convert the Layer 10 task catalogue, task standards, estimation model, role catalogue, dependency model, and project schedule model into an operational project estimation and delivery workbook.

The Spreadsheet Model is the **presentation and operationalisation layer** of Layer 10.

It does not redefine:

- capabilities
- implementation activities
- tasks
- task standards
- effort assumptions
- roles
- dependencies
- scheduling rules

Instead, it consumes those authoritative models and represents them in a structured workbook suitable for:

- project estimation
- resource planning
- project scheduling
- effort tracking
- project controls
- customer planning
- delivery management
- status reporting
- financial estimation
- milestone management
- dependency management
- critical-path management
- project governance
- project closure
- model calibration

---

# Repository Structure

```text
07-spreadsheet-model/
│
├── README.md
├── workbook-structure.md
├── data-model.md
├── calculation-model.md
├── reporting-model.md
└── workbook-governance.md
```

---

# Document Catalogue

| File | Purpose |
|---|---|
| `README.md` | Spreadsheet Model methodology and governance |
| `workbook-structure.md` | Defines workbook sheets, hierarchy and workbook organisation |
| `data-model.md` | Defines the spreadsheet data model and field structure |
| `calculation-model.md` | Defines estimation, duration, scheduling and resource calculations |
| `reporting-model.md` | Defines project reporting, dashboards and management views |
| `workbook-governance.md` | Defines workbook ownership, versioning, controls and change management |

---

# Position Within Layer 10

The Spreadsheet Model is the seventh component of Layer 10.

```text
01 — Task Catalogue
        ↓
02 — Task Standards
        ↓
03 — Estimation Model
        ↓
04 — Role Catalogue
        ↓
05 — Dependency Model
        ↓
06 — Project Schedule Model
        ↓
07 — Spreadsheet Model
        ↓
08 — Calibration
```

The relationship is:

```text
Task Catalogue
What work exists?
        ↓
Task Standards
How must work be represented?
        ↓
Estimation Model
How much effort is required?
        ↓
Role Catalogue
Who performs the work?
        ↓
Dependency Model
What must happen before what?
        ↓
Project Schedule Model
When should work happen?
        ↓
Spreadsheet Model
How is all of this represented operationally?
        ↓
Calibration
How accurate was the model?
```

---

# 1. Spreadsheet Model Objectives

The workbook must provide a consistent mechanism to:

1. Import the authoritative task catalogue.
2. Preserve task traceability.
3. Apply baseline effort.
4. apply project-specific estimation adjustments.
5. assign delivery roles.
6. identify customer responsibilities.
7. represent dependencies.
8. calculate task duration.
9. calculate schedule dates.
10. identify critical-path tasks.
11. represent milestones.
12. represent phase gates.
13. calculate workstream totals.
14. calculate phase totals.
15. calculate domain totals.
16. calculate role loading.
17. calculate customer effort.
18. calculate delivery effort.
19. calculate total project effort.
20. provide project reporting.
21. support project-specific overrides.
22. preserve baseline model values.
23. support project status tracking.
24. support actual effort tracking.
25. support forecast-to-complete.
26. support project closure.
27. provide data suitable for model calibration.

---

# 2. Source Models

The workbook must consume the following authoritative sources.

| Source | Workbook Usage |
|---|---|
| Layer 1 | Deployment phase |
| Layer 2 | Domain, capability and implementation activity |
| Layer 10 Task Catalogue | Task definitions |
| Task Standards | Required task attributes |
| Estimation Model | Baseline effort and adjustment rules |
| Role Catalogue | Roles, rates and capacity |
| Dependency Model | Task relationships and critical path |
| Project Schedule Model | Dates, sequencing and milestones |

The workbook must not become a competing source of truth.

---

# 3. Workbook Design Principles

The workbook shall:

1. Preserve authoritative Task IDs.
2. Preserve Layer 1 mapping.
3. Preserve Layer 2 mapping.
4. Preserve capability traceability.
5. Preserve implementation activity traceability.
6. Preserve baseline effort.
7. Separate baseline values from project overrides.
8. Separate effort from duration.
9. Separate planned from actual values.
10. Separate delivery effort from customer effort.
11. Separate calculated fields from editable fields.
12. Use controlled values wherever possible.
13. Minimise manual duplication.
14. Prefer formulas over repeated manual calculations.
15. Protect authoritative reference data.
16. Clearly identify user-editable fields.
17. Support filtering and reporting.
18. Support project-specific tailoring.
19. Preserve an audit trail for material changes.
20. Support eventual automation.

---

# 4. Workbook Layering

The workbook should conceptually contain four layers.

```text
REFERENCE
    ↓
TASK / ESTIMATION DATA
    ↓
PROJECT PLANNING DATA
    ↓
REPORTING / DASHBOARDS
```

### Reference

Contains:

- Layer 1 phases
- Layer 2 domains
- roles
- environments
- task types
- workstreams
- statuses
- configuration values

### Task / Estimation Data

Contains:

- task catalogue
- baseline effort
- estimation factors
- baseline role
- baseline dependencies

### Project Planning Data

Contains:

- project-specific adjustments
- assigned resources
- planned dates
- customer responsibilities
- actual effort
- status
- risks
- issues
- approvals

### Reporting

Contains:

- effort summaries
- resource summaries
- schedule summaries
- phase summaries
- domain summaries
- critical path
- project health
- management dashboards

---

# 5. Workbook Outputs

The workbook should support:

- detailed estimation
- detailed project schedule
- resource plan
- project timeline
- workstream plan
- customer responsibility plan
- milestone plan
- phase-gate plan
- critical-path view
- effort summary
- role-loading summary
- cost summary
- status reporting
- project forecast
- actual-vs-baseline reporting
- project closure reporting
- calibration data

---

# 6. Definition of Done

The Spreadsheet Model is complete when:

- workbook architecture is defined
- workbook sheets are defined
- task data model is defined
- reference data model is defined
- estimation calculations are defined
- resource calculations are defined
- schedule calculations are defined
- reporting views are defined
- governance controls are defined
- baseline values are protected
- project overrides are supported
- actuals are supported
- forecast calculations are supported
- the workbook can be generated from Layer 10 source data
- the workbook can support project delivery
- the workbook can provide data for model calibration
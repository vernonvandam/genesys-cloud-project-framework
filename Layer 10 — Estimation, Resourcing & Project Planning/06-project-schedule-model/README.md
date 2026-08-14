# Layer 10 — 06 Project Schedule Model

## Purpose

This directory defines the standard project schedule model used by the Genesys Cloud Project Framework to convert the Layer 10 task catalogue, task standards, estimation model, role catalogue, and dependency model into a structured implementation schedule.

The Project Schedule Model defines how implementation tasks are:

- sequenced
- scheduled
- assigned start and finish dates
- organised into phases and workstreams
- grouped into milestones
- controlled through phase gates
- aligned to dependencies
- aligned to resource availability
- assessed for critical-path impact
- prepared for project workbook generation
- maintained through project delivery

The schedule model is intended to support both:

- baseline project planning
- project-specific detailed scheduling

The schedule is not the source of truth for task definitions, effort estimates, roles, or dependency definitions. It consumes those models and applies scheduling logic to them.

---

# Repository Structure

```text
06-project-schedule-model/
│
├── README.md
├── schedule-structure.md
├── sequencing-model.md
├── milestone-model.md
└── phase-gate-model.md
```

---

# Document Catalogue

| File | Purpose |
|---|---|
| `README.md` | Project Schedule Model methodology and governance |
| `schedule-structure.md` | Defines the structure and hierarchy of the project schedule |
| `sequencing-model.md` | Defines task sequencing and scheduling logic |
| `milestone-model.md` | Defines project milestone structure and milestone controls |
| `phase-gate-model.md` | Defines phase gates, entry criteria, exit criteria, and approval controls |

---

# Position Within Layer 10

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

The models have distinct responsibilities.

```text
Task Catalogue
What work exists?
        ↓
Task Standards
How must each task be represented?
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
When should the work happen?
        ↓
Spreadsheet Model
How is the project represented operationally?
        ↓
Calibration
How accurate was the model?
```

---

# 1. Scope

The Project Schedule Model applies to all implementation tasks within:

```text
Layer 10 — Estimation, Resourcing & Project Planning/
└── 01-task-catalogue/
```

The model covers:

- task sequencing
- task scheduling
- task start dates
- task finish dates
- task duration
- phase alignment
- workstream alignment
- milestone planning
- phase gates
- dependency-driven scheduling
- resource-aware scheduling
- customer activity scheduling
- environment scheduling
- testing windows
- migration windows
- deployment windows
- production change windows
- hypercare periods
- operational handover
- critical-path management
- schedule baseline
- schedule changes
- schedule status
- schedule reporting

---

# 2. Schedule Principles

The project schedule shall follow these principles:

1. Every scheduled activity must trace to an authoritative task.
2. Task IDs must remain consistent with the Layer 10 Task Catalogue.
3. Task effort and duration must remain separate.
4. Dependencies must drive sequencing where dependencies exist.
5. Parallel execution should be preserved where technically and operationally possible.
6. Resource constraints must be explicitly identified.
7. Customer activities must be represented where they affect delivery.
8. Third-party dependencies must be represented where they affect delivery.
9. Environment availability must be reflected in scheduling.
10. Testing and validation activities must be scheduled explicitly.
11. Migration and cutover activities must be scheduled explicitly.
12. Production change windows must be represented.
13. Milestones must represent measurable project outcomes.
14. Phase gates must represent controlled transition points.
15. Critical-path tasks must remain visible.
16. Schedule assumptions must be documented.
17. Schedule changes must be traceable.
18. The schedule must remain compatible with the estimation model.
19. The schedule must remain compatible with the dependency model.
20. The schedule must be suitable for conversion into the Layer 10 Spreadsheet Model.

---

# 3. Schedule Hierarchy

The project schedule should use the following hierarchy:

```text
Programme / Project
        ↓
Layer 1 Phase
        ↓
Workstream
        ↓
Layer 2 Domain
        ↓
Capability
        ↓
Implementation Task
        ↓
Task Activity
```

Where appropriate, milestones and phase gates are represented alongside the task hierarchy.

```text
Project
│
├── Phase
│   ├── Workstream
│   │   ├── Capability
│   │   │   ├── Task
│   │   │   └── Task
│   │   └── Capability
│   └── Milestone
│
├── Phase Gate
│
└── Next Phase
```

The task remains the fundamental scheduling unit.

---

# 4. Layer 1 Alignment

The schedule must remain aligned with the Layer 1 deployment lifecycle.

The exact Layer 1 phase names and IDs defined by the master Layer 1 methodology are authoritative.

At schedule level:

```text
Layer 1 Phase
      ↓
Layer 2 Capability Domain
      ↓
Layer 10 Task
      ↓
Schedule Position
```

A task must have one primary Layer 1 phase.

Where a task contributes to multiple lifecycle phases, its primary phase must reflect where its principal implementation outcome occurs.

---

# 5. Layer 2 Alignment

Every implementation task must retain its Layer 2 traceability.

```text
Layer 2 Domain
        ↓
Layer 2 Capability
        ↓
Layer 10 Task
        ↓
Schedule Activity
```

This allows the schedule to be reported by:

- Layer 1 phase
- Layer 2 domain
- Layer 2 capability
- task
- workstream
- role
- environment

---

# 6. Task Schedule Record

Every scheduled task should be capable of representing at least the following attributes:

| Attribute | Requirement |
|---|---|
| Task ID | REQUIRED |
| Task Name | REQUIRED |
| Layer 1 Phase | REQUIRED |
| Layer 2 Domain | REQUIRED |
| Layer 2 Capability | REQUIRED |
| Workstream | REQUIRED |
| Task Type | REQUIRED |
| Primary Role | REQUIRED |
| Customer Responsibility | REQUIRED |
| Environment | REQUIRED |
| Automation | REQUIRED where applicable |
| Baseline Effort | REQUIRED |
| Project Effort | REQUIRED when estimated |
| Duration | REQUIRED |
| Predecessor | REQUIRED where applicable |
| Successor | DERIVED / OPTIONAL |
| Start Date | REQUIRED when scheduled |
| Finish Date | REQUIRED when scheduled |
| Milestone | OPTIONAL |
| Phase Gate | OPTIONAL |
| Critical Path | REQUIRED |
| Schedule Status | REQUIRED |
| Deliverable | REQUIRED |
| Acceptance Criteria | REQUIRED |
| Assumptions | REQUIRED where applicable |

---

# 7. Schedule Status

Tasks should use standard schedule statuses.

Recommended statuses are:

```text
NOT STARTED
READY
IN PROGRESS
BLOCKED
ON HOLD
COMPLETE
CANCELLED
DEFERRED
```

Status definitions:

| Status | Meaning |
|---|---|
| NOT STARTED | Task exists but execution has not commenced |
| READY | Task prerequisites are satisfied and the task can begin |
| IN PROGRESS | Task is actively being performed |
| BLOCKED | Task cannot continue because of an unresolved dependency or issue |
| ON HOLD | Task has intentionally been paused |
| COMPLETE | Acceptance criteria have been satisfied |
| CANCELLED | Task will no longer be performed |
| DEFERRED | Task has been moved to a later schedule position |

---

# 8. Schedule Baseline

The project schedule should have an approved baseline.

The baseline should capture:

- task sequence
- task dependencies
- planned start dates
- planned finish dates
- planned duration
- planned milestones
- phase gates
- resource assumptions
- key customer activities
- major delivery windows
- planned go-live
- planned hypercare
- planned operational handover

Once approved, changes to the baseline should be controlled.

---

# 9. Schedule vs Estimate

The schedule must not alter the baseline estimation model.

The relationship is:

```text
Baseline Effort
        ↓
Project Adjusted Effort
        ↓
Available Resource Capacity
        ↓
Task Duration
        ↓
Dependencies
        ↓
Task Start / Finish
        ↓
Project Schedule
```

Example:

```text
Baseline Effort = 8 hours
Project Effort = 10 hours
Resource Availability = 50%
Duration = 2 working days
```

Effort represents work.

Duration represents elapsed time.

Schedule position represents when the work occurs.

These values must remain distinct.

---

# 10. Schedule Drivers

Schedule position may be affected by:

- task dependencies
- resource availability
- customer availability
- customer approvals
- environment availability
- third-party delivery
- architecture decisions
- design approvals
- data availability
- test environment readiness
- UAT availability
- production change windows
- migration windows
- maintenance windows
- business blackout periods
- regulatory constraints
- operational constraints
- cutover sequencing
- rollback requirements
- phase gates

---

# 11. Parallel Execution

The framework should favour parallel execution where dependencies do not prevent it.

Example:

```text
Architecture
      ↓
┌───────────────┬───────────────┬───────────────┐
│ Voice Design  │ Digital Design│ Data Design   │
└───────────────┴───────────────┴───────────────┘
      ↓
Integration Validation
```

Tasks should not be artificially sequenced merely because they belong to the same phase.

Parallel execution should only be restricted where:

- a technical dependency exists
- a customer dependency exists
- a resource constraint exists
- an environment constraint exists
- a business constraint exists
- a governance control requires sequencing

---

# 12. Resource-Aware Scheduling

The schedule must consider resource availability.

Resource constraints may include:

- specialist availability
- customer SME availability
- shared engineering resources
- testing resources
- migration specialists
- voice engineers
- integration engineers
- security specialists
- WFM specialists
- reporting specialists
- deployment resources

The schedule must distinguish between:

```text
Task Dependency
```

and:

```text
Resource Constraint
```

A resource constraint must not be incorrectly represented as a technical dependency.

---

# 13. Customer Activities

Customer activities must be scheduled where they can affect delivery.

Examples include:

- requirements workshops
- architecture decisions
- approvals
- data provision
- access provisioning
- test preparation
- UAT execution
- business validation
- cutover approval
- operational readiness
- production approval
- go-live approval
- handover acceptance

Customer activities should have:

- an owner
- a planned date
- a dependency relationship where applicable
- an expected outcome

---

# 14. Environment Scheduling

Environment-dependent activities must be scheduled against the appropriate environment.

Standard environments include:

```text
DESIGN
DEV
TEST
UAT
PROD
MULTI
```

Examples:

```text
DEV
Configuration build

TEST
System testing

UAT
Business acceptance

PROD
Production deployment
```

Environment readiness must be treated as a schedule dependency where applicable.

---

# 15. Testing and Validation Scheduling

Testing must be represented as explicit schedule activities.

The schedule should distinguish:

- test preparation
- test execution
- defect resolution
- regression testing
- customer validation
- UAT
- production validation
- post-deployment validation

Testing must not be assumed to occur automatically as part of build tasks unless the task definition explicitly states that testing is included.

---

# 16. Migration and Cutover Scheduling

Migration activities must be explicitly scheduled where applicable.

Typical sequence:

```text
Migration Preparation
        ↓
Migration Tooling
        ↓
Mock Migration
        ↓
Migration Rehearsal
        ↓
Cutover Preparation
        ↓
Data Freeze
        ↓
Final Migration
        ↓
Validation
        ↓
Reconciliation
        ↓
Business Acceptance
        ↓
Go-Live
        ↓
Hypercare
```

The schedule must explicitly identify:

- migration windows
- freeze periods
- cutover windows
- rollback windows
- validation windows
- reconciliation periods
- business acceptance windows

---

# 17. Production Deployment Scheduling

Production deployment must be treated as a controlled schedule event.

The schedule should represent:

```text
Production Readiness
        ↓
Deployment Approval
        ↓
Production Change Window
        ↓
Deployment
        ↓
Technical Validation
        ↓
Business Validation
        ↓
Go-Live
        ↓
Hypercare
```

Production activities should identify:

- change owner
- implementation window
- rollback window
- validation window
- customer availability
- support availability

---

# 18. Critical Path

Critical-path classification is inherited from the Dependency Model and Task Standards.

The schedule should be able to calculate or represent:

- earliest start
- earliest finish
- latest start
- latest finish
- total float
- free float
- critical tasks
- near-critical tasks
- critical path
- critical milestones

The schedule must not independently redefine critical-path rules.

The authoritative dependency and critical-path methodology remains in:

```text
05-dependency-model/
```

---

# 19. Schedule Health

The schedule should support assessment of:

- tasks overdue
- tasks due soon
- blocked tasks
- critical tasks at risk
- milestone variance
- phase-gate readiness
- dependency delays
- resource overload
- customer delays
- environment delays
- testing delays
- migration delays
- go-live risk

Recommended schedule health categories:

```text
ON TRACK
AT RISK
DELAYED
BLOCKED
COMPLETE
```

---

# 20. Schedule Change Control

Schedule changes should be controlled where they affect:

- baseline dates
- critical path
- major milestones
- phase gates
- go-live
- migration
- production deployment
- resource loading
- customer commitments

Changes should record:

- original value
- revised value
- change reason
- requested by
- approved by
- approval date
- downstream impact

---

# 21. Schedule Assumptions

Schedule assumptions should be recorded separately from task definitions.

Examples:

- customer SMEs are available as planned
- environments are available as scheduled
- required access is provided on time
- source data is available
- third parties meet committed dates
- production change windows are available
- UAT participants are available
- approvals occur within agreed SLA
- migration volumes remain within agreed assumptions

Assumptions should be reviewed throughout delivery.

---

# 22. Schedule Outputs

The Project Schedule Model should support generation of:

- detailed project schedule
- high-level project plan
- implementation timeline
- workstream schedule
- milestone plan
- phase-gate plan
- resource-loading view
- critical-path view
- customer activity schedule
- environment schedule
- testing schedule
- migration schedule
- cutover schedule
- hypercare schedule
- operational handover schedule

---

# 23. Downstream Relationship

The Project Schedule Model feeds:

```text
06 — Project Schedule Model
        ↓
07 — Spreadsheet Model
        ↓
Project Workbook
        ↓
Project Reporting
        ↓
Project Controls
```

The schedule model should therefore be structured so that it can be represented in spreadsheet rows without requiring manual reinterpretation.

---

# 24. Definition of Done

The Project Schedule Model is complete when:

- schedule hierarchy is defined
- task scheduling rules are defined
- Layer 1 alignment is defined
- Layer 2 alignment is defined
- task schedule attributes are defined
- sequencing rules are defined
- dependency-driven scheduling is defined
- parallel execution rules are defined
- resource-aware scheduling is defined
- customer activities are represented
- environment scheduling is defined
- testing scheduling is defined
- migration scheduling is defined
- production deployment scheduling is defined
- milestone structure is defined
- phase gates are defined
- critical-path integration is defined
- schedule baseline rules are defined
- schedule change control is defined
- schedule status is defined
- schedule outputs can feed the Spreadsheet Model

---

# Schedule Model Traceability

```text
Layer 1
Deployment Lifecycle
        ↓
Layer 2
Capability Catalogue
        ↓
Layer 10 / 01
Task Catalogue
        ↓
Layer 10 / 02
Task Standards
        ↓
Layer 10 / 03
Estimation Model
        ↓
Layer 10 / 04
Role Catalogue
        ↓
Layer 10 / 05
Dependency Model
        ↓
Layer 10 / 06
Project Schedule Model
        ↓
Layer 10 / 07
Spreadsheet Model
        ↓
Layer 10 / 08
Calibration
```

The Project Schedule Model is therefore the point at which the framework transitions from defining and estimating work to determining the temporal delivery plan.

---

# Phase Completion

The Project Schedule Model is considered complete when the schedule structure, sequencing model, milestone model, and phase-gate model can collectively transform the Layer 10 task catalogue into a controlled, dependency-aware, resource-aware implementation schedule.
# 01 — Task Catalogue

## Layer 10 — Estimation, Resourcing & Project Planning

The **Task Catalogue** is the authoritative Layer 10 repository of individual implementation tasks required to deliver a Genesys Cloud deployment.

It translates the **Layer 2 capability and implementation activity catalogue** into discrete, executable, estimable, assignable, and schedulable implementation tasks.

The Task Catalogue is the bridge between the Genesys Cloud deployment methodology and the eventual project delivery schedule and estimation model.

---

# 1. Purpose

The purpose of the Task Catalogue is to define **what work must actually be performed** to implement the Genesys Cloud solution.

Layer 2 answers:

> **What Genesys Cloud capabilities are being implemented?**

The Task Catalogue answers:

> **What individual activities must the project team perform to implement each capability?**

Layer 10 then extends those tasks into:

- sequencing
- dependencies
- roles
- customer responsibilities
- environments
- effort
- duration
- deliverables
- acceptance criteria
- critical-path analysis
- project scheduling
- resource planning
- estimation

The resulting catalogue is intended to become the authoritative source for generating a reusable Genesys Cloud project schedule and effort-estimation model.

---

# 2. Position Within the Framework

The Task Catalogue is part of **Layer 10 — Estimation, Resourcing & Project Planning**.

The overall framework relationship is:

```text
Layer 1
Deployment Lifecycle
        │
        │  When does the work happen?
        ▼
Layer 2
Genesys Cloud Capability Framework
        │
        │  What are we deploying?
        ▼
Layers 3–9
Architecture, Engineering, Integration,
Testing, Security, Automation & Operations
        │
        │  How is it designed, engineered,
        │  controlled, tested and operated?
        ▼
Layer 10
Estimation, Resourcing & Project Planning
        │
        ▼
01 — Task Catalogue
        │
        ├── Capability
        │      │
        │      └── Implementation Activities
        │              │
        │              └── Individual Tasks
        │
        ├── Role Catalogue
        ├── Effort Model
        ├── Dependency Model
        ├── Schedule Model
        └── Spreadsheet Model
                │
                ▼
        Customer Project Schedule
```

---

# 3. Relationship to Layer 2

The Task Catalogue must **not redefine or replace the Layer 2 capability catalogue**.

Layer 2 remains the authoritative source for:

- capability domains
- capabilities
- capability descriptions
- capability objectives
- implementation activities
- Layer 1 mappings
- capability dependencies
- capability-level assumptions

Layer 10 takes those implementation activities and decomposes them into individual tasks.

The relationship is therefore:

```text
Layer 2
Capability
    │
    └── Implementation Activity
              │
              ▼
Layer 10
Individual Implementation Tasks
```

For example:

```text
Layer 2
2.01.01 — Genesys Cloud Organisation
        │
        ├── Organisation Requirements
        │       │
        │       ├── L10-01.01-001
        │       ├── L10-01.01-002
        │       └── L10-01.01-003
        │
        ├── Organisation Design
        │       │
        │       ├── L10-01.01-004
        │       ├── L10-01.01-005
        │       └── ...
        │
        └── Organisation Validation
                │
                ├── L10-01.01-...
                └── L10-01.01-...
```

The Layer 2 capability remains the parent.

---

# 4. Repository Structure

The Task Catalogue is organised by **Layer 2 capability domain**.

```text
01-task-catalogue/
│
├── README.md
│
├── 01-core-platform/
│   ├── README.md
│   ├── 01-genesys-cloud-organisation.md
│   ├── 02-region-data-residency.md
│   ├── 03-organisation-settings.md
│   ├── 04-divisions.md
│   ├── 05-business-units.md
│   ├── 06-locations.md
│   ├── 07-sites.md
│   ├── 08-time-zones.md
│   ├── 09-business-hours.md
│   ├── 10-holidays.md
│   ├── 11-languages.md
│   ├── 12-media-types.md
│   ├── 13-platform-defaults.md
│   ├── 14-licensing-feature-entitlement.md
│   ├── 15-storage-retention.md
│   ├── 16-platform-limits-capacity.md
│   ├── 17-environment-strategy.md
│   └── 18-core-platform-validation.md
│
├── 02-identity-access/
│   └── ...
│
├── 03-voice-telephony/
│   └── ...
│
├── 04-acd-routing/
│   └── ...
│
├── 05-architect/
│   └── ...
│
├── 06-digital/
│   └── ...
│
├── 07-wfm-employee-engagement/
│   └── ...
│
├── 08-data-integrations-apis/
│   └── ...
│
├── 09-analytics-reporting/
│   └── ...
│
├── 10-quality-recording-evaluation/
│   └── ...
│
├── 11-security-compliance-governance/
│   └── ...
│
├── 12-testing-validation-deployment/
│   └── ...
│
├── 13-migration-data-conversion-transition/
│   └── ...
│
├── 14-operations-support-service-management/
│   └── ...
│
└── 15-optimisation-continuous-improvement/
    └── ...
```

---

# 5. File Organisation Principle

Tasks are **not** stored as individual Markdown files.

Each Layer 2 capability receives one Task Catalogue Markdown document.

For example:

```text
01-core-platform/
└── 01-genesys-cloud-organisation.md
```

That file contains:

```text
Capability
    │
    ├── Capability reference
    ├── Capability summary
    ├── Layer 1 mapping
    │
    ├── Implementation Activity 01
    │       ├── Task 001
    │       ├── Task 002
    │       └── Task 003
    │
    ├── Implementation Activity 02
    │       ├── Task 004
    │       ├── Task 005
    │       └── Task 006
    │
    └── Implementation Activity 03
            ├── Task 007
            └── Task 008
```

This approach keeps the repository manageable while retaining sufficient structure for automated extraction into the project planning model.

---

# 6. Task Catalogue Hierarchy

Every task must maintain traceability through the following hierarchy:

```text
Layer 10
    │
    └── Domain
          │
          └── Capability
                │
                └── Implementation Activity
                      │
                      └── Implementation Task
```

For example:

```text
Layer 10
└── Domain 01 — Core Platform
      │
      └── Capability 2.01.01
            Genesys Cloud Organisation
              │
              └── Activity 01.03
                    Organisation Provisioning
                      │
                      ├── L10-01.01-019
                      ├── L10-01.01-020
                      ├── L10-01.01-021
                      └── ...
```

---

# 7. Task ID Standard

Task IDs must provide stable traceability back to the Layer 2 capability.

The standard format is:

```text
L10-DD.CC-TTT
```

Where:

| Component | Meaning |
|---|---|
| `L10` | Layer 10 |
| `DD` | Layer 2 capability domain |
| `CC` | Capability within the domain |
| `TTT` | Sequential task number |

Example:

```text
L10-01.01-001
```

means:

```text
Layer 10
Domain 01 — Core Platform
Capability 01 — Genesys Cloud Organisation
Task 001
```

Another example:

```text
L10-03.07-014
```

means:

```text
Layer 10
Domain 03 — Voice & Telephony
Capability 07
Task 014
```

The Layer 1 phase is **not encoded into the Task ID**.

Layer 1 phase must remain a separate task attribute.

This is intentional because a single capability may contain tasks executed across multiple Layer 1 phases.

---

# 8. Task Granularity

A task must be sufficiently granular to be:

- assigned to an individual or defined role
- estimated independently
- scheduled independently
- given explicit dependencies
- tracked independently
- validated independently
- associated with a deliverable
- associated with acceptance criteria
- identified as customer or delivery responsibility
- identified as critical-path or non-critical-path

A task should generally represent a discrete unit of work.

### Good task

```text
Configure the Genesys Cloud organisation default time zone.
```

### Poor task

```text
Configure the platform.
```

The second example contains too many distinct activities to be independently estimated or tracked.

---

# 9. Task Decomposition Rules

When converting an implementation activity into tasks:

1. Preserve the parent Layer 2 capability.
2. Preserve the originating implementation activity.
3. Identify the applicable Layer 1 phase.
4. Break work into discrete activities.
5. Separate requirements from design.
6. Separate design from configuration.
7. Separate configuration from validation.
8. Separate validation from customer acceptance.
9. Separate defect resolution from baseline implementation.
10. Identify customer-owned activities.
11. Identify delivery-team activities.
12. Identify dependencies.
13. Identify environment.
14. Identify deliverables.
15. Identify acceptance criteria.
16. Identify effort.
17. Identify duration.
18. Identify critical-path status.
19. Identify automation opportunities.
20. Avoid combining unrelated work merely to reduce task count.

---

# 10. Standard Task Record

Every task must eventually support the following attributes.

| Attribute | Description |
|---|---|
| Task ID | Unique Layer 10 identifier |
| Layer | Framework layer |
| Layer 1 Phase | Deployment phase |
| Layer 2 Domain | Capability domain |
| Capability ID | Layer 2 capability identifier |
| Capability | Capability name |
| Workstream | Delivery workstream |
| Parent Activity | Layer 2 implementation activity |
| Task | Short task name |
| Description | Detailed task description |
| Task Type | Required, conditional, optional, customer, etc. |
| Dependencies | Predecessor tasks or decisions |
| Primary Role | Accountable delivery role |
| Supporting Role | Additional supporting role |
| Customer Responsibility | Customer-owned requirement |
| Environment | Environment where work occurs |
| Automation Method | Manual, API, Terraform, etc. |
| Effort | Estimated work effort |
| Duration | Expected elapsed duration |
| Deliverable | Result produced |
| Acceptance Criteria | Conditions for completion |
| Critical Path | Critical-path indicator |
| Notes | Additional assumptions or considerations |

---

# 11. Task Type

Tasks must use controlled classifications.

| Task Type | Definition |
|---|---|
| REQUIRED | Required for the standard deployment |
| CONDITIONAL | Required when project-specific conditions apply |
| OPTIONAL | Performed only when explicitly scoped |
| CUSTOMER | Primarily owned by the customer |
| DELIVERY | Primarily owned by the delivery team |
| JOINT | Requires customer and delivery-team collaboration |
| AUTOMATION | Primarily executed through automation |
| VALIDATION | Configuration or implementation validation |
| ACCEPTANCE | Customer or stakeholder acceptance |
| REMEDIATION | Correction of a discovered defect |
| HANDOVER | Transfer to BAU/support |

A task may have more than one applicable characteristic, but the catalogue must maintain a consistent primary classification.

---

# 12. Layer 1 Mapping

Every implementation task must map to a Layer 1 deployment phase.

Examples:

```text
P01 — Project Initiation & Mobilisation
P02 — Discovery & Current-State Assessment
P03 — Requirements & Solution Definition
P04 — Solution Architecture & Detailed Design
P05 — Platform Foundation & Environment Build
P06 — Configuration & Development
P07 — Integration & Data Enablement
P08 — Testing, Validation & Defect Resolution
P09 — Operational Readiness & Training
P10 — Go-Live Preparation & Cutover
P11 — Go-Live & Hypercare
P12 — BAU Handover & Project Closure
```

A single capability may therefore produce tasks across multiple phases.

Example:

```text
Capability
Genesys Cloud Organisation

        ├── P02
        │    Requirements
        │
        ├── P04
        │    Architecture & Design
        │
        ├── P05
        │    Platform Foundation
        │
        ├── P08
        │    Validation
        │
        └── P12
             BAU Handover
```

---

# 13. Dependency Model

Dependencies must be explicit.

A task dependency may be:

### Task-to-task

```text
L10-01.01-001
        ↓
L10-01.01-002
```

### Capability-to-capability

```text
Organisation
        ↓
Identity & Access
```

### Phase-to-phase

```text
P04
Architecture
        ↓
P05
Platform Build
```

### External/customer dependency

```text
Customer provides approved
holiday calendar
        ↓
Configure holiday schedules
```

Dependencies must not be hidden in task descriptions.

---

# 14. Customer Responsibilities

Customer-owned work must be explicitly identified.

Examples include:

- providing requirements
- providing source data
- providing business rules
- providing approval
- providing regulatory requirements
- providing security standards
- providing user information
- providing telephone numbers
- providing holiday calendars
- providing integration specifications
- providing acceptance
- providing operational ownership
- approving configuration

Customer responsibilities must be represented as tasks where they have a material impact on project sequencing or effort.

---

# 15. Environment

Each task should identify its execution environment.

Standard values should include:

| Environment | Description |
|---|---|
| DESIGN | Architecture/design activity |
| DEV | Development environment |
| TEST | Test environment |
| UAT | User acceptance environment |
| PROD | Production environment |
| MULTI | Multiple environments |
| EXTERNAL | External/customer system |
| N/A | No technical environment applicable |

Where the Genesys Cloud deployment model uses multiple organisations rather than conventional environments, the task must document the relevant organisation/environment relationship.

---

# 16. Automation Method

The catalogue must identify opportunities to automate repeatable implementation tasks.

Standard values include:

| Method | Description |
|---|---|
| MANUAL | Genesys Cloud Admin UI or manual process |
| API | Genesys Cloud API |
| SDK | Genesys Cloud SDK |
| TERRAFORM | Terraform provider/module |
| SCRIPT | Custom automation script |
| IMPORT | Bulk import or structured data import |
| PIPELINE | CI/CD or deployment pipeline |
| HYBRID | Combination of methods |
| N/A | Not applicable |

Automation should be considered during task definition rather than after the catalogue is complete.

---

# 17. Effort and Duration

Effort and duration are separate attributes.

### Effort

The amount of active work required.

Example:

```text
Effort = 2.0 hours
```

### Duration

The elapsed calendar/project time required.

Example:

```text
Duration = 1 business day
```

A task may therefore have:

```text
Effort: 2 hours
Duration: 1 day
```

because the task may require waiting for customer input or approval.

The estimation model in:

```text
../03-estimation-model/
```

will define how baseline effort is calculated and adjusted.

---

# 18. Deliverables

Tasks should identify tangible outputs where applicable.

Examples:

- architecture decision
- configuration record
- configured Genesys Cloud object
- Terraform module
- test evidence
- migration result
- approval record
- configuration export
- operational procedure
- training material
- handover record
- acceptance record

A task does not necessarily require a formal document, but it must have a clear observable outcome.

---

# 19. Acceptance Criteria

Every task should have measurable completion criteria.

### Poor

```text
Configuration completed.
```

### Better

```text
The approved Genesys Cloud organisation settings have been
configured and validated against the signed-off design.
```

Acceptance criteria should be objective wherever practical.

---

# 20. Critical Path

Every task should be assessed for critical-path relevance.

Standard values:

```text
YES
NO
CONDITIONAL
```

Critical-path status may change for a specific customer project even if the baseline task is normally non-critical.

The catalogue should therefore define the **baseline critical-path expectation**, while the instantiated project schedule determines the actual critical path.

---

# 21. Capability File Standard

Each capability Task Catalogue file must follow this structure:

```text
# Layer 10 — [Capability Name]

## Capability Reference

## Capability Objective

## Layer 1 Mapping

## Source Implementation Activities

## Implementation Tasks

### [Activity]

#### [Task ID] — [Task Name]

| Attribute | Value |
|---|---|

### Description

### Dependencies

### Deliverable

### Acceptance Criteria

### Notes

## Capability-Level Dependencies

## Capability-Level Assumptions

## Capability-Level Estimation Considerations

## Definition of Done
```

This structure must remain consistent across all 15 capability domains.

---

# 22. Domain README Standard

Each domain directory should contain a `README.md`.

For example:

```text
01-core-platform/
├── README.md
├── 01-genesys-cloud-organisation.md
├── 02-region-data-residency.md
└── ...
```

The domain README should provide:

- domain purpose
- capability list
- capability-to-task mapping
- domain-level dependencies
- domain-level assumptions
- Layer 1 phase relationships
- task-count summary
- estimation considerations
- domain definition of done

The domain README must not duplicate the detailed task records.

---

# 23. Cross-Domain Tasks

Some implementation tasks span multiple capability domains.

Examples include:

- solution architecture
- security architecture
- integration architecture
- environment provisioning
- migration planning
- end-to-end testing
- go-live preparation
- operational handover

Where possible, tasks should have a single authoritative location.

Cross-domain relationships should be represented through:

- dependencies
- references
- workstream
- Layer 1 phase
- capability references

Duplicate tasks must be avoided.

---

# 24. Task Reuse

The Task Catalogue is intended to be a reusable enterprise deployment baseline.

Tasks should therefore be written generically enough to apply across multiple customer implementations.

Avoid customer-specific wording such as:

```text
Configure ABC Bank's queue.
```

Prefer:

```text
Configure the approved customer queue.
```

Customer-specific information belongs in the instantiated project schedule.

---

# 25. Conditional Tasks

Conditional tasks must remain in the master catalogue where the capability may reasonably be required on a project.

For example:

```text
Configure emergency services
```

may be:

```text
Task Type: CONDITIONAL
```

rather than omitted entirely.

The project estimator can subsequently mark the task:

```text
Applicable: YES
```

or:

```text
Applicable: NO
```

This ensures that the master catalogue remains comprehensive.

---

# 26. Project Instantiation

The Task Catalogue is **not itself the customer project schedule**.

Instead:

```text
Master Task Catalogue
        ↓
Select applicable capabilities
        ↓
Select applicable tasks
        ↓
Apply project-specific volumes
        ↓
Apply complexity
        ↓
Apply customer responsibilities
        ↓
Apply dependencies
        ↓
Calculate effort
        ↓
Calculate duration
        ↓
Assign resources
        ↓
Create project schedule
```

The resulting project schedule should be generated from the master catalogue rather than manually rebuilt for every Genesys Cloud project.

---

# 27. Relationship to the Estimation Model

The Task Catalogue defines:

> **What work exists?**

The Estimation Model defines:

> **How much work should it take?**

The relationship is:

```text
Task
  │
  ├── Base Effort
  │
  ├── Complexity
  │
  ├── Volume
  │
  ├── Integration Factors
  │
  ├── Customer Factors
  │
  └── Automation Factors
          │
          ▼
     Estimated Effort
```

The Task Catalogue must therefore avoid embedding project-specific estimates unless the estimate represents a clearly defined baseline.

---

# 28. Relationship to the Role Catalogue

Each task must map to a standard delivery role.

Examples:

- Project Manager
- Program Manager
- Business Analyst
- Solution Architect
- Technical Architect
- Genesys Cloud Architect
- Genesys Cloud Engineer
- Integration Engineer
- Terraform / DevOps Engineer
- Data Engineer
- Security Architect
- Test Lead
- Test Analyst
- Training Lead
- Change Manager
- Service Management Lead
- Customer Platform Owner

The definitive role catalogue is maintained separately under:

```text
../04-role-catalogue/
```

---

# 29. Relationship to the Dependency Model

The Task Catalogue defines the tasks.

The Dependency Model defines how those tasks relate.

```text
Task Catalogue
        │
        ▼
Task IDs
        │
        ▼
Dependency Model
        │
        ├── Predecessors
        ├── Successors
        ├── Capability dependencies
        ├── Phase dependencies
        └── Critical path
```

Dependencies should therefore use stable Task IDs wherever possible.

---

# 30. Relationship to the Schedule Model

The Schedule Model converts the task catalogue into a delivery sequence.

```text
Task Catalogue
        ↓
Dependencies
        ↓
Roles
        ↓
Effort
        ↓
Duration
        ↓
Calendar
        ↓
Schedule
```

The Task Catalogue should not contain customer-specific start and finish dates.

Those belong to the project schedule.

---

# 31. Relationship to the Spreadsheet Model

The eventual spreadsheet/workbook will be generated from the structured task catalogue.

A target task register should contain at least:

| Column |
|---|
| Task ID |
| Layer |
| Layer 1 Phase |
| Layer 2 Domain |
| Capability ID |
| Capability |
| Workstream |
| Parent Activity |
| Task |
| Description |
| Task Type |
| Dependency |
| Primary Role |
| Supporting Role |
| Customer Responsibility |
| Environment |
| Automation Method |
| Effort |
| Duration |
| Deliverable |
| Acceptance Criteria |
| Critical Path |
| Applicable |
| Complexity |
| Volume Driver |
| Project Notes |
| Status |

The Markdown catalogue therefore needs to remain sufficiently structured for future automated extraction.

---

# 32. Quality Standards

Every task catalogue must satisfy the following standards.

## Traceability

Every task must trace to:

```text
Layer 10
    ↓
Layer 2 Domain
    ↓
Layer 2 Capability
    ↓
Implementation Activity
    ↓
Task
```

## Completeness

The catalogue must include all reasonable implementation work.

Do not omit activities merely because they are:

- conditional
- customer-owned
- operational
- testing-related
- documentation-related
- security-related
- integration-dependent
- automation-dependent

## Consistency

All capability documents must use the same structure and terminology.

## Estimability

Tasks must be sufficiently granular to estimate independently.

## Assignability

Tasks must identify an appropriate role.

## Scheduleability

Tasks must support sequencing and dependencies.

## Testability

Tasks must have objective completion criteria.

---

# 33. Task Catalogue Completion Criteria

The Task Catalogue is considered complete when:

- all 15 Layer 2 capability domains have been represented
- every Layer 2 capability has a corresponding Task Catalogue file
- every Layer 2 implementation activity has been reviewed
- implementation activities have been decomposed into individual tasks
- task IDs are unique
- task IDs maintain Layer 2 traceability
- every task has a Layer 1 phase mapping
- task types are defined
- customer responsibilities are identified
- roles are assigned
- environments are identified
- dependencies are defined
- deliverables are defined
- acceptance criteria are defined
- critical-path expectations are identified
- automation opportunities are identified
- conditional activities remain represented
- cross-domain dependencies are identified
- the catalogue can be converted into a structured spreadsheet
- the catalogue can support project-specific estimation
- the catalogue can support project schedule generation

---

# 34. Task Catalogue Gate

The Task Catalogue should progress through the following maturity sequence:

```text
Layer 2 Capability Catalogue
        ↓
Implementation Activities
        ↓
Task Decomposition
        ↓
Task Attribute Completion
        ↓
Dependency Mapping
        ↓
Role Mapping
        ↓
Effort Baseline
        ↓
Complexity / Volume Model
        ↓
Schedule Model
        ↓
Spreadsheet Extraction
        ↓
Project Template
```

A capability is ready for estimation when:

```text
Capability identified
        ↓
Implementation activities defined
        ↓
Tasks decomposed
        ↓
Tasks uniquely identified
        ↓
Layer 1 mappings confirmed
        ↓
Dependencies identified
        ↓
Roles identified
        ↓
Customer responsibilities identified
        ↓
Deliverables defined
        ↓
Acceptance criteria defined
        ↓
Baseline effort established
        ↓
READY FOR PROJECT ESTIMATION
```

---

# 35. Current Domain Status

| Domain | Status |
|---|---|
| 01 — Core Platform | In Development |
| 02 — Identity & Access | Planned |
| 03 — Voice & Telephony | Planned |
| 04 — ACD & Routing | Planned |
| 05 — Architect | Planned |
| 06 — Digital | Planned |
| 07 — Workforce Management & Employee Engagement | Planned |
| 08 — Data, Integrations & APIs | Planned |
| 09 — Analytics, Reporting & Data Visualisation | Planned |
| 10 — Quality Management, Recording & Evaluation | Planned |
| 11 — Security, Compliance & Governance | Planned |
| 12 — Testing, Validation & Deployment | Planned |
| 13 — Migration, Data Conversion & Transition | Planned |
| 14 — Operations, Support & Service Management | Planned |
| 15 — Optimisation, Continuous Improvement & Platform Evolution | Planned |

---

# 36. Design Principle

The Task Catalogue must remain a **master enterprise implementation baseline**, not a customer-specific project plan.

The guiding principle is:

> **Define the complete set of work once, then tailor it for each customer project.**

The framework should therefore enable:

```text
One Master Catalogue
        │
        ├── Project A
        ├── Project B
        ├── Project C
        ├── Project D
        └── Project N
```

without requiring the delivery team to rebuild the task structure for every project.

---

# 37. Next Step

The next step is to create the domain-level README:

```text
01-task-catalogue/
└── 01-core-platform/
    └── README.md
```

That README will define the **Core Platform Task Catalogue**, including:

- all 18 capabilities
- task catalogue structure
- capability-to-task mapping
- Layer 1 relationships
- domain dependencies
- domain-level estimation considerations
- task-count tracking
- completion status

The individual capability files will then contain the detailed implementation tasks.

---

# 38. End State

When complete, Layer 10 will provide a complete chain from capability through to project execution:

```text
Genesys Cloud Capability
        │
        ▼
Implementation Activity
        │
        ▼
Implementation Task
        │
        ├── Layer 1 Phase
        ├── Role
        ├── Customer Responsibility
        ├── Environment
        ├── Dependency
        ├── Effort
        ├── Duration
        ├── Deliverable
        └── Acceptance Criteria
                │
                ▼
        Project Schedule
                │
                ▼
        Resource Plan
                │
                ▼
        Effort Estimate
                │
                ▼
        Customer Delivery
```

This Task Catalogue is therefore the **execution-level foundation of the Genesys Cloud Project Framework** and the primary source from which the future project scheduling and estimation workbook will be generated.
# Layer 10 — 02 Task Standards

## Purpose

This directory defines the standards used to create, classify, estimate, schedule, sequence, assign, and validate implementation tasks within the Genesys Cloud Project Framework.

The standards provide the rules that govern the Layer 10 Task Catalogue and ensure that individual implementation tasks can be consistently converted into:

- project schedule activities
- effort estimates
- resource requirements
- dependency relationships
- customer responsibility assignments
- environment plans
- delivery workstreams
- project controls
- spreadsheet records
- implementation reporting

The standards apply across all 15 Layer 2 capability domains.

---

# 1. Position Within the Methodology

Layer 10 converts the Genesys Cloud capability framework into a project-planning and estimation model.

The relationship is:

```text
Layer 1
Deployment Lifecycle
        ↓
Layer 2
Genesys Cloud Capability Catalogue
        ↓
Layer 3–9
Supporting Delivery Frameworks
        ↓
Layer 10
Estimation, Resourcing & Project Planning
        ↓
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

The Layer 10/01 Task Catalogue defines **what work needs to be performed**.

The Layer 10/02 Task Standards define **how that work must be represented and controlled**.

---

# 2. Scope

The Task Standards apply to every implementation task contained within:

```text
Layer 10 — Estimation, Resourcing & Project Planning/
└── 01-task-catalogue/
```

The standards apply across:

1. Core Platform
2. Identity & Access
3. Voice & Telephony
4. ACD & Routing
5. Architect
6. Digital
7. WFM & Employee Engagement
8. Data, Integrations & APIs
9. Analytics & Reporting
10. Quality Management, Recording & Evaluation
11. Security, Compliance & Governance
12. Testing, Validation & Deployment
13. Migration, Data Conversion & Transition
14. Operations, Support & Service Management
15. Optimisation, Continuous Improvement & Platform Evolution

---

# 3. Task Standard Objectives

Every task should be:

- uniquely identifiable
- traceable to a Layer 2 capability
- mapped to the Layer 1 deployment lifecycle
- sufficiently granular for project scheduling
- sufficiently measurable for effort estimation
- assigned to an appropriate delivery role
- clear about customer responsibility
- associated with the appropriate environment
- classified by task type
- assigned dependencies where applicable
- assigned acceptance criteria
- assessed for critical-path impact
- suitable for inclusion in a project estimation workbook

---

# 4. Task Standards Catalogue

The following standards define the complete Layer 10 task representation.

| Standard | File | Purpose |
|---|---|---|
| Task Definition | `task-definition.md` | Defines what constitutes a valid implementation task |
| Task ID | `task-id-standard.md` | Defines the unique task identification convention |
| Task Types | `task-types.md` | Defines task classifications |
| Task Granularity | `task-granularity-standard.md` | Defines the required level of task decomposition |
| Acceptance Criteria | `acceptance-criteria-standard.md` | Defines task completion and acceptance requirements |
| Critical Path | `critical-path-standard.md` | Defines critical-path classification |
| Customer Responsibility | `customer-responsibility-standard.md` | Defines customer delivery obligations |
| Dependency | `dependency-standard.md` | Defines task dependency relationships |
| Duration | `duration-standard.md` | Defines task duration conventions |
| Effort Estimation | `effort-estimation-standard.md` | Defines baseline effort estimation |
| Environment | `environment-standard.md` | Defines environment classification |
| Role | `role-standard.md` | Defines primary delivery role assignment |

---

# 5. Relationship to the Task Catalogue

The standards do not replace the Layer 10/01 Task Catalogue.

They govern it.

The relationship is:

```text
Layer 2 Capability
        ↓
Layer 10 Capability Task Catalogue
        ↓
Task Standard
        ↓
Individual Implementation Task
        ↓
Effort
        ↓
Role
        ↓
Dependencies
        ↓
Schedule
        ↓
Project Workbook
```

For example:

```text
Layer 2 Capability
        │
        ▼
Platform Provisioning
        │
        ▼
Layer 10 Task
L10-01.01-001
        │
        ├── Task Type
        ├── Layer 1 Phase
        ├── Primary Role
        ├── Customer Responsibility
        ├── Environment
        ├── Automation
        ├── Effort
        ├── Duration
        ├── Dependencies
        ├── Deliverable
        ├── Acceptance Criteria
        └── Critical Path
```

---

# 6. Mandatory Task Attributes

Every implementation task must contain, either directly or through the applicable task catalogue structure, the following information.

| Attribute | Requirement |
|---|---|
| Task ID | REQUIRED |
| Task Name | REQUIRED |
| Layer 1 Phase | REQUIRED |
| Layer 2 Domain | REQUIRED |
| Layer 2 Capability | REQUIRED |
| Task Type | REQUIRED |
| Description | REQUIRED |
| Dependencies | REQUIRED |
| Primary Role | REQUIRED |
| Customer Responsibility | REQUIRED |
| Environment | REQUIRED |
| Automation | REQUIRED where applicable |
| Baseline Effort | REQUIRED |
| Duration | REQUIRED when scheduled |
| Deliverable | REQUIRED |
| Acceptance Criteria | REQUIRED |
| Critical Path | REQUIRED |

---

# 7. Task Classification

Tasks shall be classified using the approved task types defined in `task-types.md`.

At minimum, the framework supports:

- REQUIRED
- CONDITIONAL
- VALIDATION

Additional task types may only be introduced through an approved update to the Task Type Standard.

Classification must describe the implementation applicability of the task, not its importance.

For example:

```text
REQUIRED
Task applies to the normal enterprise deployment methodology.

CONDITIONAL
Task applies when a defined solution condition exists.

VALIDATION
Task confirms that an implemented capability or control operates as required.
```

---

# 8. Task Granularity

Tasks must be sufficiently atomic that they can be represented as an individual project schedule row.

A task should normally have:

- one clear implementation outcome
- one accountable primary role
- measurable completion criteria
- identifiable dependencies
- an estimable effort
- a defined deliverable or outcome

Tasks must not combine unrelated implementation outcomes simply to reduce the number of task records.

Conversely, tasks should not be decomposed into trivial administrative actions unless those actions materially affect project effort, sequencing, responsibility, risk, or acceptance.

The detailed rules are defined in:

`task-granularity-standard.md`

---

# 9. Task ID Standard

Every task must have a unique identifier.

The Layer 10 task ID convention is:

```text
L10-<DOMAIN>.<CAPABILITY>-<TASK>
```

Example:

```text
L10-01.01-001
L10-01.01-002
L10-01.02-001
```

The task ID must remain stable after creation.

Task IDs must not be reused for different implementation activities.

The detailed convention is defined in:

`task-id-standard.md`

---

# 10. Layer 1 Traceability

Every task must map to an applicable Layer 1 deployment phase.

The Layer 1 mapping provides lifecycle traceability between the implementation task and the overall Genesys Cloud deployment methodology.

Example:

```text
Layer 1
P05 — Establish Foundations
        ↓
Layer 2
Core Platform
        ↓
Layer 10
Platform Provisioning
        ↓
Task
L10-01.01-001
```

A task may have one primary Layer 1 phase.

Where a task legitimately spans multiple phases, the primary phase must represent the phase in which the task's principal implementation outcome occurs.

---

# 11. Layer 2 Traceability

Every task must trace back to:

```text
Layer 2 Domain
        ↓
Layer 2 Capability
        ↓
Layer 10 Capability Catalogue
        ↓
Implementation Task
```

This ensures that the task catalogue remains traceable to the enterprise capability model.

No implementation task should exist without a valid capability relationship unless it is explicitly identified as a cross-cutting project-management or methodology task.

---

# 12. Dependency Standards

Dependencies must identify work that must occur before the task can begin or complete.

Dependencies may include:

- prerequisite tasks
- architecture decisions
- customer decisions
- customer-provided information
- environments
- integrations
- access
- third-party dependencies
- approvals
- data availability
- testing prerequisites
- deployment prerequisites

Dependencies should use task IDs wherever the dependency is another Layer 10 task.

The detailed dependency rules are defined in:

`dependency-standard.md`

---

# 13. Role Assignment

Each task must have a primary accountable delivery role.

Examples include:

- Project Manager
- Solution Architect
- Technical Architect
- Genesys Cloud Architect
- Genesys Cloud Engineer
- Voice Engineer
- Integration Engineer
- Data Engineer
- Security Specialist
- WFM Specialist
- Reporting Specialist
- QA / Test Lead
- Migration Lead
- Service Manager

The primary role identifies who is accountable for execution of the task.

Additional supporting roles may be identified where required.

The detailed role assignment rules are defined in:

`role-standard.md`

---

# 14. Customer Responsibility

Tasks must explicitly identify whether responsibility sits with:

- Delivery Team
- Customer
- Joint

Customer responsibility may include:

- providing information
- approving designs
- providing access
- supplying data
- validating requirements
- performing customer-side configuration
- executing business acceptance
- approving production changes
- providing operational resources

The detailed rules are defined in:

`customer-responsibility-standard.md`

---

# 15. Environment Classification

Tasks must identify the environment in which the implementation activity occurs.

Standard environment classifications include:

- DESIGN
- DEV
- TEST
- UAT
- PROD
- MULTI

Where a task applies across multiple environments, `MULTI` should be used and the specific environments documented within the task description where necessary.

The detailed environment rules are defined in:

`environment-standard.md`

---

# 16. Effort and Duration

Effort and duration are separate concepts.

### Effort

Effort represents the amount of productive work required to complete the task.

Example:

```text
Baseline Effort = 4 hours
```

### Duration

Duration represents the elapsed project time required to complete the task after considering:

- resource availability
- dependencies
- scheduling
- customer availability
- environment availability
- waiting periods
- approvals
- execution windows

Example:

```text
Effort = 4 hours
Duration = 2 working days
```

Effort and duration must therefore never be treated as interchangeable.

The detailed standards are defined in:

- `effort-estimation-standard.md`
- `duration-standard.md`

---

# 17. Acceptance Criteria

Every task must define objective acceptance criteria.

Acceptance criteria should establish how the project team determines that the task is complete.

Good acceptance criteria should be:

- specific
- measurable
- testable
- observable
- relevant to the task outcome

Example:

```text
The Genesys Cloud organisation is provisioned in the approved region,
administrative access has been validated, and the baseline organisation
configuration has been documented.
```

Acceptance criteria must describe the outcome rather than merely restating the task name.

The detailed standard is defined in:

`acceptance-criteria-standard.md`

---

# 18. Critical Path

Each task must be classified as:

- YES
- NO
- CONDITIONAL

Critical-path classification must consider whether delay to the task could delay:

- a major milestone
- a deployment phase
- a dependent workstream
- production cutover
- go-live
- customer acceptance
- operational handover

The detailed rules are defined in:

`critical-path-standard.md`

---

# 19. Automation

Where relevant, tasks should identify the implementation method as:

- MANUAL
- AUTOMATED
- HYBRID

This is particularly important for:

- Terraform
- APIs
- migration tooling
- CI/CD
- configuration export/import
- bulk provisioning
- automated testing
- data transformation
- reporting
- validation

Automation classification does not determine effort by itself.

Automated tasks may still require substantial design, development, testing, troubleshooting, and operational effort.

---

# 20. Standard Task Quality Model

A valid implementation task should answer all of the following questions:

```text
WHAT?
What must be implemented?

WHY?
What capability or project outcome does it support?

WHERE?
Which Layer 1 phase and Layer 2 capability does it belong to?

WHO?
Which delivery role owns the work?

WHO ELSE?
What customer responsibility exists?

WHEN?
What dependencies and sequencing apply?

WHERE EXECUTED?
Which environment is involved?

HOW?
Is the task manual, automated, or hybrid?

HOW MUCH?
What is the baseline effort?

HOW LONG?
What is the expected duration?

WHAT IS PRODUCED?
What deliverable or outcome results?

HOW DO WE KNOW IT IS DONE?
What are the acceptance criteria?

DOES IT AFFECT THE CRITICAL PATH?
Yes, No, or Conditional?
```

A task that cannot answer these questions should be considered incomplete.

---

# 21. Task Standard Hierarchy

Where multiple standards appear to apply, the following hierarchy should be used:

```text
Layer 10 Methodology
        ↓
Task Definition
        ↓
Task Type
        ↓
Task Granularity
        ↓
Task ID
        ↓
Traceability
        ↓
Role / Responsibility
        ↓
Environment
        ↓
Dependencies
        ↓
Effort / Duration
        ↓
Acceptance
        ↓
Critical Path
```

The standards are complementary and must be applied together.

---

# 22. Relationship to Layer 10/03

The Task Standards establish the inputs required by the future Estimation Model.

The relationship is:

```text
02 — Task Standards
        │
        ├── Task Type
        ├── Task Granularity
        ├── Role
        ├── Environment
        ├── Effort
        ├── Duration
        ├── Dependencies
        ├── Customer Responsibility
        └── Critical Path
                │
                ▼
03 — Estimation Model
```

The standards define **how task information is represented**.

The Estimation Model will define **how that information is used to calculate project effort and size**.

---

# 23. Relationship to Layer 10/04

The Role Standard provides the foundation for the Role Catalogue.

```text
Task
  ↓
Primary Role
  ↓
Role Catalogue
  ↓
Resource Type
  ↓
Resource Capacity
  ↓
Project Resourcing
```

The Task Standards therefore establish the role assignment rules without attempting to define the complete resource model.

---

# 24. Relationship to Layer 10/05

The Dependency Standard establishes the rules used by the future Dependency Model.

```text
Task
  ↓
Dependency
  ↓
Dependency Type
  ↓
Dependency Relationship
  ↓
Dependency Network
  ↓
Schedule Logic
```

The Dependency Model will subsequently aggregate these relationships across the complete project.

---

# 25. Relationship to Layer 10/06

The Task Standards provide the inputs needed by the Project Schedule Model.

```text
Task
    ↓
Duration
    ↓
Dependencies
    ↓
Role
    ↓
Environment
    ↓
Customer Responsibility
    ↓
Critical Path
    ↓
Project Schedule
```

The schedule model must consume the standards rather than redefine them.

---

# 26. Relationship to Layer 10/07

The Task Standards are also the data-definition foundation for the project workbook.

A future workbook should be capable of representing at least:

| Field | Source |
|---|---|
| Task ID | Task ID Standard |
| Task | Task Definition |
| Task Type | Task Types |
| Layer 1 Phase | Layer 1 Mapping |
| Layer 2 Domain | Layer 2 Capability |
| Layer 2 Capability | Layer 2 Capability |
| Description | Task Definition |
| Dependencies | Dependency Standard |
| Primary Role | Role Standard |
| Customer Responsibility | Customer Responsibility Standard |
| Environment | Environment Standard |
| Automation | Task Definition |
| Effort | Effort Estimation Standard |
| Duration | Duration Standard |
| Deliverable | Task Definition |
| Acceptance Criteria | Acceptance Criteria Standard |
| Critical Path | Critical Path Standard |

---

# 27. Governance

Changes to the Task Standards should be controlled.

A change to a standard may affect:

- existing task catalogues
- task IDs
- effort estimates
- project schedules
- role assignments
- dependencies
- spreadsheet models
- customer estimates
- historical project comparisons

Therefore, standards should not be changed casually.

Material changes should be reviewed for downstream impact across Layer 10.

---

# 28. Standard Change Principles

When modifying a task standard:

1. Preserve compatibility with existing task catalogues where practical.
2. Avoid changing established Task IDs unnecessarily.
3. Avoid changing terminology without a clear methodology reason.
4. Document material changes.
5. Assess impact on estimation models.
6. Assess impact on project schedule models.
7. Assess impact on spreadsheet models.
8. Assess impact on historical calibration data.
9. Update affected task catalogue content where necessary.
10. Maintain consistency across all 15 capability domains.

---

# 29. Definition of Done

The `02-task-standards` component is complete when:

- `README.md` is complete.
- Task Definition Standard is complete.
- Task ID Standard is complete.
- Task Types Standard is complete.
- Task Granularity Standard is complete.
- Acceptance Criteria Standard is complete.
- Critical Path Standard is complete.
- Customer Responsibility Standard is complete.
- Dependency Standard is complete.
- Duration Standard is complete.
- Effort Estimation Standard is complete.
- Environment Standard is complete.
- Role Standard is complete.
- All standards are internally consistent.
- Standards align with the Layer 10/01 Task Catalogue.
- Standards do not duplicate the responsibilities of Layer 10/03–08.
- Standards support conversion into a project schedule.
- Standards support effort estimation.
- Standards support resource planning.
- Standards support spreadsheet generation.
- Standards are applicable across all 15 Layer 2 capability domains.

---

# 30. Completion Criteria

The ultimate objective of this directory is to ensure that every task in the Layer 10 Task Catalogue can be represented consistently and objectively.

The completed model should support:

```text
Layer 2 Capability
        ↓
Layer 10 Task
        ↓
Standardised Task Definition
        ↓
Effort
        ↓
Resource
        ↓
Dependency
        ↓
Duration
        ↓
Schedule
        ↓
Critical Path
        ↓
Project Estimate
        ↓
Project Workbook
```

The Task Standards therefore form the **contract between the implementation task catalogue and the estimation, resourcing, scheduling, and spreadsheet models that follow**.
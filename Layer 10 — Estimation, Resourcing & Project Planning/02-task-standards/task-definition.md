# Layer 10 — Task Definition Standard

## Purpose

This document defines the standard for what constitutes a valid implementation task within the Genesys Cloud Project Framework.

The task definition standard ensures that every task in the Layer 10 Task Catalogue represents a discrete, measurable, estimable, schedulable, and accountable unit of project delivery work.

---

# 1. Scope

This standard applies to every implementation task within:

```text
Layer 10 — Estimation, Resourcing & Project Planning
└── 01-task-catalogue/
```

It applies across all 15 Layer 2 capability domains.

---

# 2. Definition of an Implementation Task

An implementation task is a discrete unit of work that:

1. contributes to implementing a defined capability
2. has a clear implementation outcome
3. can be assigned to an accountable role
4. can be estimated
5. can be sequenced
6. has identifiable dependencies
7. has defined completion criteria
8. can be represented as an individual project schedule row

A task is not simply a topic, activity category, discussion, or deliverable heading.

---

# 3. Task Outcome Principle

Every task must describe an outcome rather than merely an action.

### Weak

```text
Configure queues
```

### Strong

```text
Configure the approved Genesys Cloud queues and validate queue
membership, routing configuration, naming standards, and associated
operational settings.
```

The task must make it possible to determine whether the intended outcome has been achieved.

---

# 4. Mandatory Task Attributes

Each task must contain or inherit the following attributes:

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

# 5. Task Naming

Task names must:

- begin with an implementation-oriented verb where practical
- describe a specific outcome
- avoid ambiguous language
- avoid unnecessary technical detail
- remain understandable to project stakeholders
- be suitable for use as a project schedule activity

Preferred verbs include:

- Define
- Configure
- Create
- Provision
- Implement
- Integrate
- Develop
- Validate
- Test
- Migrate
- Deploy
- Review
- Approve
- Reconcile
- Document
- Handover
- Decommission

---

# 6. Task Description

The description must explain:

- what is being performed
- what is included
- relevant scope boundaries
- important implementation considerations
- expected outcome

The description should provide enough context that a delivery resource can understand the work without needing to interpret the capability name alone.

---

# 7. Task Deliverable

Each task must identify its tangible output or implementation outcome.

Examples:

- configured queue
- provisioned environment
- approved design
- completed integration
- migrated data set
- tested Architect flow
- validated security control
- deployment package
- operational runbook
- acceptance record

A deliverable may be a configuration state rather than a physical document.

---

# 8. Task Acceptance

Every task must have objective acceptance criteria.

Acceptance criteria must determine when the task is considered complete.

Acceptance criteria must not merely repeat the task description.

---

# 9. Task Dependencies

Dependencies must identify prerequisites that materially affect task execution.

Where another Layer 10 task is the prerequisite, reference its Task ID.

---

# 10. Task Accountability

Every task must have a Primary Role.

The Primary Role is accountable for completion of the task.

Supporting roles may participate but do not replace primary accountability.

---

# 11. Customer Responsibility

Every task must identify whether delivery responsibility is:

- Delivery Team
- Customer
- Joint

Where the customer is responsible for an input, approval, action, or acceptance activity, this must be explicitly identified.

---

# 12. Environment

Every task must identify the applicable environment:

- DESIGN
- DEV
- TEST
- UAT
- PROD
- MULTI

---

# 13. Automation

Tasks should identify whether the implementation method is:

- MANUAL
- AUTOMATED
- HYBRID

Automation classification does not imply that the task is low effort.

---

# 14. Task Completeness Test

A task is complete only when the following can be answered:

```text
What must be done?
Why must it be done?
Which capability does it implement?
Which Layer 1 phase does it belong to?
Who owns the work?
What must the customer provide or perform?
Where is the work performed?
What does it depend on?
How much effort is required?
How long will it take?
What is produced?
How is completion verified?
Does it affect the critical path?
```

---

# 15. Task Quality Rule

A task must be revised if:

- its outcome is ambiguous
- it contains multiple unrelated outcomes
- it cannot be estimated
- it cannot be scheduled
- it has no accountable role
- it has no acceptance criteria
- it duplicates another task
- it is too broad to represent a meaningful schedule activity
- it is so small that it creates unnecessary schedule administration

---

# 16. Relationship to Other Standards

This document defines the overall task structure.

Detailed rules are defined by:

- `task-id-standard.md`
- `task-types.md`
- `task-granularity-standard.md`
- `acceptance-criteria-standard.md`
- `critical-path-standard.md`
- `customer-responsibility-standard.md`
- `dependency-standard.md`
- `duration-standard.md`
- `effort-estimation-standard.md`
- `environment-standard.md`
- `role-standard.md`

---

# 17. Definition of Done

A task definition is compliant when:

- the task has a unique Task ID
- the task has a clear name
- the task has a defined outcome
- Layer 1 mapping exists
- Layer 2 mapping exists
- task type is defined
- dependencies are identified
- primary role is assigned
- customer responsibility is defined
- environment is defined
- effort is estimable
- duration is schedulable
- deliverable is defined
- acceptance criteria are defined
- critical-path status is defined
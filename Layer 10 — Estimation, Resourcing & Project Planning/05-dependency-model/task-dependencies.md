# Layer 10 — Task Dependencies

## Purpose

This document defines the standard model for establishing dependencies between individual Layer 10 implementation tasks.

Task dependencies are the primary scheduling relationships used by the Project Schedule Model.

---

# 1. Dependency Principle

Every dependency must answer:

> What must happen before this task can begin or complete?

Dependencies must be based on actual delivery prerequisites rather than assumed sequencing.

---

# 2. Dependency Record

Each dependency should contain:

| Attribute | Description |
|---|---|
| Dependency ID | Unique dependency identifier |
| Predecessor Task | Task that provides the prerequisite |
| Successor Task | Task that consumes the prerequisite |
| Relationship | FS / SS / FF / SF |
| Dependency Type | Technical / Customer / Approval / etc. |
| Strength | HARD / SOFT / CONDITIONAL |
| Condition | Condition for activation |
| Owner | Role or party controlling dependency |
| Customer Dependency | YES / NO |
| External Dependency | YES / NO |
| Critical Path | YES / NO / CONDITIONAL |
| Rationale | Reason for dependency |

---

# 3. Default Relationship

The default relationship is:

```text
FINISH-TO-START
```

Example:

```text
L10-01.01-001
Establish Organisation Structure
        ↓
L10-01.02-001
Configure Divisions
```

---

# 4. Finish-to-Start

The successor cannot start until the predecessor finishes.

```text
A ────────→ B
```

This is the most common relationship.

---

# 5. Start-to-Start

The successor may start once the predecessor starts.

```text
A ────────→
            B ────────→
```

Use only when there is a legitimate overlap.

Example:

```text
Configuration Build
        ↓
Begin Configuration Documentation
```

---

# 6. Finish-to-Finish

The successor cannot finish until the predecessor finishes.

This may apply to activities such as:

- documentation
- test evidence
- deployment preparation
- operational readiness

---

# 7. Start-to-Finish

Start-to-Finish relationships should be rare.

They should only be used where the successor's completion is explicitly dependent on the predecessor starting.

---

# 8. Hard Dependencies

A hard dependency means the successor cannot proceed without the predecessor.

Examples:

```text
Create Queue
        ↓
Assign User to Queue
```

```text
Configure Integration
        ↓
Execute Integration Test
```

---

# 9. Soft Dependencies

A soft dependency indicates preferred sequencing but does not necessarily prevent work from proceeding.

Example:

```text
Configuration Documentation
        ↓
Operational Handover
```

Documentation may be developed incrementally rather than blocking the entire handover.

---

# 10. Conditional Dependencies

Conditional dependencies are activated only when the applicable solution condition exists.

Examples:

- digital channel enabled
- CRM integration required
- migration required
- PCI compliance required
- WFM included
- custom API required

---

# 11. Customer Dependencies

Customer dependencies must be explicitly represented.

Examples:

```text
Customer Provides Test Users
        ↓
Execute UAT
```

```text
Customer Approves Architecture
        ↓
Implement Architecture
```

---

# 12. External Dependencies

External dependencies may include:

- carrier provisioning
- third-party API availability
- CRM vendor configuration
- identity provider configuration
- network changes
- certificates
- DNS
- external security approval

---

# 13. Environment Dependencies

Example:

```text
Deploy Configuration to TEST
        ↓
Execute System Testing
```

or:

```text
UAT Environment Available
        ↓
Execute UAT
```

---

# 14. Approval Dependencies

Approvals should be represented as explicit dependencies where they materially affect schedule execution.

Examples:

```text
Architecture Approval
        ↓
Build
```

```text
UAT Sign-Off
        ↓
Production Deployment
```

---

# 15. Data Dependencies

Data dependencies may include:

- source extracts
- test data
- customer records
- migration mappings
- reporting data
- historical data

Example:

```text
Provide Test Data
        ↓
Execute Integration Test
```

---

# 16. Testing Dependencies

Testing tasks should depend on the actual readiness of the capability being tested.

Example:

```text
Configure Queue
        ↓
Validate Queue
        ↓
Execute Routing Test
```

Testing must not be made dependent on unrelated configuration.

---

# 17. Migration Dependencies

Migration tasks should reflect:

```text
Data Discovery
        ↓
Data Mapping
        ↓
Data Transformation
        ↓
Mock Migration
        ↓
Migration Rehearsal
        ↓
Production Migration
        ↓
Reconciliation
```

---

# 18. Deployment Dependencies

Production deployment commonly requires:

```text
Build Complete
       ↓
Testing Complete
       ↓
UAT Complete
       ↓
Defects Resolved
       ↓
Production Readiness
       ↓
Go-Live Approval
       ↓
Production Deployment
```

---

# 19. Task Dependency Example

```text
Task:
L10-04.01-001

Configure Queue

        ↓

Task:
L10-04.02-001

Configure Queue Membership

        ↓

Task:
L10-04.03-001

Validate Queue Routing

        ↓

Task:
L10-12.01-001

Execute Routing Test
```

---

# 20. Multiple Predecessors

A task may have multiple prerequisites.

Example:

```text
Queue Configuration ──────┐
Skill Configuration ──────┤
User Configuration ───────┼──→ Routing Validation
Division Configuration ───┘
```

All hard prerequisites must be satisfied.

---

# 21. Parallel Tasks

Where dependencies permit:

```text
Configure Queue ──────────────┐
Configure Skills ─────────────┤
Configure Users ──────────────┼──→ Routing Validation
Configure Architect Flow ─────┘
```

The schedule should allow parallel execution.

---

# 22. Dependency Granularity

Dependencies should be task-specific.

Avoid:

```text
All Voice tasks depend on all Core Platform tasks.
```

Prefer:

```text
Configure Phone Number
        ↓
Assign Phone Number to Queue
```

This prevents unnecessary schedule constraints.

---

# 23. Dependency Quality Rules

A valid task dependency should:

1. identify a real prerequisite
2. identify a valid predecessor
3. identify a valid successor
4. have a clear direction
5. have a rationale
6. identify its classification
7. identify its strength
8. identify customer/external involvement
9. avoid unnecessary sequencing
10. avoid circularity

---

# 24. Dependency IDs

Use:

```text
DEP.TASK.<sequence>
```

Example:

```text
DEP.TASK.001
DEP.TASK.002
DEP.TASK.003
```

---

# 25. Dependency Register Example

| Dependency ID | Predecessor | Successor | Relationship | Type | Strength |
|---|---|---|---|---|---|
| DEP.TASK.001 | L10-01.01-001 | L10-01.02-001 | FS | TECHNICAL | HARD |
| DEP.TASK.002 | L10-01.02-001 | L10-04.01-001 | FS | TECHNICAL | HARD |
| DEP.TASK.003 | L10-04.01-001 | L10-12.01-001 | FS | TEST | HARD |
| DEP.TASK.004 | L10-12.03-001 | L10-09.01-001 | FS | APPROVAL | CONDITIONAL |

---

# 26. Dependency Validation

The dependency model must validate:

- task exists
- predecessor exists
- successor exists
- no self-reference
- no duplicate relationship
- no circular dependency
- relationship type is valid
- dependency classification is valid
- conditional dependencies have conditions
- critical-path classification is valid

---

# 27. Dependency and Effort

Dependencies do not modify baseline task effort.

They influence:

- task start
- task finish
- duration
- resource loading
- float
- critical path

---

# 28. Dependency and Resource Constraints

Resource contention must not be disguised as technical dependency.

Example:

```text
Task A
Task B
```

may both be technically ready.

If one engineer must perform both, the schedule may sequence them because of resource availability.

That is a resource constraint, not a task dependency.

---

# 29. Dependency and Critical Path

Hard dependencies form the primary network used to calculate:

- earliest start
- earliest finish
- latest start
- latest finish
- total float
- critical path

---

# 30. Definition of Done

Task dependency modelling is complete when:

- applicable tasks have dependencies
- predecessor and successor relationships are defined
- dependency types are classified
- dependency strength is defined
- customer dependencies are identified
- external dependencies are identified
- conditional dependencies have conditions
- invalid relationships are detected
- circular dependencies are eliminated
- the dependency network can feed schedule generation
# Layer 10 — 05 Dependency Model

## Purpose

This directory defines the dependency model used by the Genesys Cloud Project Framework to identify, classify, sequence and manage dependencies between:

- Layer 1 deployment phases
- Layer 2 capabilities
- Layer 10 implementation tasks
- project workstreams
- customer activities
- third-party activities
- environments
- technical prerequisites
- approvals
- testing
- migration
- deployment
- operational readiness

The Dependency Model converts the Layer 10 task catalogue into a structured delivery network that can be consumed by the project schedule and estimation models.

---

# Repository Structure

```text
05-dependency-model/
│
├── README.md
├── layer-1-dependencies.md
├── capability-dependencies.md
├── task-dependencies.md
└── critical-path-model.md
```

---

# Document Catalogue

| File | Purpose |
|---|---|
| `README.md` | Dependency Model methodology and governance |
| `layer-1-dependencies.md` | Layer 1 phase sequencing and dependency relationships |
| `capability-dependencies.md` | Layer 2 capability dependency relationships |
| `task-dependencies.md` | Individual Layer 10 task dependency model |
| `critical-path-model.md` | Critical path and float methodology |

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

---

# Dependency Hierarchy

Dependencies are represented at three primary levels:

```text
Layer 1
Phase Dependencies
        ↓
Layer 2
Capability Dependencies
        ↓
Layer 10
Task Dependencies
```

The Layer 1 and Layer 2 models provide planning context.

The Layer 10 task dependency model provides the actual schedule relationships.

---

# Dependency Types

The standard dependency relationships are:

- FINISH-TO-START
- START-TO-START
- FINISH-TO-FINISH
- START-TO-FINISH
- CONDITIONAL
- EXTERNAL
- CUSTOMER
- APPROVAL
- TECHNICAL
- DATA
- ENVIRONMENT
- TEST
- MIGRATION
- OPERATIONAL

FINISH-TO-START is the default unless another relationship is explicitly justified.

---

# Dependency Strength

Dependencies are classified as:

- HARD
- SOFT
- CONDITIONAL
- INFORMATIONAL

Hard dependencies are the primary inputs into critical-path analysis.

---

# Dependency Ownership

Dependencies may be owned by:

- Delivery Team
- Customer
- Third Party
- Shared / Joint

Ownership must be explicit where dependency delay could affect the schedule.

---

# Critical Path

The dependency model provides the network required to calculate:

- earliest start
- earliest finish
- latest start
- latest finish
- float
- critical tasks
- critical paths
- near-critical tasks

---

# Dependency Principles

The following principles apply:

1. Dependencies must represent real prerequisites.
2. Dependencies must be directional.
3. Dependencies must be traceable.
4. Dependencies must have a clear rationale.
5. Dependencies must not be created merely to force sequential delivery.
6. Parallel execution should be preserved wherever technically possible.
7. Customer dependencies must be explicit.
8. External dependencies must be explicit.
9. Conditional dependencies must include their activation condition.
10. Circular dependencies must be eliminated.
11. Resource constraints must not be disguised as technical dependencies.
12. Task-level dependencies take precedence over broad phase assumptions when generating the schedule.

---

# Relationship to Layer 10 Task Standards

The Dependency Model consumes the task attributes defined by Layer 10 / 02.

In particular:

- Task ID
- Layer 1 Phase
- Layer 2 Domain
- Layer 2 Capability
- Task Type
- Primary Role
- Customer Responsibility
- Environment
- Baseline Effort
- Duration
- Critical Path

The Dependency Model adds:

- predecessor
- successor
- dependency type
- relationship
- dependency strength
- dependency owner
- dependency condition
- dependency rationale

---

# Relationship to Estimation

Dependencies do not change baseline task effort.

They affect:

- start date
- finish date
- duration
- sequencing
- resource loading
- project duration
- critical path

---

# Relationship to Roles

The Role Catalogue defines who performs a task.

The Dependency Model defines when the task can be performed.

```text
Task
 ↓
Primary Role
 ↓
Task Effort
 ↓
Dependencies
 ↓
Schedule
```

---

# Relationship to Project Schedule

The dependency model is a direct input to Layer 10 / 06.

```text
Task Catalogue
        +
Estimation Model
        +
Role Catalogue
        +
Dependency Model
        ↓
Project Schedule
```

---

# Relationship to Spreadsheet Model

The dependency model must ultimately support spreadsheet fields including:

- Task ID
- Predecessor Task ID
- Successor Task ID
- Dependency Type
- Relationship
- Dependency Strength
- Dependency Owner
- Customer Dependency
- External Dependency
- Condition
- Critical Path

---

# Definition of Done

The Dependency Model is complete when:

- Layer 1 dependencies are defined
- Layer 2 capability dependencies are defined
- Layer 10 task dependencies are defined
- dependency types are standardised
- dependency strength is defined
- dependency ownership is defined
- customer dependencies are identified
- external dependencies are identified
- environment dependencies are identified
- approval dependencies are identified
- testing dependencies are identified
- migration dependencies are identified
- deployment dependencies are identified
- circular dependencies can be detected
- dependency relationships are traceable
- critical-path analysis can consume the dependency network
- the model can feed Layer 10 / 06 Project Schedule Model
- the model can feed Layer 10 / 07 Spreadsheet Model
# Layer 10 — Sequencing Model

## Purpose

This document defines the sequencing rules used to convert Layer 10 task dependencies, effort, duration, roles, customer responsibilities, and environmental constraints into an executable Genesys Cloud implementation sequence.

---

# 1. Sequencing Principle

The schedule should execute work:

- as early as practical
- as late as necessary
- subject to valid dependencies
- subject to resource constraints
- subject to customer availability
- subject to environment availability
- subject to governance controls

The default scheduling principle is:

```text
Dependency
    ↓
Eligibility
    ↓
Resource Availability
    ↓
Environment Availability
    ↓
Schedule Position
```

---

# 2. Sequencing Hierarchy

Sequencing occurs at multiple levels.

```text
Layer 1
        ↓
Layer 2
        ↓
Workstream
        ↓
Capability
        ↓
Task
        ↓
Dependency
```

Task-level dependencies have precedence over broad assumptions about phase sequencing.

---

# 3. Dependency-Driven Sequencing

The Dependency Model is authoritative for task relationships.

The default relationship is:

```text
FINISH-TO-START
```

Example:

```text
L10-01.01-001
Provision platform
        ↓
L10-01.02-001
Configure baseline settings
        ↓
L10-01.03-001
Validate platform
```

A downstream task must not be scheduled before its hard predecessor permits execution.

---

# 4. Parallel Sequencing

Tasks should be scheduled in parallel where no blocking dependency exists.

Example:

```text
Architecture Approved
        ↓
┌──────────────────┬──────────────────┬──────────────────┐
│ Voice Build      │ Digital Build    │ Data Build       │
└──────────────────┴──────────────────┴──────────────────┘
        ↓
Integrated Testing
```

Parallelism should be preferred over artificial sequential scheduling.

---

# 5. Sequencing Rules

The following rules apply:

1. Hard dependencies must be honoured.
2. Conditional dependencies must be evaluated before scheduling.
3. Customer dependencies must be scheduled explicitly.
4. External dependencies must be scheduled explicitly.
5. Environment prerequisites must be satisfied.
6. Required approvals must be scheduled.
7. Testing prerequisites must be completed before dependent testing.
8. Production prerequisites must be completed before production deployment.
9. Migration prerequisites must be completed before migration.
10. Operational readiness must precede operational handover.
11. Phase gates must be passed before controlled progression.
12. Parallel execution should be preserved where practical.

---

# 6. Resource Constraints

Resource availability may constrain task sequencing.

Example:

```text
Task A ────────┐
               ├── Specialist Resource
Task B ────────┘
```

If the same resource cannot perform both tasks concurrently, the schedule may need to sequence them.

This is a scheduling constraint, not necessarily a dependency.

---

# 7. Customer Constraints

Customer availability may affect sequencing.

Examples:

- customer approval
- business SME availability
- UAT availability
- data owner availability
- production approval
- business validation

Customer constraints must be visible in the schedule.

---

# 8. Environment Constraints

Environment availability may constrain sequencing.

Example:

```text
DEV Available
    ↓
Build
    ↓
TEST Available
    ↓
System Testing
    ↓
UAT Available
    ↓
Business Acceptance
```

---

# 9. Approval Sequencing

Approval activities should be represented explicitly where approval is a prerequisite.

Example:

```text
Architecture Design
        ↓
Architecture Review
        ↓
Architecture Approval
        ↓
Build
```

Approval should not be hidden inside unrelated implementation tasks where it materially affects schedule timing.

---

# 10. Testing Sequence

A typical testing sequence is:

```text
Build Complete
        ↓
Test Preparation
        ↓
System Testing
        ↓
Defect Resolution
        ↓
Regression Testing
        ↓
UAT Preparation
        ↓
UAT
        ↓
Business Acceptance
```

Actual sequencing may vary by project.

---

# 11. Migration Sequence

A typical migration sequence is:

```text
Source Discovery
        ↓
Data Profiling
        ↓
Mapping
        ↓
Transformation
        ↓
Migration Tooling
        ↓
Mock Migration
        ↓
Rehearsal
        ↓
Cutover Preparation
        ↓
Production Migration
        ↓
Validation
        ↓
Reconciliation
```

---

# 12. Deployment Sequence

A typical production sequence is:

```text
Production Readiness
        ↓
Go-Live Approval
        ↓
Change Window
        ↓
Production Deployment
        ↓
Technical Validation
        ↓
Business Validation
        ↓
Go-Live
        ↓
Hypercare
```

---

# 13. Phase Sequencing

The Layer 1 lifecycle provides the high-level delivery sequence.

However, the project schedule must not assume that every task within one phase must finish before the next phase begins.

Instead:

```text
Layer 1
High-Level Lifecycle
        ↓
Task Dependencies
        ↓
Actual Schedule Sequence
```

This allows controlled overlap between phases.

---

# 14. Phase Overlap

Examples of valid phase overlap include:

```text
Architecture
      ├── Voice Design
      ├── Digital Design
      └── Integration Design

Build
      ├── Platform Configuration
      ├── Voice Configuration
      └── Architect Development

Testing
      ├── Voice Testing
      ├── Digital Testing
      └── Integration Testing
```

Phase overlap should be intentional and dependency-driven.

---

# 15. Critical Path Sequencing

The critical path should be derived from the dependency network.

Typical critical-path activities may include:

- architecture approval
- core platform readiness
- integration readiness
- migration rehearsal
- UAT
- production readiness
- cutover
- go-live
- operational handover

The exact critical path must be calculated for the project rather than assumed.

---

# 16. Float

The schedule should support:

- total float
- free float
- zero-float activities
- near-critical activities

Float should be derived from the dependency network and project dates.

---

# 17. Schedule Logic

The scheduling engine or workbook should conceptually apply:

```text
Task Duration
+
Calendar
+
Predecessor Finish
+
Dependency Relationship
+
Resource Availability
+
Constraints
=
Scheduled Start / Finish
```

---

# 18. Sequencing Exceptions

Exceptions may be required for:

- emergency fixes
- customer constraints
- third-party constraints
- production incidents
- regulatory deadlines
- fixed deployment windows
- migration windows
- business blackout periods

Exceptions must be documented and approved where they alter the baseline sequence.

---

# 19. Sequencing Validation

Before approving the schedule, validate:

- no circular dependencies
- no impossible dates
- no task scheduled before prerequisite completion
- no milestone scheduled before required tasks
- no phase gate scheduled before exit criteria
- no production deployment before production readiness
- no go-live before acceptance
- no handover before operational readiness
- no task assigned to unavailable resources

---

# 20. Definition of Done

The Sequencing Model is complete when:

- dependency-driven sequencing is defined
- parallel execution rules are defined
- resource constraints are defined
- customer constraints are defined
- environment constraints are defined
- approval sequencing is defined
- testing sequencing is defined
- migration sequencing is defined
- deployment sequencing is defined
- phase overlap rules are defined
- critical-path sequencing is defined
- float is supported
- schedule exceptions are controlled
- sequencing validation rules are defined
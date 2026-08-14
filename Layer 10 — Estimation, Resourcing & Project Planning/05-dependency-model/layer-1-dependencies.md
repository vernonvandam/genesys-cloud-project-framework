# Layer 10 — Layer 1 Dependencies

## Purpose

This document defines the standard dependency relationships between the Layer 1 deployment phases of the Genesys Cloud Project Framework.

Layer 1 dependencies provide the high-level delivery sequence used to organise the detailed Layer 10 task dependency model.

---

# 1. Layer 1 Phase Sequence

The standard Layer 1 sequence is:

```text
P01
Mobilisation & Discovery
        ↓
P02
Current-State Discovery
        ↓
P03
Requirements Definition
        ↓
P04
Architecture & Design
        ↓
P05
Platform Foundations
        ↓
P06
Build & Configuration
        ↓
P07
Integration & Migration
        ↓
P08
Testing & Validation
        ↓
P09
Deployment Preparation
        ↓
P10
Production Deployment & Validation
        ↓
P11
Hypercare
        ↓
P12
Operational Handover & Closure
```

---

# 2. Standard Phase Dependencies

| Predecessor | Successor | Relationship | Strength | Default |
|---|---|---|---|---|
| P01 | P02 | FINISH-TO-START | HARD | Required |
| P02 | P03 | FINISH-TO-START | HARD | Required |
| P03 | P04 | FINISH-TO-START | HARD | Required |
| P04 | P05 | FINISH-TO-START | CONDITIONAL | Required where foundations depend on design |
| P05 | P06 | FINISH-TO-START | HARD | Required |
| P06 | P07 | FINISH-TO-START | CONDITIONAL | Depends on integration/migration scope |
| P07 | P08 | FINISH-TO-START | HARD | Required |
| P08 | P09 | FINISH-TO-START | HARD | Required |
| P09 | P10 | FINISH-TO-START | HARD | Required |
| P10 | P11 | FINISH-TO-START | HARD | Required |
| P11 | P12 | FINISH-TO-START | HARD | Required |

---

# 3. Phase Dependency Principle

Layer 1 phase dependencies are not intended to prevent valid parallel delivery.

For example:

```text
P04 Architecture
       ↓
       ├── P05 Foundations
       ├── P06 Build
       └── P07 Integration Design
```

may occur in overlapping periods where the detailed task dependencies allow it.

The task network determines the actual schedule.

---

# 4. P01 Dependencies

## P01 → P02

P02 requires:

- project mobilisation
- project governance
- stakeholder identification
- discovery planning
- project access
- agreed discovery scope

---

# 5. P02 Dependencies

## P02 → P03

P03 requires:

- current-state understanding
- existing environment information
- business process information
- integration inventory
- platform inventory
- known constraints

---

# 6. P03 Dependencies

## P03 → P04

P04 requires:

- approved requirements
- business objectives
- technical requirements
- non-functional requirements
- security requirements
- integration requirements

---

# 7. P04 Dependencies

## P04 → P05

P05 may depend on:

- approved architecture
- environment design
- identity design
- security architecture
- platform design
- integration architecture

This dependency may be conditional where foundations can be established using previously approved standards.

---

# 8. P05 Dependencies

## P05 → P06

P06 requires appropriate platform foundations, such as:

- organisation structure
- environments
- identity foundations
- baseline security
- required administrative access
- platform standards

---

# 9. P06 Dependencies

## P06 → P07

This relationship is conditional.

Integration and migration may begin before all configuration is complete where independent prerequisites are satisfied.

Examples:

```text
Integration Design
        ↓
Integration Build
```

may proceed while unrelated platform configuration continues.

---

# 10. P07 Dependencies

## P07 → P08

Testing requires:

- configured solution
- required integrations
- required migration components
- test environments
- test data
- test users
- test prerequisites

---

# 11. P08 Dependencies

## P08 → P09

Deployment preparation requires sufficient evidence that:

- functional testing is complete
- material defects are resolved
- integration testing is complete
- UAT is complete where required
- production readiness criteria can be assessed

---

# 12. P09 Dependencies

## P09 → P10

Production deployment requires:

- deployment plan
- cutover plan
- rollback plan
- production readiness
- approvals
- operational readiness
- customer go-live approval

---

# 13. P10 Dependencies

## P10 → P11

Hypercare begins after production deployment and requires:

- production validation
- initial operational acceptance
- support coverage
- monitoring
- issue management

---

# 14. P11 Dependencies

## P11 → P12

Operational handover requires:

- stable production operation
- open issue disposition
- support documentation
- operational procedures
- knowledge transfer
- acceptance

---

# 15. Parallel Execution

Parallel work is permitted where detailed task dependencies allow.

Examples include:

```text
Voice Configuration
Digital Configuration
WFM Configuration
Reporting Configuration
```

These may proceed in parallel if their prerequisites are independently satisfied.

---

# 16. Layer 1 Dependency Rule

Layer 1 dependencies establish governance-level sequencing.

They must not be used as a substitute for task-level dependency modelling.

The detailed dependency model must always identify the actual predecessor and successor tasks where sequencing matters.

---

# 17. Definition of Done

Layer 1 dependency modelling is complete when:

- P01–P12 relationships are defined
- phase relationships have been classified
- conditional relationships are identified
- parallel execution is permitted where appropriate
- task-level dependencies can override broad phase assumptions
- the model can feed the project schedule
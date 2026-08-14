# Layer 10 — Dependency Standard

## Purpose

This document defines how task dependencies are identified and represented.

---

# 1. Purpose

Dependencies establish the logical sequencing required to deliver the project.

They support:

- scheduling
- critical-path analysis
- resource planning
- risk management
- cutover planning

---

# 2. Dependency Types

The framework recognises:

- Finish-to-Start
- Start-to-Start
- Finish-to-Finish
- Start-to-Finish

`Finish-to-Start` should be the default relationship unless another relationship is justified.

---

# 3. Task Dependencies

Where one Layer 10 task depends on another, reference the predecessor Task ID.

Example:

```text
L10-01.01-002
depends on
L10-01.01-001
```

---

# 4. External Dependencies

External dependencies may include:

- customer approvals
- third-party systems
- telecommunications providers
- CRM availability
- identity provider readiness
- data extracts
- certificates
- network connectivity
- regulatory approvals

---

# 5. Dependency Classification

Dependencies should be classified as:

```text
INTERNAL
CUSTOMER
THIRD-PARTY
TECHNICAL
DATA
ENVIRONMENT
APPROVAL
OPERATIONAL
```

---

# 6. Hard vs Soft Dependencies

### Hard Dependency

The predecessor must complete before the task can proceed.

### Soft Dependency

The predecessor materially influences the task but does not strictly prevent work from beginning.

---

# 7. Dependency Documentation

Each material dependency should identify:

- predecessor
- dependency type
- relationship
- reason
- impact if delayed

---

# 8. Circular Dependencies

Circular dependencies must not exist.

Example:

```text
Task A → Task B → Task C → Task A
```

must be resolved before the schedule is baselined.

---

# 9. External Dependency Management

External dependencies must be represented even when they are outside the delivery team's direct control.

This enables realistic project planning.

---

# 10. Dependency and Critical Path

A dependency may cause a task to become critical path.

Critical-path analysis is defined separately in:

`critical-path-standard.md`

---

# 11. Definition of Done

Dependencies are complete when:

- material predecessors are identified
- dependency relationships are classified
- external dependencies are captured
- circular dependencies are eliminated
- dependency logic can be consumed by the schedule model
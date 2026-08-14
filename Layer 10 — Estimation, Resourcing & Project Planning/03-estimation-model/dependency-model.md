# Layer 10 — Estimation Dependency Model

## Purpose

This document defines how dependencies influence estimation and project planning.

The authoritative task dependency standard is defined in:

```text
02-task-standards/dependency-standard.md
```

This document defines how those dependencies are consumed by the estimation model.

---

# 1. Dependency Categories

Dependencies may include:

- task dependencies
- customer dependencies
- environment dependencies
- technical dependencies
- data dependencies
- approval dependencies
- third-party dependencies
- operational dependencies

---

# 2. Dependency Effects

Dependencies may affect:

- start date
- duration
- resource allocation
- critical path
- risk
- estimate confidence

Dependencies should not automatically increase productive effort.

---

# 3. Hard Dependency

A hard dependency prevents the successor task from starting or completing until the prerequisite is satisfied.

Example:

```text
Environment Provisioning
        ↓
Configuration
```

---

# 4. Soft Dependency

A soft dependency influences sequencing but does not necessarily prevent work from beginning.

---

# 5. External Dependencies

External dependencies must be captured even when the delivery team cannot control them.

Examples:

```text
Customer provides test data
Third party provides API endpoint
Telephony provider completes number port
Customer approves security design
```

---

# 6. Dependency and Effort

A dependency should only change effort when it creates additional work.

Waiting time affects duration, not productive effort.

---

# 7. Dependency and Duration

Dependencies may extend duration through:

- waiting periods
- approval cycles
- environment readiness
- fixed windows
- sequential promotion

---

# 8. Dependency and Critical Path

A dependency may cause the successor task to become critical path.

Critical-path analysis is performed in accordance with:

```text
02-task-standards/critical-path-standard.md
```

---

# 9. Dependency Traceability

Dependencies should reference Task IDs wherever possible.

Example:

```text
L10-03.04-002
depends on
L10-01.03-005
```

---

# 10. Dependency Validation

Before project estimation is baselined:

- dependency completeness should be reviewed
- circular dependencies must be removed
- external dependencies must be identified
- critical dependencies must be validated
- customer dependencies must be acknowledged

---

# 11. Definition of Done

The dependency model is complete when:

- material dependencies are captured
- dependencies can affect schedule logic
- waiting time is distinguished from effort
- critical dependencies are identifiable
- dependency data can feed the project schedule
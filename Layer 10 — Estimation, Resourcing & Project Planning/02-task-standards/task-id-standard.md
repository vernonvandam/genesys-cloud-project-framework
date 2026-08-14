# Layer 10 — Task ID Standard

## Purpose

This document defines the unique identification standard for implementation tasks within the Layer 10 Task Catalogue.

---

# 1. Task ID Format

Task IDs use:

```text
L10-<DOMAIN>.<CAPABILITY>-<TASK>
```

Example:

```text
L10-01.01-001
```

---

# 2. Components

| Component | Meaning |
|---|---|
| L10 | Layer 10 |
| 01 | Layer 2 capability domain |
| 01 | Capability within the domain |
| 001 | Sequential task number |

---

# 3. Domain Number

The domain number corresponds to the Layer 2 capability domain.

Examples:

```text
01 = Core Platform
02 = Identity & Access
03 = Voice & Telephony
04 = ACD & Routing
05 = Architect
06 = Digital
07 = WFM & Employee Engagement
08 = Data, Integrations & APIs
09 = Analytics & Reporting
10 = Quality, Recording & Evaluation
11 = Security, Compliance & Governance
12 = Testing, Validation & Deployment
13 = Migration, Data Conversion & Transition
14 = Operations, Support & Service Management
15 = Optimisation, Continuous Improvement & Platform Evolution
```

---

# 4. Capability Number

The capability number corresponds to the numbered capability within the Layer 2 domain.

Example:

```text
L10-01.01
```

represents:

```text
Layer 10
Domain 01
Capability 01
```

---

# 5. Task Number

The task number is a three-digit sequential number beginning at:

```text
001
```

Example:

```text
L10-01.01-001
L10-01.01-002
L10-01.01-003
```

---

# 6. Uniqueness

Every Task ID must be unique within the framework.

Task IDs must not be reused.

A retired task ID must remain retired.

---

# 7. Stability

Once assigned, a Task ID should remain stable.

Changes to:

- task wording
- task description
- estimate
- role
- dependency
- acceptance criteria

must not normally result in a new Task ID.

A new Task ID is required when the task represents a materially different implementation outcome.

---

# 8. Task Splitting

If a task is split into multiple tasks, the original ID should not be reused.

Example:

```text
Original:
L10-01.01-001
```

After redesign:

```text
L10-01.01-002
L10-01.01-003
```

The original ID should be marked retired or superseded in change history where appropriate.

---

# 9. Task Consolidation

When multiple tasks are consolidated, the surviving Task ID must be explicitly identified.

Retired IDs must not be silently reused.

---

# 10. Formatting

Task IDs must:

- use uppercase `L`
- use uppercase domain/capability numbering
- use hyphens and periods exactly as defined
- use three digits for task sequence
- contain no spaces

Valid:

```text
L10-04.07-003
```

Invalid:

```text
l10-04.07-3
L10 04.07 003
L10-4.7-003
```

---

# 11. Project-Specific Tasks

Project-specific tasks that do not exist in the baseline catalogue must not be inserted into the baseline methodology without governance.

Where project-specific task extensions are required, they must use an explicitly defined extension convention approved by the framework owner.

---

# 12. Definition of Done

The Task ID standard is satisfied when:

- every task has a unique identifier
- the ID identifies Layer 10
- the ID maps to the Layer 2 domain
- the ID maps to the Layer 2 capability
- the sequential task number is unique
- IDs remain stable through normal task maintenance
- retired IDs are not reused
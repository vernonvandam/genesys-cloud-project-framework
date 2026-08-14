# Layer 10 — Critical Path Standard

## Purpose

This document defines how implementation tasks are classified for critical-path analysis.

---

# 1. Critical Path Classification

Every task must be classified as:

```text
YES
NO
CONDITIONAL
```

---

# 2. YES

`YES` indicates that the task is expected to directly contribute to the critical path under the baseline project model.

Examples:

- production cutover prerequisite
- production environment provisioning
- mandatory migration activity
- required go-live validation
- critical integration dependency

---

# 3. NO

`NO` indicates that delay to the task is not expected to delay a major project milestone under the baseline model.

---

# 4. CONDITIONAL

`CONDITIONAL` indicates that the task may become critical depending on project-specific sequencing, scope, resource availability, or customer decisions.

---

# 5. Critical Path Is Dynamic

Critical-path classification must not be treated as permanently fixed.

The actual project critical path depends on:

- task duration
- dependencies
- schedule dates
- resource constraints
- milestones
- customer commitments
- deployment windows

---

# 6. Critical Tasks

A task may be classified as critical where delay could affect:

- design completion
- build completion
- testing
- UAT
- migration
- cutover
- go-live
- operational handover

---

# 7. Critical Path vs Priority

Critical path does not mean:

```text
important
```

and non-critical does not mean:

```text
unimportant
```

The classification describes schedule impact.

---

# 8. Critical Path Review

Critical-path status should be reviewed when:

- dependencies change
- duration changes
- scope changes
- milestones change
- deployment dates change
- resources change
- customer availability changes

---

# 9. Critical Path and Risk

Tasks with:

- long duration
- many successors
- external dependencies
- limited resource availability
- fixed execution windows

should receive particular attention during critical-path analysis.

---

# 10. Definition of Done

Critical-path classification is complete when:

- each task has a classification
- classification is based on schedule impact
- dependencies have been considered
- conditional criticality is identified
- actual project critical path can be calculated by Layer 10/06
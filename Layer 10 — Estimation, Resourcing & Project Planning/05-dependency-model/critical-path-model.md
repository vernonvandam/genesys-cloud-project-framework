# Layer 10 — Critical Path Model

## Purpose

This document defines how the Genesys Cloud Project Framework identifies and manages the critical path using the Layer 10 dependency network.

The Critical Path Model converts task dependencies, task duration and scheduling constraints into a project completion path.

---

# 1. Critical Path Principle

The critical path is the sequence of dependent activities that determines the earliest possible project completion date under the current schedule assumptions.

Critical path analysis must be based on:

- task dependencies
- task duration
- dependency relationships
- scheduling constraints
- milestones
- project completion requirements

---

# 2. Model Flow

```text
Task Catalogue
        ↓
Task Effort
        ↓
Task Duration
        ↓
Task Dependencies
        ↓
Dependency Network
        ↓
Schedule Calculation
        ↓
Float Calculation
        ↓
Critical Path
```

---

# 3. Critical Path Definition

A task is considered critical when its available schedule float is zero or when delay to that task directly delays the project completion date.

Critical-path status is therefore a **schedule outcome**, not merely a manually assigned attribute.

---

# 4. Task Attributes

Critical-path analysis requires:

| Attribute | Requirement |
|---|---|
| Task ID | Required |
| Duration | Required |
| Predecessors | Required where applicable |
| Successors | Required where applicable |
| Relationship | Required |
| Constraint | Where applicable |
| Milestone | Where applicable |
| Calendar | Required for schedule calculation |

---

# 5. Forward Pass

The forward pass determines:

- Earliest Start
- Earliest Finish

Conceptually:

```text
Earliest Finish
=
Earliest Start
+
Duration
```

For a task with predecessors:

```text
Earliest Start
=
Latest applicable predecessor constraint
```

---

# 6. Backward Pass

The backward pass determines:

- Latest Start
- Latest Finish

Conceptually:

```text
Latest Start
=
Latest Finish
-
Duration
```

---

# 7. Float

Total float represents the amount of time a task may be delayed without delaying the project completion date.

```text
Total Float
=
Latest Start
-
Earliest Start
```

or equivalently:

```text
Total Float
=
Latest Finish
-
Earliest Finish
```

---

# 8. Critical Task

A task with:

```text
Total Float = 0
```

is normally considered critical.

---

# 9. Critical Path

The critical path is represented as:

```text
Task A
  ↓
Task B
  ↓
Task C
  ↓
Task D
```

where delay to one of the tasks directly affects project completion.

---

# 10. Multiple Critical Paths

A project may contain multiple critical paths.

Example:

```text
Voice Critical Path
A → B → C → D

Digital Critical Path
E → F → G → D
```

Both may converge on a common deployment milestone.

The model must support multiple critical paths.

---

# 11. Near-Critical Tasks

Tasks with low positive float should be identified as near-critical.

Example:

```text
0 days      Critical
1 day       Near Critical
2–3 days    Low Float
>3 days     Normal Float
```

The exact thresholds should be configurable.

---

# 12. Critical Path and Conditional Tasks

Conditional tasks should not be included in the critical path unless their condition is active for the project.

Example:

```text
PCI Requirement
      ↓
PCI Configuration
      ↓
PCI Validation
```

If PCI is not applicable, the tasks are excluded from the active schedule network.

---

# 13. Critical Path and Customer Dependencies

Customer-controlled tasks may appear on the critical path.

Examples:

- architecture approval
- requirements approval
- UAT sign-off
- production approval
- cutover approval

These must not be excluded simply because they are customer responsibilities.

---

# 14. Critical Path and External Dependencies

External dependencies may also become critical.

Examples:

- carrier provisioning
- number porting
- third-party API readiness
- identity provider configuration
- certificates
- network changes

External lead time must be represented in the schedule where it affects project completion.

---

# 15. Critical Path and Resource Constraints

Resource constraints are separate from dependency-driven critical path.

A task may become schedule-critical because:

```text
Required Resource
        ↓
Unavailable
        ↓
Task Delayed
        ↓
Successor Delayed
```

The schedule model should distinguish:

- dependency-driven criticality
- resource-driven schedule constraints

---

# 16. Critical Path and Milestones

Important milestones include:

- requirements approval
- architecture approval
- build completion
- test completion
- UAT completion
- production readiness
- go-live
- hypercare completion
- operational handover
- project closure

Milestones may form the endpoints of critical paths.

---

# 17. Critical Path Reporting

The schedule model should report:

| Attribute | Description |
|---|---|
| Task ID | Task identifier |
| Task | Task name |
| Duration | Task duration |
| Earliest Start | Calculated earliest start |
| Earliest Finish | Calculated earliest finish |
| Latest Start | Calculated latest start |
| Latest Finish | Calculated latest finish |
| Total Float | Calculated float |
| Critical | YES / NO |
| Critical Path ID | Path identifier |
| Primary Role | Assigned delivery role |
| Layer 1 Phase | P01–P12 |
| Layer 2 Domain | Capability domain |

---

# 18. Critical Path Review

Critical path analysis should be repeated when:

- task durations change
- dependencies change
- scope changes
- customer delays occur
- external dependencies change
- resources change
- migration scope changes
- production date changes
- new tasks are added
- tasks are removed

---

# 19. Critical Path Risks

Critical-path risk may arise from:

- customer approvals
- external provisioning
- migration
- data quality
- complex integrations
- security approvals
- testing defects
- limited specialist resources
- environment availability
- production change windows

---

# 20. Critical Path Mitigation

Possible mitigation strategies include:

- parallel execution
- earlier customer engagement
- early provisioning
- automation
- reusable configuration
- additional resources
- scope sequencing
- earlier testing
- mock migration
- rehearsal
- pre-approved changes
- reduction of unnecessary dependencies

---

# 21. Critical Path and Task Classification

Task classification must remain separate from critical-path status.

Example:

```text
Task Type:
REQUIRED

Critical Path:
NO
```

or:

```text
Task Type:
CONDITIONAL

Critical Path:
YES
```

A required task is not automatically critical.

A conditional task may become critical when activated.

---

# 22. Critical Path Data Flow

```text
Layer 10 Task
      ↓
Task Duration
      ↓
Task Predecessors
      ↓
Task Successors
      ↓
Schedule Network
      ↓
Forward Pass
      ↓
Backward Pass
      ↓
Float
      ↓
Critical Path
```

---

# 23. Definition of Done

The Critical Path Model is complete when:

- task duration is available
- dependency relationships are available
- predecessor and successor relationships are valid
- forward-pass calculations can be performed
- backward-pass calculations can be performed
- float can be calculated
- critical tasks can be identified
- multiple critical paths can be supported
- near-critical tasks can be identified
- customer dependencies can be represented
- external dependencies can be represented
- resource constraints can be distinguished from technical dependencies
- critical-path outputs can feed the project schedule
- critical-path status can feed the estimation workbook
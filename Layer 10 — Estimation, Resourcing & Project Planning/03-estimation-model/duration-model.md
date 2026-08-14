# Layer 10 — Duration Model

## Purpose

The Duration Model defines how elapsed project time is estimated from task effort, dependencies, resources, and delivery constraints.

---

# 1. Effort vs Duration

Effort represents productive work.

Duration represents elapsed working time.

They must remain separate.

Example:

```text
Effort: 16 hours
Duration: 4 working days
```

---

# 2. Duration Drivers

Duration may be affected by:

- resource availability
- dependencies
- customer availability
- approvals
- environment readiness
- testing windows
- change windows
- migration windows
- third-party availability
- resource contention

---

# 3. Basic Duration

Where no material constraints exist:

```text
Duration =
Effort ÷ Available Daily Capacity
```

Example:

```text
Effort = 16 hours
Available capacity = 8 hours/day

Duration = 2 days
```

---

# 4. Resource Availability

A resource may not be available full-time.

Example:

```text
Effort = 16 hours
Resource allocation = 50%

Duration ≈ 4 working days
```

---

# 5. Dependency-Driven Duration

A task may have low effort but long duration because it is waiting for:

- customer approval
- test environment
- data
- certificates
- telephony provider
- integration endpoint
- deployment window

Waiting time must be represented through schedule dependencies rather than hidden in productive effort.

---

# 6. Parallel Execution

Tasks may execute in parallel when dependencies permit.

The duration model must therefore support:

```text
Task A ────────┐
Task B ────────┼──→ Task D
Task C ────────┘
```

rather than simply adding all durations.

---

# 7. Environment Duration

Environment-specific activities may require separate sequencing:

```text
DEV
 ↓
TEST
 ↓
UAT
 ↓
PROD
```

Where promotion is sequential, the schedule must represent the dependency.

---

# 8. Fixed Windows

Some activities require fixed windows:

- production cutover
- telephony migration
- data migration
- release deployment
- maintenance activities

These should be modelled as schedule constraints.

---

# 9. Duration Confidence

Duration confidence should reflect:

- dependency certainty
- resource availability
- environment readiness
- customer availability
- external-provider constraints

---

# 10. Definition of Done

Duration modelling is complete when:

- effort is separated from duration
- resource availability is considered
- dependencies are represented
- parallel execution is supported
- fixed windows are identified
- duration can feed the project schedule
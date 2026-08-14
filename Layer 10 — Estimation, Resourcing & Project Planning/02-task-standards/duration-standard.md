# Layer 10 — Duration Standard

## Purpose

This document defines how task duration is represented and distinguished from effort.

---

# 1. Duration Definition

Duration is the elapsed project time from task start to task completion.

Duration is not equivalent to productive effort.

---

# 2. Example

A task may have:

```text
Effort = 8 hours
Duration = 3 working days
```

because:

- the resource is part-time
- the task depends on customer availability
- approval is required
- an environment becomes available later
- execution must occur within a maintenance window

---

# 3. Duration Drivers

Duration may be affected by:

- dependencies
- resource availability
- customer availability
- environment availability
- approvals
- testing windows
- change windows
- migration windows
- third-party availability
- working calendars

---

# 4. Duration Units

Project schedule duration should normally be represented in:

- working hours
- working days

The project schedule model should define the authoritative conversion.

---

# 5. Effort vs Duration

Never infer effort directly from duration.

Example:

```text
Duration = 5 days
```

does not necessarily mean:

```text
Effort = 40 hours
```

---

# 6. Parallel Work

Tasks may have duration exceeding their effort because work is scheduled around parallel activities or availability.

---

# 7. Customer Waiting Time

Where customer or third-party waiting materially affects duration, it should be represented through dependencies or schedule logic rather than hidden inside the effort estimate.

---

# 8. Baseline Duration

Where a baseline duration is maintained, it should represent a normal scheduling assumption.

Project-specific duration may differ.

---

# 9. Definition of Done

Duration classification is complete when:

- duration is distinguishable from effort
- scheduling assumptions are known
- dependencies are represented separately
- customer/third-party waiting is not hidden in effort
- duration can be consumed by Layer 10/06
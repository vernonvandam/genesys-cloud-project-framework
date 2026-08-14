# Layer 10 — Task Granularity Standard

## Purpose

This document defines the required level of decomposition for implementation tasks.

---

# 1. Objective

Tasks must be granular enough to:

- estimate effort
- schedule work
- assign responsibility
- establish dependencies
- track progress
- determine completion
- identify critical-path impact

---

# 2. Atomic Task Principle

A task should normally represent one meaningful implementation outcome.

Example:

```text
Configure queue
```

may be too broad if queue creation, membership, routing configuration, testing, and validation require different ownership or sequencing.

It may be decomposed into:

```text
Create queue
Configure queue membership
Configure queue routing settings
Validate queue configuration
```

---

# 3. Over-Decomposition

Tasks should not be split into trivial actions such as:

```text
Open browser
Log in
Navigate to Admin
Click Save
```

These actions belong within the implementation description unless they materially affect:

- effort
- dependency
- responsibility
- risk
- sequencing
- acceptance

---

# 4. Under-Decomposition

A task should be decomposed when it contains multiple independent outcomes.

Warning signs include:

- multiple deliverables
- multiple primary roles
- multiple environments
- unrelated dependencies
- substantially different effort drivers
- separate acceptance criteria
- different project phases

---

# 5. Role Boundary

A task should normally have one Primary Role.

If different parts of the work require materially different accountable roles, consider decomposition.

---

# 6. Environment Boundary

Tasks should be separated where environment transitions materially affect:

- effort
- responsibility
- sequencing
- testing
- approval
- deployment

---

# 7. Dependency Boundary

Tasks should be decomposed when one portion must complete before another can begin.

---

# 8. Acceptance Boundary

Separate tasks should be considered when individual outcomes have separate acceptance criteria.

---

# 9. Schedule Row Principle

The task must be suitable for representation as a single schedule activity.

If project management cannot reasonably track the task as one schedule activity, it may be too broad.

---

# 10. Estimation Principle

A task must be estimable with reasonable confidence.

If estimating the task requires assumptions about several unrelated work packages, it should normally be decomposed.

---

# 11. Recommended Granularity

The framework does not impose a universal hourly threshold.

Task size varies based on:

- capability complexity
- solution design
- customer maturity
- integration complexity
- regulatory requirements
- environment complexity
- migration volume
- automation
- deployment approach

The objective is **consistent delivery granularity**, not identical task duration.

---

# 12. Definition of Done

A task meets the granularity standard when:

- it represents one meaningful outcome
- it has clear accountability
- it is independently estimable
- it can be scheduled
- dependencies are understandable
- acceptance is measurable
- it is not unnecessarily decomposed
- it is not hiding multiple unrelated outcomes
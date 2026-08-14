# Layer 10 — 10.10 Schedule Governance

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Governance & Lifecycle |
| Capability ID | 10.10 |
| Capability | Schedule Governance |
| Task Catalogue ID | 10.10 |
| Primary Layer 1 Phases | P04, P09, P10, P11 |

## Capability Objective

Govern schedules generated from approved tasks, dependencies, resources and durations.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P04 | Develop schedule |
| P09 | Baseline schedule |
| P10 | Control deployment schedule |
| P11 | Reforecast schedule |

## Source Implementation Activities

1. Build schedule.
2. Validate schedule.
3. Baseline schedule.
4. Monitor schedule.
5. Reforecast schedule.

## Implementation Tasks

### Activity 01 — Build

#### L10-10.10-001 — Build Project Schedule

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | HYBRID |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Build the schedule from approved tasks, dependencies, effort and resource assumptions.

**Dependencies**

- Task catalogue
- Dependency model
- Resource model

**Deliverable**

Draft project schedule.

**Acceptance Criteria**

Schedule contains all approved scope.

### Activity 02 — Validate

#### L10-10.10-002 — Validate Schedule Logic

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P09 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate durations, dependencies, milestones and critical path.

**Dependencies**

- L10-10.10-001

**Deliverable**

Schedule validation record.

**Acceptance Criteria**

No unresolved schedule logic errors remain.

### Activity 03 — Baseline

#### L10-10.10-003 — Baseline Project Schedule

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Obtain approval and baseline the project schedule.

**Dependencies**

- L10-10.10-002

**Deliverable**

Approved schedule baseline.

**Acceptance Criteria**

Schedule baseline is approved.

### Activity 04 — Reforecast

#### L10-10.10-004 — Reforecast Project Schedule

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P11 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Update forecast dates based on actual progress and approved changes.

**Dependencies**

- Baseline schedule
- Actual progress

**Deliverable**

Current forecast schedule.

**Acceptance Criteria**

Forecast reflects current delivery position.

## Capability-Level Dependencies

- Task catalogue
- Dependency model
- Resource model
- Estimation model

## Capability-Level Estimation Considerations

Schedule effort is driven by task count, dependency complexity and resource constraints.

## Definition of Done

The schedule is validated, baselined and maintained through controlled forecasting.

---
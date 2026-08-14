# Layer 10 — 2.07.19 Schedule Publication

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 07 — Workforce Management & Employee Engagement |
| Capability ID | 2.07.19 |
| Capability | Schedule Publication |
| Task Catalogue ID | 07.19 |
| Primary Layer 1 Phases | P08, P09, P10, P11 |

## Capability Objective

Publish approved schedules to the workforce through the agreed operational process.

## Source Implementation Activities

1. Validate publication readiness.
2. Approve schedule.
3. Publish schedule.
4. Confirm workforce visibility.
5. Validate post-publication state.

## Implementation Tasks

### Activity 01 — Prepare Publication

#### L10-07.19-001 — Validate Schedule Publication Readiness

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Confirm schedules, agents, time zones, activities and publication rules are ready.

**Dependencies**

- Schedule generation
- Schedule optimisation

**Deliverable**

Publication readiness checklist.

**Acceptance Criteria**

Schedule is approved for publication.

#### L10-07.19-002 — Approve Schedule Publication

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P10 |
| Primary Role | WFM Owner |
| Customer Responsibility | YES |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 0.5h |
| Critical Path | YES |

**Description**

Obtain customer approval to publish the schedule.

**Dependencies**

- L10-07.19-001

**Deliverable**

Publication approval.

**Acceptance Criteria**

WFM owner authorises publication.

### Activity 02 — Publish and Validate

#### L10-07.19-003 — Publish Schedule

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P10 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Publish the approved schedule to the workforce.

**Dependencies**

- L10-07.19-002

**Deliverable**

Published schedule.

**Acceptance Criteria**

Schedule is published successfully.

#### L10-07.19-004 — Validate Agent Schedule Visibility

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P11 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Validate that agents and supervisors can view the correct schedules.

**Dependencies**

- L10-07.19-003

**Deliverable**

Publication validation evidence.

**Acceptance Criteria**

Representative users can access correct schedules.
# Layer 10 — 2.07.15 Activities & Activity Codes

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 07 — Workforce Management & Employee Engagement |
| Capability ID | 2.07.15 |
| Capability | Activities & Activity Codes |
| Task Catalogue ID | 07.15 |
| Primary Layer 1 Phases | P03, P04, P06, P08 |

## Capability Objective

Define and configure the activities and activity codes used to represent scheduled work and non-work states.

## Source Implementation Activities

1. Identify required activities.
2. Define activity codes.
3. Map activities to workforce rules.
4. Configure activities.
5. Validate schedule behaviour.

## Implementation Tasks

### Activity 01 — Define Activities

#### L10-07.15-001 — Identify Activity Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Identify work, break, training, meeting, leave and other activities required by the workforce model.

**Dependencies**

- Scheduling strategy

**Deliverable**

Activity inventory.

**Acceptance Criteria**

Required activities are identified.

#### L10-07.15-002 — Define Activity Codes

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define naming, purpose, duration and operational treatment for activity codes.

**Dependencies**

- L10-07.15-001

**Deliverable**

Activity-code catalogue.

**Acceptance Criteria**

Activity codes are approved.

### Activity 02 — Configure and Validate

#### L10-07.15-003 — Configure Activities

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | API / TERRAFORM |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Configure approved activities and activity codes.

**Dependencies**

- L10-07.15-002

**Deliverable**

Configured activity catalogue.

**Acceptance Criteria**

Activities match approved definitions.

#### L10-07.15-004 — Validate Activity Behaviour

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate activities in generated schedules and adherence processes.

**Dependencies**

- L10-07.15-003

**Deliverable**

Activity validation evidence.

**Acceptance Criteria**

Activities behave correctly in schedules and adherence.
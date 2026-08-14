# Layer 10 — 2.07.27 Workforce Notifications

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 07 — Workforce Management & Employee Engagement |
| Capability ID | 2.07.27 |
| Capability | Workforce Notifications |
| Task Catalogue ID | 07.27 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P09 |

## Capability Objective

Configure workforce notifications required to communicate schedules, changes, exceptions and operational events.

## Source Implementation Activities

1. Identify notification requirements.
2. Define notification events.
3. Configure notifications.
4. Validate delivery.
5. Establish operational ownership.

## Implementation Tasks

### Activity 01 — Define Notifications

#### L10-07.27-001 — Identify Workforce Notification Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | NO |

**Description**

Identify schedule, time-off, workforce and operational notifications required by the customer.

**Dependencies**

- WFM operating model

**Deliverable**

Notification catalogue.

**Acceptance Criteria**

Required notification events are approved.

#### L10-07.27-002 — Define Notification Rules

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | NO |

**Description**

Define recipients, event triggers, timing and escalation behaviour.

**Dependencies**

- L10-07.27-001

**Deliverable**

Notification rules.

**Acceptance Criteria**

Rules are approved.

### Activity 02 — Configure and Validate

#### L10-07.27-003 — Configure Workforce Notifications

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Configure approved workforce notifications.

**Dependencies**

- L10-07.27-002

**Deliverable**

Configured notifications.

**Acceptance Criteria**

Notifications are configured as approved.

#### L10-07.27-004 — Test Workforce Notifications

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | NO |

**Description**

Test notification triggers, recipients, timing and message content.

**Dependencies**

- L10-07.27-003

**Deliverable**

Notification test evidence.

**Acceptance Criteria**

Approved notification scenarios operate correctly.
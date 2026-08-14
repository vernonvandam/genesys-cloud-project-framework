# Layer 10 — 2.07.28 Workforce Communications

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 07 — Workforce Management & Employee Engagement |
| Capability ID | 2.07.28 |
| Capability | Workforce Communications |
| Task Catalogue ID | 07.28 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P09 |

## Capability Objective

Provide controlled workforce communication capabilities where required for employee engagement and operational management.

## Source Implementation Activities

1. Determine communication requirements.
2. Define audiences and governance.
3. Configure communication mechanisms.
4. Validate employee communications.
5. Establish BAU ownership.

## Implementation Tasks

### Activity 01 — Define Communications

#### L10-07.28-001 — Confirm Workforce Communication Requirement

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Determine whether dedicated workforce communications are required.

**Dependencies**

- Employee engagement scope

**Deliverable**

Communication scope decision.

**Acceptance Criteria**

Requirement is confirmed.

#### L10-07.28-002 — Define Workforce Communication Model

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P04 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Define communication audiences, ownership, content governance and operational processes.

**Dependencies**

- L10-07.28-001

**Deliverable**

Communication model.

**Acceptance Criteria**

Model is approved.

### Activity 02 — Implement and Validate

#### L10-07.28-003 — Configure Workforce Communications

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Configure approved communication mechanisms.

**Dependencies**

- L10-07.28-002

**Deliverable**

Configured workforce communications.

**Acceptance Criteria**

Approved users can communicate as designed.

#### L10-07.28-004 — Validate Workforce Communications

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

Validate message delivery, permissions and user experience.

**Dependencies**

- L10-07.28-003

**Deliverable**

Communication validation evidence.

**Acceptance Criteria**

Communication scenarios pass UAT.
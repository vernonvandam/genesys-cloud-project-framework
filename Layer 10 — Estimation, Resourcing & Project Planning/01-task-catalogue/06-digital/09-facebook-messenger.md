# Layer 10 — 2.06.09 Facebook Messenger

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 06 — Digital |
| Capability ID | 2.06.09 |
| Capability | Facebook Messenger |
| Task Catalogue ID | 06.09 |
| Primary Layer 1 Phases | P03, P04, P06, P07, P08, P10, P11 |

## Capability Objective

Implement Facebook Messenger where required, including account ownership, channel configuration, routing and operational support.

## Implementation Tasks

### L10-06.09-001 — Confirm Facebook Messenger Applicability

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | CONDITIONAL |

**Description**

Confirm business requirement, page ownership, moderation responsibilities and supported use cases.

**Dependencies**

- Digital channel strategy

**Deliverable**

Facebook Messenger decision.

**Acceptance Criteria**

Applicability is approved.

### L10-06.09-002 — Configure Facebook Messenger

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | CONDITIONAL |

**Description**

Configure the approved Facebook Messenger integration.

**Dependencies**

- L10-06.09-001

**Deliverable**

Facebook Messenger configuration.

**Acceptance Criteria**

Channel is available for testing.

### L10-06.09-003 — Validate Facebook Messenger

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Validate message ingress, routing, agent handling, response and closure.

**Dependencies**

- L10-06.09-002

**Deliverable**

Validation evidence.

**Acceptance Criteria**

Approved scenarios pass.

### L10-06.09-004 — Activate Facebook Messenger

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P10 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | CONDITIONAL |

**Description**

Activate the production channel.

**Dependencies**

- L10-06.09-003

**Deliverable**

Production Facebook Messenger capability.

**Acceptance Criteria**

Production interactions operate correctly.

## Definition of Done

Facebook Messenger is operational, tested and supported where applicable.

---

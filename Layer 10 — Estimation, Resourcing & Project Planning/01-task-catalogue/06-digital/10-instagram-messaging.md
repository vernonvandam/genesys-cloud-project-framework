# Layer 10 — 2.06.10 Instagram Messaging

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 06 — Digital |
| Capability ID | 2.06.10 |
| Capability | Instagram Messaging |
| Task Catalogue ID | 06.10 |
| Primary Layer 1 Phases | P03, P04, P06, P07, P08, P10, P11 |

## Capability Objective

Implement Instagram messaging where supported and required by the customer channel strategy.

## Implementation Tasks

### L10-06.10-001 — Confirm Instagram Messaging Requirements

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | CONDITIONAL |

**Description**

Confirm business account, use cases, ownership and moderation requirements.

**Dependencies**

- Digital channel strategy

**Deliverable**

Instagram messaging requirements.

**Acceptance Criteria**

Requirements are approved.

### L10-06.10-002 — Configure Instagram Messaging

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

Configure the supported Instagram messaging capability.

**Dependencies**

- L10-06.10-001

**Deliverable**

Instagram configuration.

**Acceptance Criteria**

Messaging is available for testing.

### L10-06.10-003 — Validate Instagram Messaging

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

Validate customer messaging, routing, agent handling and closure.

**Dependencies**

- L10-06.10-002

**Deliverable**

Test evidence.

**Acceptance Criteria**

Approved scenarios pass.

### L10-06.10-004 — Activate Instagram Messaging

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

Activate the approved production channel.

**Dependencies**

- L10-06.10-003

**Deliverable**

Production Instagram messaging.

**Acceptance Criteria**

Production messaging works successfully.

## Definition of Done

Instagram messaging is configured, tested and operational where applicable.

---
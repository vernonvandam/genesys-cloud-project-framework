# Layer 10 — 2.06.11 Apple Messages for Business

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 06 — Digital |
| Capability ID | 2.06.11 |
| Capability | Apple Messages for Business |
| Task Catalogue ID | 06.11 |
| Primary Layer 1 Phases | P03, P04, P06, P07, P08, P10, P11 |

## Capability Objective

Implement Apple Messages for Business where required and supported.

## Implementation Tasks

### L10-06.11-001 — Define Apple Messages Requirements

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Define business identity, entry points, journeys, routing, escalation and operational requirements.

**Dependencies**

- Digital channel strategy

**Deliverable**

Apple Messages requirements.

**Acceptance Criteria**

Requirements are approved.

### L10-06.11-002 — Configure Apple Messages Integration

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

Configure the supported Apple messaging integration.

**Dependencies**

- L10-06.11-001

**Deliverable**

Configured channel.

**Acceptance Criteria**

Channel is available for testing.

### L10-06.11-003 — Validate Apple Messages Journey

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

Validate customer entry, routing, agent handling and escalation.

**Dependencies**

- L10-06.11-002

**Deliverable**

Validation evidence.

**Acceptance Criteria**

Approved scenarios pass.

### L10-06.11-004 — Activate Apple Messages

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

- L10-06.11-003

**Deliverable**

Production channel.

**Acceptance Criteria**

Production interactions operate successfully.

## Definition of Done

Apple Messages for Business is configured, validated and operational where applicable.

---

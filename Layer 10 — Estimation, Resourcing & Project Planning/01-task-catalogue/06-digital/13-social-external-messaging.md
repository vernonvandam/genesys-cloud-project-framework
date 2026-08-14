# Layer 10 — 2.06.13 Social & External Messaging

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 06 — Digital |
| Capability ID | 2.06.13 |
| Capability | Social & External Messaging |
| Task Catalogue ID | 06.13 |
| Primary Layer 1 Phases | P02, P03, P04, P06, P07, P08, P09, P10, P11 |

## Capability Objective

Provide a common implementation framework for social and external messaging channels.

## Implementation Tasks

### L10-06.13-001 — Inventory Social Channels

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P02 |
| Primary Role | Business Analyst |
| Customer Responsibility | YES |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Identify existing social and external messaging channels, owners, account dependencies and business use cases.

**Dependencies**

- Digital channel strategy

**Deliverable**

Social channel inventory.

**Acceptance Criteria**

Inventory is complete.

### L10-06.13-002 — Define Social Channel Governance

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Define ownership, moderation, privacy, security, escalation and support.

**Dependencies**

- L10-06.13-001

**Deliverable**

Social channel governance model.

**Acceptance Criteria**

Governance is approved.

### L10-06.13-003 — Configure Social Messaging Integration

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Integration Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | CONDITIONAL |

**Description**

Configure applicable social messaging integrations.

**Dependencies**

- L10-06.13-002

**Deliverable**

Configured social channel.

**Acceptance Criteria**

Channel is available for testing.

### L10-06.13-004 — Validate Social Messaging

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | CONDITIONAL |

**Description**

Validate inbound messages, routing, moderation, responses, escalation and closure.

**Dependencies**

- L10-06.13-003

**Deliverable**

Social messaging validation.

**Acceptance Criteria**

Approved scenarios pass.

## Definition of Done

Applicable social channels are governed, integrated, tested and operationally supported.

---

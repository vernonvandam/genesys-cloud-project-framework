# Layer 10 — 2.06.07 Open Messaging

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 06 — Digital |
| Capability ID | 2.06.07 |
| Capability | Open Messaging |
| Task Catalogue ID | 06.07 |
| Primary Layer 1 Phases | P03, P04, P06, P07, P08, P10, P11 |

## Capability Objective

Implement Open Messaging for supported external messaging experiences.

## Implementation Tasks

### L10-06.07-001 — Define Open Messaging Requirements

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

Define supported channel, customer journey, identity, routing, integration and operational requirements.

**Dependencies**

- Digital architecture

**Deliverable**

Open Messaging requirements.

**Acceptance Criteria**

Requirements approved.

### L10-06.07-002 — Configure Open Messaging

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

Configure Open Messaging integration and channel behaviour.

**Dependencies**

- L10-06.07-001

**Deliverable**

Open Messaging configuration.

**Acceptance Criteria**

Channel can initiate test interactions.

### L10-06.07-003 — Validate Open Messaging Integration

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Integration Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | CONDITIONAL |

**Description**

Validate message ingress, routing, context, agent handling, responses and failure scenarios.

**Dependencies**

- L10-06.07-002

**Deliverable**

Integration test evidence.

**Acceptance Criteria**

End-to-end scenarios pass.

### L10-06.07-004 — Activate Open Messaging

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

Activate the approved Open Messaging channel.

**Dependencies**

- L10-06.07-003

**Deliverable**

Production Open Messaging service.

**Acceptance Criteria**

Production interactions operate successfully.

## Definition of Done

Open Messaging is configured, integrated, validated and operational where required.

---
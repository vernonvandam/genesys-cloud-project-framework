# Layer 10 — 2.06.05 Web Chat

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 06 — Digital |
| Capability ID | 2.06.05 |
| Capability | Web Chat |
| Task Catalogue ID | 06.05 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P10, P11 |

## Capability Objective

Implement web chat where required and support the associated customer journey, routing and agent handling.

## Implementation Tasks

### L10-06.05-001 — Confirm Web Chat Applicability

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | CONDITIONAL |

**Description**

Determine whether web chat is required or whether web messaging provides the target capability.

**Dependencies**

- Digital channel strategy

**Deliverable**

Web chat decision.

**Acceptance Criteria**

Decision is documented and approved.

### L10-06.05-002 — Configure Web Chat

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

Configure applicable web chat settings, routing and customer experience.

**Dependencies**

- L10-06.05-001

**Deliverable**

Web chat configuration.

**Acceptance Criteria**

Web chat is available for testing.

### L10-06.05-003 — Test Web Chat Journey

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

Test entry, routing, agent handling, transfer and closure.

**Dependencies**

- L10-06.05-002

**Deliverable**

Web chat test evidence.

**Acceptance Criteria**

Approved scenarios pass.

### L10-06.05-004 — Activate Web Chat

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

Activate web chat after successful testing and approval.

**Dependencies**

- L10-06.05-003

**Deliverable**

Production web chat.

**Acceptance Criteria**

Production journey operates successfully.

## Definition of Done

Where applicable, web chat is configured, tested and operational.

---
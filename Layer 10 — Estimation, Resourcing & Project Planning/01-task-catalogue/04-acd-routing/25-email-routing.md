# Layer 10 — 2.04.25 Email Routing

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 04 — ACD & Routing |
| Capability ID | 2.04.25 |
| Capability | Email Routing |
| Task Catalogue ID | 04.25 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P09, P10 |

## Capability Objective

Configure inbound email routing to appropriate queues and agents.

## Source Implementation Activities

1. Define email routing requirements.
2. Map addresses to queues.
3. Configure email routing.
4. Validate email delivery.

## Implementation Tasks

### L10-04.25-001 — Define Email Routing Requirements

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | CONDITIONAL |

**Description**

Define email addresses, queues, routing rules, priorities and business ownership.

**Dependencies**

- Digital architecture
- Queue architecture

**Deliverable**

Email routing matrix.

**Acceptance Criteria**

Email routing requirements are approved.

### L10-04.25-002 — Configure Email Routing

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h per address |
| Critical Path | CONDITIONAL |

**Description**

Configure inbound email addresses and routing to queues.

**Dependencies**

- L10-04.25-001

**Deliverable**

Configured email routing.

**Acceptance Criteria**

Inbound email enters the intended queue.

### L10-04.25-003 — Validate Email Routing

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h per address |
| Critical Path | CONDITIONAL |

**Description**

Validate inbound email routing, queueing, agent delivery and exception behaviour.

**Dependencies**

- L10-04.25-002

**Deliverable**

Email routing test evidence.

**Acceptance Criteria**

Email scenarios pass.

## Definition of Done

Email routing is configured and validated where applicable.

---

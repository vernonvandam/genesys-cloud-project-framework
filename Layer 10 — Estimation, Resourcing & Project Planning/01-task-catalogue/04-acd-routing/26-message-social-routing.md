# Layer 10 — 2.04.26 Message & Social Routing

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 04 — ACD & Routing |
| Capability ID | 2.04.26 |
| Capability | Message & Social Routing |
| Task Catalogue ID | 04.26 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P09, P10 |

## Capability Objective

Route supported messaging and social interactions through the appropriate digital ACD model.

## Source Implementation Activities

1. Identify messaging channels.
2. Define routing rules.
3. Configure channel routing.
4. Validate interaction delivery.

## Implementation Tasks

### L10-04.26-001 — Define Messaging and Social Routing Requirements

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

Identify supported messaging and social channels and define routing requirements.

**Dependencies**

- Digital channel strategy
- Queue architecture

**Deliverable**

Messaging routing matrix.

**Acceptance Criteria**

Channel routing requirements are approved.

### L10-04.26-002 — Configure Message and Social Routing

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h per channel |
| Critical Path | CONDITIONAL |

**Description**

Configure messaging and social interactions to route through approved queues.

**Dependencies**

- L10-04.26-001

**Deliverable**

Configured routing.

**Acceptance Criteria**

Interactions route correctly.

### L10-04.26-003 — Validate Messaging and Social Routing

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h per channel |
| Critical Path | CONDITIONAL |

**Description**

Validate queueing, agent delivery and exception handling.

**Dependencies**

- L10-04.26-002

**Deliverable**

Routing validation evidence.

**Acceptance Criteria**

All applicable channel scenarios pass.

## Definition of Done

Messaging and social routing is configured and validated where required.

---
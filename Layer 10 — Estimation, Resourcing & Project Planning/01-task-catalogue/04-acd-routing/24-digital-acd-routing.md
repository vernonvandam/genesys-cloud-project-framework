# Layer 10 — 2.04.24 Digital ACD Routing

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 04 — ACD & Routing |
| Capability ID | 2.04.24 |
| Capability | Digital ACD Routing |
| Task Catalogue ID | 04.24 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P09, P10, P11 |

## Capability Objective

Route digital interactions into the correct queues and agents using the approved digital channel strategy.

## Source Implementation Activities

1. Define digital routing requirements.
2. Map digital channels to queues.
3. Configure digital ACD routing.
4. Validate digital delivery.

## Implementation Tasks

### L10-04.24-001 — Define Digital Routing Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Define digital routing requirements for supported digital channels.

**Dependencies**

- Digital architecture
- Queue architecture

**Deliverable**

Digital routing matrix.

**Acceptance Criteria**

Routing requirements are approved.

### L10-04.24-002 — Configure Digital ACD Routing

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h per channel/routing model |
| Critical Path | YES |

**Description**

Configure digital interactions to route through the approved queues and agent-selection model.

**Dependencies**

- L10-04.24-001

**Deliverable**

Configured digital routing.

**Acceptance Criteria**

Digital interactions enter the intended routing model.

### L10-04.24-003 — Validate Digital Routing

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.5h per channel |
| Critical Path | YES |

**Description**

Validate digital queueing, routing, agent delivery and exception handling.

**Dependencies**

- L10-04.24-002

**Deliverable**

Digital routing validation.

**Acceptance Criteria**

All required digital routing scenarios pass.

## Definition of Done

Digital ACD routing is implemented and validated.

---

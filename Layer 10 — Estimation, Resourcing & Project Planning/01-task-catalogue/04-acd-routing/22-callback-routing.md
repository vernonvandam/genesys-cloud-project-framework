# Layer 10 — 2.04.22 Callback Routing

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 04 — ACD & Routing |
| Capability ID | 2.04.22 |
| Capability | Callback Routing |
| Task Catalogue ID | 04.22 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P09, P10 |

## Capability Objective

Provide callback functionality that preserves routing intent while allowing customers to avoid waiting in queue.

## Source Implementation Activities

1. Define callback requirements.
2. Define callback routing.
3. Configure callback behaviour.
4. Validate callback scenarios.

## Implementation Tasks

### L10-04.22-001 — Define Callback Requirements

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

Define queues, channels, operating conditions and customer experience for callbacks.

**Dependencies**

- In-queue experience

**Deliverable**

Callback requirements.

**Acceptance Criteria**

Callback requirements are approved.

### L10-04.22-002 — Design Callback Routing

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | CONDITIONAL |

**Description**

Define callback routing, queue association, scheduling and failure behaviour.

**Dependencies**

- L10-04.22-001

**Deliverable**

Callback design.

**Acceptance Criteria**

Callback design is approved.

### L10-04.22-003 — Configure Callback Routing

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.5h per queue |
| Critical Path | CONDITIONAL |

**Description**

Configure approved callback behaviour.

**Dependencies**

- L10-04.22-002

**Deliverable**

Configured callbacks.

**Acceptance Criteria**

Callback requests are created and routed correctly.

### L10-04.22-004 — Validate Callback Scenarios

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.5h per queue |
| Critical Path | CONDITIONAL |

**Description**

Test callback creation, scheduling, routing, completion and failure scenarios.

**Dependencies**

- L10-04.22-003

**Deliverable**

Callback validation evidence.

**Acceptance Criteria**

Callback scenarios pass.

## Definition of Done

Callback routing is configured and validated where required.

---

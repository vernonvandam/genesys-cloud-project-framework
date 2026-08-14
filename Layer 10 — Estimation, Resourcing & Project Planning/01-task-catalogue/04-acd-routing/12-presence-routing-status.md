# Layer 10 — 2.04.12 Presence Routing & Status

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 04 — ACD & Routing |
| Capability ID | 2.04.12 |
| Capability | Presence Routing & Status |
| Task Catalogue ID | 04.12 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P10 |

## Capability Objective

Ensure agent presence and status behaviour correctly controls routing eligibility and operational availability.

## Source Implementation Activities

1. Define presence requirements.
2. Map presence to routing behaviour.
3. Configure status requirements.
4. Validate routing eligibility.

## Implementation Tasks

### L10-04.12-001 — Define Presence Routing Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Define how presence and agent status affect routing eligibility.

**Dependencies**

- Routing strategy

**Deliverable**

Presence routing requirements.

**Acceptance Criteria**

Presence behaviour is approved.

### L10-04.12-002 — Configure Presence and Status Behaviour

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Configure applicable presence, status and routing behaviour.

**Dependencies**

- L10-04.12-001

**Deliverable**

Presence configuration.

**Acceptance Criteria**

Presence and status behave as designed.

### L10-04.12-003 — Validate Presence-Based Routing

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Validate routing eligibility across expected agent statuses.

**Dependencies**

- L10-04.12-002

**Deliverable**

Presence routing test evidence.

**Acceptance Criteria**

Interactions are not routed to unavailable agents.

## Definition of Done

Presence and status routing is configured and validated.

---

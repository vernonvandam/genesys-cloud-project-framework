# Layer 10 — 2.04.19 Overflow & Alternate Routing

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 04 — ACD & Routing |
| Capability ID | 2.04.19 |
| Capability | Overflow & Alternate Routing |
| Task Catalogue ID | 04.19 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P09, P10, P11 |

## Capability Objective

Provide controlled routing alternatives when primary routing conditions cannot be met.

## Source Implementation Activities

1. Identify overflow conditions.
2. Define alternate destinations.
3. Configure overflow behaviour.
4. Validate exception routing.

## Implementation Tasks

### L10-04.19-001 — Define Overflow Conditions

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

Define conditions triggering overflow or alternate routing.

**Dependencies**

- Routing strategy

**Deliverable**

Overflow rule matrix.

**Acceptance Criteria**

Conditions are approved.

### L10-04.19-002 — Define Alternate Routing Destinations

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Define alternate queues, groups, channels or destinations.

**Dependencies**

- L10-04.19-001

**Deliverable**

Alternate routing design.

**Acceptance Criteria**

Fallback destinations are approved.

### L10-04.19-003 — Configure Overflow Routing

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.5h per routing model |
| Critical Path | YES |

**Description**

Configure approved overflow and alternate routing.

**Dependencies**

- L10-04.19-002

**Deliverable**

Configured overflow routing.

**Acceptance Criteria**

Overflow conditions route to approved destinations.

### L10-04.19-004 — Validate Overflow Scenarios

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.5h per routing model |
| Critical Path | YES |

**Description**

Test all overflow and alternate routing scenarios.

**Dependencies**

- L10-04.19-003

**Deliverable**

Overflow test evidence.

**Acceptance Criteria**

All defined overflow scenarios pass.

## Definition of Done

Overflow and alternate routing is configured and validated.

---
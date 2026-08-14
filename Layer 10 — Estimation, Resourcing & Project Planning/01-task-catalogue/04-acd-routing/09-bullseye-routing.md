# Layer 10 — 2.04.09 Bullseye Routing

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 04 — ACD & Routing |
| Capability ID | 2.04.09 |
| Capability | Bullseye Routing |
| Task Catalogue ID | 04.09 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P09 |

## Capability Objective

Configure progressive routing expansion where the initial agent pool is broadened according to defined timing and eligibility criteria.

## Source Implementation Activities

1. Identify bullseye requirements.
2. Define routing rings.
3. Configure expansion behaviour.
4. Validate ring progression.

## Implementation Tasks

### L10-04.09-001 — Define Bullseye Routing Requirements

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

Identify queues requiring progressive routing expansion.

**Dependencies**

- Routing strategy

**Deliverable**

Bullseye requirements.

**Acceptance Criteria**

Applicable queues are approved.

### L10-04.09-002 — Define Bullseye Rings

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P04 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | CONDITIONAL |

**Description**

Define agent pools, skill criteria and timing for each routing ring.

**Dependencies**

- L10-04.09-001

**Deliverable**

Bullseye routing design.

**Acceptance Criteria**

Ring design is approved.

### L10-04.09-003 — Configure Bullseye Routing

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.5h per routing model |
| Critical Path | CONDITIONAL |

**Description**

Configure progressive routing expansion.

**Dependencies**

- L10-04.09-002

**Deliverable**

Configured bullseye routing.

**Acceptance Criteria**

Routing rings expand according to design.

### L10-04.09-004 — Validate Bullseye Progression

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h per routing model |
| Critical Path | CONDITIONAL |

**Description**

Test routing progression across all configured rings.

**Dependencies**

- L10-04.09-003

**Deliverable**

Bullseye validation evidence.

**Acceptance Criteria**

All routing rings operate as designed.

## Definition of Done

Bullseye routing is configured and validated where required.

---
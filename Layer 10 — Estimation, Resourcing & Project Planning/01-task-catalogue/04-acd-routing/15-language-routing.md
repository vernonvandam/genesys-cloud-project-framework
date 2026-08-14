# Layer 10 — 2.04.15 Language Routing

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 04 — ACD & Routing |
| Capability ID | 2.04.15 |
| Capability | Language Routing |
| Task Catalogue ID | 04.15 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P09 |

## Capability Objective

Route interactions according to required language capability.

## Source Implementation Activities

1. Identify language requirements.
2. Define language routing model.
3. Configure language skills.
4. Validate language routing.

## Implementation Tasks

### L10-04.15-001 — Identify Language Requirements

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

Identify languages required by business process and customer population.

**Dependencies**

- Business requirements

**Deliverable**

Language requirement matrix.

**Acceptance Criteria**

Required languages are approved.

### L10-04.15-002 — Define Language Routing Model

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

Define how language requirements will be represented and used for routing.

**Dependencies**

- L10-04.15-001

**Deliverable**

Language routing design.

**Acceptance Criteria**

Design is approved.

### L10-04.15-003 — Configure Language Routing

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.5h per language model |
| Critical Path | CONDITIONAL |

**Description**

Configure language skills and routing requirements.

**Dependencies**

- L10-04.15-002

**Deliverable**

Language routing configuration.

**Acceptance Criteria**

Interactions requiring a language are routed appropriately.

### L10-04.15-004 — Validate Language Routing

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h per language model |
| Critical Path | CONDITIONAL |

**Description**

Validate language routing and fallback behaviour.

**Dependencies**

- L10-04.15-003

**Deliverable**

Language routing test evidence.

**Acceptance Criteria**

Language routing and fallback scenarios pass.

## Definition of Done

Language routing is configured and validated where required.

---
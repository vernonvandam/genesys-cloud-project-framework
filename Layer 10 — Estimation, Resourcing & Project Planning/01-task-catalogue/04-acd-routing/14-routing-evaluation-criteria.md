# Layer 10 — 2.04.14 Routing Evaluation Criteria

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 04 — ACD & Routing |
| Capability ID | 2.04.14 |
| Capability | Routing Evaluation Criteria |
| Task Catalogue ID | 04.14 |
| Primary Layer 1 Phases | P03, P04, P06, P08 |

## Capability Objective

Define the criteria used to evaluate eligible agents when selecting the best routing destination.

## Source Implementation Activities

1. Define evaluation criteria.
2. Map criteria to routing models.
3. Configure evaluation behaviour.
4. Validate agent selection.

## Implementation Tasks

### L10-04.14-001 — Define Evaluation Criteria

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

Define criteria used to compare eligible agents.

**Dependencies**

- Routing strategy

**Deliverable**

Evaluation criteria matrix.

**Acceptance Criteria**

Criteria are approved.

### L10-04.14-002 — Configure Evaluation Criteria

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h per routing model |
| Critical Path | YES |

**Description**

Configure the approved evaluation behaviour.

**Dependencies**

- L10-04.14-001

**Deliverable**

Configured evaluation logic.

**Acceptance Criteria**

Routing evaluation reflects approved criteria.

### L10-04.14-003 — Validate Agent Selection

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Test agent selection when multiple agents are eligible.

**Dependencies**

- L10-04.14-002

**Deliverable**

Agent selection validation.

**Acceptance Criteria**

Expected agent-selection outcomes are demonstrated.

## Definition of Done

Routing evaluation criteria are implemented and validated.

---
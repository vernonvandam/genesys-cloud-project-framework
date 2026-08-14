# Layer 10 — 2.04.11 Agent Utilisation & Capacity

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 04 — ACD & Routing |
| Capability ID | 2.04.11 |
| Capability | Agent Utilisation & Capacity |
| Task Catalogue ID | 04.11 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P09, P10 |

## Capability Objective

Define how agent capacity, concurrency and utilisation influence routing decisions and operational performance.

## Source Implementation Activities

1. Define capacity requirements.
2. Identify concurrency constraints.
3. Configure capacity behaviour.
4. Validate agent utilisation impacts.

## Implementation Tasks

### L10-04.11-001 — Define Agent Capacity Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Workforce Management Lead |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Define expected agent capacity and interaction concurrency requirements.

**Dependencies**

- Routing strategy
- WFM requirements

**Deliverable**

Agent capacity model.

**Acceptance Criteria**

Capacity assumptions are approved.

### L10-04.11-002 — Configure Capacity Behaviour

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h per configuration group |
| Critical Path | CONDITIONAL |

**Description**

Configure applicable capacity and concurrency behaviour.

**Dependencies**

- L10-04.11-001

**Deliverable**

Capacity configuration.

**Acceptance Criteria**

Configured behaviour matches the approved model.

### L10-04.11-003 — Validate Capacity-Based Routing

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | CONDITIONAL |

**Description**

Validate routing when agents have differing capacity and active interactions.

**Dependencies**

- L10-04.11-002

**Deliverable**

Capacity validation evidence.

**Acceptance Criteria**

Agent capacity limits and routing outcomes operate as designed.

## Definition of Done

Capacity behaviour is defined, configured where required and validated.

---

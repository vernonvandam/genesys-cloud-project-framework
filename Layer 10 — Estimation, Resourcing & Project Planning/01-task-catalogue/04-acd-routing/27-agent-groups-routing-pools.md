# Layer 10 — 2.04.27 Agent Groups & Routing Pools

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 04 — ACD & Routing |
| Capability ID | 2.04.27 |
| Capability | Agent Groups & Routing Pools |
| Task Catalogue ID | 04.27 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P10 |

## Capability Objective

Define and configure logical groups of agents used by routing strategies.

## Source Implementation Activities

1. Identify routing pools.
2. Define pool membership.
3. Configure groups.
4. Validate routing pools.

## Implementation Tasks

### L10-04.27-001 — Define Agent Group Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Identify agent groups required for routing, business units, skills and operational ownership.

**Dependencies**

- Queue architecture
- Agent population

**Deliverable**

Agent group matrix.

**Acceptance Criteria**

Required groups are approved.

### L10-04.27-002 — Configure Routing Pools

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 0.5h per group |
| Critical Path | YES |

**Description**

Create groups and configure routing relationships.

**Dependencies**

- L10-04.27-001

**Deliverable**

Configured routing pools.

**Acceptance Criteria**

Groups exist with correct membership.

### L10-04.27-003 — Validate Agent Group Routing

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h per routing model |
| Critical Path | YES |

**Description**

Validate that routing correctly uses configured agent groups.

**Dependencies**

- L10-04.27-002

**Deliverable**

Agent group validation evidence.

**Acceptance Criteria**

Routing uses the intended agent pools.

## Definition of Done

Agent groups and routing pools are configured and validated.

---

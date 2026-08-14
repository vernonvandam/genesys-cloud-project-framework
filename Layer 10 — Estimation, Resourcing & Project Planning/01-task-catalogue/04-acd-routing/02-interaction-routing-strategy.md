# Layer 10 — 2.04.02 Interaction Routing Strategy

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 04 — ACD & Routing |
| Capability ID | 2.04.02 |
| Capability | Interaction Routing Strategy |
| Task Catalogue ID | 04.02 |
| Primary Layer 1 Phases | P01, P02, P03, P04, P06, P08, P09, P10 |

## Capability Objective

Define how interactions are selected, prioritised and delivered to appropriate agents across supported channels.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P01 | Confirm business routing objectives |
| P02 | Assess existing routing behaviour |
| P03 | Define routing rules |
| P04 | Design target routing strategy |
| P06 | Configure routing behaviour |
| P08 | Test routing outcomes |
| P09 | Obtain business acceptance |
| P10 | Confirm production readiness |

## Source Implementation Activities

1. Define routing objectives.
2. Document routing rules.
3. Define agent-selection strategy.
4. Configure routing behaviour.
5. Validate routing outcomes.

## Implementation Tasks

### Activity 01 — Define Strategy

#### L10-04.02-001 — Confirm Routing Objectives

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P01 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Confirm service-level, skill, priority, customer-experience and operational objectives.

**Dependencies**

- Business requirements

**Deliverable**

Routing objectives.

**Acceptance Criteria**

Objectives are approved.

#### L10-04.02-002 — Define Routing Rules

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define rules determining how interactions enter queues and select eligible agents.

**Dependencies**

- L10-04.02-001

**Deliverable**

Routing rule catalogue.

**Acceptance Criteria**

Rules are complete and approved.

### Activity 02 — Configure Strategy

#### L10-04.02-003 — Configure Routing Strategy

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Implement approved routing rules and agent-selection behaviour.

**Dependencies**

- L10-04.02-002
- Queue configuration
- Skills configuration

**Deliverable**

Configured routing strategy.

**Acceptance Criteria**

Configured routing produces expected outcomes.

### Activity 03 — Validate

#### L10-04.02-004 — Execute Routing Strategy Validation

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate routing decisions across normal and exception scenarios.

**Dependencies**

- L10-04.02-003

**Deliverable**

Routing validation evidence.

**Acceptance Criteria**

Expected routing outcomes are demonstrated.

## Capability-Level Dependencies

- Queue architecture
- Skills
- Agent configuration
- Architect flows
- Channel configuration

## Capability-Level Estimation Considerations

Complexity increases with:

- number of routing rules
- channel diversity
- skill combinations
- priority rules
- exception scenarios

## Definition of Done

Approved routing strategy is configured, tested and accepted.

---

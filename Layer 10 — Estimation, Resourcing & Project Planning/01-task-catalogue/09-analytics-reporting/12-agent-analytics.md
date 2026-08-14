# Layer 10 — 2.09.12 Agent Analytics

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 09 — Analytics, Reporting & Data Visualisation |
| Capability ID | 2.09.12 |
| Capability | Agent Analytics |
| Task Catalogue ID | 09.12 |
| Primary Layer 1 Phases | P03, P04, P06, P08 |

## Capability Objective

Provide agent-level analytics supporting performance, productivity, state, interaction and coaching requirements.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define agent reporting requirements |
| P04 | Design agent analytics |
| P06 | Configure reporting |
| P08 | Validate results |

## Source Implementation Activities

1. Define agent metrics.
2. Define access requirements.
3. Configure agent analytics.
4. Validate reporting.

## Implementation Tasks

### Activity 01 — Requirements

#### L10-09-12-001 — Define Agent Analytics Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Define required agent performance and productivity measures.

**Dependencies**

- L10-09-02-002

**Deliverable**

Agent analytics requirements.

**Acceptance Criteria**

Agent measures and reporting consumers are approved.

### Activity 02 — Configure

#### L10-09-12-002 — Configure Agent Analytics

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Configure agent-level analytics and reporting.

**Dependencies**

- L10-09-12-001

**Deliverable**

Agent analytics configuration.

**Acceptance Criteria**

Required agent metrics are available.

### Activity 03 — Validation

#### L10-09-12-003 — Validate Agent Analytics

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Analyst |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Validate agent metrics and access behaviour.

**Dependencies**

- L10-09-12-002

**Deliverable**

Agent analytics validation evidence.

**Acceptance Criteria**

Agent metrics and access controls pass validation.

## Capability-Level Dependencies

- Identity and access
- Users
- Queues
- ACD
- KPI framework

## Capability-Level Estimation Considerations

Effort depends on agent population, metric complexity and reporting access model.

## Definition of Done

Agent analytics are configured, validated and access-controlled.
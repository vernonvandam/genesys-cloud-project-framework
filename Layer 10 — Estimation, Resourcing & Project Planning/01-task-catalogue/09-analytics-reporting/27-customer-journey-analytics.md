# Layer 10 — 2.09.27 Customer Journey Analytics

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 09 — Analytics, Reporting & Data Visualisation |
| Capability ID | 2.09.27 |
| Capability | Customer Journey Analytics |
| Task Catalogue ID | 09.27 |
| Primary Layer 1 Phases | P03, P04, P06, P07, P08 |

## Capability Objective

Analyse customer journeys across channels, interactions, outcomes and enterprise touchpoints.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define journey analytics |
| P04 | Design journey model |
| P06 | Configure analytics |
| P07 | Integrate external journey data |
| P08 | Validate journey reporting |

## Source Implementation Activities

1. Define journey use cases.
2. Identify interaction sources.
3. Design journey model.
4. Configure reporting.
5. Validate journey analytics.

## Implementation Tasks

### Activity 01 — Requirements

#### L10-09-27-001 — Define Customer Journey Analytics Use Cases

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | CX Consultant |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | NO |

**Description**

Define customer journey analysis use cases and required outcomes.

**Dependencies**

- L10-09-02-002

**Deliverable**

Journey analytics requirements.

**Acceptance Criteria**

Journey use cases are approved.

### Activity 02 — Design

#### L10-09-27-002 — Design Customer Journey Model

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 5.0h |
| Critical Path | NO |

**Description**

Define journey stages, events, identifiers and data sources.

**Dependencies**

- L10-09-27-001

**Deliverable**

Journey analytics design.

**Acceptance Criteria**

Journey model is approved.

### Activity 03 — Integration

#### L10-09-27-003 — Integrate Journey Data Sources

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P07 |
| Primary Role | Data Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | CONDITIONAL |
| Baseline Effort | 5.0h |
| Critical Path | NO |

**Description**

Integrate required external journey data.

**Dependencies**

- L10-09-27-002

**Deliverable**

Journey data integration.

**Acceptance Criteria**

Required journey data is available.

### Activity 04 — Validation

#### L10-09-27-004 — Validate Customer Journey Analytics

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Analyst |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | NO |

**Description**

Validate journey analytics against approved journey scenarios.

**Dependencies**

- L10-09-27-003

**Deliverable**

Journey validation evidence.

**Acceptance Criteria**

Journey events and outcomes are correctly represented.

## Capability-Level Dependencies

- Digital
- Voice
- CRM
- Data integration
- Customer identity

## Capability-Level Estimation Considerations

Effort can be substantial where journey analysis spans multiple enterprise platforms.

## Definition of Done

Customer journey analytics are implemented and validated where required.
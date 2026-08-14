# Layer 10 — 2.09.04 Contact Centre Measurement Model

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 09 — Analytics, Reporting & Data Visualisation |
| Capability ID | 2.09.04 |
| Capability | Contact Centre Measurement Model |
| Task Catalogue ID | 09.04 |
| Primary Layer 1 Phases | P03, P04, P06, P08 |

## Capability Objective

Define the measurement model used to assess contact centre performance across service, productivity, customer experience and workforce dimensions.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define business measures |
| P04 | Design measurement model |
| P06 | Implement measurements |
| P08 | Validate measures |

## Source Implementation Activities

1. Define measurement categories.
2. Define metrics.
3. Map data sources.
4. Configure reporting.
5. Validate results.

## Implementation Tasks

### Activity 01 — Measurement Categories

#### L10-09-04-001 — Define Contact Centre Measurement Categories

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define service, productivity, customer experience, workforce and quality measurement categories.

**Dependencies**

- L10-09-03-001

**Deliverable**

Measurement category model.

**Acceptance Criteria**

Measurement categories are approved.

### Activity 02 — Metric Mapping

#### L10-09-04-002 — Map Metrics to Measurement Model

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Map approved KPIs to the contact centre measurement model.

**Dependencies**

- L10-09-04-001

**Deliverable**

Measurement model.

**Acceptance Criteria**

All required measures are mapped.

### Activity 03 — Reporting

#### L10-09-04-003 — Implement Measurement Reporting

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

Implement reporting views supporting the approved measurement model.

**Dependencies**

- L10-09-04-002

**Deliverable**

Measurement reporting.

**Acceptance Criteria**

Required measures are available in target reporting.

### Activity 04 — Validation

#### L10-09-04-004 — Validate Measurement Model

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

Validate calculations, source data and business interpretation.

**Dependencies**

- L10-09-04-003

**Deliverable**

Measurement validation evidence.

**Acceptance Criteria**

Measures reconcile to agreed business definitions.

## Capability-Level Dependencies

- KPI framework
- Reporting requirements
- ACD configuration
- WFM requirements
- Quality requirements

## Capability-Level Estimation Considerations

Effort depends on metric complexity and the number of operational and business measures.

## Definition of Done

The contact centre measurement model is implemented, validated and approved.
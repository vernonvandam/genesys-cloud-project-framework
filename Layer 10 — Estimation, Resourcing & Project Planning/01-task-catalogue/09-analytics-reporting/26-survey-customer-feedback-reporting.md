# Layer 10 — 2.09.26 Survey & Customer Feedback Reporting

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 09 — Analytics, Reporting & Data Visualisation |
| Capability ID | 2.09.26 |
| Capability | Survey & Customer Feedback Reporting |
| Task Catalogue ID | 09.26 |
| Primary Layer 1 Phases | P03, P04, P06, P07, P08 |

## Capability Objective

Provide reporting on customer surveys, feedback, satisfaction and related experience measures.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define survey reporting |
| P04 | Design feedback model |
| P06 | Configure reporting |
| P07 | Integrate external survey data |
| P08 | Validate results |

## Source Implementation Activities

1. Define survey metrics.
2. Identify survey sources.
3. Configure reporting.
4. Integrate external feedback.
5. Validate results.

## Implementation Tasks

### Activity 01 — Requirements

#### L10-09-26-001 — Define Survey Reporting Requirements

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | CX Consultant |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Define customer feedback, satisfaction and survey reporting requirements.

**Dependencies**

- L10-09-02-002

**Deliverable**

Survey reporting requirements.

**Acceptance Criteria**

Survey requirements are approved.

### Activity 02 — Data Integration

#### L10-09-26-002 — Map Survey Data Sources

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P07 |
| Primary Role | Data Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Map Genesys Cloud and external survey data sources.

**Dependencies**

- L10-09-26-001

**Deliverable**

Survey data mapping.

**Acceptance Criteria**

Required survey sources are identified.

### Activity 03 — Configure

#### L10-09-26-003 — Configure Survey Reporting

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Configure survey and customer feedback reporting.

**Dependencies**

- L10-09-26-002

**Deliverable**

Survey reporting.

**Acceptance Criteria**

Required feedback metrics are available.

### Activity 04 — Validation

#### L10-09-26-004 — Validate Customer Feedback Reporting

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Analyst |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Validate survey data and customer feedback calculations.

**Dependencies**

- L10-09-26-003

**Deliverable**

Survey validation evidence.

**Acceptance Criteria**

Survey reporting reconciles to source data.

## Capability-Level Dependencies

- Digital
- Voice
- Survey platform
- Data integration

## Capability-Level Estimation Considerations

Effort depends on survey platform integration and data mapping complexity.

## Definition of Done

Survey and customer feedback reporting is configured and validated where required.
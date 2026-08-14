# Layer 10 — 2.09.16 ASA & Speed of Answer Analytics

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 09 — Analytics, Reporting & Data Visualisation |
| Capability ID | 2.09.16 |
| Capability | ASA & Speed of Answer Analytics |
| Task Catalogue ID | 09.16 |
| Primary Layer 1 Phases | P03, P04, P06, P08 |

## Capability Objective

Provide consistent average speed of answer analytics across required queues and reporting periods.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define ASA requirements |
| P04 | Define calculation |
| P06 | Configure analytics |
| P08 | Validate results |

## Source Implementation Activities

1. Define ASA calculation.
2. Configure ASA reporting.
3. Validate calculations.

## Implementation Tasks

### Activity 01 — Definition

#### L10-09-16-001 — Define ASA Calculation

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define approved average speed of answer calculation and exclusions.

**Dependencies**

- L10-09-03-001

**Deliverable**

ASA definition.

**Acceptance Criteria**

Calculation is approved.

### Activity 02 — Configure

#### L10-09-16-002 — Configure ASA Reporting

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

Configure ASA reporting.

**Dependencies**

- L10-09-16-001

**Deliverable**

ASA reporting.

**Acceptance Criteria**

ASA reporting is available.

### Activity 03 — Validate

#### L10-09-16-003 — Validate ASA Analytics

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Analyst |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate ASA calculations against source interaction data.

**Dependencies**

- L10-09-16-002

**Deliverable**

ASA validation evidence.

**Acceptance Criteria**

ASA calculations reconcile.

## Capability-Level Dependencies

- Queue analytics
- ACD
- KPI framework

## Capability-Level Estimation Considerations

Effort depends on queue count and required reporting dimensions.

## Definition of Done

ASA reporting is configured and validated.
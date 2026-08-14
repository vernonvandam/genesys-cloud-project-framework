# Layer 10 — 2.09.07 Data Quality & Reconciliation

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 09 — Analytics, Reporting & Data Visualisation |
| Capability ID | 2.09.07 |
| Capability | Data Quality & Reconciliation |
| Task Catalogue ID | 09.07 |
| Primary Layer 1 Phases | P04, P07, P08, P11 |

## Capability Objective

Ensure reporting data is complete, accurate, consistent and reconciled against authoritative sources.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P04 | Define quality model |
| P07 | Implement reconciliation |
| P08 | Validate data |
| P11 | Monitor production data |

## Source Implementation Activities

1. Define quality criteria.
2. Define reconciliation rules.
3. Implement controls.
4. Validate data.
5. Monitor production quality.

## Implementation Tasks

### Activity 01 — Quality Model

#### L10-09-07-001 — Define Analytics Data Quality Criteria

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Data Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Define completeness, accuracy, consistency, timeliness and validity criteria.

**Dependencies**

- L10-09-05-003

**Deliverable**

Data quality model.

**Acceptance Criteria**

Quality criteria are approved.

### Activity 02 — Reconciliation

#### L10-09-07-002 — Define Reporting Reconciliation Rules

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Data Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Define rules for reconciling critical metrics between source and reporting platforms.

**Dependencies**

- L10-09-07-001

**Deliverable**

Reconciliation specification.

**Acceptance Criteria**

Critical reporting measures have defined reconciliation rules.

### Activity 03 — Implementation

#### L10-09-07-003 — Implement Data Quality Controls

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P07 |
| Primary Role | Data Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | CONDITIONAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Implement agreed data quality and reconciliation controls.

**Dependencies**

- L10-09-07-002

**Deliverable**

Configured data quality controls.

**Acceptance Criteria**

Controls execute successfully.

### Activity 04 — Validation

#### L10-09-07-004 — Validate Reporting Data Quality

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Analyst |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Validate data quality and reconcile critical reporting results.

**Dependencies**

- L10-09-07-003

**Deliverable**

Data quality validation evidence.

**Acceptance Criteria**

Critical data quality controls pass.

## Capability-Level Dependencies

- Data source inventory
- KPI framework
- Data architecture
- External integrations

## Capability-Level Estimation Considerations

Complexity increases with external sources, historical data and reconciliation requirements.

## Definition of Done

Critical analytics data is quality-controlled, reconciled and validated.
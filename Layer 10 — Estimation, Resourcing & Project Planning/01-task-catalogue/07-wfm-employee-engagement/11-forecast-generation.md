# Layer 10 — 2.07.11 Forecast Generation

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 07 — Workforce Management & Employee Engagement |
| Capability ID | 2.07.11 |
| Capability | Forecast Generation |
| Task Catalogue ID | 07.11 |
| Primary Layer 1 Phases | P06, P08, P10, P11 |

## Capability Objective

Generate, review, approve and publish forecasts for operational workforce planning.

## Source Implementation Activities

1. Prepare forecast inputs.
2. Generate forecasts.
3. Review forecast outputs.
4. Apply approved adjustments.
5. Approve forecasts.

## Implementation Tasks

### Activity 01 — Prepare Forecast

#### L10-07.11-001 — Prepare Forecast Inputs

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Validate planning groups, historical data, forecast models and assumptions before generation.

**Dependencies**

- Forecast model
- Historical workload

**Deliverable**

Forecast-ready configuration.

**Acceptance Criteria**

All required forecast inputs are available.

#### L10-07.11-002 — Generate Forecast

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | WFM Consultant |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Generate the forecast for the approved planning horizon.

**Dependencies**

- L10-07.11-001

**Deliverable**

Generated forecast.

**Acceptance Criteria**

Forecast completes successfully.

### Activity 02 — Review and Approve

#### L10-07.11-003 — Review Forecast

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P08 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Review forecast outputs for anomalies, events, seasonality and operational assumptions.

**Dependencies**

- L10-07.11-002

**Deliverable**

Forecast review record.

**Acceptance Criteria**

Forecast is accepted or adjustments are documented.

#### L10-07.11-004 — Approve Production Forecast

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P10 |
| Primary Role | WFM Owner |
| Customer Responsibility | YES |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Approve the forecast for production workforce planning.

**Dependencies**

- L10-07.11-003

**Deliverable**

Approved production forecast.

**Acceptance Criteria**

Customer WFM owner approves the forecast.
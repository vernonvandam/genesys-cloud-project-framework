# Layer 10 — 2.07.09 Forecast Models

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 07 — Workforce Management & Employee Engagement |
| Capability ID | 2.07.09 |
| Capability | Forecast Models |
| Task Catalogue ID | 07.09 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P11, P15 |

## Capability Objective

Design, configure and validate the forecast models used to predict future workforce demand.

## Source Implementation Activities

1. Identify forecast model requirements.
2. Configure forecast models.
3. Apply assumptions.
4. Generate representative forecasts.
5. Validate accuracy and behaviour.

## Implementation Tasks

### Activity 01 — Define Forecast Model

#### L10-07.09-001 — Identify Forecast Model Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Determine forecast model requirements by channel, planning group, historical data and operational horizon.

**Dependencies**

- Forecasting strategy
- Planning groups

**Deliverable**

Forecast model requirements.

**Acceptance Criteria**

Model requirements are approved.

#### L10-07.09-002 — Configure Forecast Models

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Configure forecast models and approved assumptions.

**Dependencies**

- L10-07.09-001
- Historical data

**Deliverable**

Configured forecast models.

**Acceptance Criteria**

Models are available for forecast generation.

### Activity 02 — Validate Models

#### L10-07.09-003 — Generate Model Test Forecast

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Generate representative forecast outputs using configured models.

**Dependencies**

- L10-07.09-002

**Deliverable**

Test forecast.

**Acceptance Criteria**

Forecast is generated without configuration errors.

#### L10-07.09-004 — Validate Forecast Model Accuracy

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Compare forecast outputs against known demand and validate model suitability.

**Dependencies**

- L10-07.09-003

**Deliverable**

Forecast model validation report.

**Acceptance Criteria**

Model performance meets agreed acceptance thresholds.
# Layer 10 — 2.07.24 Intraday Management

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 07 — Workforce Management & Employee Engagement |
| Capability ID | 2.07.24 |
| Capability | Intraday Management |
| Task Catalogue ID | 07.24 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P09, P11 |

## Capability Objective

Define processes for managing real-time deviations between forecast, staffing and actual demand.

## Source Implementation Activities

1. Define intraday responsibilities.
2. Define exception thresholds.
3. Define corrective actions.
4. Configure operational views.
5. Validate intraday processes.

## Implementation Tasks

### Activity 01 — Define Intraday Model

#### L10-07.24-001 — Define Intraday Management Process

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Define ownership, monitoring intervals, exception handling and escalation.

**Dependencies**

- Forecast
- Staffing model

**Deliverable**

Intraday management model.

**Acceptance Criteria**

Process is approved.

#### L10-07.24-002 — Define Intraday Thresholds

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define thresholds for volume, staffing, service level and adherence exceptions.

**Dependencies**

- L10-07.24-001

**Deliverable**

Intraday threshold catalogue.

**Acceptance Criteria**

Thresholds are approved.

### Activity 02 — Configure and Validate

#### L10-07.24-003 — Configure Intraday Views and Processes

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Configure the operational views and supporting processes needed for intraday management.

**Dependencies**

- L10-07.24-002

**Deliverable**

Configured intraday capability.

**Acceptance Criteria**

WFM users can monitor agreed intraday metrics.

#### L10-07.24-004 — Execute Intraday Scenario Validation

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Test volume spikes, staffing shortages, adherence exceptions and corrective actions.

**Dependencies**

- L10-07.24-003

**Deliverable**

Intraday scenario test evidence.

**Acceptance Criteria**

Defined exception scenarios can be identified and managed.
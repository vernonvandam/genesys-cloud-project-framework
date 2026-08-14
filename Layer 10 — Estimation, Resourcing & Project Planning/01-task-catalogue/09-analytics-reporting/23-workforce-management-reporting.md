# Layer 10 — 2.09.23 Workforce Management Reporting

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 09 — Analytics, Reporting & Data Visualisation |
| Capability ID | 2.09.23 |
| Capability | Workforce Management Reporting |
| Task Catalogue ID | 09.23 |
| Primary Layer 1 Phases | P03, P04, P06, P08 |

## Capability Objective

Provide WFM reporting covering forecasts, schedules, adherence, staffing and workforce performance.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define WFM reporting |
| P04 | Design WFM analytics |
| P06 | Configure reporting |
| P08 | Validate results |

## Source Implementation Activities

1. Define WFM metrics.
2. Map WFM data.
3. Configure reporting.
4. Validate results.

## Implementation Tasks

### Activity 01 — Requirements

#### L10-09-23-001 — Define WFM Reporting Requirements

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Define workforce reporting requirements.

**Dependencies**

- L10-09-02-002

**Deliverable**

WFM reporting requirements.

**Acceptance Criteria**

Requirements are approved.

### Activity 02 — Configure

#### L10-09-23-002 — Configure WFM Reporting

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | WFM Consultant |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | NO |

**Description**

Configure required WFM reports and dashboards.

**Dependencies**

- L10-09-23-001

**Deliverable**

WFM reporting.

**Acceptance Criteria**

Required WFM reports are available.

### Activity 03 — Validation

#### L10-09-23-003 — Validate WFM Reporting

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

Validate WFM reporting against approved workforce data.

**Dependencies**

- L10-09-23-002

**Deliverable**

WFM validation evidence.

**Acceptance Criteria**

WFM reporting reconciles to source data.

## Capability-Level Dependencies

- WFM
- Agent analytics
- Queue analytics
- Data integrations

## Capability-Level Estimation Considerations

Effort depends on WFM scope and external workforce data sources.

## Definition of Done

WFM reporting is configured and validated where required.
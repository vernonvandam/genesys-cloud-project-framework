# Layer 10 — 2.09.35 Queue & Team Performance Reporting

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 09 — Analytics, Reporting & Data Visualisation |
| Capability ID | 2.09.35 |
| Capability | Queue & Team Performance Reporting |
| Task Catalogue ID | 09.35 |
| Primary Layer 1 Phases | P03, P04, P06, P08 |

## Capability Objective

Provide team and queue performance reporting for operational and management decision-making.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define team reporting |
| P04 | Design team reporting |
| P06 | Configure reporting |
| P08 | Validate |

## Source Implementation Activities

1. Define team metrics.
2. Define queue metrics.
3. Configure reports.
4. Validate.

## Implementation Tasks

### Activity 01 — Requirements

#### L10-09-35-001 — Define Queue and Team Reporting Requirements

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

Define queue and team performance metrics.

**Dependencies**

- L10-09-11-001

**Deliverable**

Team reporting requirements.

**Acceptance Criteria**

Requirements are approved.

### Activity 02 — Configure

#### L10-09-35-002 — Configure Queue and Team Reporting

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

Configure queue and team performance reports.

**Dependencies**

- L10-09-35-001

**Deliverable**

Team performance reporting.

**Acceptance Criteria**

Required metrics are available.

### Activity 03 — Validation

#### L10-09-35-003 — Validate Queue and Team Reporting

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

Validate team and queue reporting.

**Dependencies**

- L10-09-35-002

**Deliverable**

Validation evidence.

**Acceptance Criteria**

Reports reconcile to source analytics.

## Capability-Level Dependencies

- Queue analytics
- Agent analytics
- Teams
- KPI framework

## Capability-Level Estimation Considerations

Effort depends on queue/team structures and number of reporting views.

## Definition of Done

Queue and team performance reporting is configured and validated.
# Layer 10 — 2.09.30 Operational Dashboards

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 09 — Analytics, Reporting & Data Visualisation |
| Capability ID | 2.09.30 |
| Capability | Operational Dashboards |
| Task Catalogue ID | 09.30 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P10 |

## Capability Objective

Provide operational dashboards focused on actionable contact centre performance.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define dashboard requirements |
| P04 | Design dashboard |
| P06 | Build dashboard |
| P08 | Validate dashboard |
| P10 | Deploy dashboard |

## Source Implementation Activities

1. Define operational metrics.
2. Design dashboard.
3. Configure dashboard.
4. Validate usability.
5. Deploy.

## Implementation Tasks

### Activity 01 — Requirements

#### L10-09-30-001 — Define Operational Dashboard Requirements

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

Define operational dashboard metrics, consumers and refresh requirements.

**Dependencies**

- L10-09-29-001

**Deliverable**

Dashboard requirements.

**Acceptance Criteria**

Operational requirements are approved.

### Activity 02 — Design

#### L10-09-30-002 — Design Operational Dashboard

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Design dashboard layout, metrics, filters and navigation.

**Dependencies**

- L10-09-30-001

**Deliverable**

Dashboard design.

**Acceptance Criteria**

Dashboard design is approved.

### Activity 03 — Build

#### L10-09-30-003 — Build Operational Dashboard

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

Build the approved operational dashboard.

**Dependencies**

- L10-09-30-002

**Deliverable**

Operational dashboard.

**Acceptance Criteria**

Dashboard meets approved design.

### Activity 04 — Validation

#### L10-09-30-004 — Validate Operational Dashboard

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

Validate dashboard data, usability and performance.

**Dependencies**

- L10-09-30-003

**Deliverable**

Dashboard validation evidence.

**Acceptance Criteria**

Dashboard passes functional and user validation.

## Capability-Level Dependencies

- Real-time reporting
- Queue analytics
- KPI framework

## Capability-Level Estimation Considerations

Effort depends on dashboard complexity and number of metrics.

## Definition of Done

Operational dashboard is validated and deployed.
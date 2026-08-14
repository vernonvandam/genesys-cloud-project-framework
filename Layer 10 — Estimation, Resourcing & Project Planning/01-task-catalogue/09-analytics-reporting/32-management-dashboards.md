# Layer 10 — 2.09.32 Management Dashboards

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 09 — Analytics, Reporting & Data Visualisation |
| Capability ID | 2.09.32 |
| Capability | Management Dashboards |
| Task Catalogue ID | 09.32 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P10 |

## Capability Objective

Provide management-level dashboards combining operational, service, workforce, quality and customer measures.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define management requirements |
| P04 | Design management dashboard |
| P06 | Build dashboard |
| P08 | Validate |
| P10 | Deploy |

## Source Implementation Activities

1. Define management KPIs.
2. Design dashboard.
3. Build dashboard.
4. Validate.
5. Deploy.

## Implementation Tasks

### Activity 01 — Requirements

#### L10-09-32-001 — Define Management Dashboard Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Define management-level KPI and dashboard requirements.

**Dependencies**

- L10-09-03-001

**Deliverable**

Management dashboard requirements.

**Acceptance Criteria**

Requirements are approved.

### Activity 02 — Design

#### L10-09-32-002 — Design Management Dashboard

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

Design management dashboard structure and KPI presentation.

**Dependencies**

- L10-09-32-001

**Deliverable**

Management dashboard design.

**Acceptance Criteria**

Design is approved.

### Activity 03 — Build

#### L10-09-32-003 — Build Management Dashboard

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

Build management dashboard.

**Dependencies**

- L10-09-32-002

**Deliverable**

Management dashboard.

**Acceptance Criteria**

Dashboard meets approved requirements.

### Activity 04 — Validation

#### L10-09-32-004 — Validate Management Dashboard

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

Validate management dashboard calculations and presentation.

**Dependencies**

- L10-09-32-003

**Deliverable**

Validation evidence.

**Acceptance Criteria**

Management users approve dashboard.

## Capability-Level Dependencies

- KPI framework
- Operational dashboards
- Reporting security

## Capability-Level Estimation Considerations

Effort depends on KPI complexity and dashboard integration requirements.

## Definition of Done

Management dashboards are validated and ready for production use.
# Layer 10 — 2.09.01 Analytics & Reporting Strategy

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 09 — Analytics, Reporting & Data Visualisation |
| Capability ID | 2.09.01 |
| Capability | Analytics & Reporting Strategy |
| Task Catalogue ID | 09.01 |
| Primary Layer 1 Phases | P01, P02, P03, P04, P12 |

## Capability Objective

Define the enterprise analytics and reporting strategy, including reporting consumers, information requirements, data sources, governance and reporting lifecycle.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P01 | Establish reporting scope |
| P02 | Discover current reporting |
| P03 | Define requirements |
| P04 | Design target analytics strategy |
| P12 | Handover governance |

## Source Implementation Activities

1. Establish reporting strategy.
2. Identify reporting stakeholders.
3. Assess existing reporting.
4. Define target reporting model.
5. Approve strategy.

## Implementation Tasks

### Activity 01 — Strategy

#### L10-09-01-001 — Establish Analytics Strategy Scope

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P01 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define the scope, objectives and stakeholders for analytics and reporting.

**Dependencies**

- P01 project initiation

**Deliverable**

Analytics strategy scope.

**Acceptance Criteria**

Reporting scope and stakeholders are documented.

### Activity 02 — Discovery

#### L10-09-01-002 — Assess Existing Reporting Landscape

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Business Analyst |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Inventory existing reports, dashboards, KPIs and reporting processes.

**Dependencies**

- L10-09-01-001

**Deliverable**

Current-state reporting inventory.

**Acceptance Criteria**

Existing reporting landscape is documented.

### Activity 03 — Design

#### L10-09-01-003 — Define Target Analytics Strategy

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Define target analytics, reporting, dashboard, data and governance principles.

**Dependencies**

- L10-09-01-002

**Deliverable**

Target analytics strategy.

**Acceptance Criteria**

Target strategy is approved.

### Activity 04 — Approval

#### L10-09-01-004 — Approve Analytics Strategy

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Obtain business and technical approval of the analytics strategy.

**Dependencies**

- L10-09-01-003

**Deliverable**

Approved analytics strategy.

**Acceptance Criteria**

Required stakeholders approve the strategy.

### Activity 05 — Governance

#### L10-09-01-005 — Establish Reporting Governance Baseline

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Define ownership, lifecycle and governance expectations for analytics.

**Dependencies**

- L10-09-01-004

**Deliverable**

Reporting governance baseline.

**Acceptance Criteria**

Reporting ownership and lifecycle are documented.

## Capability-Level Dependencies

- Project scope
- Business stakeholders
- Existing reporting
- KPI requirements
- Data architecture

## Capability-Level Estimation Considerations

Effort is driven by organisational complexity, number of reporting stakeholders, existing reporting estate and governance maturity.

## Definition of Done

Analytics strategy is approved, documented and ready to drive detailed reporting requirements and design.
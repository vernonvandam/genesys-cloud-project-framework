# Layer 10 — 2.09.03 KPI & Metrics Framework

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 09 — Analytics, Reporting & Data Visualisation |
| Capability ID | 2.09.03 |
| Capability | KPI & Metrics Framework |
| Task Catalogue ID | 09.03 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P12 |

## Capability Objective

Establish a controlled catalogue of KPIs, metric definitions, calculation rules, ownership and reporting usage.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define KPI requirements |
| P04 | Design metric model |
| P06 | Implement KPI definitions |
| P08 | Validate calculations |
| P12 | Handover KPI governance |

## Source Implementation Activities

1. Inventory KPIs.
2. Define metric calculations.
3. Define data sources.
4. Configure metrics.
5. Reconcile results.
6. Approve KPI catalogue.

## Implementation Tasks

### Activity 01 — KPI Inventory

#### L10-09-03-001 — Inventory Required KPIs

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

Identify required operational, customer, workforce and management KPIs.

**Dependencies**

- L10-09-02-002

**Deliverable**

KPI inventory.

**Acceptance Criteria**

Required KPIs are identified and classified.

### Activity 02 — Definitions

#### L10-09-03-002 — Define KPI Calculation Rules

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 5.0h |
| Critical Path | YES |

**Description**

Define formulas, inclusions, exclusions, dimensions, time periods and source systems.

**Dependencies**

- L10-09-03-001

**Deliverable**

Metric dictionary.

**Acceptance Criteria**

Each KPI has an approved calculation definition.

### Activity 03 — Configuration

#### L10-09-03-003 — Implement KPI Reporting Definitions

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

Implement required KPI reporting definitions in the target reporting solution.

**Dependencies**

- L10-09-03-002

**Deliverable**

Configured KPI reporting.

**Acceptance Criteria**

KPI definitions are implemented according to approved rules.

### Activity 04 — Reconciliation

#### L10-09-03-004 — Reconcile KPI Results

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

Compare KPI results against approved calculations and known source data.

**Dependencies**

- L10-09-03-003

**Deliverable**

KPI reconciliation evidence.

**Acceptance Criteria**

Critical KPI calculations reconcile within agreed tolerances.

### Activity 05 — Governance

#### L10-09-03-005 — Approve KPI Catalogue

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Solution Architect |
| Customer Responsibility | YES |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Establish the approved KPI catalogue as the reporting baseline.

**Dependencies**

- L10-09-03-004

**Deliverable**

Approved KPI catalogue.

**Acceptance Criteria**

KPI ownership and definitions are approved.

## Capability-Level Dependencies

- Reporting requirements
- Data sources
- Contact centre measurement model
- Business definitions

## Capability-Level Estimation Considerations

Effort is driven by KPI count, complexity of calculations, external data dependencies and reconciliation requirements.

## Definition of Done

The KPI framework is defined, implemented, reconciled, approved and governed.
# Layer 10 — 2.15.06 KPI-Driven Optimisation

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 15 — Optimisation, Continuous Improvement & Platform Evolution |
| Capability ID | 2.15.06 |
| Capability | KPI-Driven Optimisation |
| Task Catalogue ID | 15.06 |
| Primary Layer 1 Phases | P02, P03, P08, P09, P11 |

## Capability Objective

Use measurable performance indicators to identify, prioritise, validate and continuously manage optimisation opportunities.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P02 | Establish KPI baseline |
| P03 | Define target KPIs |
| P08 | Define validation criteria |
| P09 | Monitor KPI performance |
| P11 | Validate production KPI outcomes |

## Source Implementation Activities

1. Define KPI framework.
2. Establish baseline.
3. Identify performance gaps.
4. Define optimisation targets.
5. Monitor outcomes.

## Implementation Tasks

### L10-15.06-001 — Define Optimisation KPI Framework

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Data Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Define the KPIs used to identify and evaluate optimisation opportunities.

**Dependencies**

- Business objectives
- Analytics capability

**Deliverable**

KPI optimisation framework.

**Acceptance Criteria**

KPIs, definitions and ownership are approved.

### L10-15.06-002 — Establish KPI Baseline

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Data Analyst |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Capture current KPI performance for the capabilities being optimised.

**Dependencies**

- L10-15.06-001

**Deliverable**

KPI baseline.

**Acceptance Criteria**

Baseline data is validated.

### L10-15.06-003 — Define KPI Improvement Targets

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | NO |

**Description**

Define target KPI outcomes and acceptable tolerance levels.

**Dependencies**

- L10-15.06-002

**Deliverable**

KPI target definition.

**Acceptance Criteria**

Targets are measurable and approved.

### L10-15.06-004 — Validate KPI Improvement

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P11 |
| Primary Role | Data Analyst |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Compare post-change KPI performance against the baseline and approved targets.

**Dependencies**

- L10-15.06-003
- Production deployment

**Deliverable**

KPI validation report.

**Acceptance Criteria**

KPI outcomes are measured and accepted.
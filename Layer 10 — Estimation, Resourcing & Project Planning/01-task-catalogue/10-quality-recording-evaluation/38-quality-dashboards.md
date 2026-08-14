# Layer 10 — 2.10.38 Quality Dashboards

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Quality Management, Recording & Evaluation |
| Capability ID | 2.10.38 |
| Capability | Quality Dashboards |
| Task Catalogue ID | 10.38 |
| Primary Layer 1 Phases | P03, P04, P05, P08, P09 |

## Capability Objective

Provide dashboards that present quality performance, evaluation and compliance measures to authorised stakeholders.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define dashboard requirements |
| P04 | Design dashboard model |
| P05 | Configure dashboards |
| P08 | Validate dashboard data |
| P09 | Business acceptance |

## Source Implementation Activities

1. Define dashboard requirements.
2. Design dashboard views.
3. Configure dashboards.
4. Validate metrics and access.

## Implementation Tasks

### Activity 01 — Dashboard Design

#### L10-10.38-001 — Define Quality Dashboard Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Define stakeholders, KPIs, filters, views and reporting objectives.

**Dependencies**

- Quality KPI framework

**Deliverable**

Dashboard requirements.

**Acceptance Criteria**

Requirements are approved.

#### L10-10.38-002 — Design Quality Dashboard Views

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Reporting Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Design dashboard layouts, metrics, filters and audience-specific views.

**Dependencies**

- L10-10.38-001

**Deliverable**

Dashboard design.

**Acceptance Criteria**

Dashboard views are approved.

### Activity 02 — Configure and Validate

#### L10-10.38-003 — Configure Quality Dashboards

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Configure approved quality dashboards.

**Dependencies**

- L10-10.38-002

**Deliverable**

Configured dashboards.

**Acceptance Criteria**

Required dashboards are available.

#### L10-10.38-004 — Validate Dashboard Metrics

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Validate metric calculations, filters, visibility and data accuracy.

**Dependencies**

- L10-10.38-003

**Deliverable**

Dashboard validation evidence.

**Acceptance Criteria**

Dashboard metrics reconcile to expected results.

## Definition of Done

Quality dashboards are configured, validated and accepted.

---

# Layer 10 — 2.09.13 Service Level Analytics

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 09 — Analytics, Reporting & Data Visualisation |
| Capability ID | 2.09.13 |
| Capability | Service Level Analytics |
| Task Catalogue ID | 09.13 |
| Primary Layer 1 Phases | P03, P04, P06, P08 |

## Capability Objective

Implement service-level reporting using approved service targets, calculation rules and operational dimensions.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define service-level requirements |
| P04 | Define calculation model |
| P06 | Configure reporting |
| P08 | Validate results |

## Source Implementation Activities

1. Define service targets.
2. Define calculation rules.
3. Configure reporting.
4. Reconcile results.

## Implementation Tasks

### Activity 01 — Requirements

#### L10-09-13-001 — Define Service Level Targets

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Capture agreed service-level targets and business rules.

**Dependencies**

- L10-09-03-001

**Deliverable**

Service-level target catalogue.

**Acceptance Criteria**

Targets are approved.

### Activity 02 — Design

#### L10-09-13-002 — Define Service Level Calculation Model

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

Define service-level calculation rules, exclusions and reporting dimensions.

**Dependencies**

- L10-09-13-001

**Deliverable**

Service-level calculation model.

**Acceptance Criteria**

Calculation model is approved.

### Activity 03 — Configure

#### L10-09-13-003 — Configure Service Level Reporting

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Configure service-level reporting.

**Dependencies**

- L10-09-13-002

**Deliverable**

Service-level reporting.

**Acceptance Criteria**

Service-level metrics are available.

### Activity 04 — Validation

#### L10-09-13-004 — Reconcile Service Level Reporting

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

Reconcile service-level calculations to approved business rules.

**Dependencies**

- L10-09-13-003

**Deliverable**

Reconciliation evidence.

**Acceptance Criteria**

Service-level results reconcile within approved tolerance.

## Capability-Level Dependencies

- ACD queues
- Routing
- KPI framework
- Business service targets

## Capability-Level Estimation Considerations

Effort is driven by number of service targets and calculation complexity.

## Definition of Done

Service-level analytics are configured and reconciled.
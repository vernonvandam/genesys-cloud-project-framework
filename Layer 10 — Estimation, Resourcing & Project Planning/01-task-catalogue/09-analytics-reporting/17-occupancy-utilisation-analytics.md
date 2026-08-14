# Layer 10 — 2.09.17 Occupancy & Utilisation Analytics

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 09 — Analytics, Reporting & Data Visualisation |
| Capability ID | 2.09.17 |
| Capability | Occupancy & Utilisation Analytics |
| Task Catalogue ID | 09.17 |
| Primary Layer 1 Phases | P03, P04, P06, P08 |

## Capability Objective

Provide occupancy and utilisation reporting where required to support workforce and operational management.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define utilisation requirements |
| P04 | Define measurement model |
| P06 | Configure reporting |
| P08 | Validate results |

## Source Implementation Activities

1. Define utilisation metrics.
2. Map WFM data.
3. Configure reporting.
4. Validate results.

## Implementation Tasks

### Activity 01 — Requirements

#### L10-09-17-001 — Define Occupancy and Utilisation Requirements

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Define occupancy and utilisation measures required by operations and WFM.

**Dependencies**

- L10-09-03-001

**Deliverable**

Utilisation requirements.

**Acceptance Criteria**

Required measures are approved.

### Activity 02 — Design

#### L10-09-17-002 — Define Utilisation Measurement Model

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P04 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Define calculation rules and source data for occupancy and utilisation.

**Dependencies**

- L10-09-17-001

**Deliverable**

Utilisation model.

**Acceptance Criteria**

Measurement model is approved.

### Activity 03 — Configure

#### L10-09-17-003 — Configure Occupancy and Utilisation Reporting

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

Configure required occupancy and utilisation reporting.

**Dependencies**

- L10-09-17-002

**Deliverable**

Utilisation reporting.

**Acceptance Criteria**

Required measures are available.

### Activity 04 — Validation

#### L10-09-17-004 — Validate Occupancy Reporting

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

Validate occupancy and utilisation results against agreed calculations.

**Dependencies**

- L10-09-17-003

**Deliverable**

Validation evidence.

**Acceptance Criteria**

Results reconcile to approved measurement rules.

## Capability-Level Dependencies

- WFM
- Agent analytics
- KPI framework

## Capability-Level Estimation Considerations

Effort is driven by WFM integration and complexity of utilisation calculations.

## Definition of Done

Occupancy and utilisation reporting is implemented and validated where required.
# Layer 10 — 2.09.15 AHT & Handle Time Analytics

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 09 — Analytics, Reporting & Data Visualisation |
| Capability ID | 2.09.15 |
| Capability | AHT & Handle Time Analytics |
| Task Catalogue ID | 09.15 |
| Primary Layer 1 Phases | P03, P04, P06, P08 |

## Capability Objective

Implement consistent average handle time and interaction handling analytics.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define AHT requirements |
| P04 | Define calculation model |
| P06 | Configure analytics |
| P08 | Validate results |

## Source Implementation Activities

1. Define AHT formula.
2. Define included states.
3. Configure reporting.
4. Validate calculations.

## Implementation Tasks

### Activity 01 — Definition

#### L10-09-15-001 — Define AHT Calculation

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

Define the approved AHT and handle-time calculation.

**Dependencies**

- L10-09-03-001

**Deliverable**

AHT definition.

**Acceptance Criteria**

Calculation is approved.

### Activity 02 — Configure

#### L10-09-15-002 — Configure AHT Analytics

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

Configure AHT and handle-time reporting.

**Dependencies**

- L10-09-15-001

**Deliverable**

AHT reporting.

**Acceptance Criteria**

AHT metrics are available.

### Activity 03 — Validation

#### L10-09-15-003 — Validate AHT Analytics

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Analyst |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate AHT calculations against sample interactions.

**Dependencies**

- L10-09-15-002

**Deliverable**

AHT validation evidence.

**Acceptance Criteria**

AHT calculations reconcile to approved definitions.

## Capability-Level Dependencies

- Interaction analytics
- ACD
- KPI framework

## Capability-Level Estimation Considerations

Effort depends on channels, calculation variations and reporting dimensions.

## Definition of Done

AHT reporting is configured, reconciled and approved.
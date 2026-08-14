# Layer 10 — 2.09.41 Data Modelling & Transformation

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 09 — Analytics, Reporting & Data Visualisation |
| Capability ID | 2.09.41 |
| Capability | Data Modelling & Transformation |
| Task Catalogue ID | 09.41 |
| Primary Layer 1 Phases | P04, P07, P08 |

## Capability Objective

Define and implement data models and transformation rules required for enterprise reporting.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P04 | Design data model |
| P07 | Implement transformations |
| P08 | Validate data model |

## Source Implementation Activities

1. Define data model.
2. Define transformations.
3. Implement transformations.
4. Validate outputs.

## Implementation Tasks

### Activity 01 — Model

#### L10-09-41-001 — Define Analytics Data Model

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P04 |
| Primary Role | Data Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 5.0h |
| Critical Path | NO |

**Description**

Define entities, relationships, measures and dimensions for reporting.

**Dependencies**

- L10-09-39-002

**Deliverable**

Analytics data model.

**Acceptance Criteria**

Data model is approved.

### Activity 02 — Transformation

#### L10-09-41-002 — Define Data Transformation Rules

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P04 |
| Primary Role | Data Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | NO |

**Description**

Define transformation, enrichment, mapping and aggregation rules.

**Dependencies**

- L10-09-41-001

**Deliverable**

Transformation specification.

**Acceptance Criteria**

Transformation rules are approved.

### Activity 03 — Implement

#### L10-09-41-003 — Implement Data Transformations

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P07 |
| Primary Role | Data Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | CONDITIONAL |
| Baseline Effort | 6.0h |
| Critical Path | NO |

**Description**

Implement approved transformation rules.

**Dependencies**

- L10-09-41-002

**Deliverable**

Transformation pipeline.

**Acceptance Criteria**

Transformations execute successfully.

### Activity 04 — Validation

#### L10-09-41-004 — Validate Transformed Data

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Data Analyst |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | NO |

**Description**

Validate transformed data against source and expected results.

**Dependencies**

- L10-09-41-003

**Deliverable**

Transformation validation evidence.

**Acceptance Criteria**

Transformed data reconciles to approved rules.

## Capability-Level Dependencies

- Data warehouse/lake
- BI platform
- Data sources
- KPI framework

## Capability-Level Estimation Considerations

Effort depends on data model complexity and number of transformations.

## Definition of Done

Required data models and transformations are implemented and validated.
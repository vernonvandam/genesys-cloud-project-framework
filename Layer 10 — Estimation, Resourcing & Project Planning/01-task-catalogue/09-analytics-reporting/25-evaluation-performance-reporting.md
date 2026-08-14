# Layer 10 — 2.09.25 Evaluation & Performance Reporting

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 09 — Analytics, Reporting & Data Visualisation |
| Capability ID | 2.09.25 |
| Capability | Evaluation & Performance Reporting |
| Task Catalogue ID | 09.25 |
| Primary Layer 1 Phases | P03, P04, P06, P08 |

## Capability Objective

Provide reporting on agent evaluations, scores, trends and performance outcomes.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define evaluation reporting |
| P04 | Design performance model |
| P06 | Configure reporting |
| P08 | Validate results |

## Source Implementation Activities

1. Define evaluation measures.
2. Configure reporting.
3. Validate evaluation results.

## Implementation Tasks

### Activity 01 — Requirements

#### L10-09-25-001 — Define Evaluation Reporting Requirements

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Quality Consultant |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Define evaluation and agent performance reporting requirements.

**Dependencies**

- L10-09-24-001

**Deliverable**

Evaluation reporting requirements.

**Acceptance Criteria**

Requirements are approved.

### Activity 02 — Configure

#### L10-09-25-002 — Configure Evaluation Reporting

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Configure evaluation and performance reporting.

**Dependencies**

- L10-09-25-001

**Deliverable**

Evaluation reporting.

**Acceptance Criteria**

Required evaluation metrics are available.

### Activity 03 — Validation

#### L10-09-25-003 — Validate Evaluation Reporting

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Analyst |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Validate evaluation results and performance calculations.

**Dependencies**

- L10-09-25-002

**Deliverable**

Evaluation validation evidence.

**Acceptance Criteria**

Evaluation metrics reconcile to source records.

## Capability-Level Dependencies

- Quality Management
- Evaluations
- Agent analytics

## Capability-Level Estimation Considerations

Effort depends on evaluation model complexity and reporting population.

## Definition of Done

Evaluation performance reporting is configured and validated where required.
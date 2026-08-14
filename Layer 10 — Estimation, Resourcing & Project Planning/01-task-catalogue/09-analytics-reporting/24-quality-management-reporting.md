# Layer 10 — 2.09.24 Quality Management Reporting

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 09 — Analytics, Reporting & Data Visualisation |
| Capability ID | 2.09.24 |
| Capability | Quality Management Reporting |
| Task Catalogue ID | 09.24 |
| Primary Layer 1 Phases | P03, P04, P06, P08 |

## Capability Objective

Provide reporting for quality management programmes, quality scores, evaluations and coaching.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define quality reporting |
| P04 | Design quality analytics |
| P06 | Configure reports |
| P08 | Validate results |

## Source Implementation Activities

1. Define quality metrics.
2. Define reporting consumers.
3. Configure reporting.
4. Validate results.

## Implementation Tasks

### Activity 01 — Requirements

#### L10-09-24-001 — Define Quality Reporting Requirements

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Quality Consultant |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Define quality management reporting requirements.

**Dependencies**

- L10-09-02-002

**Deliverable**

Quality reporting requirements.

**Acceptance Criteria**

Requirements are approved.

### Activity 02 — Configure

#### L10-09-24-002 — Configure Quality Management Reporting

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | NO |

**Description**

Configure quality management reporting.

**Dependencies**

- L10-09-24-001

**Deliverable**

Quality reporting.

**Acceptance Criteria**

Required quality metrics are available.

### Activity 03 — Validation

#### L10-09-24-003 — Validate Quality Reporting

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

Validate quality reporting against evaluations and quality records.

**Dependencies**

- L10-09-24-002

**Deliverable**

Quality validation evidence.

**Acceptance Criteria**

Quality results reconcile to source data.

## Capability-Level Dependencies

- Quality Management
- Evaluation configuration
- Recording
- Agent analytics

## Capability-Level Estimation Considerations

Effort depends on quality programme complexity and evaluation volumes.

## Definition of Done

Quality management reporting is configured and validated where required.
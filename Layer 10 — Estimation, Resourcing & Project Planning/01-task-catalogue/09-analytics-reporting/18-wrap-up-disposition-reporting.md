# Layer 10 — 2.09.18 Wrap-Up & Disposition Reporting

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 09 — Analytics, Reporting & Data Visualisation |
| Capability ID | 2.09.18 |
| Capability | Wrap-Up & Disposition Reporting |
| Task Catalogue ID | 09.18 |
| Primary Layer 1 Phases | P03, P04, P06, P08 |

## Capability Objective

Provide reporting on wrap-up codes, dispositions and interaction outcomes.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define disposition requirements |
| P04 | Design disposition reporting |
| P06 | Configure reporting |
| P08 | Validate results |

## Source Implementation Activities

1. Define disposition requirements.
2. Map wrap-up codes.
3. Configure reporting.
4. Validate outcomes.

## Implementation Tasks

### Activity 01 — Requirements

#### L10-09-18-001 — Define Wrap-Up Reporting Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define required wrap-up and disposition reporting.

**Dependencies**

- L10-09-02-002

**Deliverable**

Disposition reporting requirements.

**Acceptance Criteria**

Requirements are approved.

### Activity 02 — Configure

#### L10-09-18-002 — Configure Wrap-Up Reporting

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

Configure wrap-up and disposition reporting.

**Dependencies**

- L10-09-18-001

**Deliverable**

Wrap-up reporting.

**Acceptance Criteria**

Required wrap-up values appear correctly.

### Activity 03 — Validation

#### L10-09-18-003 — Validate Disposition Reporting

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

Validate disposition reporting against interaction outcomes.

**Dependencies**

- L10-09-18-002

**Deliverable**

Validation evidence.

**Acceptance Criteria**

Disposition reporting reconciles to source interactions.

## Capability-Level Dependencies

- Architect
- ACD
- Wrap-up configuration
- Interaction analytics

## Capability-Level Estimation Considerations

Effort depends on number of wrap-up codes and reporting dimensions.

## Definition of Done

Wrap-up and disposition reporting is configured and validated.
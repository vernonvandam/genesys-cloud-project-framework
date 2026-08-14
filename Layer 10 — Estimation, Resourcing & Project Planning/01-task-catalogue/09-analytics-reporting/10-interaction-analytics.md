# Layer 10 — 2.09.10 Interaction Analytics

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 09 — Analytics, Reporting & Data Visualisation |
| Capability ID | 2.09.10 |
| Capability | Interaction Analytics |
| Task Catalogue ID | 09.10 |
| Primary Layer 1 Phases | P03, P04, P06, P08 |

## Capability Objective

Provide detailed interaction-level reporting across voice, digital and other supported interaction channels.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define interaction reporting requirements |
| P04 | Design interaction analytics |
| P06 | Configure reporting |
| P08 | Validate results |

## Source Implementation Activities

1. Define interaction metrics.
2. Define dimensions.
3. Configure analytics.
4. Validate interaction results.

## Implementation Tasks

### Activity 01 — Requirements

#### L10-09-10-001 — Define Interaction Analytics Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Define interaction-level metrics, dimensions and reporting requirements.

**Dependencies**

- L10-09-02-002

**Deliverable**

Interaction analytics requirements.

**Acceptance Criteria**

Required interaction measures are approved.

### Activity 02 — Design

#### L10-09-10-002 — Design Interaction Analytics

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

Design interaction reporting structure, filters and dimensions.

**Dependencies**

- L10-09-10-001

**Deliverable**

Interaction analytics design.

**Acceptance Criteria**

Design is approved.

### Activity 03 — Configure

#### L10-09-10-003 — Configure Interaction Analytics

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

Configure interaction analytics and required reporting views.

**Dependencies**

- L10-09-10-002

**Deliverable**

Configured interaction analytics.

**Acceptance Criteria**

Required views and metrics operate correctly.

### Activity 04 — Validation

#### L10-09-10-004 — Validate Interaction Analytics

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

Validate interaction analytics against approved requirements.

**Dependencies**

- L10-09-10-003

**Deliverable**

Validation evidence.

**Acceptance Criteria**

Interaction metrics reconcile to source data.

## Capability-Level Dependencies

- Voice
- Digital
- ACD
- Analytics
- KPI framework

## Capability-Level Estimation Considerations

Effort varies by number of channels, interaction dimensions and required reporting views.

## Definition of Done

Interaction analytics are configured, validated and available to authorised consumers.
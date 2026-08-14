# Layer 10 — 2.09.14 Abandonment Analytics

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 09 — Analytics, Reporting & Data Visualisation |
| Capability ID | 2.09.14 |
| Capability | Abandonment Analytics |
| Task Catalogue ID | 09.14 |
| Primary Layer 1 Phases | P03, P04, P06, P08 |

## Capability Objective

Provide accurate reporting of abandoned interactions and abandonment rates using approved business rules.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define abandonment requirements |
| P04 | Define calculation model |
| P06 | Configure analytics |
| P08 | Validate results |

## Source Implementation Activities

1. Define abandonment rules.
2. Configure metrics.
3. Configure reporting.
4. Validate calculations.

## Implementation Tasks

### Activity 01 — Requirements

#### L10-09-14-001 — Define Abandonment Rules

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

Define what constitutes an abandoned interaction and required exclusions.

**Dependencies**

- L10-09-03-001

**Deliverable**

Abandonment rules.

**Acceptance Criteria**

Rules are approved.

### Activity 02 — Configure

#### L10-09-14-002 — Configure Abandonment Reporting

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

Configure abandonment counts, rates and reporting views.

**Dependencies**

- L10-09-14-001

**Deliverable**

Abandonment reporting.

**Acceptance Criteria**

Required abandonment metrics are available.

### Activity 03 — Validation

#### L10-09-14-003 — Validate Abandonment Analytics

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

Validate abandonment calculations against source interactions.

**Dependencies**

- L10-09-14-002

**Deliverable**

Validation evidence.

**Acceptance Criteria**

Abandonment results reconcile to approved rules.

## Capability-Level Dependencies

- ACD
- Queue configuration
- Service-level definitions
- KPI framework

## Capability-Level Estimation Considerations

Effort depends on abandonment rules and queue/report complexity.

## Definition of Done

Abandonment analytics are configured and validated.
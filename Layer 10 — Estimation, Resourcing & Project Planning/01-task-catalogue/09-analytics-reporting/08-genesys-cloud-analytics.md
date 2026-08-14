# Layer 10 — 2.09.08 Genesys Cloud Analytics

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 09 — Analytics, Reporting & Data Visualisation |
| Capability ID | 2.09.08 |
| Capability | Genesys Cloud Analytics |
| Task Catalogue ID | 09.08 |
| Primary Layer 1 Phases | P04, P05, P06, P08, P10 |

## Capability Objective

Configure Genesys Cloud native analytics capabilities required to provide operational and historical contact centre reporting.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P04 | Design analytics model |
| P05 | Establish analytics foundations |
| P06 | Configure analytics |
| P08 | Validate analytics |
| P10 | Deploy analytics |

## Source Implementation Activities

1. Define analytics requirements.
2. Configure analytics views.
3. Configure filters and dimensions.
4. Validate metrics.
5. Deploy reporting.

## Implementation Tasks

### Activity 01 — Design

#### L10-09-08-001 — Define Genesys Cloud Analytics Configuration

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

Define the required Genesys Cloud analytics views, metrics, filters and dimensions.

**Dependencies**

- L10-09-02-004
- L10-09-03-002

**Deliverable**

Analytics configuration design.

**Acceptance Criteria**

Analytics design is approved.

### Activity 02 — Configure

#### L10-09-08-002 — Configure Genesys Cloud Analytics

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

Configure required Genesys Cloud analytics views and reporting components.

**Dependencies**

- L10-09-08-001

**Deliverable**

Configured analytics.

**Acceptance Criteria**

Required analytics views operate correctly.

### Activity 03 — Validation

#### L10-09-08-003 — Validate Genesys Cloud Analytics

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

Validate analytics against approved KPI and reporting definitions.

**Dependencies**

- L10-09-08-002

**Deliverable**

Analytics validation evidence.

**Acceptance Criteria**

Required metrics reconcile to approved definitions.

### Activity 04 — Production

#### L10-09-08-004 — Deploy Analytics Configuration

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P10 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | CONDITIONAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Deploy validated analytics configuration to production.

**Dependencies**

- L10-09-08-003

**Deliverable**

Production analytics configuration.

**Acceptance Criteria**

Production analytics are available and validated.

## Capability-Level Dependencies

- Core platform
- ACD routing
- Architect
- KPI framework
- Reporting requirements

## Capability-Level Estimation Considerations

Effort depends on report complexity, number of views, business units and required analytics dimensions.

## Definition of Done

Genesys Cloud analytics are configured, validated and deployed.
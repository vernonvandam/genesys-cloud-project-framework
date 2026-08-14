# Layer 10 — 2.09.20 Digital Analytics

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 09 — Analytics, Reporting & Data Visualisation |
| Capability ID | 2.09.20 |
| Capability | Digital Analytics |
| Task Catalogue ID | 09.20 |
| Primary Layer 1 Phases | P03, P04, P06, P08 |

## Capability Objective

Provide analytics across supported digital interaction channels.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define digital reporting |
| P04 | Design digital analytics |
| P06 | Configure analytics |
| P08 | Validate reporting |

## Source Implementation Activities

1. Define digital metrics.
2. Define channel dimensions.
3. Configure analytics.
4. Validate results.

## Implementation Tasks

### Activity 01 — Requirements

#### L10-09-20-001 — Define Digital Analytics Requirements

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Digital Consultant |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Define digital-channel metrics, dimensions and reporting requirements.

**Dependencies**

- L10-09-02-002

**Deliverable**

Digital analytics requirements.

**Acceptance Criteria**

Digital reporting requirements are approved.

### Activity 02 — Configure

#### L10-09-20-002 — Configure Digital Analytics

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

Configure required digital analytics.

**Dependencies**

- L10-09-20-001

**Deliverable**

Digital analytics configuration.

**Acceptance Criteria**

Required digital metrics are available.

### Activity 03 — Validation

#### L10-09-20-003 — Validate Digital Analytics

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

Validate digital analytics across representative interactions.

**Dependencies**

- L10-09-20-002

**Deliverable**

Validation evidence.

**Acceptance Criteria**

Digital analytics reconcile to source interactions.

## Capability-Level Dependencies

- Digital
- ACD
- Interaction analytics

## Capability-Level Estimation Considerations

Effort depends on digital channels and reporting complexity.

## Definition of Done

Digital analytics are configured and validated where required.
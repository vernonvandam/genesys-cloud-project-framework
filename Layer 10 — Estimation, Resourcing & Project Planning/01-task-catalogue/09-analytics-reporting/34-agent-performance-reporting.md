# Layer 10 — 2.09.34 Agent Performance Reporting

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 09 — Analytics, Reporting & Data Visualisation |
| Capability ID | 2.09.34 |
| Capability | Agent Performance Reporting |
| Task Catalogue ID | 09.34 |
| Primary Layer 1 Phases | P03, P04, P06, P08 |

## Capability Objective

Provide agent-level performance reporting supporting coaching, development and operational performance management.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define performance requirements |
| P04 | Design agent performance reporting |
| P06 | Configure reports |
| P08 | Validate |

## Source Implementation Activities

1. Define performance measures.
2. Design reporting.
3. Configure reports.
4. Validate results.

## Implementation Tasks

### Activity 01 — Requirements

#### L10-09-34-001 — Define Agent Performance Requirements

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

Define agent performance measures and reporting consumers.

**Dependencies**

- L10-09-12-001

**Deliverable**

Performance reporting requirements.

**Acceptance Criteria**

Performance measures are approved.

### Activity 02 — Configure

#### L10-09-34-002 — Configure Agent Performance Reporting

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

Configure agent performance reports.

**Dependencies**

- L10-09-34-001

**Deliverable**

Agent performance reports.

**Acceptance Criteria**

Required performance measures are available.

### Activity 03 — Validation

#### L10-09-34-003 — Validate Agent Performance Reporting

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

Validate performance calculations and agent visibility.

**Dependencies**

- L10-09-34-002

**Deliverable**

Validation evidence.

**Acceptance Criteria**

Agent performance reporting passes validation.

## Capability-Level Dependencies

- Agent analytics
- Quality
- WFM
- Reporting security

## Capability-Level Estimation Considerations

Effort depends on metric count, agent population and reporting access model.

## Definition of Done

Agent performance reporting is configured and validated.
# Layer 10 — 2.08.27 Case / Work Item Synchronisation

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 08 — Data, Integrations & APIs |
| Capability ID | 2.08.27 |
| Capability | Case / Work Item Synchronisation |
| Task Catalogue ID | 08.27 |
| Primary Layer 1 Phases | P03, P04, P06, P08 |

## Capability Objective

Synchronise cases, work items and related status information between Genesys Cloud and external systems.

## Implementation Tasks

### L10-08.27-001 — Define Case Synchronisation Requirements

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Define case identifiers, attributes, status transitions and ownership.

**Dependencies**

- Case management requirements

**Deliverable**

Case synchronisation specification.

**Acceptance Criteria**

Case lifecycle requirements are approved.

### L10-08.27-002 — Implement Case Synchronisation

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Integration Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 6.0h |
| Critical Path | CONDITIONAL |

**Description**

Implement case and work-item create, retrieve and update operations as required.

**Dependencies**

- L10-08.27-001
- Data mapping

**Deliverable**

Case synchronisation integration.

**Acceptance Criteria**

Case transactions operate correctly.

### L10-08.27-003 — Validate Case Lifecycle

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Integration Engineer |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | CONDITIONAL |

**Description**

Validate case creation, update, closure and error handling.

**Dependencies**

- L10-08.27-002

**Deliverable**

Case lifecycle test evidence.

**Acceptance Criteria**

All approved lifecycle scenarios pass.
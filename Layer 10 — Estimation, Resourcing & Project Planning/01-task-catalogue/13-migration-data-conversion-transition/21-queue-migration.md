# Layer 10 — 2.13.21 Queue Migration

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 13 — Migration, Data Conversion & Transition |
| Capability ID | 2.13.21 |
| Capability | Queue Migration |
| Task Catalogue ID | 13.21 |
| Primary Layer 1 Phases | P04, P06, P08 |

## Capability Objective

Migrate or recreate queues and associated queue configuration.

## Source Implementation Activities

1. Inventory queues.
2. Map queue configuration.
3. Configure and validate queues.

## Implementation Tasks

### L10-13.21-001 — Inventory and Map Queues

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Map source queues to target queues and identify configuration differences.

**Dependencies**

- Migration scope
- Routing migration design

**Deliverable**

Queue migration mapping.

**Acceptance Criteria**

Queue mappings are approved.

### L10-13.21-002 — Configure Target Queues

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | HYBRID |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Create and configure target queues according to approved mappings.

**Dependencies**

- L10-13.21-001

**Deliverable**

Configured queues.

**Acceptance Criteria**

Required queues and attributes exist.

### L10-13.21-003 — Validate Queue Migration

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate queue behaviour, membership, routing and reporting dependencies.

**Dependencies**

- L10-13.21-002

**Deliverable**

Queue validation evidence.

**Acceptance Criteria**

Queues operate as approved.

## Definition of Done

Required queues are migrated and validated.

---
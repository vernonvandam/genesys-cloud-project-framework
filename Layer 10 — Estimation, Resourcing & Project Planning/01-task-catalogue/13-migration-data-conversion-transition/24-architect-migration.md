# Layer 10 — 2.13.24 Architect Migration

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 13 — Migration, Data Conversion & Transition |
| Capability ID | 2.13.24 |
| Capability | Architect Migration |
| Task Catalogue ID | 13.24 |
| Primary Layer 1 Phases | P04, P06, P08, P10 |

## Capability Objective

Migrate or recreate Architect flows, prompts, schedules, data dependencies and associated configuration.

## Implementation Tasks

### L10-13.24-001 — Inventory Architect Assets

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Inventory flows, prompts, schedules, dependencies and reusable components.

**Dependencies**

- Migration scope

**Deliverable**

Architect migration inventory.

**Acceptance Criteria**

Required Architect assets are identified.

### L10-13.24-002 — Migrate Architect Configuration

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | HYBRID |
| Baseline Effort | 5.0h |
| Critical Path | YES |

**Description**

Recreate or migrate approved Architect configuration into target.

**Dependencies**

- L10-13.24-001
- Target dependencies

**Deliverable**

Migrated Architect configuration.

**Acceptance Criteria**

Flows compile and required dependencies resolve.

### L10-13.24-003 — Validate Architect Flows

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Execute functional and exception-path validation of migrated flows.

**Dependencies**

- L10-13.24-002

**Deliverable**

Architect validation results.

**Acceptance Criteria**

Approved flow scenarios pass.

## Definition of Done

Required Architect assets are migrated and validated.

---

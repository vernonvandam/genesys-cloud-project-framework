# Layer 10 — 2.13.19 Configuration Migration

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 13 — Migration, Data Conversion & Transition |
| Capability ID | 2.13.19 |
| Capability | Configuration Migration |
| Task Catalogue ID | 13.19 |
| Primary Layer 1 Phases | P04, P06, P08, P10 |

## Capability Objective

Migrate approved Genesys Cloud configuration from source environments or legacy platforms into the target solution.

## Source Implementation Activities

1. Identify configuration objects.
2. Map and transform configuration.
3. Deploy and validate configuration.

## Implementation Tasks

### L10-13.19-001 — Inventory Migrated Configuration

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Identify configuration objects requiring migration or recreation.

**Dependencies**

- Migration scope
- Source inventory

**Deliverable**

Configuration migration inventory.

**Acceptance Criteria**

Configuration objects are classified as migrate, recreate, replace or retire.

### L10-13.19-002 — Migrate Configuration

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | HYBRID |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Deploy approved configuration into the target environment.

**Dependencies**

- L10-13.19-001
- Target platform foundation

**Deliverable**

Migrated configuration.

**Acceptance Criteria**

Target configuration is deployed successfully.

### L10-13.19-003 — Validate Migrated Configuration

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | HYBRID |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Validate migrated configuration against source and approved target design.

**Dependencies**

- L10-13.19-002

**Deliverable**

Configuration migration validation.

**Acceptance Criteria**

Required configuration operates as designed.

## Definition of Done

Approved configuration is migrated, validated and ready for production deployment.

---

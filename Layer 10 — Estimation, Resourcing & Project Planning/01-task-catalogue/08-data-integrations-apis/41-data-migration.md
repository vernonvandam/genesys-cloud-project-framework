# Layer 10 — 2.08.41 Data Migration

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 08 — Data, Integrations & APIs |
| Capability ID | 2.08.41 |
| Capability | Data Migration |
| Task Catalogue ID | 08.41 |
| Primary Layer 1 Phases | P02, P03, P04, P07, P08, P09, P10 |

## Capability Objective

Plan, execute, validate and reconcile data migration required to support the Genesys Cloud deployment.

## Implementation Tasks

### L10-08.41-001 — Define Migration Scope

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P02 |
| Primary Role | Data Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Identify source data, migration objects, volumes, retention and target destinations.

**Dependencies**

- Discovery
- Data inventory

**Deliverable**

Migration scope.

**Acceptance Criteria**

Migration scope is approved.

### L10-08.41-002 — Define Migration Mapping and Validation

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P04 |
| Primary Role | Data Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Define transformation, cleansing, validation and reconciliation rules.

**Dependencies**

- L10-08.41-001

**Deliverable**

Migration mapping specification.

**Acceptance Criteria**

Mappings and validation rules are approved.

### L10-08.41-003 — Execute Migration

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P07 |
| Primary Role | Data Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 8.0h |
| Critical Path | YES |

**Description**

Execute migration using approved tools and procedures.

**Dependencies**

- L10-08.41-002

**Deliverable**

Migrated data.

**Acceptance Criteria**

Migration completes successfully.

### L10-08.41-004 — Reconcile Migrated Data

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Data Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Reconcile source and target records and resolve migration defects.

**Dependencies**

- L10-08.41-003

**Deliverable**

Migration reconciliation report.

**Acceptance Criteria**

Approved reconciliation thresholds are achieved.
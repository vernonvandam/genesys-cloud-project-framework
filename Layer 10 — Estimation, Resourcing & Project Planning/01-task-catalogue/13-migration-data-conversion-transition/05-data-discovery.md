# Layer 10 — 2.13.05 Data Discovery

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 13 — Migration, Data Conversion & Transition |
| Capability ID | 2.13.05 |
| Capability | Data Discovery |
| Task Catalogue ID | 13.05 |
| Primary Layer 1 Phases | P02, P03 |

## Capability Objective

Identify datasets, structures, volumes, relationships and dependencies that may be affected by migration.

## Source Implementation Activities

1. Discover migration datasets.
2. Identify relationships and dependencies.
3. Document data inventory.

## Implementation Tasks

### L10-13.05-001 — Discover Migration Datasets

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Data Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Identify data stores, datasets and records relevant to migration.

**Dependencies**

- Source system inventory

**Deliverable**

Data inventory.

**Acceptance Criteria**

Material migration datasets are identified.

### L10-13.05-002 — Identify Data Relationships

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Data Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Identify relationships, dependencies and referential requirements between migration datasets.

**Dependencies**

- L10-13.05-001

**Deliverable**

Data relationship model.

**Acceptance Criteria**

Material relationships are documented.

### L10-13.05-003 — Approve Data Discovery Results

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P03 |
| Primary Role | Migration Lead |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Review and approve the migration data inventory and identified dependencies.

**Dependencies**

- L10-13.05-002

**Deliverable**

Approved data inventory.

**Acceptance Criteria**

Customer data owners approve identified migration datasets.

## Definition of Done

Migration datasets, relationships and ownership are understood.

---

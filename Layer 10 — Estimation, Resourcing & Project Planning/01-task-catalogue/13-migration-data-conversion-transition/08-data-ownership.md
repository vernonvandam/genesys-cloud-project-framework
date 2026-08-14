# Layer 10 — 2.13.08 Data Ownership

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 13 — Migration, Data Conversion & Transition |
| Capability ID | 2.13.08 |
| Capability | Data Ownership |
| Task Catalogue ID | 13.08 |
| Primary Layer 1 Phases | P01, P02, P03, P12 |

## Capability Objective

Establish accountable ownership for source data, target data, migration decisions and acceptance.

## Source Implementation Activities

1. Identify data owners.
2. Assign accountability.
3. Obtain ownership acceptance.

## Implementation Tasks

### L10-13.08-001 — Identify Data Owners

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Business Analyst |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Identify accountable owners for each migration dataset.

**Dependencies**

- Data discovery

**Deliverable**

Data ownership register.

**Acceptance Criteria**

Each material dataset has an owner.

### L10-13.08-002 — Assign Migration Approval Responsibilities

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Migration Lead |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define who approves mapping, cleansing, migration and reconciliation outcomes.

**Dependencies**

- L10-13.08-001

**Deliverable**

Migration accountability matrix.

**Acceptance Criteria**

Approval responsibilities are documented.

### L10-13.08-003 — Confirm Data Ownership Handover

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Service Manager |
| Customer Responsibility | YES |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Confirm operational ownership of migrated data.

**Dependencies**

- Migration completion

**Deliverable**

Data ownership handover.

**Acceptance Criteria**

Operational data ownership is accepted.

## Definition of Done

Data ownership and migration decision authority are explicit.

---

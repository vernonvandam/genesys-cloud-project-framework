# Layer 10 — 2.13.04 Source System Inventory

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 13 — Migration, Data Conversion & Transition |
| Capability ID | 2.13.04 |
| Capability | Source System Inventory |
| Task Catalogue ID | 13.04 |
| Primary Layer 1 Phases | P02, P03 |

## Capability Objective

Create a complete inventory of systems contributing data, configuration or operational dependencies to migration.

## Source Implementation Activities

1. Identify source systems.
2. Record ownership and technical details.
3. Assess migration relevance.

## Implementation Tasks

### L10-13.04-001 — Identify Source Systems

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Migration Lead |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Identify all source platforms, applications, repositories and data stores relevant to migration.

**Dependencies**

- L10-13.03-001

**Deliverable**

Source system inventory.

**Acceptance Criteria**

Known migration source systems are recorded.

### L10-13.04-002 — Document Source System Ownership

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Business Analyst |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Record business, technical and data ownership for each source.

**Dependencies**

- L10-13.04-001

**Deliverable**

Source ownership register.

**Acceptance Criteria**

Each source has an accountable owner.

### L10-13.04-003 — Assess Source Migration Readiness

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Migration Lead |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Assess availability, extractability, quality and constraints for each source.

**Dependencies**

- L10-13.04-002

**Deliverable**

Source readiness assessment.

**Acceptance Criteria**

Source constraints and prerequisites are documented.

## Definition of Done

All material migration sources are inventoried, owned and assessed.

---

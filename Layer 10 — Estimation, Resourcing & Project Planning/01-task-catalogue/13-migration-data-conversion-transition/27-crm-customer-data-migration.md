# Layer 10 — 2.13.27 CRM / Customer Data Migration

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 13 — Migration, Data Conversion & Transition |
| Capability ID | 2.13.27 |
| Capability | CRM / Customer Data Migration |
| Task Catalogue ID | 13.27 |
| Primary Layer 1 Phases | P03, P04, P06, P08 |
| Classification | CONDITIONAL |

## Capability Objective

Migrate customer, account, interaction context and CRM-related data required by the target solution.

## Implementation Tasks

### L10-13.27-001 — Assess CRM Data Migration

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P02 |
| Primary Role | Data Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | CONDITIONAL |

**Description**

Identify customer and CRM data required in the target solution.

**Dependencies**

- Data discovery
- Integration architecture

**Deliverable**

CRM migration assessment.

**Acceptance Criteria**

Required CRM datasets are identified.

### L10-13.27-002 — Migrate CRM Data

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Data Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | HYBRID |
| Baseline Effort | 5.0h |
| Critical Path | CONDITIONAL |

**Description**

Transform and load approved CRM/customer data.

**Dependencies**

- L10-13.27-001
- Data mapping

**Deliverable**

Migrated CRM data.

**Acceptance Criteria**

Required CRM data is loaded successfully.

### L10-13.27-003 — Validate CRM Data

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Data Architect |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | HYBRID |
| Baseline Effort | 3.0h |
| Critical Path | CONDITIONAL |

**Description**

Validate customer data, relationships and CRM interaction context.

**Dependencies**

- L10-13.27-002

**Deliverable**

CRM validation report.

**Acceptance Criteria**

Customer data passes agreed validation.

## Definition of Done

Required CRM/customer data is migrated and validated.

---
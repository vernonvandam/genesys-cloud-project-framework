# Layer 10 — 2.13.23 Routing Migration

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 13 — Migration, Data Conversion & Transition |
| Capability ID | 2.13.23 |
| Capability | Routing Migration |
| Task Catalogue ID | 13.23 |
| Primary Layer 1 Phases | P04, P06, P08, P10 |

## Capability Objective

Migrate routing configuration and business rules into the target Genesys Cloud solution.

## Implementation Tasks

### L10-13.23-001 — Assess Source Routing

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

Assess source routing rules, queues, skills, priorities and business logic.

**Dependencies**

- Migration scope
- Queue migration

**Deliverable**

Routing assessment.

**Acceptance Criteria**

Material routing rules are identified.

### L10-13.23-002 — Implement Target Routing

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

Implement approved target routing configuration.

**Dependencies**

- L10-13.23-001
- Skills and queues

**Deliverable**

Target routing configuration.

**Acceptance Criteria**

Routing configuration is deployed.

### L10-13.23-003 — Validate Routing Behaviour

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

Validate routing outcomes against approved business rules.

**Dependencies**

- L10-13.23-002

**Deliverable**

Routing validation results.

**Acceptance Criteria**

Expected routing outcomes are achieved.

## Definition of Done

Routing is migrated, tested and accepted.

---

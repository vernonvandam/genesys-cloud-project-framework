# Layer 10 — 2.13.22 Skill & Language Migration

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 13 — Migration, Data Conversion & Transition |
| Capability ID | 2.13.22 |
| Capability | Skill & Language Migration |
| Task Catalogue ID | 13.22 |
| Primary Layer 1 Phases | P04, P06, P08 |

## Capability Objective

Migrate skills, language requirements and associated agent assignments.

## Implementation Tasks

### L10-13.22-001 — Map Skills and Languages

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

Map source skills and language requirements to the target model.

**Dependencies**

- User migration
- Routing migration

**Deliverable**

Skill and language mapping.

**Acceptance Criteria**

Mappings are approved.

### L10-13.22-002 — Configure Skills and Languages

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

Configure target skills, languages and assignments.

**Dependencies**

- L10-13.22-001

**Deliverable**

Configured skills and languages.

**Acceptance Criteria**

Required objects exist and are correctly assigned.

### L10-13.22-003 — Validate Skill and Language Routing

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

Validate routing using migrated skills and language requirements.

**Dependencies**

- L10-13.22-002

**Deliverable**

Routing validation evidence.

**Acceptance Criteria**

Skill and language routing operates correctly.

## Definition of Done

Skills and languages are migrated and validated.

---
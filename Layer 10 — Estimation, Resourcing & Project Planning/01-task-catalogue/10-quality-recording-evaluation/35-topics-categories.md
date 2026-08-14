# Layer 10 — 2.10.35 Topics & Categories

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Quality Management, Recording & Evaluation |
| Capability ID | 2.10.35 |
| Capability | Topics & Categories |
| Task Catalogue ID | 10.35 |
| Primary Layer 1 Phases | P03, P04, P05, P08, P09 |

## Capability Objective

Define and configure topics and categories used to classify and analyse interactions.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define topic requirements |
| P04 | Design topic taxonomy |
| P05 | Configure topics |
| P08 | Validate classification |
| P09 | Business acceptance |

## Source Implementation Activities

1. Identify analytical topics.
2. Define taxonomy.
3. Configure topics.
4. Validate classification.

## Implementation Tasks

### Activity 01 — Topic Taxonomy

#### L10-10.35-001 — Identify Required Topics and Categories

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Identify topics and categories required for quality, compliance and customer insight.

**Dependencies**

- Analytics requirements

**Deliverable**

Topic catalogue.

**Acceptance Criteria**

Topics are approved.

#### L10-10.35-002 — Design Topic Taxonomy

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Define topic structure, naming, scope and classification rules.

**Dependencies**

- L10-10.35-001

**Deliverable**

Topic taxonomy.

**Acceptance Criteria**

Taxonomy is approved.

### Activity 02 — Configure and Validate

#### L10-10.35-003 — Configure Topics and Categories

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Configure approved topics and categories.

**Dependencies**

- L10-10.35-002

**Deliverable**

Configured topic taxonomy.

**Acceptance Criteria**

Topics are available for analysis.

#### L10-10.35-004 — Validate Topic Classification

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Validate topic detection against representative interactions.

**Dependencies**

- L10-10.35-003

**Deliverable**

Topic validation evidence.

**Acceptance Criteria**

Required classification scenarios pass.

## Definition of Done

Topics and categories are configured and validated.

---

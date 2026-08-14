# Layer 10 — 2.10.34 Speech & Text Analytics

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Quality Management, Recording & Evaluation |
| Capability ID | 2.10.34 |
| Capability | Speech & Text Analytics |
| Task Catalogue ID | 10.34 |
| Primary Layer 1 Phases | P03, P04, P05, P08, P09 |

## Capability Objective

Configure speech and text analytics capabilities to identify quality, compliance and customer experience insights.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define analytics requirements |
| P04 | Design analytics model |
| P05 | Configure analytics |
| P08 | Validate analytics |
| P09 | Business acceptance |

## Source Implementation Activities

1. Define analytics objectives.
2. Define supported interaction scope.
3. Configure analytics.
4. Validate outputs.

## Implementation Tasks

### Activity 01 — Analytics Design

#### L10-10.34-001 — Define Speech and Text Analytics Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Define business questions, interaction scope and analytical outcomes.

**Dependencies**

- Quality strategy

**Deliverable**

Analytics requirements.

**Acceptance Criteria**

Requirements are approved.

#### L10-10.34-002 — Design Speech and Text Analytics Model

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Define languages, analytics scope, topics, sentiment and reporting relationships.

**Dependencies**

- L10-10.34-001

**Deliverable**

Analytics design.

**Acceptance Criteria**

Design is approved.

### Activity 02 — Configure and Validate

#### L10-10.34-003 — Configure Speech and Text Analytics

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | NO |

**Description**

Configure approved speech and text analytics capabilities.

**Dependencies**

- L10-10.34-002

**Deliverable**

Configured analytics.

**Acceptance Criteria**

Analytics processing is enabled for required scenarios.

#### L10-10.34-004 — Validate Analytics Outputs

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Validate analytics processing and expected outputs.

**Dependencies**

- L10-10.34-003

**Deliverable**

Analytics validation evidence.

**Acceptance Criteria**

Expected analytical outputs are produced.

## Definition of Done

Speech and text analytics operate against approved requirements.

---
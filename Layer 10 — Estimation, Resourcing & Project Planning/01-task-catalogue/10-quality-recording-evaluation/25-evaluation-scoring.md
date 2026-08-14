# Layer 10 — 2.10.25 Evaluation Scoring

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Quality Management, Recording & Evaluation |
| Capability ID | 2.10.25 |
| Capability | Evaluation Scoring |
| Task Catalogue ID | 10.25 |
| Primary Layer 1 Phases | P03, P04, P05, P08, P09 |

## Capability Objective

Implement scoring models that produce consistent and meaningful quality evaluation outcomes.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define scoring requirements |
| P04 | Design scoring model |
| P05 | Configure scoring |
| P08 | Validate calculations |
| P09 | Obtain business acceptance |

## Source Implementation Activities

1. Define scoring model.
2. Define weights and thresholds.
3. Configure scoring.
4. Validate outcomes.

## Implementation Tasks

### Activity 01 — Scoring Design

#### L10-10.25-001 — Define Evaluation Scoring Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Quality Lead |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Define scoring rules, weights, thresholds and interpretation.

**Dependencies**

- Evaluation questions

**Deliverable**

Scoring requirements.

**Acceptance Criteria**

Scoring model is approved.

#### L10-10.25-002 — Design Evaluation Scoring Model

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Translate requirements into implementable scoring logic.

**Dependencies**

- L10-10.25-001

**Deliverable**

Scoring design.

**Acceptance Criteria**

Scoring design is approved.

### Activity 02 — Configure and Validate

#### L10-10.25-003 — Configure Evaluation Scoring

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Configure scoring rules and weights.

**Dependencies**

- L10-10.25-002

**Deliverable**

Configured scoring model.

**Acceptance Criteria**

Configured scoring matches design.

#### L10-10.25-004 — Validate Evaluation Scoring

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Test scoring calculations and boundary conditions.

**Dependencies**

- L10-10.25-003

**Deliverable**

Scoring validation evidence.

**Acceptance Criteria**

Expected scores are produced for defined test cases.

## Definition of Done

Scoring produces accurate, repeatable and approved evaluation outcomes.

---

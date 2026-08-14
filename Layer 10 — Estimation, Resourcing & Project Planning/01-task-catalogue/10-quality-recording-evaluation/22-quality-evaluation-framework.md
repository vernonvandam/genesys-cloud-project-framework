# Layer 10 — 2.10.22 Quality Evaluation Framework

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Quality Management, Recording & Evaluation |
| Capability ID | 2.10.22 |
| Capability | Quality Evaluation Framework |
| Task Catalogue ID | 10.22 |
| Primary Layer 1 Phases | P03, P04, P05, P08, P09 |

## Capability Objective

Define the end-to-end quality evaluation framework used to assess interactions and agent performance.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define evaluation requirements |
| P04 | Design evaluation framework |
| P05 | Configure evaluation components |
| P08 | Validate evaluation |
| P09 | Obtain business acceptance |

## Source Implementation Activities

1. Define evaluation objectives.
2. Design evaluation model.
3. Configure evaluation framework.
4. Validate evaluation lifecycle.

## Implementation Tasks

### Activity 01 — Design Framework

#### L10-10.22-001 — Define Evaluation Objectives

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define what the evaluation programme must measure and improve.

**Dependencies**

- Quality strategy

**Deliverable**

Evaluation objectives.

**Acceptance Criteria**

Objectives are approved.

#### L10-10.22-002 — Design Evaluation Framework

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Define forms, questions, scoring, assignment, workflow, calibration and reporting relationships.

**Dependencies**

- L10-10.22-001

**Deliverable**

Evaluation framework design.

**Acceptance Criteria**

Framework is approved.

### Activity 02 — Configure and Validate

#### L10-10.22-003 — Configure Evaluation Framework

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Configure the evaluation framework components.

**Dependencies**

- L10-10.22-002

**Deliverable**

Configured evaluation framework.

**Acceptance Criteria**

Framework components are available.

#### L10-10.22-004 — Validate Evaluation Lifecycle

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

Validate evaluation from interaction selection through completion and reporting.

**Dependencies**

- L10-10.22-003

**Deliverable**

Evaluation lifecycle test evidence.

**Acceptance Criteria**

End-to-end evaluation scenarios pass.

## Definition of Done

The quality evaluation framework is configured and validated.

---

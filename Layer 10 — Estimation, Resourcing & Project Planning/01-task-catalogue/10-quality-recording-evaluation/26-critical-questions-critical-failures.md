# Layer 10 — 2.10.26 Critical Questions & Critical Failures

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Quality Management, Recording & Evaluation |
| Capability ID | 2.10.26 |
| Capability | Critical Questions & Critical Failures |
| Task Catalogue ID | 10.26 |
| Primary Layer 1 Phases | P03, P04, P05, P08, P09 |

## Capability Objective

Identify and implement critical quality conditions that materially affect evaluation outcomes.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define critical-failure requirements |
| P04 | Design critical controls |
| P05 | Configure controls |
| P08 | Validate outcomes |
| P09 | Business acceptance |

## Source Implementation Activities

1. Identify critical questions.
2. Define failure conditions.
3. Configure critical controls.
4. Validate evaluation outcomes.

## Implementation Tasks

### Activity 01 — Define Critical Controls

#### L10-10.26-001 — Identify Critical Evaluation Questions

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

Identify questions where failure represents a material quality, compliance or customer-impact event.

**Dependencies**

- Evaluation questions

**Deliverable**

Critical question catalogue.

**Acceptance Criteria**

Critical questions are approved.

#### L10-10.26-002 — Define Critical Failure Behaviour

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Quality Lead |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Define how critical failures affect scoring, outcomes and follow-up.

**Dependencies**

- L10-10.26-001

**Deliverable**

Critical failure design.

**Acceptance Criteria**

Failure behaviour is approved.

### Activity 02 — Implement and Validate

#### L10-10.26-003 — Configure Critical Failure Controls

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

Configure critical questions and failure behaviour.

**Dependencies**

- L10-10.26-002

**Deliverable**

Configured critical controls.

**Acceptance Criteria**

Controls operate as designed.

#### L10-10.26-004 — Validate Critical Failure Outcomes

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

Test critical pass and failure scenarios.

**Dependencies**

- L10-10.26-003

**Deliverable**

Critical-failure validation evidence.

**Acceptance Criteria**

Expected critical outcomes are produced.

## Definition of Done

Critical quality conditions and failure behaviour are implemented and tested.

---

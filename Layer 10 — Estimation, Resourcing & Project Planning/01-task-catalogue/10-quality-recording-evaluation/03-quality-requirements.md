# Layer 10 — 2.10.03 Quality Requirements

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Quality Management, Recording & Evaluation |
| Capability ID | 2.10.03 |
| Capability | Quality Requirements |
| Task Catalogue ID | 10.03 |
| Primary Layer 1 Phases | P02, P03, P04, P08, P09 |

## Capability Objective

Capture, validate and trace quality management, recording, evaluation and analytics requirements.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P02 | Assess current quality requirements |
| P03 | Capture target requirements |
| P04 | Trace requirements to solution design |
| P08 | Validate requirements |
| P09 | Obtain business acceptance |

## Source Implementation Activities

1. Assess current requirements.
2. Capture target requirements.
3. Establish traceability.
4. Validate requirements.

## Implementation Tasks

### Activity 01 — Requirements Discovery

#### L10-10.03-001 — Assess Current Quality Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Review existing quality, recording, evaluation and compliance requirements.

**Dependencies**

- Current-state discovery

**Deliverable**

Current-state requirements assessment.

**Acceptance Criteria**

Known requirements and gaps are documented.

---

#### L10-10.03-002 — Capture Target Quality Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Capture functional, operational, reporting, compliance and quality requirements.

**Dependencies**

- L10-10.03-001

**Deliverable**

Quality requirements catalogue.

**Acceptance Criteria**

Requirements are documented with owners and priorities.

### Activity 02 — Trace and Validate

#### L10-10.03-003 — Establish Quality Requirement Traceability

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

Map quality requirements to capabilities, configuration, testing and acceptance criteria.

**Dependencies**

- L10-10.03-002

**Deliverable**

Requirements traceability matrix.

**Acceptance Criteria**

Critical requirements have traceable solution and test coverage.

---

#### L10-10.03-004 — Validate Quality Requirements

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P09 |
| Primary Role | Business Analyst |
| Customer Responsibility | YES |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Confirm that implemented capabilities satisfy approved quality requirements.

**Dependencies**

- L10-10.03-003

**Deliverable**

Requirements validation record.

**Acceptance Criteria**

Customer confirms requirements have been satisfied.

## Definition of Done

Quality requirements are approved, traceable, tested and accepted.

---

# Layer 10 — 2.12.22 Quality Management Testing

## Capability Reference

| Attribute | Value |
|---|---|
| Layer 2 Capability | 2.12.22 — Quality Management Testing |
| Layer 10 Domain | 12 — Testing, Validation & Deployment |
| Task Prefix | L10-12.22 |
| Default Classification | CONDITIONAL |
| Primary Layer 1 Phases | P06–P08 |
| Primary Role | Quality Management Specialist |
| Customer Responsibility | JOINT |
| Primary Environment | TEST / UAT |
| Automation | MANUAL |
| Critical Path | CONDITIONAL |

## Capability Objective

Validate quality management policies, evaluations, forms, calibration, scoring, coaching and related workflows where in scope.

## Source Implementation Activities

- Validate quality configuration.
- Test evaluations.
- Test scoring.
- Validate calibration.
- Validate quality workflows.

## Implementation Tasks

### Activity 01 — Validate QM Configuration

#### L10-12.22-001 — Validate Quality Management Baseline

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Quality Management Specialist |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | CONDITIONAL |

**Description**

Validate QM policies, forms, evaluation settings and configuration.

**Dependencies**

Quality Management implementation.

**Deliverable**

QM Configuration Validation.

**Acceptance Criteria**

Configuration matches approved design.

### Activity 02 — Test Evaluations

#### L10-12.22-002 — Execute Evaluation Tests

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P08 |
| Primary Role | Quality Management Specialist |
| Customer Responsibility | JOINT |
| Environment | TEST / UAT |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | CONDITIONAL |

**Description**

Validate evaluation assignment, completion, scoring and results.

**Dependencies**

L10-12.22-001 and Recording Testing.

**Deliverable**

QM Test Results.

**Acceptance Criteria**

Required evaluation workflows operate correctly.

### Activity 03 — Validate Calibration

#### L10-12.22-003 — Validate Calibration and Scoring

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P08 |
| Primary Role | Quality Management Specialist |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | CONDITIONAL |

**Description**

Validate scoring consistency and calibration workflows.

**Dependencies**

L10-12.22-002.

**Deliverable**

Calibration Validation Results.

**Acceptance Criteria**

Scoring and calibration outcomes are acceptable.

## Capability-Level Dependencies

- Recording
- Quality Management
- Analytics
- Identity & Access

## Capability-Level Estimation Considerations

Forms, evaluations, policies, calibration and workflow complexity drive effort.

## Definition of Done

All in-scope quality management functionality passes testing.

---
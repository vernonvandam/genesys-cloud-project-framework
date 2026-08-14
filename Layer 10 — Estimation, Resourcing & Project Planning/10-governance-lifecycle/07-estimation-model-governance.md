# Layer 10 — 10.07 Estimation Model Governance

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Governance & Lifecycle |
| Capability ID | 10.07 |
| Capability | Estimation Model Governance |
| Task Catalogue ID | 10.07 |
| Primary Layer 1 Phases | P03, P04, P12 |

## Capability Objective

Govern estimation formulas, assumptions, multipliers, calibration factors and calculation logic.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define estimation requirements |
| P04 | Establish calculation controls |
| P12 | Review model performance |

## Source Implementation Activities

1. Identify model components.
2. Define calculation controls.
3. Validate model logic.
4. Approve model changes.
5. Review model performance.

## Implementation Tasks

### Activity 01 — Inventory

#### L10-10.07-001 — Inventory Estimation Model Components

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Estimation Lead |
| Customer Responsibility | NO |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Inventory effort baselines, factors, multipliers and calculation rules.

**Dependencies**

- Estimation model

**Deliverable**

Model component inventory.

**Acceptance Criteria**

All calculation components are identified.

### Activity 02 — Validate

#### L10-10.07-002 — Validate Estimation Calculation Logic

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P04 |
| Primary Role | Estimation Lead |
| Customer Responsibility | NO |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Validate formulas and model outputs against known scenarios.

**Dependencies**

- L10-10.07-001

**Deliverable**

Model validation record.

**Acceptance Criteria**

Calculation logic produces expected outputs.

### Activity 03 — Approve

#### L10-10.07-003 — Approve Estimation Model Version

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Methodology Owner |
| Customer Responsibility | NO |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Approve the controlled estimation model version.

**Dependencies**

- L10-10.07-002

**Deliverable**

Approved model version.

**Acceptance Criteria**

Version and approval are recorded.

### Activity 04 — Review

#### L10-10.07-004 — Review Estimation Model Performance

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P12 |
| Primary Role | Estimation Lead |
| Customer Responsibility | NO |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Review model accuracy against actual project outcomes.

**Dependencies**

- Project actuals
- Calibration data

**Deliverable**

Model performance review.

**Acceptance Criteria**

Calibration candidates are identified where required.

## Capability-Level Dependencies

- Estimation model
- Calibration
- Actuals

## Capability-Level Estimation Considerations

Effort depends on model complexity and validation depth.

## Definition of Done

The estimation model is controlled, validated and periodically reviewed.

---
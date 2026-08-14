# Layer 10 — 10.21 Actuals & Variance Management

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Governance & Lifecycle |
| Capability ID | 10.21 |
| Capability | Actuals & Variance Management |
| Task Catalogue ID | 10.21 |
| Primary Layer 1 Phases | P11, P12 |

## Capability Objective

Compare estimated effort and schedule against actual delivery performance.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P11 | Monitor actuals and variance |
| P12 | Complete final variance analysis |

## Source Implementation Activities

1. Capture actuals.
2. Calculate variance.
3. Analyse causes.
4. Define corrective action.
5. Feed calibration.

## Implementation Tasks

### Activity 01 — Capture

#### L10-10.21-001 — Capture Final Delivery Actuals

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P11 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Capture actual effort, duration and task completion.

**Dependencies**

- Project delivery records

**Deliverable**

Actuals dataset.

**Acceptance Criteria**

Actuals are complete for applicable tasks.

### Activity 02 — Calculate

#### L10-10.21-002 — Calculate Estimate Variance

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Estimation Lead |
| Customer Responsibility | NO |
| Environment | MULTI |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Calculate baseline-to-actual effort and schedule variance.

**Dependencies**

- L10-10.21-001
- Approved baseline

**Deliverable**

Variance analysis.

**Acceptance Criteria**

Variance is calculated by applicable dimension.

### Activity 03 — Analyse

#### L10-10.21-003 — Analyse Variance Causes

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Estimation Lead |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Identify root causes of material variance.

**Dependencies**

- L10-10.21-002

**Deliverable**

Variance root-cause analysis.

**Acceptance Criteria**

Material variances have documented causes.

### Activity 04 — Feed Back

#### L10-10.21-004 — Feed Variance into Calibration

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Estimation Lead |
| Customer Responsibility | NO |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Identify estimation-model improvements from observed variance.

**Dependencies**

- L10-10.21-003

**Deliverable**

Calibration feedback.

**Acceptance Criteria**

Material calibration candidates are recorded.

## Capability-Level Dependencies

- Baseline
- Actuals
- Calibration

## Capability-Level Estimation Considerations

Effort is driven by number of tasks and depth of variance analysis.

## Definition of Done

Actuals, variance, root causes and calibration inputs are documented.

---
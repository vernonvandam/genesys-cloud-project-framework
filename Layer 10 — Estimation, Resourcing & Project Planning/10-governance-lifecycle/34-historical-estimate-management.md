# Layer 10 — 10.34 Historical Estimate Management

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Governance & Lifecycle |
| Capability ID | 10.34 |
| Capability | Historical Estimate Management |
| Task Catalogue ID | 10.34 |
| Primary Layer 1 Phases | P12 |

## Capability Objective

Maintain historical estimates and actual delivery data for future benchmarking and calibration.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P12 | Capture and archive historical estimate data |

## Source Implementation Activities

1. Collect final estimate.
2. Collect actuals.
3. Reconcile outcomes.
4. Archive historical record.
5. Make available for calibration.

## Implementation Tasks

### Activity 01 — Collect

#### L10-10.34-001 — Collect Final Estimate Record

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Estimation Lead |
| Customer Responsibility | NO |
| Environment | MULTI |
| Automation | HYBRID |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Capture final approved estimate and baseline information.

**Dependencies**

- Project closure
- Estimate version control

**Deliverable**

Final estimate record.

**Acceptance Criteria**

Final estimate is complete.

### Activity 02 — Collect Actuals

#### L10-10.34-002 — Collect Final Actual Delivery Data

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Capture final effort, duration, roles and task outcomes.

**Dependencies**

- Actuals management

**Deliverable**

Final actual dataset.

**Acceptance Criteria**

Actuals are complete.

### Activity 03 — Reconcile

#### L10-10.34-003 — Reconcile Historical Estimate Record

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P12 |
| Primary Role | Estimation Lead |
| Customer Responsibility | NO |
| Environment | MULTI |
| Automation | HYBRID |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Reconcile estimate, actuals and variance before archival.

**Dependencies**

- L10-10.34-001
- L10-10.34-002

**Deliverable**

Reconciled historical record.

**Acceptance Criteria**

Estimate and actuals reconcile.

### Activity 04 — Archive

#### L10-10.34-004 — Archive Historical Estimate Record

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Methodology Owner |
| Customer Responsibility | NO |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Archive the project estimate and outcome for future calibration.

**Dependencies**

- L10-10.34-003

**Deliverable**

Historical estimate record.

**Acceptance Criteria**

Historical record is retrievable and protected from uncontrolled alteration.

## Capability-Level Dependencies

- Estimate
- Actuals
- Variance

## Capability-Level Estimation Considerations

Archival effort is low but data quality requirements are high.

## Definition of Done

Historical estimate and actual delivery data is reconciled and archived.

---
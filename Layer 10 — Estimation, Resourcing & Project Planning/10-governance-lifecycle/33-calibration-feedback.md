# Layer 10 — 10.33 Calibration Feedback

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Governance & Lifecycle |
| Capability ID | 10.33 |
| Capability | Calibration Feedback |
| Task Catalogue ID | 10.33 |
| Primary Layer 1 Phases | P11, P12 |

## Capability Objective

Convert project actuals and variance evidence into controlled estimation-model calibration.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P11 | Identify calibration candidates |
| P12 | Approve calibration inputs |

## Source Implementation Activities

1. Collect actuals.
2. Analyse variance.
3. Identify calibration candidates.
4. Validate candidates.
5. Approve calibration input.

## Implementation Tasks

### Activity 01 — Collect

#### L10-10.33-001 — Collect Calibration Evidence

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P11 |
| Primary Role | Estimation Lead |
| Customer Responsibility | NO |
| Environment | MULTI |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Collect actual effort, duration and variance data.

**Dependencies**

- Actuals
- Variance management

**Deliverable**

Calibration evidence set.

**Acceptance Criteria**

Evidence is complete.

### Activity 02 — Analyse

#### L10-10.33-002 — Analyse Calibration Candidates

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Estimation Lead |
| Customer Responsibility | NO |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Identify recurring patterns that may justify estimation model changes.

**Dependencies**

- L10-10.33-001

**Deliverable**

Calibration candidate analysis.

**Acceptance Criteria**

Candidates are evidence-based.

### Activity 03 — Validate

#### L10-10.33-003 — Validate Calibration Candidate

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P12 |
| Primary Role | Estimation Lead |
| Customer Responsibility | NO |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Validate candidate changes against historical and current evidence.

**Dependencies**

- L10-10.33-002

**Deliverable**

Calibration validation.

**Acceptance Criteria**

Candidate is confirmed, rejected or deferred.

### Activity 04 — Approve

#### L10-10.33-004 — Approve Calibration Input

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Methodology Owner |
| Customer Responsibility | NO |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Approve validated calibration input for future model changes.

**Dependencies**

- L10-10.33-003

**Deliverable**

Approved calibration input.

**Acceptance Criteria**

Calibration input is recorded in the improvement backlog.

## Capability-Level Dependencies

- Actuals
- Variance analysis
- Historical estimates

## Capability-Level Estimation Considerations

Calibration effort depends on data volume and statistical complexity.

## Definition of Done

Evidence-based calibration feedback is validated and approved.

---
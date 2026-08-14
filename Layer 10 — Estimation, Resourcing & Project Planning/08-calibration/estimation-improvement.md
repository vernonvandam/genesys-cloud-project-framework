# Layer 10 — Estimation Improvement

## Purpose

This document defines how calibration findings are converted into controlled improvements to the Genesys Cloud Project Framework estimation and planning models.

The objective is not simply to adjust numbers.

The objective is to improve the quality, accuracy and predictability of the complete Layer 10 model.

---

# 1. Improvement Scope

Model improvement may apply to:

- task definitions
- task granularity
- task types
- task effort
- task duration
- complexity factors
- role factors
- customer effort
- dependency assumptions
- scheduling assumptions
- environment assumptions
- implementation activities
- capability scope
- domain scope
- estimation guidance

---

# 2. Improvement Sources

Model improvements may originate from:

- estimation calibration
- variance analysis
- historical comparison
- project retrospectives
- project closure
- delivery-team feedback
- customer feedback
- recurring issues
- task omissions
- estimation errors
- technology changes
- Genesys Cloud platform changes
- methodology changes

---

# 3. Improvement Lifecycle

```text
Calibration Finding
        ↓
Problem Definition
        ↓
Evidence Review
        ↓
Root Cause
        ↓
Improvement Proposal
        ↓
Impact Assessment
        ↓
Review
        ↓
Approval
        ↓
Model Update
        ↓
Version Increment
        ↓
Future Project Usage
```

---

# 4. Improvement Types

## 4.1 Baseline Effort Adjustment

Example:

```text
Existing baseline = 8h
Approved baseline = 10h
```

Used where repeated evidence demonstrates systematic under-estimation.

---

## 4.2 Baseline Duration Adjustment

Used when elapsed delivery time is consistently inaccurate.

Duration must remain separate from effort.

---

## 4.3 Complexity Factor Adjustment

Example:

```text
Standard complexity factor = 1.00

High complexity factor
Existing = 1.25
New = 1.35
```

---

## 4.4 Role Factor Adjustment

Used where the expected role effort is systematically inaccurate.

---

## 4.5 Task Addition

A new task should be created when recurring work is not represented in the catalogue.

Example:

```text
Observed recurring activity
        ↓
Not represented by existing task
        ↓
Create new task
        ↓
Assign Layer 1 mapping
        ↓
Assign Layer 2 capability
        ↓
Estimate
        ↓
Add to catalogue
```

---

## 4.6 Task Decomposition

A task may be decomposed when it consistently contains multiple independent outcomes.

Example:

```text
Existing Task
Configure Integration

Observed Work
    ├── Design
    ├── Build
    ├── Security Configuration
    ├── Testing
    └── Deployment

Improvement
Split into separate tasks
```

---

## 4.7 Task Consolidation

Tasks may be consolidated where excessive decomposition creates unnecessary project-management overhead and no meaningful estimation benefit.

---

## 4.8 Dependency Improvement

A recurring dependency may require:

- explicit dependency
- dependency type change
- sequencing adjustment
- customer prerequisite
- external dependency classification

---

## 4.9 Customer Responsibility Improvement

If repeated projects show customer work being omitted or underestimated, the customer responsibility model should be updated.

---

# 5. Improvement Proposal

Every proposed change should include:

| Attribute | Requirement |
|---|---|
| Change ID | REQUIRED |
| Date | REQUIRED |
| Source Projects | REQUIRED |
| Affected Layer | REQUIRED |
| Affected File | REQUIRED |
| Current Value | REQUIRED |
| Proposed Value | REQUIRED |
| Reason | REQUIRED |
| Evidence | REQUIRED |
| Impact | REQUIRED |
| Confidence | REQUIRED |
| Owner | REQUIRED |
| Approval | REQUIRED |
| Effective Version | REQUIRED |

---

# 6. Evidence Standard

Improvement proposals should identify:

- project evidence
- task evidence
- variance evidence
- historical evidence
- customer evidence
- technical evidence

Evidence should be traceable to source project records.

---

# 7. Improvement Confidence

Use:

```text
LOW
MEDIUM
HIGH
VERY HIGH
```

A model change based on LOW confidence evidence should normally be deferred unless there is a compelling methodology or technical reason.

---

# 8. Change Impact

Each proposed change should assess impact on:

- task catalogue
- task standards
- estimation model
- role catalogue
- dependency model
- project schedule model
- spreadsheet model
- calibration model
- existing project estimates
- future projects

---

# 9. Layer 10 Impact Assessment

A change to one model may affect other models.

Example:

```text
Task Baseline Changed
        ↓
Estimation Model
        ↓
Project Effort
        ↓
Role Loading
        ↓
Schedule
        ↓
Spreadsheet Calculations
        ↓
Calibration Baseline
```

Changes must therefore be assessed across Layer 10 rather than treated as isolated edits.

---

# 10. Model Versioning

Every material model change should increment the model version.

Example:

```text
v1.0
Baseline methodology

v1.1
Minor task and estimate refinements

v1.2
Role factor improvements

v2.0
Major estimation methodology change
```

Versioning rules should distinguish minor and major changes.

---

# 11. Historical Integrity

When a model changes:

```text
Project A
Estimated under v1.0
        ↓
Completed
        ↓
Calibration
        ↓
Model v1.1
```

Project A remains associated with v1.0.

It must not be retrospectively recalculated using v1.1 unless explicitly required for analytical purposes.

---

# 12. Improvement Approval

Material changes should be reviewed by the appropriate framework owner.

Approval should consider:

- evidence quality
- sample size
- business impact
- estimation impact
- delivery impact
- consistency with methodology
- downstream model impact

---

# 13. Improvement Implementation

Once approved:

1. Update the authoritative source model.
2. Update affected documentation.
3. Update task baselines.
4. Update factors where required.
5. Update spreadsheet reference data.
6. Update estimation calculations.
7. Update dependency assumptions where required.
8. Update schedule assumptions where required.
9. Record model version.
10. Document the change.
11. Make the change effective for future estimates.

---

# 14. Improvement Validation

After implementation, the change should be monitored against subsequent projects.

Example:

```text
Problem
Task consistently underestimated by 20%

Improvement
Baseline increased by 15%

Next Projects
+5%
+8%
-2%
+4%

Result
Improvement appears effective.
```

Calibration should continue to validate the change.

---

# 15. Improvement Register

The framework should maintain an improvement register.

| Field | Description |
|---|---|
| Improvement ID | Unique identifier |
| Finding | Calibration finding |
| Source | Project evidence |
| Model Area | Affected model |
| Current State | Existing assumption |
| Proposed State | New assumption |
| Evidence | Supporting evidence |
| Confidence | Confidence level |
| Impact | Impact assessment |
| Decision | Approved / Rejected / Deferred |
| Model Version | Version implemented |
| Effective Date | Date active |
| Validation | Post-change outcome |

---

# 16. Model Improvement Categories

The improvement register should support:

```text
TASK
EFFORT
DURATION
ROLE
DEPENDENCY
CUSTOMER
COMPLEXITY
SCHEDULE
SCOPE
WORKFLOW
DATA
TOOLING
METHODOLOGY
```

---

# 17. Preventing Over-Calibration

The framework must avoid excessive changes based on noise.

Do not modify the model simply because:

- one project was unusual
- one task had an isolated defect
- a customer delayed a decision
- scope changed
- an exceptional resource issue occurred
- an external system failed

Instead determine whether the issue is:

```text
Systematic
        OR
Project-Specific
```

Only systematic or materially justified findings should normally alter the baseline model.

---

# 18. Improvement Prioritisation

Changes should be prioritised based on:

- frequency
- effort impact
- schedule impact
- financial impact
- customer impact
- critical-path impact
- confidence
- number of future projects affected

Example:

| Priority | Criteria |
|---|---|
| HIGH | Significant recurring model error |
| MEDIUM | Moderate recurring error |
| LOW | Small or isolated improvement |

---

# 19. Improvement Governance

The model must maintain:

- change history
- model versions
- approval history
- source evidence
- effective dates
- affected documents
- affected calculations
- validation results

---

# 20. Definition of Done

An estimation improvement is complete when:

- calibration evidence exists
- root cause is understood
- improvement is defined
- impact is assessed
- confidence is established
- change is approved
- authoritative model is updated
- dependent models are reviewed
- version is incremented where required
- change is documented
- future projects can consume the improvement
- post-change validation is planned

---

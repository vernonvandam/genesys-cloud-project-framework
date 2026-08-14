# Layer 10 — 08 Calibration

## Purpose

The Calibration Model defines how the Genesys Cloud Project Framework measures actual project performance against the baseline estimation, scheduling, resourcing, dependency and effort assumptions established by Layer 10.

Calibration is the mechanism by which the framework improves over time.

The calibration model consumes project delivery evidence and uses it to identify:

- estimation variance
- effort variance
- duration variance
- role variance
- dependency variance
- task sizing variance
- complexity variance
- project-specific factors
- recurring estimation errors
- inaccurate baseline assumptions
- opportunities for model improvement

Calibration must improve the authoritative Layer 10 models without compromising historical traceability.

---

# Repository Structure

```text
08-calibration/
│
├── README.md
├── estimation-calibration.md
├── variance-analysis.md
├── historical-project-comparison.md
└── estimation-improvement.md
```

---

# Document Catalogue

| File | Purpose |
|---|---|
| `README.md` | Calibration methodology, governance and lifecycle |
| `estimation-calibration.md` | Defines how baseline estimates are compared with actual project outcomes |
| `variance-analysis.md` | Defines analysis of effort, duration, resource and schedule variance |
| `historical-project-comparison.md` | Defines comparison of current projects against completed projects |
| `estimation-improvement.md` | Defines how calibration findings are converted into improvements to the estimation model |

---

# Position Within Layer 10

Calibration is the eighth component of Layer 10.

```text
01 — Task Catalogue
        ↓
02 — Task Standards
        ↓
03 — Estimation Model
        ↓
04 — Role Catalogue
        ↓
05 — Dependency Model
        ↓
06 — Project Schedule Model
        ↓
07 — Spreadsheet Model
        ↓
08 — Calibration
```

The relationship is:

```text
Task Catalogue
What work exists?
        ↓
Task Standards
How must work be represented?
        ↓
Estimation Model
What should the work cost in effort?
        ↓
Role Catalogue
Who performs the work?
        ↓
Dependency Model
What must happen before what?
        ↓
Project Schedule Model
How should work be sequenced?
        ↓
Spreadsheet Model
How is the model operationalised?
        ↓
Project Delivery
What actually happened?
        ↓
Calibration
How accurate was the model?
        ↓
Model Improvement
What should change?
```

---

# 1. Calibration Objectives

The Calibration Model shall provide a repeatable mechanism to:

1. Capture actual project performance.
2. Compare actual effort against baseline effort.
3. Compare actual duration against baseline duration.
4. Compare planned resources against actual resources.
5. Identify estimation variance.
6. Identify recurring variance patterns.
7. Identify task-level estimation weaknesses.
8. Identify capability-level estimation weaknesses.
9. Identify role-level estimation weaknesses.
10. Identify project complexity factors.
11. Identify customer dependency impacts.
12. Identify environmental impacts.
13. Identify migration and integration impacts.
14. Compare similar historical projects.
15. Identify systemic estimation bias.
16. Improve baseline effort assumptions.
17. Improve duration assumptions.
18. Improve complexity factors.
19. Improve role assumptions.
20. Improve dependency assumptions.
21. Preserve historical baseline estimates.
22. Prevent retrospective rewriting of historical estimates.
23. Provide evidence for future estimates.
24. Improve estimation confidence over time.

---

# 2. Calibration Principles

Calibration shall follow these principles.

## 2.1 Preserve Historical Baselines

Once a project baseline has been approved, its baseline values must remain unchanged.

```text
Original Baseline
       ↓
Project Execution
       ↓
Actual Outcome
       ↓
Variance Analysis
       ↓
Calibration Finding
       ↓
Future Model Improvement
```

The original estimate must not be overwritten to make historical performance appear more accurate.

---

## 2.2 Separate Estimate From Actual

The framework must maintain separate values for:

- baseline effort
- approved project effort
- forecast effort
- actual effort
- baseline duration
- approved project duration
- actual duration

Example:

```text
Baseline Effort       = 8 hours
Project Estimate      = 10 hours
Actual Effort         = 14 hours
```

The original 8-hour baseline remains unchanged.

---

## 2.3 Calibrate From Evidence

Model changes should be supported by delivery evidence.

Evidence may include:

- completed task records
- actual timesheets
- project schedules
- task status history
- resource allocation
- project change records
- dependency records
- issue records
- customer delays
- environment delays
- technical complexity
- implementation notes
- migration results
- testing results
- project closure reports

---

## 2.4 Do Not Calibrate From Isolated Exceptions

A single unusual project should not automatically change the enterprise baseline.

Potential model changes should consider:

- sample size
- project comparability
- recurring variance
- confidence
- complexity
- customer-specific conditions
- technology-specific conditions
- delivery-team-specific conditions

---

## 2.5 Separate Model Error From Project Variance

Not all variance indicates a bad baseline.

Variance may be caused by:

```text
Model Error
    OR
Project Complexity
    OR
Customer Dependency
    OR
Scope Change
    OR
Resource Constraint
    OR
Technical Issue
    OR
External Dependency
```

The calibration process must determine the probable cause before changing the baseline model.

---

# 3. Calibration Inputs

The calibration process should consume information from:

| Source | Calibration Input |
|---|---|
| Layer 10 Task Catalogue | Task definition |
| Task Standards | Task attributes |
| Estimation Model | Baseline effort and factors |
| Role Catalogue | Role and resource assumptions |
| Dependency Model | Dependency assumptions |
| Project Schedule Model | Duration and sequencing assumptions |
| Spreadsheet Model | Planned and actual project records |
| Project Timesheets | Actual effort |
| Project Schedule | Actual dates |
| Project Closure | Final project outcomes |
| Change Control | Scope changes |
| RAID Log | Risks, assumptions and issues |
| Customer Records | Customer-driven variance |
| Delivery Retrospective | Qualitative evidence |

---

# 4. Calibration Lifecycle

```text
Project Baseline
      ↓
Project Delivery
      ↓
Actual Effort / Duration Capture
      ↓
Project Closure
      ↓
Data Quality Review
      ↓
Baseline vs Actual Comparison
      ↓
Variance Analysis
      ↓
Root Cause Analysis
      ↓
Historical Project Comparison
      ↓
Calibration Findings
      ↓
Model Improvement Proposal
      ↓
Review / Approval
      ↓
Updated Baseline Model
      ↓
Future Project Estimates
```

---

# 5. Calibration Levels

Calibration should occur at multiple levels.

## Level 1 — Task

Example:

```text
L10-01.01-001
```

Determine whether the baseline for the individual task is accurate.

---

## Level 2 — Capability

Example:

```text
Core Platform
Platform Provisioning
```

Determine whether the collection of tasks associated with a capability is correctly sized.

---

## Level 3 — Domain

Example:

```text
03 — Voice & Telephony
```

Determine whether the domain's overall estimation model is accurate.

---

## Level 4 — Role

Determine whether the assumed effort assigned to particular delivery roles is accurate.

---

## Level 5 — Project

Determine whether the project-level model accurately represented the project.

---

## Level 6 — Portfolio

Determine whether the model is consistently accurate across multiple projects.

---

# 6. Calibration Metrics

The model should support at least:

### Absolute Variance

```text
Absolute Variance
= Actual - Baseline
```

### Percentage Variance

```text
Variance %
= ((Actual - Baseline) / Baseline) × 100
```

### Effort Accuracy

```text
Effort Accuracy %
= (Baseline / Actual) × 100
```

### Schedule Variance

```text
Schedule Variance
= Actual Duration - Baseline Duration
```

### Resource Variance

```text
Resource Variance
= Actual Resource Requirement - Planned Resource Requirement
```

Additional metrics may be introduced as the calibration model matures.

---

# 7. Variance Classification

Variance should be classified as:

- UNDER ESTIMATE
- OVER ESTIMATE
- ON TARGET
- PROJECT-SPECIFIC
- SCOPE-DRIVEN
- CUSTOMER-DRIVEN
- TECHNICAL
- RESOURCE-DRIVEN
- DEPENDENCY-DRIVEN
- DATA-DRIVEN
- ENVIRONMENT-DRIVEN
- UNKNOWN

The classification should distinguish model performance from external project conditions.

---

# 8. Calibration Thresholds

Initial calibration thresholds may be established as:

| Variance | Classification | Action |
|---|---|---|
| 0–10% | Within tolerance | Monitor |
| >10–20% | Moderate | Review |
| >20–30% | Significant | Root-cause analysis |
| >30% | Material | Model review required |

These thresholds are starting points rather than permanent values.

The thresholds themselves should be reviewed as historical project data accumulates.

---

# 9. Calibration Governance

Calibration changes should be governed.

At minimum:

- baseline values must be version controlled
- changes must be documented
- changes must have evidence
- changes must have an identified reason
- historical estimates must remain unchanged
- material changes should be reviewed
- model versions must be identifiable
- calibration findings must be traceable to project evidence

---

# 10. Model Versioning

The estimation model should support versioning.

Example:

```text
Estimation Model v1.0
        ↓
Project A
        ↓
Calibration
        ↓
Estimation Model v1.1
        ↓
Project B
        ↓
Calibration
        ↓
Estimation Model v1.2
```

A project must retain the model version used to create its estimate.

---

# 11. Calibration Outputs

Calibration should produce:

- variance analysis
- calibration findings
- root-cause analysis
- historical comparisons
- baseline adjustment recommendations
- estimation factor recommendations
- role adjustment recommendations
- duration adjustment recommendations
- dependency adjustment recommendations
- model change proposals
- approved model updates
- calibration history

---

# 12. Relationship to Future Estimates

The calibration model creates a feedback loop.

```text
Historical Projects
        ↓
Actual Performance
        ↓
Calibration
        ↓
Model Improvement
        ↓
Improved Baselines
        ↓
Future Estimates
        ↓
Future Projects
        ↓
New Actual Performance
        ↓
Calibration
```

The framework therefore becomes progressively more accurate as delivery evidence accumulates.

---

# 13. Definition of Done

The Calibration Model is complete when:

- actual project data can be captured
- baseline values can be preserved
- actuals can be compared with baselines
- variance can be calculated
- variance can be classified
- root causes can be recorded
- historical projects can be compared
- calibration findings can be documented
- model improvement recommendations can be created
- approved changes can be version controlled
- historical project estimates remain traceable
- future estimates can consume calibrated values
- the calibration process can be repeated consistently

---

# 14. Calibration Governance Principle

Calibration is not a mechanism for making estimates retrospectively look accurate.

It is a mechanism for making future estimates more accurate.

```text
Do not change history.
        ↓
Understand the variance.
        ↓
Identify the cause.
        ↓
Determine whether the model was wrong.
        ↓
Change the model only where evidence supports it.
        ↓
Apply the improvement to future estimates.
```

---

# Phase Completion

The Layer 10/08 Calibration component is complete when all calibration documents are implemented and the model provides a controlled feedback mechanism from completed projects into future estimation, scheduling, resourcing and planning.
# Layer 10 — Estimation Calibration

## Purpose

This document defines the method used to compare baseline estimates with actual project delivery outcomes.

Estimation calibration determines whether the Layer 10 estimation assumptions accurately predicted the effort required to deliver Genesys Cloud implementation tasks.

The process must distinguish between:

- estimation error
- project-specific complexity
- scope change
- customer dependency
- technical issues
- resource constraints
- external dependencies
- data quality problems
- scheduling constraints

The objective is to improve future estimates without rewriting historical project baselines.

---

# 1. Calibration Scope

Calibration applies to:

- task effort
- task duration
- capability effort
- domain effort
- role effort
- customer effort
- delivery effort
- resource loading
- project effort
- project duration
- dependency assumptions
- complexity factors
- estimation factors

---

# 2. Required Inputs

For each completed project, calibration should obtain:

| Input | Required |
|---|---|
| Task ID | YES |
| Baseline Effort | YES |
| Approved Project Estimate | YES |
| Actual Effort | YES |
| Baseline Duration | YES where applicable |
| Actual Duration | YES where applicable |
| Primary Role | YES |
| Customer Responsibility | YES |
| Layer 1 Phase | YES |
| Layer 2 Domain | YES |
| Layer 2 Capability | YES |
| Task Type | YES |
| Dependencies | YES |
| Project Complexity | YES |
| Scope Changes | YES |
| Variance Cause | YES where known |

---

# 3. Baseline Hierarchy

Calibration should preserve three distinct estimate levels.

```text
Baseline Model Estimate
        ↓
Project-Specific Estimate
        ↓
Actual Delivery
```

### Baseline Model Estimate

The standard estimate from the Layer 10 estimation model.

### Project-Specific Estimate

The approved estimate after applying project-specific factors.

### Actual Delivery

The actual effort and duration recorded during delivery.

---

# 4. Calibration Record

A calibration record should contain:

| Field | Description |
|---|---|
| Project ID | Project identifier |
| Task ID | Layer 10 task identifier |
| Model Version | Estimation model version |
| Baseline Effort | Original model estimate |
| Project Estimate | Approved project estimate |
| Actual Effort | Recorded actual effort |
| Effort Variance | Actual minus baseline |
| Effort Variance % | Percentage variance |
| Baseline Duration | Original expected duration |
| Actual Duration | Recorded duration |
| Duration Variance | Actual minus baseline |
| Primary Role | Delivery role |
| Complexity | Project/task complexity |
| Variance Cause | Primary variance reason |
| Corrective Action | Required model action |
| Calibration Status | Review status |

---

# 5. Calibration Process

## Step 1 — Freeze Historical Baseline

Capture the original approved estimate.

The original value must never be replaced with actuals.

---

## Step 2 — Capture Actuals

Collect actual:

- effort
- duration
- resources
- dependencies
- dates
- customer delays
- scope changes

---

## Step 3 — Validate Actual Data

Review the quality of actual data.

Identify:

- missing timesheets
- incorrectly allocated effort
- duplicated effort
- unrecorded customer activity
- unrecorded scope changes
- inaccurate task status
- incomplete duration records

Poor-quality actuals should not be used to recalibrate the model.

---

## Step 4 — Calculate Variance

Calculate effort and duration variance.

```text
Effort Variance
= Actual Effort - Baseline Effort
```

```text
Effort Variance %
= ((Actual Effort - Baseline Effort) / Baseline Effort) × 100
```

---

## Step 5 — Analyse Cause

Determine why the variance occurred.

Example:

```text
Baseline
8 hours

Actual
14 hours

Variance
+6 hours / +75%

Cause
Customer data unavailable
+ technical troubleshooting
+ additional configuration
```

The result must not automatically be interpreted as a baseline-estimation error.

---

## Step 6 — Compare With Project Estimate

Where project-specific estimation factors were applied:

```text
Baseline
    ↓
Project Adjustment
    ↓
Approved Estimate
    ↓
Actual
```

This allows the team to determine whether:

- the baseline was wrong
- the adjustment was wrong
- the actual was caused by an external condition

---

## Step 7 — Determine Calibration Action

Possible actions:

- no change
- monitor
- adjust task baseline
- adjust complexity factor
- adjust role factor
- adjust duration
- add conditional task
- revise task granularity
- revise dependency
- revise customer responsibility
- revise estimation guidance

---

# 6. Calibration Decision Matrix

| Finding | Model Action |
|---|---|
| Small isolated variance | No change |
| Recurring variance | Investigate baseline |
| Consistent under-estimation | Increase baseline |
| Consistent over-estimation | Reduce baseline |
| Variance caused by complexity | Improve complexity factor |
| Variance caused by customer dependency | Improve customer/dependency factor |
| Variance caused by missing work | Add task |
| Variance caused by poor task decomposition | Rework task structure |
| Variance caused by scope change | No baseline change |
| Variance caused by unique technical issue | Document exception |
| Actual data unreliable | Exclude from calibration |

---

# 7. Task-Level Calibration

Task-level calibration should identify:

- baseline effort
- actual effort
- variance
- variance percentage
- variance cause
- number of historical occurrences
- mean actual effort
- median actual effort
- range
- standard deviation where sufficient data exists

Example:

```text
Task: L10-01.01-001

Baseline: 8h

Historical Actuals:
7h
9h
8h
12h
10h

Median: 9h
Mean: 9.2h

Finding:
Baseline may be slightly low.
```

---

# 8. Capability-Level Calibration

Aggregate tasks belonging to a Layer 2 capability.

Example:

```text
Platform Provisioning

Task 001   8h
Task 002   4h
Task 003   6h
Task 004   3h

Baseline Total = 21h

Actual Total = 27h

Variance = +6h / +28.6%
```

Capability-level variance may indicate that individual tasks are correctly estimated but that the overall capability contains missing or underestimated work.

---

# 9. Domain-Level Calibration

Aggregate capability results by Layer 2 domain.

Example:

```text
03 — Voice & Telephony

Baseline       240h
Actual         276h
Variance        +36h
Variance %      +15%
```

Domain-level calibration should investigate whether the domain is systematically under-estimated.

---

# 10. Role-Level Calibration

Compare estimated and actual effort by role.

Example:

```text
Genesys Cloud Engineer

Baseline       420h
Actual         475h
Variance        +55h
Variance %      +13.1%
```

Possible findings include:

- role baseline too low
- insufficient task allocation
- role performing work outside expected scope
- supporting role not captured
- customer activities incorrectly assigned

---

# 11. Customer Effort Calibration

Customer effort must be calibrated separately from delivery-team effort.

Example:

```text
Delivery Effort
Baseline = 300h
Actual   = 315h

Customer Effort
Baseline = 80h
Actual   = 140h
```

The delivery estimate may be accurate even if customer effort was materially underestimated.

---

# 12. Duration Calibration

Effort and duration must be analysed independently.

Example:

```text
Effort
Baseline = 16h
Actual   = 15h

Duration
Baseline = 3 days
Actual   = 7 days
```

Potential causes include:

- approval delays
- customer availability
- environment availability
- testing windows
- dependency sequencing
- release windows
- change freezes

This should not result in increasing the task effort baseline.

---

# 13. Calibration Confidence

Each calibration finding should have a confidence classification.

| Confidence | Meaning |
|---|---|
| LOW | Limited or unreliable evidence |
| MEDIUM | Some supporting evidence |
| HIGH | Repeated reliable evidence |
| VERY HIGH | Strong recurring evidence across comparable projects |

Model changes should normally require MEDIUM or HIGH confidence.

---

# 14. Sample Size

Calibration should consider the number of historical observations.

```text
1 project
    ↓
Observation

2–4 projects
    ↓
Emerging pattern

5+ comparable projects
    ↓
Potential calibration baseline

10+ comparable projects
    ↓
Strong statistical evidence
```

These are guidance thresholds rather than mandatory statistical rules.

---

# 15. Calibration Outputs

Each calibration cycle should produce:

- variance results
- root-cause findings
- confidence rating
- recommended model action
- model-change rationale
- calibration approval
- updated model version where applicable

---

# 16. Definition of Done

Estimation calibration is complete when:

- historical baseline is preserved
- actuals are validated
- variance is calculated
- causes are classified
- project-specific factors are considered
- task-level results are reviewed
- capability-level results are reviewed
- domain-level patterns are reviewed
- role-level patterns are reviewed
- customer effort is reviewed
- duration is reviewed separately
- calibration confidence is assessed
- model-change recommendations are documented

---

# Phase Completion

A calibration cycle is complete when the project has produced an evidence-based assessment of estimation accuracy and identified whether any Layer 10 model changes are warranted.
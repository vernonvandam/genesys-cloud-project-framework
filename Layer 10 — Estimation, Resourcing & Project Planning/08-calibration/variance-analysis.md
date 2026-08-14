# Layer 10 — Variance Analysis

## Purpose

This document defines the method for analysing variance between the Layer 10 baseline model, approved project estimates and actual project delivery.

Variance analysis is used to determine whether differences are caused by estimation error or by conditions specific to the project.

---

# 1. Variance Model

The primary comparison is:

```text
Baseline
    ↓
Approved Project Estimate
    ↓
Actual
```

Each transition must be analysed independently.

---

# 2. Variance Types

The model shall support:

- effort variance
- duration variance
- resource variance
- role variance
- dependency variance
- customer effort variance
- delivery effort variance
- schedule variance
- milestone variance
- capability variance
- domain variance

---

# 3. Effort Variance

```text
Effort Variance
= Actual Effort - Baseline Effort
```

Example:

```text
Baseline = 10h
Actual   = 13h

Variance = +3h
```

---

# 4. Percentage Variance

```text
Variance %
= ((Actual - Baseline) / Baseline) × 100
```

Example:

```text
Baseline = 10h
Actual   = 13h

Variance %
= ((13 - 10) / 10) × 100
= 30%
```

---

# 5. Variance Direction

| Result | Meaning |
|---|---|
| Positive | Actual exceeded baseline |
| Negative | Actual was below baseline |
| Zero | Actual matched baseline |

---

# 6. Variance Classification

Variance should be classified using:

```text
MODEL
PROJECT
SCOPE
CUSTOMER
RESOURCE
DEPENDENCY
TECHNICAL
DATA
ENVIRONMENT
EXTERNAL
UNKNOWN
```

---

# 7. Root Cause Analysis

Variance analysis must determine the primary cause.

Example:

```text
Task
L10-08.15-003

Baseline
12h

Actual
20h

Variance
+8h / +66.7%

Analysis

4h — Additional API troubleshooting
2h — Customer test-data delay
2h — Configuration complexity

Conclusion

Not a pure estimation-model error.
```

---

# 8. Variance Categories

## 8.1 Model Variance

The baseline assumption was inaccurate.

Examples:

- task effort underestimated
- task effort overestimated
- missing implementation activity
- incorrect complexity factor
- incorrect role assumption

---

## 8.2 Scope Variance

Work changed after the baseline was created.

Examples:

- additional queues
- additional flows
- additional integrations
- additional regions
- additional languages

Scope variance should normally not change the baseline.

---

## 8.3 Customer Variance

Customer dependencies affected delivery.

Examples:

- delayed approvals
- unavailable SMEs
- delayed data
- unavailable test users
- delayed infrastructure
- delayed business decisions

---

## 8.4 Technical Variance

Technical complexity affected delivery.

Examples:

- undocumented legacy behaviour
- integration defects
- unsupported configuration
- API limitations
- complex routing requirements

---

## 8.5 Resource Variance

The actual resource profile differed from the planned resource profile.

Examples:

- skill shortage
- resource substitution
- onboarding
- reduced availability
- concurrent project commitments

---

## 8.6 Dependency Variance

The task was affected by another task or external dependency.

Examples:

- integration unavailable
- security approval delayed
- migration dependency delayed
- environment not ready

---

# 9. Effort vs Duration Variance

These must be analysed separately.

```text
Effort
Amount of productive work

Duration
Elapsed project time
```

Example:

```text
Baseline Effort = 20h
Actual Effort   = 19h

Baseline Duration = 4 days
Actual Duration   = 8 days
```

The effort model is accurate.

The schedule or dependency model may be inaccurate.

---

# 10. Variance Aggregation

Variance should be analysed at:

```text
Task
 ↓
Capability
 ↓
Domain
 ↓
Layer 1 Phase
 ↓
Role
 ↓
Project
 ↓
Portfolio
```

---

# 11. Weighted Variance

Large tasks should not be treated identically to small tasks.

Example:

```text
Task A
Baseline 2h
Actual 4h
Variance +100%

Task B
Baseline 100h
Actual 110h
Variance +10%
```

Task A has a larger percentage variance.

Task B has a larger absolute variance.

Both measures should be retained.

---

# 12. Recurring Variance

Recurring variance should be identified where similar tasks consistently deviate in the same direction.

Example:

```text
Task baseline = 8h

Project 1 = 10h
Project 2 = 11h
Project 3 = 10h
Project 4 = 12h
Project 5 = 11h
```

This may indicate that the baseline is systematically low.

---

# 13. Variance Trend

The model should support trend analysis.

```text
Project 1    +25%
Project 2    +18%
Project 3    +14%
Project 4    +9%
Project 5    +6%
```

This may indicate that previous calibration changes are improving accuracy.

---

# 14. Variance Thresholds

Initial thresholds:

| Variance | Action |
|---|---|
| 0–10% | Monitor |
| >10–20% | Review |
| >20–30% | Investigate |
| >30% | Material variance |

Thresholds may be adjusted through calibration governance.

---

# 15. Variance Reporting

The reporting model should provide:

- total baseline effort
- total actual effort
- total variance
- variance percentage
- baseline duration
- actual duration
- duration variance
- largest under-estimates
- largest over-estimates
- recurring variance
- variance by domain
- variance by capability
- variance by role
- variance by project
- variance by cause

---

# 16. Calibration Decision

Variance analysis must result in one of:

```text
NO MODEL CHANGE
MONITOR
PROJECT-SPECIFIC ADJUSTMENT
TASK BASELINE REVIEW
COMPLEXITY FACTOR REVIEW
ROLE FACTOR REVIEW
DURATION MODEL REVIEW
DEPENDENCY MODEL REVIEW
TASK CATALOGUE CHANGE
```

---

# 17. Definition of Done

Variance analysis is complete when:

- baseline and actual values are available
- effort variance is calculated
- duration variance is calculated
- variance is classified
- root causes are identified where possible
- recurring patterns are identified
- variance is aggregated at appropriate levels
- material variance is reviewed
- calibration action is determined
- results are recorded for future model improvement

---

# Phase Completion

Variance analysis provides the evidence required to determine whether observed project differences represent estimation-model weaknesses or project-specific delivery conditions.
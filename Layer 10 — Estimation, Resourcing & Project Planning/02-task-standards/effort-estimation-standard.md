# Layer 10 — Effort Estimation Standard

## Purpose

This document defines how baseline implementation effort is estimated within the Genesys Cloud Project Framework.

---

# 1. Effort Definition

Effort represents the amount of productive work required to complete a task.

Effort is distinct from elapsed duration.

Example:

```text
Effort: 8 hours
Duration: 3 working days
```

---

# 2. Baseline Effort

Every implementation task should have a baseline effort estimate.

Baseline effort represents the expected effort under the framework's standard assumptions.

It is not a guaranteed project commitment.

---

# 3. Effort Units

The preferred unit is:

```text
Hours
```

Days may be used for reporting where the conversion standard is explicitly defined.

---

# 4. Estimation Scope

Baseline effort should normally include:

- preparation
- configuration
- implementation
- normal troubleshooting
- validation directly associated with the task
- task documentation

It should not automatically include:

- major rework
- project management
- unrelated meetings
- customer delays
- major defects
- scope changes
- contingency

unless explicitly defined by the applicable estimation model.

---

# 5. Effort Drivers

Effort may be influenced by:

- number of objects
- configuration complexity
- number of environments
- integration complexity
- data volume
- automation
- security requirements
- regulatory requirements
- customer maturity
- migration complexity
- custom development
- testing requirements

---

# 6. Complexity Factors

Where appropriate, tasks may be classified:

```text
LOW
MEDIUM
HIGH
VERY HIGH
```

Complexity is an input to estimation, not a replacement for effort.

---

# 7. Baseline vs Project Estimate

The baseline effort represents the methodology estimate.

The project estimate may adjust the baseline based on known project conditions.

Example:

```text
Baseline:
8 hours

Complexity adjustment:
+25%

Project estimate:
10 hours
```

The adjustment must be documented.

---

# 8. Customer Effort

Customer effort must be separately identified.

Example:

```text
Delivery Effort: 8h
Customer Effort: 4h
Total Activity Effort: 12h
```

The delivery estimate must not silently include customer effort.

---

# 9. Contingency

Contingency should be managed separately from baseline task effort.

Do not inflate every task simply to hide uncertainty.

Contingency should be represented in the estimation model.

---

# 10. Estimate Confidence

Where practical, estimates may be classified:

```text
HIGH CONFIDENCE
MEDIUM CONFIDENCE
LOW CONFIDENCE
```

Confidence should reflect the quality of available information.

---

# 11. Estimation Drivers

Estimation should be recalibrated when actual project characteristics differ materially from baseline assumptions.

---

# 12. Definition of Done

Effort estimation is complete when:

- baseline effort is assigned
- effort units are defined
- assumptions are documented
- major effort drivers are known
- customer effort is distinguishable
- contingency is treated separately
- estimate confidence is understood
- the estimate can feed Layer 10/03
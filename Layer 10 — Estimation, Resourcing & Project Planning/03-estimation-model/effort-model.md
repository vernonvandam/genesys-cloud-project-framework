# Layer 10 — Effort Model

## Purpose

The Effort Model defines how baseline implementation effort is assigned to Layer 10 tasks.

---

# 1. Effort Unit

The authoritative effort unit is:

```text
Hours
```

Effort represents productive delivery work.

---

# 2. Baseline Effort

Every applicable task should have a baseline effort estimate.

Baseline effort represents the expected effort under standard assumptions.

It is not a project commitment.

---

# 3. Effort Components

A task estimate may include:

| Component | Included |
|---|---|
| Preparation | YES |
| Configuration | YES |
| Implementation | YES |
| Normal troubleshooting | YES |
| Task-level validation | YES |
| Task documentation | YES |
| Project management | NO |
| Contingency | NO |
| Customer effort | NO |
| Scope change | NO |
| Major defect remediation | NO |

---

# 4. Effort Calculation

Where volume-based estimation applies:

```text
Baseline Effort =
Base Effort
+
(Volume × Unit Effort)
```

Where complexity adjustment applies:

```text
Adjusted Effort =
Baseline Effort × Complexity Factor
```

Where project-specific adjustment applies:

```text
Project Effort =
Adjusted Effort × Project Adjustment Factor
```

The actual calculation method must be selected according to the applicable task model.

---

# 5. Effort Estimation Methods

The framework may use:

### Fixed Estimate

Used where effort is relatively stable.

```text
Effort = 8 hours
```

### Unit-Based Estimate

Used where effort scales with volume.

```text
Effort = 2 hours × number of queues
```

### Base + Unit Estimate

Used where there is a fixed setup component plus scalable implementation effort.

```text
Effort = 4 hours + (1.5 hours × number of objects)
```

### Complexity-Adjusted Estimate

Used where difficulty materially changes effort.

```text
Effort = Baseline × Complexity Factor
```

### Composite Estimate

Used where multiple drivers apply.

```text
Effort =
Base
+ Volume
+ Complexity
+ Environment
+ Integration
+ Migration
```

---

# 6. Effort Boundaries

Effort should not be used to compensate for:

- unclear scope
- missing dependencies
- customer delays
- unidentified requirements
- contingency
- schedule compression

These should be represented through the appropriate model.

---

# 7. Customer Effort

Customer effort must be separately identified.

Example:

```text
Delivery Effort = 8h
Customer Effort = 4h
Total Activity Effort = 12h
```

---

# 8. Environment Effort

Where a task must be repeated across environments, the estimate should account for the additional implementation effort.

Example:

```text
DEV configuration
TEST configuration
UAT configuration
PROD deployment
```

This may be represented through volume or an explicit project adjustment.

---

# 9. Automation

Automation may reduce repetitive implementation effort but can increase initial development effort.

The estimate must consider the total implementation lifecycle rather than assuming automation always reduces effort.

---

# 10. Estimate Confidence

Effort should be accompanied by an estimate confidence level:

```text
HIGH
MEDIUM
LOW
```

Low-confidence estimates should identify the assumptions causing uncertainty.

---

# 11. Rounding

Baseline effort should normally be expressed in practical estimation increments appropriate to the task size.

Excessive precision should be avoided.

For example:

```text
6.75 hours
```

should not imply greater certainty than the underlying estimation evidence supports.

---

# 12. Effort Aggregation

Effort can be aggregated by:

- task
- capability
- Layer 2 domain
- Layer 1 phase
- role
- environment
- project workstream

---

# 13. Definition of Done

The Effort Model is complete when:

- each task can receive a baseline effort
- estimation method is defined
- volume effects are understood
- complexity effects are understood
- customer effort is separate
- project adjustments are separate
- effort can be aggregated
- assumptions can be traced
- estimates can later be calibrated against actuals
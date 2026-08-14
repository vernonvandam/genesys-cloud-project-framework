# Layer 10 — Complexity Model

## Purpose

The Complexity Model provides a consistent method for assessing implementation difficulty.

---

# 1. Complexity Levels

| Level | Definition |
|---|---|
| LOW | Straightforward implementation using standard configuration |
| MEDIUM | Standard implementation with moderate configuration or dependency complexity |
| HIGH | Significant configuration, integration, customisation, migration, or dependency complexity |
| VERY HIGH | Highly complex implementation requiring specialist design, significant coordination, custom engineering, or substantial risk management |

---

# 2. Complexity Dimensions

Complexity should consider:

- configuration complexity
- integration complexity
- data complexity
- migration complexity
- security complexity
- regulatory complexity
- environment complexity
- dependency complexity
- customer maturity
- customisation
- automation
- testing complexity
- operational complexity

---

# 3. Complexity Assessment

A task should be assessed against the relevant dimensions rather than using subjective judgement alone.

Example:

| Dimension | Assessment |
|---|---|
| Configuration | Medium |
| Integration | High |
| Data | Low |
| Security | Medium |
| Dependencies | High |

Overall complexity:

```text
HIGH
```

---

# 4. Complexity Factors

The estimation model may define controlled factors such as:

```text
LOW        = 1.00
MEDIUM     = 1.25
HIGH       = 1.50
VERY HIGH  = 2.00
```

These values are methodology calibration parameters and may be revised as actual project data becomes available.

---

# 5. Complexity vs Volume

Complexity and volume are independent.

Example:

```text
Low complexity × high volume
```

may still produce substantial effort.

Likewise:

```text
High complexity × low volume
```

may require significant specialist effort.

---

# 6. Complexity Examples

### LOW

- standard configuration
- single environment
- no external dependencies
- well-defined requirements

### MEDIUM

- multiple configuration objects
- several environments
- moderate customer dependencies
- standard integration

### HIGH

- complex integration
- multiple systems
- migration requirements
- significant security controls
- custom implementation

### VERY HIGH

- major legacy transformation
- extensive coexistence
- complex migration
- highly regulated environment
- multiple critical integrations
- significant custom engineering

---

# 7. Complexity Review

Complexity should be reassessed when:

- requirements change
- volumes change
- architecture changes
- integration scope changes
- migration scope changes
- security requirements change
- customer responsibilities change

---

# 8. Complexity and Effort

Complexity should influence effort only through the approved estimation model.

Do not independently multiply estimates without documenting the applicable factor.

---

# 9. Definition of Done

Complexity assessment is complete when:

- applicable complexity dimensions are assessed
- overall complexity is classified
- assumptions are recorded
- the complexity factor is traceable
- the resulting estimate is reproducible
# Layer 10 — Environment Standard

## Purpose

This document defines the environment classification used for implementation tasks.

---

# 1. Standard Environments

The framework uses:

| Environment | Meaning |
|---|---|
| DESIGN | Architecture, design, planning, or non-runtime work |
| DEV | Development / configuration environment |
| TEST | Technical and system testing environment |
| UAT | User acceptance testing environment |
| PROD | Production |
| MULTI | Multiple environments materially involved |

---

# 2. DESIGN

Use `DESIGN` where the task does not primarily involve runtime configuration.

Examples:

- architecture design
- requirements analysis
- migration mapping
- security design
- test planning

---

# 3. DEV

Use `DEV` for development or initial configuration activities.

---

# 4. TEST

Use `TEST` for technical validation and system testing.

---

# 5. UAT

Use `UAT` for customer/business acceptance testing.

---

# 6. PROD

Use `PROD` for production configuration, deployment, validation, or operational activities.

---

# 7. MULTI

Use `MULTI` where multiple environments materially contribute to the task.

Examples:

```text
Deploy configuration across DEV, TEST, UAT and PROD.
```

---

# 8. Environment and Dependencies

Environment readiness may be a dependency.

Examples:

- environment provisioned
- access available
- integrations available
- test data available
- deployment window approved

---

# 9. Environment and Effort

Environment classification should be considered during estimation.

A task requiring configuration in multiple environments may have materially different effort from a task requiring one environment.

---

# 10. Definition of Done

Environment classification is complete when:

- the primary environment is identified
- MULTI is used where appropriate
- environment dependencies are documented
- environment-specific effort considerations are understood
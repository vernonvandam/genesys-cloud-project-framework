# Layer 10 — Task Types Standard

## Purpose

This document defines the classification of implementation tasks within the Layer 10 Task Catalogue.

---

# 1. Standard Task Types

The baseline task types are:

| Type | Meaning |
|---|---|
| REQUIRED | Normally applicable to the enterprise deployment methodology |
| CONDITIONAL | Applicable only when defined conditions exist |
| VALIDATION | Confirms an implemented capability, configuration, or control operates correctly |

---

# 2. REQUIRED

A REQUIRED task is normally expected within the standard Genesys Cloud deployment methodology.

Examples:

- provision required environments
- configure core platform settings
- establish baseline routing
- configure required security controls
- perform standard deployment validation

Required does not mean that the task must occur in every individual project without assessment.

The project may formally determine that a standard task is not applicable.

---

# 3. CONDITIONAL

A CONDITIONAL task applies only when one or more defined conditions exist.

Examples:

- PCI payment security
- recording migration
- digital channels
- historical data migration
- coexistence
- complex API migration
- data staging
- legacy decommissioning

The condition should be documented.

Example:

```text
Applicable when historical interaction data must remain available
within the new solution.
```

---

# 4. VALIDATION

A VALIDATION task verifies that an existing implementation operates as required.

Examples:

- validate SSO
- validate queue routing
- validate recording
- validate migrated data
- validate integration connectivity
- validate production configuration

Validation tasks should reference the implementation they are validating.

---

# 5. Classification Does Not Equal Priority

Task Type must not be interpreted as:

```text
REQUIRED = High priority
CONDITIONAL = Low priority
VALIDATION = Optional
```

Task Type describes applicability.

Priority and critical-path status are separate concepts.

---

# 6. Conditional Task Assessment

A conditional task must have an applicability condition.

The project should determine:

```text
Applicable
Not Applicable
Deferred
```

The reason for the decision should be recorded in the project-specific implementation model.

---

# 7. Validation Task Placement

Validation tasks may occur:

- during build
- during system testing
- during UAT
- during deployment
- during production validation
- during hypercare
- during operational handover

The applicable Layer 1 phase determines where the validation activity belongs.

---

# 8. Task Type Changes

Task type should not be changed solely to manipulate project estimates.

Changes must reflect actual applicability.

---

# 9. Definition of Done

Task classification is complete when:

- every task has a valid task type
- REQUIRED tasks represent baseline methodology work
- CONDITIONAL tasks have a documented applicability condition
- VALIDATION tasks represent verification activities
- classification is independent of critical-path status
- classification is independent of priority
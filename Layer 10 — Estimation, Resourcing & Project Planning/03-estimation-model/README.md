# Layer 10 — 03 Estimation Model

## Purpose

This directory defines the standard estimation model used to convert the Layer 10 task catalogue into consistent baseline effort, duration, resource, and project estimation inputs.

The estimation model consumes:

```text
Layer 2
Genesys Cloud Capability Catalogue
        ↓
Layer 10 / 01
Task Catalogue
        ↓
Layer 10 / 02
Task Standards
        ↓
Layer 10 / 03
Estimation Model
        ↓
Project Schedule
        ↓
Resource Plan
        ↓
Effort Estimate
        ↓
Project Workbook
```

The model is designed to provide a repeatable baseline for Genesys Cloud implementation estimation while allowing project-specific adjustment where scope, complexity, volumes, dependencies, customer responsibilities, or delivery conditions differ from the baseline assumptions.

---

# 1. Scope

The estimation model covers:

- task effort
- task duration
- task complexity
- task volumes
- resource requirements
- dependencies affecting estimates
- estimation assumptions
- baseline estimation rules
- project-specific estimation adjustments
- estimate confidence
- estimation boundaries

The model does not replace:

- the Layer 10 Task Catalogue
- task standards
- the project schedule model
- the spreadsheet model
- the calibration model

---

# 2. Estimation Principles

The estimation model follows these principles:

1. Estimate implementation work at task level.
2. Use the Layer 10 task catalogue as the authoritative work breakdown.
3. Separate effort from duration.
4. Separate delivery effort from customer effort.
5. Use volume and complexity as explicit estimation drivers.
6. Identify assumptions rather than hiding them inside estimates.
7. Avoid double-counting work across capabilities.
8. Treat conditional tasks according to applicability.
9. Preserve traceability to Layer 1 and Layer 2.
10. Allow project-specific adjustments without changing baseline methodology values.
11. Maintain estimate confidence.
12. Recalibrate estimates using actual project performance.

---

# 3. Estimation Inputs

The model uses the following primary inputs:

| Input | Source |
|---|---|
| Task ID | Layer 10 Task Catalogue |
| Task Type | Task Standards |
| Layer 1 Phase | Task Catalogue |
| Layer 2 Domain | Capability Catalogue |
| Layer 2 Capability | Capability Catalogue |
| Primary Role | Task Catalogue / Role Catalogue |
| Customer Responsibility | Task Catalogue |
| Environment | Task Catalogue |
| Automation | Task Catalogue |
| Complexity | Complexity Model |
| Volume | Volume Model |
| Dependencies | Dependency Model |
| Baseline Effort | Effort Model |
| Duration | Duration Model |
| Assumptions | Estimation Assumptions |

---

# 4. Estimation Flow

```text
Identify Applicable Tasks
        ↓
Validate Task Scope
        ↓
Determine Volume
        ↓
Determine Complexity
        ↓
Apply Baseline Effort
        ↓
Apply Approved Adjustments
        ↓
Validate Dependencies
        ↓
Determine Duration
        ↓
Assign Resource Requirements
        ↓
Assess Estimate Confidence
        ↓
Calculate Project Estimate
        ↓
Review and Approve
```

---

# 5. Baseline vs Project Estimate

The framework distinguishes between:

### Baseline Estimate

The standard effort associated with a task under defined methodology assumptions.

### Project Estimate

The baseline estimate adjusted for known project-specific conditions.

The baseline should remain unchanged when estimating an individual project.

Project-specific adjustments should be recorded separately.

---

# 6. Effort

Effort is measured in productive hours.

The baseline effort should include only the work defined by the task.

Effort should not automatically include:

- project management
- contingency
- customer effort
- unrelated meetings
- scope changes
- major rework
- unidentified defects

unless explicitly defined by the estimation model.

---

# 7. Duration

Duration represents elapsed working time.

Duration may differ materially from effort because of:

- dependencies
- resource allocation
- approvals
- customer availability
- environment availability
- maintenance windows
- testing windows
- migration windows

---

# 8. Complexity

Complexity represents the implementation difficulty of the task.

Standard classifications are:

```text
LOW
MEDIUM
HIGH
VERY HIGH
```

Complexity is not a substitute for task effort.

---

# 9. Volume

Volume represents the quantity of objects, users, flows, integrations, data, environments, or other implementation units that materially affect effort.

Examples:

- number of users
- number of queues
- number of Architect flows
- number of integrations
- number of phone numbers
- number of reports
- number of migration records

---

# 10. Resource Requirements

Resource requirements are derived from:

- Primary Role
- supporting roles
- task effort
- task duration
- dependency sequencing
- required specialist skills
- environment requirements

Resource planning is not simply a conversion of hours into headcount.

---

# 11. Estimation Confidence

Every project estimate should have an understood confidence level.

Suggested levels:

```text
HIGH
MEDIUM
LOW
```

Confidence should reflect the quality of:

- scope definition
- source information
- task applicability
- volume information
- complexity assessment
- dependency information
- customer assumptions

---

# 12. Estimation Adjustments

Adjustments may be required for:

- high complexity
- unusually large volumes
- poor source data
- multiple environments
- extensive customisation
- customer maturity
- integration complexity
- regulatory requirements
- migration complexity
- automation requirements
- constrained delivery windows

Adjustments must be explicit.

---

# 13. Double-Counting Prevention

Each implementation outcome must have one authoritative task.

Where multiple capabilities interact, the estimation model must determine which task owns the work.

Examples:

```text
Integration configuration
Integration testing
Production validation
```

are distinct activities and should not be estimated repeatedly under multiple domains.

---

# 14. Customer Effort

Customer effort must remain separate from delivery effort.

The model should be able to report:

```text
Delivery Effort
Customer Effort
Total Activity Effort
```

---

# 15. Contingency

Contingency should not be hidden inside individual task estimates.

Where required, contingency should be modelled separately so that:

```text
Baseline Estimate
+
Approved Adjustments
+
Contingency
=
Project Estimate
```

---

# 16. Estimation Outputs

The estimation model should support:

- total project effort
- effort by Layer 1 phase
- effort by Layer 2 domain
- effort by capability
- effort by task
- effort by role
- effort by environment
- customer effort
- conditional effort
- critical-path effort
- project duration
- resource demand
- estimate confidence

---

# 17. Traceability

Every estimate must remain traceable:

```text
Layer 1 Phase
      ↓
Layer 2 Domain
      ↓
Layer 2 Capability
      ↓
Layer 10 Task
      ↓
Complexity
      ↓
Volume
      ↓
Baseline Effort
      ↓
Project Adjustment
      ↓
Project Estimate
```

---

# 18. Downstream Dependencies

The estimation model feeds:

```text
04-role-catalogue
05-dependency-model
06-project-schedule-model
07-spreadsheet-model
08-calibration
```

The model must therefore remain structured enough to be consumed programmatically or through spreadsheet-based estimation.

---

# 19. Definition of Done

The estimation model is complete when:

- every applicable task can be estimated
- baseline effort is defined
- effort and duration are separated
- complexity is defined
- volume drivers are defined
- resource requirements can be derived
- dependencies can affect scheduling
- assumptions are explicit
- customer effort is separated
- project adjustments are explicit
- estimate confidence can be assessed
- outputs can feed the project schedule
- outputs can feed the project workbook
- actual project data can later be used for calibration
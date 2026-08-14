# Layer 10 — 2.05.17 Variables & Expressions

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 05 — Architect |
| Capability ID | 2.05.17 |
| Capability | Variables & Expressions |
| Task Catalogue ID | 05.17 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P09, P10, P11, P12 |

## Capability Objective

Implement flow variables, expressions and business logic required to control Architect execution.

## Source Implementation Activities

1. Define data and logic requirements.
2. Configure variables and expressions.
3. Validate flow logic.

## Implementation Tasks

### Activity 01 — Define Flow Logic

#### L10-05.17-001 — Define Variable Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | NO |

**Description**

Define variables, data types, default values, transformations and business logic.

**Dependencies**

- Flow requirements

**Deliverable**

Variable and expression specification.

**Acceptance Criteria**

Required variables and logic are documented.

---

#### L10-05.17-002 — Configure Variables and Expressions

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | NO |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 2.5h |
| Critical Path | NO |

**Description**

Implement variables, expressions, conditions and calculations.

**Dependencies**

- L10-05.17-001

**Deliverable**

Configured flow logic.

**Acceptance Criteria**

Logic implements approved business rules.

---

#### L10-05.17-003 — Validate Flow Logic

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | NO |

**Description**

Validate normal, boundary and exception logic paths.

**Dependencies**

- L10-05.17-002

**Deliverable**

Logic validation evidence.

**Acceptance Criteria**

All defined logic scenarios pass.
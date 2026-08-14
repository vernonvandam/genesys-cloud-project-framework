# Layer 10 — 2.15.38 Proof of Concept

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 15 — Optimisation, Continuous Improvement & Platform Evolution |
| Capability ID | 2.15.38 |
| Capability | Proof of Concept |
| Task Catalogue ID | 15.38 |
| Primary Layer 1 Phases | P03, P04, P06, P08 |

## Capability Objective

Provide a controlled mechanism to prove technical or business feasibility before committing to production implementation.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define PoC objectives |
| P04 | Define PoC design |
| P06 | Build PoC |
| P08 | Evaluate PoC |

## Source Implementation Activities

1. Define PoC objectives.
2. Define success criteria.
3. Design PoC.
4. Build PoC.
5. Evaluate results.

## Implementation Tasks

### L10-15.38-001 — Define PoC Objectives

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | NO |

**Description**

Define the business and technical question the PoC must answer.

**Dependencies**

- Business requirement
- Innovation opportunity

**Deliverable**

PoC objectives.

**Acceptance Criteria**

Objectives are approved.

### L10-15.38-002 — Define PoC Success Criteria

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Define measurable success and failure criteria.

**Dependencies**

- L10-15.38-001

**Deliverable**

PoC success criteria.

**Acceptance Criteria**

Criteria are measurable.

### L10-15.38-003 — Build Proof of Concept

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | HYBRID |
| Baseline Effort | 4.0h |
| Critical Path | NO |

**Description**

Build the minimum implementation necessary to test the defined hypothesis.

**Dependencies**

- L10-15.38-002

**Deliverable**

PoC implementation.

**Acceptance Criteria**

PoC executes the intended scenario.

### L10-15.38-004 — Evaluate PoC

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | NO |

**Description**

Evaluate PoC results against success criteria.

**Dependencies**

- L10-15.38-003

**Deliverable**

PoC evaluation.

**Acceptance Criteria**

Go / no-go decision is documented.
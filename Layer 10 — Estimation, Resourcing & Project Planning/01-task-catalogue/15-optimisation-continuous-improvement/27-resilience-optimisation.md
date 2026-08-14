# Layer 10 — 2.15.27 Resilience Optimisation

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 15 — Optimisation, Continuous Improvement & Platform Evolution |
| Capability ID | 2.15.27 |
| Capability | Resilience Optimisation |
| Task Catalogue ID | 15.27 |
| Primary Layer 1 Phases | P02, P03, P04, P06, P08, P09, P11 |

## Capability Objective

Improve the ability of the Genesys Cloud solution and its dependencies to withstand failures and continue providing critical services.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P02 | Assess resilience posture |
| P03 | Define resilience requirements |
| P04 | Design resilience improvements |
| P06 | Implement improvements |
| P08 | Validate resilience |
| P09 | Operationalise resilience |
| P11 | Validate production resilience |

## Source Implementation Activities

1. Assess resilience.
2. Identify failure scenarios.
3. Define resilience improvements.
4. Implement controls.
5. Test resilience.

## Implementation Tasks

### L10-15.27-001 — Assess Resilience Posture

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Technical Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.5h |
| Critical Path | NO |

**Description**

Assess resilience across platform, telephony, integrations, data, identity and operational dependencies.

**Dependencies**

- Architecture
- Business continuity requirements

**Deliverable**

Resilience assessment.

**Acceptance Criteria**

Resilience risks are documented.

### L10-15.27-002 — Define Resilience Improvements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Technical Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Define improvements for identified failure scenarios.

**Dependencies**

- L10-15.27-001

**Deliverable**

Resilience improvement plan.

**Acceptance Criteria**

Improvements are approved.

### L10-15.27-003 — Implement Resilience Improvements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Technical Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | HYBRID |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Implement approved resilience improvements.

**Dependencies**

- L10-15.27-002

**Deliverable**

Resilience improvements.

**Acceptance Criteria**

Controls are implemented and documented.

### L10-15.27-004 — Validate Resilience

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | HYBRID |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Execute agreed failure and resilience scenarios.

**Dependencies**

- L10-15.27-003

**Deliverable**

Resilience test evidence.

**Acceptance Criteria**

Critical resilience scenarios meet approved outcomes.
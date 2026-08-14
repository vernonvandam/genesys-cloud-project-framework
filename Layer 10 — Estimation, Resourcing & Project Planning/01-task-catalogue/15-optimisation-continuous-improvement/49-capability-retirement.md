# Layer 10 — 2.15.49 Capability Retirement

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 15 — Optimisation, Continuous Improvement & Platform Evolution |
| Capability ID | 2.15.49 |
| Capability | Capability Retirement |
| Task Catalogue ID | 15.49 |
| Primary Layer 1 Phases | P02, P03, P04, P09, P10, P12 |

## Capability Objective

Safely retire Genesys Cloud capabilities, configuration, integrations or processes that are obsolete, replaced or no longer provide sufficient value.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P02 | Identify retirement candidates |
| P03 | Assess retirement requirements |
| P04 | Design retirement approach |
| P09 | Prepare retirement |
| P10 | Execute retirement |
| P12 | Close lifecycle activity |

## Source Implementation Activities

1. Identify retirement candidate.
2. Assess dependencies.
3. Define retirement plan.
4. Obtain approval.
5. Execute retirement.
6. Validate impact.

## Implementation Tasks

### L10-15.49-001 — Identify Retirement Candidate

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P02 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | NO |

**Description**

Identify obsolete, redundant or replaced platform capabilities.

**Dependencies**

- Capability inventory

**Deliverable**

Retirement candidate.

**Acceptance Criteria**

Candidate is documented.

### L10-15.49-002 — Assess Retirement Dependencies

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Technical Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Assess dependencies, data, integrations, users, processes and operational impacts.

**Dependencies**

- L10-15.49-001

**Deliverable**

Retirement impact assessment.

**Acceptance Criteria**

Dependencies are understood.

### L10-15.49-003 — Define Retirement Plan

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Define retirement sequence, validation, rollback and stakeholder communication.

**Dependencies**

- L10-15.49-002

**Deliverable**

Retirement plan.

**Acceptance Criteria**

Plan is approved.

### L10-15.49-004 — Execute Capability Retirement

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P10 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | HYBRID |
| Baseline Effort | 2.5h |
| Critical Path | NO |

**Description**

Retire the approved capability and validate dependent services.

**Dependencies**

- L10-15.49-003
- Retirement approval

**Deliverable**

Retired capability.

**Acceptance Criteria**

Capability is retired without unacceptable service impact.
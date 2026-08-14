# Layer 10 — 10.13 Assumption Governance

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Governance & Lifecycle |
| Capability ID | 10.13 |
| Capability | Assumption Governance |
| Task Catalogue ID | 10.13 |
| Primary Layer 1 Phases | P02, P03, P04, P09 |

## Capability Objective

Control assumptions that influence scope, effort, schedule, resources and risk.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P02 | Identify current-state assumptions |
| P03 | Capture planning assumptions |
| P04 | Validate assumptions |
| P09 | Confirm baseline assumptions |

## Source Implementation Activities

1. Identify assumptions.
2. Record assumptions.
3. Assess impact.
4. Validate assumptions.
5. Track assumption status.

## Implementation Tasks

### Activity 01 — Identify

#### L10-10.13-001 — Identify Estimation Assumptions

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Estimation Lead |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Identify assumptions affecting estimation and project planning.

**Dependencies**

- Discovery
- Requirements

**Deliverable**

Assumption register.

**Acceptance Criteria**

Material assumptions are identified.

### Activity 02 — Assess

#### L10-10.13-002 — Assess Assumption Impact

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Estimation Lead |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Assess effort, schedule, scope and risk impact of assumptions.

**Dependencies**

- L10-10.13-001

**Deliverable**

Assumption impact assessment.

**Acceptance Criteria**

Material impacts are documented.

### Activity 03 — Validate

#### L10-10.13-003 — Validate Baseline Assumptions

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P09 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Confirm assumptions remain valid before baseline approval.

**Dependencies**

- L10-10.13-002

**Deliverable**

Validated assumption register.

**Acceptance Criteria**

Invalid assumptions are resolved or accepted.

### Activity 04 — Track

#### L10-10.13-004 — Track Assumption Changes

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P11 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | CONDITIONAL |

**Description**

Monitor assumptions during project delivery and update affected forecasts.

**Dependencies**

- Baseline assumptions

**Deliverable**

Updated assumption register.

**Acceptance Criteria**

Material assumption changes are reflected in planning.

## Capability-Level Dependencies

- Discovery
- Requirements
- Estimation model

## Capability-Level Estimation Considerations

Unknowns and assumption volatility increase estimation confidence risk.

## Definition of Done

Material assumptions are documented, assessed, validated and monitored.

---
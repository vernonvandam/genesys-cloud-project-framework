# Layer 10 — 2.15.40 Controlled Rollout

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 15 — Optimisation, Continuous Improvement & Platform Evolution |
| Capability ID | 2.15.40 |
| Capability | Controlled Rollout |
| Task Catalogue ID | 15.40 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P10, P11 |

## Capability Objective

Deploy significant optimisation changes progressively while controlling operational risk and validating outcomes at each stage.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define rollout strategy |
| P04 | Define rollout architecture |
| P06 | Prepare rollout |
| P08 | Validate rollout readiness |
| P10 | Execute production rollout |
| P11 | Monitor rollout |

## Source Implementation Activities

1. Define rollout scope.
2. Define rollout waves.
3. Establish rollback criteria.
4. Execute controlled deployment.
5. Monitor each wave.
6. Progress or stop rollout.

## Implementation Tasks

### L10-15.40-001 — Define Controlled Rollout Strategy

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Define rollout waves, success criteria, stop criteria and rollback approach.

**Dependencies**

- Pilot or change assessment

**Deliverable**

Controlled rollout strategy.

**Acceptance Criteria**

Rollout approach is approved.

### L10-15.40-002 — Define Rollout Waves

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P04 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Define the sequence and scope of each rollout wave.

**Dependencies**

- L10-15.40-001

**Deliverable**

Rollout wave plan.

**Acceptance Criteria**

Wave scope and dependencies are approved.

### L10-15.40-003 — Execute Controlled Rollout

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P10 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | HYBRID |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Deploy the approved change progressively according to the rollout plan.

**Dependencies**

- L10-15.40-002
- Go-live approval

**Deliverable**

Production rollout.

**Acceptance Criteria**

Each wave meets progression criteria.

### L10-15.40-004 — Validate Rollout Outcomes

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P11 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate performance and business outcomes before progressing between waves.

**Dependencies**

- L10-15.40-003

**Deliverable**

Rollout validation.

**Acceptance Criteria**

Wave progression criteria are met.
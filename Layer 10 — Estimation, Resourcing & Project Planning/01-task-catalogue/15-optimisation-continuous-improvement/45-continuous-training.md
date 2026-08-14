# Layer 10 — 2.15.45 Continuous Training

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 15 — Optimisation, Continuous Improvement & Platform Evolution |
| Capability ID | 2.15.45 |
| Capability | Continuous Training |
| Task Catalogue ID | 15.45 |
| Primary Layer 1 Phases | P03, P09, P11, P12 |

## Capability Objective

Maintain user capability as Genesys Cloud functionality, business processes, security requirements and operating models evolve.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Identify training requirements |
| P09 | Maintain training capability |
| P11 | Provide change-related training |
| P12 | Transition training ownership |

## Source Implementation Activities

1. Assess training needs.
2. Maintain training materials.
3. Deliver capability updates.
4. Measure training effectiveness.
5. Transfer training ownership.

## Implementation Tasks

### L10-15.45-001 — Assess Continuous Training Needs

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Change Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | NO |

**Description**

Assess training needs arising from platform changes, new capabilities and process changes.

**Dependencies**

- Platform roadmap
- Change portfolio

**Deliverable**

Training needs assessment.

**Acceptance Criteria**

Training requirements are documented.

### L10-15.45-002 — Update Training Materials

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | Change Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Update training material, procedures, guides and learning content.

**Dependencies**

- L10-15.45-001

**Deliverable**

Updated training materials.

**Acceptance Criteria**

Materials reflect current operating procedures.

### L10-15.45-003 — Deliver Continuous Training

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P11 |
| Primary Role | Change Manager |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Deliver training for approved changes and new capabilities.

**Dependencies**

- L10-15.45-002

**Deliverable**

Training delivery.

**Acceptance Criteria**

Target users receive required training.

### L10-15.45-004 — Validate Training Effectiveness

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P12 |
| Primary Role | Change Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Assess whether users understand and can operate changed capabilities.

**Dependencies**

- L10-15.45-003

**Deliverable**

Training effectiveness assessment.

**Acceptance Criteria**

Training outcomes are accepted.
# Layer 10 — 2.15.39 Pilot Management

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 15 — Optimisation, Continuous Improvement & Platform Evolution |
| Capability ID | 2.15.39 |
| Capability | Pilot Management |
| Task Catalogue ID | 15.39 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P09, P11 |

## Capability Objective

Validate significant optimisation or new capability changes with a controlled user population before broad rollout.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define pilot objectives |
| P04 | Define pilot design |
| P06 | Configure pilot |
| P08 | Validate pilot |
| P09 | Support pilot users |
| P11 | Evaluate production pilot |

## Source Implementation Activities

1. Define pilot objectives.
2. Select pilot population.
3. Configure pilot.
4. Execute pilot.
5. Measure results.
6. Decide rollout.

## Implementation Tasks

### L10-15.39-001 — Define Pilot Objectives

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Product Owner |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | NO |

**Description**

Define pilot objectives, scope and success criteria.

**Dependencies**

- PoC or business case

**Deliverable**

Pilot objectives.

**Acceptance Criteria**

Pilot objectives are approved.

### L10-15.39-002 — Select Pilot Population

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P04 |
| Primary Role | Change Manager |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | NO |

**Description**

Select representative users, queues, channels or business groups for the pilot.

**Dependencies**

- L10-15.39-001

**Deliverable**

Pilot population.

**Acceptance Criteria**

Pilot participants are agreed.

### L10-15.39-003 — Execute Pilot

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | HYBRID |
| Baseline Effort | 4.0h |
| Critical Path | NO |

**Description**

Deploy and operate the capability for the defined pilot population.

**Dependencies**

- L10-15.39-002

**Deliverable**

Pilot implementation.

**Acceptance Criteria**

Pilot operates within agreed scope.

### L10-15.39-004 — Evaluate Pilot

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P11 |
| Primary Role | Product Owner |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Measure pilot outcomes and determine rollout recommendation.

**Dependencies**

- L10-15.39-003

**Deliverable**

Pilot evaluation.

**Acceptance Criteria**

Pilot results and rollout recommendation are approved.
# Layer 10 — 2.15.10 Routing Optimisation

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 15 — Optimisation, Continuous Improvement & Platform Evolution |
| Capability ID | 2.15.10 |
| Capability | Routing Optimisation |
| Task Catalogue ID | 15.10 |
| Primary Layer 1 Phases | P02, P03, P04, P06, P08, P11 |

## Capability Objective

Optimise interaction routing, queue performance, skills, priorities, overflow, utilisation and customer outcomes.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P02 | Assess routing performance |
| P03 | Define routing improvement requirements |
| P04 | Design routing improvements |
| P06 | Implement routing changes |
| P08 | Validate routing |
| P11 | Validate production outcomes |

## Source Implementation Activities

1. Assess routing performance.
2. Identify routing inefficiencies.
3. Analyse queues, skills and priorities.
4. Design routing improvements.
5. Implement and validate changes.

## Implementation Tasks

### L10-15.10-001 — Assess Routing Performance

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Assess queue performance, routing methods, skills, priorities, utilisation, overflow and customer outcomes.

**Dependencies**

- Routing configuration
- Analytics data

**Deliverable**

Routing performance assessment.

**Acceptance Criteria**

Routing issues and opportunities are documented.

### L10-15.10-002 — Design Routing Improvements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.5h |
| Critical Path | NO |

**Description**

Design approved improvements to routing logic, queue configuration, skills, priorities and overflow behaviour.

**Dependencies**

- L10-15.10-001

**Deliverable**

Routing optimisation design.

**Acceptance Criteria**

Design is approved.

### L10-15.10-003 — Implement Routing Improvements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | HYBRID |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Implement approved routing changes.

**Dependencies**

- L10-15.10-002
- Change approval

**Deliverable**

Updated routing configuration.

**Acceptance Criteria**

Routing configuration is implemented and tested.

### L10-15.10-004 — Validate Routing Outcomes

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P11 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Validate routing performance against the agreed baseline and targets.

**Dependencies**

- L10-15.10-003

**Deliverable**

Routing validation report.

**Acceptance Criteria**

Routing performance meets approved targets.
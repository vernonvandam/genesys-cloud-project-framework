# Layer 10 — 2.04.21 Holiday Routing

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 04 — ACD & Routing |
| Capability ID | 2.04.21 |
| Capability | Holiday Routing |
| Task Catalogue ID | 04.21 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P10, P12 |

## Capability Objective

Provide routing behaviour for public holidays, planned closures and exceptional operating days.

## Source Implementation Activities

1. Identify holiday requirements.
2. Define holiday schedules.
3. Configure holiday routing.
4. Validate holiday behaviour.
5. Establish BAU ownership.

## Implementation Tasks

### L10-04.21-001 — Define Holiday Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Identify applicable public holidays, closures and exceptions.

**Dependencies**

- Business hours requirements

**Deliverable**

Holiday calendar requirements.

**Acceptance Criteria**

Calendar is approved.

### L10-04.21-002 — Configure Holiday Schedules

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 0.5h per schedule |
| Critical Path | YES |

**Description**

Configure approved holiday schedules.

**Dependencies**

- L10-04.21-001

**Deliverable**

Holiday schedules.

**Acceptance Criteria**

All required holiday dates are configured.

### L10-04.21-003 — Configure Holiday Routing Behaviour

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 0.5h per routing model |
| Critical Path | YES |

**Description**

Configure closed or alternate routing for holiday conditions.

**Dependencies**

- L10-04.21-002

**Deliverable**

Holiday routing configuration.

**Acceptance Criteria**

Holiday interactions follow approved behaviour.

### L10-04.21-004 — Validate Holiday Routing

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Validate holiday conditions using controlled test dates.

**Dependencies**

- L10-04.21-003

**Deliverable**

Holiday routing test evidence.

**Acceptance Criteria**

Holiday routing passes all defined scenarios.

## Definition of Done

Holiday routing is configured, validated and assigned to an operational owner.

---

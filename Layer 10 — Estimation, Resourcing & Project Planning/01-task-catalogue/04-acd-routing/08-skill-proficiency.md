# Layer 10 — 2.04.08 Skill Proficiency

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 04 — ACD & Routing |
| Capability ID | 2.04.08 |
| Capability | Skill Proficiency |
| Task Catalogue ID | 04.08 |
| Primary Layer 1 Phases | P03, P06, P08, P09 |

## Capability Objective

Define and configure agent proficiency against skills where proficiency-based routing is required.

## Source Implementation Activities

1. Define proficiency model.
2. Obtain agent proficiency data.
3. Configure proficiency.
4. Validate proficiency routing.

## Implementation Tasks

### L10-04.08-001 — Define Skill Proficiency Model

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | CONDITIONAL |

**Description**

Define how proficiency levels are represented and used in routing.

**Dependencies**

- Skills taxonomy

**Deliverable**

Proficiency model.

**Acceptance Criteria**

Model is approved.

### L10-04.08-002 — Load Agent Proficiency Data

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 0.25h per agent/skill |
| Critical Path | CONDITIONAL |

**Description**

Configure approved proficiency values.

**Dependencies**

- L10-04.08-001
- Customer proficiency data

**Deliverable**

Configured proficiency assignments.

**Acceptance Criteria**

Assignments match approved source data.

### L10-04.08-003 — Validate Proficiency Routing

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | CONDITIONAL |

**Description**

Validate that proficiency influences routing as designed.

**Dependencies**

- L10-04.08-002

**Deliverable**

Proficiency routing test evidence.

**Acceptance Criteria**

Routing produces expected proficiency-based outcomes.

## Definition of Done

Proficiency requirements are defined, configured and validated where applicable.

---

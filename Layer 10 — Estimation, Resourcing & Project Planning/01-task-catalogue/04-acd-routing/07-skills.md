# Layer 10 — 2.04.07 Skills

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 04 — ACD & Routing |
| Capability ID | 2.04.07 |
| Capability | Skills |
| Task Catalogue ID | 04.07 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P10, P11 |

## Capability Objective

Define and configure skills used to identify agent capability and route interactions.

## Source Implementation Activities

1. Identify skill requirements.
2. Define skill taxonomy.
3. Create skills.
4. Assign skills to agents.
5. Apply skills to routing.
6. Validate skill routing.

## Implementation Tasks

### L10-04.07-001 — Define Skill Taxonomy

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define the skills required to represent agent capability and routing requirements.

**Dependencies**

- Routing strategy

**Deliverable**

Skill taxonomy.

**Acceptance Criteria**

Required skills are documented and approved.

### L10-04.07-002 — Configure Skills

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 0.25h per skill |
| Critical Path | YES |

**Description**

Create and configure approved skills.

**Dependencies**

- L10-04.07-001

**Deliverable**

Configured skill catalogue.

**Acceptance Criteria**

Required skills exist with approved names and definitions.

### L10-04.07-003 — Assign Skills to Agents

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 0.25h per agent/skill set |
| Critical Path | YES |

**Description**

Assign skills to agents based on customer-provided capability data.

**Dependencies**

- L10-04.07-002

**Deliverable**

Agent skill assignments.

**Acceptance Criteria**

Assignments match approved source data.

### L10-04.07-004 — Validate Skill-Based Routing

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Validate that skill requirements correctly influence agent selection.

**Dependencies**

- L10-04.07-003

**Deliverable**

Skill routing validation.

**Acceptance Criteria**

Interactions route to appropriately skilled agents.

## Capability-Level Dependencies

- User provisioning
- Queue configuration
- Routing methods
- Skill proficiency

## Definition of Done

Skills are defined, configured, assigned and validated.

---

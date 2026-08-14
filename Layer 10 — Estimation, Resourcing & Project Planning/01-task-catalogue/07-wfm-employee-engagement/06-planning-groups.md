# Layer 10 — 2.07.06 Planning Groups

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 07 — Workforce Management & Employee Engagement |
| Capability ID | 2.07.06 |
| Capability | Planning Groups |
| Task Catalogue ID | 07.06 |
| Primary Layer 1 Phases | P02, P03, P04, P05, P06, P08 |

## Capability Objective

Define planning groups that accurately represent demand, queues, media, skills and workforce planning requirements.

## Source Implementation Activities

1. Identify planning populations.
2. Map demand sources.
3. Define planning groups.
4. Configure planning groups.
5. Validate demand and workforce relationships.

## Implementation Tasks

### Activity 01 — Planning Group Design

#### L10-07.06-001 — Identify Planning Populations

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Identify workforce populations requiring distinct planning treatment.

**Dependencies**

- Management-unit model
- ACD routing model

**Deliverable**

Planning population inventory.

**Acceptance Criteria**

All required planning populations are identified.

#### L10-07.06-002 — Map Demand to Planning Groups

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Map queues, skills, media and demand sources to planning groups.

**Dependencies**

- L10-07.06-001
- ACD queue catalogue

**Deliverable**

Planning-group mapping.

**Acceptance Criteria**

Demand sources are mapped to approved planning groups.

### Activity 02 — Configure and Validate

#### L10-07.06-003 — Configure Planning Groups

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | API / TERRAFORM |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Configure planning groups according to the approved design.

**Dependencies**

- L10-07.06-002

**Deliverable**

Configured planning groups.

**Acceptance Criteria**

Planning groups match approved demand mappings.

#### L10-07.06-004 — Validate Planning Group Demand

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate that planning groups receive the expected demand.

**Dependencies**

- L10-07.06-003

**Deliverable**

Planning-group validation evidence.

**Acceptance Criteria**

Demand appears against the correct planning groups.
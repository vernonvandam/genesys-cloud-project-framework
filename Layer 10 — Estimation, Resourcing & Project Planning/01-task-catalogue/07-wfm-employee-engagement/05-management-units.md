# Layer 10 — 2.07.05 Management Units

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 07 — Workforce Management & Employee Engagement |
| Capability ID | 2.07.05 |
| Capability | Management Units |
| Task Catalogue ID | 07.05 |
| Primary Layer 1 Phases | P02, P03, P04, P05, P08, P12 |

## Capability Objective

Define and configure management units representing the operational groups responsible for workforce management.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P02 | Discover management structure |
| P03 | Define requirements |
| P04 | Design management-unit model |
| P05 | Configure management units |
| P08 | Validate |
| P12 | Handover |

## Source Implementation Activities

1. Identify management units.
2. Define management-unit ownership.
3. Configure management units.
4. Assign appropriate workforce populations.
5. Validate and document.

## Implementation Tasks

### Activity 01 — Design Management Units

#### L10-07.05-001 — Identify Management Units

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

Identify management units based on workforce ownership, operational structure and planning requirements.

**Dependencies**

- Business-unit model

**Deliverable**

Management-unit inventory.

**Acceptance Criteria**

Required management units are identified.

#### L10-07.05-002 — Define Management-Unit Rules

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define management-unit naming, ownership, workforce assignment and operating rules.

**Dependencies**

- L10-07.05-001

**Deliverable**

Management-unit design.

**Acceptance Criteria**

Management-unit design is approved.

### Activity 02 — Configure and Validate

#### L10-07.05-003 — Configure Management Units

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | API / TERRAFORM |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Configure approved management units and relationships.

**Dependencies**

- L10-07.05-002

**Deliverable**

Configured management units.

**Acceptance Criteria**

Configuration matches the approved design.

#### L10-07.05-004 — Validate Management Units

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Validate workforce assignment, ownership and management-unit behaviour.

**Dependencies**

- L10-07.05-003

**Deliverable**

Validation evidence.

**Acceptance Criteria**

Management units operate as designed.

#### L10-07.05-005 — Document Management-Unit Model

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Document final management-unit configuration and ownership.

**Dependencies**

- L10-07.05-004

**Deliverable**

Management-unit configuration record.

**Acceptance Criteria**

Documentation is accepted for BAU.
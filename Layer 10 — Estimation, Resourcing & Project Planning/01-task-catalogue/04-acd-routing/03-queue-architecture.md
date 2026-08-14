# Layer 10 — 2.04.03 Queue Architecture

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 04 — ACD & Routing |
| Capability ID | 2.04.03 |
| Capability | Queue Architecture |
| Task Catalogue ID | 04.03 |
| Primary Layer 1 Phases | P02, P03, P04, P06, P08, P12 |

## Capability Objective

Define the logical queue model supporting business units, departments, channels, skills, service levels and operational reporting.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P02 | Assess current queue model |
| P03 | Define queue requirements |
| P04 | Design target queue architecture |
| P06 | Configure queues |
| P08 | Validate queue behaviour |
| P12 | Handover queue architecture |

## Source Implementation Activities

1. Inventory queues.
2. Define queue structure.
3. Define queue naming and ownership.
4. Map queues to channels and routing.
5. Validate queue architecture.

## Implementation Tasks

### Activity 01 — Queue Discovery

#### L10-04.03-001 — Inventory Required Queues

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Identify all queues required by business process, channel and operating model.

**Dependencies**

- Business requirements

**Deliverable**

Queue inventory.

**Acceptance Criteria**

Required queues are identified and approved.

### Activity 02 — Queue Design

#### L10-04.03-002 — Define Queue Architecture

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define queue hierarchy, ownership, channels, skills and routing relationships.

**Dependencies**

- L10-04.03-001

**Deliverable**

Queue architecture.

**Acceptance Criteria**

Queue model is approved.

#### L10-04.03-003 — Define Queue Naming Standards

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 0.5h |
| Critical Path | NO |

**Description**

Define queue naming, descriptions, ownership and documentation standards.

**Dependencies**

- L10-04.03-002

**Deliverable**

Queue naming standard.

**Acceptance Criteria**

Naming convention is approved.

### Activity 03 — Validate

#### L10-04.03-004 — Validate Queue Architecture

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Validate queues against approved business and routing requirements.

**Dependencies**

- Queue configuration

**Deliverable**

Queue validation record.

**Acceptance Criteria**

Queue structure and relationships are correct.

## Capability-Level Dependencies

- Business units
- Divisions
- Routing strategy
- Skills
- Channel configuration

## Capability-Level Estimation Considerations

Estimate according to:

- queue count
- queue complexity
- channel count
- routing relationships
- migration requirements

## Definition of Done

Queue architecture is approved, configured, validated and documented.

---

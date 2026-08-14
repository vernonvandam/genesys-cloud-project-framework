# Layer 10 — 2.06.20 Digital Queues & Skills

## Capability Objective

Establish queues and skills required for digital interaction handling.

## Implementation Tasks

### L10-06.20-001 — Define Digital Queue and Skill Model

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

Define digital queues, skills, membership, service levels and ownership.

**Dependencies**

- Digital routing requirements

**Deliverable**

Queue and skill matrix.

**Acceptance Criteria**

Matrix approved.

### L10-06.20-002 — Configure Digital Queues

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Create or configure queues required for digital interactions.

**Dependencies**

- L10-06.20-001

**Deliverable**

Configured queues.

**Acceptance Criteria**

Queues are available for routing.

### L10-06.20-003 — Configure Digital Skills

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Configure digital skills and applicable agent assignments.

**Dependencies**

- L10-06.20-002

**Deliverable**

Digital skills configuration.

**Acceptance Criteria**

Skills are available to routing.

### L10-06.20-004 — Validate Queue and Skill Routing

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate queue and skill-based routing.

**Dependencies**

- L10-06.20-003

**Deliverable**

Validation evidence.

**Acceptance Criteria**

Interactions reach the intended agents.

## Definition of Done

Digital queues and skills are configured and validated.

---

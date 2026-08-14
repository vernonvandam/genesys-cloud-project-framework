# Layer 10 — 2.08.05 Data Ownership & Stewardship

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 08 — Data, Integrations & APIs |
| Capability ID | 2.08.05 |
| Capability | Data Ownership & Stewardship |
| Task Catalogue ID | 08.05 |
| Primary Layer 1 Phases | P02, P03, P04, P09, P12 |

## Capability Objective

Establish accountable ownership and stewardship for data exchanged through Genesys Cloud integrations.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P02 | Identify current data owners |
| P03 | Define ownership requirements |
| P04 | Design stewardship model |
| P09 | Establish operational ownership |
| P12 | Handover BAU stewardship |

## Source Implementation Activities

1. Identify data owners.
2. Define stewardship responsibilities.
3. Establish operational ownership.
4. Document and hand over ownership.

## Implementation Tasks

### L10-08.05-001 — Identify Data Owners

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Data Architect |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Identify business and technical owners for each integration data domain.

**Dependencies**

- Data domain catalogue

**Deliverable**

Data ownership matrix.

**Acceptance Criteria**

All critical data domains have accountable owners.

### L10-08.05-002 — Define Stewardship Responsibilities

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Data Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Define responsibilities for data quality, access, retention, corrections and lifecycle management.

**Dependencies**

- L10-08.05-001

**Deliverable**

Data stewardship model.

**Acceptance Criteria**

Stewardship responsibilities are documented.

### L10-08.05-003 — Establish BAU Data Ownership

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Project Manager |
| Customer Responsibility | YES |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Confirm ongoing ownership after project closure.

**Dependencies**

- L10-08.05-002

**Deliverable**

Approved BAU ownership register.

**Acceptance Criteria**

Operational owners accept ownership.
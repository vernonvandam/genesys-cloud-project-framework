# Layer 10 — 2.08.04 System-of-Record Definition

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 08 — Data, Integrations & APIs |
| Capability ID | 2.08.04 |
| Capability | System-of-Record Definition |
| Task Catalogue ID | 08.04 |
| Primary Layer 1 Phases | P02, P03, P04, P07, P08 |

## Capability Objective

Define authoritative systems of record for customer, interaction, workforce, case, operational and reporting data.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P02 | Discover current data ownership |
| P03 | Define target systems of record |
| P04 | Design data ownership model |
| P07 | Implement approved data flows |
| P08 | Validate data authority and reconciliation |

## Source Implementation Activities

1. Identify data domains.
2. Determine systems of record.
3. Define data ownership and synchronisation rules.
4. Validate implementation.

## Implementation Tasks

### L10-08.04-001 — Identify Data Domains

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Data Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Identify major data domains exchanged with Genesys Cloud.

**Dependencies**

- Integration inventory

**Deliverable**

Data domain catalogue.

**Acceptance Criteria**

Relevant data domains are identified.

### L10-08.04-002 — Define Systems of Record

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Identify the authoritative system for each data domain.

**Dependencies**

- L10-08.04-001

**Deliverable**

System-of-record matrix.

**Acceptance Criteria**

Business owners approve system-of-record decisions.

### L10-08.04-003 — Define Synchronisation Rules

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Data Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define which systems may create, update, consume and reconcile each data domain.

**Dependencies**

- L10-08.04-002

**Deliverable**

Data synchronisation rules.

**Acceptance Criteria**

Data authority and update rules are documented.

### L10-08.04-004 — Validate Data Authority

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Data Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Validate that implemented integrations honour approved system-of-record decisions.

**Dependencies**

- L10-08.04-003
- Integration testing

**Deliverable**

System-of-record validation evidence.

**Acceptance Criteria**

No unauthorised data authority conflicts remain.
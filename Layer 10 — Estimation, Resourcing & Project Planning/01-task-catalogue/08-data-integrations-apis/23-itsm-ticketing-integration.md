# Layer 10 — 2.08.23 ITSM & Ticketing Integration

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 08 — Data, Integrations & APIs |
| Capability ID | 2.08.23 |
| Capability | ITSM & Ticketing Integration |
| Task Catalogue ID | 08.23 |
| Primary Layer 1 Phases | P02, P03, P04, P06, P08 |

## Capability Objective

Integrate Genesys Cloud with ITSM or ticketing platforms to support case creation, updates and operational workflows.

## Implementation Tasks

### L10-08.23-001 — Define ITSM Integration Requirements

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P02 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Identify ticket types, triggers, fields, status transitions and ownership.

**Dependencies**

- ITSM process discovery

**Deliverable**

ITSM integration requirements.

**Acceptance Criteria**

Required ticketing use cases are documented.

### L10-08.23-002 — Implement Ticketing Integration

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Integration Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 6.0h |
| Critical Path | CONDITIONAL |

**Description**

Implement ticket creation, update, lookup and status synchronisation as required.

**Dependencies**

- L10-08.23-001
- Data mapping

**Deliverable**

ITSM integration.

**Acceptance Criteria**

Required ticketing workflows execute successfully.

### L10-08.23-003 — Validate Ticket Synchronisation

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Integration Engineer |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | CONDITIONAL |

**Description**

Validate creation, updates, error handling and reconciliation.

**Dependencies**

- L10-08.23-002

**Deliverable**

ITSM validation evidence.

**Acceptance Criteria**

Ticket workflows pass end-to-end validation.
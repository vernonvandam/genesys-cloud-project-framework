# Layer 10 — 2.06.08 WhatsApp

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 06 — Digital |
| Capability ID | 2.06.08 |
| Capability | WhatsApp |
| Task Catalogue ID | 06.08 |
| Primary Layer 1 Phases | P03, P04, P06, P07, P08, P10, P11 |

## Capability Objective

Implement WhatsApp customer engagement including business account dependencies, templates, routing, compliance and agent handling.

## Implementation Tasks

### L10-06.08-001 — Confirm WhatsApp Business Requirements

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Define business account, number, template, use-case, routing and compliance requirements.

**Dependencies**

- Digital channel strategy

**Deliverable**

WhatsApp requirements.

**Acceptance Criteria**

Requirements and external dependencies are approved.

### L10-06.08-002 — Configure WhatsApp Channel

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | CONDITIONAL |

**Description**

Configure WhatsApp connectivity and Genesys Cloud channel settings.

**Dependencies**

- L10-06.08-001

**Deliverable**

WhatsApp configuration.

**Acceptance Criteria**

Channel is available for testing.

### L10-06.08-003 — Validate WhatsApp Customer Journey

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | CONDITIONAL |

**Description**

Validate inbound, outbound, templates, routing, context, transfers and agent handling.

**Dependencies**

- L10-06.08-002

**Deliverable**

WhatsApp test evidence.

**Acceptance Criteria**

Approved scenarios pass.

### L10-06.08-004 — Activate WhatsApp

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P10 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | CONDITIONAL |

**Description**

Activate the production WhatsApp channel.

**Dependencies**

- L10-06.08-003

**Deliverable**

Production WhatsApp capability.

**Acceptance Criteria**

Production interaction completes successfully.

## Definition of Done

WhatsApp is approved, integrated, tested, compliant and operational.

---

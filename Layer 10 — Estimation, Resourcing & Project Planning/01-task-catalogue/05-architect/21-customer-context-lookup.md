# Layer 10 — 2.05.21 Customer Context & Lookup

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 05 — Architect |
| Capability ID | 2.05.21 |
| Capability | Customer Context & Lookup |
| Task Catalogue ID | 05.21 |
| Primary Layer 1 Phases | P03, P04, P06, P07, P08, P09, P10, P11, P12 |

## Capability Objective

Retrieve and use customer context within Architect flows to personalise journeys and improve routing.

## Source Implementation Activities

1. Define customer context requirements.
2. Configure customer lookup.
3. Validate returned context.

## Implementation Tasks

### Activity 01 — Define Customer Context

#### L10-05.21-001 — Define Customer Context Requirements

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | CONDITIONAL |

**Description**

Define customer identifiers, lookup attributes, returned context and business uses.

**Dependencies**

- CRM/data requirements

**Deliverable**

Customer context specification.

**Acceptance Criteria**

Lookup requirements are approved.

---

#### L10-05.21-002 — Configure Customer Lookup

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | PARTIAL |
| Baseline Effort | 3.0h |
| Critical Path | CONDITIONAL |

**Description**

Configure customer lookup, mapping, error handling and context variables.

**Dependencies**

- L10-05.21-001
- Required Data Action

**Deliverable**

Configured customer lookup.

**Acceptance Criteria**

Customer context is retrieved using approved identifiers.

---

#### L10-05.21-003 — Validate Customer Context

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | CONDITIONAL |

**Description**

Validate successful, unmatched, ambiguous and unavailable customer records.

**Dependencies**

- L10-05.21-002

**Deliverable**

Customer context validation evidence.

**Acceptance Criteria**

All lookup outcomes are handled correctly.
# Layer 10 — 2.03.11 Telephone Numbers & DIDs

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 03 — Voice & Telephony |
| Capability ID | 2.03.11 |
| Capability | Telephone Numbers & DIDs |
| Task Catalogue ID | 03.11 |
| Primary Layer 1 Phases | P02, P03, P04, P06, P07, P08, P10 |

## Capability Objective

Inventory, design, provision, configure and validate telephone numbers and DIDs.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P02 | Discover number estate |
| P03 | Define numbering requirements |
| P04 | Design number strategy |
| P06 | Configure numbers |
| P07 | Port/provision numbers |
| P08 | Validate |
| P10 | Activate |

## Source Implementation Activities

1. Inventory numbers.
2. Define numbering requirements.
3. Allocate numbers.
4. Configure numbers.
5. Validate.
6. Prepare production activation.

## Implementation Tasks

### Activity 01 — Inventory

#### L10-03.11-001 — Inventory Telephone Numbers

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Business Analyst |
| Customer Responsibility | YES |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Inventory DIDs, service numbers, toll-free numbers, emergency numbers and extensions.

**Dependencies**

- Voice discovery

**Deliverable**

Number inventory.

**Acceptance Criteria**

Number estate is reconciled with customer records.

### Activity 02 — Design

#### L10-03.11-002 — Define Number Allocation Strategy

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

Define ownership, purpose, geography, routing and lifecycle for numbers.

**Dependencies**

- L10-03.11-001

**Deliverable**

Number allocation strategy.

**Acceptance Criteria**

Strategy approved.

### Activity 03 — Configure

#### L10-03.11-003 — Configure Telephone Numbers

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 1.0h/10 numbers |
| Critical Path | YES |

**Description**

Configure numbers according to the approved numbering strategy.

**Dependencies**

- L10-03.11-002

**Deliverable**

Configured numbers.

**Acceptance Criteria**

Numbers are correctly configured and associated.

### Activity 04 — Validate

#### L10-03.11-004 — Validate Number Routing

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P08 |
| Primary Role | Telephony Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate inbound routing and expected number presentation.

**Dependencies**

- L10-03.11-003
- Routing configuration

**Deliverable**

Number validation evidence.

**Acceptance Criteria**

All test numbers route correctly.

## Capability-Level Dependencies

- Carrier
- Number strategy
- Routing
- Dial plan

## Capability-Level Estimation Considerations

Estimate by number volume and geographic diversity.

## Definition of Done

All required telephone numbers are inventoried, configured, validated and ready for production.
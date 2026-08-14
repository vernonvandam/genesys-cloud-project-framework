<!-- FILE: 07-sites.md -->

# Layer 10 — 2.03.07 Sites

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 03 — Voice & Telephony |
| Capability ID | 2.03.07 |
| Capability | Sites |
| Task Catalogue ID | 03.07 |
| Primary Layer 1 Phases | P02, P03, P04, P05, P06, P08, P12 |

## Capability Objective

Define and configure Genesys Cloud sites and their associated telephony, network, location and operational characteristics.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P02 | Discover locations |
| P03 | Define site requirements |
| P04 | Design site architecture |
| P05 | Establish sites |
| P06 | Configure telephony |
| P08 | Validate |
| P12 | Handover |

## Source Implementation Activities

1. Inventory sites.
2. Define site requirements.
3. Design site structure.
4. Configure sites.
5. Associate telephony.
6. Validate.

## Implementation Tasks

### Activity 01 — Discovery

#### L10-03.07-001 — Inventory Voice Sites

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Business Analyst |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Inventory physical and logical locations requiring voice services.

**Dependencies**

- Voice discovery

**Deliverable**

Voice site inventory.

**Acceptance Criteria**

All required sites are identified.

### Activity 02 — Design

#### L10-03.07-002 — Define Site Telephony Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Telephony Engineer |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define site-specific carrier, network, endpoint, routing and resilience requirements.

**Dependencies**

- L10-03.07-001

**Deliverable**

Site requirements matrix.

**Acceptance Criteria**

Requirements are approved.

### Activity 03 — Build

#### L10-03.07-003 — Configure Genesys Cloud Sites

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 1.0h/site |
| Critical Path | YES |

**Description**

Create and configure required sites and associate relevant telephony settings.

**Dependencies**

- L10-03.07-002
- Core Platform

**Deliverable**

Configured sites.

**Acceptance Criteria**

Sites match approved design.

### Activity 04 — Validate

#### L10-03.07-004 — Validate Site Telephony

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P08 |
| Primary Role | Telephony Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h/site |
| Critical Path | YES |

**Description**

Validate site telephony configuration and media behaviour.

**Dependencies**

- L10-03.07-003

**Deliverable**

Site validation evidence.

**Acceptance Criteria**

All required sites pass validation.

## Capability-Level Dependencies

- Locations
- Network
- Telephony model
- Edges where applicable

## Capability-Level Estimation Considerations

Estimate per site where site designs differ.

## Definition of Done

All required voice sites are configured, validated and documented.
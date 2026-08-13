# Layer 10 — 2.01.07 Sites

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 01 — Core Platform |
| Capability ID | 2.01.07 |
| Capability | Sites |
| Task Catalogue ID | 01.07 |
| Primary Layer 1 Phases | P02, P03, P04, P05, P06, P08 |

## Capability Objective

Design and configure Genesys Cloud sites required for telephony, network, location, and operational architecture.

## Source Implementation Activities

1. Identify site requirements.
2. Gather site and network information.
3. Design site structure.
4. Configure sites.
5. Configure associated telephony settings.
6. Validate sites.

## Implementation Tasks

### Activity 01 — Requirements

#### L10-01.07-001 — Identify Site Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Technical Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Identify sites required for the customer deployment, including location, telephony, network, and operational requirements.

**Dependencies**

- Location requirements
- Voice architecture

**Deliverable**

Site requirements.

**Acceptance Criteria**

Required sites are documented.

#### L10-01.07-002 — Gather Site Network and Telephony Data

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Technical Architect |
| Customer Responsibility | YES |
| Environment | EXTERNAL |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Collect network, subnet, address, timezone, telephony, and other site information required for configuration.

**Dependencies**

- L10-01.07-001

**Deliverable**

Validated site dataset.

**Acceptance Criteria**

Required site data is complete.

### Activity 02 — Design

#### L10-01.07-003 — Design Site Architecture

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Technical Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Design the site model and its relationship to network, telephony, locations, and configuration.

**Dependencies**

- L10-01.07-002

**Deliverable**

Site architecture.

**Acceptance Criteria**

Site architecture is approved.

### Activity 03 — Configure

#### L10-01.07-004 — Create Sites

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | API / MANUAL |
| Baseline Effort | 0.5h per site |
| Critical Path | YES |

**Description**

Create the approved Genesys Cloud site configuration.

**Dependencies**

- L10-01.07-003

**Deliverable**

Configured sites.

**Acceptance Criteria**

All approved sites are configured correctly.

#### L10-01.07-005 — Configure Site-Specific Settings

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | API / MANUAL |
| Baseline Effort | Volume-based |
| Critical Path | CONDITIONAL |

**Description**

Configure site-specific settings required by the telephony and network architecture.

**Dependencies**

- L10-01.07-004

**Deliverable**

Site configuration.

**Acceptance Criteria**

Site-specific configuration matches the approved design.

### Activity 04 — Validate

#### L10-01.07-006 — Validate Site Configuration

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Analyst |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h per site group |
| Critical Path | YES |

**Description**

Validate site configuration and associated telephony/network behaviour.

**Dependencies**

- L10-01.07-005

**Deliverable**

Site validation evidence.

**Acceptance Criteria**

Sites pass required configuration and functional validation.

## Estimation Considerations

Drivers include:

- number of sites
- network complexity
- telephony architecture
- site-specific configuration
- customer data quality
- number of validation cycles

## Definition of Done

All required sites are designed, configured, validated, and documented.
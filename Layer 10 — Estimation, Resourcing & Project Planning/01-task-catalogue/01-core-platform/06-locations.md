# Layer 10 — 2.01.06 Locations

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 01 — Core Platform |
| Capability ID | 2.01.06 |
| Capability | Locations |
| Task Catalogue ID | 01.06 |
| Primary Layer 1 Phases | P02, P03, P04, P05, P08 |

## Capability Objective

Define and configure physical and logical customer locations required by the Genesys Cloud operating model.

## Source Implementation Activities

1. Identify location requirements.
2. Gather location data.
3. Design location model.
4. Configure locations.
5. Validate location data.
6. Document location configuration.

## Implementation Tasks

### Activity 01 — Requirements

#### L10-01.06-001 — Identify Location Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Business Analyst |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 0.5h |
| Critical Path | NO |

**Description**

Determine the locations required to support the customer operating model.

**Dependencies**

- Organisation requirements

**Deliverable**

Location requirements list.

**Acceptance Criteria**

Location requirements are approved.

#### L10-01.06-002 — Obtain Location Master Data

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | YES |
| Environment | EXTERNAL |
| Automation | IMPORT |
| Baseline Effort | 1.0h |
| Critical Path | CONDITIONAL |

**Description**

Obtain and validate the customer-provided location master data.

**Dependencies**

- L10-01.06-001

**Deliverable**

Validated location dataset.

**Acceptance Criteria**

Required location attributes are complete and usable.

### Activity 02 — Design

#### L10-01.06-003 — Define Location Model

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Define the target Genesys Cloud location structure and associated attributes.

**Dependencies**

- L10-01.06-002

**Deliverable**

Location model.

**Acceptance Criteria**

Location model is approved.

### Activity 03 — Configure

#### L10-01.06-004 — Configure Locations

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | API / MANUAL |
| Baseline Effort | 0.25h per location |
| Critical Path | NO |

**Description**

Create and configure approved locations.

**Dependencies**

- L10-01.06-003

**Deliverable**

Configured locations.

**Acceptance Criteria**

Location records match approved master data.

### Activity 04 — Validate

#### L10-01.06-005 — Validate Location Configuration

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Analyst |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 0.5h per location |
| Critical Path | NO |

**Description**

Validate location records and their use by dependent configuration.

**Dependencies**

- L10-01.06-004

**Deliverable**

Location validation evidence.

**Acceptance Criteria**

All applicable location records pass validation.

## Estimation Considerations

Primary drivers:

- number of locations
- quality of source data
- data cleansing requirements
- import versus manual configuration
- dependent configuration

## Definition of Done

All required locations are configured, validated, and documented.
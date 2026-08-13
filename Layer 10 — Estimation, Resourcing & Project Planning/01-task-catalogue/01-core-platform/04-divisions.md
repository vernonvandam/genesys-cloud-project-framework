# Layer 10 — 2.01.04 Divisions

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 01 — Core Platform |
| Capability ID | 2.01.04 |
| Capability | Divisions |
| Task Catalogue ID | 01.04 |
| Primary Layer 1 Phases | P02, P03, P04, P05, P06, P08 |

## Capability Objective

Define and configure the Genesys Cloud division structure required for organisational separation, access control, configuration ownership, and reporting.

## Source Implementation Activities

1. Discover organisational separation requirements.
2. Design division model.
3. Configure divisions.
4. Assign applicable objects.
5. Validate division structure.
6. Document division model.

## Implementation Tasks

### Activity 01 — Discover Requirements

#### L10-01.04-001 — Identify Division Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Business Analyst |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Identify business, operational, security, reporting, and administrative requirements that justify division separation.

**Dependencies**

- L10-01.01-006

**Deliverable**

Division requirements.

**Acceptance Criteria**

Division requirements are approved.

### Activity 02 — Design

#### L10-01.04-002 — Design Division Structure

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Design the division hierarchy and determine which configuration objects belong within each division.

**Dependencies**

- L10-01.04-001

**Deliverable**

Division design.

**Acceptance Criteria**

Division model is approved.

### Activity 03 — Configure

#### L10-01.04-003 — Create Divisions

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | TERRAFORM / API / MANUAL |
| Baseline Effort | 0.25h per division |
| Critical Path | YES |

**Description**

Create the approved division structure.

**Dependencies**

- L10-01.04-002

**Deliverable**

Configured divisions.

**Acceptance Criteria**

All approved divisions exist with correct names and descriptions.

### Activity 04 — Configure Object Ownership

#### L10-01.04-004 — Assign Configuration Objects to Divisions

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | TERRAFORM / API / MANUAL |
| Baseline Effort | Volume-based |
| Critical Path | CONDITIONAL |

**Description**

Assign applicable users, queues, flows, groups, and other supported configuration objects to the correct divisions.

**Dependencies**

- L10-01.04-003

**Deliverable**

Division ownership configuration.

**Acceptance Criteria**

Applicable objects are assigned according to the approved design.

### Activity 05 — Validate

#### L10-01.04-005 — Validate Division Access and Separation

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Analyst |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate that division boundaries operate correctly for configuration ownership and access.

**Dependencies**

- L10-01.04-004

**Deliverable**

Division validation evidence.

**Acceptance Criteria**

Division separation and access behaviour pass validation.

### Activity 06 — Document

#### L10-01.04-006 — Document Division Model

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Document the final division structure and object ownership model.

**Dependencies**

- L10-01.04-005

**Deliverable**

Division model documentation.

**Acceptance Criteria**

Documentation reflects production configuration and is handed over.

## Estimation Considerations

Primary drivers:

- number of divisions
- number of objects assigned
- complexity of organisational separation
- security requirements
- reporting requirements
- automation method

## Definition of Done

Division structure is approved, configured, populated, validated, documented, and ready for downstream configuration.
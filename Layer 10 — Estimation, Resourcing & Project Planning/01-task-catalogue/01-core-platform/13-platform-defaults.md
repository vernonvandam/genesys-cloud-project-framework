# Layer 10 — 2.01.13 Platform Defaults

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 01 — Core Platform |
| Capability ID | 2.01.13 |
| Capability | Platform Defaults |
| Task Catalogue ID | 01.13 |
| Primary Layer 1 Phases | P03, P04, P05, P06, P08 |

## Capability Objective

Define and configure standard Genesys Cloud platform defaults required to provide a consistent foundation for downstream configuration and administration.

## Source Implementation Activities

1. Identify applicable platform defaults.
2. Define default configuration standards.
3. Configure defaults.
4. Validate defaults.
5. Document baseline.

## Implementation Tasks

### Activity 01 — Requirements

#### L10-01.13-001 — Inventory Applicable Platform Defaults

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Identify platform-level defaults that require explicit design or configuration.

**Dependencies**

- Organisation settings
- Platform requirements

**Deliverable**

Platform default inventory.

**Acceptance Criteria**

Applicable defaults are identified.

### Activity 02 — Design

#### L10-01.13-002 — Define Platform Default Standards

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Define approved default values and standards.

**Dependencies**

- L10-01.13-001

**Deliverable**

Platform defaults design.

**Acceptance Criteria**

Defaults are approved.

### Activity 03 — Configure

#### L10-01.13-003 — Configure Platform Defaults

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | API / TERRAFORM / MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Implement the approved platform defaults.

**Dependencies**

- L10-01.13-002

**Deliverable**

Configured platform defaults.

**Acceptance Criteria**

Configuration matches approved design.

### Activity 04 — Validate

#### L10-01.13-004 — Validate Platform Defaults

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Analyst |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Validate configured defaults and their impact on dependent configuration.

**Dependencies**

- L10-01.13-003

**Deliverable**

Validation evidence.

**Acceptance Criteria**

Defaults operate as designed.

## Estimation Considerations

Drivers include:

- number of defaults
- number of environments
- automation method
- complexity of configuration
- number of dependent capabilities

## Definition of Done

All applicable platform defaults are defined, configured, validated, and documented.
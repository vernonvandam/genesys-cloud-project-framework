# Layer 10 — 2.01.14 Licensing & Feature Entitlements

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 01 — Core Platform |
| Capability ID | 2.01.14 |
| Capability | Licensing & Feature Entitlements |
| Task Catalogue ID | 01.14 |
| Primary Layer 1 Phases | P01, P02, P03, P04, P05, P08, P10 |

## Capability Objective

Confirm that the Genesys Cloud subscription, licences, feature entitlements, and associated commercial requirements support the target solution.

## Source Implementation Activities

1. Review contractual scope.
2. Inventory required capabilities.
3. Map capabilities to licence requirements.
4. Identify gaps.
5. Validate entitlements.
6. Configure and assign licences.
7. Confirm production readiness.

## Implementation Tasks

### Activity 01 — Commercial and Scope Review

#### L10-01.14-001 — Review Contracted Genesys Cloud Scope

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P01 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Review contracted products, licences, users, services, and commercial scope relevant to the project.

**Dependencies**

- Project mobilisation

**Deliverable**

Commercial scope baseline.

**Acceptance Criteria**

Scope is confirmed against project requirements.

### Activity 02 — Licence Requirements

#### L10-01.14-002 — Map Solution Capabilities to Licensing Requirements

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

Map in-scope Genesys Cloud capabilities to required licences and feature entitlements.

**Dependencies**

- Layer 2 capability scope
- L10-01.14-001

**Deliverable**

Licence requirements matrix.

**Acceptance Criteria**

All in-scope capabilities have a licensing assessment.

#### L10-01.14-003 — Identify Licensing Gaps

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Identify any licence or feature entitlement gaps that prevent implementation of the target design.

**Dependencies**

- L10-01.14-002

**Deliverable**

Licensing gap register.

**Acceptance Criteria**

All gaps have an agreed resolution.

### Activity 03 — Entitlement Validation

#### L10-01.14-004 — Validate Purchased Entitlements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Validate that the organisation reflects the purchased and approved product entitlements.

**Dependencies**

- L10-01.14-003

**Deliverable**

Entitlement validation.

**Acceptance Criteria**

Required entitlements are available.

### Activity 04 — Licence Assignment

#### L10-01.14-005 — Configure Licence Assignment Model

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | API / SCRIPT / MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Configure the licence assignment approach and identify applicable user populations.

**Dependencies**

- L10-01.14-004
- Identity and access design

**Deliverable**

Licence assignment configuration.

**Acceptance Criteria**

Licence assignment aligns with approved design.

### Activity 05 — Validate

#### L10-01.14-006 — Validate Feature Entitlements

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate that required features are available and usable for the target solution.

**Dependencies**

- L10-01.14-005

**Deliverable**

Feature entitlement validation.

**Acceptance Criteria**

Required features pass validation.

### Activity 06 — Production Readiness

#### L10-01.14-007 — Confirm Production Licence Readiness

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P10 |
| Primary Role | Solution Architect |
| Customer Responsibility | YES |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 0.5h |
| Critical Path | YES |

**Description**

Confirm production licence quantities and entitlements are sufficient for go-live.

**Dependencies**

- L10-01.14-006

**Deliverable**

Production licensing readiness confirmation.

**Acceptance Criteria**

Production licence readiness is formally approved.

## Estimation Considerations

Drivers include:

- number of licence types
- number of users
- feature complexity
- commercial dependencies
- procurement lead time
- licence assignment complexity
- testing requirements

## Definition of Done

All required licences and feature entitlements are confirmed, available, correctly assigned, validated, and production-ready.
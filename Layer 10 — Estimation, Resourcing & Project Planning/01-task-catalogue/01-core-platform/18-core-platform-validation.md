# Layer 10 — 2.01.18 Core Platform Validation

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 01 — Core Platform |
| Capability ID | 2.01.18 |
| Capability | Core Platform Validation |
| Task Catalogue ID | 01.18 |
| Primary Layer 1 Phases | P08, P10, P11, P12 |

## Capability Objective

Validate that the complete Core Platform foundation has been implemented according to approved architecture, requirements, security controls, configuration standards, and operational requirements.

## Source Implementation Activities

1. Define validation scope.
2. Prepare validation checklist.
3. Execute platform validation.
4. Record defects.
5. Remediate defects.
6. Revalidate.
7. Obtain platform acceptance.
8. Complete handover.

## Implementation Tasks

### Activity 01 — Validation Planning

#### L10-01.18-001 — Define Core Platform Validation Scope

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Define the scope of validation across organisation, region, settings, divisions, business units, locations, sites, schedules, licensing, retention, capacity, and environment configuration.

**Dependencies**

- Completion of applicable Core Platform configuration

**Deliverable**

Validation scope.

**Acceptance Criteria**

Validation scope is approved.

#### L10-01.18-002 — Prepare Core Platform Validation Checklist

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P08 |
| Primary Role | Test Analyst |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Prepare a repeatable validation checklist covering all Core Platform requirements and configuration items.

**Dependencies**

- L10-01.18-001

**Deliverable**

Core Platform validation checklist.

**Acceptance Criteria**

Checklist covers all applicable platform requirements.

### Activity 02 — Execute Validation

#### L10-01.18-003 — Validate Organisation Configuration

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Analyst |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Validate organisation, regional, organisational, and platform-level configuration.

**Dependencies**

- L10-01.18-002

**Deliverable**

Organisation validation results.

**Acceptance Criteria**

Organisation configuration passes validation.

#### L10-01.18-004 — Validate Organisational Structures

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

Validate divisions, business units, locations, sites, time zones, business hours, and holidays.

**Dependencies**

- L10-01.18-003

**Deliverable**

Organisational structure validation evidence.

**Acceptance Criteria**

All applicable organisational structures pass validation.

#### L10-01.18-005 — Validate Licensing and Feature Entitlements

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Validate that required licensing and feature entitlements are available.

**Dependencies**

- Licensing configuration

**Deliverable**

Entitlement validation evidence.

**Acceptance Criteria**

Required entitlements are confirmed.

#### L10-01.18-006 — Validate Environment Configuration

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Technical Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Validate environment separation, access, deployment, and configuration promotion controls.

**Dependencies**

- Environment strategy

**Deliverable**

Environment validation evidence.

**Acceptance Criteria**

Environment configuration passes validation.

### Activity 03 — Defect Management

#### L10-01.18-007 — Record Core Platform Defects

| Attribute | Value |
|---|---|
| Task Type | REMEDIATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Analyst |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h baseline |
| Critical Path | YES |

**Description**

Record defects identified during Core Platform validation and classify them by severity, ownership, and impact.

**Dependencies**

- Validation execution

**Deliverable**

Platform defect register.

**Acceptance Criteria**

All identified defects are recorded and assigned.

#### L10-01.18-008 — Remediate Core Platform Defects

| Attribute | Value |
|---|---|
| Task Type | REMEDIATION |
| Layer 1 Phase | P08 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | CONDITIONAL |
| Environment | TEST |
| Automation | API / TERRAFORM / MANUAL |
| Baseline Effort | Volume-based |
| Critical Path | YES |

**Description**

Correct configuration defects identified during validation.

**Dependencies**

- L10-01.18-007

**Deliverable**

Remediated platform configuration.

**Acceptance Criteria**

Assigned defects are resolved or formally accepted.

#### L10-01.18-009 — Revalidate Remediated Configuration

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Analyst |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | Volume-based |
| Critical Path | YES |

**Description**

Re-execute failed validation scenarios following remediation.

**Dependencies**

- L10-01.18-008

**Deliverable**

Updated validation evidence.

**Acceptance Criteria**

Remediated items pass validation.

### Activity 04 — Production Readiness

#### L10-01.18-010 — Execute Production Readiness Validation

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P10 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Confirm that the production Core Platform configuration is ready for go-live.

**Dependencies**

- UAT completion
- Defect resolution
- Production configuration

**Deliverable**

Production readiness assessment.

**Acceptance Criteria**

All mandatory Core Platform readiness criteria are satisfied.

#### L10-01.18-011 — Execute Post-Go-Live Platform Validation

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P11 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate the production platform after cutover and confirm that foundational services operate as expected.

**Dependencies**

- Production cutover

**Deliverable**

Post-go-live validation record.

**Acceptance Criteria**

Production platform passes post-go-live checks.

### Activity 05 — Acceptance and Handover

#### L10-01.18-012 — Obtain Core Platform Acceptance

| Attribute | Value |
|---|---|
| Task Type | ACCEPTANCE |
| Layer 1 Phase | P11 |
| Primary Role | Solution Architect |
| Customer Responsibility | YES |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 0.5h |
| Critical Path | YES |

**Description**

Obtain customer acceptance that the Core Platform foundation meets agreed requirements.

**Dependencies**

- L10-01.18-011

**Deliverable**

Customer acceptance record.

**Acceptance Criteria**

Customer formally accepts the Core Platform foundation.

#### L10-01.18-013 — Complete Core Platform Operational Handover

| Attribute | Value |
|---|---|
| Task Type | HANDOVER |
| Layer 1 Phase | P12 |
| Primary Role | Service Management Lead |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Transfer Core Platform configuration, documentation, ownership, support procedures, and known operational considerations to the BAU support team.

**Dependencies**

- L10-01.18-012
- Operational readiness

**Deliverable**

Core Platform handover package.

**Acceptance Criteria**

Operational owner accepts the handover.

## Capability-Level Dependencies

This capability depends on completion or sufficient maturity of:

- Genesys Cloud Organisation
- Region & Data Residency
- Organisation Settings
- Divisions
- Business Units
- Locations
- Sites
- Time Zones
- Business Hours
- Holidays
- Languages
- Media Types
- Platform Defaults
- Licensing & Feature Entitlements
- Storage & Retention
- Platform Limits & Capacity
- Environment Strategy

## Estimation Considerations

Core Platform validation effort is primarily influenced by:

- number of configured capabilities
- number of environments
- number of organisations
- configuration volume
- complexity
- number of validation scenarios
- customer acceptance requirements
- defect volume
- number of remediation cycles
- production readiness requirements
- automation coverage

## Definition of Done

Core Platform validation is complete when:

- all applicable validation scenarios have been executed
- configuration defects have been resolved or formally accepted
- remediation has been revalidated
- production readiness has been confirmed
- post-go-live validation has passed
- customer acceptance has been obtained
- operational handover has been completed
- all required evidence has been retained
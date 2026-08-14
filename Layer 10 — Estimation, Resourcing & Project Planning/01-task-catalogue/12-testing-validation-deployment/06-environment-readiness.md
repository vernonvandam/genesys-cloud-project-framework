# Layer 10 — 2.12.06 Environment Readiness

## Capability Reference

| Attribute | Value |
|---|---|
| Layer 2 Capability | 2.12.06 — Environment Readiness |
| Layer 10 Domain | 12 — Testing, Validation & Deployment |
| Task Prefix | L10-12.06 |
| Default Classification | REQUIRED |
| Primary Layer 1 Phases | P05–P08 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Primary Environment | TEST / UAT |
| Automation | HYBRID |
| Critical Path | YES |

## Capability Objective

Confirm that required Genesys Cloud and supporting environments are available, configured, accessible and stable enough for formal testing.

## Source Implementation Activities

- Provision or confirm test environments.
- Validate configuration baseline.
- Validate connectivity and dependencies.
- Validate access.
- Complete environment readiness sign-off.

## Implementation Tasks

### Activity 01 — Provision / Confirm Environment

#### L10-12.06-001 — Confirm Test Environment Availability

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Confirm required Genesys Cloud test organisations and supporting systems are available.

**Dependencies**

Test Environment Strategy.

**Deliverable**

Environment Availability Record.

**Acceptance Criteria**

All required environments are accessible.

### Activity 02 — Validate Baseline

#### L10-12.06-002 — Validate Environment Configuration Baseline

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | HYBRID |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Validate required platform configuration, divisions, users, roles, settings and dependencies.

**Dependencies**

L10-12.06-001.

**Deliverable**

Environment Baseline Validation.

**Acceptance Criteria**

Required baseline configuration is present.

### Activity 03 — Validate Connectivity

#### L10-12.06-003 — Validate External Dependencies

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P07 |
| Primary Role | Integration Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | HYBRID |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Validate connectivity to required enterprise and third-party dependencies.

**Dependencies**

Integration configuration.

**Deliverable**

Connectivity Validation Results.

**Acceptance Criteria**

All critical dependencies are reachable and functional.

### Activity 04 — Sign Off Environment

#### L10-12.06-004 — Complete Environment Readiness Sign-Off

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST / UAT |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Confirm that the environment meets test-entry criteria.

**Dependencies**

L10-12.06-001 through L10-12.06-003.

**Deliverable**

Environment Readiness Sign-Off.

**Acceptance Criteria**

Environment entry criteria are met and approved.

## Capability-Level Dependencies

- Core Platform
- Identity & Access
- Integration configuration
- Security controls

## Capability-Level Estimation Considerations

Environment count, configuration complexity and external dependencies are primary drivers.

## Definition of Done

Each required test environment has passed readiness criteria.

---
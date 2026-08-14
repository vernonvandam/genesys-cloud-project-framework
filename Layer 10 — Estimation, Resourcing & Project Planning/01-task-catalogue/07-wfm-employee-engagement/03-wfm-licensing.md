# Layer 10 — 2.07.03 WFM Licensing

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 07 — Workforce Management & Employee Engagement |
| Capability ID | 2.07.03 |
| Capability | WFM Licensing |
| Task Catalogue ID | 07.03 |
| Primary Layer 1 Phases | P01, P03, P04, P05, P08, P10 |

## Capability Objective

Confirm that the required Genesys Cloud licensing and feature entitlements exist for the planned WFM solution.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P01 | Confirm licensing scope |
| P03 | Define entitlement requirements |
| P04 | Validate licensing architecture |
| P05 | Apply entitlements |
| P08 | Validate licensing |
| P10 | Confirm production readiness |

## Source Implementation Activities

1. Determine WFM licensing requirements.
2. Map users and capabilities to entitlements.
3. Confirm commercial licensing.
4. Configure or assign required entitlements.
5. Validate licensing.

## Implementation Tasks

### Activity 01 — Determine Requirements

#### L10-07.03-001 — Confirm WFM Licensing Scope

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P01 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Confirm which WFM capabilities are in scope and require licensing.

**Dependencies**

- WFM scope

**Deliverable**

Licensing requirements catalogue.

**Acceptance Criteria**

Required WFM capabilities are identified.

#### L10-07.03-002 — Map User Populations to Licensing

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Map workforce populations and administrative roles to required licences and entitlements.

**Dependencies**

- L10-07.03-001

**Deliverable**

WFM licensing matrix.

**Acceptance Criteria**

All required user populations are mapped.

### Activity 02 — Configure and Validate

#### L10-07.03-003 — Validate Commercial Licensing

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Project Manager |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Confirm purchased licensing supports the target solution.

**Dependencies**

- L10-07.03-002

**Deliverable**

Commercial licensing confirmation.

**Acceptance Criteria**

Customer confirms required licences are available.

#### L10-07.03-004 — Configure WFM Entitlements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Apply or assign required WFM entitlements.

**Dependencies**

- L10-07.03-003

**Deliverable**

Configured WFM entitlements.

**Acceptance Criteria**

Required capabilities are available to authorised users.

#### L10-07.03-005 — Validate WFM Licensing

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Validate that licensing supports all in-scope WFM functionality.

**Dependencies**

- L10-07.03-004

**Deliverable**

Licensing validation evidence.

**Acceptance Criteria**

All required WFM features operate under the approved licensing model.
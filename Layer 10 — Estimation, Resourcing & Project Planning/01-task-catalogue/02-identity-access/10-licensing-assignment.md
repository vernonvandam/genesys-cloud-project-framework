# Layer 10 — 2.02.10 Licensing Assignment

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 02 — Identity & Access |
| Capability ID | 2.02.10 |
| Capability | Licensing Assignment |
| Task Catalogue ID | 02.10 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P10, P12 |

## Capability Objective

Map required Genesys Cloud licences and feature entitlements to user personas and validate that licensing supports the target solution.

## Source Implementation Activities

1. Identify user personas.
2. Define licensing requirements.
3. Map licences to personas.
4. Configure licence assignments.
5. Validate entitlement coverage.
6. Document licence governance.

## Implementation Tasks

### Activity 01 — Design

#### L10-02.10-001 — Define Licensing Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Identify required licences and feature entitlements for each user population.

**Dependencies**

- User persona catalogue
- Solution scope

**Deliverable**

Licensing requirements matrix.

**Acceptance Criteria**

Licensing requirements are approved.

#### L10-02.10-002 — Map Licences to Personas

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

Map licences to operational and administrative personas while avoiding unnecessary entitlement.

**Dependencies**

- L10-02.10-001

**Deliverable**

Licence assignment matrix.

**Acceptance Criteria**

Licence mappings are approved.

### Activity 02 — Configure

#### L10-02.10-003 — Configure Licence Assignments

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | PARTIAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Apply the approved licence assignments.

**Dependencies**

- L10-02.10-002

**Deliverable**

Configured licence assignments.

**Acceptance Criteria**

User licensing matches the approved matrix.

### Activity 03 — Validate

#### L10-02.10-004 — Validate Feature Entitlements

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate that required platform features are available to the correct user populations.

**Dependencies**

- L10-02.10-003

**Deliverable**

Licence validation evidence.

**Acceptance Criteria**

Required capabilities are available and unnecessary access is minimised.

#### L10-02.10-005 — Document Licensing Model

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Document licensing assumptions, mappings and BAU ownership.

**Dependencies**

- L10-02.10-004

**Deliverable**

Licensing administration record.

**Acceptance Criteria**

Customer accepts the licensing model.s
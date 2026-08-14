# Layer 10 — 2.02.09 Division-Based Access

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 02 — Identity & Access |
| Capability ID | 2.02.09 |
| Capability | Division-Based Access |
| Task Catalogue ID | 02.09 |
| Primary Layer 1 Phases | P02, P03, P04, P05, P06, P08 |

## Capability Objective

Define and implement division-based resource and access boundaries aligned with the customer operating model and security requirements.

## Source Implementation Activities

1. Assess division requirements.
2. Define division strategy.
3. Map resources to divisions.
4. Configure divisions.
5. Configure user access.
6. Validate access boundaries.

## Implementation Tasks

### Activity 01 — Design

#### L10-02.09-001 — Assess Division Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Assess organisational, geographic, business and security requirements affecting divisions.

**Dependencies**

- Organisation architecture
- Business structure

**Deliverable**

Division requirements assessment.

**Acceptance Criteria**

Division requirements are documented.

#### L10-02.09-002 — Define Division Access Model

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

Define divisions, users, roles and resources requiring access boundaries.

**Dependencies**

- L10-02.09-001
- L10-02.08-002

**Deliverable**

Division access matrix.

**Acceptance Criteria**

Division access model is approved.

### Activity 02 — Configure

#### L10-02.09-003 — Configure Divisions

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | PARTIAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Create and configure the approved divisions.

**Dependencies**

- L10-02.09-002

**Deliverable**

Configured division model.

**Acceptance Criteria**

Divisions match the approved design.

#### L10-02.09-004 — Configure Division Permissions

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

Configure role/division combinations according to the access matrix.

**Dependencies**

- L10-02.09-003
- L10-02.08-003

**Deliverable**

Division access configuration.

**Acceptance Criteria**

Users have only approved division access.

### Activity 03 — Validate

#### L10-02.09-005 — Test Division Access Boundaries

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

Test access to resources inside and outside assigned divisions.

**Dependencies**

- L10-02.09-004

**Deliverable**

Division validation evidence.

**Acceptance Criteria**

Cross-division access behaves according to the approved model.
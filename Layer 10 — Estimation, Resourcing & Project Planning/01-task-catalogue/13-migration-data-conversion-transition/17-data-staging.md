# Layer 10 — 2.13.17 Data Staging

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 13 — Migration, Data Conversion & Transition |
| Capability ID | 2.13.17 |
| Capability | Data Staging |
| Task Catalogue ID | 13.17 |
| Primary Layer 1 Phases | P05, P06, P08 |
| Classification | CONDITIONAL |

## Capability Objective

Provide controlled staging areas for migration data where direct source-to-target loading is not appropriate.

## Source Implementation Activities

1. Determine staging requirement.
2. Establish staging.
3. Validate staged data.

## Implementation Tasks

### L10-13.17-001 — Assess Staging Requirement

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P04 |
| Primary Role | Technical Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | CONDITIONAL |

**Description**

Determine whether staging is required based on architecture, transformation, security or operational requirements.

**Dependencies**

- Migration architecture

**Deliverable**

Staging decision.

**Acceptance Criteria**

Staging requirement is documented.

### L10-13.17-002 — Establish Migration Staging

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P05 |
| Primary Role | Data Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | HYBRID |
| Baseline Effort | 4.0h |
| Critical Path | CONDITIONAL |

**Description**

Establish secure staging infrastructure and access.

**Dependencies**

- L10-13.17-001

**Deliverable**

Migration staging environment.

**Acceptance Criteria**

Staging is secure and operational.

### L10-13.17-003 — Validate Staged Data

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Data Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Validate staged data before loading.

**Dependencies**

- L10-13.17-002

**Deliverable**

Staging validation evidence.

**Acceptance Criteria**

Staged data passes integrity and security checks.

## Definition of Done

Required staging infrastructure is operational and validated.

---
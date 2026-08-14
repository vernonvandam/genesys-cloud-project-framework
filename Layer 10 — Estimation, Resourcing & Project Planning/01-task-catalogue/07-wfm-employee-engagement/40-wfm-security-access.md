# Layer 10 — 2.07.40 WFM Security & Access

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 07 — Workforce Management & Employee Engagement |
| Capability ID | 2.07.40 |
| Capability | WFM Security & Access |
| Task Catalogue ID | 07.40 |
| Primary Layer 1 Phases | P03, P04, P05, P08, P09, P12 |

## Capability Objective

Apply least-privilege security and access controls to WFM capabilities and workforce data.

## Source Implementation Activities

1. Define WFM security requirements.
2. Define roles and permissions.
3. Configure access.
4. Validate access boundaries.
5. Document security controls.

## Implementation Tasks

### Activity 01 — Define Security Model

#### L10-07.40-001 — Identify WFM Security Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Identify security, privacy, segregation and workforce-data access requirements.

**Dependencies**

- Security framework
- WFM scope

**Deliverable**

WFM security requirements.

**Acceptance Criteria**

Requirements are approved.

#### L10-07.40-002 — Define WFM Roles and Permissions

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Define permissions for agents, supervisors, planners, administrators and support users.

**Dependencies**

- L10-07.40-001

**Deliverable**

WFM security matrix.

**Acceptance Criteria**

Access model is approved.

### Activity 02 — Configure and Validate

#### L10-07.40-003 — Configure WFM Access Controls

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | API / TERRAFORM |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Configure approved WFM roles and permissions.

**Dependencies**

- L10-07.40-002

**Deliverable**

Configured access controls.

**Acceptance Criteria**

Users receive approved access.

#### L10-07.40-004 — Validate WFM Access Boundaries

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Test authorised and unauthorised WFM actions.

**Dependencies**

- L10-07.40-003

**Deliverable**

Security validation evidence.

**Acceptance Criteria**

Access boundaries conform to approved security model.
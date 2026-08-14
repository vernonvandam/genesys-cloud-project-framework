# Layer 10 — 2.02.11 External / Guest Access

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 02 — Identity & Access |
| Capability ID | 2.02.11 |
| Capability | External / Guest Access |
| Task Catalogue ID | 02.11 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P10 |

## Capability Objective

Assess and control external or guest access requirements while maintaining security and least privilege.

## Source Implementation Activities

1. Determine whether external access is required.
2. Identify external populations.
3. Define access controls.
4. Configure approved access.
5. Validate external access.
6. Document governance.

## Implementation Tasks

### Activity 01 — Assess and Design

#### L10-02.11-001 — Determine External Access Requirement

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 0.5h |
| Critical Path | CONDITIONAL |

**Description**

Determine whether external parties require access to Genesys Cloud resources or administration.

**Dependencies**

- Identity architecture

**Deliverable**

External access decision.

**Acceptance Criteria**

Requirement is documented.

#### L10-02.11-002 — Define External Access Controls

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P04 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | CONDITIONAL |

**Description**

Define restrictions, roles, lifecycle, monitoring and approval requirements.

**Dependencies**

- L10-02.11-001

**Deliverable**

External access design.

**Acceptance Criteria**

Controls are approved.

### Activity 02 — Configure and Validate

#### L10-02.11-003 — Configure Approved External Access

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | CONDITIONAL |

**Description**

Configure approved external access using the minimum required permissions.

**Dependencies**

- L10-02.11-002

**Deliverable**

External access configuration.

**Acceptance Criteria**

External users receive only approved access.

#### L10-02.11-004 — Validate External Access

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | CONDITIONAL |

**Description**

Validate allowed and prohibited activities for external users.

**Dependencies**

- L10-02.11-003

**Deliverable**

External access test evidence.

**Acceptance Criteria**

Access boundaries operate as designed.
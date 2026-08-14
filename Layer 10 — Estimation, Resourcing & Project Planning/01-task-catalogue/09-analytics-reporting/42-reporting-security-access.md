# Layer 10 — 2.09.42 Reporting Security & Access

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 09 — Analytics, Reporting & Data Visualisation |
| Capability ID | 2.09.42 |
| Capability | Reporting Security & Access |
| Task Catalogue ID | 09.42 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P10 |

## Capability Objective

Control access to analytics, reports and dashboards according to least-privilege and data protection requirements.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define reporting access requirements |
| P04 | Design access model |
| P06 | Configure access |
| P08 | Validate access |
| P10 | Deploy access model |

## Source Implementation Activities

1. Classify reporting data.
2. Define access groups.
3. Configure permissions.
4. Test access.
5. Approve access model.

## Implementation Tasks

### Activity 01 — Requirements

#### L10-09-42-001 — Define Reporting Access Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Define reporting access requirements by role, division, team and data classification.

**Dependencies**

- Identity and access model
- L10-09-06-001

**Deliverable**

Reporting access requirements.

**Acceptance Criteria**

Access requirements are approved.

### Activity 02 — Design

#### L10-09-42-002 — Design Reporting Access Model

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

Define roles, permissions, divisions and access boundaries.

**Dependencies**

- L10-09-42-001

**Deliverable**

Reporting access model.

**Acceptance Criteria**

Access design is approved.

### Activity 03 — Configure

#### L10-09-42-003 — Configure Reporting Access Controls

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Configure reporting access according to approved design.

**Dependencies**

- L10-09-42-002

**Deliverable**

Reporting access configuration.

**Acceptance Criteria**

Users receive only approved access.

### Activity 04 — Validation

#### L10-09-42-004 — Validate Reporting Access

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Security Analyst |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Test authorised and unauthorised reporting access.

**Dependencies**

- L10-09-42-003

**Deliverable**

Access validation evidence.

**Acceptance Criteria**

All access tests pass.

## Capability-Level Dependencies

- Identity and access
- Divisions
- Reporting
- Security requirements

## Capability-Level Estimation Considerations

Effort depends on data sensitivity and access model complexity.

## Definition of Done

Reporting access is configured according to approved security requirements and validated.
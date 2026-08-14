# Layer 10 — 2.07.23 Agent Self-Service

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 07 — Workforce Management & Employee Engagement |
| Capability ID | 2.07.23 |
| Capability | Agent Self-Service |
| Task Catalogue ID | 07.23 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P09 |

## Capability Objective

Enable agents to perform approved workforce activities without unnecessary supervisor intervention.

## Source Implementation Activities

1. Identify self-service requirements.
2. Define agent permissions.
3. Configure self-service functions.
4. Validate user experience.
5. Prepare training and support.

## Implementation Tasks

### Activity 01 — Define Self-Service

#### L10-07.23-001 — Identify Agent Self-Service Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Identify agent-accessible functions such as schedules, time off, notifications and applicable workforce actions.

**Dependencies**

- WFM operating model

**Deliverable**

Self-service requirements.

**Acceptance Criteria**

Required self-service functions are approved.

#### L10-07.23-002 — Define Agent Permissions

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Define least-privilege access for agent self-service.

**Dependencies**

- L10-07.23-001
- Identity model

**Deliverable**

Agent permission model.

**Acceptance Criteria**

Permissions are approved.

### Activity 02 — Configure and Validate

#### L10-07.23-003 — Configure Agent Self-Service

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Configure approved agent self-service capabilities.

**Dependencies**

- L10-07.23-002

**Deliverable**

Configured self-service capability.

**Acceptance Criteria**

Agents have approved functionality only.

#### L10-07.23-004 — Validate Agent Experience

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Validate representative agent workflows.

**Dependencies**

- L10-07.23-003

**Deliverable**

Agent self-service validation.

**Acceptance Criteria**

UAT users successfully complete approved workflows.
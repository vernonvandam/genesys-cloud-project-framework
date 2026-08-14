# Layer 10 — 2.06.26 Agent Digital Workspace

## Capability Objective

Provide agents with the required digital interaction handling experience.

## Implementation Tasks

### L10-06.26-001 — Define Digital Agent Experience

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Define agent presentation, interaction controls, customer context, transfers, responses and closure.

**Dependencies**

- Digital architecture

**Deliverable**

Agent experience design.

**Acceptance Criteria**

Agent experience approved.

### L10-06.26-002 — Configure Agent Digital Workspace

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Configure the digital agent experience and supporting permissions.

**Dependencies**

- L10-06.26-001

**Deliverable**

Configured workspace.

**Acceptance Criteria**

Agents can handle required digital interactions.

### L10-06.26-003 — Validate Agent Experience

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | UAT |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Validate digital interaction handling, context, transfers, responses and closure.

**Dependencies**

- L10-06.26-002

**Deliverable**

Agent experience validation.

**Acceptance Criteria**

UAT users successfully complete approved scenarios.

## Definition of Done

Agents can handle all required digital interactions using the approved workspace.

---
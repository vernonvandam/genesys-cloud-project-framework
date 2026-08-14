# Layer 10 — 2.04.05 Queue Membership

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 04 — ACD & Routing |
| Capability ID | 2.04.05 |
| Capability | Queue Membership |
| Task Catalogue ID | 04.05 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P10, P11 |

## Capability Objective

Establish agent membership of queues and ensure agents are eligible for the intended interactions.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P03 | Define membership requirements |
| P04 | Design membership model |
| P06 | Configure membership |
| P08 | Validate routing eligibility |
| P10 | Prepare production membership |
| P11 | Validate production membership |

## Source Implementation Activities

1. Identify required queue members.
2. Define membership rules.
3. Configure queue membership.
4. Validate eligibility.

## Implementation Tasks

### Activity 01 — Define Membership

#### L10-04.05-001 — Identify Queue Membership Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Identify agents, groups and teams that require queue membership.

**Dependencies**

- Queue architecture
- Agent population

**Deliverable**

Queue membership matrix.

**Acceptance Criteria**

Membership requirements are approved.

### Activity 02 — Configure Membership

#### L10-04.05-002 — Configure Queue Membership

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 0.25h per agent/queue assignment |
| Critical Path | YES |

**Description**

Assign agents to queues according to the approved membership model.

**Dependencies**

- L10-04.05-001

**Deliverable**

Configured queue memberships.

**Acceptance Criteria**

Required agents have correct queue membership.

### Activity 03 — Validate

#### L10-04.05-003 — Validate Queue Eligibility

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h per queue group |
| Critical Path | YES |

**Description**

Validate that agents can receive interactions from assigned queues.

**Dependencies**

- L10-04.05-002

**Deliverable**

Membership validation evidence.

**Acceptance Criteria**

Expected agents are eligible and unintended agents are excluded.

## Capability-Level Dependencies

- Identity and access
- User provisioning
- Queue configuration
- Skills
- Routing strategy

## Capability-Level Estimation Considerations

Effort is primarily driven by:

- number of agents
- number of queues
- group complexity
- automation method
- migration volume

## Definition of Done

Queue membership is configured, tested and operationally ready.

---
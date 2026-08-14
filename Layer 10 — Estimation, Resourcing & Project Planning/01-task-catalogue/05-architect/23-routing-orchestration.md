# Layer 10 — 2.05.23 Routing Orchestration

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 05 — Architect |
| Capability ID | 2.05.23 |
| Capability | Routing Orchestration |
| Task Catalogue ID | 05.23 |
| Primary Layer 1 Phases | P03, P04, P05, P06, P08, P09, P10, P11, P12 |

## Capability Objective

Orchestrate customer journey decisions that determine queue, skill, priority, transfer and escalation outcomes.

## Source Implementation Activities

1. Define routing decision requirements.
2. Design orchestration logic.
3. Configure routing logic.
4. Validate routing outcomes.

## Implementation Tasks

### Activity 01 — Define Routing Orchestration

#### L10-05.23-001 — Define Routing Decision Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define how customer context, selections, business rules and other inputs influence routing.

**Dependencies**

- ACD routing requirements
- Customer journey requirements

**Deliverable**

Routing decision matrix.

**Acceptance Criteria**

Routing decisions and outcomes are approved.

---

#### L10-05.23-002 — Configure Routing Orchestration

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | NO |
| Environment | DEV |
| Automation | PARTIAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Implement flow logic that determines queue, skill, priority, transfer and escalation outcomes.

**Dependencies**

- L10-05.23-001
- Queue configuration

**Deliverable**

Configured routing orchestration.

**Acceptance Criteria**

Routing decisions match the approved matrix.

---

#### L10-05.23-003 — Validate Routing Outcomes

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate all routing branches, fallback routes and escalation conditions.

**Dependencies**

- L10-05.23-002

**Deliverable**

Routing validation evidence.

**Acceptance Criteria**

All approved routing scenarios pass.
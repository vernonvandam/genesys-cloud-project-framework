# Layer 10 — 2.15.08 Agent Experience Optimisation

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 15 — Optimisation, Continuous Improvement & Platform Evolution |
| Capability ID | 2.15.08 |
| Capability | Agent Experience Optimisation |
| Task Catalogue ID | 15.08 |
| Primary Layer 1 Phases | P02, P03, P04, P08, P09, P11 |

## Capability Objective

Improve agent productivity, usability, workload, information access and interaction handling through targeted Genesys Cloud optimisation.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P02 | Assess current agent experience |
| P03 | Define agent improvement requirements |
| P04 | Design target agent experience |
| P08 | Validate changes |
| P09 | Prepare agents and supervisors |
| P11 | Measure production impact |

## Source Implementation Activities

1. Assess agent experience.
2. Identify agent pain points.
3. Define improvement requirements.
4. Design agent experience changes.
5. Validate and measure outcomes.

## Implementation Tasks

### L10-15.08-001 — Assess Agent Experience Baseline

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Assess agent workflow, handling time, transfers, effort, usability, information access and productivity.

**Dependencies**

- Agent performance data
- Operational stakeholder input

**Deliverable**

Agent experience baseline.

**Acceptance Criteria**

Current-state agent experience is documented.

### L10-15.08-002 — Identify Agent Experience Improvements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Identify improvements to agent workflows, information access, routing, workspace and automation.

**Dependencies**

- L10-15.08-001

**Deliverable**

Agent optimisation backlog.

**Acceptance Criteria**

Opportunities are documented and prioritised.

### L10-15.08-003 — Design Agent Experience Improvements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.5h |
| Critical Path | NO |

**Description**

Design approved improvements to the agent experience and supporting configuration.

**Dependencies**

- L10-15.08-002

**Deliverable**

Agent experience design.

**Acceptance Criteria**

Target design is approved.

### L10-15.08-004 — Validate Agent Outcomes

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P11 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Measure agent productivity, effort and experience after implementation.

**Dependencies**

- L10-15.08-003

**Deliverable**

Agent outcome validation.

**Acceptance Criteria**

Expected outcomes are measured and accepted.
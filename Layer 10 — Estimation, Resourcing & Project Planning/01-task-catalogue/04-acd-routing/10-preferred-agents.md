# Layer 10 — 2.04.10 Preferred Agents

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 04 — ACD & Routing |
| Capability ID | 2.04.10 |
| Capability | Preferred Agents |
| Task Catalogue ID | 04.10 |
| Primary Layer 1 Phases | P03, P04, P06, P08, P09 |

## Capability Objective

Support routing requirements where interactions should preferentially be offered to specific agents or agent groups.

## Source Implementation Activities

1. Identify preferred-agent requirements.
2. Define preference rules.
3. Configure preference behaviour.
4. Validate routing.

## Implementation Tasks

### L10-04.10-001 — Identify Preferred Agent Requirements

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Business Analyst |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | CONDITIONAL |

**Description**

Identify business processes requiring preferred-agent treatment.

**Dependencies**

- Business requirements

**Deliverable**

Preferred-agent requirements.

**Acceptance Criteria**

Requirements are approved.

### L10-04.10-002 — Define Preference Rules

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | CONDITIONAL |

**Description**

Define agent preference criteria and fallback behaviour.

**Dependencies**

- L10-04.10-001

**Deliverable**

Preference design.

**Acceptance Criteria**

Preference and fallback rules are approved.

### L10-04.10-003 — Configure Preferred-Agent Routing

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h per routing model |
| Critical Path | CONDITIONAL |

**Description**

Implement approved preferred-agent routing behaviour.

**Dependencies**

- L10-04.10-002

**Deliverable**

Configured preferred-agent routing.

**Acceptance Criteria**

Preferred agents are selected where eligible and fallback operates correctly.

### L10-04.10-004 — Validate Preferred-Agent Routing

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | CONDITIONAL |

**Description**

Validate preferred-agent and fallback scenarios.

**Dependencies**

- L10-04.10-003

**Deliverable**

Validation evidence.

**Acceptance Criteria**

Preferred and fallback behaviour passes test cases.

## Definition of Done

Preferred-agent routing operates as approved where applicable.

---

# Layer 10 — 2.04.28 Routing Dependencies

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 04 — ACD & Routing |
| Capability ID | 2.04.28 |
| Capability | Routing Dependencies |
| Task Catalogue ID | 04.28 |
| Primary Layer 1 Phases | P02, P03, P04, P05, P07, P08, P10, P11 |

## Capability Objective

Identify, manage and validate dependencies that affect ACD and routing behaviour.

## Source Implementation Activities

1. Identify routing dependencies.
2. Classify dependencies.
3. Track dependency readiness.
4. Validate dependencies.
5. Manage unresolved risks.

## Implementation Tasks

### L10-04.28-001 — Identify Routing Dependencies

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Identify dependencies on queues, users, skills, Architect, telephony, digital, integrations and data.

**Dependencies**

- Current-state assessment

**Deliverable**

Routing dependency register.

**Acceptance Criteria**

Material dependencies are identified.

### L10-04.28-002 — Assess Dependency Readiness

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P07 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Confirm that required routing dependencies are available before configuration and testing.

**Dependencies**

- L10-04.28-001

**Deliverable**

Dependency readiness assessment.

**Acceptance Criteria**

Critical dependencies are ready or have approved workarounds.

### L10-04.28-003 — Validate Routing Dependencies

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Validate routing against all identified dependencies.

**Dependencies**

- L10-04.28-002
- Routing configuration

**Deliverable**

Dependency validation record.

**Acceptance Criteria**

No unresolved critical routing dependency remains.

## Definition of Done

Routing dependencies are identified, tracked, validated and operationally resolved.

---

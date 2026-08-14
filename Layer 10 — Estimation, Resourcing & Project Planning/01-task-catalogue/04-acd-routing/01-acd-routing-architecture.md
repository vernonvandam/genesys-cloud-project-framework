# Layer 10 — 2.04.01 ACD & Routing Architecture

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 04 — ACD & Routing |
| Capability ID | 2.04.01 |
| Capability | ACD & Routing Architecture |
| Task Catalogue ID | 04.01 |
| Primary Layer 1 Phases | P01, P02, P03, P04, P05, P08, P10, P12 |

## Capability Objective

Define the target ACD and routing architecture covering queues, skills, routing methods, priorities, agent groups, overflow, channels, and routing dependencies.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P01 | Confirm routing scope and ownership |
| P02 | Assess current routing architecture |
| P03 | Define routing requirements |
| P04 | Produce target routing architecture |
| P05 | Establish routing foundations |
| P08 | Validate routing architecture |
| P10 | Confirm production readiness |
| P12 | Document and hand over routing architecture |

## Source Implementation Activities

1. Confirm ACD and routing requirements.
2. Assess current-state routing.
3. Define target routing architecture.
4. Establish routing configuration standards.
5. Validate routing architecture.
6. Document the final routing model.

## Implementation Tasks

### Activity 01 — Confirm Routing Requirements

#### L10-04.01-001 — Confirm ACD and Routing Scope

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P01 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Confirm channels, queues, routing objectives, agent populations and business processes included in the ACD solution.

**Dependencies**

- Project initiation
- Business requirements

**Deliverable**

Approved routing scope.

**Acceptance Criteria**

Routing scope is documented and approved.

#### L10-04.01-002 — Identify Routing Dependencies

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Identify dependencies on Architect, telephony, digital channels, identity, WFM, integrations and data.

**Dependencies**

- L10-04.01-001

**Deliverable**

Routing dependency register.

**Acceptance Criteria**

All material routing dependencies are documented.

### Activity 02 — Design Routing Architecture

#### L10-04.01-003 — Define Target Routing Architecture

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Define queue, skill, routing-method, priority, overflow and agent-selection architecture.

**Dependencies**

- L10-04.01-002

**Deliverable**

Target ACD and routing architecture.

**Acceptance Criteria**

Architecture is documented and approved.

#### L10-04.01-004 — Define Routing Configuration Standards

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | NO |

**Description**

Define naming, configuration, ownership and documentation standards for routing components.

**Dependencies**

- L10-04.01-003

**Deliverable**

Routing configuration standards.

**Acceptance Criteria**

Standards are approved for implementation.

### Activity 03 — Validate Architecture

#### L10-04.01-005 — Validate Routing Architecture

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

Review implemented routing against the approved architecture.

**Dependencies**

- L10-04.01-003
- Routing configuration

**Deliverable**

Architecture validation record.

**Acceptance Criteria**

Implemented routing conforms to the approved target design.

### Activity 04 — Handover

#### L10-04.01-006 — Document Routing Architecture

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Document final routing architecture and operational dependencies.

**Dependencies**

- L10-04.01-005

**Deliverable**

Routing architecture record.

**Acceptance Criteria**

Documentation is complete and accepted for handover.

## Capability-Level Dependencies

- Core platform organisation
- Identity and access
- Telephony and digital channels
- Architect
- Business requirements

## Capability-Level Estimation Considerations

Effort varies according to:

- number of channels
- number of queues
- routing complexity
- number of skills
- existing-state complexity
- migration requirements
- integration dependencies

## Definition of Done

The routing architecture is approved, implemented consistently, validated, documented and ready for operational ownership.

---

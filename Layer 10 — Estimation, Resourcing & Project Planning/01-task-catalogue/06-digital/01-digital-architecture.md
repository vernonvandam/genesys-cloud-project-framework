# Layer 10 — 2.06.01 Digital Architecture

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 06 — Digital |
| Capability ID | 2.06.01 |
| Capability | Digital Architecture |
| Task Catalogue ID | 06.01 |
| Primary Layer 1 Phases | P01, P02, P03, P04, P05, P06, P08, P09, P10, P11, P12 |

## Capability Objective

Define the target digital architecture covering channels, customer journeys, identity, routing, queues, skills, bots, integrations, agent handling, security, analytics and operational support.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P01 | Establish digital scope |
| P02 | Assess current-state digital architecture |
| P03 | Define requirements |
| P04 | Produce target architecture |
| P05 | Establish digital foundation |
| P06 | Configure digital solution |
| P08 | Validate architecture |
| P09 | Prepare operational model |
| P10 | Confirm production readiness |
| P11 | Validate production architecture |
| P12 | Complete handover |

## Source Implementation Activities

1. Establish digital architecture scope.
2. Assess current-state digital channels.
3. Define target digital architecture.
4. Map dependencies.
5. Validate target architecture.
6. Document the architecture.

## Implementation Tasks

### Activity 01 — Establish Digital Architecture Scope

#### L10-06.01-001 — Confirm Digital Architecture Scope

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

Confirm channels, customer journeys, integrations, routing, identity, agent experience and operational components included in the digital architecture.

**Dependencies**

- Project initiation

**Deliverable**

Digital architecture scope.

**Acceptance Criteria**

Scope is documented and approved.

### Activity 02 — Assess Current State

#### L10-06.01-002 — Assess Existing Digital Architecture

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Assess existing digital channels, integrations, routing, customer identity, journeys and agent handling.

**Dependencies**

- L10-06.01-001

**Deliverable**

Current-state assessment.

**Acceptance Criteria**

Current-state architecture and known constraints are documented.

### Activity 03 — Design Target Architecture

#### L10-06.01-003 — Define Digital Target Architecture

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Define target digital channels, routing, identity, journeys, integrations, security, analytics and agent handling.

**Dependencies**

- L10-06.01-002
- Layer 2 Core Platform
- Layer 2 ACD Routing

**Deliverable**

Digital target architecture.

**Acceptance Criteria**

Architecture is reviewed and approved.

### Activity 04 — Validate Architecture

#### L10-06.01-004 — Validate Digital Architecture Dependencies

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate that channel, routing, identity, integration, security and agent dependencies are implementable.

**Dependencies**

- L10-06.01-003

**Deliverable**

Architecture validation record.

**Acceptance Criteria**

All material dependencies have owners and resolution paths.

### Activity 05 — Document Architecture

#### L10-06.01-005 — Document Digital Architecture

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Document final digital architecture and operational dependencies.

**Dependencies**

- L10-06.01-004

**Deliverable**

Digital architecture document.

**Acceptance Criteria**

Architecture is complete and accepted.

## Capability-Level Dependencies

- Core Platform
- Identity & Access
- ACD Routing
- Architect
- Integrations
- Security

## Capability-Level Estimation Considerations

Effort depends on:

- number of channels
- number of journeys
- number of integrations
- complexity of identity
- routing complexity
- existing-state complexity
- security requirements

## Definition of Done

Digital architecture is approved, implementable, documented and aligned with dependent platform domains.

---
# Layer 10 — 2.05.01 Architect Architecture

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 05 — Architect |
| Capability ID | 2.05.01 |
| Capability | Architect Architecture |
| Task Catalogue ID | 05.01 |
| Primary Layer 1 Phases | P01, P02, P03, P04, P05, P06, P08, P09, P10, P11, P12 |

## Capability Objective

Define the overall Architect architecture, flow boundaries, reusable components, data dependencies, routing integration, security model and lifecycle approach.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P01 | Establish Architect scope and ownership |
| P02 | Discover existing Architect architecture |
| P03 | Define flow and orchestration requirements |
| P04 | Design target Architect architecture |
| P05 | Establish Architect foundation |
| P06 | Build and configure Architect solution |
| P08 | Validate Architect behaviour |
| P09 | Prepare operational support |
| P10 | Deploy production flows |
| P11 | Monitor and stabilise |
| P12 | Handover Architect ownership |

## Source Implementation Activities

1. Establish Architect architecture and scope.
2. Assess existing flows and dependencies.
3. Define target-state architecture.
4. Configure required Architect foundation.
5. Validate architectural implementation.

## Implementation Tasks

### Activity 01 — Establish Architect Architecture

#### L10-05.01-001 — Confirm Architect Scope

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

Confirm the Architect capabilities, interaction channels, journeys and business processes included in the implementation.

**Dependencies**

- Project initiation

**Deliverable**

Architect scope definition.

**Acceptance Criteria**

Architect scope is documented and approved.

---

#### L10-05.01-002 — Assess Existing Architect Architecture

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P02 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | CONDITIONAL |

**Description**

Assess existing Architect flows, modules, data dependencies, integrations, schedules and routing relationships.

**Dependencies**

- L10-05.01-001

**Deliverable**

Architect current-state assessment.

**Acceptance Criteria**

Existing Architect dependencies and risks are documented.

---

#### L10-05.01-003 — Design Target Architect Architecture

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

Define the target Architect architecture, including flow types, reusable components, data interactions, routing, security and lifecycle.

**Dependencies**

- L10-05.01-002

**Deliverable**

Architect architecture design.

**Acceptance Criteria**

Target architecture is documented and approved.

## Capability-Level Dependencies

- Core Platform
- Voice & Telephony
- ACD Routing
- Data and Integrations
- Security
- Environment strategy

## Capability-Level Estimation Considerations

Effort is influenced by:

- number of interaction channels
- flow count
- flow complexity
- integrations
- reusable components
- security requirements
- migration complexity

## Definition of Done

Architect architecture is approved, dependencies are understood, implementation boundaries are defined, and dependent Architect capabilities can proceed.
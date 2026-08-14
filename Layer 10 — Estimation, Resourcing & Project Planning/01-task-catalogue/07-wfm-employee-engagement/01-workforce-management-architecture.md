# Layer 10 — 2.07.01 Workforce Management Architecture

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 07 — Workforce Management & Employee Engagement |
| Capability ID | 2.07.01 |
| Capability | Workforce Management Architecture |
| Task Catalogue ID | 07.01 |
| Primary Layer 1 Phases | P01, P02, P03, P04, P05, P08, P09, P12 |

## Capability Objective

Define the target WFM architecture, operating model, dependencies, data flows and integration boundaries.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P01 | Confirm WFM scope and ownership |
| P02 | Assess current workforce architecture |
| P03 | Define WFM requirements |
| P04 | Produce WFM architecture |
| P05 | Establish WFM foundation |
| P08 | Validate architecture |
| P09 | Prepare operational ownership |
| P12 | Complete architecture handover |

## Source Implementation Activities

1. Establish WFM architectural requirements.
2. Assess current workforce architecture.
3. Define target WFM architecture.
4. Define cross-domain dependencies.
5. Document and approve the architecture.

## Implementation Tasks

### Activity 01 — Establish WFM Architectural Requirements

#### L10-07.01-001 — Confirm WFM Scope

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

Confirm WFM capabilities, organisational scope, workforce populations and implementation boundaries.

**Dependencies**

- Project initiation
- WFM ownership

**Deliverable**

Approved WFM scope.

**Acceptance Criteria**

WFM scope is documented and approved.

---

#### L10-07.01-002 — Capture WFM Architectural Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | WFM Consultant |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Capture requirements covering forecasting, staffing, scheduling, adherence, integrations, reporting and employee experience.

**Dependencies**

- L10-07.01-001

**Deliverable**

WFM requirements catalogue.

**Acceptance Criteria**

Requirements are documented, traceable and approved.

### Activity 02 — Define Target Architecture

#### L10-07.01-003 — Design WFM Architecture

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

Design the WFM architecture covering business units, management units, planning groups, forecasting, scheduling, adherence, integrations and reporting.

**Dependencies**

- L10-07.01-002
- ACD routing design

**Deliverable**

WFM architecture design.

**Acceptance Criteria**

Architecture addresses all in-scope WFM capabilities and dependencies.

---

#### L10-07.01-004 — Define WFM Integration Boundaries

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Technical Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define boundaries between Genesys Cloud WFM, ACD, HR/HCM, payroll, reporting and external systems.

**Dependencies**

- L10-07.01-003

**Deliverable**

WFM integration boundary definition.

**Acceptance Criteria**

System ownership and data boundaries are approved.

### Activity 03 — Validate and Handover Architecture

#### L10-07.01-005 — Validate WFM Architecture

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

Validate that the configured WFM solution conforms to the approved architecture.

**Dependencies**

- L10-07.01-003
- WFM configuration

**Deliverable**

Architecture validation record.

**Acceptance Criteria**

Architecture deviations are resolved or formally accepted.

---

#### L10-07.01-006 — Handover WFM Architecture

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | NO |

**Description**

Document the final WFM architecture and transfer ownership to BAU stakeholders.

**Dependencies**

- L10-07.01-005

**Deliverable**

WFM architecture handover pack.

**Acceptance Criteria**

Customer operational owners accept the final architecture.

## Capability-Level Dependencies

- Core Platform
- ACD Routing
- Identity & Access
- HR/HCM requirements
- Reporting requirements

## Capability-Level Estimation Considerations

Effort is influenced by:

- number of workforce populations
- organisational complexity
- number of integrations
- WFM scope
- reporting complexity
- regulatory requirements

## Definition of Done

The WFM architecture is approved, validated, documented and accepted by the operational owner.
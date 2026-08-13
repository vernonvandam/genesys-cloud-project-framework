# Layer 10 — 2.01.01 Genesys Cloud Organisation

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 01 — Core Platform |
| Capability ID | 2.01.01 |
| Capability | Genesys Cloud Organisation |
| Task Catalogue ID | 01.01 |
| Primary Layer 1 Phases | P01, P02, P03, P04, P05, P08, P10, P11, P12 |

## Capability Objective

Establish, configure, secure, document, and validate the Genesys Cloud organisation that will host the customer solution.

The implementation must confirm organisation ownership, provisioning requirements, tenant strategy, administrative boundaries, regional requirements, and production readiness.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P01 | Confirm ownership, scope and provisioning responsibilities |
| P02 | Assess existing organisation and current-state configuration |
| P03 | Define organisation requirements |
| P04 | Produce organisation architecture and design |
| P05 | Provision and establish the organisation |
| P08 | Validate organisation configuration |
| P10 | Confirm production readiness |
| P11 | Validate production organisation after cutover |
| P12 | Complete operational handover |

## Source Implementation Activities

1. Confirm organisation requirements and ownership.
2. Assess existing organisation or establish new-organisation strategy.
3. Define organisation architecture.
4. Provision or configure the Genesys Cloud organisation.
5. Validate organisation configuration.
6. Document organisation configuration and handover requirements.

## Implementation Tasks

### Activity 01 — Confirm Organisation Requirements and Ownership

#### L10-01.01-001 — Confirm Organisation Ownership

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P01 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 0.5h |
| Critical Path | YES |

**Description**

Confirm the legal, commercial, technical, and operational owner of the Genesys Cloud organisation.

**Dependencies**

- Project initiation
- Customer stakeholder identification

**Deliverable**

Organisation ownership decision.

**Acceptance Criteria**

Organisation ownership is documented and approved by the customer.

---

#### L10-01.01-002 — Confirm Existing or New Organisation Strategy

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Determine whether the project will use an existing Genesys Cloud organisation or require a new organisation.

**Dependencies**

- L10-01.01-001

**Deliverable**

Organisation strategy decision.

**Acceptance Criteria**

The approved organisation strategy is documented.

---

#### L10-01.01-003 — Confirm Organisation Provisioning Responsibility

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 0.5h |
| Critical Path | YES |

**Description**

Confirm who is responsible for requesting, provisioning, accessing, and administering the Genesys Cloud organisation.

**Dependencies**

- L10-01.01-002

**Deliverable**

Provisioning responsibility matrix.

**Acceptance Criteria**

Responsibilities are documented and accepted by all parties.

### Activity 02 — Assess Existing Organisation

#### L10-01.01-004 — Assess Existing Organisation Configuration

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P02 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Review the existing organisation configuration, including organisational structures, settings, users, roles, integrations, and other existing dependencies.

**Dependencies**

- L10-01.01-002

**Deliverable**

Current-state organisation assessment.

**Acceptance Criteria**

Relevant existing configuration and risks are documented.

---

#### L10-01.01-005 — Identify Existing Configuration Conflicts

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P02 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | CONDITIONAL |

**Description**

Identify existing configuration that may conflict with the target-state design.

**Dependencies**

- L10-01.01-004

**Deliverable**

Configuration conflict register.

**Acceptance Criteria**

Conflicts are documented with an agreed resolution approach.

### Activity 03 — Define Organisation Architecture

#### L10-01.01-006 — Define Organisation Architecture

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define the target organisation architecture and its relationship to divisions, business units, environments, identity, routing, reporting, and security.

**Dependencies**

- L10-01.01-003
- L10-01.01-004

**Deliverable**

Organisation architecture design.

**Acceptance Criteria**

Target organisation architecture is documented and approved.

### Activity 04 — Provision and Configure Organisation

#### L10-01.01-007 — Provision Genesys Cloud Organisation

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Provision the Genesys Cloud organisation where a new organisation is required.

**Dependencies**

- L10-01.01-006

**Deliverable**

Provisioned organisation.

**Acceptance Criteria**

Organisation is accessible and available for configuration.

---

#### L10-01.01-008 — Establish Initial Administrative Access

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Establish initial administrative access required to continue platform configuration.

**Dependencies**

- L10-01.01-007

**Deliverable**

Validated administrative access.

**Acceptance Criteria**

Authorised administrators can access the organisation using the approved authentication approach.

### Activity 05 — Validate Organisation

#### L10-01.01-009 — Validate Organisation Accessibility

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 0.5h |
| Critical Path | YES |

**Description**

Validate that the organisation can be accessed and operated as designed.

**Dependencies**

- L10-01.01-008

**Deliverable**

Organisation validation evidence.

**Acceptance Criteria**

Organisation access and baseline platform availability are confirmed.

---

#### L10-01.01-010 — Document Organisation Configuration

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Document the final organisation configuration, ownership, access model, and relevant operational dependencies.

**Dependencies**

- L10-01.01-009

**Deliverable**

Organisation configuration record.

**Acceptance Criteria**

Documentation is complete and accepted for operational handover.

## Capability-Level Dependencies

- Project initiation
- Customer ownership decisions
- Data residency requirements
- Identity and access strategy
- Environment strategy
- Security requirements

## Capability-Level Estimation Considerations

Effort is influenced by:

- new versus existing organisation
- number of organisations
- number of environments
- existing configuration complexity
- migration requirements
- administrative access model
- customer approval cycles
- automation requirements

## Definition of Done

The Genesys Cloud organisation is:

- established or confirmed
- owned and governed
- architecturally defined
- accessible to authorised administrators
- validated
- documented
- ready for dependent platform configuration
- handed over to the appropriate operational owner
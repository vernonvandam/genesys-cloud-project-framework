# Layer 10 — 2.02.01 Identity Architecture & Governance

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 02 — Identity & Access |
| Capability ID | 2.02.01 |
| Capability | Identity Architecture & Governance |
| Task Catalogue ID | 02.01 |
| Primary Layer 1 Phases | P01, P02, P03, P04, P05, P09, P12 |

## Capability Objective

Define the identity architecture, ownership model, governance framework and security principles governing access to Genesys Cloud.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P01 | Identify identity owners and governance stakeholders |
| P02 | Assess current IAM architecture |
| P03 | Define identity requirements |
| P04 | Design target identity architecture |
| P05 | Establish foundational identity controls |
| P09 | Define operational governance |
| P12 | Complete BAU identity handover |

## Source Implementation Activities

1. Confirm identity ownership and governance.
2. Assess current-state IAM architecture.
3. Define identity requirements.
4. Design target identity architecture.
5. Define governance and control processes.
6. Document the approved identity architecture.

## Implementation Tasks

### Activity 01 — Establish Identity Governance

#### L10-02.01-001 — Confirm Identity Ownership

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

Confirm the business, security, IAM and technical owners responsible for Genesys Cloud identity management.

**Dependencies**

- Project initiation
- Customer stakeholder identification

**Deliverable**

Identity ownership matrix.

**Acceptance Criteria**

Identity ownership and accountability are documented and approved.

---

#### L10-02.01-002 — Define Identity Governance Principles

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Define least-privilege, separation-of-duties, authentication, provisioning and privileged-access principles.

**Dependencies**

- L10-02.01-001

**Deliverable**

Identity governance principles.

**Acceptance Criteria**

Principles are documented and approved.

### Activity 02 — Assess Current State

#### L10-02.01-003 — Assess Existing IAM Architecture

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

Assess the customer identity provider, authentication model, directory structure, provisioning processes and administrative controls.

**Dependencies**

- L10-02.01-001

**Deliverable**

Current-state IAM assessment.

**Acceptance Criteria**

Current identity architecture and material gaps are documented.

### Activity 03 — Define Target Architecture

#### L10-02.01-004 — Define Target Identity Architecture

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

Define the target identity architecture covering human users, administrators, service identities, federation, provisioning and access governance.

**Dependencies**

- L10-02.01-003
- Customer security requirements

**Deliverable**

Identity architecture design.

**Acceptance Criteria**

Target architecture is approved.

#### L10-02.01-005 — Define Identity Governance Model

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | NO |

**Description**

Define ownership, approval, access review, privileged access and exception-management processes.

**Dependencies**

- L10-02.01-004

**Deliverable**

Identity governance model.

**Acceptance Criteria**

Governance responsibilities and review processes are documented.

### Activity 04 — Handover

#### L10-02.01-006 — Document Identity Architecture

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

Document the approved identity architecture, ownership model, controls and operational dependencies.

**Dependencies**

- L10-02.01-004
- L10-02.01-005

**Deliverable**

Identity architecture and governance documentation.

**Acceptance Criteria**

Documentation is complete and accepted for BAU.

## Capability-Level Dependencies

- Genesys Cloud organisation
- Customer IAM platform
- Security architecture
- Division model
- Environment strategy

## Capability-Level Estimation Considerations

Effort is influenced by:

- IAM maturity
- number of identity providers
- number of user populations
- security governance requirements
- regulatory controls
- number of environments
- customer approval cycles

## Definition of Done

Identity architecture and governance are approved, documented, operationally owned and aligned with the target Genesys Cloud solution.
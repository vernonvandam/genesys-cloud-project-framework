# Layer 10 — 2.14.01 Operating Model

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 14 — Operations, Support & Service Management |
| Capability ID | 2.14.01 |
| Capability | Operating Model |
| Task Catalogue ID | 14.01 |
| Primary Layer 1 Phases | P01, P02, P03, P04, P09, P12 |

## Capability Objective

Define the operating model required to manage, support and govern Genesys Cloud after implementation.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P01 | Identify operational stakeholders |
| P02 | Assess current operating model |
| P03 | Define operational requirements |
| P04 | Design target operating model |
| P09 | Prepare operational teams |
| P12 | Accept BAU operating model |

## Source Implementation Activities

1. Identify operational stakeholders and ownership.
2. Assess the current operating model.
3. Define the target operating model.
4. Define support and governance responsibilities.
5. Validate operational readiness.
6. Complete operational acceptance.

## Implementation Tasks

### Activity 01 — Define Operating Model

#### L10-14.01-001 — Identify Operational Stakeholders

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P01 |
| Primary Role | Service Manager |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Identify business, service, platform, support, security, integration and vendor stakeholders.

**Dependencies**

- Project initiation
- Customer stakeholder identification

**Deliverable**

Operational stakeholder register.

**Acceptance Criteria**

All required operational stakeholder groups are identified and ownership is agreed.

#### L10-14.01-002 — Define Target Operating Model

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

Define the target operating model, including ownership, support tiers, governance, escalation and operational responsibilities.

**Dependencies**

- L10-14.01-001
- Current-state assessment

**Deliverable**

Target operating model.

**Acceptance Criteria**

The operating model is documented and approved.

#### L10-14.01-003 — Validate Operating Model Readiness

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P09 |
| Primary Role | Service Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate that operational ownership and responsibilities are ready for BAU.

**Dependencies**

- L10-14.01-002
- Support model
- Training
- Operational documentation

**Deliverable**

Operating model readiness assessment.

**Acceptance Criteria**

All critical operational responsibilities have accountable owners.

## Capability-Level Dependencies

- Project governance
- Customer operating model
- Support model
- Security governance
- BAU resources

## Capability-Level Estimation Considerations

- number of support teams
- support hours
- number of environments
- operational complexity
- customer governance requirements
- vendor dependencies

## Definition of Done

The target operating model is documented, approved, resourced and ready for BAU.

---
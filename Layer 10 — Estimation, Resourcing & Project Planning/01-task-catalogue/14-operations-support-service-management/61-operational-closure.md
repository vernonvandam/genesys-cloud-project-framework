# Layer 10 — 2.14.61 Operational Closure

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 14 — Operations, Support & Service Management |
| Capability ID | 2.14.61 |
| Capability | Operational Closure |
| Task Catalogue ID | 14.61 |
| Primary Layer 1 Phases | P12 |

## Capability Objective

Complete formal operational closure of the implementation and confirm that the Genesys Cloud service has transitioned successfully into BAU.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P12 | Complete operational closure and confirm BAU acceptance |

## Source Implementation Activities

1. Confirm operational deliverables.
2. Confirm outstanding operational actions.
3. Confirm BAU ownership.
4. Confirm project documentation.
5. Obtain operational closure approval.

## Implementation Tasks

### Activity 01 — Confirm Operational Deliverables

#### L10-14.61-001 — Review Operational Deliverables

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Service Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Review operational documentation, support processes, training, monitoring, ownership and handover deliverables.

**Dependencies**

- Operational handover
- BAU transition
- Hypercare exit

**Deliverable**

Operational closure checklist.

**Acceptance Criteria**

Required operational deliverables are complete or formally accepted with exceptions.

---

### Activity 02 — Confirm Outstanding Actions

#### L10-14.61-002 — Review Outstanding Operational Actions

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Service Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Review open operational issues, risks, defects, documentation actions and optimisation items.

**Dependencies**

- L10-14.61-001
- Optimisation backlog

**Deliverable**

Operational action register.

**Acceptance Criteria**

All outstanding actions have owners, priorities and agreed treatment.

---

### Activity 03 — Confirm BAU Ownership

#### L10-14.61-003 — Confirm BAU Service Ownership

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P12 |
| Primary Role | Service Manager |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Confirm that the customer has formally accepted ownership of the operational Genesys Cloud service.

**Dependencies**

- L10-14.61-002
- Service ownership
- Operational handover

**Deliverable**

BAU ownership confirmation.

**Acceptance Criteria**

Named BAU owner formally accepts service responsibility.

---

### Activity 04 — Complete Operational Closure

#### L10-14.61-004 — Obtain Operational Closure Approval

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P12 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Obtain formal approval that the operational transition is complete and the service can be managed through BAU governance.

**Dependencies**

- L10-14.61-003
- Operational closure checklist
- BAU transition

**Deliverable**

Operational closure approval.

**Acceptance Criteria**

Customer and delivery stakeholders approve operational closure.

## Capability-Level Dependencies

- Operating model
- Service ownership
- BAU readiness
- Support model
- Monitoring
- Documentation
- Training
- Knowledge transfer
- Operational handover
- Hypercare exit
- BAU transition
- Optimisation backlog

## Capability-Level Estimation Considerations

Effort is influenced by:

- number of operational workstreams
- number of support tiers
- documentation volume
- customer governance requirements
- number of operational stakeholders
- outstanding project actions
- hypercare duration
- BAU acceptance process
- number of open optimisation items

## Definition of Done

Operational closure is complete when:

- operational deliverables are reviewed
- outstanding actions are assigned
- BAU ownership is accepted
- operational documentation is complete
- support processes are operational
- hypercare exit is approved
- BAU transition is complete
- optimisation backlog is transferred
- operational closure is formally approved

---

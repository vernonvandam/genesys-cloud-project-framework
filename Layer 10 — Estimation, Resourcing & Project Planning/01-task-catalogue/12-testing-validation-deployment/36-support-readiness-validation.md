# Layer 10 — 2.12.36 Support Readiness Validation

## Capability Reference

| Attribute | Value |
|---|---|
| Layer 2 Capability | 2.12.36 — Support Readiness Validation |
| Layer 10 Domain | 12 — Testing, Validation & Deployment |
| Task Prefix | L10-12.36 |
| Default Classification | REQUIRED |
| Primary Layer 1 Phases | P09–P10 |
| Primary Role | Service Manager |
| Customer Responsibility | JOINT |
| Primary Environment | PROD / MULTI |
| Automation | MANUAL |
| Critical Path | YES |

## Capability Objective

Confirm support teams can diagnose, escalate, resolve and manage Genesys Cloud incidents after go-live.

## Source Implementation Activities

- Validate support model.
- Validate support documentation.
- Validate escalation paths.
- Validate incident workflows.
- Obtain support readiness approval.

## Implementation Tasks

### Activity 01 — Validate Support Model

#### L10-12.36-001 — Review Support Operating Model

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | Service Manager |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Confirm support ownership, hours, escalation and service management processes.

**Dependencies**

Operations & Support design.

**Deliverable**

Support Readiness Checklist.

**Acceptance Criteria**

Support responsibilities and escalation paths are defined.

### Activity 02 — Validate Support Materials

#### L10-12.36-002 — Validate Support Documentation

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09–P10 |
| Primary Role | Service Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Review runbooks, troubleshooting guides and operational documentation.

**Dependencies**

Operations documentation.

**Deliverable**

Support Documentation Validation.

**Acceptance Criteria**

Required support materials are complete and usable.

### Activity 03 — Validate Escalation

#### L10-12.36-003 — Validate Incident Escalation Process

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P10 |
| Primary Role | Service Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate technical, business and vendor escalation paths.

**Dependencies**

L10-12.36-001 and L10-12.36-002.

**Deliverable**

Escalation Validation Results.

**Acceptance Criteria**

Escalation paths are confirmed.

## Capability-Level Dependencies

- Operations
- Support
- Documentation
- Training

## Capability-Level Estimation Considerations

Number of support tiers, integrations and escalation paths drives effort.

## Definition of Done

Support teams are ready to operate the solution.

---
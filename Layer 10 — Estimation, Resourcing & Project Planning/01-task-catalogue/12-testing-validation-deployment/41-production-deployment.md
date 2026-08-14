# Layer 10 — 2.12.41 Production Deployment

## Capability Reference

| Attribute | Value |
|---|---|
| Layer 2 Capability | 2.12.41 — Production Deployment |
| Layer 10 Domain | 12 — Testing, Validation & Deployment |
| Task Prefix | L10-12.41 |
| Default Classification | REQUIRED |
| Primary Layer 1 Phases | P10–P11 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Primary Environment | PROD |
| Automation | HYBRID |
| Critical Path | YES |

## Capability Objective

Execute the approved production deployment according to the authorised deployment and cutover plans.

## Source Implementation Activities

- Confirm deployment prerequisites.
- Execute production deployment.
- Monitor deployment.
- Validate deployment completion.
- Record deployment evidence.

## Implementation Tasks

### Activity 01 — Confirm Deployment Entry

#### L10-12.41-001 — Confirm Production Deployment Prerequisites

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P10 |
| Primary Role | Project Manager |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Confirm go-live approval, deployment window, resources, access and rollback readiness.

**Dependencies**

Go-Live Readiness.

**Deliverable**

Deployment Entry Checklist.

**Acceptance Criteria**

All deployment prerequisites are satisfied.

### Activity 02 — Execute Deployment

#### L10-12.41-002 — Execute Production Deployment

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P10–P11 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | HYBRID |
| Baseline Effort | 8.0h |
| Critical Path | YES |

**Description**

Execute approved production deployment steps.

**Dependencies**

L10-12.41-001.

**Deliverable**

Production Deployment Record.

**Acceptance Criteria**

All approved deployment steps complete successfully.

### Activity 03 — Record Evidence

#### L10-12.41-003 — Capture Deployment Evidence

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P11 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Capture deployment logs, validation evidence and issues.

**Dependencies**

L10-12.41-002.

**Deliverable**

Deployment Evidence Pack.

**Acceptance Criteria**

Required evidence is complete and retained.

## Capability-Level Dependencies

- Go-Live Approval
- Deployment Plan
- Cutover Plan
- Rollback Plan

## Capability-Level Estimation Considerations

Deployment duration, number of components and manual steps drive effort.

## Definition of Done

Production deployment completes successfully and evidence is captured.

---
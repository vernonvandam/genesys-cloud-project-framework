# Layer 10 — 2.14.03 BAU Readiness

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 14 — Operations, Support & Service Management |
| Capability ID | 2.14.03 |
| Capability | BAU Readiness |
| Task Catalogue ID | 14.03 |
| Primary Layer 1 Phases | P08, P09, P10, P11, P12 |
| Classification | REQUIRED |

## Capability Objective

Ensure the customer can operate and support the Genesys Cloud solution following go-live.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P08 | Validate operational processes |
| P09 | Complete BAU readiness |
| P10 | Confirm production readiness |
| P11 | Operate during hypercare |
| P12 | Accept BAU transition |

## Source Implementation Activities

1. Define BAU readiness criteria.
2. Assess operational capabilities.
3. Close operational readiness gaps.
4. Validate support readiness.
5. Obtain BAU acceptance.

## Implementation Tasks

### L10-14.03-001 — Define BAU Readiness Criteria

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P08 |
| Primary Role | Service Manager |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define measurable criteria for support, monitoring, documentation, training, ownership and service acceptance.

**Dependencies**

- Operating model
- Support model

**Deliverable**

BAU readiness checklist.

**Acceptance Criteria**

Criteria are approved by customer stakeholders.

### L10-14.03-002 — Execute BAU Readiness Assessment

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P09 |
| Primary Role | Service Manager |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Assess the project against the approved BAU readiness criteria.

**Dependencies**

- L10-14.03-001
- Operational documentation
- Training
- Monitoring
- Support model

**Deliverable**

BAU readiness assessment.

**Acceptance Criteria**

All critical readiness items are complete or have approved remediation.

### L10-14.03-003 — Approve BAU Readiness

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P10 |
| Primary Role | Service Manager |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Obtain formal approval that the service is ready for BAU.

**Dependencies**

- L10-14.03-002
- Cutover readiness

**Deliverable**

BAU readiness approval.

**Acceptance Criteria**

Customer formally approves operational readiness.

## Definition of Done

BAU readiness has been assessed, gaps resolved and formally approved.

---
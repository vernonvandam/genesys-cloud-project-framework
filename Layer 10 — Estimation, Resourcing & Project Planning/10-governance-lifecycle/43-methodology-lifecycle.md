# Layer 10 — 10.43 Methodology Lifecycle

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 10 — Governance & Lifecycle |
| Capability ID | 10.43 |
| Capability | Methodology Lifecycle |
| Task Catalogue ID | 10.43 |
| Primary Layer 1 Phases | P01, P12 |

## Capability Objective

Define and govern the lifecycle of the Genesys Cloud Deployment Methodology.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P01 | Establish methodology governance |
| P12 | Review methodology lifecycle and release state |

## Source Implementation Activities

1. Establish methodology ownership.
2. Define lifecycle states.
3. Review methodology.
4. Approve revisions.
5. Supersede obsolete versions.

## Implementation Tasks

### Activity 01 — Establish

#### L10-10.43-001 — Establish Methodology Ownership

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P01 |
| Primary Role | Methodology Owner |
| Customer Responsibility | NO |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Establish ownership and accountability for the methodology.

**Dependencies**

- Governance framework

**Deliverable**

Methodology ownership record.

**Acceptance Criteria**

Owner is identified.

### Activity 02 — Define

#### L10-10.43-002 — Define Methodology Lifecycle States

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P01 |
| Primary Role | Methodology Owner |
| Customer Responsibility | NO |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Define draft, review, active, superseded and archived states.

**Dependencies**

- L10-10.43-001

**Deliverable**

Lifecycle standard.

**Acceptance Criteria**

Lifecycle states are documented.

### Activity 03 — Review

#### L10-10.43-003 — Review Methodology Version

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P12 |
| Primary Role | Methodology Owner |
| Customer Responsibility | NO |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | NO |

**Description**

Review methodology performance, structure and currency.

**Dependencies**

- Lessons learned
- Calibration
- Platform evolution

**Deliverable**

Methodology review.

**Acceptance Criteria**

Required changes are identified.

### Activity 04 — Release

#### L10-10.43-004 — Release Methodology Version

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P12 |
| Primary Role | Methodology Owner |
| Customer Responsibility | NO |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | NO |

**Description**

Approve and release the next methodology version.

**Dependencies**

- L10-10.43-003
- Methodology change control

**Deliverable**

Released methodology version.

**Acceptance Criteria**

Current methodology version is clearly identified.

## Capability-Level Dependencies

- Repository governance
- Change control
- Continuous improvement

## Capability-Level Estimation Considerations

Methodology lifecycle effort depends on change frequency and framework scope.

## Definition of Done

Methodology versions have controlled lifecycle states and ownership.

---
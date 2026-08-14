# Layer 10 — 2.02.15 Audit & Administrative Traceability

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 02 — Identity & Access |
| Capability ID | 2.02.15 |
| Capability | Audit & Administrative Traceability |
| Task Catalogue ID | 02.15 |
| Primary Layer 1 Phases | P03, P04, P05, P08, P09, P10, P12 |

## Capability Objective

Establish sufficient administrative traceability to support security investigations, compliance, operational support and governance.

## Source Implementation Activities

1. Define audit requirements.
2. Identify administrative events requiring traceability.
3. Configure audit access and retention.
4. Validate audit records.
5. Define operational review.
6. Document audit procedures.

## Implementation Tasks

### Activity 01 — Define Requirements

#### L10-02.15-001 — Define Audit Requirements

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

Define audit, traceability, retention and monitoring requirements.

**Dependencies**

- Security requirements

**Deliverable**

Audit requirements.

**Acceptance Criteria**

Requirements are approved.

#### L10-02.15-002 — Define Administrative Audit Scope

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Identify administrative and security events that must be traceable.

**Dependencies**

- L10-02.15-001

**Deliverable**

Audit event catalogue.

**Acceptance Criteria**

Audit scope is approved.

### Activity 02 — Configure and Validate

#### L10-02.15-003 — Configure Audit Access

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Configure appropriate access to audit information while maintaining least privilege.

**Dependencies**

- L10-02.15-002

**Deliverable**

Audit access configuration.

**Acceptance Criteria**

Authorised users can access required audit information.

#### L10-02.15-004 — Validate Administrative Traceability

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 1.5h |
| Critical Path | YES |

**Description**

Perform representative administrative actions and verify that traceability requirements are satisfied.

**Dependencies**

- L10-02.15-003

**Deliverable**

Audit validation evidence.

**Acceptance Criteria**

Required administrative events can be traced.

#### L10-02.15-005 — Establish Audit Review Procedure

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P09 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Define operational ownership and review procedures for administrative audit information.

**Dependencies**

- L10-02.15-004

**Deliverable**

Audit review procedure.

**Acceptance Criteria**

BAU audit ownership is documented.
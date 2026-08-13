# Layer 10 — 2.01.02 Region & Data Residency

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 01 — Core Platform |
| Capability ID | 2.01.02 |
| Capability | Region & Data Residency |
| Task Catalogue ID | 01.02 |
| Primary Layer 1 Phases | P02, P03, P04, P05, P08, P10 |

## Capability Objective

Determine and implement the appropriate Genesys Cloud region and data residency strategy based on customer requirements, regulatory obligations, contractual commitments, and supported Genesys Cloud capabilities.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P02 | Discover geographic, regulatory and data residency requirements |
| P03 | Define target region and residency requirements |
| P04 | Architecture and compliance design |
| P05 | Establish target organisation in correct region |
| P08 | Validate regional configuration |
| P10 | Confirm production readiness |

## Source Implementation Activities

1. Identify geographic and residency requirements.
2. Assess regulatory and contractual constraints.
3. Select target Genesys Cloud region.
4. Confirm data residency implications.
5. Validate organisation region.
6. Document residency decisions and constraints.

## Implementation Tasks

### Activity 01 — Discover Requirements

#### L10-01.02-001 — Identify Customer Data Residency Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Business Analyst |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Capture countries, jurisdictions, regulatory requirements, contractual commitments, and internal policies governing where customer and contact-centre data may be processed or stored.

**Dependencies**

- Project initiation

**Deliverable**

Data residency requirements register.

**Acceptance Criteria**

Requirements are documented and approved by the customer.

---

#### L10-01.02-002 — Identify Regulatory and Compliance Constraints

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

Assess applicable privacy, regulatory, security, and contractual constraints that influence the Genesys Cloud region decision.

**Dependencies**

- L10-01.02-001

**Deliverable**

Regional compliance assessment.

**Acceptance Criteria**

Applicable constraints are identified and incorporated into the architecture.

### Activity 02 — Select Region

#### L10-01.02-003 — Evaluate Available Genesys Cloud Regions

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Evaluate supported Genesys Cloud regions against customer requirements and project constraints.

**Dependencies**

- L10-01.02-002

**Deliverable**

Region assessment.

**Acceptance Criteria**

Available options have been evaluated against documented requirements.

---

#### L10-01.02-004 — Select Target Region

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Solution Architect |
| Customer Responsibility | YES |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 0.5h |
| Critical Path | YES |

**Description**

Obtain formal approval of the target Genesys Cloud region.

**Dependencies**

- L10-01.02-003

**Deliverable**

Approved region decision.

**Acceptance Criteria**

Customer formally approves the selected region.

### Activity 03 — Implement and Validate

#### L10-01.02-005 — Confirm Organisation Region

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P05 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | NO |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 0.5h |
| Critical Path | YES |

**Description**

Confirm that the organisation has been provisioned in the approved region.

**Dependencies**

- L10-01.02-004
- L10-01.01-007

**Deliverable**

Region verification evidence.

**Acceptance Criteria**

Organisation region matches approved architecture.

---

#### L10-01.02-006 — Validate Data Residency Assumptions

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | YES |

**Description**

Validate that the implemented solution remains consistent with approved data residency requirements and documented architectural assumptions.

**Dependencies**

- L10-01.02-005

**Deliverable**

Data residency validation record.

**Acceptance Criteria**

No unresolved residency conflicts remain.

---

#### L10-01.02-007 — Document Regional and Residency Constraints

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P10 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | MULTI |
| Automation | MANUAL |
| Baseline Effort | 1.0h |
| Critical Path | NO |

**Description**

Document regional architecture, residency constraints, and operational implications for future administrators.

**Dependencies**

- L10-01.02-006

**Deliverable**

Regional and residency documentation.

**Acceptance Criteria**

Documentation is approved and included in the solution handover.

## Capability-Level Dependencies

- Organisation strategy
- Security requirements
- Privacy requirements
- Regulatory requirements
- Customer legal and compliance review

## Capability-Level Estimation Considerations

Effort increases with:

- multiple jurisdictions
- multiple organisations
- complex regulatory requirements
- legal review
- cross-region integration requirements
- complex data movement requirements

## Definition of Done

The target region is approved, implemented, validated, documented, and confirmed to satisfy the customer's applicable residency requirements.
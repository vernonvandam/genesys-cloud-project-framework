# Layer 10 — 2.11.02 Security Requirements

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 11 — Security, Compliance & Governance |
| Capability ID | 2.11.02 |
| Capability | Security Requirements |
| Task Catalogue ID | 11.02 |
| Primary Layer 1 Phases | P02, P03, P04, P08, P10 |

## Capability Objective

Capture, classify, trace and obtain approval for security requirements applicable to the Genesys Cloud solution.

## Layer 1 Mapping

| Phase | Application |
|---|---|
| P02 | Discover security requirements |
| P03 | Document requirements |
| P04 | Trace requirements into design |
| P08 | Validate requirements |
| P10 | Confirm production compliance |

## Source Implementation Activities

1. Discover security requirements.
2. Classify requirements.
3. Map requirements to controls.
4. Obtain approval.

## Implementation Tasks

### Activity 01 — Define Security Requirements

#### L10-11.02-001 — Discover Security Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Gather enterprise, customer, regulatory and platform security requirements.

**Dependencies**

- Security stakeholder identification

**Deliverable**

Security requirements catalogue.

**Acceptance Criteria**

Applicable requirements are documented and agreed.

---

#### L10-11.02-002 — Map Requirements to Security Controls

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Map each security requirement to a Genesys Cloud configuration, process or compensating control.

**Dependencies**

- L10-11.02-001
- Security architecture

**Deliverable**

Security control matrix.

**Acceptance Criteria**

All mandatory requirements have an identified control or approved exception.

## Capability-Level Dependencies

- Security strategy
- Enterprise policies
- Regulatory requirements

## Capability-Level Estimation Considerations

Effort increases with regulatory complexity, number of business units and number of security controls.

## Definition of Done

Security requirements are approved, traceable and mapped to implementation or governance controls.
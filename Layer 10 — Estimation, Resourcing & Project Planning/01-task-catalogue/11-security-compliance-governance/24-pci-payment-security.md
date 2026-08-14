FILE: Layer 10 — Estimation, Resourcing & Project Planning/01-task-catalogue/11-security-compliance-governance/24-pci-payment-security.md

# Layer 10 — 2.11.24 PCI & Payment Security

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 11 — Security, Compliance & Governance |
| Capability ID | 2.11.24 |
| Capability | PCI & Payment Security |
| Task Catalogue ID | 11.24 |
| Primary Layer 1 Phases | P02, P03, P04, P06, P08, P10 |

## Capability Objective

Assess payment-data handling and implement applicable PCI-related controls.

## Implementation Tasks

### Activity 01 — Assess PCI Requirements

#### L10-11.24-001 — Determine PCI Applicability

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P02 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Determine whether the solution processes, transmits or interacts with payment information requiring PCI controls.

**Dependencies**

- Data classification
- Solution design

**Deliverable**

PCI applicability assessment.

**Acceptance Criteria**

PCI applicability is documented and approved.

---

#### L10-11.24-002 — Validate Payment Security Controls

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P08 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | CONDITIONAL |

**Description**

Validate applicable payment-data controls and evidence.

**Dependencies**

- L10-11.24-001
- Payment solution configuration

**Deliverable**

PCI control validation.

**Acceptance Criteria**

Applicable controls are validated and evidence retained.
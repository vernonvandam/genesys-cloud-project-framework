# Layer 10 — 2.11.20 Encryption

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 11 — Security, Compliance & Governance |
| Capability ID | 2.11.20 |
| Capability | Encryption |
| Task Catalogue ID | 11.20 |
| Primary Layer 1 Phases | P03, P04, P07, P08, P10 |

## Capability Objective

Confirm encryption requirements for data at rest and in transit and identify any customer-specific controls.

## Implementation Tasks

### Activity 01 — Validate Encryption

#### L10-11.20-001 — Define Encryption Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Document encryption requirements and applicable Genesys Cloud and integration controls.

**Dependencies**

- Data classification
- Security requirements

**Deliverable**

Encryption requirements.

**Acceptance Criteria**

Encryption requirements are approved.

---

#### L10-11.20-002 — Validate Encryption Controls

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate encryption controls for applicable data flows and storage locations.

**Dependencies**

- L10-11.20-001

**Deliverable**

Encryption validation evidence.

**Acceptance Criteria**

Required encryption controls are confirmed.
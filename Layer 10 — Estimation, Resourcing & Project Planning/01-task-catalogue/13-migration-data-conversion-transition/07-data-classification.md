# Layer 10 — 2.13.07 Data Classification

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 13 — Migration, Data Conversion & Transition |
| Capability ID | 2.13.07 |
| Capability | Data Classification |
| Task Catalogue ID | 13.07 |
| Primary Layer 1 Phases | P02, P03, P04 |

## Capability Objective

Classify migration data according to sensitivity, business criticality, regulatory requirements and handling restrictions.

## Source Implementation Activities

1. Identify sensitive datasets.
2. Classify data.
3. Define handling requirements.

## Implementation Tasks

### L10-13.07-001 — Identify Sensitive Data

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P02 |
| Primary Role | Security Specialist |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Identify personal, sensitive, confidential and regulated data in migration scope.

**Dependencies**

- Data discovery

**Deliverable**

Sensitive-data inventory.

**Acceptance Criteria**

Sensitive datasets are identified.

### L10-13.07-002 — Apply Data Classification

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P03 |
| Primary Role | Security Specialist |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Apply the customer's approved data classification model to migration datasets.

**Dependencies**

- L10-13.07-001

**Deliverable**

Data classification register.

**Acceptance Criteria**

All material datasets have an approved classification.

### L10-13.07-003 — Define Data Handling Controls

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Security Specialist |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define handling, transfer, access and storage controls based on classification.

**Dependencies**

- L10-13.07-002

**Deliverable**

Data handling requirements.

**Acceptance Criteria**

Handling requirements are approved by security and data owners.

## Definition of Done

Migration data is classified and appropriate controls are defined.

---

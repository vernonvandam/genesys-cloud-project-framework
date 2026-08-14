# Layer 10 — 2.11.11 Permission Policies

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 11 — Security, Compliance & Governance |
| Capability ID | 2.11.11 |
| Capability | Permission Policies |
| Task Catalogue ID | 11.11 |
| Primary Layer 1 Phases | P04, P05, P06, P08 |

## Capability Objective

Define and implement permission policies controlling access to Genesys Cloud resources.

## Implementation Tasks

### Activity 01 — Define Policies

#### L10-11.11-001 — Define Permission Policies

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Genesys Cloud Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define policy requirements and the resources to which policies apply.

**Dependencies**

- Permission matrix
- Division model

**Deliverable**

Permission policy design.

**Acceptance Criteria**

Policies are approved.

---

#### L10-11.11-002 — Configure and Validate Permission Policies

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P08 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | HYBRID |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Implement and test permission policies.

**Dependencies**

- L10-11.11-001

**Deliverable**

Policy configuration and test evidence.

**Acceptance Criteria**

Policy behaviour matches the approved design.
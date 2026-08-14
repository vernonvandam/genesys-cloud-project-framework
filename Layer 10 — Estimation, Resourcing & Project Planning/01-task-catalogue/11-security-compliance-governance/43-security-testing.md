FILE: Layer 10 — Estimation, Resourcing & Project Planning/01-task-catalogue/11-security-compliance-governance/43-security-testing.md

# Layer 10 — 2.11.43 Security Testing

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 11 — Security, Compliance & Governance |
| Capability ID | 2.11.43 |
| Capability | Security Testing |
| Task Catalogue ID | 11.43 |
| Primary Layer 1 Phases | P04, P06, P08, P10 |

## Capability Objective

Plan and execute security testing of the Genesys Cloud solution.

## Implementation Tasks

### Activity 01 — Execute Security Testing

#### L10-11.43-001 — Develop Security Test Plan

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P08 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Define security test scenarios covering identity, access, data, integrations and administration.

**Dependencies**

- Security architecture
- Security requirements

**Deliverable**

Security test plan.

**Acceptance Criteria**

Security test scope and expected outcomes are approved.

---

#### L10-11.43-002 — Execute Security Tests

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | HYBRID |
| Baseline Effort | 4.0h |
| Critical Path | YES |

**Description**

Execute security tests and document findings.

**Dependencies**

- L10-11.43-001

**Deliverable**

Security test results.

**Acceptance Criteria**

Critical security defects are resolved or formally accepted.
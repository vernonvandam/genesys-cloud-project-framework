# Layer 10 — 2.06.23 Digital Attachments

## Capability Objective

Define and control attachment handling across supported digital channels.

## Implementation Tasks

### L10-06.23-001 — Define Attachment Policy

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P03 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Define supported file types, size limits, security requirements, retention and handling rules.

**Dependencies**

- Security requirements

**Deliverable**

Attachment policy.

**Acceptance Criteria**

Policy is approved.

### L10-06.23-002 — Configure Attachment Handling

| Attribute | Value |
|---|---|
| Task Type | CONDITIONAL |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Configure supported attachment behaviour and associated controls.

**Dependencies**

- L10-06.23-001

**Deliverable**

Attachment configuration.

**Acceptance Criteria**

Approved attachment types are handled correctly.

### L10-06.23-003 — Test Attachment Security

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P08 |
| Primary Role | Security Architect |
| Customer Responsibility | JOINT |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | CONDITIONAL |

**Description**

Test allowed, disallowed, oversized and security-sensitive attachments.

**Dependencies**

- L10-06.23-002

**Deliverable**

Attachment security evidence.

**Acceptance Criteria**

Attachment controls pass approved scenarios.

## Definition of Done

Attachment behaviour and security controls are approved and validated.

---

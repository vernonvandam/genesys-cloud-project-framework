# Layer 10 — 2.06.04 Web Messenger Deployment

## Capability Reference

| Attribute | Value |
|---|---|
| Layer | Layer 10 — Estimation, Resourcing & Project Planning |
| Domain | 06 — Digital |
| Capability ID | 2.06.04 |
| Capability | Web Messenger Deployment |
| Task Catalogue ID | 06.04 |
| Primary Layer 1 Phases | P04, P05, P06, P07, P08, P10, P11 |

## Capability Objective

Deploy the web messenger experience into the customer's digital properties and validate the end-to-end customer journey.

## Source Implementation Activities

1. Define deployment requirements.
2. Configure deployment.
3. Integrate web properties.
4. Validate deployment.
5. Activate and monitor.

## Implementation Tasks

### L10-06.04-001 — Define Web Messenger Deployment Requirements

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P04 |
| Primary Role | Solution Architect |
| Customer Responsibility | JOINT |
| Environment | DESIGN |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Define websites, domains, deployment method, security, branding and environment requirements.

**Dependencies**

- Digital architecture

**Deliverable**

Deployment specification.

**Acceptance Criteria**

Deployment approach is approved.

### L10-06.04-002 — Configure Web Messenger Deployment

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P06 |
| Primary Role | Genesys Cloud Engineer |
| Customer Responsibility | JOINT |
| Environment | DEV |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Configure the Genesys Cloud web messenger deployment.

**Dependencies**

- L10-06.04-001

**Deliverable**

Configured deployment.

**Acceptance Criteria**

Deployment is available for integration testing.

### L10-06.04-003 — Deploy Web Messenger to Customer Property

| Attribute | Value |
|---|---|
| Task Type | REQUIRED |
| Layer 1 Phase | P07 |
| Primary Role | Customer Web Engineer |
| Customer Responsibility | YES |
| Environment | TEST |
| Automation | MANUAL |
| Baseline Effort | 3.0h |
| Critical Path | YES |

**Description**

Deploy the approved messenger implementation to the customer's test property.

**Dependencies**

- L10-06.04-002

**Deliverable**

Test web messenger deployment.

**Acceptance Criteria**

Messenger loads correctly on supported customer properties.

### L10-06.04-004 — Validate Production Deployment

| Attribute | Value |
|---|---|
| Task Type | VALIDATION |
| Layer 1 Phase | P10 |
| Primary Role | Test Lead |
| Customer Responsibility | JOINT |
| Environment | PROD |
| Automation | MANUAL |
| Baseline Effort | 2.0h |
| Critical Path | YES |

**Description**

Validate production deployment, customer entry, routing and agent handling.

**Dependencies**

- L10-06.04-003
- UAT approval

**Deliverable**

Production deployment validation.

**Acceptance Criteria**

End-to-end production customer journey passes.

## Definition of Done

Web Messenger is deployed, validated and operational on approved customer properties.

---

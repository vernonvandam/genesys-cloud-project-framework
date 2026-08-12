# Layer 2.11 — Security, Compliance & Governance

## Capability Domain README

**Methodology:** Genesys Cloud Deployment Methodology  
**Layer:** 2 — Genesys Cloud Capability Catalogue  
**Domain:** 11 — Security, Compliance & Governance  
**Status:** Baseline Capability Catalogue  
**Purpose:** Define the security, privacy, compliance, governance, audit and operational-control capabilities required to deploy and operate Genesys Cloud securely within an enterprise environment.

---

# 1. Purpose

The Security, Compliance & Governance domain defines the controls required to protect the Genesys Cloud environment, customer data, employee data, recordings, integrations, identities and operational configuration.

This domain covers:

- Security architecture
- Security requirements
- Information security governance
- Identity security
- Authentication
- SSO
- MFA
- Role-based access control
- Permissions
- Permission policies
- Divisions
- Data segregation
- Least privilege
- Privileged access
- Service accounts
- API clients
- OAuth
- Secrets
- Credential management
- Integration security
- Data protection
- Encryption
- Data residency
- Privacy
- PII
- Sensitive data
- PCI considerations
- Recording security
- Retention
- Data deletion
- Audit logging
- Security monitoring
- Threat detection
- Incident response
- Vulnerability management
- Change governance
- Configuration governance
- Compliance requirements
- Regulatory requirements
- Customer security policies
- Audit evidence
- Access reviews
- Security reviews
- Third-party risk
- Business continuity
- Disaster recovery considerations
- Operational governance
- Security testing
- Compliance testing
- Production security validation
- Security handover

---

# 2. Scope

```text
11 Security, Compliance & Governance
│
├── 01 Security Strategy
├── 02 Security Requirements
├── 03 Security Architecture
├── 04 Security Governance
├── 05 Identity Security
├── 06 Authentication
├── 07 SSO
├── 08 MFA
├── 09 Role-Based Access Control
├── 10 Permissions
├── 11 Permission Policies
├── 12 Divisions & Data Segregation
├── 13 Least Privilege
├── 14 Privileged Access
├── 15 Service Accounts
├── 16 API Clients & OAuth
├── 17 Secrets & Credential Management
├── 18 Integration Security
├── 19 Data Protection
├── 20 Encryption
├── 21 Data Residency
├── 22 Privacy
├── 23 PII & Sensitive Data
├── 24 PCI & Payment Security
├── 25 Recording Security
├── 26 Retention & Deletion
├── 27 Audit Logging
├── 28 Security Monitoring
├── 29 Threat Detection
├── 30 Security Incident Response
├── 31 Vulnerability Management
├── 32 Security Change Management
├── 33 Configuration Governance
├── 34 Compliance Requirements
├── 35 Regulatory Controls
├── 36 Customer Security Policies
├── 37 Audit Evidence
├── 38 Access Reviews
├── 39 Security Reviews
├── 40 Third-Party Risk
├── 41 Business Continuity
├── 42 Disaster Recovery
├── 43 Security Testing
├── 44 Compliance Testing
├── 45 Production Security Validation
├── 46 Operational Security Governance
└── 47 Security Handover
```

---

# 3. Capability Classification

| Capability | Default Classification |
|---|---|
| Security Strategy | Required |
| Security Requirements | Required |
| Security Architecture | Required |
| Security Governance | Required |
| Identity Security | Required |
| Authentication | Required |
| SSO | Required |
| MFA | Required |
| Role-Based Access Control | Required |
| Permissions | Required |
| Permission Policies | Required |
| Divisions & Data Segregation | Required |
| Least Privilege | Required |
| Privileged Access | Required |
| Service Accounts | Conditional |
| API Clients & OAuth | Conditional |
| Secrets & Credential Management | Required |
| Integration Security | Required |
| Data Protection | Required |
| Encryption | Required |
| Data Residency | Required |
| Privacy | Required |
| PII & Sensitive Data | Required |
| PCI & Payment Security | Conditional |
| Recording Security | Required |
| Retention & Deletion | Required |
| Audit Logging | Required |
| Security Monitoring | Required |
| Threat Detection | Conditional |
| Security Incident Response | Required |
| Vulnerability Management | Required |
| Security Change Management | Required |
| Configuration Governance | Required |
| Compliance Requirements | Required |
| Regulatory Controls | Conditional |
| Customer Security Policies | Required |
| Audit Evidence | Required |
| Access Reviews | Required |
| Security Reviews | Required |
| Third-Party Risk | Conditional |
| Business Continuity | Required |
| Disaster Recovery | Required |
| Security Testing | Required |
| Compliance Testing | Required |
| Production Security Validation | Required |
| Operational Security Governance | Required |
| Security Handover | Required |

---

# 4. Security Architecture

```text
                    Enterprise Security Governance
                              │
                              ▼
                    Genesys Cloud Security
                              │
        ┌─────────────────────┼─────────────────────┐
        │                     │                     │
        ▼                     ▼                     ▼
 Identity & Access       Data Protection       Platform Security
        │                     │                     │
        ▼                     ▼                     ▼
 Authentication          Encryption             Configuration
 SSO / MFA               Privacy                Change Control
 RBAC                    Retention              Monitoring
 Permissions             PII                    Audit
 Divisions               Recording              Incident Response
        │                     │                     │
        └─────────────────────┼─────────────────────┘
                              ▼
                       Security Operations
                              │
                              ▼
                       Governance / Audit
```

---

# 5. Security Design Principles

1. Security must be designed before production configuration.
2. Least privilege is the default access principle.
3. Access must be based on business responsibility.
4. Privileged access must be tightly controlled.
5. Administrative access must be auditable.
6. SSO should be used where supported and appropriate.
7. MFA should be enforced according to enterprise policy.
8. Service accounts must have explicit ownership.
9. API credentials must never be hard-coded.
10. Secrets must be stored using approved enterprise mechanisms.
11. Data must be classified before security controls are selected.
12. PII must be protected according to applicable privacy requirements.
13. Recording security must align with the broader data-security model.
14. Retention must be explicitly defined.
15. Data deletion must be governed.
16. Security configuration must be change controlled.
17. Security events must be auditable.
18. Security testing must precede production.
19. Compliance requirements must be traceable to configuration and evidence.
20. Security ownership must transfer explicitly to BAU operations.
21. Customer-specific policies override generic assumptions where stricter.
22. Security controls must be periodically reviewed.
23. Security exceptions must be documented and approved.
24. Security evidence must be retained according to governance requirements.

---

# 6. Security Lifecycle

```text
Security Strategy
      │
      ▼
Security Requirements
      │
      ▼
Security Architecture
      │
      ▼
Security Controls
      │
      ▼
Configuration
      │
      ▼
Security Testing
      │
      ▼
Compliance Validation
      │
      ▼
Production Approval
      │
      ▼
Operational Monitoring
      │
      ▼
Periodic Review
      │
      ▼
Continuous Improvement
```

---

# 7. Standard Security Artefacts

The project may require:

- Security strategy
- Security requirements catalogue
- Security architecture
- Security control matrix
- IAM design
- Authentication design
- SSO design
- MFA design
- RBAC matrix
- Permission matrix
- Division model
- Data segregation design
- Privileged access model
- Service-account register
- API-client register
- OAuth design
- Secrets management design
- Integration security design
- Data classification matrix
- Privacy assessment
- PII assessment
- PCI assessment
- Recording security assessment
- Retention matrix
- Data deletion procedure
- Audit logging design
- Security monitoring design
- Incident response procedure
- Vulnerability management procedure
- Security change process
- Compliance matrix
- Regulatory control matrix
- Security exception register
- Audit evidence register
- Access review procedure
- Security review checklist
- Third-party risk assessment
- Business continuity assessment
- Disaster recovery assessment
- Security test plan
- Compliance test plan
- Production security checklist
- Security operations runbook
- Security handover document

---

# 8. Layer 1 Mapping

| Layer 1 Phase | Security Activities |
|---|---|
| Phase 1 — Initiation | Identify security stakeholders |
| Phase 2 — Discovery | Discover enterprise security requirements |
| Phase 3 — Requirements | Define security and compliance requirements |
| Phase 4 — Architecture | Design security architecture |
| Phase 5 — Platform Foundation | Establish IAM and security foundations |
| Phase 6 — Solution Build | Implement security controls |
| Phase 7 — Integration & Migration | Secure integrations and migration processes |
| Phase 8 — Testing | Execute security and compliance testing |
| Phase 9 — Operational Readiness | Establish security operations |
| Phase 10 — Production Deployment | Validate production controls |
| Phase 11 — Hypercare | Monitor security |
| Phase 12 — BAU Handover | Transfer security ownership |

---

# 9. Standard Implementation Task Model

| Field | Requirement |
|---|---|
| Task ID | Unique identifier |
| Layer | Layer 2 |
| Domain | 11 |
| Capability | Security capability |
| Phase | Layer 1 phase |
| Workstream | Security / Compliance / Governance |
| Classification | Required / Conditional / Optional |
| Task | Atomic implementation task |
| Description | Detailed activity |
| Dependency | Predecessor |
| Role | Delivery owner |
| Customer Responsibility | Yes / No |
| Environment | DEV / TEST / UAT / PROD |
| Effort | Estimated hours |
| Duration | Elapsed duration |
| Deliverable | Task output |
| Acceptance Criteria | Completion requirement |
| Critical Path | Yes / No |

---

# 10. Major Dependencies

Security depends on:

- Core Platform
- Identity & Access
- Voice & Telephony
- ACD Routing
- Architect
- Digital
- Data & Integrations
- Analytics
- Quality Management
- WFM
- Testing
- Migration
- Operations

Security provides dependencies for every other domain.

---

# 11. Security Risks

| Risk | Impact | Mitigation |
|---|---|---|
| Excessive permissions | Critical | RBAC and least privilege |
| Privileged account compromise | Critical | MFA and privileged access controls |
| Incorrect division model | High | Formal design and testing |
| Unsecured API credentials | Critical | Secret management |
| Sensitive data exposure | Critical | Data classification and controls |
| Incorrect retention | High | Approved retention matrix |
| Missing audit logs | High | Audit validation |
| Security monitoring gaps | High | Monitoring design |
| Inadequate incident response | Critical | IR procedure |
| Unapproved configuration changes | High | Change governance |
| Compliance requirements missed | Critical | Compliance matrix |
| Insufficient security testing | High | Formal security test plan |
| Third-party integration risk | High | Security assessment |
| Incorrect production permissions | Critical | Production access review |
| Security ownership unclear | High | Operational handover |
| Security exceptions undocumented | High | Exception register |
| Weak service-account controls | High | Ownership and credential governance |
| Inadequate data deletion | High | Deletion controls and testing |

---

# 12. Definition of Done

The Security, Compliance & Governance domain is complete when:

- Security strategy is approved.
- Security requirements are documented.
- Security architecture is approved.
- Security governance is established.
- Authentication is configured.
- SSO is configured where required.
- MFA is configured where required.
- RBAC is implemented.
- Permissions are validated.
- Permission policies are validated.
- Divisions are validated.
- Least privilege is tested.
- Privileged access is controlled.
- Service accounts are documented.
- API clients are documented.
- OAuth is governed.
- Secrets are secured.
- Integrations are security assessed.
- Data protection requirements are met.
- Encryption requirements are validated.
- Data residency is approved.
- Privacy requirements are documented.
- PII controls are validated.
- PCI controls are validated where applicable.
- Recording security is validated.
- Retention is approved.
- Deletion requirements are implemented.
- Audit logging is validated.
- Security monitoring is operational.
- Incident response is established.
- Vulnerability management is established.
- Change governance is operational.
- Compliance controls are mapped.
- Audit evidence is available.
- Access review is completed.
- Security review is completed.
- Business continuity is assessed.
- Disaster recovery is assessed.
- Security testing is complete.
- Compliance testing is complete.
- Production security validation is complete.
- Operational security ownership is established.
- Security handover is accepted.

---

# 13. Domain Gate

```text
SECURITY STRATEGY APPROVED
            +
SECURITY ARCHITECTURE APPROVED
            +
IAM / RBAC APPROVED
            +
DATA PROTECTION APPROVED
            +
PRIVACY / COMPLIANCE APPROVED
            +
SECURITY CONTROLS IMPLEMENTED
            +
SECURITY TESTING PASSED
            +
COMPLIANCE TESTING PASSED
            +
PRODUCTION SECURITY VALIDATED
            +
OPERATIONS READY
            ↓
SECURITY READY FOR PRODUCTION
```

---

# 14. Domain File Catalogue

```text
11-Security-Compliance-Governance/
│
├── README.md
├── 01-Security-Strategy.md
├── 02-Security-Requirements.md
├── 03-Security-Architecture.md
├── 04-Security-Governance.md
├── 05-Identity-Security.md
├── 06-Authentication.md
├── 07-SSO.md
├── 08-MFA.md
├── 09-Role-Based-Access-Control.md
├── 10-Permissions.md
├── 11-Permission-Policies.md
├── 12-Divisions-Data-Segregation.md
├── 13-Least-Privilege.md
├── 14-Privileged-Access.md
├── 15-Service-Accounts.md
├── 16-API-Clients-OAuth.md
├── 17-Secrets-Credential-Management.md
├── 18-Integration-Security.md
├── 19-Data-Protection.md
├── 20-Encryption.md
├── 21-Data-Residency.md
├── 22-Privacy.md
├── 23-PII-Sensitive-Data.md
├── 24-PCI-Payment-Security.md
├── 25-Recording-Security.md
├── 26-Retention-Deletion.md
├── 27-Audit-Logging.md
├── 28-Security-Monitoring.md
├── 29-Threat-Detection.md
├── 30-Security-Incident-Response.md
├── 31-Vulnerability-Management.md
├── 32-Security-Change-Management.md
├── 33-Configuration-Governance.md
├── 34-Compliance-Requirements.md
├── 35-Regulatory-Controls.md
├── 36-Customer-Security-Policies.md
├── 37-Audit-Evidence.md
├── 38-Access-Reviews.md
├── 39-Security-Reviews.md
├── 40-Third-Party-Risk.md
├── 41-Business-Continuity.md
├── 42-Disaster-Recovery.md
├── 43-Security-Testing.md
├── 44-Compliance-Testing.md
├── 45-Production-Security-Validation.md
├── 46-Operational-Security-Governance.md
└── 47-Security-Handover.md
```

---

# 15. Capability Catalogue

# Layer 2.11.01 — Security Strategy

## Purpose

Define the overall security objectives and control strategy for the Genesys Cloud deployment.

## Classification

**Required**

## Activities

1. Identify security stakeholders.
2. Identify enterprise security standards.
3. Identify customer security requirements.
4. Identify regulatory requirements.
5. Define security objectives.
6. Define security principles.
7. Define control ownership.
8. Define security governance.
9. Define security assurance requirements.
10. Obtain approval.

## Deliverables

- Security strategy
- Security principles
- Security control ownership model

## Acceptance Criteria

Security strategy is approved by the appropriate security stakeholders.

## Definition of Done

Security strategy is formally approved.

---

# Layer 2.11.02 — Security Requirements

## Purpose

Capture functional and non-functional security requirements.

## Classification

**Required**

## Activities

- Conduct security workshops.
- Identify authentication requirements.
- Identify authorisation requirements.
- Identify data requirements.
- Identify audit requirements.
- Identify privacy requirements.
- Identify compliance requirements.
- Identify monitoring requirements.
- Prioritise requirements.
- Obtain approval.

## Definition of Done

Security requirements are complete, approved and traceable.

---

# Layer 2.11.03 — Security Architecture

## Purpose

Define the security architecture for the Genesys Cloud solution.

## Classification

**Required**

## Activities

- Define trust boundaries.
- Define identity architecture.
- Define authentication.
- Define authorisation.
- Define data protection.
- Define integration security.
- Define audit.
- Define monitoring.
- Define incident response.
- Review architecture with security stakeholders.
- Obtain approval.

## Definition of Done

Security architecture is approved.

---

# Layer 2.11.04 — Security Governance

## Purpose

Establish ownership, decision rights and review mechanisms.

## Classification

**Required**

## Activities

- Define security owners.
- Define compliance owners.
- Define platform owners.
- Define operational owners.
- Define review cadence.
- Define exception process.
- Define escalation.
- Define security change process.
- Define audit responsibilities.

## Definition of Done

Security governance model is operational.

---

# Layer 2.11.05 — Identity Security

## Purpose

Secure the identities used to access and administer Genesys Cloud.

## Classification

**Required**

## Activities

- Identify identity sources.
- Identify user lifecycle.
- Identify administrator identities.
- Define identity ownership.
- Define account provisioning.
- Define account deprovisioning.
- Define identity review.
- Configure controls.
- Validate.

## Definition of Done

Identity lifecycle and security controls are approved.

---

# Layer 2.11.06 — Authentication

## Purpose

Define how users authenticate to Genesys Cloud.

## Classification

**Required**

## Activities

- Identify authentication sources.
- Define authentication methods.
- Define password requirements where applicable.
- Define authentication policies.
- Define account recovery.
- Configure.
- Test.
- Validate.

## Definition of Done

Authentication meets enterprise security requirements.

---

# Layer 2.11.07 — SSO

## Purpose

Integrate Genesys Cloud with enterprise identity federation.

## Classification

**Required**

## Activities

- Identify IdP.
- Confirm federation requirements.
- Configure SSO.
- Configure claims.
- Configure user attributes.
- Configure authentication policies.
- Test login.
- Test logout.
- Test failure handling.
- Validate user lifecycle.

## Definition of Done

SSO is operational and tested.

---

# Layer 2.11.08 — MFA

## Purpose

Apply multi-factor authentication according to security requirements.

## Classification

**Required**

## Activities

- Confirm MFA policy.
- Identify privileged users.
- Identify general users.
- Define exceptions.
- Configure MFA through approved identity controls.
- Test.
- Validate.

## Definition of Done

MFA requirements are implemented.

---

# Layer 2.11.09 — Role-Based Access Control

## Purpose

Define and implement role-based access to Genesys Cloud capabilities.

## Classification

**Required**

## Activities

- Identify personas.
- Identify responsibilities.
- Map permissions.
- Define roles.
- Define custom roles where required.
- Remove unnecessary permissions.
- Test.
- Obtain security approval.

## Definition of Done

RBAC model is approved and validated.

---

# Layer 2.11.10 — Permissions

## Purpose

Define granular permissions required by each business role.

## Classification

**Required**

## Activities

- Inventory required capabilities.
- Map capabilities to permissions.
- Define permission sets.
- Identify dangerous permissions.
- Review administrator access.
- Test access boundaries.

## Definition of Done

Permissions are documented and validated.

---

# Layer 2.11.11 — Permission Policies

## Purpose

Apply contextual restrictions to permissions where supported.

## Classification

**Required**

## Activities

- Identify contextual restrictions.
- Define policy requirements.
- Map users and roles.
- Configure policies.
- Test allowed access.
- Test denied access.

## Definition of Done

Permission policies enforce approved access boundaries.

---

# Layer 2.11.12 — Divisions & Data Segregation

## Purpose

Use divisions and related controls to establish appropriate administrative and data boundaries.

## Classification

**Required**

## Activities

- Identify business boundaries.
- Identify regional boundaries.
- Identify operational boundaries.
- Design division model.
- Map objects.
- Map roles.
- Configure.
- Test cross-division access.
- Validate.

## Definition of Done

Division model is approved and security tested.

---

# Layer 2.11.13 — Least Privilege

## Purpose

Ensure users receive only the access required to perform their responsibilities.

## Classification

**Required**

## Activities

- Review permissions.
- Remove excessive permissions.
- Identify administrative exceptions.
- Validate role necessity.
- Test access.
- Perform access review.

## Definition of Done

Least-privilege review is complete.

---

# Layer 2.11.14 — Privileged Access

## Purpose

Protect administrative and high-impact access.

## Classification

**Required**

## Activities

- Identify privileged roles.
- Identify privileged users.
- Define MFA requirements.
- Define administrative access process.
- Define privileged account review.
- Define logging.
- Define emergency access.
- Test.

## Definition of Done

Privileged access is controlled and auditable.

---

# Layer 2.11.15 — Service Accounts

## Purpose

Govern non-human identities used by applications and integrations.

## Classification

**Conditional**

## Activities

- Identify service accounts.
- Identify owners.
- Define purpose.
- Define permissions.
- Define credential lifecycle.
- Define rotation.
- Define monitoring.
- Document.

## Definition of Done

All service accounts are documented and governed.

---

# Layer 2.11.16 — API Clients & OAuth

## Purpose

Secure API-based access to Genesys Cloud.

## Classification

**Conditional**

## Activities

- Identify API integrations.
- Identify OAuth clients.
- Define grant types.
- Define scopes.
- Define ownership.
- Define credential lifecycle.
- Configure.
- Test.
- Document.

## Definition of Done

API clients use approved authentication and authorisation controls.

---

# Layer 2.11.17 — Secrets & Credential Management

## Purpose

Prevent exposure and uncontrolled use of sensitive credentials.

## Classification

**Required**

## Activities

- Identify secrets.
- Identify credentials.
- Define storage mechanism.
- Define access.
- Define rotation.
- Define revocation.
- Remove credentials from source code.
- Test rotation.

## Definition of Done

Secrets are securely stored and governed.

---

# Layer 2.11.18 — Integration Security

## Purpose

Secure integrations between Genesys Cloud and enterprise or third-party systems.

## Classification

**Required**

## Activities

- Inventory integrations.
- Identify trust relationships.
- Identify data flows.
- Identify authentication.
- Identify authorisation.
- Identify encryption.
- Identify network controls.
- Identify logging.
- Conduct security review.

## Definition of Done

All production integrations pass security assessment.

---

# Layer 2.11.19 — Data Protection

## Purpose

Protect data throughout its lifecycle.

## Classification

**Required**

## Activities

- Identify data categories.
- Classify data.
- Define handling requirements.
- Define access.
- Define retention.
- Define deletion.
- Define export controls.
- Validate platform controls.

## Definition of Done

Data protection requirements are implemented.

---

# Layer 2.11.20 — Encryption

## Purpose

Validate encryption requirements for Genesys Cloud data.

## Classification

**Required**

## Activities

- Review data in transit.
- Review data at rest.
- Review integration encryption.
- Review customer security requirements.
- Document encryption controls.
- Identify exceptions.
- Obtain approval.

## Definition of Done

Encryption requirements are satisfied.

---

# Layer 2.11.21 — Data Residency

## Purpose

Ensure platform deployment and data handling meet approved residency requirements.

## Classification

**Required**

## Activities

- Identify residency requirements.
- Identify regulated data.
- Confirm Genesys Cloud region.
- Identify cross-border data flows.
- Review integrations.
- Review storage.
- Obtain legal/security approval.

## Definition of Done

Data residency is formally approved.

---

# Layer 2.11.22 — Privacy

## Purpose

Ensure privacy requirements are incorporated into the deployment.

## Classification

**Required**

## Activities

- Identify privacy obligations.
- Identify personal data.
- Identify processing purposes.
- Define access.
- Define retention.
- Define deletion.
- Define privacy notices.
- Conduct privacy assessment.

## Definition of Done

Privacy requirements are approved and traceable.

---

# Layer 2.11.23 — PII & Sensitive Data

## Purpose

Protect personally identifiable and sensitive information.

## Classification

**Required**

## Activities

- Identify PII.
- Identify sensitive categories.
- Identify interaction capture.
- Identify recording capture.
- Identify digital capture.
- Define masking/exclusion requirements.
- Define retention.
- Test.

## Definition of Done

PII controls are validated.

---

# Layer 2.11.24 — PCI & Payment Security

## Purpose

Address payment-card data and related security requirements.

## Classification

**Conditional**

## Activities

- Identify payment workflows.
- Identify PCI scope.
- Identify payment data.
- Identify recording risks.
- Define approved payment architecture.
- Define pause/resume requirements.
- Define compliance controls.
- Conduct security review.
- Test.

## Definition of Done

PCI requirements are approved and implemented where applicable.

---

# Layer 2.11.25 — Recording Security

## Purpose

Secure interaction recordings and associated metadata.

## Classification

**Required**

## Activities

- Identify recording users.
- Define access.
- Define retention.
- Define export.
- Define deletion.
- Define audit.
- Test playback access.
- Test unauthorised access.

## Definition of Done

Recording security controls are validated.

---

# Layer 2.11.26 — Retention & Deletion

## Purpose

Control how long data is retained and when it is deleted.

## Classification

**Required**

## Activities

- Identify retention requirements.
- Define retention by data type.
- Define legal holds.
- Define deletion.
- Define exceptions.
- Test.
- Document evidence.

## Definition of Done

Retention and deletion controls are operational.

---

# Layer 2.11.27 — Audit Logging

## Purpose

Ensure security-relevant activity is recorded and auditable.

## Classification

**Required**

## Activities

- Identify audit events.
- Identify administrative events.
- Identify access events.
- Identify configuration events.
- Define retention.
- Define monitoring.
- Define audit evidence.
- Validate logs.

## Definition of Done

Required audit events are available and usable.

---

# Layer 2.11.28 — Security Monitoring

## Purpose

Monitor security-relevant platform activity.

## Classification

**Required**

## Activities

- Identify monitoring requirements.
- Identify security events.
- Define monitoring ownership.
- Define alerting.
- Define escalation.
- Configure integrations where required.
- Test monitoring.

## Definition of Done

Security monitoring is operational.

---

# Layer 2.11.29 — Threat Detection

## Purpose

Detect suspicious or anomalous activity.

## Classification

**Conditional**

## Activities

- Identify threat scenarios.
- Define detection requirements.
- Identify data sources.
- Define alerting.
- Define escalation.
- Integrate with enterprise security tooling where applicable.
- Test.

## Definition of Done

Approved threat-detection controls are operational.

---

# Layer 2.11.30 — Security Incident Response

## Purpose

Define how security incidents involving Genesys Cloud are detected, contained and resolved.

## Classification

**Required**

## Activities

- Define incident categories.
- Define severity.
- Define escalation.
- Define security contacts.
- Define evidence collection.
- Define containment.
- Define recovery.
- Define communications.
- Conduct tabletop exercise.

## Definition of Done

Genesys Cloud is incorporated into the enterprise incident response process.

---

# Layer 2.11.31 — Vulnerability Management

## Purpose

Manage vulnerabilities affecting integrations, custom components and supporting infrastructure.

## Classification

**Required**

## Activities

- Identify customer-managed components.
- Identify APIs and applications.
- Identify integration components.
- Define scanning.
- Define patching.
- Define vulnerability ownership.
- Define remediation SLA.
- Document exceptions.

## Definition of Done

Vulnerability management responsibilities are defined.

---

# Layer 2.11.32 — Security Change Management

## Purpose

Ensure security-impacting changes are controlled.

## Classification

**Required**

## Activities

- Define security-impacting changes.
- Define approval process.
- Define risk assessment.
- Define testing.
- Define implementation.
- Define rollback.
- Define evidence.
- Integrate with enterprise change management.

## Definition of Done

Security changes follow an approved process.

---

# Layer 2.11.33 — Configuration Governance

## Purpose

Control changes to Genesys Cloud configuration.

## Classification

**Required**

## Activities

- Identify configuration items.
- Define ownership.
- Define baseline.
- Define change control.
- Define versioning.
- Define deployment process.
- Define drift detection.
- Define audit evidence.

## Definition of Done

Configuration governance is operational.

---

# Layer 2.11.34 — Compliance Requirements

## Purpose

Translate business, legal and regulatory requirements into Genesys Cloud controls.

## Classification

**Required**

## Activities

- Identify applicable standards.
- Identify customer policies.
- Identify regulatory requirements.
- Map requirements to controls.
- Identify evidence.
- Identify gaps.
- Obtain compliance approval.

## Definition of Done

Compliance requirements are documented and traceable.

---

# Layer 2.11.35 — Regulatory Controls

## Purpose

Implement controls required by applicable regulations.

## Classification

**Conditional**

## Activities

- Identify applicable regulations.
- Map requirements.
- Define controls.
- Define evidence.
- Implement controls.
- Test.
- Obtain compliance sign-off.

## Definition of Done

Applicable regulatory controls are implemented.

---

# Layer 2.11.36 — Customer Security Policies

## Purpose

Ensure deployment aligns with customer-specific security standards.

## Classification

**Required**

## Activities

- Obtain security policies.
- Identify applicable controls.
- Compare with Genesys capabilities.
- Identify gaps.
- Define compensating controls.
- Obtain customer security approval.

## Definition of Done

Customer security requirements are incorporated.

---

# Layer 2.11.37 — Audit Evidence

## Purpose

Maintain evidence demonstrating that required controls have been implemented.

## Classification

**Required**

## Activities

- Define evidence requirements.
- Identify evidence owners.
- Capture configuration evidence.
- Capture test evidence.
- Capture approvals.
- Capture access reviews.
- Maintain evidence repository.
- Define retention.

## Definition of Done

Required security evidence is complete and accessible.

---

# Layer 2.11.38 — Access Reviews

## Purpose

Periodically verify that users retain only required access.

## Classification

**Required**

## Activities

- Define review frequency.
- Identify access populations.
- Generate access reports.
- Review privileged access.
- Review administrative roles.
- Review service accounts.
- Remove inappropriate access.
- Document approval.

## Definition of Done

Initial access review is completed and BAU cadence established.

---

# Layer 2.11.39 — Security Reviews

## Purpose

Conduct formal security reviews throughout the project lifecycle.

## Classification

**Required**

## Review Points

- Architecture
- Configuration
- Integrations
- Security testing
- UAT
- Production readiness
- Post-go-live

## Definition of Done

Required security reviews are completed.

---

# Layer 2.11.40 — Third-Party Risk

## Purpose

Assess security risks associated with third-party systems and integrations.

## Classification

**Conditional**

## Activities

- Identify vendors.
- Identify data exchanged.
- Identify trust relationships.
- Review vendor security documentation.
- Assess authentication.
- Assess encryption.
- Assess privacy.
- Assess incident response.
- Record risks.

## Definition of Done

Third-party risks are assessed and accepted or mitigated.

---

# Layer 2.11.41 — Business Continuity

## Purpose

Determine how Genesys Cloud participates in the organisation's business continuity strategy.

## Classification

**Required**

## Activities

- Identify critical business processes.
- Define availability requirements.
- Identify dependencies.
- Identify operational workarounds.
- Define business continuity scenarios.
- Define recovery responsibilities.
- Conduct review.

## Definition of Done

Genesys Cloud continuity requirements are documented.

---

# Layer 2.11.42 — Disaster Recovery

## Purpose

Define recovery expectations for Genesys Cloud and customer-managed dependencies.

## Classification

**Required**

## Activities

- Identify critical services.
- Identify customer-managed dependencies.
- Identify integration dependencies.
- Define RTO requirements.
- Define RPO requirements where applicable.
- Define recovery responsibilities.
- Define failover procedures.
- Test customer-managed recovery processes.

## Definition of Done

Disaster recovery responsibilities are understood and documented.

---

# Layer 2.11.43 — Security Testing

## Purpose

Validate that security controls operate as designed.

## Classification

**Required**

## Activities

- Develop security test plan.
- Test authentication.
- Test SSO.
- Test MFA.
- Test RBAC.
- Test divisions.
- Test privileged access.
- Test API access.
- Test sensitive data.
- Test audit.
- Test monitoring.
- Record defects.
- Retest.

## Definition of Done

Critical security test cases pass.

---

# Layer 2.11.44 — Compliance Testing

## Purpose

Validate that required compliance controls are implemented.

## Classification

**Required**

## Activities

- Create compliance test matrix.
- Map requirements to tests.
- Execute tests.
- Capture evidence.
- Identify gaps.
- Remediate.
- Retest.
- Obtain approval.

## Definition of Done

Applicable compliance controls are tested and accepted.

---

# Layer 2.11.45 — Production Security Validation

## Purpose

Confirm that production configuration meets approved security requirements.

## Classification

**Required**

## Activities

- Review production roles.
- Review administrators.
- Review divisions.
- Review authentication.
- Review integrations.
- Review API clients.
- Review secrets.
- Review recording security.
- Review audit.
- Review monitoring.
- Review security exceptions.
- Obtain production security approval.

## Definition of Done

Production security checklist is approved.

---

# Layer 2.11.46 — Operational Security Governance

## Purpose

Transfer security controls into BAU operations.

## Classification

**Required**

## Activities

- Define operational security owner.
- Define access review cadence.
- Define security review cadence.
- Define incident process.
- Define change process.
- Define audit process.
- Define compliance review.
- Define security reporting.
- Define exception management.

## Definition of Done

Security operations are accepted by BAU owners.

---

# Layer 2.11.47 — Security Handover

## Purpose

Transfer security knowledge, controls, documentation and ownership to the operational organisation.

## Classification

**Required**

## Activities

- Complete security documentation.
- Transfer security architecture.
- Transfer IAM model.
- Transfer RBAC model.
- Transfer compliance matrix.
- Transfer audit evidence.
- Transfer security runbooks.
- Train operational teams.
- Complete access review.
- Obtain formal acceptance.

## Definition of Done

Security handover is formally accepted.

---

# 16. Implementation Task Decomposition Preview

The final implementation catalogue should decompose this domain into atomic tasks.

```text
SEC-011-001  Identify security stakeholders
SEC-011-002  Obtain enterprise security standards
SEC-011-003  Obtain customer security policies
SEC-011-004  Identify regulatory requirements
SEC-011-005  Define security objectives
SEC-011-006  Define security governance
SEC-011-007  Develop security strategy
SEC-011-008  Obtain security strategy approval
SEC-011-009  Conduct security requirements workshops
SEC-011-010  Document security requirements
SEC-011-011  Develop security control matrix
SEC-011-012  Develop security architecture
SEC-011-013  Review security architecture
SEC-011-014  Approve security architecture
SEC-011-015  Define identity architecture
SEC-011-016  Define authentication requirements
SEC-011-017  Configure SSO
SEC-011-018  Validate SSO
SEC-011-019  Define MFA requirements
SEC-011-020  Validate MFA
SEC-011-021  Identify Genesys personas
SEC-011-022  Develop RBAC matrix
SEC-011-023  Configure roles
SEC-011-024  Configure permissions
SEC-011-025  Validate permissions
SEC-011-026  Develop division model
SEC-011-027  Configure divisions
SEC-011-028  Test division segregation
SEC-011-029  Conduct least-privilege review
SEC-011-030  Identify privileged users
SEC-011-031  Configure privileged access
SEC-011-032  Develop service-account register
SEC-011-033  Develop API-client register
SEC-011-034  Review OAuth clients
SEC-011-035  Define OAuth scopes
SEC-011-036  Review credential storage
SEC-011-037  Implement secret management
SEC-011-038  Review integration security
SEC-011-039  Define data classification
SEC-011-040  Define data protection controls
SEC-011-041  Validate encryption requirements
SEC-011-042  Validate data residency
SEC-011-043  Conduct privacy assessment
SEC-011-044  Identify PII
SEC-011-045  Define sensitive-data controls
SEC-011-046  Conduct PCI assessment
SEC-011-047  Validate recording security
SEC-011-048  Define retention
SEC-011-049  Define deletion
SEC-011-050  Validate audit logging
SEC-011-051  Define security monitoring
SEC-011-052  Configure security monitoring
SEC-011-053  Define threat scenarios
SEC-011-054  Define incident response
SEC-011-055  Conduct incident-response tabletop
SEC-011-056  Define vulnerability management
SEC-011-057  Define security change management
SEC-011-058  Define configuration governance
SEC-011-059  Develop compliance matrix
SEC-011-060  Map regulatory controls
SEC-011-061  Review customer security policies
SEC-011-062  Develop audit evidence register
SEC-011-063  Conduct initial access review
SEC-011-064  Conduct security architecture review
SEC-011-065  Conduct integration security review
SEC-011-066  Conduct third-party risk assessment
SEC-011-067  Conduct business continuity assessment
SEC-011-068  Conduct disaster recovery assessment
SEC-011-069  Develop security test plan
SEC-011-070  Execute authentication testing
SEC-011-071  Execute SSO testing
SEC-011-072  Execute MFA testing
SEC-011-073  Execute RBAC testing
SEC-011-074  Execute division testing
SEC-011-075  Execute privileged-access testing
SEC-011-076  Execute API security testing
SEC-011-077  Execute sensitive-data testing
SEC-011-078  Execute audit testing
SEC-011-079  Execute security monitoring testing
SEC-011-080  Develop compliance test plan
SEC-011-081  Execute compliance testing
SEC-011-082  Remediate security defects
SEC-011-083  Retest security defects
SEC-011-084  Conduct production security review
SEC-011-085  Validate production roles
SEC-011-086  Validate production integrations
SEC-011-087  Validate production audit controls
SEC-011-088  Validate production monitoring
SEC-011-089  Approve production security
SEC-011-090  Establish security operations
SEC-011-091  Establish access-review cadence
SEC-011-092  Establish security-review cadence
SEC-011-093  Establish compliance-review cadence
SEC-011-094  Complete security handover
SEC-011-095  Obtain operational security acceptance
```

The final implementation workbook should further decompose these tasks where separate activities are required for:

- Requirements
- Architecture
- Design
- Configuration
- Development
- Security
- Compliance
- Data preparation
- Testing
- UAT
- Business approval
- Deployment
- Validation
- Documentation
- Training
- Operational handover

---

# 17. Cross-Domain Dependencies

| Dependency Domain | Security Dependency |
|---|---|
| 01 — Core Platform | Platform configuration and governance |
| 02 — Identity & Access | Identity, roles and permissions |
| 03 — Voice & Telephony | Voice security and telephony controls |
| 04 — ACD Routing | Queue and access boundaries |
| 05 — Architect | Secure flow and data handling |
| 06 — Digital | Digital-channel data protection |
| 07 — WFM | Workforce data security |
| 08 — Data & Integrations | API and integration security |
| 09 — Analytics & Reporting | Reporting access and data protection |
| 10 — Quality | Recording and evaluation security |
| 11 — Security | Current domain |
| 12 — Testing | Security validation |
| 13 — Migration | Data security during migration |
| 14 — Operations | Security operations |
| 15 — Optimisation | Ongoing security improvement |

---

# 18. Critical Cross-Domain Relationships

## Core Platform → Security

Core platform configuration establishes:

- Organisation
- Region
- Divisions
- Administrative structure
- Configuration baseline

---

## Identity & Access → Security

Identity and access controls establish:

- Authentication
- SSO
- MFA
- Roles
- Permissions
- User lifecycle
- Administrative access

---

## Voice & Telephony → Security

Telephony security includes:

- Recording
- Caller data
- Number ownership
- Telephony integrations
- Sensitive interactions

---

## Architect → Security

Architect flows may expose or process:

- PII
- Authentication information
- Payment information
- Customer identifiers
- External API data

Security controls must therefore be applied to flow design.

---

## Data & Integrations → Security

Every integration requires review of:

```text
Data
 ↓
Authentication
 ↓
Authorisation
 ↓
Transport
 ↓
Storage
 ↓
Logging
 ↓
Retention
```

---

## Quality → Security

Quality capabilities require security controls over:

- Recordings
- Evaluations
- Agent performance
- Sensitive data
- Reports
- Exports

---

# 19. IAM Design Sequence

```text
Business Personas
        ↓
Responsibilities
        ↓
Genesys Capabilities
        ↓
Permissions
        ↓
Roles
        ↓
Divisions
        ↓
Permission Policies
        ↓
User Assignment
        ↓
Least Privilege Review
        ↓
Security Testing
        ↓
Production Approval
```

---

# 20. Data Security Lifecycle

```text
Data Created
      ↓
Data Classified
      ↓
Data Transmitted
      ↓
Data Stored
      ↓
Data Accessed
      ↓
Data Processed
      ↓
Data Retained
      ↓
Data Archived / Preserved
      ↓
Data Deleted
```

Each stage must have an appropriate control.

---

# 21. Security Exception Model

Security exceptions should follow:

```text
Exception Identified
        ↓
Risk Assessment
        ↓
Business Justification
        ↓
Security Review
        ↓
Compensating Control
        ↓
Risk Owner Approval
        ↓
Expiry Date
        ↓
Periodic Review
```

No permanent exception should be created without explicit governance approval.

---

# 22. Security Testing Model

```text
Security Requirements
        ↓
Security Test Cases
        ↓
Environment Preparation
        ↓
Configuration
        ↓
Test Execution
        ↓
Evidence Collection
        ↓
Defect Management
        ↓
Remediation
        ↓
Retest
        ↓
Security Sign-off
```

---

# 23. Security Test Areas

Testing should include:

### Identity

- User provisioning
- User deprovisioning
- SSO
- MFA
- Authentication failures

### Authorisation

- Role access
- Permission access
- Division access
- Administrative access
- Cross-division access

### Data

- PII
- Sensitive information
- Recording
- Retention
- Deletion
- Export

### Integrations

- OAuth
- API scopes
- Credential security
- Failed authentication
- Invalid authorisation

### Audit

- Administrative events
- Configuration changes
- Access activity
- Security events

### Monitoring

- Security alerts
- Escalation
- Incident workflows

---

# 24. Compliance Control Model

Each requirement should be traceable:

```text
Regulation / Policy
        ↓
Requirement
        ↓
Control
        ↓
Genesys Configuration
        ↓
Test Case
        ↓
Evidence
        ↓
Approval
```

The compliance matrix should therefore include:

| Field | Description |
|---|---|
| Requirement ID | Unique requirement |
| Regulation / Policy | Source |
| Requirement | Requirement text |
| Control | Security control |
| Genesys Capability | Relevant capability |
| Configuration | Implementation |
| Test | Validation |
| Evidence | Proof |
| Owner | Responsible party |
| Status | Current state |

---

# 25. Access Review Model

Access reviews should cover:

- Users
- Administrators
- Supervisors
- QA users
- Compliance users
- Service accounts
- API clients
- OAuth clients
- Privileged roles
- Division access

Review process:

```text
Generate Access Report
        ↓
Business Owner Review
        ↓
Security Review
        ↓
Remove Unnecessary Access
        ↓
Document Exceptions
        ↓
Approve
        ↓
Archive Evidence
```

---

# 26. Production Security Validation

Production validation should confirm:

```text
Authentication
      +
MFA
      +
SSO
      +
RBAC
      +
Divisions
      +
Least Privilege
      +
Privileged Access
      +
API Security
      +
Secrets
      +
Data Protection
      +
Audit
      +
Monitoring
      +
Compliance
      ↓
PRODUCTION SECURITY ACCEPTANCE
```

---

# 27. Operational Security Model

```text
                   Security Governance
                           │
                           ▼
                  Security Operations
                           │
        ┌──────────────────┼──────────────────┐
        │                  │                  │
        ▼                  ▼                  ▼
      IAM              Monitoring          Compliance
        │                  │                  │
        ▼                  ▼                  ▼
 Access Review        Incident Response    Audit
        │                  │                  │
        └──────────────────┼──────────────────┘
                           ▼
                    Risk Management
                           │
                           ▼
                  Continuous Improvement
```

---

# 28. Security Change Management

Changes requiring security review include:

- Roles
- Permissions
- Divisions
- Authentication
- SSO
- MFA
- OAuth clients
- API scopes
- Integrations
- Recording policies
- Retention
- Data flows
- Security monitoring
- Compliance controls
- Data residency
- Sensitive-data processing

Standard workflow:

```text
Change
  ↓
Security Impact Assessment
  ↓
Risk Assessment
  ↓
Security Approval
  ↓
Configuration
  ↓
Testing
  ↓
Production Change
  ↓
Validation
  ↓
Evidence
```

---

# 29. Security Documentation Standards

Every security-controlled capability should document:

1. Capability
2. Purpose
3. Owner
4. Security requirement
5. Configuration
6. Dependencies
7. Access model
8. Data handled
9. Compliance requirements
10. Testing
11. Evidence
12. Exceptions
13. Review frequency
14. BAU owner

Every privileged role should document:

1. Role
2. Business purpose
3. Permissions
4. Users
5. Owner
6. Approval
7. Review frequency
8. Emergency use
9. Audit requirements

---

# 30. Security Handover Package

The security handover should include:

- Security architecture
- Security requirements
- Security control matrix
- RBAC matrix
- Division model
- Permission model
- Service-account register
- API-client register
- Integration security assessment
- Data classification
- Privacy assessment
- PCI assessment
- Retention model
- Audit model
- Monitoring model
- Incident response procedure
- Security test evidence
- Compliance evidence
- Access review evidence
- Security exceptions
- Production security checklist
- BAU governance
- Security contacts

---

# 31. Security Acceptance Model

A security capability is accepted only when:

```text
Requirement
    +
Architecture
    +
Configuration
    +
Security Review
    +
Functional Test
    +
Security Test
    +
Compliance Review
    +
Evidence
    +
Approval
    ↓
Accepted Security Capability
```

---

# 32. Environment Security Model

The project should consider security separately for:

```text
Development
      ↓
System Integration Testing
      ↓
User Acceptance Testing
      ↓
Production
```

Each environment should be reviewed for:

- Users
- Roles
- Permissions
- Credentials
- API clients
- Test data
- PII
- Recording
- Integrations
- Logging
- Monitoring
- Security configuration

---

# 33. Business Continuity Model

The project should identify:

- Critical processes
- Critical queues
- Critical integrations
- Critical users
- Critical customer channels
- External dependencies
- Manual workarounds
- Communication procedures
- Recovery responsibilities
- Recovery testing

Genesys Cloud continuity planning must be integrated with the customer's broader business continuity strategy.

---

# 34. Security Support Model

```text
L1 — Contact Centre Operations
        │
        ▼
L2 — Genesys Platform Support
        │
        ▼
L3 — Genesys Engineering / Specialist
        │
        ▼
Security / Vendor Escalation
```

Security incidents should additionally integrate with:

- SOC
- Cyber Security
- Privacy
- Compliance
- Legal
- Risk
- Business Owners

where applicable.

---

# 35. Critical Path Considerations

The following activities may become critical-path items:

```text
Security Requirements
        ↓
Security Architecture
        ↓
IAM / RBAC Design
        ↓
Customer Security Review
        ↓
Compliance Review
        ↓
Security Configuration
        ↓
Integration Security
        ↓
Security Testing
        ↓
Compliance Testing
        ↓
Production Security Review
        ↓
Security Approval
        ↓
Production
```

Potential blockers include:

- Security architecture approval
- Identity provider configuration
- MFA requirements
- Security policy conflicts
- Division model changes
- Compliance assessment
- Privacy approval
- PCI assessment
- Integration security review
- Security testing
- Production access approval

---

# 36. Security Governance Cadence

The BAU governance model should establish appropriate frequencies for:

| Governance Activity | Typical Cadence |
|---|---|
| Privileged Access Review | Regular |
| User Access Review | Regular |
| Service Account Review | Regular |
| API Client Review | Regular |
| Security Configuration Review | Regular |
| Security Exception Review | Regular |
| Compliance Review | Regular |
| Incident Review | After significant incidents |
| Architecture Review | On material change |
| Disaster Recovery Review | Regular |
| Security Policy Review | Regular |

Exact cadence must be determined by customer policy and regulatory requirements.

---

# 37. Implementation Dependencies

| Activity | Primary Dependency |
|---|---|
| Security Strategy | Project scope |
| Security Requirements | Enterprise policies |
| Security Architecture | Solution architecture |
| IAM | Identity provider |
| SSO | Customer IdP |
| MFA | Enterprise authentication policy |
| RBAC | Business personas |
| Divisions | Operating model |
| API Security | Integration design |
| Data Protection | Data classification |
| Privacy | Legal / privacy requirements |
| PCI | Payment architecture |
| Recording Security | Recording design |
| Audit | Security operations |
| Monitoring | SOC requirements |
| Compliance | Regulatory requirements |
| Security Testing | Solution configuration |
| Production Security | UAT and remediation |
| Handover | Operational readiness |

---

# 38. Domain Completion Gate

The Security, Compliance & Governance domain is considered **capability-complete** when:

- Security strategy is approved.
- Security requirements are complete.
- Security architecture is approved.
- Security governance is established.
- Identity security is defined.
- Authentication is defined.
- SSO is implemented where required.
- MFA is implemented where required.
- RBAC is approved.
- Permissions are validated.
- Permission policies are validated.
- Divisions are validated.
- Least privilege is confirmed.
- Privileged access is controlled.
- Service accounts are governed where applicable.
- API clients and OAuth are governed where applicable.
- Secrets are protected.
- Integrations are security assessed.
- Data protection is implemented.
- Encryption requirements are satisfied.
- Data residency is approved.
- Privacy requirements are approved.
- PII controls are validated.
- PCI requirements are addressed where applicable.
- Recording security is validated.
- Retention and deletion are approved.
- Audit logging is validated.
- Security monitoring is operational.
- Threat detection is implemented where applicable.
- Incident response is established.
- Vulnerability management is established.
- Security change management is operational.
- Configuration governance is operational.
- Compliance requirements are mapped.
- Regulatory controls are implemented where applicable.
- Customer security policies are addressed.
- Audit evidence is complete.
- Access reviews are complete.
- Security reviews are complete.
- Third-party risk is assessed where applicable.
- Business continuity is documented.
- Disaster recovery is documented.
- Security testing is complete.
- Compliance testing is complete.
- Production security validation is complete.
- Operational security governance is established.
- Security handover is accepted.

```text
SECURITY STRATEGY
        │
        ▼
SECURITY REQUIREMENTS
        │
        ▼
SECURITY ARCHITECTURE
        │
        ▼
IAM / RBAC / DIVISIONS
        │
        ▼
DATA / PRIVACY / COMPLIANCE
        │
        ▼
SECURITY CONTROLS
        │
        ▼
INTEGRATION SECURITY
        │
        ▼
SECURITY TESTING
        │
        ▼
COMPLIANCE TESTING
        │
        ▼
PRODUCTION SECURITY VALIDATION
        │
        ▼
OPERATIONAL SECURITY GOVERNANCE
        │
        ▼
SECURITY HANDOVER
        │
        ▼
SECURITY READY FOR BAU
```

---

# 39. Domain Completion

**Layer:** 2  
**Domain:** 11 — Security, Compliance & Governance  
**Capability Documents:** 47  
**Status:** Capability catalogue complete  
**Next Activity:** Continue with Layer 2 Domain 12.

This domain defines the **capability catalogue**. It is not yet the final implementation schedule.

The eventual implementation workbook will convert these capabilities into detailed implementation tasks suitable for the master Genesys Cloud deployment workbook.

The final implementation workbook will contain:

- Task ID
- Phase
- Workstream
- Capability
- Task
- Description
- Dependencies
- Role
- Customer responsibility
- Environment
- Effort
- Duration
- Deliverable
- Acceptance criteria
- Critical-path indicator

---

# Phase Completion

**Layer 2.11 — Security, Compliance & Governance is complete at capability-catalogue level.**

**Next Domain:**

`12 — Testing, Validation & Deployment`
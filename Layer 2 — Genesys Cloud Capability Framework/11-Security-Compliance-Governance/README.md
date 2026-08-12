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

The following sections define the implementation requirements for each capability.

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
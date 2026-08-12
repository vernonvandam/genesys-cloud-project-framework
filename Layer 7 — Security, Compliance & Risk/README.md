# Layer 7 — Security, Compliance & Risk

## Purpose

Layer 7 defines security, privacy, compliance and risk requirements across the Genesys Cloud deployment lifecycle.

Layer 7 answers:

> **How do we make the deployment secure, compliant and controlled?**

## Objective

Ensure security is designed into the solution rather than treated as a final project activity.

# Security Domains

## 7.1 Identity

- SSO
- SAML
- MFA
- IAM
- SCIM
- User lifecycle
- Role mapping

## 7.2 Access Control

- RBAC
- Least privilege
- Divisions
- Roles
- Permissions
- Privileged access
- Access reviews

## 7.3 API Security

- OAuth
- API clients
- Tokens
- Secrets
- Certificates
- Rotation
- Scope

## 7.4 Data Security

- Data classification
- Encryption
- Data residency
- Retention
- Privacy
- PII
- Sensitive information

## 7.5 Recording Security

- Recording access
- Retention
- Export
- Playback
- Secure pause
- Legal hold
- Audit

## 7.6 Compliance

Potential areas include:

- Privacy
- Telecommunications
- Financial services
- Healthcare
- Government
- PCI
- Regulatory obligations
- Customer-specific controls

# Security Lifecycle

```text
Discovery
    ↓
Security Requirements
    ↓
Security Architecture
    ↓
Threat / Risk Assessment
    ↓
Implementation
    ↓
Security Testing
    ↓
Security Acceptance
    ↓
BAU Security Operations
```

# Risk Framework

Each risk should contain:

- Risk ID
- Description
- Probability
- Impact
- Rating
- Owner
- Mitigation
- Contingency
- Trigger
- Status

# Security Reviews

Recommended reviews:

- Architecture security review
- IAM review
- API review
- Data privacy review
- Recording review
- Integration review
- Production access review
- Final security acceptance

# Security Controls

Controls should address:

- Authentication
- Authorisation
- Encryption
- Secrets
- Logging
- Monitoring
- Access
- Data
- Retention
- Audit
- Incident response

# Security Handover

BAU must receive:

- Security architecture
- Access model
- OAuth inventory
- Service account inventory
- Secrets ownership
- Audit requirements
- Security procedures
- Incident escalation

# Future Documentation

```text
README.md
SECURITY-ARCHITECTURE.md
IAM.md
RBAC.md
OAUTH.md
DATA-PRIVACY.md
RECORDING-SECURITY.md
COMPLIANCE.md
RISK-MANAGEMENT.md
SECURITY-TESTING.md
SECURITY-HANDOVER.md
```

# Definition of Done

Layer 7 is complete when security, privacy, compliance and risk requirements are integrated into the lifecycle and every relevant Genesys Cloud capability has defined security controls and acceptance criteria.
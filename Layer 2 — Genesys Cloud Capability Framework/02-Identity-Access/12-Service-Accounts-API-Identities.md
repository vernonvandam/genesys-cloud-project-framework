# Layer 2.02.12 — Service Accounts & API Identities

## 1. Purpose

Define non-human identities used for integrations, automation and API access.

## 2. Classification

**Conditional**

## 3. Discovery

Identify:

- Integration identities.
- Automation processes.
- API consumers.
- Terraform identities.
- Data export processes.
- Monitoring identities.
- Ownership.
- Required permissions.
- Credential lifecycle.

## 4. Design

Each identity must have:

- Business purpose.
- Technical owner.
- Customer owner.
- Environment.
- Permissions.
- Division scope.
- Credential storage.
- Rotation procedure.
- Expiry/revocation process.

## 5. Implementation

```text
Identify integration
Define identity
Define permissions
Create credentials
Store securely
Test API access
Test denied access
Document lifecycle
```

## 6. Security

Never embed credentials in:

- Source code
- Git repositories
- Terraform files
- Documentation
- Scripts
- CI logs

Use an approved secrets-management mechanism.

## 7. Acceptance Criteria

Every non-human identity has documented ownership, least-privilege permissions and secure credential storage.

## 8. Definition of Done

Service identities are configured, tested, documented and operationally governed.

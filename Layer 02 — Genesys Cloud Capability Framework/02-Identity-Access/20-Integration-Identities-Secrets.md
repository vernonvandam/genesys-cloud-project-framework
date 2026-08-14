# Layer 2.02.20 — Integration Identities & Secrets

## 1. Purpose

Define secure identity and credential management for integrations connecting Genesys Cloud with external platforms.

## 2. Classification

**Conditional**

## 3. Scope

- API identities
- OAuth clients
- Client secrets
- Tokens
- Certificates where applicable
- Integration credentials
- Terraform credentials
- CI/CD credentials
- Data-action credentials
- External system credentials

## 4. Discovery

For every integration identify:

- System.
- Identity.
- Authentication method.
- Permissions.
- Secret location.
- Owner.
- Rotation.
- Expiry.
- Environment.
- Monitoring.

## 5. Implementation

```text
Identify integration
       ↓
Identify identity
       ↓
Define minimum permissions
       ↓
Create credential
       ↓
Store securely
       ↓
Configure integration
       ↓
Test
       ↓
Document
       ↓
Operationalise rotation
```

## 6. Security

Credentials must not be stored in source repositories or plaintext project documentation.

## 7. Acceptance Criteria

All integration credentials are securely managed and have documented ownership and lifecycle.

## 8. Definition of Done

Integration identities and secrets are configured, secured and operationally governed.

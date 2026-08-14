# 23 — Security Testing

## Capability Definition

Validates security controls implemented across the Genesys Cloud solution, including identity, access, authentication, authorisation, integrations and data protection.

---

# 1. Scope

- Authentication
- Authorisation
- Roles
- Permissions
- SSO
- MFA
- API access
- Data access
- Administrative controls
- Security logging

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

- Identify security requirements.
- Identify personas.
- Identify sensitive capabilities.
- Identify privileged roles.
- Identify API clients.
- Identify compliance requirements.

---

# 4. Design Activities

- Define security test scenarios.
- Define positive and negative access tests.
- Define privilege tests.
- Define authentication tests.
- Define API security tests.

---

# 5. Implementation Activities

```text
Test authentication
Test MFA
Test SSO
Test role permissions
Test least privilege
Test administrative access
Test restricted data access
Test API scopes
Test invalid credentials
Test unauthorised access
Validate security logging
Record security defects
```

---

# 6. Dependencies

- Identity & Access
- Security Architecture
- APIs
- Compliance

---

# 7. Layer 1 Mapping

Primary:

- Phase 5 — Platform Configuration & Security
- Phase 8 — Testing & Validation

---

# 8. Roles

- Security Specialist
- Identity Administrator
- Genesys Cloud Architect
- Test Lead

---

# 9. Customer Responsibilities

- Approve security requirements.
- Provide security SMEs.
- Approve security test results.

---

# 10. Testing

Execute both authorised and unauthorised access scenarios.

---

# 11. Deliverables

- Security Test Cases
- Security Validation
- Security Defect Register

---

# 12. Effort Drivers

- Number of roles
- Security controls
- Integrations
- Compliance
- Privileged access

---

# 13. Acceptance Criteria

- Authentication works.
- Unauthorised access is denied.
- Privileges operate correctly.
- Sensitive data access is controlled.

---

# 14. Definition of Done

Security controls are tested and accepted.

---

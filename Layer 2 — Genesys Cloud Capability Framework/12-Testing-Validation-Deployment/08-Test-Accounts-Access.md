# 08 — Test Accounts & Access

## Capability Definition

Provides the user accounts, roles, permissions, credentials and access required to execute testing.

---

# 1. Scope

- Test users
- Personas
- Roles
- Permissions
- Identity provider
- SSO
- MFA
- API accounts
- Service accounts
- External systems

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

- Identify test personas.
- Identify required permissions.
- Identify SSO requirements.
- Identify test service accounts.
- Identify API credentials.
- Identify external system access.

---

# 4. Design Activities

- Define test account matrix.
- Define role mapping.
- Define permission requirements.
- Define authentication approach.
- Define service-account controls.

---

# 5. Implementation Activities

```text
Create test account matrix
Create test users
Assign roles
Configure permissions
Configure SSO
Configure MFA
Create service accounts where required
Configure API credentials
Configure external system access
Validate least privilege
Execute login tests
Validate role behaviour
```

---

# 6. Dependencies

- Identity & Access
- Security
- Integration
- Test Environment

---

# 7. Layer 1 Mapping

Primary:

- Phase 5 — Platform Configuration & Security
- Phase 8 — Testing & Validation

---

# 8. Roles

- Identity Administrator
- Genesys Cloud Administrator
- Security Specialist
- Test Lead

---

# 9. Customer Responsibilities

- Provide test identities.
- Approve access.
- Approve roles.
- Provide external credentials.

---

# 10. Testing

Validate authentication, authorisation, role permissions and access segregation.

---

# 11. Deliverables

- Test Account Matrix
- Test Role Matrix
- Access Validation Results

---

# 12. Effort Drivers

- Number of personas
- Number of roles
- SSO complexity
- MFA
- External systems
- Service accounts

---

# 13. Acceptance Criteria

- Test accounts exist.
- Required roles assigned.
- SSO/MFA validated.
- Access permissions validated.

---

# 14. Definition of Done

All required test identities and access permissions are operational.

---
# Layer 2.01.17 — Environment Strategy

## Capability Definition

Defines how Genesys Cloud configuration is developed, tested, approved and deployed across environments or organisational instances.

---

# 1. Scope

- Development
- Test
- UAT
- Production
- Environment ownership
- Configuration promotion
- Data separation
- Integration endpoints
- Credentials
- Test data
- Release management
- Configuration migration
- Terraform/IaC
- CI/CD

Genesys Cloud environments and organisation strategy must be designed according to the capabilities and controls actually available in the target implementation.

---

# 2. Classification

**Required**

---

# 3. Discovery

Determine:

- Number of organisations/environments.
- Development requirements.
- Test requirements.
- UAT requirements.
- Production requirements.
- Customer governance.
- Integration endpoint strategy.
- Test data strategy.
- Automation requirements.
- Terraform requirements.
- CI/CD requirements.

---

# 4. Design

Define:

```text
Development
    ↓
Testing
    ↓
UAT
    ↓
Production
```

For each environment define:

- Ownership
- Access
- Configuration
- Data
- Integrations
- Credentials
- Deployment mechanism
- Change control
- Backup/export
- Rollback approach

---

# 5. Implementation

```text
Define environment strategy
Approve architecture
Establish environments/organisations as applicable
Configure access
Configure integration endpoints
Configure test data
Configure deployment mechanism
Validate promotion process
Document strategy
```

---

# 6. Dependencies

- Architecture
- Security
- IAM
- Integration
- Terraform
- CI/CD
- Testing
- Change management

---

# 7. Testing

Validate:

- Configuration can be deployed.
- Environment-specific settings are correct.
- Integration endpoints are correct.
- Credentials are isolated.
- Test data is controlled.
- Production is protected from development activity.

---

# 8. Operational Requirements

Define:

- Who can change each environment.
- How changes are promoted.
- How emergency changes are managed.
- How configuration drift is identified.
- How production changes are approved.
- How rollback is performed.

---

# 9. Acceptance Criteria

The environment strategy is approved and the deployment process has been successfully demonstrated.

---

# 10. Definition of Done

All required environments or organisational instances are established, secured and supported by an approved configuration-promotion strategy.

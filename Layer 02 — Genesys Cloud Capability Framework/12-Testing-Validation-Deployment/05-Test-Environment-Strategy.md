# 05 — Test Environment Strategy

## Capability Definition

Defines the environments required to build, test, validate and deploy the Genesys Cloud solution and its dependent systems.

---

# 1. Scope

- Development
- Configuration
- Integration
- SIT
- UAT
- Production
- External systems
- Network
- Identity
- Test data
- Environment separation

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

- Inventory existing environments.
- Identify Genesys Cloud organisation strategy.
- Identify external test environments.
- Identify integration endpoints.
- Identify identity providers.
- Identify telephony test requirements.
- Identify data requirements.
- Identify environment constraints.

---

# 4. Design Activities

- Define environment topology.
- Define environment ownership.
- Define environment access.
- Define configuration promotion approach.
- Define integration endpoints.
- Define test data separation.
- Define environment refresh approach.

---

# 5. Implementation Activities

```text
Inventory environments
Map environment purposes
Define environment ownership
Define access requirements
Define Genesys Cloud organisation strategy
Define external endpoints
Define test telephony
Define test data boundaries
Define environment configuration
Define environment promotion process
Document environment strategy
```

---

# 6. Dependencies

- Architecture
- Identity & Access
- Integration Architecture
- Test Data
- Security Requirements

---

# 7. Layer 1 Mapping

Primary:

- Phase 4 — Solution Architecture & Detailed Design
- Phase 8 — Testing & Validation

---

# 8. Roles

- Solution Architect
- Genesys Cloud Architect
- Technical Architect
- Integration Engineer
- Security Specialist
- Test Lead

---

# 9. Customer Responsibilities

- Provide required environments.
- Provide external test endpoints.
- Provide identity infrastructure.
- Approve environment topology.

---

# 10. Testing

Validate environment isolation, connectivity, access and configuration.

---

# 11. Deliverables

- Test Environment Strategy
- Environment Matrix
- Environment Ownership Matrix
- Environment Dependency Map

---

# 12. Effort Drivers

- Number of environments
- Number of external systems
- Number of integrations
- Identity complexity
- Network complexity
- Telephony complexity

---

# 13. Acceptance Criteria

- All required environments identified.
- Ownership assigned.
- Dependencies documented.
- Access requirements defined.

---

# 14. Definition of Done

The environment strategy is approved and supports all required test phases.

---
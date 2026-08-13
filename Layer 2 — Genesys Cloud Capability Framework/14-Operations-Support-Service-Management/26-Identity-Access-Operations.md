# Layer 2.14.26 — Identity & Access Operations

## Capability Definition

Identity & Access Operations governs ongoing user, role, permission, authentication and access lifecycle management for Genesys Cloud.

---

# 1. Scope

- User lifecycle
- Role assignment
- Permission management
- SSO
- MFA
- Groups
- Divisions
- OAuth clients
- Access reviews
- Privileged access

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

- Identify identity provider.
- Identify administrators.
- Identify access processes.
- Identify role structures.
- Identify joiner/mover/leaver processes.
- Identify access review requirements.

---

# 4. Design Activities

- Define access lifecycle.
- Define administrative roles.
- Define access request process.
- Define access review.
- Define privileged access.
- Define OAuth credential ownership.

---

# 5. Implementation Activities

| Task ID | Task | Primary Layer 1 Phase | Role | Effort |
|---|---|---|---|---:|
| 2.14.26-T01 | Review identity operational model | Phase 2 | IAM Lead | 4h |
| 2.14.26-T02 | Define access lifecycle | Phase 3 | Security Architect | 4h |
| 2.14.26-T03 | Define administrative access controls | Phase 4 | Security Architect | 6h |
| 2.14.26-T04 | Configure operational access procedures | Phase 6 | IAM Lead | 6h |
| 2.14.26-T05 | Test joiner/mover/leaver scenarios | Phase 8 | Test Lead | 6h |
| 2.14.26-T06 | Transition identity operations | Phase 12 | IAM Lead | 4h |

---

# 6. Dependencies

- Identity & Access
- Security
- API/OAuth Lifecycle
- Governance

---

# 7. Layer 1 Mapping

- Phase 2 — Discovery & Current State Assessment
- Phase 3 — Requirements & Solution Definition
- Phase 4 — Solution Architecture & Detailed Design
- Phase 6 — Feature Configuration & Solution Build
- Phase 8 — Testing & Validation
- Phase 12 — BAU Handover & Project Closure

---

# 8. Roles

- IAM Lead
- Security Architect
- Operations Lead
- Test Lead

---

# 9. Customer Responsibilities

- Manage identity provider.
- Approve access model.
- Perform access reviews.
- Maintain authorised administrators.

---

# 10. Testing

Test user lifecycle, role changes, privileged access and authentication.

---

# 11. Deliverables

- IAM Operations Guide
- Access Lifecycle
- Access Review Process
- Privileged Access Procedure

---

# 12. Effort Drivers

User volume, identity architecture, automation and access complexity.

---

# 13. Acceptance Criteria

- Lifecycle documented.
- Access model approved.
- Reviews defined.
- Scenarios tested.

---

# 14. Definition of Done

Genesys Cloud access can be securely managed throughout the user and credential lifecycle.
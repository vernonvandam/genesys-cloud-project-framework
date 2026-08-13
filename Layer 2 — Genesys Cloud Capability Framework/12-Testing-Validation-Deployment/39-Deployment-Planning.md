# 39 — Deployment Planning

## Capability Definition

Defines the technical and operational approach for promoting the Genesys Cloud solution into production.

---

# 1. Scope

- Configuration promotion
- Code
- Architect
- Integrations
- APIs
- Telephony
- Data
- Security
- Deployment sequencing

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

- Identify production components.
- Identify promotion dependencies.
- Identify deployment tooling.
- Identify configuration dependencies.
- Identify production access.

---

# 4. Design Activities

- Define deployment sequence.
- Define pre-deployment checks.
- Define deployment validation.
- Define rollback.
- Define ownership.

---

# 5. Implementation Activities

```text
Inventory production components
Identify dependencies
Define deployment order
Define pre-checks
Prepare deployment artefacts
Validate production access
Prepare deployment scripts
Prepare configuration
Prepare validation
Prepare rollback
Conduct deployment rehearsal
Baseline deployment plan
```

---

# 6. Dependencies

- Build
- Testing
- Cutover
- Release Management
- Rollback

---

# 7. Layer 1 Mapping

Primary:

- Phase 9 — Operational Readiness & Cutover Preparation
- Phase 10 — Production Deployment & Go-Live

---

# 8. Roles

- Release Manager
- Genesys Cloud Architect
- Genesys Cloud Engineer
- Integration Engineer
- Project Manager

---

# 9. Customer Responsibilities

- Approve production access.
- Approve deployment window.
- Approve deployment plan.

---

# 10. Testing

Validate deployment procedures in a lower environment where possible.

---

# 11. Deliverables

- Deployment Plan
- Deployment Runbook
- Deployment Checklist
- Rollback Plan

---

# 12. Effort Drivers

- Number of components
- Number of integrations
- Deployment tooling
- Manual activities
- Production complexity

---

# 13. Acceptance Criteria

- Deployment sequence defined.
- Artefacts ready.
- Dependencies defined.
- Rollback ready.

---

# 14. Definition of Done

Deployment plan is approved and executable.

---

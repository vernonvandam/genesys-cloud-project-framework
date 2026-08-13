# 41 — Production Deployment

## Capability Definition

Executes the approved production deployment and transitions the Genesys Cloud solution into live operation.

---

# 1. Scope

- Production configuration
- Configuration promotion
- Integrations
- Telephony
- Architect
- Routing
- Users
- Data
- Validation

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

- Confirm approved deployment plan.
- Confirm deployment window.
- Confirm resources.
- Confirm dependencies.
- Confirm rollback.

---

# 4. Design Activities

- Confirm deployment sequence.
- Confirm validation checkpoints.
- Confirm communication points.
- Confirm escalation.

---

# 5. Implementation Activities

```text
Open deployment bridge
Confirm go decision
Execute pre-deployment checks
Deploy configuration
Deploy integrations
Deploy Architect
Deploy routing
Deploy telephony changes
Enable users
Execute data migration where applicable
Validate components
Execute smoke tests
Communicate deployment status
Record deployment evidence
```

---

# 6. Dependencies

- Go-Live Readiness
- Cutover Planning
- Deployment Planning
- Rollback

---

# 7. Layer 1 Mapping

Primary:

- Phase 10 — Production Deployment & Go-Live

---

# 8. Roles

- Deployment Lead
- Genesys Cloud Architect
- Genesys Cloud Engineer
- Integration Engineer
- Voice Engineer
- Operations

---

# 9. Customer Responsibilities

- Provide deployment approval.
- Provide business resources.
- Participate in validation.
- Approve production acceptance.

---

# 10. Testing

Production deployment must immediately transition into production smoke testing.

---

# 11. Deliverables

- Deployment Record
- Deployment Checklist
- Deployment Evidence
- Production Configuration Baseline

---

# 12. Effort Drivers

- Deployment complexity
- Number of components
- Number of integrations
- Telephony
- Migration
- Cutover duration

---

# 13. Acceptance Criteria

- Deployment completed.
- No blocking deployment errors.
- Critical components operational.
- Smoke testing commenced.

---

# 14. Definition of Done

Production deployment is completed and handed to production validation.

---

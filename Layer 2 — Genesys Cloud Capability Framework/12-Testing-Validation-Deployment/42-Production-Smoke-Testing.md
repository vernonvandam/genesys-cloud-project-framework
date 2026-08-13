# 42 — Production Smoke Testing

## Capability Definition

Performs rapid validation immediately after deployment to confirm that critical platform functions are operational before broader production validation.

---

# 1. Scope

- Login
- Inbound voice
- Outbound voice
- Routing
- Architect
- Integrations
- Digital
- Recording
- Analytics

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

- Identify critical production functions.
- Identify smoke test users.
- Identify test numbers.
- Identify test scenarios.
- Identify acceptable results.

---

# 4. Design Activities

- Define minimal smoke suite.
- Define execution order.
- Define failure criteria.
- Define escalation.

---

# 5. Implementation Activities

```text
Validate administrator access
Validate agent login
Test inbound interaction
Test outbound interaction
Test routing
Test Architect
Test critical integration
Test digital channel where applicable
Test recording
Validate analytics
Validate critical reporting
Record results
Escalate failures
```

---

# 6. Dependencies

- Production Deployment
- Test Accounts
- Voice
- Routing
- Architect
- Integrations

---

# 7. Layer 1 Mapping

Primary:

- Phase 10 — Production Deployment & Go-Live

---

# 8. Roles

- Test Lead
- Genesys Cloud Engineer
- Integration Engineer
- Voice Engineer
- Business SME

---

# 9. Customer Responsibilities

- Provide smoke testers.
- Validate business-critical transactions.
- Approve smoke results.

---

# 10. Testing

Smoke testing must be fast, repeatable and focused on critical production functionality.

---

# 11. Deliverables

- Production Smoke Checklist
- Smoke Test Results
- Production Issue Register

---

# 12. Effort Drivers

- Number of critical functions
- Channels
- Integrations
- Production complexity

---

# 13. Acceptance Criteria

- Critical login works.
- Critical interactions work.
- Routing works.
- Critical integrations work.
- No blocking smoke failures.

---

# 14. Definition of Done

Production passes smoke testing and proceeds to full production validation.

---

# 14 — ACD & Routing Testing

## Capability Definition

Validates queues, routing methods, skills, priorities, bullseye routing, utilisation, overflow, transfer and queue behaviour.

---

# 1. Scope

- Queues
- Skills
- Languages
- Routing methods
- Bullseye routing
- Priorities
- Utilisation
- Overflow
- Callbacks
- Transfers
- Queue announcements

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

- Identify routing scenarios.
- Identify queues.
- Identify skills.
- Identify routing rules.
- Identify overflow.
- Identify priority rules.
- Identify exception paths.

---

# 4. Design Activities

Define test cases for:

- Correct queue selection
- Skill matching
- Priority
- Bullseye expansion
- Overflow
- No-agent scenarios
- Agent unavailable
- Transfer
- Callback
- Business hours

---

# 5. Implementation Activities

```text
Test queue selection
Test skill matching
Test language matching
Test priority
Test bullseye routing
Test overflow
Test queue timeout
Test callback
Test transfer
Test agent unavailable
Test business hours
Test exception routing
Validate routing metrics
```

---

# 6. Dependencies

- ACD & Routing
- Architect
- Voice
- WFM
- Users

---

# 7. Layer 1 Mapping

Primary:

- Phase 7 — Component & Integration Testing
- Phase 8 — Testing & Validation

---

# 8. Roles

- Genesys Cloud Architect
- Genesys Cloud Engineer
- Test Analyst
- Business SME

---

# 9. Customer Responsibilities

- Validate routing outcomes.
- Provide routing scenarios.
- Approve business rules.

---

# 10. Testing

Validate routing decisions against approved business rules.

---

# 11. Deliverables

- Routing Test Cases
- Routing Test Results
- Queue Validation
- Skill Validation

---

# 12. Effort Drivers

- Number of queues
- Skills
- Routing rules
- Overflow complexity
- Callback
- Priority logic

---

# 13. Acceptance Criteria

- Correct queue selected.
- Correct agent selection.
- Skills respected.
- Overflow works.
- Exception handling works.

---

# 14. Definition of Done

All routing scenarios pass testing.

---
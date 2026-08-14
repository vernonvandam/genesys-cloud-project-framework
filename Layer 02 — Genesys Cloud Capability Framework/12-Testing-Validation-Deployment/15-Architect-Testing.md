# 15 — Architect Testing

## Capability Definition

Validates Genesys Cloud Architect flows, menus, prompts, variables, logic, data actions, transfers, error handling and end-to-end interaction behaviour.

---

# 1. Scope

- Inbound flows
- In-queue flows
- IVR
- Menus
- Prompts
- Variables
- Decisions
- Data Actions
- Transfers
- Disconnects
- Error handling
- Reusable modules

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

- Inventory Architect flows.
- Identify flow dependencies.
- Identify data actions.
- Identify prompts.
- Identify variables.
- Identify exception paths.

---

# 4. Design Activities

Develop test scenarios covering:

- Happy path
- Invalid input
- Timeout
- Retry
- Transfer
- Disconnect
- Data failure
- Backend failure
- Business-hours logic
- Emergency logic
- Language selection

---

# 5. Implementation Activities

```text
Validate flow publication
Test flow entry
Test menu navigation
Test valid input
Test invalid input
Test timeout
Test retry
Test data actions
Test decisions
Test transfers
Test disconnects
Test error handling
Test business hours
Test emergency paths
Test reusable modules
Capture execution evidence
```

---

# 6. Dependencies

- Architect
- ACD & Routing
- Data Actions
- Integrations
- Voice
- Digital

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
- Integration Engineer
- Business SME

---

# 9. Customer Responsibilities

- Validate business flow outcomes.
- Provide expected interaction journeys.
- Approve prompts and business logic.

---

# 10. Testing

Test every meaningful flow branch, exception path and integration dependency.

---

# 11. Deliverables

- Architect Test Cases
- Flow Test Results
- Branch Coverage
- Defect Register

---

# 12. Effort Drivers

- Number of flows
- Flow complexity
- Branches
- Data Actions
- Integrations
- Languages

---

# 13. Acceptance Criteria

- Required flows tested.
- Branches tested.
- Exceptions tested.
- Integrations tested.
- Business outcome validated.

---

# 14. Definition of Done

All in-scope Architect flows pass functional and integration testing.

---

# Layer 2.13.23 — Routing Migration

## Capability Definition

Routing Migration transfers source routing logic into the approved Genesys Cloud ACD routing model.

---

# 1. Scope

- Routing rules
- Skills
- Languages
- Priority
- Bullseye
- Preferred agents
- Overflow
- Business hours
- Queue routing

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

Document source routing logic, exceptions and business rules.

---

# 4. Design Activities

Map source routing to Genesys Cloud routing constructs.

---

# 5. Implementation Activities

| Task ID | Task | Phase | Effort |
|---|---|---|---:|
| 2.13.23-T01 | Inventory routing rules | Phase 2 | 6h |
| 2.13.23-T02 | Map routing logic | Phase 4 | 8h |
| 2.13.23-T03 | Configure routing | Phase 6 | 8h |
| 2.13.23-T04 | Execute routing migration | Phase 7 | 6h |
| 2.13.23-T05 | Test routing scenarios | Phase 8 | 8h |

---

# 6. Dependencies

- Queues
- Skills
- Architect
- Telephony

---

# 7. Layer 1 Mapping

- Phase 3 — Requirements
- Phase 4 — Design
- Phase 6 — Build
- Phase 7 — Migration
- Phase 8 — Testing
- Phase 10 — Go-Live

---

# 8. Roles

- Genesys Cloud Architect
- Routing Specialist
- Migration Engineer

---

# 9. Customer Responsibilities

Validate business routing outcomes.

---

# 10. Testing

Execute positive, negative, overflow and exception routing tests.

---

# 11. Deliverables

- Routing Mapping
- Routing Configuration
- Routing Validation

---

# 12. Effort Drivers

Number of queues, rules, skills and exceptions.

---

# 13. Acceptance Criteria

Routing matches approved target design.

---

# 14. Definition of Done

Routing is migrated and validated.

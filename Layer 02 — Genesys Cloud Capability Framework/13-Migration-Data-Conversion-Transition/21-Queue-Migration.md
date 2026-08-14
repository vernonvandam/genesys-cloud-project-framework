# Layer 2.13.21 — Queue Migration

## Capability Definition

Queue Migration establishes target Genesys Cloud queues based on approved source queue inventory and target routing design.

---

# 1. Scope

- Queue names
- Queue hierarchy
- Division
- Members
- Skills
- Languages
- Service level
- Routing
- Wrap-up
- In-queue behaviour

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

Inventory source queues and associated configuration.

---

# 4. Design Activities

Map source queues to target queues and determine recreated, consolidated and retired queues.

---

# 5. Implementation Activities

| Task ID | Task | Phase | Effort |
|---|---|---|---:|
| 2.13.21-T01 | Inventory source queues | Phase 2 | 4h |
| 2.13.21-T02 | Map queue target design | Phase 4 | 5h |
| 2.13.21-T03 | Configure target queues | Phase 6 | 6h |
| 2.13.21-T04 | Migrate memberships | Phase 7 | 4h |
| 2.13.21-T05 | Validate queue routing | Phase 8 | 5h |

---

# 6. Dependencies

- ACD
- Skills
- Users
- Routing

---

# 7. Layer 1 Mapping

- Phase 2 — Discovery
- Phase 4 — Design
- Phase 6 — Build
- Phase 7 — Migration
- Phase 8 — Testing

---

# 8. Roles

- Genesys Cloud Architect
- Genesys Cloud Engineer
- Migration Engineer

---

# 9. Customer Responsibilities

Approve queue structure and business routing.

---

# 10. Testing

Validate membership, routing, service level and queue behaviour.

---

# 11. Deliverables

- Queue Mapping
- Queue Configuration
- Queue Validation

---

# 12. Effort Drivers

Queue count and routing complexity.

---

# 13. Acceptance Criteria

Queues operate according to approved routing design.

---

# 14. Definition of Done

All required queues are migrated and validated.


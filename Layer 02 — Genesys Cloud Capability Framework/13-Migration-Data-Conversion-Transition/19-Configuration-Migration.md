# Layer 2.13.19 — Configuration Migration

## Capability Definition

Configuration Migration transfers or recreates Genesys Cloud configuration required to implement the approved target state.

---

# 1. Scope

- Users
- Queues
- Skills
- Languages
- Routing
- Architect
- Telephony
- Digital
- Data tables
- Integrations
- Policies

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

Identify reusable, replaceable and obsolete source configuration.

---

# 4. Design Activities

Map source configuration to target configuration and determine migration method.

---

# 5. Implementation Activities

| Task ID | Task | Phase | Effort |
|---|---|---|---:|
| 2.13.19-T01 | Inventory source configuration | Phase 2 | 6h |
| 2.13.19-T02 | Map source to target configuration | Phase 4 | 8h |
| 2.13.19-T03 | Configure migration tooling | Phase 6 | 6h |
| 2.13.19-T04 | Execute configuration migration | Phase 7 | 8h |
| 2.13.19-T05 | Validate configuration | Phase 8 | 6h |
| 2.13.19-T06 | Resolve configuration defects | Phase 8 | 4h |

---

# 6. Dependencies

- Core Platform
- Identity
- ACD
- Architect
- Telephony
- Integration

---

# 7. Layer 1 Mapping

- Phase 4 — Architecture
- Phase 6 — Solution Build
- Phase 7 — Migration
- Phase 8 — Testing
- Phase 9 — Cutover

---

# 8. Roles

- Genesys Cloud Architect
- Genesys Cloud Engineer
- Migration Engineer

---

# 9. Customer Responsibilities

Validate business configuration.

---

# 10. Testing

Perform configuration comparison and functional testing.

---

# 11. Deliverables

- Configuration Mapping
- Migration Scripts
- Configuration Validation Report

---

# 12. Effort Drivers

Number and complexity of configuration objects.

---

# 13. Acceptance Criteria

Target configuration matches approved design.

---

# 14. Definition of Done

Configuration migration is validated and accepted.

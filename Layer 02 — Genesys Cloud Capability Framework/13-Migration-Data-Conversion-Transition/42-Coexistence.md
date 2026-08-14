# Layer 2.13.42 — Coexistence

## Capability Definition

Coexistence enables legacy and Genesys Cloud platforms to operate concurrently during a phased migration.

---

# 1. Scope

- Parallel operation
- Routing
- Data synchronisation
- Telephony
- Digital channels
- Reporting
- User populations
- Cutover waves

---

# 2. Classification

**Conditional**

---

# 3. Discovery Activities

Identify business processes requiring parallel operation.

---

# 4. Design Activities

Define routing, integration, data and operational coexistence architecture.

---

# 5. Implementation Activities

| Task ID | Task | Phase | Effort |
|---|---|---|---:|
| 2.13.42-T01 | Identify coexistence requirements | Phase 2 | 4h |
| 2.13.42-T02 | Design coexistence model | Phase 4 | 6h |
| 2.13.42-T03 | Configure coexistence | Phase 6 | 8h |
| 2.13.42-T04 | Test parallel operation | Phase 8 | 8h |
| 2.13.42-T05 | Operate coexistence | Phase 10 | 4h |
| 2.13.42-T06 | Exit coexistence | Phase 10 | 4h |

---

# 6. Dependencies

- Telephony
- Routing
- Integrations
- Migration Waves

---

# 7. Layer 1 Mapping

- Phase 4 — Design
- Phase 6 — Build
- Phase 8 — Testing
- Phase 9 — Cutover Preparation
- Phase 10 — Go-Live
- Phase 11 — Hypercare

---

# 8. Roles

- Solution Architect
- Migration Lead
- Voice Architect
- Integration Engineer

---

# 9. Customer Responsibilities

Provide operational support for parallel systems.

---

# 10. Testing

Validate routing and data integrity across both platforms.

---

# 11. Deliverables

- Coexistence Architecture
- Coexistence Runbook
- Exit Plan

---

# 12. Effort Drivers

Number of platforms, migration waves and routing complexity.

---

# 13. Acceptance Criteria

Coexistence does not compromise customer service or data integrity.

---

# 14. Definition of Done

Coexistence is exited successfully or established as BAU where required.


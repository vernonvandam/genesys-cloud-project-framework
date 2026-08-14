# Layer 2.13.24 — Architect Migration

## Capability Definition

Architect Migration recreates or transforms source IVR, inbound, in-queue, outbound and digital workflows into Genesys Cloud Architect.

---

# 1. Scope

- IVR flows
- Inbound flows
- In-queue flows
- Secure flows
- Menus
- Prompts
- Data actions
- Data tables
- Variables
- Error handling

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

Inventory source flows, dependencies, prompts, integrations and business rules.

---

# 4. Design Activities

Map source flows to target Architect patterns and identify redesign requirements.

---

# 5. Implementation Activities

| Task ID | Task | Phase | Effort |
|---|---|---|---:|
| 2.13.24-T01 | Inventory source flows | Phase 2 | 6h |
| 2.13.24-T02 | Map flow dependencies | Phase 3 | 6h |
| 2.13.24-T03 | Define target flow mapping | Phase 4 | 8h |
| 2.13.24-T04 | Recreate or redesign flows | Phase 6 | 12h |
| 2.13.24-T05 | Validate flows | Phase 8 | 8h |

---

# 6. Dependencies

- Architect
- ACD
- Telephony
- Data Actions
- Integrations

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
- Architect Developer
- Integration Engineer

---

# 9. Customer Responsibilities

Provide flow documentation and business acceptance.

---

# 10. Testing

Validate every flow path, error condition and integration.

---

# 11. Deliverables

- Architect Mapping
- Migrated Architect Flows
- Flow Validation

---

# 12. Effort Drivers

Flow count, complexity and integration dependencies.

---

# 13. Acceptance Criteria

All in-scope flows operate according to approved design.

---

# 14. Definition of Done

Architect migration is complete and validated.


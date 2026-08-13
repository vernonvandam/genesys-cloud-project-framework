# Layer 2.13.04 — Source System Inventory

## Capability Definition

The Source System Inventory identifies all systems providing configuration, identity, customer, interaction, telephony, WFM, quality, reporting and integration data relevant to migration.

---

# 1. Scope

- Legacy contact centre platform
- CRM
- Identity provider
- Telephony carrier
- WFM
- Recording platforms
- Quality platforms
- Reporting platforms
- Data warehouse
- Integration middleware
- Custom applications

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

- Identify every source system.
- Record system owner.
- Record technical owner.
- Record environment.
- Record data types.
- Record interfaces.
- Record extraction method.
- Record data volume.
- Record retention requirements.
- Record migration disposition.

---

# 4. Design Activities

Define source-system relationships and migration dependencies.

---

# 5. Implementation Activities

| Task ID | Task | Phase | Effort |
|---|---|---|---:|
| 2.13.04-T01 | Identify source systems | Phase 2 | 4h |
| 2.13.04-T02 | Identify system owners | Phase 2 | 3h |
| 2.13.04-T03 | Document interfaces and dependencies | Phase 2 | 6h |
| 2.13.04-T04 | Document data domains and volumes | Phase 2 | 6h |
| 2.13.04-T05 | Document extraction methods | Phase 3 | 4h |
| 2.13.04-T06 | Baseline source inventory | Phase 3 | 3h |

---

# 6. Dependencies

- Discovery
- Integration inventory
- Data discovery

---

# 7. Layer 1 Mapping

- Phase 2 — Discovery & Current State Assessment
- Phase 3 — Requirements & Solution Definition
- Phase 7 — Integration & Data Migration

---

# 8. Roles

- Migration Lead
- Data Architect
- Integration Architect
- Technical Architect

---

# 9. Customer Responsibilities

Provide system owners, architecture information and source-system access.

---

# 10. Testing

Validate that all migration-relevant systems are represented.

---

# 11. Deliverables

- Source System Inventory
- Source Dependency Matrix
- Source Data Inventory

---

# 12. Effort Drivers

Number of source systems, interfaces and data domains.

---

# 13. Acceptance Criteria

All material migration source systems are identified and ownership is confirmed.

---

# 14. Definition of Done

The source-system inventory is approved and baselined.


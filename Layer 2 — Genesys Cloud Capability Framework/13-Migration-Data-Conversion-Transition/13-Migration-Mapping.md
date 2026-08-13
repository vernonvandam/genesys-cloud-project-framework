# Layer 2.13.13 — Migration Mapping

## Capability Definition

Migration Mapping establishes source-to-target mappings for configuration and data.

---

# 1. Scope

- Source fields
- Target fields
- Object mappings
- Value mappings
- Reference mappings
- Transformation rules
- Default values
- Exceptions

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

- Identify source structures.
- Identify target structures.
- Identify missing target attributes.
- Identify reference relationships.

---

# 4. Design Activities

- Define field mappings.
- Define object mappings.
- Define value translations.
- Define default values.
- Define exceptions.
- Define validation rules.

---

# 5. Implementation Activities

| Task ID | Task | Phase | Effort |
|---|---|---|---:|
| 2.13.13-T01 | Extract source structures | Phase 2 | 4h |
| 2.13.13-T02 | Identify target structures | Phase 3 | 4h |
| 2.13.13-T03 | Build source-to-target mapping | Phase 4 | 8h |
| 2.13.13-T04 | Define transformation rules | Phase 4 | 6h |
| 2.13.13-T05 | Review mappings with SMEs | Phase 4 | 4h |
| 2.13.13-T06 | Baseline mapping | Phase 4 | 3h |

---

# 6. Dependencies

- Data Discovery
- Target architecture
- Configuration design

---

# 7. Layer 1 Mapping

- Phase 2 — Discovery
- Phase 3 — Requirements
- Phase 4 — Detailed Design
- Phase 7 — Migration

---

# 8. Roles

- Data Architect
- Migration Lead
- Genesys Cloud Architect
- Business SME

---

# 9. Customer Responsibilities

Validate business mappings and approve exceptions.

---

# 10. Testing

Mapping must be tested using representative migration data.

---

# 11. Deliverables

- Source-to-Target Mapping
- Value Mapping
- Exception Register

---

# 12. Effort Drivers

Number of fields, objects and transformations.

---

# 13. Acceptance Criteria

All migration mappings are reviewed and approved.

---

# 14. Definition of Done

Mapping is baselined and ready for migration execution.

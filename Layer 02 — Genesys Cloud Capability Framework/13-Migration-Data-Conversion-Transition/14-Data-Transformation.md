# Layer 2.13.14 — Data Transformation

## Capability Definition

Data Transformation converts source data into structures and formats compatible with Genesys Cloud and target integrations.

---

# 1. Scope

- Field conversion
- Value translation
- Format conversion
- Normalisation
- Reference conversion
- Derived values
- Business rules

---

# 2. Classification

**Conditional**

---

# 3. Discovery Activities

Identify source-to-target differences requiring transformation.

---

# 4. Design Activities

Define transformation rules, algorithms, exception handling and validation.

---

# 5. Implementation Activities

| Task ID | Task | Phase | Effort |
|---|---|---|---:|
| 2.13.14-T01 | Identify transformation requirements | Phase 3 | 4h |
| 2.13.14-T02 | Define transformation rules | Phase 4 | 6h |
| 2.13.14-T03 | Implement transformations | Phase 7 | 8h |
| 2.13.14-T04 | Execute transformation test | Phase 8 | 4h |
| 2.13.14-T05 | Resolve transformation defects | Phase 8 | 4h |

---

# 6. Dependencies

- Migration Mapping
- Data Profiling
- Data Cleansing

---

# 7. Layer 1 Mapping

- Phase 3 — Requirements
- Phase 4 — Design
- Phase 7 — Migration
- Phase 8 — Testing

---

# 8. Roles

- Data Engineer
- Data Architect
- Migration Lead

---

# 9. Customer Responsibilities

Approve business transformation rules.

---

# 10. Testing

Validate transformed data against expected target values.

---

# 11. Deliverables

- Transformation Rules
- Transformation Scripts
- Transformation Test Results

---

# 12. Effort Drivers

Complexity of transformation logic and data volume.

---

# 13. Acceptance Criteria

Transformation produces target-compatible data with no unexplained exceptions.

---

# 14. Definition of Done

Transformation logic is tested and approved.


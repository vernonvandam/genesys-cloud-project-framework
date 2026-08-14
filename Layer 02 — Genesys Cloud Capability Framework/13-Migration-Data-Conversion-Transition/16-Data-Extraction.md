# Layer 2.13.16 — Data Extraction

## Capability Definition

Data Extraction provides controlled mechanisms for obtaining migration data from source systems.

---

# 1. Scope

- API extraction
- Database extraction
- File extraction
- Configuration export
- Bulk extraction
- Incremental extraction

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

Identify extraction sources, methods, permissions, volumes and schedules.

---

# 4. Design Activities

Define extraction method, format, security, frequency and validation.

---

# 5. Implementation Activities

| Task ID | Task | Phase | Effort |
|---|---|---|---:|
| 2.13.16-T01 | Confirm source access | Phase 5 | 3h |
| 2.13.16-T02 | Define extraction method | Phase 4 | 4h |
| 2.13.16-T03 | Build extraction process | Phase 7 | 8h |
| 2.13.16-T04 | Execute test extraction | Phase 7 | 4h |
| 2.13.16-T05 | Validate extracted data | Phase 8 | 4h |
| 2.13.16-T06 | Baseline extraction process | Phase 8 | 2h |

---

# 6. Dependencies

- Source System Inventory
- Migration Architecture
- Data Mapping

---

# 7. Layer 1 Mapping

- Phase 5 — Platform Foundation & Environment Build
- Phase 7 — Integration & Data Migration
- Phase 8 — Testing & Validation

---

# 8. Roles

- Data Engineer
- Migration Engineer
- Source System SME

---

# 9. Customer Responsibilities

Provide source access and extraction permissions.

---

# 10. Testing

Validate completeness and integrity of extracted datasets.

---

# 11. Deliverables

- Extraction Process
- Extracted Data
- Extraction Validation Report

---

# 12. Effort Drivers

Source technology, data volume and extraction method.

---

# 13. Acceptance Criteria

Required source data can be reliably extracted.

---

# 14. Definition of Done

Extraction is repeatable, secure and validated.

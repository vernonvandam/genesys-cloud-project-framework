# Layer 2.13.15 — Data Cleansing

## Capability Definition

Data Cleansing removes, corrects or standardises invalid, duplicate, incomplete or obsolete migration data before loading.

---

# 1. Scope

- Duplicates
- Invalid values
- Missing data
- Obsolete data
- Standardisation
- Referential integrity
- Data correction

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

- Profile source data.
- Identify quality issues.
- Identify business-critical defects.
- Identify duplicate records.

---

# 4. Design Activities

- Define cleansing rules.
- Define ownership.
- Define remediation process.
- Define acceptance thresholds.

---

# 5. Implementation Activities

| Task ID | Task | Phase | Effort |
|---|---|---|---:|
| 2.13.15-T01 | Identify cleansing requirements | Phase 2 | 4h |
| 2.13.15-T02 | Define cleansing rules | Phase 3 | 5h |
| 2.13.15-T03 | Execute cleansing | Phase 7 | 8h |
| 2.13.15-T04 | Validate cleansed data | Phase 8 | 4h |
| 2.13.15-T05 | Obtain data-owner acceptance | Phase 8 | 3h |

---

# 6. Dependencies

- Data Profiling
- Data Ownership
- Data Classification

---

# 7. Layer 1 Mapping

- Phase 2 — Discovery
- Phase 3 — Requirements
- Phase 7 — Migration
- Phase 8 — Testing

---

# 8. Roles

- Data Engineer
- Data Owner
- Migration Lead

---

# 9. Customer Responsibilities

Approve cleansing rules and provide data remediation.

---

# 10. Testing

Validate completeness, uniqueness and validity after cleansing.

---

# 11. Deliverables

- Cleansing Rules
- Cleansed Dataset
- Cleansing Report

---

# 12. Effort Drivers

Data quality and volume.

---

# 13. Acceptance Criteria

Data meets agreed quality thresholds.

---

# 14. Definition of Done

Data is clean and approved for migration.

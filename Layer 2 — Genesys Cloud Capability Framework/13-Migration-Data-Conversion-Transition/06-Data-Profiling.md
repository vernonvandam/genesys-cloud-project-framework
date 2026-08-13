# Layer 2.13.06 — Data Profiling

## Capability Definition

Data Profiling assesses the structure, completeness, consistency, uniqueness, validity and quality of migration data.

---

# 1. Scope

- Completeness
- Accuracy
- Consistency
- Uniqueness
- Validity
- Referential integrity
- Null values
- Duplicates
- Invalid values
- Data anomalies

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

- Identify profiling requirements.
- Determine acceptable quality thresholds.
- Identify known data-quality problems.
- Identify business-critical fields.

---

# 4. Design Activities

Define profiling rules, thresholds, exception handling and reporting.

---

# 5. Implementation Activities

| Task ID | Task | Phase | Effort |
|---|---|---|---:|
| 2.13.06-T01 | Define profiling rules | Phase 3 | 4h |
| 2.13.06-T02 | Extract representative datasets | Phase 7 | 4h |
| 2.13.06-T03 | Profile data quality | Phase 7 | 8h |
| 2.13.06-T04 | Identify exceptions | Phase 7 | 6h |
| 2.13.06-T05 | Produce quality report | Phase 7 | 4h |
| 2.13.06-T06 | Obtain business acceptance | Phase 7 | 3h |

---

# 6. Dependencies

- Data Discovery
- Data Classification
- Data Ownership

---

# 7. Layer 1 Mapping

- Phase 2 — Discovery & Current State Assessment
- Phase 3 — Requirements & Solution Definition
- Phase 7 — Integration & Data Migration
- Phase 8 — Testing & Validation

---

# 8. Roles

- Data Architect
- Data Engineer
- Migration Lead
- Data Owner

---

# 9. Customer Responsibilities

Confirm quality thresholds and remediation ownership.

---

# 10. Testing

Validate profiling results against agreed thresholds.

---

# 11. Deliverables

- Data Profiling Report
- Data Quality Exception Register
- Remediation Plan

---

# 12. Effort Drivers

Data volume, number of fields and quality complexity.

---

# 13. Acceptance Criteria

Quality issues are identified and remediation decisions are approved.

---

# 14. Definition of Done

Data quality has been assessed and accepted for migration.

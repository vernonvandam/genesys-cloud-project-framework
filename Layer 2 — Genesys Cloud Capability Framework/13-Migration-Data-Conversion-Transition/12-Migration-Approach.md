# Layer 2.13.12 — Migration Approach

## Capability Definition

Migration Approach defines how individual migration objects and datasets will be moved into Genesys Cloud.

---

# 1. Scope

- Manual migration
- Automated migration
- API migration
- Bulk loading
- Configuration recreation
- Data transformation
- Migration waves

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

Classify migration objects by volume, complexity, risk and available migration mechanisms.

---

# 4. Design Activities

For each object define:

- Migration method
- Migration owner
- Source
- Target
- Transformation
- Validation
- Rollback

---

# 5. Implementation Activities

| Task ID | Task | Phase | Effort |
|---|---|---|---:|
| 2.13.12-T01 | Classify migration methods | Phase 3 | 5h |
| 2.13.12-T02 | Identify automation candidates | Phase 3 | 4h |
| 2.13.12-T03 | Define migration sequencing | Phase 4 | 5h |
| 2.13.12-T04 | Define object-level validation | Phase 4 | 4h |
| 2.13.12-T05 | Baseline migration approach | Phase 4 | 3h |

---

# 6. Dependencies

- Migration Scope
- Migration Architecture
- Migration Mapping

---

# 7. Layer 1 Mapping

- Phase 3 — Requirements
- Phase 4 — Architecture & Design
- Phase 6 — Feature Configuration & Solution Build
- Phase 7 — Integration & Data Migration

---

# 8. Roles

- Migration Lead
- Genesys Cloud Architect
- Data Architect
- Technical Architect

---

# 9. Customer Responsibilities

Approve migration methods and exceptions.

---

# 10. Testing

Validate selected migration methods through mock migration.

---

# 11. Deliverables

- Migration Approach Matrix
- Migration Method Decision Register

---

# 12. Effort Drivers

Object count, migration mechanism and automation complexity.

---

# 13. Acceptance Criteria

Each migration object has a defined migration approach.

---

# 14. Definition of Done

Migration approach is baselined.


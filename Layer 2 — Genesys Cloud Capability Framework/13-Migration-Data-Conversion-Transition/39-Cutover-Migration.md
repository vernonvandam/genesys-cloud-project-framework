# Layer 2.13.39 — Cutover Migration

## Capability Definition

Cutover Migration executes the approved production migration of configuration and data into Genesys Cloud.

---

# 1. Scope

- Final migration preparation
- Data freeze
- Extraction
- Transformation
- Loading
- Validation
- Reconciliation
- Business acceptance

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

Confirm final migration scope and cutover conditions.

---

# 4. Design Activities

Define exact cutover sequence, timing, dependencies and decision points.

---

# 5. Implementation Activities

| Task ID | Task | Phase | Effort |
|---|---|---|---:|
| 2.13.39-T01 | Confirm go/no-go criteria | Phase 9 | 2h |
| 2.13.39-T02 | Execute data freeze where required | Phase 10 | 2h |
| 2.13.39-T03 | Execute final extraction | Phase 10 | 4h |
| 2.13.39-T04 | Execute transformation and load | Phase 10 | 8h |
| 2.13.39-T05 | Execute validation | Phase 10 | 6h |
| 2.13.39-T06 | Obtain business acceptance | Phase 10 | 3h |

---

# 6. Dependencies

- Rehearsal
- Data Freeze
- Delta Migration
- Rollback
- Go-Live Readiness

---

# 7. Layer 1 Mapping

- Phase 9 — Cutover Preparation
- Phase 10 — Production Deployment & Go-Live
- Phase 11 — Hypercare

---

# 8. Roles

- Migration Lead
- Genesys Cloud Engineer
- Data Engineer
- Project Manager
- Business SMEs

---

# 9. Customer Responsibilities

Approve go/no-go and validate migrated business outcomes.

---

# 10. Testing

Execute production validation and reconciliation.

---

# 11. Deliverables

- Migration Execution Record
- Migration Results
- Validation Report

---

# 12. Effort Drivers

Data volume and cutover duration.

---

# 13. Acceptance Criteria

Migration completes and production services are validated.

---

# 14. Definition of Done

Production migration is complete and accepted.


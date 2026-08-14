# 25 — Data & Migration Testing

## Capability Definition

Validates migrated, transformed and synchronised data used by Genesys Cloud and associated systems.

---

# 1. Scope

- User data
- Configuration data
- Historical data
- Interaction data
- Integration data
- Migration data
- Reconciliation

---

# 2. Classification

**Conditional**

---

# 3. Discovery Activities

- Identify migrated datasets.
- Identify source systems.
- Identify mappings.
- Identify transformation rules.
- Identify reconciliation requirements.

---

# 4. Design Activities

- Define data test cases.
- Define reconciliation rules.
- Define completeness checks.
- Define accuracy checks.
- Define transformation validation.

---

# 5. Implementation Activities

```text
Extract source counts
Load target data
Compare record counts
Compare key attributes
Validate transformations
Validate mandatory fields
Validate relationships
Validate migrated configuration
Validate historical data
Record discrepancies
Remediate migration issues
Repeat reconciliation
```

---

# 6. Dependencies

- Migration
- Data
- Integrations
- Test Data

---

# 7. Layer 1 Mapping

Primary:

- Phase 7 — Component & Integration Testing
- Phase 8 — Testing & Validation
- Phase 10 — Production Deployment & Go-Live

---

# 8. Roles

- Migration Lead
- Data Engineer
- Test Analyst
- Business SME

---

# 9. Customer Responsibilities

- Approve mappings.
- Provide source data owners.
- Validate business data.

---

# 10. Testing

Reconcile source and target data and validate business usability.

---

# 11. Deliverables

- Migration Test Cases
- Reconciliation Report
- Data Validation Results

---

# 12. Effort Drivers

- Data volume
- Number of sources
- Transformation complexity
- Historical data
- Reconciliation rules

---

# 13. Acceptance Criteria

- Required data migrated.
- Counts reconcile.
- Transformations correct.
- Business validation complete.

---

# 14. Definition of Done

Migrated data passes agreed validation and reconciliation.

---

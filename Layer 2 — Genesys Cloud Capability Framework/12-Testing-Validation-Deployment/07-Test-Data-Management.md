# 07 — Test Data Management

## Capability Definition

Defines the creation, preparation, protection, refresh and disposal of data required to execute Genesys Cloud testing.

---

# 1. Scope

- Test data requirements
- Synthetic data
- Masked data
- Customer data
- User data
- Interaction data
- Integration data
- Privacy
- Data refresh
- Data disposal

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

- Identify test data requirements.
- Identify sensitive data.
- Identify data owners.
- Identify source systems.
- Identify data volumes.
- Identify test scenarios requiring specific data states.

---

# 4. Design Activities

- Define test data strategy.
- Define synthetic versus production-derived data.
- Define masking.
- Define data refresh.
- Define data retention.
- Define data disposal.

---

# 5. Implementation Activities

```text
Identify test data requirements
Identify sensitive data
Define data ownership
Create synthetic test data
Extract approved source data where required
Mask sensitive information
Load test data
Validate data
Create test-data refresh process
Define data reset process
Define data disposal
Record test-data inventory
```

---

# 6. Dependencies

- Security
- Privacy
- Compliance
- Migration
- Test Cases
- Integration Testing

---

# 7. Layer 1 Mapping

Primary:

- Phase 4 — Solution Architecture & Detailed Design
- Phase 8 — Testing & Validation

---

# 8. Roles

- Test Lead
- Data Engineer
- Security Specialist
- Compliance Specialist
- Business SMEs

---

# 9. Customer Responsibilities

- Approve data usage.
- Provide test data owners.
- Approve masking rules.
- Confirm retention requirements.

---

# 10. Testing

Validate data accuracy, masking, completeness and suitability for test scenarios.

---

# 11. Deliverables

- Test Data Strategy
- Test Data Inventory
- Test Data Sets
- Data Masking Rules
- Data Refresh Procedure

---

# 12. Effort Drivers

- Data volume
- Sensitive data
- Number of integrations
- Number of scenarios
- Data transformation requirements

---

# 13. Acceptance Criteria

- Required data exists.
- Sensitive information is protected.
- Data supports planned scenarios.
- Refresh and disposal procedures exist.

---

# 14. Definition of Done

All required test data is available, protected and approved for use.

---

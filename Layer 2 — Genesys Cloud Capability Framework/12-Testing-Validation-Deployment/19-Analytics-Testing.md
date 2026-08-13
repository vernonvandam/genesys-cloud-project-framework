# 19 — Analytics Testing

## Capability Definition

Validates Genesys Cloud analytics data, metrics, filters, views and analytical outcomes.

---

# 1. Scope

- Conversation analytics
- Queue analytics
- Agent analytics
- Performance metrics
- Historical analytics
- Real-time analytics
- Filters
- Dimensions

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

- Identify required metrics.
- Identify source data.
- Identify business definitions.
- Identify reporting consumers.

---

# 4. Design Activities

- Define expected metrics.
- Define test datasets.
- Define calculation validation.
- Define filter validation.
- Define time-zone validation.

---

# 5. Implementation Activities

```text
Generate known interactions
Validate interaction records
Validate queue metrics
Validate agent metrics
Validate service level
Validate abandonment
Validate handle time
Validate filters
Validate date ranges
Validate time zones
Compare expected and actual results
Record discrepancies
```

---

# 6. Dependencies

- Analytics
- ACD
- Routing
- Voice
- Digital
- Reporting

---

# 7. Layer 1 Mapping

Primary:

- Phase 8 — Testing & Validation

Supporting:

- Phase 7 — Component & Integration Testing

---

# 8. Roles

- Analytics Specialist
- Test Analyst
- Genesys Cloud Architect
- Business Analyst

---

# 9. Customer Responsibilities

- Define metric expectations.
- Validate business calculations.
- Approve analytical outcomes.

---

# 10. Testing

Use controlled interactions to validate analytical calculations.

---

# 11. Deliverables

- Analytics Test Cases
- Metric Validation
- Analytics Reconciliation

---

# 12. Effort Drivers

- Number of metrics
- Reporting complexity
- Number of queues
- Number of channels
- Data integrations

---

# 13. Acceptance Criteria

- Required metrics available.
- Calculations accurate.
- Filters operate.
- Data aligns with expectations.

---

# 14. Definition of Done

Analytics outputs are validated and accepted.

---
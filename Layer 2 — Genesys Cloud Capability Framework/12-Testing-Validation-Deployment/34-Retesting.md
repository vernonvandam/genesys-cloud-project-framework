# 34 — Retesting

## Capability Definition

Validates that previously failed test cases pass following defect remediation or configuration changes.

---

# 1. Scope

- Failed test cases
- Defect fixes
- Configuration changes
- Integration fixes
- Retest evidence

---

# 2. Classification

**Required**

---

# 3. Discovery Activities

- Identify failed tests.
- Identify associated defects.
- Identify remediation status.
- Confirm test environment readiness.

---

# 4. Design Activities

- Define retest cases.
- Define expected outcomes.
- Define evidence requirements.

---

# 5. Implementation Activities

```text
Review failed test
Confirm defect remediation
Prepare environment
Execute failed scenario
Validate corrected behaviour
Capture evidence
Update defect
Close or reopen defect
Identify regression impact
```

---

# 6. Dependencies

- Defect Management
- Unit Testing
- Integration Testing
- Regression Testing

---

# 7. Layer 1 Mapping

Primary:

- Phase 8 — Testing & Validation

---

# 8. Roles

- Test Analyst
- Engineer
- Test Lead

---

# 9. Customer Responsibilities

- Validate business defects.
- Confirm acceptance.

---

# 10. Testing

Retesting shall reproduce the original failure condition wherever practical.

---

# 11. Deliverables

- Retest Results
- Updated Defects
- Evidence

---

# 12. Effort Drivers

- Defect volume
- Retest complexity
- Environment availability

---

# 13. Acceptance Criteria

- Failed scenarios re-executed.
- Expected result achieved.
- Evidence recorded.

---

# 14. Definition of Done

All applicable defects have passed retesting or have an approved disposition.

---
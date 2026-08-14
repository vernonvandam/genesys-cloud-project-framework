# Layer 10 — Acceptance Criteria Standard

## Purpose

This document defines the standard for task acceptance criteria.

---

# 1. Purpose of Acceptance Criteria

Acceptance criteria establish the objective conditions under which a task is considered complete.

They provide the link between:

```text
Task
  ↓
Expected Outcome
  ↓
Verification
  ↓
Acceptance
```

---

# 2. Acceptance Criteria Requirements

Acceptance criteria must be:

- specific
- measurable
- observable
- testable
- relevant
- unambiguous

---

# 3. Acceptance Criteria Format

Where practical, use statements such as:

```text
The configured capability has been implemented according to the approved
design and successfully validated against the defined acceptance criteria.
```

Where more detail is required, list individual criteria.

---

# 4. Good Acceptance Criteria

Example:

```text
- Queue exists with the approved name.
- Required members are assigned.
- Routing configuration matches the approved design.
- Test interactions route to the intended queue.
- No configuration errors are present.
```

---

# 5. Poor Acceptance Criteria

Avoid:

```text
Queue configured correctly.
```

This is insufficiently objective.

---

# 6. Acceptance Evidence

Where applicable, acceptance evidence may include:

- screenshots
- test results
- logs
- configuration exports
- API responses
- reports
- signed approvals
- test scripts
- reconciliation results
- deployment records

---

# 7. Customer Acceptance

Where the customer is responsible for acceptance, this must be represented separately from technical validation.

Technical completion does not automatically equal customer acceptance.

---

# 8. Failed Acceptance

If acceptance criteria are not met:

1. task remains incomplete
2. defect or remediation activity is recorded
3. required remediation is performed
4. validation is repeated
5. acceptance is re-evaluated

---

# 9. Acceptance Criteria and Definition of Done

Acceptance criteria must be satisfied before a task is marked complete.

A task may not be considered complete solely because configuration work has been performed.

---

# 10. Definition of Done

Acceptance criteria are compliant when:

- they define the intended outcome
- they are objectively testable
- they can be evidenced
- they identify material completion conditions
- they support technical or business acceptance
- they do not simply repeat the task name
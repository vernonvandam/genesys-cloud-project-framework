# Layer 10 — Customer Responsibility Standard

## Purpose

This document defines how customer responsibility is represented within implementation tasks.

---

# 1. Responsibility Categories

Each task must identify one of:

```text
YES
NO
JOINT
```

---

# 2. YES

`YES` indicates that the customer has a material responsibility for completing the task.

Examples:

- customer provides source data
- customer performs business configuration
- customer provides required credentials
- customer approves design
- customer executes business acceptance

---

# 3. NO

`NO` indicates that the task is performed entirely by the delivery team, with no material customer execution responsibility.

The customer may still provide routine access or information.

---

# 4. JOINT

`JOINT` indicates that successful completion requires material work by both delivery and customer teams.

Examples:

- UAT
- production readiness
- migration validation
- business acceptance
- operational handover
- cutover

---

# 5. Customer Inputs

Where customer responsibility exists, the task should identify the expected customer input.

Examples:

- approved requirements
- source data
- access
- business rules
- test users
- acceptance
- change approval

---

# 6. Customer Responsibility and Effort

Customer responsibility does not automatically mean that customer effort must be included in delivery team effort.

The estimation model must distinguish:

```text
Delivery Effort
Customer Effort
Total Project Effort
```

---

# 7. Customer Dependencies

Customer responsibilities that can delay delivery must also be represented as dependencies.

Example:

```text
Customer provides production certificates
        ↓
Integration configuration
        ↓
Integration testing
```

---

# 8. Responsibility Principle

A task should not be classified as `NO` merely because the delivery team performs the technical work if customer approval is required to complete it.

---

# 9. Definition of Done

Customer responsibility is complete when:

- responsibility classification is defined
- material customer actions are documented
- customer dependencies are identified
- customer effort is distinguishable from delivery effort
- approval responsibilities are explicit
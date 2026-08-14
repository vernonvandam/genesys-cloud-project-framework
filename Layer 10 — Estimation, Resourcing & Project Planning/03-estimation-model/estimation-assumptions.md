# Layer 10 — Estimation Assumptions

## Purpose

This document defines the standard assumptions governing baseline estimation.

Assumptions provide the boundary conditions under which the baseline estimates are considered valid.

---

# 1. General Assumptions

Baseline estimates assume:

- scope is sufficiently defined
- standard Genesys Cloud capabilities are used
- approved requirements are available
- customer stakeholders are available when required
- required environments exist
- required access is available
- required information is provided in a timely manner
- implementation follows approved architecture
- standard implementation patterns are used

---

# 2. Configuration Assumptions

Baseline estimates generally assume:

- standard configuration
- supported Genesys Cloud capabilities
- no undocumented customisation
- standard administrative processes
- normal configuration complexity

---

# 3. Integration Assumptions

Unless explicitly identified otherwise, estimates assume:

- integration endpoints are available
- APIs are documented
- credentials are provided
- required network connectivity exists
- third-party systems are accessible
- integration requirements are known

---

# 4. Data Assumptions

Data-related estimates assume:

- source data can be extracted
- source data is accessible
- data ownership is defined
- required data structures are understood
- major data quality issues are identified during discovery

Extensive data cleansing may require additional effort.

---

# 5. Migration Assumptions

Migration estimates assume:

- migration scope is defined
- source systems are known
- migration volumes are available
- mappings can be established
- migration windows are agreed
- required source extracts can be generated

Complex coexistence or rollback requirements may materially change the estimate.

---

# 6. Customer Assumptions

The customer is assumed to provide:

- timely decisions
- business SMEs
- data owners
- required approvals
- required access
- source information
- test participants
- acceptance decisions

Customer delays are schedule impacts and are not automatically delivery effort.

---

# 7. Environment Assumptions

Baseline estimates assume:

- required environments are available
- appropriate access is available
- deployment mechanisms are available
- test environments are sufficiently representative

---

# 8. Security Assumptions

Baseline estimates assume standard security controls.

Additional effort may apply for:

- highly regulated environments
- specialised security architecture
- extensive audit requirements
- unusual identity requirements
- custom security controls

---

# 9. Testing Assumptions

Baseline estimates assume standard testing activities.

Additional effort may apply for:

- extensive regression testing
- performance testing
- complex migration testing
- large UAT populations
- extensive defect remediation

---

# 10. Estimate Exclusions

Unless explicitly included, baseline estimates exclude:

- major scope changes
- extensive custom development
- customer delays
- third-party delays
- major defect remediation
- undocumented requirements
- contingency
- unrelated project management overhead
- post-go-live optimisation beyond defined tasks

---

# 11. Assumption Review

Assumptions must be reviewed when:

- scope changes
- architecture changes
- volumes change
- customer responsibilities change
- integration requirements change
- migration scope changes
- regulatory requirements change
- delivery constraints change

---

# 12. Assumption Impact

When an assumption is invalidated, the project estimate should be reassessed.

The original baseline should not be silently overwritten.

---

# 13. Definition of Done

Estimation assumptions are complete when:

- baseline boundaries are documented
- exclusions are understood
- customer assumptions are explicit
- technical assumptions are explicit
- migration assumptions are explicit
- invalid assumptions can trigger estimate review
# Layer 2.01.15 — Storage & Retention

## Capability Definition

Defines storage, retention and data lifecycle requirements for Genesys Cloud information.

---

# 1. Scope

Potential data categories include:

- Interaction recordings
- Screen recordings
- Digital interaction data
- Analytics data
- Audit information
- Configuration information
- Customer data
- User information
- Exported data
- Integration data

Specific retention capabilities and limits must be validated against the current Genesys Cloud product, licence and contractual model.

---

# 2. Classification

**Conditional**

The complexity is driven by recording, compliance, regulatory and data requirements.

---

# 3. Discovery

Determine:

- Required retention periods.
- Data categories.
- Regulatory requirements.
- Legal hold requirements.
- Deletion requirements.
- Data export requirements.
- Storage requirements.
- Customer ownership.
- Integration destinations.

---

# 4. Design

- Define data categories.
- Define retention periods.
- Identify platform-supported retention.
- Identify external storage requirements.
- Define deletion process.
- Define access controls.
- Define evidence requirements.

---

# 5. Implementation

```text
Identify data types
Define retention requirements
Validate platform capability
Configure applicable policies
Validate storage behaviour
Validate deletion behaviour
Document retention model
```

---

# 6. Dependencies

- Security
- Compliance
- Recording
- Analytics
- Integration
- Data migration

---

# 7. Testing

Validate:

- Data is retained according to requirements.
- Access is restricted appropriately.
- Deletion behaves as designed.
- Required data can be retrieved.
- External exports operate where required.

---

# 8. Acceptance Criteria

The approved data retention model is implemented and validated.

---

# 9. Definition of Done

Storage and retention requirements have been implemented, tested, documented and accepted.

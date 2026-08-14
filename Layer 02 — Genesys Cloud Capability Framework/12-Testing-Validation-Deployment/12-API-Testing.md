# 12 — API Testing

## Capability Definition

Validates Genesys Cloud APIs, custom APIs and API-based integrations for functionality, authentication, authorisation, data integrity, error handling and operational behaviour.

---

# 1. Scope

- Genesys Cloud APIs
- OAuth
- API clients
- Custom APIs
- API gateways
- Rate limits
- Error handling
- Data validation

---

# 2. Classification

**Conditional**

---

# 3. Discovery Activities

- Identify APIs.
- Identify API consumers.
- Identify OAuth clients.
- Identify scopes.
- Identify rate limits.
- Identify error conditions.

---

# 4. Design Activities

- Define API test cases.
- Define authentication tests.
- Define authorisation tests.
- Define payload validation.
- Define negative testing.
- Define rate-limit testing where required.

---

# 5. Implementation Activities

```text
Validate OAuth authentication
Validate required scopes
Execute API requests
Validate response codes
Validate response payloads
Validate data mapping
Validate invalid requests
Validate unauthorised requests
Validate expired credentials
Validate error handling
Validate rate-limit handling
Capture API test evidence
```

---

# 6. Dependencies

- API Architecture
- OAuth
- Integration Testing
- Security
- Test Data

---

# 7. Layer 1 Mapping

Primary:

- Phase 7 — Component & Integration Testing
- Phase 8 — Testing & Validation

---

# 8. Roles

- Integration Engineer
- API Developer
- Genesys Cloud Engineer
- Security Specialist

---

# 9. Customer Responsibilities

- Provide API test requirements.
- Provide external API owners.
- Approve security scope.

---

# 10. Testing

Validate functional and non-functional API behaviour.

---

# 11. Deliverables

- API Test Cases
- API Test Results
- API Evidence
- Defect Records

---

# 12. Effort Drivers

- API count
- API complexity
- OAuth complexity
- Number of consumers
- Rate-limit requirements

---

# 13. Acceptance Criteria

- Required APIs tested.
- Authentication validated.
- Authorisation validated.
- Error behaviour validated.
- Data integrity validated.

---

# 14. Definition of Done

All in-scope API integrations pass API testing.

---

# Layer 2.02.03 — User Provisioning & Deprovisioning

## 1. Purpose

Define how users are created, updated and removed from Genesys Cloud.

## 2. Classification

**Required**

## 3. Discovery

Determine:

- Manual or automated provisioning.
- Source attributes.
- Username/email convention.
- User naming.
- Role assignment.
- Division assignment.
- Licence assignment.
- Deactivation process.
- Deletion requirements.

## 4. Implementation

```text
Define user attributes
Define source mapping
Configure provisioning
Create test users
Validate attributes
Validate roles
Validate divisions
Validate licences
Test deactivation
Test termination
```

## 5. Dependencies

- Identity architecture
- SCIM where applicable
- Groups
- Roles
- Divisions
- Licensing

## 6. Testing

Must include:

- Create.
- Update.
- Role change.
- Division change.
- Licence change.
- Deactivate.
- Re-enable where permitted.
- Terminate.

## 7. Deliverables

- Provisioning design
- Attribute mapping
- Provisioning configuration
- Test evidence
- Runbook

## 8. Risks

- Incorrect attribute mapping.
- Users receive excessive access.
- Deprovisioning does not occur.
- Licence assignments become stale.

## 9. Acceptance Criteria

Users are correctly provisioned and deprovisioned according to approved lifecycle rules.

## 10. Definition of Done

Provisioning and deprovisioning operate successfully across all agreed lifecycle scenarios.

# Layer 2.02.06 — SCIM & Automated Provisioning

## 1. Purpose

Define automated user lifecycle integration using SCIM where supported and selected.

## 2. Classification

**Conditional**

## 3. Discovery

Determine:

- Identity provider.
- SCIM support.
- Required attributes.
- Group mappings.
- User mappings.
- Provisioning scope.
- Deprovisioning behaviour.
- Licence assignment.
- Role assignment.
- Division assignment.

## 4. Design

Document:

- Attribute mapping.
- User lifecycle.
- Group mapping.
- Provisioning authority.
- Error handling.
- Monitoring.
- Reconciliation.
- Manual exception process.

## 5. Implementation

```text
Configure SCIM
Map attributes
Map groups
Provision test user
Validate updates
Validate access changes
Test deprovisioning
Test error handling
Document operational support
```

## 6. Testing

Mandatory scenarios:

- Create user.
- Modify user.
- Group change.
- Role/access change.
- Disable user.
- Deprovision user.
- Reprovision where supported.

## 7. Risks

- Attribute mismatch.
- Incorrect group assignment.
- Failed deprovisioning.
- Duplicate identities.

## 8. Acceptance Criteria

Automated provisioning operates according to approved identity lifecycle rules.

## 9. Definition of Done

SCIM is configured, validated and operationally supported where selected.

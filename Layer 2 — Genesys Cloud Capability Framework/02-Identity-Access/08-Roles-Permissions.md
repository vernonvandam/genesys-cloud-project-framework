# Layer 2.02.08 — Roles & Permissions

## 1. Purpose

Define the Genesys Cloud role and permission model.

## 2. Classification

**Required**

## 3. Discovery

Determine:

- User personas.
- Agent permissions.
- Supervisor permissions.
- WFM permissions.
- QM permissions.
- Reporting permissions.
- Architect permissions.
- Integration permissions.
- Administrator permissions.
- Security permissions.

## 4. Design

Create a permission matrix:

| Persona | Role | Permissions | Division Scope | Environment |
|---|---|---|---|---|
| Agent | Approved role | Required only | Applicable | All |
| Supervisor | Approved role | Required only | Applicable | All |
| Administrator | Restricted | Elevated | Defined | Restricted |
| Integration | API permissions | Minimal | Defined | Defined |

## 5. Implementation

```text
Define personas
Map personas to roles
Review permissions
Remove unnecessary permissions
Configure roles
Assign users/groups
Validate effective access
```

## 6. Security Principle

**Least privilege is mandatory.**

Do not assign administrative permissions merely because a user requires access to a feature.

## 7. Testing

Test:

- Positive access.
- Negative access.
- Cross-division access.
- Administrative access.
- Agent access.
- Supervisor access.
- Reporting access.

## 8. Acceptance Criteria

Users receive exactly the access required for their approved persona.

## 9. Definition of Done

Role and permission design is approved, implemented and validated.

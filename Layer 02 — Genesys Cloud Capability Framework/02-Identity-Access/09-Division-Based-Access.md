# Layer 2.02.09 — Division-Based Access

## 1. Purpose

Define how divisions are used to constrain access to Genesys Cloud resources.

## 2. Classification

**Required**

## 3. Discovery

Determine:

- Division model.
- Resource ownership.
- Administrative boundaries.
- Geographic boundaries.
- Business-unit boundaries.
- Reporting requirements.

## 4. Design

Map:

```text
User / Group
     ↓
Role
     ↓
Permission
     ↓
Division
     ↓
Resource
```

## 5. Implementation

- Map resources.
- Map users/groups.
- Assign appropriate division access.
- Validate administrator boundaries.
- Test cross-division access.

## 6. Risks

- Users access resources outside their responsibility.
- Administrators cannot support required resources.
- Excessive division complexity.

## 7. Acceptance Criteria

Division access matches the approved security model.

## 8. Definition of Done

Division-based authorisation is implemented and validated.

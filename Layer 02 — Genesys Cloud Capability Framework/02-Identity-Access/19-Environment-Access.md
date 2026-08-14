# Layer 2.02.19 — Environment Access

## 1. Purpose

Define identity and access controls across development, test, UAT and production environments.

## 2. Classification

**Required**

## 3. Discovery

Determine:

- Environment model.
- User groups.
- Development access.
- Test access.
- UAT access.
- Production access.
- Administrator access.
- Customer access.
- Vendor access.

## 4. Design

Create an access matrix:

| Persona | DEV | TEST | UAT | PROD |
|---|---:|---:|---:|---:|
| Developer | Yes | Yes | Limited | No/Controlled |
| Tester | Yes | Yes | Yes | No |
| Customer UAT | No | Limited | Yes | No |
| Operations | Limited | Limited | Yes | Yes |
| Administrator | Yes | Yes | Yes | Restricted |

The actual model must be tailored to the customer's governance.

## 5. Implementation

- Configure environment access.
- Assign groups.
- Apply roles.
- Validate separation.
- Test privileged production access.
- Document access matrix.

## 6. Acceptance Criteria

Environment access matches approved security and release-management policies.

## 7. Definition of Done

Environment access is implemented and validated.

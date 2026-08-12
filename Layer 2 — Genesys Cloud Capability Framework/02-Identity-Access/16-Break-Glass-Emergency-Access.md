# Layer 2.02.16 — Break-Glass & Emergency Access

## 1. Purpose

Provide controlled emergency administrative access when normal authentication or identity-management processes are unavailable.

## 2. Classification

**Conditional**

Required where customer security governance mandates emergency access.

## 3. Discovery

Determine:

- Emergency scenarios.
- Emergency identity owner.
- Storage method.
- Authentication.
- Approval.
- Monitoring.
- Notification.
- Review.
- Recovery.

## 4. Design

Define:

```text
Emergency
   ↓
Authorisation
   ↓
Access
   ↓
Action
   ↓
Audit
   ↓
Notification
   ↓
Review
   ↓
Credential Rotation
```

## 5. Testing

Conduct controlled emergency-access testing.

Validate:

- Access works.
- Access is restricted.
- Actions are audited.
- Notifications occur.
- Credentials can be rotated.

## 6. Risks

- Emergency account unavailable.
- Credentials compromised.
- Emergency access becomes permanent privileged access.

## 7. Acceptance Criteria

Emergency access is available when required, tightly controlled and auditable.

## 8. Definition of Done

Break-glass procedures are documented, tested and approved.

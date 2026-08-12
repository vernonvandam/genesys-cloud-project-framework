# Layer 2.02.04 — SSO & Identity Federation

## 1. Purpose

Define federated authentication between the customer identity provider and Genesys Cloud where supported and required.

## 2. Classification

**Conditional**

## 3. Discovery

Determine:

- Identity provider.
- Federation protocol.
- Metadata exchange.
- Certificate lifecycle.
- Domain configuration.
- Login behaviour.
- Logout requirements.
- MFA handling.
- Conditional access.
- Failover requirements.

## 4. Design

- Define IdP ownership.
- Define federation configuration.
- Define certificate management.
- Define user matching.
- Define login flow.
- Define failure handling.
- Define support model.

## 5. Implementation

1. Obtain IdP requirements.
2. Configure federation.
3. Exchange required metadata.
4. Configure domains/settings as required.
5. Test standard authentication.
6. Test invalid authentication.
7. Test MFA.
8. Test expired/invalid certificate scenarios where applicable.
9. Test administrator authentication.
10. Document support procedure.

## 6. Dependencies

- Customer IdP
- Authentication policy
- MFA
- User provisioning
- DNS/domain ownership where required

## 7. Layer 1 Mapping

- Phase 4 — Architecture
- Phase 5 — Foundation
- Phase 8 — Testing

## 8. Risks

- Federation outage.
- Certificate expiration.
- Incorrect claims.
- User matching failures.
- SSO dependency not tested before production.

## 9. Acceptance Criteria

Authorised users can authenticate using the approved identity provider and unauthorised users cannot.

## 10. Definition of Done

SSO is configured, tested, documented and supported by an agreed operational process.

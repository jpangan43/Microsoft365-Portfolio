# MFA Deployment Plan

## Deployment sequence

1. Confirm tenant licensing and current authentication protections.
2. Select the supported enforcement approach: Security Defaults or Conditional Access, as appropriate. These approaches are not interchangeable and may not be independently enabled together.
3. Define a pilot group and document the expected sign-in experience.
4. Confirm emergency-access arrangements and recovery procedures before policy changes.
5. Configure approved authentication methods and registration requirements.
6. If using Conditional Access, test with a pilot and use Report-only where appropriate before enforcing.
7. Validate standard-user and administrator sign-ins.
8. Review sign-in logs and address unexpected results.
9. Expand scope only after successful testing and approval.
10. Document exceptions and review them regularly.

## Test scenarios

- New user completes required registration.
- Registered user is challenged according to the intended policy.
- User who loses a method follows the documented recovery process.
- Privileged accounts receive the intended stronger protection.
- Policy does not unintentionally lock out legitimate users.

**Caution:** Never change production authentication policy without an approved change plan and a tested recovery path.

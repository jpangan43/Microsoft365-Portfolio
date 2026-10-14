# MFA Deployment Plan

## Goal
Require strong authentication for users and administrators, using a controlled rollout.

## Procedure
1. Review current authentication methods and tenant security settings.
2. Confirm licensing and determine whether Security Defaults or Conditional Access is the appropriate approach.
3. Create a pilot group with test accounts.
4. Communicate the change and registration steps to test users.
5. Configure the selected policy approach. If using Conditional Access, begin in Report-only where supported.
6. Validate sign-in logs and expected MFA behavior.
7. Resolve unexpected prompts or exclusions before broad rollout.
8. Enable for a wider group in stages, with a documented rollback/recovery procedure.

## Test record

| Test | Expected behavior | Actual result | Evidence |
|---|---|---|---|
| Pilot user sign-in | MFA enforced as configured | Not tested | Add evidence |
| Admin sign-in | Strong authentication enforced | Not tested | Add evidence |
| Recovery scenario | Authorized recovery process works | Not tested | Restricted notes only |

## Notes
- Do not enable Security Defaults and Conditional Access together without checking the supported configuration and Microsoft guidance.
- Authentication behavior can depend on authentication strength, session settings, app, device, and licensing.

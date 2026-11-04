# Self-Service Password Reset (SSPR)

## Configuration procedure

1. Review current Microsoft SSPR requirements and tenant licensing.
2. Navigate to **Identity → Protection → Password reset** in Entra, if available.
3. Configure the intended user scope, starting with a pilot group where supported.
4. Configure permitted verification methods and required method count according to policy.
5. Configure notifications where available.
6. For cloud-only identities, assess the cloud password-reset workflow. For hybrid environments, configure password writeback only when required and supported.
7. Save the configuration.
8. Test with a designated test account using Microsoft's password reset experience.
9. Verify successful reset, subsequent sign-in, and relevant audit or notification events.
10. Record results and support fallback steps.

## Test scenarios

- Enrolled user completes verification and resets the password.
- Unregistered user follows the intended registration or help-desk path.
- Help desk verifies identity before manually resetting a password.
- Hybrid password writeback is tested only if the lab actually uses a supported hybrid setup.

Reference: [SSPR overview](https://learn.microsoft.com/en-us/entra/identity/authentication/concept-sspr-howitworks).

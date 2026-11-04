# Create Users

## Before you begin

- Confirm the request is approved and the account is for a fictional lab identity or authorized user.
- Confirm the correct verified domain and naming convention.
- Confirm licensing, department, manager, and access requirements.
- Never record passwords in this repository.

## Portal procedure

1. Sign in to the [Microsoft Entra admin center](https://entra.microsoft.com/).
2. Go to **Identity → Users → All users**.
3. Select **New user** and choose the appropriate create-user workflow.
4. Enter the display name and user principal name (UPN).
5. Populate department and other attributes needed by access policies or dynamic groups.
6. Set the initial sign-in process according to organizational policy.
7. Assign usage location if required for licensing.
8. Assign the approved license through the supported Microsoft 365 licensing workflow.
9. Add the user to approved assigned security groups.
10. Verify the user object, attributes, group memberships, and license.
11. Record the result in the test log.

## Validation

- User appears in the directory.
- UPN and attributes are correct.
- Only approved groups and licenses are assigned.
- Sign-in and authentication requirements are tested with a test account.

## Evidence

Capture a sanitized user record and test result. Do not expose credentials, personal data, or tenant details that should remain private.

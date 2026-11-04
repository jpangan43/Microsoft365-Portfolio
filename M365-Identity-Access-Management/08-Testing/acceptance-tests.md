# Acceptance Test Plan

Fill in actual results only after performing the tests. Use synthetic accounts and authorized resources.

| Test ID | Scenario | Expected result | Actual result | Status | Evidence |
|---|---|---|---|---|---|
| IAM-01 | Create a standard user | Correct user and attributes exist | | Not run | |
| IAM-02 | Add user to assigned group | Membership is correct | | Not run | |
| IAM-03 | Update attribute used by dynamic group | Membership recalculates as expected | | Not run | |
| IAM-04 | Test delegated admin role | Only authorized actions are permitted | | Not run | |
| IAM-05 | Sign in with MFA requirements | Intended authentication is enforced | | Not run | |
| IAM-06 | Complete SSPR | Password reset succeeds after verification | | Not run | |
| IAM-07 | Invite guest | Guest reaches approved resource | | Not run | |
| IAM-08 | Test guest resource boundary | Unapproved access is denied | | Not run | |
| IAM-09 | Complete access review | Decision and outcome are recorded | | Not run | |
| IAM-10 | Onboard employee | Approved account/access is provisioned | | Not run | |
| IAM-11 | Offboard employee | Sign-in is blocked and access is addressed | | Not run | |
| IAM-12 | Review audit evidence | Relevant activity is available where supported | | Not run | |

## Per-test record

For each test, capture: test ID, date, tester, preconditions, steps, expected result, actual result, pass/fail, evidence filename, and remediation required.

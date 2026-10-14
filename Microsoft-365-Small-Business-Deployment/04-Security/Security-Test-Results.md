# Security Test Results

Do not mark a test PASS until you have run it and captured evidence.

| Test ID | Scenario | Expected result | Actual result | Status | Evidence |
|---|---|---|---|---|---|
| SEC-001 | Pilot user authentication | Matches configured MFA policy | Not tested | Not tested | |
| SEC-002 | Privileged user sign-in | Matches admin policy | Not tested | Not tested | |
| SEC-003 | Legacy authentication attempt | Blocked if policy applies | Not tested | Not tested | |
| SEC-004 | Unauthorized access to restricted site | Access denied | Not tested | Not tested | |
| SEC-005 | Emergency access procedure | Recovery process works | Not tested | Not tested | Restricted evidence only |
| SEC-006 | Policy evaluation | Sign-in logs match intended result | Not tested | Not tested | |

## Findings and remediation
Document each finding with severity, impact, evidence reference, recommended fix, owner, and due date. Do not include secrets or sensitive sign-in details in the public repository.

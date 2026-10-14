# Group Design

Prefer group-based assignment for access and policy scope where supported. Document why each group exists and who owns it.

| Group | Suggested type | Purpose |
|---|---|---|
| `SG-Employees` | Security | Broad employee targeting where appropriate |
| `SG-Management` | Security | Management access assignments |
| `SG-Finance` | Security | Finance site/access assignments |
| `SG-HR` | Security | HR site/access assignments |
| `SG-Sales` | Security | Sales resources |
| `SG-Operations` | Security | Operations resources |
| `SG-Marketing` | Security | Marketing resources |
| `SG-IT` | Security | IT resources |
| `SG-MFA-Pilot` | Security | Controlled policy testing |
| `SG-CA-Exclusions-Review` | Security | Optional tracking group only; exclusions must be tightly governed |

## Procedure
1. Confirm the business purpose and owner of each group.
2. Create the group in Entra ID.
3. Select assigned or dynamic membership only after checking feature/licensing requirements.
4. Add pilot users and verify membership.
5. Use the group for the intended resource or policy.
6. Review membership periodically and at employee transfer/termination.

Do not use a broad group as a substitute for a permission review.

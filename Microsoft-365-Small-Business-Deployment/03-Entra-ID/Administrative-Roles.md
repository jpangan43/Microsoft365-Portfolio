# Administrative Role Matrix

Assign built-in roles only when their permissions match the task. Prefer least privilege and time-bound elevation where available.

| Role / account | Intended purpose | Notes |
|---|---|---|
| Global Administrator | Emergency or exceptional tenant-wide tasks | Minimize count; not for daily work |
| User Administrator | User and group lifecycle tasks within role limits | Verify exact role permissions |
| Exchange Administrator | Exchange configuration | Separate from routine user account |
| SharePoint Administrator | SharePoint administration | Separate from routine user account |
| Security Administrator | Security configuration | Use only for approved duties |
| Reports Reader / equivalent | Read-only review where sufficient | Prefer read-only for audit tasks |

## Procedure
1. Identify the exact task and minimum role required using current Microsoft role documentation.
2. Create a separate admin identity where appropriate.
3. Assign the role through the supported admin center.
4. Verify the role assignment and test only the approved task.
5. Record the approver, scope, date, and review/expiry date if applicable.
6. Review assignments periodically and remove unnecessary privileges.

Never make every IT user a Global Administrator. Role names and capabilities may vary by workload and change over time.

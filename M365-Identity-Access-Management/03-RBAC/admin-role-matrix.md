# Administrative Role Matrix

Assign roles only after reviewing current Microsoft role permissions and the business need. The examples below are design guidance, not instructions to grant all roles.

| Role | Potential duty | Assignment principle |
|---|---|---|
| Global Administrator | Tenant-wide administration | Very limited, protected assignment |
| User Administrator | Manage user accounts | Use only for required user-management tasks |
| Groups Administrator | Manage groups | Limit to group-management duties |
| Authentication Administrator | Manage authentication methods for supported accounts | Carefully review scope and restrictions |
| Exchange Administrator | Exchange Online administration | Assign only if required |
| SharePoint Administrator | SharePoint administration | Assign only if required |

## Assignment procedure

1. Identify the task that needs privileged access.
2. Review Microsoft's current role permissions.
3. Choose the narrowest role that supports the task.
4. Use a dedicated privileged account rather than a daily-use account where practical.
5. Assign the role through the Entra role-management interface or approved process.
6. Verify the assignment and test only authorized actions.
7. Record approver, assignee, justification, start/end or review date, and evidence.
8. Review assignments periodically and remove unnecessary privileges.

Reference: [Microsoft Entra built-in roles](https://learn.microsoft.com/en-us/entra/identity/role-based-access-control/permissions-reference).

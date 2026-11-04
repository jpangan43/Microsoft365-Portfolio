# Group Design

## Naming convention

- Assigned security groups: `SG-<Department>` (example: `SG-Finance`).
- Dynamic groups: `DG-<Population>-<Purpose>` (example: `DG-Users-Operations`).
- Guest groups: `SG-Guests-<ProjectOrPurpose>`.
- Role-assignable groups should be created only when required, with the appropriate role-assignable configuration and governance.

## Department group plan

| Department | Example users | Group | Suggested membership |
|---|---:|---|---|
| Management | 3 | `SG-Management` | Assigned |
| IT | 3 | `SG-IT` | Assigned |
| Sales | 8 | `SG-Sales` | Assigned |
| Operations | 10 | `SG-Operations` | Assigned |
| Finance | 6 | `SG-Finance` | Assigned |

Total example users: **30**.

## Design guidance

1. Use assigned membership for groups whose membership is approved manually.
2. Use dynamic membership only where attributes are reliably populated and the required licensing is available.
3. Document the business purpose, owner, approver, and target resources for every group.
4. A group does not grant access by itself; assign it to the appropriate resource or application.
5. Avoid using department membership alone to grant privileged access.

# Assigned Security Groups

## Create a group

1. Open the Entra admin center and navigate to **Identity → Groups → All groups**.
2. Select **New group**.
3. Choose **Security** as the group type.
4. Select **Assigned** membership.
5. Enter the group name, such as `SG-Finance`, and a clear description.
6. Add approved test users.
7. Create the group and verify its members.
8. Record the owner, approver, purpose, and resources to which the group is assigned.

## Initial groups

`SG-Management`, `SG-IT`, `SG-Sales`, `SG-Operations`, and `SG-Finance`.

## Validation

- Membership matches the approved inventory.
- Test access works only for intended resources.
- Removing a user from the group removes group-based access where that resource supports group-based authorization.

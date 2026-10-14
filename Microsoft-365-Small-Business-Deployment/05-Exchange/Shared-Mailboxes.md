# Shared Mailbox Runbook

## Example use cases
- `info@<your-domain>`
- `sales@<your-domain>`
- `support@<your-domain>`

## Procedure
1. Confirm the business owner, purpose, and required users.
2. Create the shared mailbox in Exchange admin center.
3. Assign only approved Full Access, Send As, or Send on Behalf permissions.
4. Confirm the users have the required licenses and mailbox access prerequisites.
5. Test access and sending behavior using an approved test account.
6. Document ownership and review permissions periodically.

## Permission matrix

| Shared mailbox | Full Access | Send As | Owner |
|---|---|---|---|
| Info | Approved support group | Approved delegates | Operations |
| Sales | Approved sales group | Sales delegates | Sales manager |

## Offboarding
Remove departing users' access promptly and confirm a business owner remains assigned.

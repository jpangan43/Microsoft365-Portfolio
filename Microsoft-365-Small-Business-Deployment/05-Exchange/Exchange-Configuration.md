# Exchange Online Configuration

## Procedure
1. Open Exchange admin center: https://admin.exchange.microsoft.com/
2. Confirm licensed users have the intended mailboxes.
3. Create a pilot mailbox and validate sign-in and mail flow.
4. Configure shared mailboxes only for approved business functions.
5. Assign Full Access and Send As permissions according to the access matrix.
6. Test internal and external mail flow where domain/DNS configuration permits.
7. Review anti-spam, anti-phishing, malware, and auditing settings available under the tenant's licensing.
8. Record actual results and any limitations.

## Mailbox inventory template

| Mailbox | Type | Business owner | Access group | License requirement reviewed? |
|---|---|---|---|---|
| `info@<your-domain>` | Shared | Operations | Approved support group | Yes / No |
| `sales@<your-domain>` | Shared | Sales | Approved sales group | Yes / No |

Use placeholders in public documentation. A shared mailbox may not need a separate license only while it remains within applicable service limits and does not require features that trigger licensing; verify current Microsoft rules.

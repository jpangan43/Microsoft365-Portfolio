# Email Security Plan

- **SPF:** Authorize legitimate sending infrastructure; maintain a single SPF record.
- **DKIM:** Enable signing for the custom domain using Microsoft-provided DNS selectors.
- **DMARC:** Begin with monitoring after inventorying senders; tighten policy based on report analysis.
- **Anti-phishing / anti-spam:** Review available policies and licensing.
- **Mailbox access:** Review delegates, forwarding, and shared mailbox permissions.
- **Validation:** Test legitimate mail flow and review authentication results in message headers.

Do not copy sample DNS values from this repository into production. Use tenant-generated values and an approved change window.

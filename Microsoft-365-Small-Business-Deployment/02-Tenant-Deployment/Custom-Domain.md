# Custom Domain Runbook

## Before you start
- Use only a domain you own or are authorized to manage.
- Keep the default `onmicrosoft.com` domain if you do not have a suitable domain.
- Plan mail flow before changing MX records, especially for an existing business.

## Procedure
1. Open Microsoft 365 admin center → **Settings → Domains**.
2. Choose **Add domain** and enter the domain you control.
3. Copy the verification TXT record shown by Microsoft.
4. Add that exact record at the authoritative DNS provider.
5. Wait for DNS propagation, then select **Verify** in Microsoft 365.
6. Review the DNS records Microsoft recommends for the services you intend to use.
7. Do not change MX until mailboxes are provisioned and a migration/cutover plan is approved.
8. Record the result and take a sanitized screenshot.

## Validation checklist
- [ ] Domain ownership verified
- [ ] Intended users/mailboxes use the correct domain
- [ ] DNS records reviewed
- [ ] Mail-flow cutover risks considered
- [ ] Rollback/cutover plan documented if existing mail is involved

**Placeholder warning:** `contosodesign.com` in this repository is an example only.

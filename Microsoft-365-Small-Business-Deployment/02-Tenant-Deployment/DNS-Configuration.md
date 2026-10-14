# DNS Configuration Record

Use the exact values generated for your tenant and DNS provider. The table below is a documentation template, not a set of records to copy.

| Record | Host/name | Value / target | Purpose | Status |
|---|---|---|---|---|
| TXT | Provider-specific | Microsoft-provided value | Domain verification | Planned |
| MX | Provider-specific | Microsoft-provided target | Inbound mail | Planned |
| CNAME | `autodiscover` | Microsoft-provided target | Outlook discovery | Planned |
| TXT | `@` or provider-specific | Approved SPF value | Sender authorization | Planned |
| CNAME | Microsoft-provided selector names | Microsoft-provided targets | DKIM | Planned |
| TXT | `_dmarc` | Approved DMARC policy | Reporting/enforcement | Planned |

## SPF
- Publish one SPF record for the domain; multiple SPF records can cause evaluation errors.
- Include all legitimate sending services, not only Microsoft 365, if other systems send mail.
- Confirm the correct Microsoft-provided syntax in current documentation.

## DKIM
- Enable/configure DKIM for the custom domain using the exact selectors and DNS targets shown by Microsoft.
- Verify signing status after DNS changes.

## DMARC
- Start with a monitoring policy only after inventorying legitimate senders and reviewing SPF/DKIM alignment.
- Review aggregate reports before tightening policy to quarantine/reject.
- Decide how reports will be received and protected.

## Safety
Never commit real DNS tokens, tenant-specific secrets, or sensitive report files. A domain's DNS records are public by design, but redact values if they expose operational details you do not want in a public portfolio.

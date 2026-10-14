# Tenant Configuration Runbook

## Prerequisites
- Dedicated lab tenant or written authorization for a client tenant
- Administrative account with only the permissions needed for each task
- Confirmed license/trial availability
- Change log and rollback notes
- MFA method available for the administrator

## Procedure
1. Sign in to the Microsoft 365 admin center: https://admin.microsoft.com/
2. Record the tenant's default `onmicrosoft.com` domain in private working notes. Do not publish tenant identifiers unnecessarily.
3. Review **Settings**, **Org settings**, and **Billing / Your products**.
4. Confirm the tenant region, organization profile, and available licenses.
5. Review admin accounts and remove unnecessary standing privilege where authorized.
6. Configure basic organization settings relevant to the scenario.
7. Record each change, reason, date, operator, and validation result in the change log below.

## Change log

| Date | Change | Reason | Validation | Status |
|---|---|---|---|---|
| YYYY-MM-DD | Example: review org profile | Establish baseline | Confirmed in admin center | Replace with actual result |

## Evidence
Save sanitized screenshots under `../evidence/tenant/` and add each to `../evidence/EVIDENCE-INDEX.md`.

## Notes
Admin center menus can change. Confirm current Microsoft documentation and do not infer success from a saved configuration alone.

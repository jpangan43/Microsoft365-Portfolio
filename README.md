# Microsoft 365 Small Business Deployment

A portfolio project documenting the design, configuration, validation, and handover of a secure Microsoft 365 environment for a **fictional 30-user small business**.

> **Portfolio disclaimer:** This repository is a lab/reference implementation, not evidence of a production deployment. Mark each control as **Planned**, **In progress**, **Implemented in lab**, or **Not tested** based on what you actually completed. Never claim a test passed unless you performed it and retained evidence.

## Project scenario

**Fictional client:** Contoso Design & Consulting  
**Industry:** Professional services  
**Size:** 30 users  
**Work model:** Office and remote/hybrid  
**Lab domain:** Use a domain you own and control, or keep the default `*.onmicrosoft.com` domain. `contosodesign.com` is a placeholder only—do not configure it unless you own it.

## Objectives

- Document business and technical requirements.
- Configure tenant settings and a custom domain where available.
- Design Entra ID users, groups, administrative roles, and emergency access.
- Plan and test MFA and Conditional Access safely.
- Configure Exchange Online, SharePoint Online, OneDrive, and Teams.
- Document licensing, security controls, acceptance testing, and client handover.
- Produce sanitized evidence suitable for a public GitHub portfolio.

## Scope

### In scope
- Tenant baseline and custom domain/DNS planning
- Identity lifecycle, groups, and least-privilege role assignment
- MFA and Conditional Access design/testing
- Exchange Online mailbox and email-authentication planning
- SharePoint site/access design and OneDrive governance
- Teams structure and governance
- Licensing rationale, security baseline, testing, and handover

### Out of scope unless explicitly added
- Production migration of real client data
- Production incident response or compliance certification
- Guaranteed security or regulatory compliance
- Advanced Defender/Intune configuration unless licensed and tested
- Automated provisioning scripts that have not been reviewed and tested

## Repository map

| Path | Purpose |
|---|---|
| `01-Requirements/` | Fictional client requirements and scope |
| `02-Tenant-Deployment/` | Tenant setup and domain/DNS runbooks |
| `03-Entra-ID/` | Users, groups, roles, and emergency access |
| `04-Security/` | MFA, Conditional Access, and baseline |
| `05-Exchange/` | Mailboxes and email security |
| `06-SharePoint/` | Sites and permissions |
| `07-OneDrive/` | OneDrive governance |
| `08-Teams/` | Teams configuration and governance |
| `09-Licensing/` | Licensing assumptions and strategy |
| `10-Testing/` | Acceptance tests and evidence tracking |
| `11-Handover/` | Client handover and support procedures |
| `diagrams/` | Architecture diagram source |
| `evidence/` | Sanitized screenshots and evidence index |

## Suggested implementation sequence

1. Complete the requirements and scope documents.
2. Confirm tenant access, trial/paid licensing, and domain ownership.
3. Configure the tenant baseline and verify the custom domain.
4. Create pilot users and groups; document role assignments.
5. Plan emergency access before enabling Conditional Access.
6. Configure MFA and Conditional Access in **Report-only** first, then test.
7. Configure Exchange, SharePoint, OneDrive, and Teams.
8. Apply the security baseline and review licensing requirements.
9. Execute acceptance tests and record actual results.
10. Complete handover documents and sanitize evidence.
11. Update this README with only verified outcomes.

## Important safety notes

- Use a dedicated lab tenant and fictional identities.
- Never commit passwords, recovery codes, tokens, private keys, real customer data, or unredacted screenshots.
- Do not lock yourself out: retain a tested emergency-access procedure and review policy exclusions carefully.
- Conditional Access requires appropriate licensing (commonly Microsoft Entra ID P1 or a qualifying Microsoft 365 plan). Verify current licensing before implementation.
- Do not enable overlapping identity/security configurations blindly. Security Defaults and Conditional Access are alternative approaches in many tenant scenarios; review Microsoft guidance before switching.
- Keep policies in Report-only until sign-in logs and test cases confirm expected behavior.
- Use a domain only if you own/control it. Verify DNS values directly in your tenant rather than copying examples.

## Current project status

Update this table as you work.

| Workstream | Status | Evidence / notes |
|---|---|---|
| Requirements | Planned | `01-Requirements/` |
| Tenant and domain | Planned | `02-Tenant-Deployment/` |
| Entra ID | Planned | `03-Entra-ID/` |
| MFA / Conditional Access | Planned | `04-Security/` |
| Exchange Online | Planned | `05-Exchange/` |
| SharePoint / OneDrive | Planned | `06-SharePoint/`, `07-OneDrive/` |
| Teams | Planned | `08-Teams/` |
| Licensing | Planned | `09-Licensing/` |
| Acceptance testing | Planned | `10-Testing/` |
| Handover | Planned | `11-Handover/` |

## Evidence standards

For each significant configuration, capture:
1. The relevant setting or policy (sanitized screenshot).
2. The intended configuration and rationale.
3. A test case and actual result.
4. Any limitations, exceptions, or follow-up actions.

Use `evidence/EVIDENCE-INDEX.md` to track evidence. Screenshots are intentionally not included until you add your own.

## Suggested GitHub description

`Reference deployment project for a fictional small business Microsoft 365 tenant, covering identity, security, collaboration, validation, and client handover.`

## Disclaimer

This repository is for educational and portfolio purposes. Microsoft 365 features, admin center layouts, licensing, and recommended configurations can change. Confirm current Microsoft documentation and tenant-specific licensing before applying settings to a real organization.

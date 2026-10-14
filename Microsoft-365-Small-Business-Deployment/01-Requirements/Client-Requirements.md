# Fictional Client Requirements

## Client profile
- **Name:** Contoso Design & Consulting (fictional)
- **Industry:** Professional services
- **Employees:** 30
- **Work model:** Office and remote/hybrid
- **Current state:** Assumed to use mixed email, local files, and consumer collaboration tools. This is a lab scenario, not a real client assessment.

## Business goals
1. Provide company-branded email.
2. Improve identity security with MFA and least privilege.
3. Store team documents in controlled shared locations.
4. Provide personal work storage to employees.
5. Enable collaboration through Teams.
6. Standardize onboarding and offboarding.
7. Produce a supportable, documented environment.

## Functional requirements
- Users can sign in using approved work identities.
- Staff receive the Microsoft 365 services required by their job.
- Department access is controlled by approved groups.
- Shared mailboxes support common addresses where appropriate.
- SharePoint stores departmental documents.
- OneDrive is used for individual work files.
- Teams has clear owners and a documented guest-access approach.

## Security requirements
- MFA for users and stronger protection for administrators.
- Emergency access procedure documented and tested.
- Least-privilege administrative roles.
- Legacy authentication blocked where applicable.
- External sharing reviewed and limited to business need.
- Email authentication configured where the domain supports it.
- Audit/sign-in logs reviewed during validation.

## Assumptions and dependencies
- The lab operator has authorized access to a dedicated Microsoft 365 tenant.
- A custom domain is optional and must be owned/controlled by the operator.
- Features depend on tenant configuration and licenses.
- No production data is used.

## Acceptance
The project is complete when the selected controls are implemented, tests have actual recorded results, limitations are documented, and handover material is ready.

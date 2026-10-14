# SharePoint Permissions and Access Testing

## Procedure
1. Identify the data owner and sensitivity of the site content.
2. Assign owners and groups based on least privilege.
3. Avoid granting broad organization-wide access to confidential sites.
4. Review sharing links and guest access settings.
5. Test with one authorized account and one account that should not have access.
6. Record the actual outcome.

## Test template

| Test ID | Account type | Resource | Expected | Actual | Status |
|---|---|---|---|---|---|
| SP-001 | Finance user | Finance site | Access granted | Not tested | Not tested |
| SP-002 | Non-Finance user | Finance site | Access denied | Not tested | Not tested |
| SP-003 | Guest | Restricted site | Denied unless approved | Not tested | Not tested |

Use fictional accounts and files only.

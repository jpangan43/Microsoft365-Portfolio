# Emergency Access Account Procedure

Emergency access accounts help recover from certain tenant lockout scenarios. They are high-risk accounts and must be designed using current Microsoft guidance and the organization's security requirements.

## Planning checklist
- [ ] Document the business owner and emergency-use criteria.
- [ ] Use a dedicated account not used for normal administration.
- [ ] Select authentication methods consistent with current Microsoft emergency-access guidance.
- [ ] Store credentials/recovery material in an approved secure vault outside this repository.
- [ ] Apply monitoring and alerting for any sign-in or change involving the account.
- [ ] Review Conditional Access exclusions carefully; exclusions create risk and must be limited.
- [ ] Test the recovery procedure in a controlled, authorized way.
- [ ] Review account access and procedure periodically.

## Important
Do not put the account name, password, recovery codes, authentication details, or sensitive screenshots in public GitHub. Do not assume that excluding an account from a policy is automatically the safest design. Follow current Microsoft guidance and document the rationale.

# Authentication Methods

## Planning procedure

1. Review authentication methods available in the tenant.
2. Identify required user populations and privileged accounts.
3. Select methods that meet security, usability, accessibility, and recovery requirements.
4. Where supported, prioritize phishing-resistant methods such as passkeys or FIDO2 security keys for higher-risk users.
5. Consider Microsoft Authenticator where appropriate and supported.
6. Avoid treating SMS as the strongest available method.
7. Configure the relevant method policies and registration experience.
8. Test enrollment, normal sign-in, lost-device recovery, and support escalation.

## Evidence

Record which methods are enabled, the intended scope, the test account, and the result. Do not capture QR codes, one-time passcodes, recovery codes, or other authentication secrets.

Reference: [Microsoft Entra authentication methods](https://learn.microsoft.com/en-us/entra/identity/authentication/concept-authentication-methods).

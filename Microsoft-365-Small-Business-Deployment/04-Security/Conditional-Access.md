# Conditional Access Policy Plan

> **Lockout warning:** Do not activate tenant-wide policies until emergency access is prepared and pilot tests are complete. Start in Report-only when available and review sign-in logs.

## Policy inventory

| ID | Policy name | Initial mode | Intended control |
|---|---|---|---|
| CA001 | Require MFA for workforce | Report-only | Require MFA for targeted users/apps |
| CA002 | Protect privileged roles | Report-only | Strong authentication for admin roles |
| CA003 | Block legacy authentication | Report-only / validate first | Block legacy clients where appropriate |
| CA004 | Protect admin portals | Report-only | Apply stronger controls to admin resources |

These are design examples, not ready-to-enable policies. Confirm current policy templates, licensing, exclusions, workload requirements, and emergency-access guidance.

## Build and test procedure
1. Confirm licensing for Conditional Access and the intended features.
2. Review current Security Defaults state and plan any transition carefully.
3. Prepare and document emergency access.
4. Create a pilot group and select a low-risk test account.
5. Create one policy at a time; specify users, target resources, conditions, grant/session controls, and exclusions intentionally.
6. Set to Report-only where available.
7. Use Entra sign-in logs and the What If tool where available to understand policy impact.
8. Test normal users, admins, mobile/desktop clients, and relevant service workflows.
9. Resolve unexpected results before enabling the policy.
10. Enable in a controlled rollout and continue monitoring.

## Policy review template
- **Policy ID/name:**
- **Business purpose:**
- **Users/groups included:**
- **Exclusions and rationale:**
- **Target resources:**
- **Conditions:**
- **Grant/session controls:**
- **Mode:**
- **Test cases/evidence:**
- **Approver:**
- **Rollback/recovery:**
- **Last review:**

## Caution
Do not blindly exclude every administrator or every service account. Scope each exception to a documented requirement and use current Microsoft recommendations.

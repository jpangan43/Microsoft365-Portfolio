# Access Reviews

Access review features depend on tenant licensing and supported configuration. If the feature is unavailable, document a manual review as a simulation and do not describe it as an implemented Entra access review.

## Entra access-review procedure

1. Navigate to **Identity Governance → Access reviews**, if available.
2. Select a supported group, application, or other review target.
3. Choose reviewers, such as the resource owner or manager.
4. Define review frequency, duration, instructions, and decision deadline.
5. Configure the supported outcome for denied or unanswered decisions.
6. Start the review.
7. Complete a test review and verify the decision and resulting access changes.
8. Save sanitized results and document unresolved decisions.

## Suggested review schedule

| Target | Suggested reviewer | Suggested frequency |
|---|---|---|
| Guest collaboration group | Internal sponsor or owner | Quarterly |
| Sensitive department group | Department manager | Quarterly |
| Privileged role assignments | Authorized security/IT owner | Risk-based, at least periodically |

These are example planning values. Agree on actual review frequency with the organization.

Reference: [Access reviews overview](https://learn.microsoft.com/en-us/entra/id-governance/access-reviews-overview).

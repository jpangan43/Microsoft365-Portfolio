# Dynamic Groups

Dynamic group membership is evaluated by Microsoft Entra using configured user or device attributes. Availability depends on licensing and supported configuration.

## Example: Operations users

1. Confirm test users have the exact `department` value `Operations`.
2. Navigate to **Identity → Groups → All groups → New group**.
3. Choose **Security** and select **Dynamic User** membership.
4. Name the group `DG-Users-Operations`.
5. Open the dynamic membership rule editor.
6. Configure and validate this example rule:

```text
(user.department -eq "Operations")
```

7. Save the rule and allow membership processing to complete.
8. Verify that only the expected test users are members.
9. Change a test user's department attribute and verify that membership recalculates.
10. Record the rule, test outcome, and license prerequisite.

## Risks and controls

- Incorrect or missing attributes can produce incorrect membership.
- Do not expect dynamic groups to be manually managed like assigned groups.
- Do not use an untested dynamic rule for sensitive access.
- Document the rule owner and expected processing behavior.

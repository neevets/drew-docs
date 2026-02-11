---
label: Requirements
icon: checklist
---

# Requirements

Review these requirements before installation to avoid common permission and visibility failures.

!!!info Read Before Installing
All requirements in this page should be validated before opening the invite flow.

## Account and Server Requirements

- An active Discord account
- A Discord server where you have permission to manage integrations
- A stable internet connection for API operations

## Permission Requirements

The account performing installation must have:

- `Administrator` (required)

!!!danger Mandatory Administrator Access
Drew requires the `Administrator` permission to operate correctly across its OPSEC and incident-response modules.

## Role Hierarchy Requirements

After installation, place the Drew role high enough in the server role list to perform intended actions. If the role is too low, moderation or utility features may fail silently due to Discord hierarchy rules.

## Operational Recommendation

Create a dedicated staff-only test channel to validate command behavior before enabling Drew in public channels.

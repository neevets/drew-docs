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

At minimum, the account performing installation should have:

- `Manage Server`
- `Manage Roles` (recommended for full setup validation)
- Access to channels where Drew commands will be executed

=== Minimum Baseline
- `Manage Server`
- Access to at least one writable setup channel

=== Recommended for Staff Setup
- `Manage Server`
- `Manage Roles`
- Visibility into category-level channel overrides

## Role Hierarchy Requirements

After installation, place the Drew role high enough in the server role list to perform intended actions. If the role is too low, moderation or utility features may fail silently due to Discord hierarchy rules.

## Operational Recommendation

Create a dedicated staff-only test channel to validate command behavior before enabling Drew in public channels.

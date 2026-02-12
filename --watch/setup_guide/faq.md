---
label: FAQ
icon: question
---

# FAQ

:::info FAQ Scope
This page covers frequently asked questions from server owners and moderators.
:::

## Is Drew free to use?

Drew is a premium-only service and includes a **5-day free trial** for full-feature testing. After the trial period ends, an active paid plan is required.

## What permissions does Drew require?

Drew requires the `Administrator` permission to ensure all OPSEC and recovery modules function reliably.

## Does Drew need a high role position?

Yes. Drew should be placed as high as possible in the role hierarchy. Otherwise, moderation actions may fail due to Discord role restrictions.

## Why can Drew see one channel but not another?

This is usually caused by channel permission overrides.

Verify that the Drew role has:

- `View Channel`
- `Send Messages`

enabled at both category and channel levels.

## Why is a command not responding?

Common causes include:

- Missing permissions
- Role hierarchy conflicts
- Disabled command contexts
- Temporary Discord API delays

Follow the troubleshooting guide in  
[setup_guide/troubleshooting.md](troubleshooting.md).

## Does Drew store message content?

No. Drew does not store message content or chat logs, as outlined in the Privacy Policy.

---

## For Server Owners

- Start with 'getting_started/requirements'
- Approve the `Administrator` permission during authorization
- Keep one private channel for operational testing

## For Moderators

- Verify category and channel overrides first
- Include IDs and UTC time when reporting issues

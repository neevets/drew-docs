---
label: FAQ
icon: question
---

# FAQ

!!!info FAQ Scope
This page covers high-frequency operational questions from server owners and moderators.

## Is Drew free to use?

Drew is premium-only and includes a 5-day free tier for full-feature testing. After the trial period, an active paid plan is required.

## What permissions does Drew require?

Drew requires `Administrator` permission to ensure all OPSEC and recovery modules can execute reliably.

## Why can Drew see one channel but not another?

This is typically caused by channel overrides. Verify `View Channel` and `Send Messages` for the Drew role at both category and channel levels.

## Why is a command not responding?

Common causes include missing channel permissions, role hierarchy conflicts, disabled command contexts, or temporary Discord API delays. Follow `setup_guide/troubleshooting.md` in order.

## Does Drew require administrator permissions?

Yes. `Administrator` permission is required.

## Does Drew store message content?

No. Drew does not store message content or chat logs, as described in the Privacy Policy.

=== For Server Owners
- Start with `getting_started/requirements.md`.
- Approve `Administrator` permission during authorization.
- Keep one private channel for operational testing.

=== For Moderators
- Verify category and channel overrides first.
- Escalate with IDs and UTC time when reporting issues.

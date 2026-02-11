---
label: FAQ
icon: question
---

# FAQ

!!!info FAQ Scope
This page covers high-frequency operational questions from server owners and moderators.

## Is Drew free to use?

Drew may be available at no cost for baseline usage. If premium plans are introduced, pricing and feature boundaries will be documented separately.

## What permissions does Drew require?

Required permissions depend on enabled modules and channel scope. During authorization, grant only the permissions required by your moderation and operations policy.

## Why can Drew see one channel but not another?

This is typically caused by channel overrides. Verify `View Channel` and `Send Messages` for the Drew role at both category and channel levels.

## Why is a command not responding?

Common causes include missing channel permissions, role hierarchy conflicts, disabled command contexts, or temporary Discord API delays. Follow `setup_guide/troubleshooting.md` in order.

## Does Drew require administrator permissions?

Not necessarily. Most deployments can run safely with scoped permissions. Administrator access should only be used temporarily for diagnostics.

## Does Drew store message content?

No. Drew does not store message content or chat logs, as described in the Privacy Policy.

=== For Server Owners
- Start with `getting_started/requirements.md`.
- Roll out using least-privilege permissions.
- Keep one private channel for operational testing.

=== For Moderators
- Verify category and channel overrides first.
- Escalate with IDs and UTC time when reporting issues.

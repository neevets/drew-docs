---
label: Invite
icon: link
---

# Invite

Use this page only if you are deploying Drew through a hosted bot account.

!!!warning Environment Selection
Always confirm whether you are inviting Drew to a production server or a staging/testing server before authorization.

!!!info Self-Hosted Note
If you are running Drew from source code, this page is optional. Use `getting_started/installation.md` and `getting_started/configuration.md` instead.

## Pre-Invite Checklist

- You have `Administrator` permission in the target server.
- You selected the correct server environment (production vs. testing).
- Your moderation policy permits all requested scopes.

=== Production Server
- Confirm your moderation policy owner approved the requested scopes.
- Validate channel and role strategy before making Drew visible to members.

=== Testing Server
- Use a private channel for first command execution.
- Validate role hierarchy behavior before production rollout.

## Authorization Procedure

1. Open the official invitation URL.
2. Select the target server.
3. Confirm that `Administrator` is granted in the Discord authorization screen.
4. Approve the request.

## Immediate Verification

After authorization:

- Confirm Drew appears in the member list.
- Confirm the Drew role was created.
- Confirm the bot can view and send messages in your setup channel.

If any item fails, continue with `setup_guide/troubleshooting.md`.

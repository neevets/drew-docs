---
label: Troubleshooting
icon: thumbsup
---

# Troubleshooting

Use this runbook when Drew is not operating as expected. Execute each section in order.

!!!danger Incident Handling
Do not change multiple permission variables at once. Apply one change, retest, and record the result.

## 1. Confirm Installation State

- Verify that Drew is present in the server member list.
- Confirm the Drew role exists.
- Confirm the bot is not timed out or restricted by Discord safety actions.

## 2. Confirm Channel Permissions

In the affected channel:

- Validate `View Channel`
- Validate `Send Messages`
- Validate `Read Message History` (recommended)

Also check category-level overrides, which may supersede role defaults.

## 3. Validate Role Hierarchy

- Ensure the bot role is positioned correctly in the server role order.
- Confirm the bot can perform required moderation or utility actions based on role priority.

## 4. Validate Command Context

- Confirm commands are used in supported channels.
- Check whether a feature requires prior setup or configuration.

## 5. Retry After Temporary Outages

Discord API interruptions may temporarily affect responses. Wait briefly and retry.

## 6. Escalate with Diagnostic Details

If the issue persists, provide:

- Server ID
- Channel ID
- Command used
- Approximate timestamp (UTC)
- Screenshot or copied error output, if available

=== Fast Isolation
If Drew is online but does not answer:
1. Test in a private setup channel.
2. Re-check channel overrides for `View Channel` and `Send Messages`.
3. Validate role position.

=== Full Investigation
If failures persist after all checks:
1. Capture IDs and UTC timestamp.
2. Record exact command and response behavior.
3. Escalate with complete diagnostics.

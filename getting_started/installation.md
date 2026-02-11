---
label: Installation
icon: rocket
---

# Installation

This section describes the standard deployment flow for Drew.

!!!primary Deployment Goal
Complete installation with verified command execution before granting broad channel visibility.

## Step 1: Install the Bot

1. Open the official invite link.
2. Select the target server from your Discord account.
3. Review the requested permissions.
4. Confirm authorization to complete installation.

## Step 2: Verify Core Access

After installation, validate the following:

- Drew is visible in your server member list.
- The Drew role exists and is enabled.
- Drew can read and send messages in at least one setup channel.

## Step 3: Validate Command Execution

Run one basic command in your setup channel. A successful response confirms:

- Bot presence
- Message permissions
- API connectivity

!!!success Validation Passed
If all checks in Steps 2 and 3 pass, continue with production permission rollout.

## Step 4: Apply Production Permissions

Once validation is complete, grant channel-level permissions according to your server policy. Use least-privilege access where possible.

If a command does not respond, continue with `setup_guide/troubleshooting.md`.

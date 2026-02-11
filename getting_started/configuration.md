---
label: Configuration
icon: sliders
---

# Configuration

Configure Drew using environment variables.

!!!warning Required Values
Do not run Drew in production with empty token, database, or cache settings.

## Environment Template

```env
DISCORD_TOKEN=""
DISCORD_PREFIX=""
BOT_OWNERS=
SENTRY_DSN=""
DATABASE_URL="sqlite+aiosqlite:///src/data/drew.db"
REDIS_URL=""
REDIS_PASSWORD=""
SETTINGS_CACHE_TTL="30"
BETTERSTACK_BOT_HEARTBEAT=""
BETTERSTACK_DB_HEARTBEAT=""
BETTERSTACK_CACHE_HEARTBEAT=""
```

## Minimum Required

- `DISCORD_TOKEN`: Bot token from the Discord Developer Portal
- `DISCORD_PREFIX`: Prefix for message-based commands
- `DATABASE_URL`: SQLAlchemy async connection string

## Recommended for Production

- `REDIS_URL`: Cache and fast state operations
- `REDIS_PASSWORD`: Redis authentication
- `SENTRY_DSN`: Error and exception monitoring
- `BETTERSTACK_*`: Runtime heartbeat telemetry

## Security Notes

- Never commit `.env` to version control.
- Rotate `DISCORD_TOKEN` immediately if exposure is suspected.
- Restrict access to production credentials to trusted operators only.

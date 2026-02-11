---
label: Architecture
icon: cpu
order: 3
---

# Architecture

## Stack

- Language: Python
- Discord library: discord.py
- ORM: SQLAlchemy async
- Cache: Redis

## Runtime Model

- Discord gateway events drive moderation and automation workflows
- Async data access supports scalable guild operations
- Redis-backed caching reduces latency for frequently accessed settings

## Reliability Guidance

- Use persistent storage for production deployments
- Enable monitoring and heartbeat telemetry
- Keep cache and database endpoints highly available

# HEARTBEAT.md

# Keep this file empty (or with only comments) to skip heartbeat API calls.
# Add tasks below when you want the agent to check something periodically.

## Periodic Checks

<!-- Examples:
- Check for urgent unread emails
- Review upcoming calendar events (next 24-48h)
- Check for new notifications or mentions
-->

## Notes

- Keep this file small to limit token burn
- Use HEARTBEAT_OK if nothing needs attention
- Prefer batching checks here over creating multiple cron jobs
- Track check state in `memory/heartbeat-state.json` if needed

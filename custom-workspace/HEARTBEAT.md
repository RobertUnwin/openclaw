# HEARTBEAT.md - Periodic Checks

On heartbeats (every ~30 min if enabled), rotate through these sparingly (e.g., 2-4x/day max). Stay quiet (HEARTBEAT_OK) unless something needs attention. Track last checks in memory/heartbeat-state.json.

## Checklist (Rotate/Prioritize)
- **Memory Review (every 3 days):** Read recent memory/YYYY-MM-DD.md files. Distill significant insights to MEMORY.md. Prune outdated/irrelevant from MEMORY.md.
- **System Health:** Quick openclaw status if not checked recently.
- **Proactive Scans (daily):** Check for upcoming events/weather if relevant (use skills). Monitor token usage via session_status; flag waste.
- **Optimization Review (weekly):** Scan for agent improvements (e.g., via web_fetch on trends).
- **Quiet Hours:** Skip non-urgent stuff 23:00-08:00 Perth time.

If nothing urgent: HEARTBEAT_OK


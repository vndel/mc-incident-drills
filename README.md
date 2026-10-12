# mc-incident-drills

Controlled game-day scenarios for testing Minecraft network operations. Run only in an isolated staging environment or an explicitly approved maintenance window with a named incident lead and abort criteria.

## Scenarios
- Redis unavailable during proxy reconnect.
- One backend removed from rotation.
- Database latency spike and bounded pool exhaustion.
- Disk nearing capacity during world save.
- Invalid plugin release requiring rollback.

Measure detection time, player impact, operator handoffs, recovery time, and data integrity. Never inject faults into production without explicit authorization. MIT licensed.

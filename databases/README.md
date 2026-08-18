# Database Storage

This folder contains bot databases synced from SC Bot containers.

## Naming Convention

`{baseType}-{username}.json`

Examples:
- `MD-ahyan.json` - Multi Device bot for user ahyan
- `MULTI_DEVICE-user123.json` - Multi Device bot for user user123

## Auto-Sync

- **Upload:** Every 30 seconds after database changes
- **Download:** When bot connects (compare timestamps)
- **Strategy:** Use the newest (local vs GitHub)

---

Last updated: 2026-08-18T02:53:31.452Z

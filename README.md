# Hermes Backup Repository

This repository stores full backups of the Hermes Agent configuration including:
- Skills (`.hermes/skills/`)
- Memory snapshots (`.hermes/memory/`)
- Cron job configurations
- Agent settings and preferences

## Structure
```
hermes-backup/
├── README.md
├── skills/           # Saved skill definitions
├── memory/           # Persistent memory exports
├── cronjobs/         # Cron job configurations
├── configs/          # Agent config files
└── history/          # Session history archives
```

## Auto-Backup
Backups are pushed automatically via cron jobs configured in Hermes Agent.

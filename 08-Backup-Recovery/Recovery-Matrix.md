# Recovery Matrix

| System | Backup | RPO | RTO | Recovery Method |
|---|---|---:|---:|---|
| DC01 | System State | 24h | 4h | AD Recovery |
| Business Data | File Backup | 24h | 4h | File Restore |
| FortiGate | Config Backup | Change-based | 1h | Config Restore |
| WAZUH01 | VM/Config | 24h | 4h | System Restore |
| WIN11-01 | Rebuild | 24h | 4h | Reimage |

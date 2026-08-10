# Firewall Rules

| ID | Source | Destination | Service | Action | Purpose |
|---|---|---|---|---|---|
| 10 | Management | Servers | HTTPS/SSH | Allow | Administration |
| 20 | Users | Internet | HTTP/HTTPS | Allow | Web access |
| 30 | Guest | Internal | Any | Deny | Isolation |
| 40 | Endpoints | WAZUH01 | Wazuh | Allow | Monitoring |
| 50 | Any | Internal | Any | Deny | Default protection |

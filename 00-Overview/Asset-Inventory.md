# Asset Inventory

| Hostname | Role | OS | IP Address | Network |
|---|---|---|---|---|
| FW01 | Firewall | FortiOS | 192.168.10.1 | Management |
| DC01 | Domain Controller | Windows Server | 192.168.10.10 | Server |
| WAZUH01 | SIEM | Ubuntu Server | 192.168.10.20 | Security |
| BACKUP01 | Backup Server | Windows Server | 192.168.10.30 | Server |
| WIN11-01 | Endpoint | Windows 11 | DHCP | Endpoint |

## Critical Systems

### DC01

Provides:

- Active Directory
- DNS
- DHCP
- Authentication

### FW01

Provides:

- Internet gateway
- Firewall
- NAT
- Network security
- Inter-VLAN routing

### WAZUH01

Provides:

- Security monitoring
- Log collection
- Detection
- Alerting

### BACKUP01

Provides:

- Backup storage
- Recovery data
- Backup verification

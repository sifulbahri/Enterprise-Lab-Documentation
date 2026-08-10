# Runbook — Domain Controller Recovery

## Trigger

DC01 is unavailable or corrupted.

## Procedure

1. Identify failure
2. Determine last known good backup
3. Verify backup
4. Restore System State
5. Validate Active Directory
6. Validate DNS
7. Validate authentication
8. Validate Wazuh monitoring
9. Test client connectivity
10. Return service to production

## Validation

- dcdiag
- Get-ADDomain
- DNS resolution
- Domain authentication
- Wazuh agent

# Runbook — Windows Endpoint Isolation

## Purpose

Isolate a suspected compromised Windows endpoint.

## Trigger

Use when:

- Wazuh reports suspicious activity
- Malware is suspected
- Account compromise is suspected
- Unusual network activity is detected

## Procedure

### 1. Identify Endpoint

Record:

- Hostname
- IP address
- Username
- Timestamp

### 2. Validate Alert

Review:

- Wazuh
- Windows Security
- Sysmon
- PowerShell

### 3. Collect Evidence

Collect:

- Running processes
- Network connections
- Security events
- PowerShell events

### 4. Isolate

Disable network connectivity or isolate the endpoint through the
network security infrastructure.

### 5. Investigate

Determine:

- Initial access
- Account involved
- Processes involved
- Network connections
- Persistence

### 6. Eradicate

Remove malicious or unauthorized artifacts.

### 7. Recover

Restore normal connectivity after validation.

### 8. Document

Record all actions and timestamps.

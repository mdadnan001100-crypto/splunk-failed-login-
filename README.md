# Failed Login & Brute Force Detection – Splunk SOC Project

## Objective
Detect brute force and password spray attacks using Windows Security authentication logs in Splunk.

## Log Source
- Windows Security Logs
- Event ID: 4625 (Failed Login)
- Index: wineventlog

## Detection Use Cases
- Repeated failed login attempts on a single account
- Password spray attempts from a single IP
- Correlation between failed and successful logins

## Tools Used
- Splunk SIEM
- Windows Event Logs

## MITRE ATT&CK Mapping
- Tactic: Credential Access (TA0006)
- Technique: Brute Force (T1110)

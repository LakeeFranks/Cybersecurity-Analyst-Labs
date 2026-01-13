# Windows Security Log Ingestion (Splunk)

## Goal for Today
Ingest Windows Security Event Logs into Splunk and verify visibility of authentication activity

---

## Objective
Configure Splunk Enterprise to collect Windows Security Event Logs and confirm successful ingestion by querying authentication events.

---

## Environment
- Host OS: Windows
- Virtualization: VirtualBox
- Guest OS: Windows 10 Pro
- SIEM: Splunk Enterprise

---

## Logs Ingested
- Windows Security Event Log

---

## Validation Steps
The following Splunk searches were used to confirm log ingestion and visibiltiy: 
- index=wineventlog
- index=wineventlog EventCode=4624
- index=wineventlog EventCode 4625

---

## Observations
- Windows Security logs are successfully ingested into Splunk
- Authentication events include timestamps, usernames, and logon metadata
- Both successful and failed login events are visible

---

## Why This Matters
Windows authentication logs are a primary source for SOC analysts and are used to detect:
- Brute-force login attempts
- Unauthorized access
- Account behavior

---

## Current Status
Windows Security log ingestion is complete and functioning as expected.

--- 

## Next Steps
- Generate failed login activity
- Analyze authentication patterns
- Identify suspicious logins

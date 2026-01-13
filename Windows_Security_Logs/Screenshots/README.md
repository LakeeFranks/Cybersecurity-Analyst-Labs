# Windows Security Logs in Splunk

## Purpose
Demonstrate successful ingestion and visibility of Windows Security Event Logs in Splunk.

## What This Folder Shows
- Windows Security logs are ingested into Splunk
- Authentication events can be queried and analyzed

## Validation
Key Splunk searches used:
- index=wineventlog
- index=wineventlog EventCode=4624
- index=wineventlog EventCode=4625

## Evidence
See screenshots in the `Screenshots/` directory.

## Status
Log ingestion complete. Analysis and simulation to follow.


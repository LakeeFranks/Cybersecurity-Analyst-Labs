# Splunk Installation & Initial Setup (Windows 10 VM)

## Objective
Establish a foundational SOC lab by installing Splunk Enterprise on a Windows 10 VM

## Environment
- Host OS: Windows
- Hypervisor: VirtualBox
  - Guest OS: Windows 10 Pro
    - SIEM: Splunk Enterprise

## Steps Completed
- Downloaded Windows 10 ISO from Microsoft
- Created and configured a Windows 10 virtual machine
- Performed manual Windows installation
- Installed Splunk Enterprise
- Created Splunk admin account
- Verified Splunk admin account
- Verified Splunk web interface accessibility

## Validation
Splunk web interface accessibility:
http://localhost:8000

## Key Lessons Learned
- Automated installations can fail; manual installs are sometimes more reliable
- Splunk operates as a background service accessed through a web interface
- Unactivated Windows is sufficient for lab and learning environments

## Current Status
Splunk is installed and running.  
No log ingestion configured yet.

## Next Steps
- Enable Windows Security Event logging
- Ingest Windows authentication logs into Splunk
- Analyze Event IDs 4624 (successful login) and 4625 (failed login)



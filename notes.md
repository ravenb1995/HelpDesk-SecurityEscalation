## Analyst Notes: Incident #SEC-2025-001

### Initial Trigger:
User reported suspicious pop-up and system slowdown.

### Triage Findings:
- PowerShell script `login.ps1` auto-launched from Downloads folder.
- User did not knowingly run script.
- Event ID 4688 confirmed PowerShell execution.
- VirusTotal showed script hash matched known phishing dropper.

### Next Steps:
- Escalated to SOC team.
- Quarantined the file and disabled user account.
- Scheduled phishing training follow-up.

### 7. 🔎 Threat Hunting – Windows Registry Persistence Investigation

Documented a Threat Hunting exercise using Wazuh to investigate a Windows Registry Persistence alert.

## Screenshot
![windows-registry-1](/screenshots/windows-registry-1.jpg)
![windows-registry-2](/screenshots/windows-registry-2.jpg)

**Investigation Details:**
- SIEM: `Wazuh`
- Rule ID: `92302`
- Severity: `6`
- Process: `reg.exe`
- Technique: `Registry Persistence`
- MITRE ATT&CK Tactic: `Persistence`

**Key Findings:**
- Registry modification was successfully detected by Wazuh.
- The alert was associated with a persistence technique.
- The involved process was validated during the investigation.
- The activity was intentionally generated in the controlled home lab environment.

**Skills Practiced:**
- Threat Hunting
- Wazuh SIEM
- Windows Registry Analysis
- Alert Investigation
- Process Analysis
- MITRE ATT&CK Mapping
- SOC Analysis

📄 [Read Threat Hunting Investigation](threat-hunting-registry-persistence.md)

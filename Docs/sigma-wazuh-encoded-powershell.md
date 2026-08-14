### 10. 🛡️ Sigma Rule + Custom Wazuh Detection | Encoded PowerShell

Created a Sigma Rule and implemented its equivalent custom Wazuh detection rule to identify suspicious Base64-encoded PowerShell execution.

## Sceenshot

![sigma-1](/screenshots/sigma-1.jpg)
![sigma-2](/screenshots/sigma-2.jpg)
![sigma-3](/screenshots/sigma-3.jpg)

**Detection Scenario:**
- Detection: `-enc` / `-EncodedCommand`
- Sigma Rule: `.yml`
- SIEM: Wazuh
- Endpoint: Windows 11
- Telemetry: Sysmon
- Alert Level: 12
- MITRE ATT&CK: T1059.001 – PowerShell
- Tactic: Execution

**What I Did:**
- Created a Sigma Rule for encoded PowerShell detection
- Worked with `logsource`, `detection`, `condition`, and MITRE tags
- Converted the Sigma logic into a custom Wazuh XML rule
- Restarted Wazuh Manager and validated the rule
- Executed a controlled Base64-encoded PowerShell command
- Successfully generated a Level 12 Wazuh alert

**Skills Practiced:**
- Sigma Rule Development
- Wazuh Custom Rules
- PowerShell Detection
- Sysmon Telemetry
- MITRE ATT&CK Mapping
- Detection Engineering
- Threat Hunting
- SOC Operations

**Key Learning:**

Sigma Rules provide vendor-neutral detection logic that can be translated into SIEM-specific rules such as Wazuh custom rules.

📄 [Read Sigma + Wazuh Detection Post](sigma-wazuh-encoded-powershell.md)

### 5. 🛡️ Custom Wazuh Rule – Registry Persistence Detection

Documented the creation and validation of a custom Wazuh detection rule for Windows Registry Persistence.

## Screenshot
![custom-1](/screenshots/custom-rule-1.jpg)
![custom-2](/screenshots/custom-rule-2.jpg)
![custom-3](/screenshots/custom-rule-3.jpg)

**Detection Details:**
- Custom Rule ID: `100500`
- Alert Level: `10`
- MITRE ATT&CK: `T1547.001 – Registry Run Keys / Startup Folder`

**Steps Performed:**
- Connected a Windows endpoint to Wazuh
- Generated a controlled Registry Persistence event
- Created a custom Wazuh rule
- Mapped the detection to MITRE ATT&CK
- Successfully triggered a Level 10 custom alert
- Investigated the generated alert in Wazuh Dashboard

**Skills Demonstrated:**
- Wazuh SIEM
- Custom Rule Creation
- Windows Registry Monitoring
- Threat Detection
- MITRE ATT&CK Mapping
- SOC Analysis

📄 [Read Custom Rule Post](custom-registry-rule-100500.md)

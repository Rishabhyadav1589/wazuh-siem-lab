### 4. ⚡ PowerShell Detection Validation

Documented a controlled PowerShell-based simulation to validate whether Wazuh successfully detects file creation activity on a Windows endpoint.

**Test Objective:**
- Generate safe test telemetry
- Create an executable file in the Windows temporary directory
- Create a PowerShell script file
- Validate the complete detection pipeline

- ## Screenshot
- ![powershell-1](/screenshots/powershell-1.jpg)
- - ![powershell-1](/screenshots/powershell-2.jpg)
  - - ![powershell-1](/screenshots/powershell-3.jpg)

**Detection Workflow:**

PowerShell → Sysmon → Wazuh Agent → Wazuh Manager → Wazuh Dashboard

**Lab Environment:**
- Ubuntu Server
- Wazuh Manager
- Wazuh Dashboard
- Windows 11 VM
- Sysmon
- Wazuh Agent

**Key Learning:**

The exercise demonstrated practical detection validation by generating controlled events and confirming that the complete SIEM pipeline successfully processed the telemetry.

📄 [Read Detection Validation Post](powershell-detection-validation.md)

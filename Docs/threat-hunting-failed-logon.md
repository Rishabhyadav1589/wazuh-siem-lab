### 6. 🔎 Threat Hunting – Windows Failed Logon Investigation

Documented a Threat Hunting exercise using Wazuh to investigate a Windows failed logon event.

## Screenshot

![failed-1](/screenshots/failed-login-1.jpg)
![failed-2](/screenshots/failed-login-2.jpg)
![failed-3](/screenshots/failed-login-3.jpg)

**Investigation Details:**
- Rule ID: `60122`
- Event ID: `4625`
- Severity: `5 – Medium`
- Alert: `Logon Failure – Unknown user or bad password`
- Source IP: `127.0.0.1`

**Findings:**
- The failed login attempt originated from the local machine.
- Authentication failed because of invalid credentials.
- The event was successfully collected and analyzed through Wazuh Threat Hunting.
- No evidence of lateral movement or successful compromise was observed.

**Skills Practiced:**
- Threat Hunting
- Wazuh SIEM
- Windows Event Analysis
- Log Investigation
- Authentication Failure Investigation
- SOC Analysis

📄 [Read Threat Hunting Investigation](threat-hunting-failed-logon.md)

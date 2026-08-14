### 3. 🔐 Windows Failed Login Investigation – Event ID 4625

Documented a controlled failed Windows login attempt and investigated how Wazuh detects authentication failures.

## Screenshot
![failed-1](/screenshots/failed-1.jpg)
![failed-2](/screenshots/failed-2.jpg)
![failed-3](/screenshots/failed-3.jpg)

**Detection Details:**
- Event ID: `4625`
- Rule ID: `60122`
- Rule Level: `5`
- Target User: `testuser`
- Logon Type: `2 – Interactive`
- Status: `0xC000006D`
- Sub Status: `0xC000006A – Incorrect Password`
- Source: `127.0.0.1`

**Investigation covered:**
- Windows Security Event Log analysis
- Failed authentication detection
- Incorrect password validation
- Source IP analysis
- Wazuh alert investigation
- SOC alert triage

📄 [Read Investigation Post](failed-login-4625-investigation.md)

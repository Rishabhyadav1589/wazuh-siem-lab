### 8. 🛡️ Custom Suricata Rule – Nmap SYN Scan Detection

Documented the creation and testing of a custom Suricata IDS detection rule integrated with Wazuh SIEM.

## Screenshot

![suricata-1](/screenshots/suricata-1.jpg)

![suricata-2](/screenshots/suricata-2.jpg)

![suricata-3](/screenshots/suricata-3.jpg)

**Detection Scenario:**
- IDS: `Suricata`
- SIEM: `Wazuh`
- Attack Simulation: `Nmap SYN Scan`
- Detection Type: `Custom IDS Rule`

**What I Did:**
- Created a custom Suricata rule
- Troubleshot configuration and rule syntax errors
- Restarted and validated the Suricata service
- Simulated an Nmap SYN scan in the lab
- Verified the generated alert in Wazuh Dashboard

**Skills Practiced:**
- Suricata Rule Creation
- IDS Detection
- Wazuh SIEM
- Nmap Traffic Analysis
- Detection Engineering
- Configuration Troubleshooting
- Alert Validation

**Key Learning:**

Reliable detections require testing, debugging, and validation rather than simply deploying security tools.

📄 [Read Suricata Detection Post](suricata-nmap-syn-scan.md)

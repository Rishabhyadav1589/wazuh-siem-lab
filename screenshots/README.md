# SOC Home Lab Screenshots

This directory contains screenshots captured during the development, testing, detection, and investigation phases of the Wazuh SOC Home Lab.

The screenshots provide visual evidence of the lab environment, security telemetry, alerts, threat hunting activities, custom detection rules, and investigation workflows.

---

## 📸 Screenshot Categories

### 1. Wazuh Dashboard

Screenshots showing the Wazuh Dashboard, security events, alerts, severity levels, and monitoring activity.

---

### 2. Sysmon Integration

Screenshots demonstrating Sysmon integration with the Windows endpoint and Wazuh Agent.

Examples:

- Sysmon Event Logs
- Process Creation
- DNS Queries
- Network Connections
- Registry Changes
- File Creation

---

### 3. Alert Investigation

Screenshots showing investigation of Wazuh alerts and their associated event details.

Examples:

- Rule ID
- Alert Level
- Event ID
- MITRE ATT&CK Mapping
- Source/Destination Information
- Process Information

---

### 4. Threat Hunting

Screenshots captured during threat hunting exercises.

Examples:

- Failed Login Investigation
- PowerShell Investigation
- Registry Persistence Investigation
- DNS Investigation
- SSH Brute Force Investigation
- Network Activity Investigation

---

### 5. Custom Wazuh Rules

Screenshots demonstrating custom detection rules created and tested in the lab.

Examples:

- Custom Rule ID
- Rule Level
- Detection Trigger
- Wazuh Alert
- MITRE ATT&CK Mapping

---

### 6. Sigma Rules

Screenshots related to Sigma-based detection engineering.

Examples:

- Sigma Rule YAML
- Detection Logic
- MITRE ATT&CK Tags
- Converted Wazuh Rule
- Generated Wazuh Alert

---

### 7. Suricata Integration

Screenshots demonstrating Suricata IDS integration with Wazuh.

Examples:

- Suricata Configuration
- Custom Detection Rule
- Nmap SYN Scan Simulation
- Suricata Alert
- Wazuh Detection

---

### 8. SSH Brute Force Detection

Screenshots related to the controlled SSH brute-force simulation.

Examples:

- Kali Linux
- SSH Connection
- Failed Authentication Attempts
- Wazuh Alert
- Investigation Results

---

## 📂 Screenshot Naming Convention

Screenshots should use descriptive filenames.

Example:

```text
screenshots/
├── wazuh-dashboard.png
├── sysmon-process-creation.png
├── sysmon-dns-monitoring.png
├── sysmon-network-monitoring.png
├── sysmon-registry-monitoring.png
├── rule-92213-investigation.png
├── failed-login-4625.png
├── powershell-detection.png
├── registry-persistence.png
├── suricata-nmap-syn-scan.png
├── ssh-brute-force-investigation.png
└── sigma-wazuh-encoded-powershell.png

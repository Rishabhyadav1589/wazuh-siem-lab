# 🛡️ Wazuh SOC Home Lab

A hands-on Security Operations Center (SOC) home lab built using Wazuh SIEM, Windows, Sysmon, Ubuntu, and Kali Linux.

The purpose of this project is to simulate a practical SOC L1 environment where Windows endpoint telemetry is collected, analyzed, and investigated using Wazuh.

---

## 🎯 Objectives

- Build a functional SOC monitoring environment
- Deploy Wazuh SIEM
- Configure Windows endpoint monitoring
- Integrate Sysmon with Wazuh
- Collect Windows security telemetry
- Monitor process creation and endpoint activity
- Detect suspicious behavior
- Perform basic threat hunting
- Investigate security alerts
- Map detections to MITRE ATT&CK
- Simulate attacks from Kali Linux

---

## 🏗️ Lab Architecture

The lab consists of:

- Ubuntu Server → Wazuh Manager
- Wazuh Dashboard → Security monitoring and investigation
- Windows Endpoint → Monitored endpoint
- Sysmon → Detailed Windows telemetry
- Wazuh Agent → Sends endpoint logs to Wazuh Manager
- Kali Linux → Attack simulation

---

## 🔧 Technologies Used

| Technology | Purpose |
|---|---|
| Wazuh | SIEM / XDR platform |
| Sysmon | Windows endpoint telemetry |
| Windows | Monitored endpoint |
| Ubuntu | Wazuh Manager |
| Kali Linux | Attack simulation |
| VirtualBox | Virtualization |
| MITRE ATT&CK | Detection mapping |

---

## 🔍 Monitoring & Detection

The lab covers:

- Process Creation
- DNS Activity
- Network Connections
- Registry Modifications
- Authentication Events
- Sysmon Events
- Suspicious File Activity
- High Severity Alerts

---

## 🕵️ Threat Hunting

Practical threat hunting scenarios include:

- Process hunting
- DNS hunting
- Registry hunting
- Failed login investigation
- Sysmon event analysis
- Suspicious endpoint behavior

---

## 🚨 Alert Investigation

Alerts are investigated using:

- Alert severity
- Rule ID
- Rule description
- Event timestamp
- Endpoint information
- MITRE ATT&CK mapping
- Event details

---

## 📊 Example Wazuh Alerts

The lab successfully generated and investigated Sysmon-related alerts including:

- Executable file activity in folders commonly associated with malware
- Application Compatibility Database activity
- Sysmon endpoint telemetry

---

## 📁 Repository Structure

```text
architecture/       → Lab architecture
setup/              → Wazuh installation and configuration
sysmon/             → Sysmon integration
detection/          → Detection use cases
threat-hunting/     → Hunting exercises
alerts/             → Alert investigation
attack-simulation/  → Kali attack scenarios
screenshots/        → Lab screenshots
docs/               → Supporting documentationThis Folder Contains Screenshots of the Wazuh SIEM Lab

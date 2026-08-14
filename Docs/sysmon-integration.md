# Enhanced My SOC Home Lab with Sysmon Integration

After setting up my Wazuh SIEM lab, I took the next step by integrating Sysmon to improve endpoint visibility and Windows telemetry.

## Screenshot
![Splunk SOC Lab Architecture](screenshots/sysmon-1.jpg)
![Splunk SOC Lab Architecture](screenshots/sysmon-2.jpg)

## What I configured

- Installed Sysmon on the Windows endpoint
- Configured Wazuh Agent to collect Sysmon Operational logs
- Verified Sysmon event collection in Wazuh
- Explored process creation, DNS, and endpoint monitoring events
- Practiced basic threat hunting using Wazuh Dashboard

## Key Learning

Sysmon provides much deeper visibility into Windows activity than standard event logs, making it easier to investigate process execution, endpoint behavior, and potential security incidents.

## Next Step

Simulating attacks from Kali Linux and investigating them in Wazuh.

## LinkedIn

#CyberSecurity #SOCAnalyst #BlueTeam #Sysmon #Wazuh #SIEM #ThreatHunting #WindowsSecurity #Linux

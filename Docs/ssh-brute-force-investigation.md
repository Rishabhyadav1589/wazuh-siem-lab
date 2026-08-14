### 9. 🔐 SSH Brute Force Attack Investigation

Documented a controlled SSH brute-force simulation and investigation using Wazuh SIEM.

## Screenshot

![ssh-1](ssh-login-1.jpg)
![ssh-1](ssh-login-2.jpg)
![ssh-1](ssh-login-3.jpg)


**Lab Workflow:**
- Configured and enabled SSH on Ubuntu Server
- Verified SSH connectivity from Kali Linux
- Simulated failed SSH login attempts using Hydra
- Investigated authentication failure alerts in Wazuh Dashboard
- Reviewed rule details and validated the detection

**Tools Used:**
- Wazuh SIEM
- Kali Linux
- Hydra
- Ubuntu Server
- OpenSSH

**Skills Practiced:**
- SSH Authentication Monitoring
- Brute-Force Detection
- Wazuh Alert Investigation
- Linux Log Analysis
- Threat Detection
- SOC Investigation
- Detection Engineering

**Key Learning:**

The exercise demonstrated how repeated SSH authentication failures can be detected and investigated before they potentially lead to unauthorized access.

📄 [Read SSH Brute Force Investigation](ssh-brute-force-investigation.md)

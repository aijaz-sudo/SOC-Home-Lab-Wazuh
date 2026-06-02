# SOC Home Lab using Wazuh + Sysmon

## 📌 Project Overview

Built a professional SOC (Security Operations Center) Home Lab using Wazuh SIEM, Windows 10, Kali Linux, Sysmon, and Wazuh Agent for endpoint monitoring, attack simulation, threat hunting, and security analysis.


# 🛠 Tools & Technologies Used

* Wazuh SIEM
* Windows 10
* Kali Linux
* Sysmon
* Wazuh Agent
* Oracle VirtualBox
* Nmap
* Windows Event Viewer



# 🏗 Lab Architecture

Kali Linux
↓
Windows 10 + Sysmon + Wazuh Agent
↓
Wazuh SIEM Dashboard
↓
Threat Hunting & Alert Monitoring



# 🚀 Setup Steps

1. Installed Oracle VirtualBox
2. Created Windows 10 VM
3. Created Kali Linux VM
4. Imported Wazuh OVA
5. Configured VM networking
6. Installed Wazuh Agent on Windows 10
7. Installed Sysmon on Windows 10
8. Connected logs to Wazuh SIEM
9. Performed attack simulations using Kali Linux
10. Conducted threat hunting and log analysis


# 🔥 Attack Simulations

## Nmap Scan

```bash
nmap WINDOWS10-IP
```

## Advanced Nmap Scan

```bash
nmap -A WINDOWS10-IP
```

---

# 📊 Monitoring & Detection

* Sysmon process monitoring
* Endpoint telemetry collection
* Wazuh alert generation
* Security event monitoring
* Threat hunting analysis



# 📸 Screenshots Included

* VirtualBox setup
* Wazuh dashboard
* Active agents
* Sysmon installation
* Threat hunting
* Nmap scans
* Security alerts
* Connectivity tests



# 🎯 Skills Demonstrated

* SIEM Administration
* Threat Hunting
* SOC Operations
* Endpoint Monitoring
* Log Analysis
* Security Monitoring
* Windows Event Analysis
* Kali Linux
* Nmap
* Blue Team Operations



# 🧠 Key Findings

* Successfully integrated Sysmon with Wazuh
* Detected endpoint activity using Sysmon telemetry
* Generated alerts from attack simulations
* Investigated security events using Wazuh Threat Hunting



# 🚀 Future Improvements

* Malware simulation
* Brute force detection
* Suricata integration
* Active Directory monitoring
* Sigma rule testing



# 📌 Conclusion

Successfully built a professional SOC home lab capable of attack simulation, endpoint monitoring, SIEM log analysis, threat hunting, and alert monitoring using Wazuh and Sysmon.

This project demonstrates practical SOC analyst and blue team skills suitable for cybersecurity internships and entry-level SOC analyst roles.

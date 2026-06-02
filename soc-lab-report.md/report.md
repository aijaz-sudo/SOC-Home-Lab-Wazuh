# SOC Home Lab Implementation Report

## 📌 Implementation Summary

A professional SOC home lab was built using Wazuh SIEM, Windows 10, Kali Linux, Sysmon, and Wazuh Agent inside Oracle VirtualBox.

The lab environment was designed to simulate real-world SOC monitoring, attack detection, and threat hunting workflows.



# 🛠 Components Implemented

* Wazuh SIEM Dashboard
* Windows 10 Endpoint
* Kali Linux Attacker Machine
* Sysmon Telemetry
* Wazuh Agent Monitoring
* Network Connectivity Between VMs



# 🚀 Setup Performed

## Windows 10

* Installed Windows 10 VM
* Installed Wazuh Agent
* Installed Sysmon
* Generated endpoint activity logs

## Kali Linux

* Installed Kali Linux VM
* Performed Nmap scans
* Simulated attack activity

## Wazuh

* Imported Wazuh OVA
* Configured dashboard access
* Verified active agents
* Monitored alerts and events



# 🔥 Detections Observed

* Process creation events
* Sysmon telemetry events
* Network scan activity
* Endpoint command execution
* Security alerts in Wazuh



# 🧪 Attack Simulations

## Basic Nmap Scan

```bash
nmap WINDOWS10-IP
```

## Advanced Nmap Scan

```bash
nmap -A WINDOWS10-IP
```



# 📊 Threat Hunting Activities

Performed threat hunting using Wazuh dashboard by searching:

* sysmon
* process events
* cmd.exe
* network activity

Investigated:

* event timestamps
* process names
* endpoint activity
* alert severity



# 🧠 Findings

* Sysmon successfully generated endpoint telemetry
* Wazuh successfully collected and displayed security events
* Kali Linux attack simulations generated detectable activity
* Threat hunting workflow was successfully demonstrated



# ✅ Recommendations

* Integrate Suricata IDS
* Add Active Directory environment
* Create custom Wazuh detection rules
* Simulate malware attacks safely
* Expand monitoring coverage



# 🎯 Conclusion

The SOC home lab successfully demonstrated SIEM deployment, endpoint monitoring, attack simulation, log analysis, and threat hunting capabilities using Wazuh and Sysmon.

The project provided hands-on experience with practical SOC analyst and blue team workflows.

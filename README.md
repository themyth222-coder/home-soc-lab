# home-soc-lab
Hands‑on security monitoring lab featuring Wazuh SIEM, Windows event forwarding, CIS Benchmark scanning, and secure remote access via Cloudflare Tunnel. Built to practice log analysis, troubleshooting, and endpoint monitoring.
# Home SOC Lab – Wazuh SIEM + Windows Endpoint + Cloudflare Zero‑Trust

## Overview
This project is a fully functional home Security Operations Center (SOC) environment built to practice real‑world monitoring, alerting, and system administration. It includes a Wazuh SIEM server, a monitored Windows endpoint, and secure remote access through Cloudflare Zero‑Trust. The goal of this lab is to build hands‑on experience with log analysis, troubleshooting, endpoint monitoring, and secure infrastructure design.

---

## Architecture
                   +---------------------------+
                   |     Cloudflare Tunnel     |
                   |  Secure Zero-Trust Access |
                   +-------------+-------------+
                                 |
                                 v
+-------------------+     +-------------------+
|   Windows 10 VM   | --> |   Wazuh Server    |
| Wazuh Agent Logs  |     | Ubuntu + Wazuh SIEM|
+-------------------+     +-------------------+
                                 |
                                 v
                     +-----------------------+
                     |   Wazuh Dashboard     |
                     |  Alerts & Monitoring  |
                     +-----------------------+

---

## Features
- Real‑time Windows event log monitoring  
- Authentication event tracking  
- PowerShell activity detection  
- CIS Benchmark scanning  
- File Integrity Monitoring (FIM)  
- System change detection  
- Secure remote dashboard access via Cloudflare Tunnel  
- Virtualized environment using VirtualBox  

---

## Skills Demonstrated
- SIEM configuration & management  
- Linux administration (Ubuntu Server)  
- Windows endpoint monitoring  
- Log analysis & alert triage  
- Network fundamentals (TCP/IP, DNS, DHCP)  
- Secure tunneling with Cloudflare Zero‑Trust  
- Virtualization (VirtualBox)  
- Troubleshooting & system diagnostics  
- Technical documentation  

---

## Tools Used
- Wazuh SIEM  
- Ubuntu Server  
- Windows 10  
- Cloudflare Tunnel / Zero‑Trust  
- VirtualBox  
- Linux CLI  
- PowerShell  

---

## How It Works
1. The Windows 10 endpoint sends logs to the Wazuh server using the Wazuh agent.  
2. Wazuh analyzes logs, applies rules, and generates alerts.  
3. The Wazuh Dashboard displays real‑time events, CIS Benchmark results, and system activity.  
4. Cloudflare Tunnel provides secure remote access to the dashboard without exposing ports.  

---

## Why I Built This
I created this home SOC lab to gain hands‑on experience with real security tools, log analysis, and endpoint monitoring. This project helped me practice SIEM configuration, Linux administration, Windows event monitoring, and secure remote access using Cloudflare Zero‑Trust. It also supports my long‑term goal of working in IT support, networking, or system administration.

---

---

## Future Improvements
- Add Linux endpoints  
- Add File Integrity Monitoring rules for Documents/Desktop  
- Add Suricata or Zeek for network monitoring  
- Add automated alert reports  
- Expand to multi‑endpoint monitoring  
- Add PowerShell script logging enhancements  

---

## Resume
My full résumé is available upon request or on my LinkedIn profile. im seeking an entry level postion to kick start my carrerr

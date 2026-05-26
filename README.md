#  Windows Endpoint Hardening + Sysmon Logging

##  Overview
This project demonstrates how to harden a Windows endpoint and configure **Sysmon** for detailed system activity logging. It integrates logs with **Wazuh SIEM** to detect suspicious behavior and strengthen endpoint security.

---

##  What I Did
- Installed Sysmon and applied the **SwiftOnSecurity configuration**
- Enabled detailed logging for:
  - Process creation
  - Network connections
  - Registry changes
  - File creation
- Connected the endpoint to **Wazuh SIEM**
- Triggered test events (PowerShell, simulated attacks)
- Verified Sysmon logs flowing into Wazuh
- Analyzed alerts and patterns for anomalies

---

##  Skills Demonstrated
Sysmon • Windows Hardening • Logging & Monitoring • Detection Engineering • Wazuh SIEM • Threat Analysis

---

## Project Image
![Sysmon Endpoint Logging Diagram](sysmon-diagram.png)

---

## Folder Structure

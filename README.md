
# Enterprise SOC Homelab

## Project Status

🚧 Project in progress

## Objective

Building an enterprise-style Security Operations Center (SOC) home lab to develop practical skills in:

- Active Directory
- Windows Security
- Sysmon
- Splunk
- Log Analysis
- Threat Detection
- Incident Response
- MITRE ATT&CK

## Environment

Currently building the Active Directory environment.

## Progress

- [x] GitHub repository created
- [x] Project documentation structure created
- [x] Active Directory deployment
- [x] Windows client configuration
- [ ] Sysmon deployment
- [ ] Splunk deployment
- [ ] Log forwarding
- [ ] Attack simulation
- [ ] Detection engineering
- [ ] Incident investigation


## Network Topology & Environment

* Domain Controller (DC): Windows Server 2022 (AD DS, DNS, DHCP, RRAS NAT)
* Internal Network Subnet: 172.16.0.0/24
* Client Endpoint: Windows 10 Enterprise (Domain-joined)
* Virtualization: VMware Workstation Pro
  
<details>
<summary>View Evidence</summary>

![Network Topology](architecture/01-network-architecture.jpeg)

</details>


## Lab Modules & Documentation

| Module | Topic | Status | Link |
| :--- | :--- | :--- | :--- |
| 01 | Active Directory Domain Services (AD DS) & Network Setup | Completed | [View Documentation](documentation/01-active-directory-setup.md) |
| 02 | Telemetry Ingestion & Endpoint Monitoring (Sysmon) | Pending | *Upcoming* |
| 03 | SIEM Deployment & Log Forwarding (Splunk) | Pending | *Upcoming* |
| 04 | Adversary Emulation & Attack Detection | Pending | *Upcoming* |


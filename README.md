# Hi, I'm Tenny Wu 👋

Cybersecurity student graduating in **December 2026** with hands-on experience in SOC/SIEM monitoring, cloud security, network security, IAM/RBAC, vulnerability assessment, incident response, and digital forensics.

I am preparing for entry-level opportunities in **IT, SOC operations, and cybersecurity**.

## 🎓 Education

**University of Texas at San Antonio (UTSA)**  
B.B.A. in Cyber Security — Expected December 2026  
GPA: **3.6**

## 📜 Certification

- **CompTIA Security+ (SY0-701)**

## 🔐 Cybersecurity Focus

- Security Operations & SIEM
- Detection Engineering
- Incident Investigation & Response
- Cloud Security
- Identity & Access Management
- Network Security
- Vulnerability Assessment
- OT/ICS Security
- Digital Forensics
- Security Automation

## 🛠️ Technical Skills

**SIEM & Detection**
- Splunk Enterprise
- Splunk Universal Forwarder
- SPL
- Sysmon
- Windows Event Logs
- Detection Engineering
- Alert Tuning
- Dashboard Studio
- MITRE ATT&CK
- Log Correlation

**Cloud & IAM**
- Microsoft Azure
- Azure RBAC
- Managed Identities
- Virtual Networks & Subnets
- Network Security Groups
- Azure Activity Log
- Azure Policy
- Microsoft Entra ID concepts
- Azure CLI

**Security & Network Analysis**
- Wireshark
- NetworkMiner
- Snort
- Nmap
- Vulnerability Assessment
- Packet Analysis
- Incident Reconstruction
- Registry & Process Analysis
- Memory Forensics

**Systems & Scripting**
- Windows
- Linux (Ubuntu, Kali)
- PowerShell
- Bash
- Python
- Java
- SQL
- Git & GitHub
- VMware

## 🚀 Featured Projects

### SOC/SIEM Detection & Incident Response Lab

Built an isolated SOC monitoring environment using **Splunk Enterprise, Windows 11, Sysmon, Splunk Universal Forwarder, and VMware**.

Highlights:

- Forwarded Windows Security and Sysmon telemetry into dedicated Splunk indexes
- Built custom search-time field extraction for Sysmon and Windows Security XML events
- Engineered and validated **5 SPL detections** for suspicious PowerShell, Run-key persistence, Rundll32 abuse, PowerShell network activity, and repeated failed logons
- Baselined normal activity, tuned false positives, and configured scheduled alerts
- Built a Splunk SOC dashboard for endpoint, authentication, network, and detection visibility
- Investigated a controlled multi-stage incident using **ProcessGuid** correlation across process, file, registry, child-process, and network events
- Reconstructed an incident timeline and mapped activity to **MITRE ATT&CK**
- Documented sanitized Sysmon and Splunk configuration artifacts in GitHub

🔗 [View the SOC/SIEM Detection & Incident Response Lab](https://github.com/714tenny/soc-siem-detection-lab)

---

### Azure Cloud Security & IAM Lab

Built and secured a fictional small-business Azure environment focused on cloud security, IAM, least privilege, and remediation validation.

Highlights:

- Designed a segmented Azure Virtual Network with management and workload subnets
- Configured Network Security Groups to restrict management access and block workload-to-management traffic
- Implemented least-privilege Azure RBAC with managed identities
- Created and remediated controlled SSH and excessive-permission findings
- Investigated remediation activity using Azure Activity Log
- Validated security controls using Azure CLI
- Created a Bash security-review script for repeatable NSG and RBAC checks
- Documented architecture, evidence, findings, and final security posture

🔗 [View the Azure Cloud Security & IAM Lab](https://github.com/714tenny/azure-cloud-security-iam-lab)

## 🔎 Additional Labs & Investigations

Documented academic labs with investigation notes, screenshots, tools, findings, and evidence limitations.

- **[OnyxCrew Malware Analysis](https://github.com/714tenny/onyxcrew-malware-analysis)** — Static analysis of a UPX-packed sample, string extraction, and indicator documentation.
- **[Poison Ivy Memory Forensics](https://github.com/714tenny/poison-ivy-memory-forensics)** — Volatility analysis correlating process ancestry, DLLs, file paths, and network artifacts.
- **[FTP Server Compromise Investigation](https://github.com/714tenny/ftp-compromise-investigation)** — Anonymous FTP enumeration and Windows host triage linking suspicious files, processes, and port checks.
- **[Attack Analysis & Incident Reconstruction](https://github.com/714tenny/attack-analysis-incident-reconstruction)** — Wireshark and event-log analysis reconstructing SMB/RPC activity, a victim callback, and a PE file transfer.
- **[Windows Host Hardening & Control Validation](https://github.com/714tenny/windows-host-hardening)** — Local account, service, RDP listener, and browser-control checks with documented validation gaps.
- **[Cryptography & Data Protection Fundamentals](https://github.com/714tenny/cryptography-and-data-protection)** — Coursework demonstrating document protection, AES encryption/decryption, hashing, and information hiding.
- **[Linux Filesystem, Permissions & Memory Management](https://github.com/714tenny/linux-filesystem-and-memory-management)** — GPT partitions, inodes, links, permissions, and C debugging with GCC and GDB.

## 🎯 Current Goals

- Begin my career in IT, SOC operations, or cybersecurity
- Continue strengthening detection engineering and incident-response skills
- Expand cloud-security and security-automation experience
- Build practical projects that demonstrate real investigation and remediation workflows

## 🤝 Connect With Me

- [LinkedIn](https://www.linkedin.com/in/tenny-wu-283965310)
- [GitHub](https://github.com/714tenny)

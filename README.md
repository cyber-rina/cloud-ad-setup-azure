# Cloud‑Based Active Directory Setup & User Management (Azure)

## 🧠 Project Overview
This project demonstrates the deployment of a cloud‑hosted Active Directory environment using Microsoft Azure. A domain controller (DC01) and Windows client (Client01) were configured inside a private virtual network to simulate enterprise identity management, user authentication, and domain join processes.

## ⚙️ Environment Setup
- **Azure Virtual Machines**
  - DC01 – Windows Server 2022
  - Client01 – Windows 10/11
- **Private Virtual Network**
- **DNS configured to point Client01 to DC01**
- **Remote Desktop access for configuration**

## 🔧 Active Directory Configuration
- Installed **Active Directory Domain Services (AD DS)** on DC01  
- Promoted DC01 to a domain controller (`corp.local`)  
- Created Organizational Units (OUs)  
- Added domain users (e.g., Sophia)  
- Joined Client01 to the domain  
- Verified authentication and connectivity  

## 📸 Screenshots

### Client01 Domain Membership
![Client01 Domain](screenshots/client01-domain.png)

### DC01 Domain Controller
![DC01 Domain](screenshots/dc01-domain.png)

### Active Directory – Computers OU
![Computers OU](screenshots/dc01-computers-ou.png)

### Active Directory – Users OU
![Users OU](screenshots/dc01-users-ou.png)

### Event Viewer – User Account Created (4720)
![User Created](screenshots/event-user-created.png)

### Event Viewer – Security Log Overview
![Security Log](screenshots/event-viewer-security-log.png)

### Ping Test & Domain User Verification
![Ping Test](screenshots/ping-test.png)

## 🔐 Skills Demonstrated
Identity & Access Management (IAM)  
Windows Server Administration  
Azure Virtual Machines  
DNS & Network Configuration  
Kerberos Authentication  
Event Viewer Log Analysis  
Cloud Infrastructure Setup  

## 🧰 Tools Used
Microsoft Azure  
Windows Server 2022  
Active Directory Domain Services  
PowerShell  
Event Viewer  
DNS Manager  

## 🏁 Outcome
Successfully deployed and validated a functional Active Directory domain in Azure. Demonstrated secure user authentication, domain join processes, and core identity management concepts aligned with Security+ and entry‑level SOC analyst skills.

## 🚀 Next Steps (Planned Enhancements)
- Group Policy Objects (GPOs)  
- File server + NTFS permissions  
- SIEM integration (Splunk / Wazuh)  
- Security log monitoring & alerting  

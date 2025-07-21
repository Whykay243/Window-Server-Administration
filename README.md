# 🖥️ Windows Server 2022 Administration Lab

## 🚀 Project Overview

This project showcases my implementation of a Windows Server 2022 environment on VirtualBox. I performed end-to-end configuration of Active Directory, DNS, DHCP, and Print Services. I also joined both Windows and Linux clients to the domain, managing a hybrid network with centralized control using Active Directory.

## 🛠️ Tools & Technologies

- **VirtualBox** for virtualization
- **Windows Server 2022 Evaluation Center**
- **Windows 11 Enterprise** (Client VM)
- **Ubuntu 24.04 Desktop** (Linux Client VM)
- **Rocky Linux** (Linux Client VM)
- **Active Directory Domain Services (AD DS)**
- **DNS Server**
- **DHCP Server**
- **Print and Document Services**
- **RealmD / SSSD** for Linux integration
- **IONOS** for domain registration
- **AWS Route 53** for external DNS resolution

## 📋 What I Did

### 🖥️ Server Configuration

- Installed Windows Server 2022 on a VirtualBox VM and configured a **static IP**.
- Installed and configured:
  - Active Directory Domain Services (AD DS)
  - DNS Server
  - DHCP Server
  - Print and Document Services
- Promoted the server to domain controller for my custom domain: `physicstutors.org`.
- Configured DNS zones and DHCP scope to manage IP distribution across the network.
- Enabled file and printer sharing on the domain controller.

### 🧑‍💻 Windows Client

- Joined **Windows 11 Enterprise** VM to the domain.
- Verified successful domain join and tested login with Active Directory credentials.

### 🐧 Linux Clients (Ubuntu + Rocky)

- Installed `realm`, `sssd`, and other dependencies on **Ubuntu 24.04** and **Rocky Linux**.
- Configured Linux clients to join the Active Directory domain using `realm join`.
- Verified domain membership and successfully logged in using AD credentials.

## 📂 Project Folder Structure

```
Windows-Server-Administration/
├── screenshots/
│   ├── Windows-Client/ #screentshots
│   ├── Ubuntu-Client/ #screentshots
│   └── Rocky-Linux-Client/ #screnshots
├── Reports/
│   └── documentation and troubleshooting steps
└── README.md (this file)
```

## 📸 Screenshots

All screenshots of configurations and steps are stored in the `screenshots/` folder, organized by client OS:

- `Windows-Client/`
- `Ubuntu-Client/`
- `Rocky-Linux-Client/`

## 🎓 Key Takeaways

- Set up and promoted a domain controller on Windows Server 2022
- Managed DNS, DHCP, and Print Services
- Joined Windows and Linux machines to a centralized domain
- Implemented file and printer sharing across the network
- Handled external domain integration via IONOS and AWS Route 53

---

*Prepared by: Yinka Ajibola*


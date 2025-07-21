🖥️ Windows Server 2022 Administration Lab
🚀 Project Overview
In this project, I set up and administered a Windows Server 2022 environment using VirtualBox. I configured Active Directory, DNS, DHCP, and Print Services roles, and joined both Windows 11 Enterprise and Linux clients (Ubuntu 24.04 and Rocky Linux) to my domain. This hands-on work gave me valuable experience managing a mixed-OS network with centralized authentication and resource management.

🛠️ Technologies I Used
Windows Server 2022

Windows 11 Enterprise (Client VM)

Ubuntu 24.04 Desktop (Linux Client VM)

Rocky Linux (Linux Client VM)

VirtualBox for virtualization

Active Directory Domain Services (AD DS)

DNS Server

DHCP Server

Print and Document Services

RealmD / SSSD for Linux AD integration

IONOS domain registration and AWS Route53 DNS management

📋 What I Did
Server Setup
Installed Windows Server 2022 on a VirtualBox VM and assigned a static IP

Installed and configured Active Directory Domain Services, DNS, DHCP, and Print Services

Promoted the server to domain controller for my domain, physicstutors.org

Managed DNS zones and created DHCP scopes for network management

Client Setup
Joined Windows 11 Enterprise VM to my Active Directory domain and tested user login

On Ubuntu 24.04 and Rocky Linux clients, installed necessary packages and joined them to the domain using RealmD and SSSD

Verified successful domain join and tested domain user authentication on Linux clients

📸 Screenshots
I have screenshots documenting each step and configuration stored in the screenshots/ folder for reference.

🎓 What I Learned
Deploying and managing a Windows Server 2022 domain controller

Configuring DNS, DHCP, and print sharing in Active Directory

Integrating Linux clients with a Windows Active Directory domain

Managing users, groups, and organizational units in AD

Handling external DNS with IONOS and AWS Route53


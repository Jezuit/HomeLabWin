# 🏰 HomeLabWin: Windows Server 2022 Infrastructure Lab

## 📖 Project Overview

**HomeLabWin** is a documentation repository for my personal virtualization lab. The primary goal of this project is to simulate a corporate IT environment to bridge the gap between theoretical networking knowledge and practical system administration skills.

This project documents the deployment of **Active Directory Domain Services (AD DS)**, network configuration, and security policies implementation, simulating a small-to-medium business infrastructure.

## 🎯 Objectives

  - **Infrastructure:** Deploying Windows Server 2022 on Oracle VirtualBox.
  - **Identity Management:** Configuring Active Directory, Users, Groups, and OUs.
  - **Networking:** implementing static IP addressing, DNS, and DHCP services tailored for a domain environment.
  - **Documentation:** Practicing "Infrastructure as Code" (IaC) principles by documenting every configuration step.

-----

## 🛠️ Tech Stack & Tools

  * **Hypervisor:** Oracle VirtualBox (Bridged/NAT Networks)
  * **Server OS:** Windows Server 2022 Evaluation
  * **Client OS:** Windows 10/11 Enterprise (Planned)
  * **Scripting:** PowerShell
  * **Security:** Wazuh SIEM (Planned integration)

-----

## 📚 Theory vs. Practice (Educational Context)

This lab is heavily inspired by the **"Pasja Informatyki"** networking curriculum. I use this repository to translate theoretical concepts explained in the videos into real-world configurations.

| Network Concept | Practical Implementation in Lab |
| :--- | :--- |
| **IP Addressing & Subnetting** | Configured Static IP `192.168.x.x` on DC01 to ensure stable DNS resolution. |
| **DNS Hierarchy** | Deployed a local Forward Lookup Zone (`lab.local`) and configured Loopback address for AD replication. |
| **DHCP (DORA Process)** | (In Progress) Setting up DHCP Scope to lease addresses to client workstations. |
| **Users & Permissions** | Mapping logical business structures to Organizational Units (OUs) in Active Directory. |

-----

## 🗂️ Repository Structuretext

HomeLabWin/
├── docs/
│   ├── 01-setup/           \# VirtualBox network configuration & OS Installation
│   ├── 02-identity/        \# Active Directory promotion & User Management
│   └── 03-networking/      \# DNS and DHCP configuration notes
├── scripts/                \# PowerShell automation scripts
├── theory-notes/           \# My notes based on videos
├── assets/                 \# Screenshots and diagrams
└── README.md

## 📸 Network Topology
*(...)*

---

## 🚀 Getting Started
To replicate this setup:
1.  Ensure virtualization (VT-x/AMD-V) is enabled in BIOS.
2.  Install Oracle VirtualBox.
3.  Download Windows Server 2022 ISO from Microsoft Evaluation Center.
4.  Follow the guides in the `/docs` folder.

---

## 📝 Latest Learning Log
*   **:** Initialized repository. Installed Windows Server 2022.
*   **:** Promoted server to Domain Controller (`dcpromo`).
*   *(Update this log as you progress!)*

---

## 📫 Contact
Created by **Karol Jezuit**.
Connect with me on [LinkedIn](www.linkedin.com/in/karol-jezuit-060b97303).

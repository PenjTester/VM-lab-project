# Enterprise IT Infrastructure Lab (Virtualized)

This repository documents the design and build of a Windows-based virtual enterprise network using VirtualBox.  
The goal is to gain practical, hands-on experience with real-world IT administration tasks, including Active Directory, DNS, DHCP, Group Policy, user management, domain-joined clients, and enterprise networking concepts.

---

## Lab Overview

| Component | Details |
|-----------|---------|
| Virtualization Platform | VirtualBox (Type 2 Hypervisor) |
| Domain Name | lab.local |
| Server OS | Windows Server 2019 (Domain Controller / DNS) |
| Client OS | Windows 10 (domain-joined workstation) |
| Network Mode | Internal Network (lab-network) |
| Lab Purpose | Simulate enterprise IT infrastructure for learning and documentation |

---

##  Milestone Documentation

| Milestone | Status | Documentation |
|-----------|--------|---------------|
| 01 – Domain Controller Setup | ✔ Completed | /documentation/01-domain-controller-setup.md |
| 02 – Windows Client Domain Join | ✔ Completed | /documentation/02-client-domain-join.md |
| 03 – AD Users, Organizational Units & Group Policy | ⏳ Upcoming | Coming soon |
| 04 – File Sharing, Permissions, and NTFS Management | ⏳ Upcoming | Coming soon |
| 05 – DHCP Configuration & Dynamic IP Assignment | ⏳ Upcoming | Coming soon |

---

##  Project Objectives

- Build a virtualized enterprise-style IT infrastructure  
- Configure Active Directory Domain Services (AD DS) and DNS  
- Join Windows clients to the domain and authenticate using AD credentials  
- Apply Group Policy Objects (GPO) to enforce system-wide settings  
- Practice user, group, and organizational unit management  
- Demonstrate networking fundamentals (DNS, DHCP, static IP, name resolution)  
- Document each step clearly to build a portfolio-ready reference  

---

##  Current Status

✔ Domain Controller built and operational  
✔ AD Domain `lab.local` established  
✔ DNS fully resolving internal hostnames  
✔ Windows 10 client successfully joined to the domain  
✔ Documentation captured and stored in GitHub  
 Next: Create AD Users, OUs, and apply Group Policy  

---

_Project is being built incrementally. Each milestone includes screenshots, configurations, and domain-relevant documentation to serve as a personal skills portfolio._

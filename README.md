# Virtual Home Lab Project

This repository documents the build of a Windows-based virtual enterprise network using VirtualBox.  
The goal is to gain hands-on experience with Active Directory, DNS, DHCP, Group Policy, and domain-joined client machines.

---

## Lab Overview

| Component | Details |
|-----------|---------|
| Hypervisor | VirtualBox |
| Domain | lab.local |
| Server OS | Windows Server 2019 (Domain Controller) |
| Client OS | Windows 10/11 (to be added) |
| Network Type | NAT + Internal Network |
| Purpose | Practice real-world IT administration tasks in a virtual lab |

---

## Milestone Documentation

| Milestone | Status | Link |
|-----------|--------|------|
| 01 – Domain Controller Setup | ✔ Completed | /documentation/01_domain_controller_setup.md |
| 02 – Client Machine Setup & Domain Join | Pending | Coming soon |
| 03 – Group Policy, Users, and Organizational Units | Pending | Coming soon |
| 04 – File Sharing, Permissions, and Management | Pending | Coming soon |

---

## Project Objectives

- Build a virtualized enterprise-style IT environment  
- Configure a domain controller with DNS, Active Directory, and DHCP  
- Join client machines to the domain  
- Apply Group Policy to enforce configurations and restrictions  
- Practice user, group, and resource management  
- Document each milestone in detail to build a portfolio reference

---

## Repository Structure

- `VM-lab-project/` – Root of the lab repository  
  - `documentation/` – Step-by-step lab build documentation  
    - `01_domain_controller_setup.md`  
  - `notes/` – Personal notes and learning scratchpad  
  - `scripts/` – PowerShell or other configuration scripts (future)  
  - `README.md` – Main project overview


# Windows Server Implementation Project – Computer Networks II

This repository contains the full implementation of the **Computer Networks II - Homework 1** project.  
The objective was to install and configure Windows Server in a virtual environment and simulate a network environment with clients, domain services, DNS, DHCP, FTP, Web, and Mail servers.

---

## 🖥️ Project Environment

- **Virtualization Software**: VirtualBox
- **Server OS**: Windows Server 2019
- **Client OS**: Windows 10 and Windows 7

---

## ✅ Completed Tasks Overview

### A. Virtualization & Installation
- Setup of virtual environment and installation of Windows Server

### B. Active Directory
- Installation and configuration with domain name: `yourname.yoursurname`

### C. DNS Server
- DNS records added: `yourname.net.tr` and `yoursurname.net.tr`
- A, MX, NS, CNAME records created for `www`, `mail`, `web`, `w3`

### D. NAT & Network Configuration
- Two Ethernet cards: `10.16.16.1/16` (external), `10.17.17.1/16` (internal)
- NAT routing set up via Routing and Remote Access

### E. Group Policies & User Testing
- Group `Student`: restricted from Control Panel
- Group `Personal`: restricted from software installation
- Users created and tested in client OS

### F. User & Group Management
- 4 users: `OgrUser1`, `OgrUser2`, `PersUser1`, `PersUser2`
- 2 groups: `Student`, `Personal`

### G. DHCP Server
- DHCP Server configured with two pools for both networks
- Clients successfully received dynamic IP addresses

### H. FTP Server
- FTP Server setup with user-specific file access permissions

### J. Web Server
- Hosted and published webpages for:
  - `www.yourname.net.tr`
  - `www.yoursurname.net.tr`

### K. Mail Server
- Mail server configured for internal communication
- Outlook set up and tested with `mail.yourname.net.tr`

---

## 📌 Notes

- Turkish characters in domain/usernames were replaced with English equivalents.
- All steps were verified in client systems.
- Screenshots were taken via Print Screen and saved as PNG.

---

© 2025 – Nebi Erdenay Çubukçu | Computer Engineering Student

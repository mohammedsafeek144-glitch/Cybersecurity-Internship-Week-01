# 🔐 Week 01 | Cybersecurity Internship – Kali Linux Lab Setup

Setting up a cybersecurity lab with **Oracle VirtualBox** and **Kali Linux** to prepare for hands-on cybersecurity and ethical hacking practice.

> Cybersecurity Internship with @NETWORKWALKS, guided by @Waqas Karim (CCIE).

---

## 📌 Overview

In Week 01, I built an isolated virtual lab environment where I can safely practice cybersecurity and ethical hacking skills without affecting my main system.

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Oracle VirtualBox | Virtualization platform |
| Kali Linux | Penetration testing operating system |
| NAT Network | Dedicated virtual lab network |
| GitHub | Documentation |

## 🎯 Tasks Completed

- [x] Installed and configured Oracle VirtualBox
- [x] Downloaded and imported the Kali Linux virtual machine
- [x] Completed the initial Kali Linux configuration
- [x] Created and configured a dedicated NAT Network
- [x] Reviewed and configured network settings
- [x] Tested network connectivity
- [x] Created a VM snapshot for recovery purposes

## 📋 Setup Steps

### 1. Install Oracle VirtualBox
Downloaded and installed Oracle VirtualBox on the host machine.

### 2. Import the Kali Linux VM
Downloaded the official Kali Linux virtual machine image and imported it into VirtualBox using **File → Import Appliance**.

### 3. Initial Kali Linux Configuration
Started the VM, logged in, and completed the initial configuration.

![Kali Linux Desktop](screenshots/kali-desktop.png)

### 4. Create a NAT Network
Created a dedicated NAT Network in VirtualBox and attached the Kali VM's network adapter to it.

### 5. Review Network Settings and Test Connectivity
Checked the network configuration from the Kali terminal. The `ip route` command shows the default gateway and the `10.0.0.0/24` network used by the `eth0` interface, assigned by DHCP.

```bash
ip route
ip a
ping -c 4 google.com
```

![ip route output](screenshots/ip-route.jpeg)

> Note: IP addresses in the screenshot are blurred for privacy.

### 6. Create a VM Snapshot
Took a clean snapshot (**Machine → Take Snapshot**) so the VM can be restored quickly if something goes wrong.

## 💡 Key Learnings

- Virtualization and Linux environments
- Virtual networking with NAT Networks
- IP configuration
- Network connectivity testing
- VM snapshot management

## 📁 Repository Structure

```
.
├── README.md
└── screenshots/
    ├── kali-desktop.png
    └── ip-route.jpeg
```

## ⚠️ Disclaimer

This lab is for **educational and ethical purposes only**. Only test systems you own or have explicit permission to test.

## 🚀 What's Next

Week 02: exploring more cybersecurity concepts, improving technical skills, and completing new hands-on projects.

**Learn • Practice • Improve • Repeat**<img width="1600" height="743" alt="WhatsApp Image 2026-11-03 at 5 20 49 PM" src="https://github.com/user-attachments/assets/1f8a7a46-c757-4406-8e40-e29e1034f3f8" />

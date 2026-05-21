# Debian Linux Admin Lab - Setup Log

This document tracks every step taken to build and configure a Debian Linux virtual machine for system administration practice.

---

## Step 1: Virtual Machine Setup
- Created Debian VM using VirtualBox
- Allocated resources (CPU, RAM, disk)
- Installed Debian 12

---

## Step 2: Initial Login
- Logged into system using created user account

---

## Step 3: System Update

Updated the Debian system packages to ensure the latest security patches and software versions were installed.

### Command used:
```bash
sudo apt update && sudo apt upgrade -y

---

## Step 4: Install Core Administration Tools

Installed essential Linux system administration tools to support networking, monitoring, and remote access.

### Tools Installed:
- OpenSSH Server (remote access via SSH)
- UFW (firewall management)
- curl (data transfer tool)
- wget (file retrieval tool)
- net-tools (network diagnostics utilities)
- htop (system monitoring tool)

### Command used:
```bash
sudo apt install openssh-server ufw curl wget net-tools htop -y

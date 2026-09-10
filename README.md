# Cybersecurity Lab Environment Setup

Building an isolated virtual lab using VirtualBox and Kali Linux for cybersecurity learning and ethical hacking practice.

---

## 📌 Project Overview

This project documents the setup of a cybersecurity laboratory environment using VirtualBox and Kali Linux.

The purpose of this lab is to create an isolated environment for practicing networking, security tools, vulnerability assessment, and ethical hacking techniques.

---

## 🎯 Objectives

- Install and configure VirtualBox
- Setup Kali Linux virtual machine
- Create NAT Network
- Configure network settings
- Verify IP address using Linux commands
- Document the complete setup process

---

# 🏗️ Lab Setup Procedure

## Step 1: Create NAT Network

A NAT Network was created in VirtualBox to allow communication between virtual machines.

![NAT Network](screenshots/1-nat-network.png)


---

## Step 2: Configure Network Settings

The Kali Linux virtual machine network adapter was configured to use the NAT Network.

![Network Settings](screenshots/2-network-settings.png)


---

## Step 3: Verify IP Address

The Kali Linux network configuration was checked using:

```bash
ip a

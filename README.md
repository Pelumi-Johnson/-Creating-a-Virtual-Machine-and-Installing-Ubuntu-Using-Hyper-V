# 🖥️ Creating a Virtual Machine and Installing Ubuntu Using Hyper-V

![Badge](https://img.shields.io/badge/Cloud%20Security-Virtualization%20%7C%20Linux%20Deployment-red?style=for-the-badge)

## 📌 Project Overview
UMGC lab focused on creating a virtual machine using Hyper-V Manager and installing Ubuntu Linux. The project emphasizes virtualization fundamentals, internal networking configuration, and preparing a Linux environment for cloud security architecture labs.

---

## 🧠 Course Information
- **Institution:** University of Maryland Global Campus (UMGC)
- **Course:** CMIT 320 – Network Security
- **Lab Title:** Creating a Virtual Machine and Installing Ubuntu Using Hyper-V
- **Date:** January 13, 2026

---

## 🎯 Objective
Create a virtual machine using Hyper-V Manager and install Ubuntu Linux while configuring internal virtual networking to support future cloud and security-related tasks.

---

## 🧰 Tools & Environment
- uCertify Virtual Lab (Windows Host)
- Hyper-V Manager
- Ubuntu Linux ISO
- Internal Virtual Switch (Student-Switch)

---

## ✅ Lab Walkthrough

### Step 1: Access Hyper-V Manager
- Launched Hyper-V Manager from the Windows desktop
- Prepared the environment for VM and network configuration

### Step 2: Create a Virtual Switch
- Opened Virtual Switch Manager
- Created an **Internal** virtual switch named **Student-Switch**
- Enabled host-to-VM communication while maintaining network isolation

### Step 3: Create the Virtual Machine
- Used the New Virtual Machine Wizard
- Named the VM **ubuntu1**
- Allocated memory and storage per lab requirements
- Connected the network adapter to **Student-Switch**

### Step 4: Attach Ubuntu ISO
- Selected the Ubuntu Linux ISO as the boot media
- Configured the VM to install the OS from a virtual CD/DVD drive

### Step 5: Install Ubuntu
- Started the virtual machine
- Selected **Install Ubuntu**
- Chose language and keyboard layout
- Confirmed disk changes
- Created a user account named **student** with a password

### Step 6: Complete Installation
- Restarted the virtual machine after installation
- Successfully logged into the Ubuntu desktop environment

---

## 📊 Results Summary
- Virtual machine successfully created using Hyper-V
- Ubuntu Linux installed without errors
- Internal virtual networking configured correctly
- System ready for cloud and security labs

---

## 🧾 Conclusion
This lab demonstrated how virtualization can be used to deploy a Linux operating system in a controlled environment. Configuring a virtual machine with Hyper-V and installing Ubuntu provided essential hands-on experience with virtualization concepts foundational to cloud security architecture.

---

## 🔑 Key Takeaways
- Virtualization enables efficient use of hardware resources
- Hyper-V supports flexible and secure virtual networking
- Linux virtual machines are essential for cloud and security training

---

## 📎 Documentation
- 📄 Full UMGC Lab Report (PDF): `Creating a Virtual Machine and Installing Ubuntu Using Hyper-V.pdf`

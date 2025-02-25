# Virtualization

## Project Overview
This project demonstrates how to build a **home virtual lab** for cybersecurity testing using **VirtualBox**. 
The lab consists of:
- A **Windows 10 virtual machine** (Target System)
- A **Kali Linux virtual machine** (Attacker System)
- Security tools such as **Sysmon** and **Splunk** for log analysis

## Features
- Sandbox environment for safe malware testing
- Network segmentation to isolate test machines
- Pre-configured **Snapshots** for easy rollback
- Security monitoring with **Splunk & Sysmon**

## Setup Instructions
### 1 Install VirtualBox
Download and install [VirtualBox](https://www.virtualbox.org/):
### 2 Install a Windows 10 VM
Download the Windows 10 ISO from Microsoft's website.
Create a new Virtual Machine in VirtualBox.
Allocate at least 4GB RAM and 50GB Disk.
Attach the ISO and install Windows.
### 3 Install a Kali Linux VM
Download Kali Linux VM from Kali.org.
Import the Kali .ova file into VirtualBox.
### 4 Network Configuration
Set the Windows 10 VM to Host-Only Adapter.
Set the Kali Linux VM to NAT Network.
This isolates the test environment from the internet.

### Screenshots
![Screenshot 2025-02-25 030749](https://github.com/user-attachments/assets/7cc3e916-d56f-4b42-908e-dd01c3cdea61)

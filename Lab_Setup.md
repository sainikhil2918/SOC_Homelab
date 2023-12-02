# SOC Lab Setup

## Original Date: December 1, 2023
This guide explains how to set up a SOC lab using VirtualBox, Splunk, and related tools.

## Prerequisites
- Windows 10 laptop
- VirtualBox
- Splunk Enterprise
- Splunk Universal Forwarder
- Kali Linux VM
- Windows 10 ISO

## Steps
### 1. Install VirtualBox
- Download and install VirtualBox for Windows from the official site.
- Enable networking permissions during installation.

### 2. Install Splunk
- Download and install Splunk Enterprise on Windows.
- Access Splunk at `http://localhost:8000`.
- Set up admin credentials.

### 3. Configure Virtual Machines
- Import the pre-built Kali Linux VM for VirtualBox.
- Create a Windows 10 VM using an ISO file.

### 4. Simulate Events
- Use tools like Nmap and Metasploit on Kali Linux to generate logs.
- Monitor logs in Splunk and create dashboards for analysis.


## Tools Used
- VirtualBox
- Splunk Enterprise
- Kali Linux
- Windows 10

## Simulations
- Run Nmap to generate logs in Splunk.
- Use Metasploit for additional attack simulations.


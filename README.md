# Network Penetration Testing 

## Overview
Set up a virtual lab to simulate real-world network attacks 
using Kali Linux and Windows 11 on VirtualBox.

## Tools Used
- Bettercap — MITM attack
- Nmap — Network scanning
- Wireshark — Traffic analysis
- Metasploit — Exploitation

## What I Did

### MITM Attack
- Used Bettercap to perform ARP spoofing
- Intercepted HTTP credentials in plain text
- Verified using Wireshark

### Network Scanning
- Scanned target with Nmap
- Found open ports including SMB on port 445

### Exploitation
- Tried EternalBlue exploit on Windows 11
- Target was patched and not vulnerable

## What I Learned
- HTTP exposes credentials — always use HTTPS
- Windows 11 is protected against older exploits
- Regular updates matter for security

## Screenshots
See screenshots folder

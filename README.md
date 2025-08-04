# Cybersecurity Internship Task 1: Nmap and Wireshark Analysis

#Objective
Perform a network scan using Nmap to identify open ports and services on local hosts, and analyze the resulting traffic using Wireshark.

# Tools Used
- Nmap: Version 7.97 (network scanning).
- Wireshark: Version 4.2.5 (packet analysis).
- Operating System: Windows 11 (based on file path `C:\Users\Rahul\`).

# Task Description
Scanned a local network (172.20.46.0/24) to identify active hosts, open ports, and services, then captured and analyzed the network traffic.

# Steps
## Nmap Scan
1. Installed and verified Nmap with `nmap --version`.
2. Ran a SYN scan on the subnet `172.20.46.0/24`:
    bash -- nmap -sS 172.20.46.0/24

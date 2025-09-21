Network Analysis Lab Assignments — Nmap, Zenmap, Wireshark, Hping3
Overview

This repository contains my network analysis and penetration testing lab assignments using:

Nmap (network scanning & service enumeration)

Zenmap (GUI for Nmap with profiles)

Wireshark (packet capture and analysis)

Hping3 (packet crafting and traffic generation)

All experiments were performed in a controlled and authorized lab environment only.


Repository Structure

nmap/ — Nmap scan reports, commands, and notes

zenmap/ — Zenmap profiles and screenshots

wireshark/ — PCAP files and analysis notes

hping3/ — Hping3 test logs and examples

reports/ — Summary of findings (PDF)


Tools & Versions

Nmap
Zenmap
Wireshark
Hping3


Example Commands (Lab Use Only)

Nmap:
nmap -sV -p 22,80,443 192.168.56.101


Zenmap:
Load “Intense scan” profile → Target: 192.168.56.101 → Save screenshot.

Wireshark:
Start capture, apply filter http, save as wireshark/http_traffic.pcap.

Hping3:
sudo hping3 -1 192.168.56.101 -c 3


What I Documented
Host discovery results (open ports, services, versions)
Service fingerprinting and notes on findings
Packet captures of TCP handshake, HTTP requests/responses
Hping3 test results (logs and timing analysis)


How to Reproduce (Lab)
Run two VMs in a private network.
Use one VM to perform scans with Nmap/Zenmap.
Capture traffic with Wireshark.
Run controlled Hping3 probes.
Save all reports/screenshots in respective folders.


Ethics & Legal Disclaimer
All experiments were conducted in an authorized lab environment.
⚠️ Never run scans or traffic generation on networks/systems without permission. Unauthorized use is illegal.



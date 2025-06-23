# Task 1: Nmap Network Scan

## Objective
To discover open ports on devices within the local network using Nmap and verify scan behavior with Wireshark.

## Tools Used
- Nmap
- Wireshark
- Command Prompt

## Command Used
```bash
nmap -sS -Pn 192.168.29.0/24 -oN scan_results.txt


## Files
analysis.txt: Summary of findings
nmapScan_capture.pcapng: Wireshark capture file
screenshots/: Scan and capture screenshots

## Key Findings
Detected 7 live hosts
Open ports: 80, 443, 445, 8080, etc.
Risky ports: 445 (SMB), 6666 (IRC)

## Wireshark Insights
Observed SYN packets sent by Nmap
Confirmed open ports with SYN-ACK replies

## Learnings
Gained hands-on experience in basic network reconnaissance, port scanning, and packet-level inspection using professional tools.

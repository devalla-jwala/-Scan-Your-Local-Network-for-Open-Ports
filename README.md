# -Scan-Your-Local-Network-for-Open-Ports
 Task 1:  Scan Your Local Network for Open Ports*Elevate Labs*
# Local Network Port Scan

## Objective
Perform a port scan on my local network to identify open ports and assess security risks.

## Tools Used
- Nmap (`nmap -sS 172.20.10.0/24`)
- Wireshark (optional)

## Steps
1. Identified my local IP range: `172.20.10.0/24`.
2. Ran a TCP SYN scan: `sudo nmap -sS 172.20.10.0/24`.
3. Saved results to ` my_sj.txt`.
4. sudo wireshark
5. caputre the packets

## Findings
- **172.20.10.0/24**: Port 22 (SSH) and 80 (HTTP) open.
- **Risk**: Open SSH could allow brute-force attacks.
## screenshorts

![image alt](https://github.com/devalla-jwala/-Scan-Your-Local-Network-for-Open-Ports/blob/c7850ae1dd6d55ca4d7d80608a53a6d12026f92e/Nmap.jpg)

![image alt](https://github.com/devalla-jwala/-Scan-Your-Local-Network-for-Open-Ports/blob/8f769f2b9cfaf7225c79032f8fbc9610f6a171af/packet%20capture%20with%20Wireshark.jpg)

# Advanced Nmap Scan

## Objective
Perform an advanced scan to gather detailed information about the target system.

## Command Used
nmap -sS -sV -O -A -T4 10.10.10.10

## Explanation
- -sS: TCP SYN scan (stealth scan)
- -sV: Detect service versions
- -O: Detect operating system
- -A: Aggressive scan (OS detection, version detection, script scanning, traceroute)
- -T4: Faster scan timing

## Results
- Open ports: 22 (SSH), 80 (HTTP)
- OS detected: Linux
- Service versions identified

## Analysis
The system is running SSH and a web server, which could be potential entry points. Version detection may allow identification of known vulnerabilities.

## Conclusion
This scan provides a detailed overview of the system and helps plan further enumeration or exploitation.

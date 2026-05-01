# Basic Nmap Scan

## Objective
Perform a basic network scan to identify open ports and services.

## Command Used
nmap -sS -sV 10.10.10.10

## Explanation
- -sS: TCP SYN scan
- -sV: Service version detection

## Results
Open ports identified:
- 22 (SSH)
- 80 (HTTP)

## Conclusion
The target system is running SSH and a web server, which could be potential entry points for further testing.

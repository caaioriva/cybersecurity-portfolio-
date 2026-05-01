# UDP Scan

## Objective
Identify open UDP ports on the target system.

## Command Used
nmap -sU 10.10.10.10

## Explanation
- -sU: UDP scan

## Results
- Open UDP services detected (e.g., DNS)

## Analysis
UDP services are often overlooked but can expose critical vulnerabilities.

## Conclusion
UDP scanning is slower but important for full network visibility.

## Next Steps
- Perform deeper enumeration
- Use tools like Gobuster or Nikto
- Attempt exploitation if applicable

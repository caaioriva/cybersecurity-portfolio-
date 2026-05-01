# Full Port Scan

## Objective
Scan all 65535 TCP ports to identify hidden services.

## Command Used
nmap -p- -T4 10.10.10.10

## Explanation
- -p-: Scan all ports
- -T4: Faster scan

## Results
- Additional open ports discovered beyond default scan

## Analysis
Some services run on non-standard ports, which may be missed in default scans.

## Conclusion
Full port scanning is essential for thorough reconnaissance.

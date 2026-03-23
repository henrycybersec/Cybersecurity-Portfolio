# Host Enumeration with Nmap

## Lab Type
Network Reconnaissance / Port Scanning

## Objective
To perform basic host discovery and service enumeration on a local Linux system in order to understand system exposure and attack surface.

## Tools Used
- Kali Linux Terminal
- Nmap

## Commands Executed
nmap localhost

sudo nmap -O localhost

## Activities Performed
- Verified that the host was reachable on the network
- Scanned for open and closed TCP ports
- Attempted operating system fingerprinting
- Observed service availability on the local machine
- Analysed the system attack surface based on scan results

## Key Findings
- Host responded to network probes (system online)
- Majority of ports were closed
- No active web or database services detected
- SSH service not running
- OS fingerprinting results were inconclusive due to limited exposed services

## Skills Demonstrated
- Network scanning fundamentals
- Host reconnaissance methodology
- Basic service discovery
- Attack surface awareness
- Command-line security tooling usage

## Cybersecurity Relevance
This lab reflects the **enumeration phase of a penetration testing workflow**, where analysts identify reachable systems, discover running services and evaluate potential entry points before vulnerability assessment.
## Evidence


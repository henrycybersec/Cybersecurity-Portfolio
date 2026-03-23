# Network Traffic Analysis Lab

## Lab Type
Network Monitoring / Packet Analysis

## Objective
To observe live network traffic and understand how common protocols such as ICMP, DNS and HTTP operate.

## Tools Used
- ping
- tcpdump
- curl

## Activities Performed

### Connectivity Testing
Tested internet connectivity using ICMP echo requests.

Command:
ping google.com

### DNS Traffic Observation
Captured DNS packets on port 53.

Command:
sudo tcpdump -i any port 53

### HTTP Traffic Observation
Monitored web traffic packets on port 80.

Command:
sudo tcpdump -i any port 80

### TCP Connection Observation
Observed TCP 3-way handshake behaviour.

Commands:
sudo tcpdump -i any tcp  
curl https://example.com

## Skills Demonstrated
- Basic packet capture
- Protocol awareness (ICMP, DNS, HTTP, TCP)
- Traffic interpretation mindset
- Network troubleshooting fundamentals

## Outcome
Developed foundational skills required for SOC monitoring and network security analysis.

## Evidence
Screenshots to be added.

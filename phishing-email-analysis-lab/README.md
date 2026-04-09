# Phishing Email Analysis Lab

## Lab Type
Email Security / Threat Analysis

## Objective
To analyze a suspected phishing email by examining the sender details, URL, file hash, and domain reputation in order to determine if the email is malicious.

---

## Tools Used
- VirusTotal
- Cisco Talos Intelligence
- Zscaler (Zulu URL analysis)

---

## Analysis Performed

### 1. Email Inspection
- Sender email did not match the organization name
- Use of generic greeting ("Dear John")
- Presence of a billing-related message designed to create urgency

### 2. URL Analysis
- URL: http://waterscrest.buzz
- The domain is unusual and does not match a legitimate company domain
- Flagged as suspicious by security analysis tools

### 3. File Hash Analysis
- MD5 Hash: 31cf9a5d5b8347bdb8c22b2a93ddc1f5
- No known malicious detection found on VirusTotal
- Considered safe but still treated with caution

### 4. Domain Reputation Check
- Checked using Cisco Talos Intelligence
- Domain not flagged but lacks credibility and trusted history
- Considered suspicious due to uncommon domain structure

---

## Conclusion
The email is identified as a phishing attempt based on inconsistencies in the sender information, suspicious URL, and social engineering techniques.  
Although the file hash did not return malicious results, the overall context indicates a high likelihood of phishing activity.

---

## Skills Demonstrated
- Email threat analysis
- Phishing detection techniques
- URL and domain reputation analysis
- Hash verification (MD5)
- Security tool usage (VirusTotal, Cisco Talos)

---

## Evidence



## Cybersecurity Relevance
This lab reflects the initial analysis phase in a Security Operations Center (SOC), where analysts investigate suspicious emails to determine potential threats and prevent compromise.

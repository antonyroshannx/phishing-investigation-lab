# phishing-investigation-lab
Phishing investigation lab covering URL analysis, DNS/WHOIS reconnaissance, certificate analysis, IOC identification, and MITRE ATT&amp;CK mapping.
Phishing Investigation Lab
Overview

This project demonstrates a structured investigation of a simulated phishing scenario using common cybersecurity investigation and threat-intelligence techniques.

The investigation focuses on identifying suspicious indicators, analyzing domain and DNS information, examining certificate details, documenting Indicators of Compromise (IOCs), and mapping relevant activity to the MITRE ATT&CK framework.

Objectives
Analyze a suspicious URL and domain.
Perform WHOIS and DNS reconnaissance.
Examine SSL/TLS certificate information.
Identify and document potential IOCs.
Map relevant phishing activity to MITRE ATT&CK techniques.
Maintain investigation evidence in a structured format.
Tools & Frameworks
WHOIS
dig
OpenSSL
Web browser / URL analysis
MITRE ATT&CK
Kali Linux
Investigation Workflow
Suspicious URL
      ↓
Domain & URL Analysis
      ↓
WHOIS / DNS Reconnaissance
      ↓
Certificate Analysis
      ↓
IOC Identification
      ↓
MITRE ATT&CK Mapping
      ↓
Investigation Summary
Indicators of Compromise

The investigation documents relevant indicators such as:

Suspicious URLs
Domains
IP addresses
Redirects
Nameservers
Certificate information
Other observed indicators

No personal email addresses, credentials, or private information are included in this repository.

MITRE ATT&CK

Relevant phishing-related activity is mapped to the MITRE ATT&CK framework where applicable. The mapping is based on the behavior observed during the investigation rather than assuming that every phishing scenario contains all phishing techniques.

Evidence

Screenshots and investigation evidence are stored in the evidence/ directory.

Conclusion

This lab demonstrates a basic phishing investigation workflow from initial URL analysis through IOC documentation and MITRE ATT&CK mapping. It is intended as a cybersecurity learning and portfolio project.

Disclaimer

This project was conducted in a controlled and educational environment. No unauthorized access, credential collection, or attacks against real users or systems were performed.

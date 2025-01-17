***
# Kaspersky Advisory
## (K-Mercedes-Benz-2023-008) Arbitrary File Read in UserData
***
### Type
Arbitrary File Read
### Vendor
HARMAN Becker Automotive Systems GmbH
### Affected products
Mercedes Benz NTG 6 
### CVSS v3 Vector

CVSS:3.1/AV:L/AC:L/PR:N/UI:R/S:U/C:N/I:N/A:H
### CVSS v3 Score

5.5 medium
### CVE ID

CVE-2023-34403
### Vulnerability description
Head-unit NTG6 has Ethernet pins on Base Board to connect module CSB. Attacker can connect to this pins and get access to internal network. 
A race condition can be acquired and attacker can spoof “UserData” with desirable file path and access it though backup on USB.
### Remediation
Apply updates per vendor instructions.
### Acknowledgements
Vulnerability was discovered by Radu Motspan (Kaspersky).

### References
https://github.com/klsecservices/Advisories/blob/master/K-Mercedes-Benz-2023-008.md
Report
EN: [https://securelist.com/mercedes-benz-head-unit-security-research/115218/](https://securelist.com/mercedes-benz-head-unit-security-research/115218/)
RU: [https://securelist.ru/mercedes-benz-head-unit-security-research/111516/](https://securelist.ru/mercedes-benz-head-unit-security-research/111516/)
https://github.com/klsecservices/Publications/blob/master/Mercedes-Benz_Head_Unit_security_research_report.pdf
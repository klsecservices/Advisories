***
# Kaspersky Advisory
## (K-Mercedes-Benz-2023-009) Command Injection in NetworkService
***
### Type
Command Injection
### Vendor
HARMAN Becker Automotive Systems GmbH
### Affected products
Mercedes Benz NTG 6 
### CVSS v3 Vector

CVSS:3.1/AV:L/AC:L/PR:N/UI:R/S:U/C:N/I:N/A:H
### CVSS v3 Score

5.5 medium
### CVE ID

CVE-2023-34404
### Vulnerability description
Head-unit NTG6 has Ethernet pins on Base Board to connect module CSB. Attacker can connect to these pins and get access to internal network.
As a result, by accessing a specific port an attacker can send call request to all registered services in router and achieve command injection vulnerability.
### Remediation
Apply updates per vendor instructions.
### Acknowledgements
Vulnerability was discovered by Radu Motspan (Kaspersky).

### References
https://github.com/klsecservices/Advisories/blob/master/K-Mercedes-Benz-2023-009.md
Report
EN: [https://securelist.com/mercedes-benz-head-unit-security-research/115218/](https://securelist.com/mercedes-benz-head-unit-security-research/115218/)
RU: [https://securelist.ru/mercedes-benz-head-unit-security-research/111516/](https://securelist.ru/mercedes-benz-head-unit-security-research/111516/)
https://github.com/klsecservices/Publications/blob/master/Mercedes-Benz_Head_Unit_security_research_report.pdf
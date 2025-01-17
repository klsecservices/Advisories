***
# Kaspersky Advisory
## (K-Mercedes-Benz-2023-006)  Heap Buffer Overflow in libspeech
***
### Type
Heap Buffer Overflow
### Vendor
HARMAN Becker Automotive Systems GmbH
### Affected products
Mercedes Benz NTG 6 
### CVSS v3 Vector

CVSS:3.1/AV:L/AC:L/PR:N/UI:R/S:U/C:N/I:N/A:H
### CVSS v3 Score

5.5 medium
### CVE ID

CVE-2023-34401
### Vulnerability description
Head-unit NTG6 contains functions to import or export profile settings over USB. Inside profile folder there is a file, which is  encoded with proprietary UD2 codec. Due to missed size checks in the enapsulate file, attacker can achieve Out-of-Bound Read in heap memory.
### Remediation
Apply updates per vendor instructions.
### Acknowledgements
Vulnerability was discovered by Radu Motspan (Kaspersky).

### References
https://github.com/klsecservices/Advisories/blob/master/K-Mercedes-Benz-2023-006.md
Report
EN: [https://securelist.com/mercedes-benz-head-unit-security-research/115218/](https://securelist.com/mercedes-benz-head-unit-security-research/115218/)
RU: [https://securelist.ru/mercedes-benz-head-unit-security-research/111516/](https://securelist.ru/mercedes-benz-head-unit-security-research/111516/)
https://github.com/klsecservices/Publications/blob/master/Mercedes-Benz_Head_Unit_security_research_report.pdf
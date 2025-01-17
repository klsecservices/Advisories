***
# Kaspersky Advisory
## (K-Mercedes-Benz-2022-004) Null pointer dereference in AirTunes/AirPlay
***
### Type
Incorrect Access Control
### Vendor
Mercedes-Benz
### Affected products
Mercedes Benz NTG 6 - through 2021 
### CVSS v3 Vector

CVSS:3.1/AV:P/AC:L/PR:N/UI:N/S:U/C:N/I:N/A:H
### CVSS v3 Score

4.6 medium
### CVE ID

CVE-2024-37602
### Vulnerability description
An issue was discovered on Mercedes Benz NTG 6 through 2021.  A possible NULL pointer dereference in the Apple Car Play function  affects NTG 6 head units. To perform this attack, physical access to Ethernet pins of the head unit base board is needed. With a static IP address, an attacker can connect via the internal network to the AirTunes / AirPlay service. With prepared HTTP requests, an attacker can cause the Car Play service to fail.
### Remediation
Apply updates per vendor instructions.
### Acknowledgements
Vulnerability was discovered by Mikhail Evdokimov and Kirill Nesterov (Kaspersky).

### References
https://github.com/klsecservices/Advisories/blob/master/K-Mercedes-Benz-2022-004.md
Report
EN: [https://securelist.com/mercedes-benz-head-unit-security-research/115218/](https://securelist.com/mercedes-benz-head-unit-security-research/115218/)
RU: [https://securelist.ru/mercedes-benz-head-unit-security-research/111516/](https://securelist.ru/mercedes-benz-head-unit-security-research/111516/)
https://github.com/klsecservices/Publications/blob/master/Mercedes-Benz_Head_Unit_security_research_report.pdf
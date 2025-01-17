***
# Kaspersky Advisory
## (K-Mercedes-Benz-2022-002) Heap Buffer Overflow in UserData
***
### Type
Buffer Overflow
### Vendor
Mercedes-Benz
### Affected products
Mercedes Benz NTG 6 
### CVSS v3 Vector

CVSS:3.1/AV:L/AC:L/PR:N/UI:R/S:U/C:N/I:N/A:H
### CVSS v3 Score

5.5 medium
### CVE ID

CVE-2024-37601
### Vulnerability description
An issue was discovered on Mercedes Benz NTG 6.  A possible heap buffer overflow exists in the user data import/export function of Mercedes-Benz NTG 6 head units. To perform this attack, local access to the USB interface of the car is needed. With prepared data, an attacker can cause the User-Data service to fail. The failed service instance will restart automatically.
### Remediation
Apply updates per vendor instructions.
### Acknowledgements
Vulnerability was discovered by Mikhail Evdokimov (Kaspersky).

### References
https://github.com/klsecservices/Advisories/blob/master/K-Mercedes-Benz-2022-002.md
Report
EN: [https://securelist.com/mercedes-benz-head-unit-security-research/115218/](https://securelist.com/mercedes-benz-head-unit-security-research/115218/)
RU: [https://securelist.ru/mercedes-benz-head-unit-security-research/111516/](https://securelist.ru/mercedes-benz-head-unit-security-research/111516/)
https://github.com/klsecservices/Publications/blob/master/Mercedes-Benz_Head_Unit_security_research_report.pdf
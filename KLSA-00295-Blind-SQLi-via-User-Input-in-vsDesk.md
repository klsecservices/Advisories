***
# Kaspersky Security Services Advisory
## KLSA-00295 (K-vsDesk-2024-004) Use of user input in raw SQL queries in vsDesk leading to blind SQL injection
***
### Affected Hardware/Software
vsDesk 11.06.02 and possibly others
### Severity level
Impact: An attacker can access database data or cause a denial of service.

Access Vector: Network
### CVSS v4 Vector

CVSS:4.0/AV:N/AC:L/AT:N/PR:N/UI:N/VC:H/VI:N/VA:H/SC:N/SI:N/SA:N
### CVSS v4 Score

8.8
### CVE ID

CVE-2025-14603 
### Vulnerability description
The application component processes user-supplied parameters insecurely, passing them into SQL queries. This can enable blind SQL injection, potentially exposing database contents or causing the application to become unresponsive.

### Remediation
Apply patch from vendor https://vsdesk.ru/. Versions 14.0101 and on have the patch.  
### Acknowledgements
The vulnerability was discovered by Kirill Nikolaev from Kaspersky (https://kaspersky.com)

### References
https://github.com/klsecservices/Advisories/blob/master/KLSA-00295-Blind-SQLi-via-User-Input-in-vsDesk.md


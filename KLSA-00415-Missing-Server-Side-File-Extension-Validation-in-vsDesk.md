***
# Kaspersky Security Services Advisory
## KLSA-00415 (K-vsDesk-2026-001) Missing Server-Side File Extension Validation in vsDesk
***
### Affected Hardware/Software
vsDesk 14.01.01, and possibly others
### Severity level
Impact: An attacker with administrative access can execute arbitrary code in the context of the web application helper process.

Access Vector: Network
### CVSS v4 Vector

CVSS:4.0/AV:N/AC:L/AT:N/PR:H/UI:N/VC:H/VI:H/VA:H/SC:H/SI:H/SA:H
### CVSS v4 Score

9.4
### CVE ID

CVE-2026-2334
### Vulnerability description
vsDesk v14.0101 contains a file upload vulnerability within its administrative interface. Due to insufficient verification of uploaded file types on the server side, an authenticated attacker with administrative privileges can bypass existing client-side restrictions. This allows the upload of a malicious file to the web server, potentially leading to arbitrary code execution.

### Remediation
Apply patch from vendor https://vsdesk.ru/. Versions 14.0402 and on have the patch.  
### Acknowledgements
The vulnerability was discovered by Kirill Nikolaev from Kaspersky (https://kaspersky.com)

### References
https://github.com/klsecservices/Advisories/blob/master/KLSA-00415-Missing-Server-Side-File-Extension-Validation-in-vsDesk.md
https://vsdesk.ru/news/vyshla-novaya-versiya-140422


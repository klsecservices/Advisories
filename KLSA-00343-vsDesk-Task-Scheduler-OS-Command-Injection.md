***
# Kaspersky Security Services Advisory
## KLSA-00343 (K-vsDesk-2024-002) vsDesk Task Scheduler OS Command Injection
***
### Affected Hardware/Software
vsDesk 11.06.02 and possibly others
### Severity level
Impact: An authenticated attacker with administrative privileges can execute arbitrary operating system commands, potentially leading to a complete compromise of the web server.

Access Vector: Network
### CVSS v4 Vector

CVSS:4.0/AV:N/AC:L/AT:N/PR:H/UI:N/VC:H/VI:H/VA:H/SC:N/SI:N/SA:N
### CVSS v4 Score

8.6
### CVE ID

CVE-2025-14601
### Vulnerability description
 An OS command injection vulnerability in vsDesk allows an authenticated administrative attacker to execute arbitrary shell commands due to insufficient input filtering. An attacker can exploit this flaw to disrupt web server operations, expose sensitive data, or gain full control over the underlying system.

### Remediation
Apply patch from vendor https://vsdesk.ru/. Versions 14.0101 and on have the patch.  
### Acknowledgements
The vulnerability was discovered by Kirill Nikolaev from Kaspersky (https://kaspersky.com)

### References
https://github.com/klsecservices/Advisories/blob/master/KLSA-00343-vsDesk-Task-Scheduler-OS-Command-Injection.md

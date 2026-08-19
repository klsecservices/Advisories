***
# Kaspersky Security Services Advisory
## KLSA-00296 (K-vsDesk-2024-001) Admin Account Takeover via Path Traversal in vsDesk
***
### Affected Hardware/Software
vsDesk 11.06.02, 14.01.01, and possibly others
### Severity level
Impact: Allows an attacker to gain unauthorized administrative privileges and compromise the system.

Access Vector: Network
### CVSS v4 Vector

CVSS:4.0/AV:N/AC:L/AT:N/PR:N/UI:N/VC:H/VI:H/VA:H/SC:N/SI:N/SA:N
### CVSS v4 Score

9.3
### CVE ID

CVE-2025-14600
### Vulnerability description
An insecure deserialization vulnerability in vsDesk allows a remote attacker to gain unauthorized administrative access. By manipulating application configuration data, an attacker can force the system to authenticate against an arbitrary LDAP server and provision a new administrative account.

### Remediation
Apply patch from vendor https://vsdesk.ru/. Versions 14.0402 and on have the patch.  
### Acknowledgements
The vulnerability was discovered by Kirill Nikolaev from Kaspersky (https://kaspersky.com)

### References
https://github.com/klsecservices/Advisories/blob/master/KLSA-00296-Admin-Account-Takeover-via-Path-Traversal-in-vsDesk.md
https://vsdesk.ru/news/vyshla-novaya-versiya-140422


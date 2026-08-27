***
# Kaspersky Security Services Advisory
## KLSA-00294 (K-vsDesk-2024-003) Weak File Name Generation in vsDesk
***
### Affected Hardware/Software
vsDesk 11.06.02 and possibly others
### Severity level
Impact: An attacker can successfully locate and access uploaded files, which can be used to facilitate further attacks.

Access Vector: Network
### CVSS v4 Vector

CVSS:4.0/AV:N/AC:L/AT:N/PR:L/UI:N/VC:L/VI:N/VA:N/SC:N/SI:N/SA:N
### CVSS v4 Score

5.3
### CVE ID

CVE-2025-14602 
### Vulnerability description
The application generates uploaded file names using a weak and predictable method based on the request timestamp. This allows a remote attacker to accurately guess or brute-force the generated filename within a short time window.

### Remediation
Apply patch from vendor https://vsdesk.ru/. Versions 14.0101 and on have the patch.  
### Acknowledgements
The vulnerability was discovered by Kirill Nikolaev from Kaspersky (https://kaspersky.com)

### References
https://github.com/klsecservices/Advisories/blob/master/KLSA-00294-Weak-File-Name-Generation-in-vsDesk.md


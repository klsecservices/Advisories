***
# Kaspersky Advisory
## (K-Delinea-2023-001) Arbitrary File Reading in Centrify PAS
***
### Affected Hardware/Software
Centrify PAS v. 21.3 and possibly others
### Severity level
Impact: This vulnerability may allow to dump credentials for DB or even dump entire local DB. Also an attacker may retrieve encryption keys for stored credentials.

Access Vector: The vulnerability can be exploited by any authorized user with network access.
### CVSS v3 Vector

CVSS:3.1/AV:N/AC:L/PR:L/UI:N/S:C/C:H/I:N/A:N
### CVSS v3 Score

7.7
### CVE ID

CVE-2024-5865
### Vulnerability description
The application is prone to the path traversal vulnerability allowing arbitrary files reading outside the web publish directory.
### Remediation
Apply patch from vendor. Versions 23.1-HF7 and on have the patch. 
### Acknowledgements
The vulnerability was discovered by Vladas Bulavas from Kaspersky

### References
https://github.com/klsecservices/Advisories/blob/master/K-Delinea-2023-001.md


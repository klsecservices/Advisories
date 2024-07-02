***
# Kaspersky Advisory
## (K-Delinea-2023-002) Arbitrary Directory Listing in Centrify PAS
***
### Affected Hardware/Software
Centrify PAS v. 21.3 and possibly others
### Severity level
Impact: This vulnerability may allow to get sensitive information from filenames and may help to exploit arbitrary file reading vulnerability.

Access Vector: The vulnerability can be exploited by any authorized user with network access.
### CVSS v3 Vector

CVSS:3.1/AV:N/AC:L/PR:L/UI:N/S:C/C:L/I:N/A:N
### CVSS v3 Score

5.0
### CVE ID

CVE-2024-5866
### Vulnerability description
The application is prone to the path traversal vulnerability allowing listing of arbitrary directory outside the root directory of the web application.
### Remediation
Apply patch from vendor. Versions 23.1-HF7 and on have the patch. 
### Acknowledgements
The vulnerability was discovered by Vladas Bulavas from Kaspersky
### References
https://github.com/klsecservices/Advisories/blob/master/K-Delinea-2023-002.md




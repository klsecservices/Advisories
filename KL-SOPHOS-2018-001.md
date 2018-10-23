***

# Kaspersky Lab Advisory

## (KL-SOPHOS-2018-001) SQL Injection

***


### Affected Software
Software version: Sophos XG Firewall versions 16 and older, 16.5 OEM, 17.0
### Severity level
* Impact: An authenticated attacker is able to access information in database, modificate arbitrary values in database.
* Access Vector: Remote
* CVSS v3 Vector: AV:N/AC:H/PR:L/UI:N/S:C/C:H/I:H/A:H
* Overall CVSS Score: 8.5
* CVE: CVE-2018-16116
* CWE Type: CWE-89
### Software description
Sohos XG Firewall is a software firewall and network access control appliance.
### Vulnerability description
SQL injection vulnerability in AccountStatus.jsp in Admin Portal of Sophos XG firewall allow remote authenticated attackers to execute arbitrary SQL commands via the `username` GET parameter.

SQL injection vulnerability is present in `/webconsole/webpages/myaccount/AccountStatus.jsp` URL in GET parameter `username`. Exploitation requires authentication with a low-privileged account (`Audit Admin`, for example).

### How to fix

Vendor has released a patch for the vulnerability- https://community.sophos.com/kb/en-us/132637

### Credits

The weakness was discovered by specialists from Kaspersky Lab.

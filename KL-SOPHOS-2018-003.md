***

# Kaspersky Lab Advisory

## (KL-SOPHOS-2018-002) Remote Code Execution

***
### Affected Software
Software version: Sophos XG Firewall versions 17.0 and older, 17.1.
### Severity level
* Impact: An authenticated attacker is able to execute arbitrary system commands as a result of exploiting this vulnerability.
* Access Vector: Remote
* CVSS v3 Vector: AV:N/AC:H/PR:L/UI:N/S:C/C:H/I:H/A:H
* Overall CVSS Score: 8.5
* CVE: CVE-2018-16117
* CWE Type: CWE-78
### Software description
Sohos XG Firewall is a software firewall and network access control appliance.
### Vulnerability description
A vulnerability is `/webconsole/Controller` URL in Admin Portal of Sophos XG firewall that allows remote authenticated attackers to execute arbitrary OS commands via shell metacharacters in the `dbName` POST parameter. Inserting backticks in parameter `dbName` enables an attacker to execute arbitrary shell commands with root privileges. Exploitation requires authentication with a low-privileged account (`Audit Admin`, for example).

### Mitigation

Vendor has released a patch for the vulnerability- https://community.sophos.com/kb/en-us/132637

### Credits

The weakness was discovered by specialists from Kaspersky Lab.

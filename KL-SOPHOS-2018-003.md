***

# Kaspersky Lab Advisory

## (KL-SOPHOS-2018-003) Remote Code Execution

***
### Affected Software
Software version: Sophos XG Firewall versions 17.0, 17.1, 16.5 OEM, 16 and older.
### Severity level
* Impact: An attacker is able to execute arbitrary system commands as a result of exploiting this vulnerability.
* Access Vector: Remote
* CVSS v3 Vector: AV:N/AC:H/PR:N/UI:N/S:C/C:H/I:H/A:H
* Overall CVSS Score: 9.0
* CVE: CVE-2018-16118
* CWE Type: CWE-78
### Software description
Sohos XG Firewall is a software firewall and network access control appliance.
### Vulnerability description
Shell escape vulnerability is present in `/webconsole/APIController` URL in HTTP header `X-Forwarded-for`. Inserting backticks in HTTP header `X-Forwarded-for` enables an attacker to execute arbitrary shell commands with root privileges. Exploitation requires the API Configuration feature of the firewall to be enabled and made.
accessible.

### Mitigation

Vendor has released a patch for the vulnerability- https://community.sophos.com/kb/en-us/132637

### Credits

The weakness was discovered by specialists from Kaspersky Lab.

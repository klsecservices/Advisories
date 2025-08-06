***
# Kaspersky Advisory
## (K-TechPowerUp-2025-001) Code Execution / Escalation of Privileges in ThrottleStop
***
### Affected Hardware/Software
ThrottleStop.sys version 3.0.0.0 and possibly others

### Severity level
Impact: 
A malicious user-mode application can exploit the vulnerability by sending crafted IOCTL requests to the ThrottleStop.sys driver that lead to execute arbitrary code and escalate privileges
Access Vector: 
Local

### CVSS v4 Vector

CVSS:4.0/AV:L/AC:H/AT:N/PR:H/UI:N/VC:H/VI:H/VA:H/SC:H/SI:H/SA:H
### CVSS v4 Score

8.7 / HIGH
- Exploitability: Medium
- Complexity: Medium
- Vulnerable system: High
- Subsequent system: Medium
- Exploitation: High
- Security requirements: High
### CVE ID

CVE-2025-7771
### Vulnerability description
ThrottleStop.sys, a legitimate driver, exposes two IOCTL interfaces that allow arbitrary read and write access to physical memory via the MmMapIoSpace function. This insecure implementation can be exploited by a malicious user-mode application to patch the running Windows kernel and invoke arbitrary kernel functions with ring-0 privileges. The vulnerability enables local attackers to execute arbitrary code in kernel context, resulting in privilege escalation and potential follow-on attacks, such as disabling security software or bypassing kernel-level protections.
### Remediation
Apply updates per vendor instructions.
### Acknowledgements
Vulnerability was discovered by Cristian Souza (Kaspersky), Ashley Muñoz (Kaspersky), Eduardo Ovalle (Kaspersky), Francesco Figurelli (Kaspersky), and Anderson Leite (Kaspersky)

### References
https://github.com/klsecservices/Advisories/blob/master/K-TechPowerUp-2025-001.md
https://www.techpowerup.com/download/techpowerup-throttlestop/
Related article https://securelist.com/av-killer-exploiting-throttlestop-sys/117026/


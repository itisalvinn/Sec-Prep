# Privilege Escalation

How can an attacker gain higher-level access to a system? 
- exploit vulnerability
- bug or design flaw
- social engineering for admin credentials

**Windows Remote Access Elevation of Privilege Vulnerability** (CVE 2020-1530)
- Server 2008, 2012, 2016, 2019
- Windows 7, 8.1, 10
- gains elevated access of system due to an exploit on said systems

**Rule of least privilege** - user is given the minimum levels of access they need to perform their job

**Mitigation**
- patch vulnerability quickly
- update anti-virus software
- *data execution prevention* - only data in executable areas can run
- *address space layout randomization* - prevent buffer overrun at memory address


# Attack Vectors

Method of approach used by an attacker to enter a network or system. Essentially, exploiting a vulnerability to gain access and it is important to discover and close such attack vectors.

**Direct Access**
- physical access to data center, servers etc.
- *lock them down* 
- easily modify operating system (reboot with new admin password)
- use keylogger to collect usernames and passwords
- transfer files from server w/ USB
- physical tampering (e.g. pull the power, damage the equipment etc.)

**Wireless**
- modify access point config 
- always *change default credentials*
- Rogue access points (e.g. bring in external router)
- Evil twin (emulate existing access points)
- Protocol vulnerabilities (e.g. update WEP, WPA etc.)
- e.g. 2017, WPA2 Key Reinstallation Attack (KRACK)

**Email**
- common form of communication
- phishing attacks
- malware attachments
- social engineer (e.g. invoice scams)

**Supply Chain**
- lots of vulnerable steps from source to destination
- attackers can tamper with underlying infrastructure / manufacturing process
- e.g. 2013, Target credit card breach
- e.g. 2020, counterfeit Cisco equipment (fake switches)

**Social Media**
- information posted online, publicly available
- easy to identify target location, behaviour, habits etc.
- potentially reveals PII (e.g. where you were born, name of school, where you live etc.)
- 'fake friends' on socials for personal gain

**Removal media**
- circumvent firewall with USB
- portable networking devices to allow threat actors access without authentication
- can act as keyboards for the attacker
- data exfiltration (low bandwidth by downloading all data directly onto USB) 

**Cloud attack**
- public facing applications and services are vulnerable
- security misconfigurations (data permissions and public data stores)
- phishing users of cloud service
- attackers can increase load on the cloud to strain resources and potentially cause denial of service
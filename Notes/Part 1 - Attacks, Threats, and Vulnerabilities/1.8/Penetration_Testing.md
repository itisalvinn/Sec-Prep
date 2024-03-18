# Penetration Testing

Security exercise to find and exploit vulnerabilities in a system. The purpose is to simulate an attack and identify if there are any potential weaknesses that need to be fixed. Similar to a vulnerability scan; however, we take it further and try to exploit the vulnerability to gain access into the system. Often this is compliance mandated for an organization to undergo regular penetration testing by a 3rd party. 

*If you can get through, the attackers can get through*

**Note**: *Kali Linux* tool for pen testing

**Rules of Engagement**
- Must define purpose and scope
- Everyone needs to be aware of test parameters
- Define type of testing and schedule 
    - On-site physical breach
    - internal / external test
    - During / after working hours etc.
- *Rules*
    - IP address ranges
    - emergency contacts ready
    - how to handle PII
    - in-scope and out-of-scope devices / apps

**Working Knowledge**
- *unknown environment* = blind test
- *known environment* = full disclosure
- *partialy known environment* = focus on certain systems

**Exploiting Vulnerabilities**
- try to break into the system!!
    - can cause denial of service or loss of data
    - buffer overflows can cause instability
    - gain privilege escalation
- ensure there is a way to return system to normal
- many diff vulnerability types
    - password brute force
    - social engineering
    - database injections
    - buffer overflows
- *the process*
    - initial exploitation (get into the network)
    - *lateral movement* = move from system to system inside the network
    - persistence (e.g. set up backdoor, build user accounts, change passwords etc.)
    - pivot point (*establish footprint* in network and *using that access* to move to other systems / dive deeper)

**Pentest Aftermath**
- clean up
    - leave network in original state
    - remove binaries / temp files
    - remove backdoors
    - delete user accounts created during the test
- Bug Bounty
    - reward for discovering vulnerabilities
    - document for money

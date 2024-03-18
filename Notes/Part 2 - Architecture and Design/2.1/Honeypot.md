# Honeypots and Deception

A honeypot is a system designed to look attractive to attackers; a virtual world to investigate attackers and their behaviour. It is a constant battle to discern the real from the fake. 

**Honeynet**
- a collection honey pots
- more than one source and honeypot on the network
- *honeyfiles* = deceptive files for intrusion detection
- [fun informative website](https://www.projecthoneypot.org/) for honeypots etc. 

**Fake Telemetry**
- interpret big data to identify patterns within network using ML
- train machine w/ actual data
    - malware, malicious code signatures
    - malware behaviour / actions
    - **attackers can send fake data to confuse and train the machine on their malware**

**DNS Sinkhole**
- hands out incorrect IP addresses
- redirect known malicious domains to a benign IP address
- users that hit this IP address are infected (raise an alert!)
- can be integrated with a firewall 
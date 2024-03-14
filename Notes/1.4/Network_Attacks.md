# Network Attacks

**On-path attack**
- redirects your traffic then passes it onto the destination
- man-in-the-middle can view all data transmitted between the source and destination
- must be on the local network
- e.g. *ARP (address resolution protocol) Poisoning* - on path attack on local subnet; no security with ARP

    <img src="assets/ARP_poisoning.png" alt="ARP Poisoning" width="700"/>\

    ##### *ARP Poisoning*. Attacker sends victim the router's IP address to update ARP cache; vice versa with the router so all data goes through the attacker's device.

**On-path browser attack**
- middleman is on the victim's computer (via malware/trojan or something)
- malware does all the proxy work
- easy to proxy encrypted traffic
- everything looks normal to the victim
- e.g. waits for victim to login to banking account, then steals all their money using their captured data

**MAC Flooding**
- switches examine incoming traffic and adds unknown *source* MAC address to MAC address table
- send many requests to target switch containing a different source MAC address to consume available memory in MAC address table
- eventually switch reaches max capacity > becomes a hub and starts sending all traffic to all interfaces
- now attacker can *capture all network traffic*

**MAC cloning / MAC spoofing**
- attacker changes their MAC address to match MAC address of existing device
- circumvent filters against external MAC addresses
- create DoS against the user

**DNS Poisoning**
- modify client HOST file (host file takes precedent over DNS queries)
- on-path attack to modify DNS query sent to client and change their destination IP address
    - attacker modifies DNS files on server so user grabs incorrect IP
    - subsequent request retrieves that malicious IP

**Domain Hijacking**
- obtain admin access to domain registration to control where traffic flows
- don't need to touch the actual servers
- e.g. Oct 22, 2016, Domain name registrations of 36 domains changed @ brazilian bank for 6 hours

**URL Hijack**
- *typosquatting* - create a similar domain name w/ typos  
- used as an advertisement page to make money off network traffic
- malicious website to infect users that navigated there by accident
- sell similar spelling website to actual owner
- different top level domain (e.g. professormesser.**com** vs professormesser.**org**)

**Denial of Service (DoS)**
- force service to fail (overload)
    - competitive advantage
    - take adv. of system design failure or vulnerability
    - distraction for another exploit (precursor to DNS spoofing etc.)
- turn off the power
- *unintentional DoS* with wrong wiring, network loops etc.
- *DDOS* - use a botnet to create distributed denial of service
    - amplification w/ spoofed IP address + small query
    - 28 char query returns response of over 1300 chars into web server
    - attackers usually have smaller resource pool but aim to overwhelm the target
- e.g. zip bomb 
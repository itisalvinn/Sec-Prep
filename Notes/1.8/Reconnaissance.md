# Reconnaissance

Threat actors need information before they launch an attack. 

**Overview**
- gather digital footprint; learn as much as you can about the system
- understand security posture (firewalls etc.)
- minimize the attack area (focus on key systems)
- create network map (identify routers, networks, remote sites)

**Passive Footprint**
- use open source systems (e.g. social media, public website, forums etc.)
- [Open Source Intelligence](https://osintframework.com/) (OSINT)
- *Wardriving* = combine wifi monitoring and GPS 
    - search from car, plane, drone etc.
    - identify where the target network may be located
    - gather info on the network SSID, encryption, network names etc.
    - e.g. Kismet, inSSIDer, [Wireless Geographic Logging Engine](https://wigle.net/) to map out results

**Active Footprint**
- Send info into network to gain more information (Secure? Type of service? General info?)
- Ping scans, port scans, dns queries
- OS scans, OS fingerprinting
- Service scans, version scans
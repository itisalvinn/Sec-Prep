# General Terms

Define and document words that I did not understand and/or those small topics that were too short to be covered in a file.

**Bluejacking** - sending of unsolicited messages over bluetooth-bluetooth
- does not require mobile carrier 
- close radius (~10m)
- cannot access anything on the device

**Bluesnarfing** - accessing data through unauthorized bluetooth connection
- steal contact list, calendar, email, pictures, videos etc. 
- Released in 2003 but patched

**Cloud-based security** - centralized, lower costs
- no dedicated hardware, no data center to secure
- 3rd party handles infrastructure and security at the cost of reduced customization
- highly scalable and user enforced best-practices
- limited downtime

**Credential harvesting** - attackers collect login details
- stolen from browser, credential manager, sticky note, phishing email etc.
- happens in the background; can be unnoticeable

**Dark web**
- need specific software and configs
- e.g. TOR browser
- access to hacking group activities and services

**Driver Manipulation**
- capitalize on interaction between hardware and OS
- tons of sensitive information conveyed via hardware
- e.g. May 2016, HP Audio Drivers (debugging feature enabled a keylogger)

**Dumpster Diving** - when someone sifts through disposed [data] from another individual
- always dispose your data in a secure way (e.g. encrypt, burn, shred, lock etc.)
- trash is open to the public and anyone can acccess

**Dynamic Link Library** - windows library containing code and data
- many applications may use a number of different DLL's
- attackers can inject their own DLL in an application to run as part of the target process

**LAN switching** - forward or drop frames based on destination MAC address
- gather constantly updating list of MAC addresses (age out periodically)
- maintain loop free environment (spanning tree protocol)
- goal to increase efficiency of LAN + increase network scalability

**Logic Bomb** - type of malware attack when a separate event is triggered
- waits for predefined event such as a time, user action
- difficult to identify because there is no known signature
- can delete themselves after execution
- e.g. March 19, 2023 South Korea (malicious email sent out > activated a day later to steal / delete data etc.)
- e.g. Dec 17, 2016 (Real world logic bomb that disabled electric circuits at certain times)
- *need formal process and control, system monitoring, security auditing* for prevention

**MAC Adress** - Media access control address
- 'physical' adddress of network adapter
- unique to device
- 48 bits / 6 bytes long, hexadecimal
- e.g. **[8c:2d:aa]:[4b:98:a7]**
- *first 3 bytes* = organizationally unique identifier (manufacturer number)
- *last 3 bytes* = network interface controller specific (serial number)

**On-premise security** - security burden is on the client
- data center security completely managed in-house
- infrastructure costs and resource management budgeted (can be expensive)
- local team maintains uptime and availability (more downtime than cloud)
- fully responsible for security posture (this can be a *good thing!!*)

**Race condition** - undesirable situation that occurs when device or system attempts to perform two or more operations at the same time
- *time-of-check to time-of-use attack*
    - make modifications knowing there are multiple changes happening at the same time
    - [Race condition example from Prof Messer](https://www.youtube.com/watch?v=zg_kTCOcinQ&list=PLG49S3nxzAnkL2ulFS3132mOVKuzzBxA8&index=34)
- e.g. Jan 2004, Mars rover "Spirit" (stuck in reboot loop)
- e.g. 2003, GE Energy caused blackout (powerlines failed and race condition delayed alerts)

**Rainbow Table** - optimized, pre-built set of hashes
- saves time and storage space
- contains most common hashes to reduce computational time
- pre-calculated hash chains for varying password lengths

**Refactoring**
- metamorphic malware = different program each time it is downloaded
- *NOP* instructions that change the *structure but not functionality* of the malware
- reorder functions, modify application flow, insert unused data types etc.
- able to avoid signatures in anti-virus software

**Shimming**
- Windows Shim allows backwards compatibility w/ previous versions
- malware write their own shims to circumvent security
- e.g. Jan 2015, Microsoft vulnerability (elevates privilege of current user)

**Shoulder Surfing** - just look over their shoulder to get access to data; self explainatory\
- e.g. at airports, one can see everything on a work laptop screen when walking by
- important to control your input (aware of surroundings)
- use privacy filters

**Spam** - unsolicited messages (from email, forums, sms etc.)
- too good to be true etc. etc.
- various advertisements that's prob fake
- use *mail gateway* to block before it reaches user
    - allow list (trusted senders)
    - SMTP standard checks
    - reverse DNS (block if sender's domain doesn't match IP)
    - tarpitting (intentionally slow down server conversation)
    - recipient filtering (block if not specified valid address)

**Tailgaiting** - use an authorized person to gain unauthorized access to a building
- blend in with clothing
- just another form of manipulation (e.g. hands full > can you open door for me etc.)
- Preventions
    - visitor policy / badge
    - one scan, one person
    - access control w/ security check
    
**Zero day attacks**
- unknown or unaddressed vulnerability
- a race between researchers vs attackers to discover vulnerabilities in a system 

[**CVE-2021-30481**](https://nvd.nist.gov/vuln/detail/CVE-2021-30481#range-6515607) 
- Valve Steam RCE vulnerability when Source engine game is installed due to buffer overflow after Steam invite
- Apex Legends - potential RCE vulnerability discovered during ALGS March 17, 2024
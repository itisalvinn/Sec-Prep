# General Terms

Define and document words that I did not understand and/or those small topics that were too short to be covered in a file.

**Cloud-based security** - centralized, lower costs
- no dedicated hardware, no data center to secure
- 3rd party handles infrastructure and security at the cost of reduced customization
- highly scalable and user enforced best-practices
- limited downtime

**Credential harvesting** - attackers collect login details
- stolen from browser, credential manager, sticky note, phishing email etc.
- happens in the background; can be unnoticeable

**Dumpster Diving** - when someone sifts through disposed [data] from another individual\
- always dispose your data in a secure way (e.g. encrypt, burn, shred, lock etc.)
- trash is open to the public and anyone can acccess

**Logic Bomb** - type of malware attack when a separate event is triggereds
- waits for predefined event such as a time, user action
- difficult to identify because there is no known signature
- can delete themselves after execution
- e.g. March 19, 2023 South Korea (malicious email sent out > activated a day later to steal / delete data etc.)
- e.g. Dec 17, 2016 (Real world logic bomb that disabled electric circuits at certain times)
- *need formal process and control, system monitoring, security auditing* for prevention

**On-premise security** - security burden is on the client
- data center security completely managed in-house
- infrastructure costs and resource management budgeted (can be expensive)
- local team maintains uptime and availability (more downtime than cloud)
- fully responsible for security posture (this can be a *good thing!!*)

**Rainbow Table** - optimized, pre-built set of hashes
- saves time and storage space
- contains most common hashes to reduce computational time
- pre-calculated hash chains for varying password lengths

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
    


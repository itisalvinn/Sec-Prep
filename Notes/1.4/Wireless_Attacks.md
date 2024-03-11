# Wireless Attacks

**Wireless Disassociation**

Weird wifi connection appears and disappears repeatedly. *Spooky*. Caused by significant wireless DoS attack - where devices on the network suddenly cannot communicate with the access point.

*Attack overview* - Search for Wi-Fi Address (w/ aireplay-ng) then send deauthentication frames to access point and station (mobile device) to disconnect the wifi network. 

- **Management Frames**
    - 802.11 wireless includes a number of *management frames*
    - important for network operations (e.g. access point association, quality of service etc.)
    - lack of management protection frames = attacker can interfere

**802.11w update** patched these vulnerabilities to encrypt management frames and sent over an protected tunnel

**802.11ac** compliance also includes 802.11w functionality rolled out moving forward to prevent users from being removed from a wireless network

**Wireless Jamming**

Malicious interference on wireless communication systems. *Not always intentional!* (e.g. microwaves, fluorescent lights). And the attacker is usually nearby to get generate a strong disruptive signal. 

- **RF Jamming**
    - decrease signal-to-noise ratio at receiving device
    - receiving device can't get a good signal
    - send *constant* random bits / legit frames to disrupt flow of data
    - *intermittently* send random data / legit frames 
    - *reactively* send random data / frames when someone else tries to communicate  

**RFID (radio frequency identification)**

Common tech for passive wireless communication and tracking through an RFID tag. A two part system, comprising of a tag and reader that uses *radar technology*. Some uses include supply chain tagging, library books, and pet microchipping. 

- **Data capture**
    - replay attack
    - theft during data transmission

- **Spoof reader**
    - attack writes own data to tag

- **Denial of service**
    - signal jam so nobody can read the RFID

- **Decrypt Communication**
    - many default keys are on Google
    - attacker can decrypt these protect channels easily

**NFC (near field communication)**

Set of communication protocols that enables low-speed communication over a close distance. 

- **Two way wireless communication**
    - builds on RFID
    - 13.56MHz frequency compliant with ISO/IEC 18000-3

- **Payment systems**
    - ez tap payment

- **Bootstrap for other wireless**
    - helps w/ automatic bluetooth pairing

- **Access token**
    - short range encryption support
    - 'identity card'  of sort

Similar to RFID, it is susceptible to *remote data capture*, *frequency jamming*, *relay / replay attacks*, *RFC device control* (steal yo phone data etc.)
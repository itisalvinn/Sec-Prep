# Secure Protocols

**Voice and Video**
- Secure Real Time Transport Protocol (SRTP)
    - add security to RTP
    - keep convo's private
    - AES encryption
    - HMAC SHA1 for replay protection

**Time Synchronization**
- Network time Protocol (NTP)
    - exploited as amplifiers in DDOS
    - NTPsec for secure transport (2015)
- Synchronize system clocks

**Email and Web**
- Secure / Multipurpose internet mail extension (S/MIME)
    - public key encryption and digital signing of mail content
    - requires PKI (public key infra)
- Secure POP / Secure IMAP
    - encrypt with SSL
- SSL/TLS
    - browser based = always encrypt with SSL
- HTTPS
    - secure connection to transfer data
    - public key encryption (symmetric session key transferred w/ asymmetric encryption)

**IPsec (internet protocol security)**
- encrypted communication tunnel to send info securely
- Security for network layer (OSI layer 3)
    - Authentication header (AH)
    - encapsulation security payload (ESP)
- confidentiality and integrity / anti replay
- very standardized
- *file transfer*
    - FTPS (FTP over SSL)
    - SFTP (SSH file transfer)

**Lightweight Directory Access Protocol (LDAP)**
- protocol for reading and writing directories over IP network
- X.500 specification by ITU
- uses **TCP/IP**
- e.g. windows active diretory, Apple OpenDirectory etc.
- *LDAP Secure*
    - non standard implementation over SSL
- Simple Authentication and Security Layer (SASL)
    - diff auth methods (e.g. Kerberos, client certs etc.)

**Domain Name Resolution (DNS)**
- originally no security
- DNSSec (security extensions)
    - validate DNS response
    - data integrity
    - use public key crypto (signed DNS rescords)

**Routing and Switching**
- SSH usage
- Simple Network Management Protocol V3 (SNMPv3)
    - confidentiality (encrypted data)
    - integrity (no data tampering)
    - authentication (verify source)
- HTTPS
    - browser based management
    - encrypted communication

**Network Address Allocation**
- use Dynamic Host Configuration Protocol (DHCP)
    - auto provide IP host with IP address and other config info (e.g. subnet mask, gateway)
    - no built in security
- use Active Directory for DHCP authorization
- configure w/ trusted certificates
- distribute DHCP from trusted interfaces
- *Starvation Attack* = change MAC address and exhaust all available IP addresses in DHCP pool
    - limit # of MAC address per interface
    - disable if multiple MAC addresses seen

**Subscription Services**
- automated subscriptions
    - anti virus
    - IPS updates
    - Firewall updates
- diff protocols and methods to update > need encryption and integrity checks
- configure trust between client and verified servers (e.g. Certs, trusted IP addresses)
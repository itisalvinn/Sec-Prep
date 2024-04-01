# Authentication Methods

**Directory Services**
- keep all of organization's username / passwords in single database
- large distributed database that is constantly replicated
- all auth requests reference this directory (single auth)
- e.g. Kerberos (auth service requests between trusted host across untrusted network), LDAP (lightweight directory access protocol)

**Federation**
- allow authnetication to your network using credentials stored at a 3rd party
- e.g. Google login, Facebook login, LinkedIn login etc.

**Attestation**
- prove hardware is really yours
- becomes difficult as number of devices scale
- *remote attestation* - device provides operational report to a verification server

**Short Message Service (SMS)**
- *text message* with verification code etc. to predefined phone number
- security flaws
    - phone number can be reassigned
    - text can be intercepted
- *push notification* to specialized app
    - apps have vulnerabilities
    - pushes sent over the network may not be protected

**Authentication Apps**
- pseudo random token generator
- e.g. Microsoft Authenticator, Google Auth, SalesForce Auth
- physical hardware token generator
- software based token generator app
- *Time-based One Time Password (TOTP)* - uses secret key and time of day (e.g. generate new key every 30s)
- *HMAC-based One Time Password (HOTP)* - keyed hash message auth code, used once and never again
    - valid until you actively request a new one
    - moving factor is *counter based*
    - generator + server must sync

**Phone Call**
- provide token over the phone (e.g. 'Your code is 1-6-2-5-1-7's)
- security flaws
    - phone call can be intercepted / forwarded
    - phone number can be added to another phone

**Static Codes**
- authentication factions that don't change
- password / passphrase / PIN etc.
- part of multifactor auths

**Smart Card**
- integrated circuit card
- contactless or contact tap
- *must have physical access to provide digital access* (digital certificate)
- e.g. credit cards
- part of multifactor auth (e.g. use with PIN)
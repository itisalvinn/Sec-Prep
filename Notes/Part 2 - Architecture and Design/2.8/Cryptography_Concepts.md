# Cryptography concepts

*Secrets and confidentiality*

**Plaintext** - unencrypted message

**Ciphertext** - encrypted message

**Cipher** - algorithm used to encrypt / decrypt the message

**Cryptanalysis** - art of cracking encryption
- constant research to identify weaknesses in ciphers
- avoid weak algo's
- adapt new, stronger algo's

**Keys**
- add keys to cipher for encryption
- larger keys are *generally* more secure 
- can have single or multiple keys

**Key Strengthening**
- ideally *want a larger encryption key*
- hash password (multiple times)
- key stretching
    - bcrypt library
    - password based key derivation (PBKDF2)
- salt the hash

**Lightweight Crypto**
- rising tech created from internet of things devices (IoT)
- new standards introduced to improve encryption
- goal = low cost, high strength

**Homomorphic Encryption**
- perform calculations on data while it's encrypted
- decrypted data can only be viewed w/ private key
- valuable when storing data in cloud
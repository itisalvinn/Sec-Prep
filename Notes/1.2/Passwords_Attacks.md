# Password Attacks

Plaintext / unencrypted easy to steal. *HORRIBLE*.\
**Hashing** adds a layer of security (if no collision) as it encrypts the data with a secure hashing algo (e.g. SHA-256).\
*note*: for one hash algo, one unique input will create one unique output\
**Salting** also adds a layer of security by adding random data before hashing (e.g. same password + salt = diff hash)

- **Spraying attack**
    - try to access account from a list of common passwords
    - move onto next account and so on 
    
- **Brute Force**
    - try every possible combination until hash matches
    - *online* = very slow and easily stopped by security protocols
    - *offline* = download password hash file and compare; lots of computations but won't be locked out
    
- **Dictionary Attack**
    - use dictionary to find common words / common word list
    - try substitute letters
    - distribute over many computers to reduce computational time
    - *rainbow table* may need diff set of hashes for diff systems

Check out [haveibeenpwned.com](https://haveibeenpwned.com/) for something fun!

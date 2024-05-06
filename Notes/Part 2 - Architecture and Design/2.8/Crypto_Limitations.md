# Cryptography Limitations

Not all implementations and situations are the same! And bad techniques can't be saved. So don't be bad.

**Limitations**
- Speed
    - crypto adds overhead and load
    - CPU needs power
- Size
    - encrypted data matches size of data to encrypt
    - e.g. AES block size 128 bits / 16 bytes - if we only encrypt 8 bytes, we have to fill in another 8 bytes
    - adding extra padding could end up using *more* storage 
- Weak Keys
    - larger keys = stronger
    - e.g. weak in RC4 > WEP security issues
- Time
    - larger files = longer time
    - asymmetric slower than symmetric
- Longevity
    - crypto tech can become less secure over time
    - will it still be secure in 5 years? 10? 20?
    - don't keep using same key!
- Predictability and Entropy
    - random numbers
    - random phrase
    - random bits
- Key reuse
    - find balance between cost and benefit
    - same key = less cost, less overhead, less complexity, higher risk w/ breach
    - new key = more overhead, more secure, expensive / difficult to change
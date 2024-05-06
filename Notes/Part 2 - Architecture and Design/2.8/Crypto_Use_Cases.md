# Cryptography Use Cases

**Finding Balance**
- Low power devices
    - smaller key sizes
    - use Elliptic Curve crypto for asymmetric encryption
- Low latency
    - fast computation time
    - symmetric encryption
- High resiliency
    - larger key sizes
    - add hashing for data integrity

**Use Cases**
- Confidentiality
    - file level, drive level Encryption etc.
- Integrity
    - prevent data modification
    - validate contents w/ hash
    - secure storage
- Obfuscation
    - malware encrypts active malware code
    - decrypt on execution and runs on infected machine
    - yikes
- Authentication
    - password hashing
    - add salt
- Non repudiation
    - hash + asymmetric encryption
    - confirm authenticity of data
    - e.g. digital signature
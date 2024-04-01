# Secure Coding Practices

A balance between time and quality. 

**Stored Procedudes**
- SQL code should not be modifiable
- stored procedures used to limit client interactions (e.g. CALL **method here**)

**Code Reuse / dead code**
- use old code to build new applications / copy paste
- may reintroduce code vulnerabilities to new code base
- *dead code* - code logic not used
- make sure we know exactly how the code is functioning to prevent vulnerabilities and risks

**Input Validation**
- validate actual vs expected data input
- *normalization* =  check and correct input
- e.g. zip code should be only X characters long with letter in X column
- *fuzzing* = automated software testing technique that injects invalid / unexpected inputs to identify defects and vulnerabilities
- **validation points**
    - server side validation (safer!)
    - client side validation 
    - both?

**Memory Management**
- must be mindful of memory usage as a developer
- never trust data input!
- *buffer overflow* - amount of data in a buffer exceeds storage capacity; extra data overflows into adjacent memory locations and corrupts / overwrites them
- some built-in functions are insecure

**Third-Party Libraries and SDKs**
- use existing application code (written by someone else)
- extends functionality of programming language
- speeds up the development process
- *may or may not be secure!!*

**Data Exposure**
- application handles a lot of sensitive data / PII
    - storage encryption?
    - network encryption?
    - visual privacy?
- verify data input / output are not exposed

**Version Control**
- create file, make changes, track changes and so forth in a cloud
- compare file current and previous files for modifications
- e.g. GitHub, GitLab, BitBucket
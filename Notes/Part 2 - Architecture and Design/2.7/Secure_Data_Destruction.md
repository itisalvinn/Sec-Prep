# Secure Data Destruction

As a security professional, we need to know what data should be destroyed, and what data should not be destroyed. In the former scenario, it must be done in a secure manner such that attackers cannot recover sensitive information from it while respecting the law. Legal issues!!

**Protecting your trash**
- secure your garbage!
    - fence / lock what you dispose
- shred / burn old documents
- pulp the paper
    - remove ink
    - recycle it etc.

**Physical Destruction**
- shredder / pulverizer
- drill / hammer
- *degausser*
    - process to remove electromagnetic field on the drive
    - destroys data
    - drive becomes unusable
- incineration

**Cerficate of Destruction**
- evidence that 3rd party has successfully destroyed the data
- confirmation on how they destroyed it
    - type of equipment
    - method used etc.
- paper trail of broken data
    - e.g. serial numbers destroyed

**Sanitizing media**
- remove / purge data from storage / data base etc.
    - only delete parts
- wipe data (unrecoverable!)
    - overwrite data storage locations
    - need to reuse media but not restore data
- e.g. UK National Heath Service Surrey, July 2013
    - 3rd party sold drives that were to be destroyed
    - certificate "provided"
    - 3000 patient records exposed
    - 200k fine
- **use file level overwriting**
    - *sdelete* command
    - *DBAN* app
    - *physical destruction*
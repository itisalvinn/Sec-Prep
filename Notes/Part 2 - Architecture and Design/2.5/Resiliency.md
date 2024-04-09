# Resiliency

Note that redundancy =/= always available!

**Non-persistence**
- cloud always in motion
- constantly built and torn down
- snapshops to capture current config and data (preserve state)
    - revert to known state
    - rollback to known config (don't modify data)
    - live boot media (e.g. usb)

**High Availability**

- always on, always available
- many components working together as an automatic failover mechanism
- high uptime = higher cost (more resources required)
- *note* - redundancy aims to eliminate that point of failure but not how to handle 

**Order of Restoration**
- application-specific
    - restore components one at a time depending on infrastructure
    - e.g. database restored before app is live
- back-up specific
    - *incremental backups* = restore **full back up + all subsequent** incremental ones
    - *differential backups* = restore **full back up + last** differential one
    - full backups

**Technology Diversity**
- reduce impact of OS vulnerabilities
    - e.g. zero-day impacting one version will not translate to organizational wide outage
- multiple security devices
    - e.g. firewall, spam filter, IPS etc.
- multiple vendors
    - utilize different 3rd parties
    - if a problem with 1 vendor, you have other layers of security
- cryptography
    - diverse certificate authorities
- controls
    - admin controls
    - physical controls
    - technical controls
    - *combine for in depth defense*
# Disk Redundancy

**Overview**
- Duplicate parts of the system
    - if one part fails, redundant part used
- Ability to maintain uptime
- Failure resilient (hardware, software, systems always available)
- multipath I/O - can redirect traffic to different channels if one is not available
    - multiple fibre channel interfaces w/ multiple switches
- *RAID* (redundant array of independent disks)
    - use of multiple drives
    - data continues to be available if one breaks

**Geographic Dispersal**
- some locations are highly susceptible to natural disasters (e.g. hurricane, flooding, tornadoes)
- diversify data center locations in case 1 goes down
- increase uptime
- east / west coast benefits
- e.g. disaster recovery center

**RAID**
- *Raid 0* - striping without parity
    - high performance and no fault tolerance
- *Raid 1* - mirroring
    - duplicates data for fault tolerance
    - requires twice the disk space
- *Raid 5* - striping with parity (place pieces of info on separate drives)
    - fault tolerant
    - requires one additional disk for redundancy
- can combine multiple RAID usage to customize redundancy and storage space
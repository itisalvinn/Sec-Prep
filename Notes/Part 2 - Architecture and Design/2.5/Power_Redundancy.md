# Power Redundancy

Power is an essential resource for our devices. Without power, everything goes down. As such, it is crucial to maintain power during outages, incidents, and unexpected events. 

**UPS**
- uninterruptible power supply
- short term back up power
- e.g. in the case of blackouts, surges, brownouts etc.
- *types*
    - offline / standby = switch over when power is lost, simple & cheap
    - line-interactive = when voltage slowly diminishing, UPS slowly ramps up power
    - on-line / double-conversion = always providing power, no switching process but expensive & complex

**Generators**
- long term power back up
- fuel storage required
- e.g. power an entire building
- requires a few minutes to start up generator (UPS powered!)

**Dual-Power supplies**
- multiple sources
    - internal server power supplies
    - external power circuits
- each power supply can handle 100% of the load
    - e.g. 2 units would normally run at 50% load each
- *hot swappable* = easy to replace without powering down

**Power Distribution Units (PDU)**
- *kinda like a power bar but better*
- provide multiple power outlets (e.g. a rack of them)
- manage power capacity
- ability to enable or disable individual outlets

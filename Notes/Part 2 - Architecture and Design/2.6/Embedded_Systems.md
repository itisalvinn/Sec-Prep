# Embedded Systems

Microprocessor based hardware with software designed for a specific function or system. 

e.g. Traffic light controller, digital watch, medical imaging system

**System on a Chip (SoC)**
- multiple components running on a single chip
- small form factor (simple decives)
    - external UI support
    - cache / flash memory
    - lower power consumption
- difficult to upgrade hardware
- limited default security options 
- e.g. raspberry pi

**Field programmable gate array (FPGA)**
- configurable integrated circuit 
- can program device in the field
- doesn't require hardware replacement
- common infrastructure

**Supervisory Control and Data Acquisition System (SCADA)**
- large scale industrial control system (ICS)
- PC manages equipment (e.g. power generation, refining, manufacturing)
- distributed control systems
- extensive segmentation from network 
    - no access from outside

**Internet of Things (IoT)**
- smart devices / general products
- e.g. sensor, thermostats, smart watch etc.
- allows tons of automation
- weak security defaults

**Specialized Devices**
- devices with single goal in mind
    - e.g. heart monitor, insulin pump
    - often use older OS / not many upgrades
- vehicles
    - internal controls
    - e.g. Tesla 
- aircraft
    - analytical tools for flight usage
    - high risk of damage if there is an outage

**Voice over Internet Protocol (VOIP)**
- replacing analog phone lines 
- complex embedded systems
- standalone devices 
    - boot process
    - individual configs etc.

**HVAC**
- heating, ventliation, air con
- integrated into fire system (safety!)
- PC manages equipment
    - cooling / heating monitor
    - network of devices for diff parts of the building etc.

**Drones**
- flying vehicles controlled from ground
- extensive commercial and non commercial use
- *may need license*

**Multifunction devices (MFD)**
- one device, many uses
    - printer, scanner, fax machine
- sophiscated firmware
- images may be stored locally on device and retrieved externally

**Real time operating system (RTOS)**
- operating system with deterministic processing schedule
    - no time to wait for other processes
- e.g. industrial equipment, military environments, anti-lock breaks
- need compromise between security vs smooth operation
    - don't want security to get in the way of equipment functionality
- *surveillance systems*
    - video / audio
    - security of monitoring system (restrict access?)
    - physically difficult to replace cameras
    - easy to upgrade firmware
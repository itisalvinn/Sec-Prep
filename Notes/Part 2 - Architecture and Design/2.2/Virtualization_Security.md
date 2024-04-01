# Virtualization Security

Cloud computing brings a huge advantage through the ability to deploy new instances extremely quickly, and easily. New server? New networks? New firewalls? Multiple infrastructures? All good. However, as more and more get built, it becomes a problem when mismanaged or excessive. 

**VM Sprawl**
- virtual machines created everywhere
- not sure which VM is related to which application
- extremely difficult to deprovision
- need formal process and detailed documentation to create / remove VM's

**VM Escape Protection**
- VM's should be self contained ... *right?*
- *VM Escape* - attack where an individual on one VM can gain access to resources on a different VM
- e.g. March 2017, Pwn2Own Competition (JavaScript engine bug in Microsoft Edge sandbox > Windows 10 kernel bug > Hardware Simulation bug in VMware to escape host)
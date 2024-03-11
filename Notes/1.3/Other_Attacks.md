# Other Application Attacks

**Memory vulnerabilities** - Very difficult to find and create a useful advantage but extremely powerful

**Memory Leak**
- unused memory not properly released
- eventually uses all available memory
- system crashes

**NULL Pointer deference**
- points memory to nothing / null 
- application crashes > cause denial of service 

**Integer overflow**
- arithmetic operation outputs numeric value falling outside of allocated memory space
- can lead to buffer overflow

**Directory Traversal**
- read files from web server that are outside of website's file directory
- *users should not be able to browse Windows folder* 
- exploit web server / web app vulnerability
- *Improper error handling* gives away too much detail
    - network info
    - memory dump
    - stack traces
    - database dumps

**API Attacks**
- vulnerabilities in API to expose sensitive data, DoS, gain privilege access
- many API requests sent b/w client-server 
- attackers can exploit these to retrieve PII

**Resource Exhaustion**
- specialized DoS (one device, low bandwidth)
- *ZIP bomb* (42KB zip decompresses to 4.5PB)
- *DHCP starvation* (attacker floods network with IP address requests from diff MAC addresses until DHCP server runs out)
# Infrastructure as Code

Infrastracture is the foundation required to operate the system (e.g. servers, network, infra as code etc.). Here, we are writing code to create the infrastructure and then deploy it autonomously - using description code, we can ensure each build is deployed identically, everytime.

**Software Defined Networking (SDN)**
- uses software based controllers or API's to communicate with underlying hardware infrastructure to direct network traffic
- *centrally managed* (single, global view)
- open standards / vendor neutral
- easily deployed, scalable, and flexible to use

**Software Defined Visibility (SDV)**
- framework that is highly programmable and easily to automate for newtork traffic visibility
- allows us to react and respond to network traffic w/ dynamic deployment
- data encapsulated and encrypted w/ VXLAN and SSL/TLS
- e.g. deploy security devices to monitor application traffic in real-time
# Provisioning and Deprovisioning

Often times in IT, we set up and take down a number of different infrastructures which require the assignment and withdrawal of a variety of resources. Additionally, the concept of providing user access and managing such permissions is also important at this stage. 

**Provisioning**
- deploy application instance (e.g. webserver, database server, middleware etc.)
- application software security
- network security (e.g. VLAN, internal / external access configs etc.)
- workstation security

**Scalability and Elasticity**
- how much workload can we handle and how are we going to approach it?
- *scalability* = ability to increase workload given infrastructure 
- *elasticity* = ability to increase / decrease available resources as workload changes

**Orchestration**
- *automate provisioning and deprovisioning* of applications (in cloud computing)
- entire apps can be instantly provisioned
- location does not matter
- consistent deployments given a baseline
- **security policies** should be part of the orchestration

**Deprovisioning**
- dismantling and removing an application instance
- security deprovisioning 
    - don't leave open holes
    - don't close important ones
- firewall policies reverted (remove access)
- securely dispose of data
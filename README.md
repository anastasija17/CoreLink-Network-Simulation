# CoreLink-Network-Simulation
Simulation of network for CoreLink company using Cisco Packet Tracer

The company CoreLink is a company that consists of a central office stationed in Belgrade and a smaller office located in Nis. The main office consists of 3 buildings, while there is only one building in Nis.

## Requirements:

Create a network topology with major components that supports the following:

*Main office* 

**The first building** - it houses the following departments: administration, finance and accounting, administration and management, as well as the human resources department. Staff computers are distributed throughout the building and some network equipment is expected to be shared.

**Second building** - the second building houses the production and quality control department, as well as the logistics and procurement department.

**The third building** - consists of the research and development department, as well as the IT department. The DNS server and other necessary servers are hosted within the IT department, while the e-mail server is hosted externally on the Cloud.

*Office in Niš*

This branch has only two departments, the legal department and the strategy and analytics department.

1. It is necessary to configure the base device as well as several end devices to ensure end-to-end network connectivity, as well as access to internal and external servers.

2. Provide access to a wireless connection within each department.

3. For each department, ensure the distribution of addresses so that 120 devices can be connected.

4. Each department is expected to be on its own dedicated IP network.

5. The switches should be configured with their respective VLANs and security settings.

6. Passwords need to be set on routers and switches.
   
7. Configure NAT.

8. Provide access to devices from only one VLAN using SSH.

9. Use OSPF to provide routing for internal network routes as well as external routing.

10. Provide traffic filtering using appropriate access control lists.

11. For the devices in the office in Belgrade, dynamic IP addresses are expected to be obtained using a DHCP server, except for the information technology department where the servers are located and where the addresses 
   are assigned statically.

12.  Within the office in Niš, addresses are statically assigned to devices in both departments.

# TELECOMMUNICATION SYSTEM COMPANY

## Overview
This project showcases the network architecture of a telecommunication system designed for an enterprise. The design ensures efficient communication, high availability, scalability, and robust security measures.

## Network Features
- **VLAN Segmentation**:  
  - VLAN 10: Customer Services  
  - VLAN 11: Customer Services Phones  
  - VLAN 20: Human Resources  
  - VLAN 21: HR Phones  
  - VLAN 30: Management  
  - VLAN 31: Management Phones  
  - VLAN 100: Server Infrastructure (Subnet: 172.0.0.0/28)

- **High Availability and Redundancy**:  
  - **HSRP (Hot Standby Router Protocol)** for seamless failover.  
  - **LACP (Link Aggregation Control Protocol)** for link aggregation and load balancing.

- **Secure Zones**:  
  - Inside Zone  
  - Outside Zone  
  - DMZ (De-Militarized Zone)  

- **VPN Connectivity**:  
  - GRE + IPSEC tunnels to securely connect remote areas.

## Architecture
- The network includes multiple areas:
  - **Area 0**: Core network infrastructure.  
  - **Area 1**: Administrative communication.  
  - **Area 2**: External connections.  

- VLAN 100 hosts server infrastructure for centralized resource management.

## Key Advantages
- Enhanced security with proper zone isolation.  
- Scalability for future expansion.  
- Reliability through redundancy protocols.  

## Diagram
The network diagram illustrates the complete design, including VLANs, zones, and device connections.  
*Please refer to the attached image for visual details.*

## Author
Designed and implemented for an enterprise-grade telecommunication solution.

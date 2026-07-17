# OSPF Network Labs
This repository contains my completed OSPF network labs for my CCNP studies. The labs are designed to help me understand and implement OSPF in a variety of network topologies and scenarios. Each lab includes a detailed explanation of the network design, configuration and topology diagrams. 

# Lab 1: Basic OSPF Configuration
In this lab, I configured a simple OSPF network topology implementing four of the OSPF router types(Backbone, Standard, Stub, and Totally Stubby). To add some complexity Area 30 which was the totally stubby area was connected to area 0 via a virtual link. The lab was designed to help me understand the different OSPF router types and how they interact with each other in a network.

## Lab Topology
![image alt](https://github.com/CathalLovesFood/OSPF-Network/blob/c5e2829a9aab3ae4b83e91016fcd7cd3c31d7bb6/Lab%201/Diagrams/Pasted%20image.png)

## Tasks
1. Configure OSPF on all routers in the network.
2. Specify R1 as the DR in Area 0.
3. Create a virtual link between R3 and R6 to allow R6 to function as an ABR for Area 30.
4. Verify OSPF configuration and routing tables on all routers.
5. Test failover capabilities by shutting down one of the routers and observing how the other routers adjust their routing tables.
6. Document the configuration and results of the lab.

## Configuration Files
The configuration for this lab can be found Here: [Lab 1 Configuration](<Lab 1/Config>)

# Lab 2: OSPF Route Redistribution and NSSA
This lab focused on OSPF route redistribution and the implementation of a Not-So-Stubby Area (NSSA). The lab was designed to help me understand how to redistribute routes between different routing protocols and how to configure an NSSA in an OSPF network. The topology for this lab is largely based on the previous lab, with the addition of a R8 which is running BGP and connected to R1 and R9 which is running EIGRP and connected to R2. 

## Lab Topology
![image alt](https://github.com/CathalLovesFood/OSPF-Network/blob/9fa92b965ae3eab775ddd6ae190fba07ba05fe0b/Lab%202/Diagrams/Pasted%20image.png)

## Tasks


## Configuration Files


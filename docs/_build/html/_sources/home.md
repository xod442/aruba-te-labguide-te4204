![Lab Overview](images/hpe-logo2.svg)

![Disclosure](images/disclose.png)


<h1>HPE Aruba Networking CX10K Spine/Leaf Workshop</h1>

# Lab Overview
During this session you will deploy a spine-leaf network as part of a distributed services architecture based on the CX 10000 Switch integrated stateful firewall preventing all traffic between two vlans but allowing ssh. You will use Aruba Fabric Composer to orchestrate the L3 spine-leaf. In addition, you will integrate AMD Pensando Policy and Services Manager as the intermediary between the CX 10000 switches and Fabric Composer for policy deployment and orchestration.

### Introduction  
The Aruba CX 10000 Series Switch introduces a ground-breaking data center switch category known as Distributed Services Switch (DSS). It combines top-notch Aruba CX data center L2/3 switching capabilities with the industry's pioneering hardware accelerated programmable processor, Pensando P4. This remarkable integration enables stateful firewall services to be delivered inline and at scale, offering wire-rate performance and significant enhancements compared to traditional data center L2/3 switches.  

In this workshop, students will have the opportunity to access two of these innovative switches as top of rack leafs. A HPE Aruba Networking 6300 will be used as a spine switch usand all the switches will be managed with the HPE Aruba Networking Fabric Composer (AFC), a powerful API-driven, software-defined orchestration solution. Additionally, they will be able to deploy policies synchronized with the AMD Pensando Policy Services Manager (PSM).  

### Objective
1. Use Aruba Fabric Composer (AFC) to configure a simple Layer 3 datacenter fabric with Ethernet VPN (EVPN) - Virtual Extensible LAN (VXLAN) and Symmetric Integrated Routing and Bridging (IRB) 
2. Observe the integration between VMware vSphere and configure AMD's Pensando Policy Service Manager (PSM) 
3. Create, deploy, and test Aruba CX 10000 (CX10K) switch traffic flow policies. 


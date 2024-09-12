![Lab Overview](images/hpe-logo2.svg)

![Disclosure](images/disclose.png)


<h1>HPE Aruba Networking Telemetry with CX10K and ELK</h1>

<h2>Technical Enablement Hands-On Lab Guide</h2>

# Lab Overview
During this session you will focus on a piar of HPE Aruba CX10K top of rack data center switches. You will configure policy to force the traffic from multiple vlans into the DPU chips inside the CX10K switch. The AMD Pensando Policy Services Manager (PSM) will program the DPU chips with the policy it recieves from the AFC. The DPU's will forward unsampled IPFIX flow data and firewall logs to an ELK stack for further visualizations.

### Introduction  
The Aruba CX 10000 Series Switch introduces a ground-breaking data center switch category known as Distributed Services Switch (DSS). It combines top-notch Aruba CX data center L2/3 switching capabilities with the industry's pioneering hardware accelerated programmable processor, Pensando P4. This remarkable integration enables stateful firewall services to be delivered inline and at scale, offering wire-rate performance and significant enhancements compared to traditional data center L2/3 switches.  

In this workshop, students will have the opportunity to access two of these innovative switches as top of rack leafs. Both switches will be managed with the HPE Aruba Networking Fabric Composer (AFC), a powerful API-driven, software-defined orchestration solution. Additionally, the results of the flow information will be visible in an open-source application called Kibana
### Objective
1. Use Aruba Fabric Composer (AFC) to configure policy to redirect traffic to the DPU
2. Review of PSM and DSS 
3. Visualize IPF Flows in Kibana (ELK). 


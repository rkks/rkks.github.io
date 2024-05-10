
Professional Summary
--------------------

Since Feb/2018
:   *Sr. Principle Engineer, Lead for Clustering, HA and TWAMP SLA* at **[Versa Networks, Ltd.](https://www.versa-networks.com/)**

As a Lead, Ravi delivers **\#2** large scale solutions, **\#1** patent on tehnologically significant area, and assists in fire-fighting various customer issues.

- *[Clustering for I/O and Services Scaling over Versa VOS](https://www.versa-networks.com/products/versa-flexvnf/)* provides an elastic solution to increase
 aggregate throughput of any deployment by horizontal scaling of VOS nodes. When extended to public Clouds, this can scale on-demand. Aim is to provide a linear
 scale-out/scale-in architecture to deliver **20 times** the throughput of any individual appliance. Ravi implements core algorithm for traffic distribution and
 session accounting.

- *[TWAMP](https://versa-networks.com/documents/solution-briefs/Versa-Zero-Trust-Architecture-Overview.pdf)* feature aims to provide fully RFC 5357 compliant,
 interoperable, and scalable Control/Test protocol stacks for SLA measurement in brownfield deployments having multi-vendor appliances. It interoperates
 with Cisco IOS, Juniper JUNOS, Nokia AOS and Arista EOS. It scales upto **64K sessions** and performance of **<20ms inter packet gap**. Together with the Versa
 SASE Client (Endpoint Agent) and Versa Cloud Gateway, it provides last-mile SLA reports with real packet-loss measurements for remote access users and provides
 historical data. Ravi single-handedly implements whole protocol stack on VOS and ports it to multiple OSes for pairing with respective endpoint agents.

- *[Split-Brain avoidance in Inter-Chassis HA](https://versa-networks.com/news/2021/versa-granted-15th-patent-extending-sase-leadership/)* solution provides a
 novel way to reliably detect peer node down. Solution is granted patent **USPTO #10972337**. Ravi implements the core solution and guides team members to
 extend the same. Ravi also implements a solution to detect, isolate, and highlight issues in configuration between nodes participating in Inter-Chassis HA.
 This assists to resolve issues before they begin to impact functioning of the system. Ravi develops the core framework and provides training, references and
 help to implement plugins for various HA-aware modules in Versa VOS.

Sep/2014 - Feb/2018
:   *Storage Networks Developer* at **[Cisco Systems, Inc.](http://www.cisco.com/)**

As Individual Contributor, delivers **FCoE over Fabric Extender (FEX)** integration for proprietary ASIC based F4 line-cards on N7000 family of DC switches and
 Broadcom Trident3 chipset based N9000 family of DC switches.

- Ravi develops innovative *[lossless on-demand tracing](https://www.kernel.org/doc/html/v4.17/trace/ftrace.html)* feature for system-wide runtime debug trace
 logging without affecting performance on NXOS for all N9000, N7000, N3000 family of switches. By nature logs are lossy as buffering, block device driver, and
 file system syncing work on best-effort basis. Idea is to have elastic, realtime buffer in RAM for lossless log collection. This helps to reduce back-and-forth
 with customers, improves issue resolution time, and customer satisfaction.
    - Ravi is **invited for presenting it to NXOS Architecture Forum** and feature is used on all product lines.

- *[N9000 DC Leaf/Spine Switches](http://www.cisco.com/c/en/us/td/docs/switches/datacenter/nexus9000/sw/7-x/FCoE/configuration/guide/b_Cisco_Nexus_9000_Series_NX-OS_FCoE_Configuration_Guide_7x/b_Cisco_Nexus_9000_Series_NX-OS_FCoE_Configuration_Guide_7x_chapter_0100.pdf)* form the backbone of ToR & EoR offerings from Cisco
 for Leaf and Spine Data Center fabrics. Built over ultra-low-cost homegrown ASICs as well as commodity Broadcom chipsets, these switches provide best value for
 money with consistent low latency and high throughput. As brownfield DCs have a mix of old and new servers, there is demand for higher number of ports for low
 cost. *Fabric Extenders (FEX)* fills that gap by extending number of ports available on a switch by many fold at a fraction of their cost. FCoE is a tunneling
 protocol that provides access to Fiber Channel/FC Storage devices over Ethernet using Converged Network Adapters (CNAs). The ethernet is turned into loss-less
 SAN through a collection of DC specific standards and extensions like Priority Flow Control, LLDP DCBX, SSPF, Naming Server, and so on. Ravi develops support
 for FCoE over FEX connected to Broadcom based N9000 line-cards by programming FEX, Trident3 chipset, Control plane, and network drivers on SUP3 as required.

- Ravi delivers *[Linux LXC container based NXOS ISSU](https://blogs.cisco.com/datacenter/data-center-high-availability-redefined)* support for FCoE N9000 ToR
 swithces by modifying relevant Kernel Loadable Modules/KLMs in FCoE packet processing path on N9K ToR switches.

- *[N7000 DC](http://www.cisco.com/c/en/us/td/docs/switches/datacenter/nexus7000/sw/fcoe/config/cisco_nexus7000_fcoe_config_guide/fcoe_over_fex.pdf)* switches
 formed the Core layer of 3-layered DC Fabric architecture of the past. These switches provided high bandwidth, traffic engineering and DC-Interconnect/DCI WAN
 acceleration features. While some Access layer features like VDP, LLDP/DCBX, User ACLs, and Overlay VTEP were left out in favour of Access switches like N3000,
 few others like VNTag/FEX, VPC/MLAG, and CDP were implemented in N7000 switches for Collapsed-Core architectures where Core Switch also assumes responsibility
 of Aggregation layer. Ravi ports support for features like FCoE over Fabric Extender/FEX, FEX Active-Active, vPC/MLAG, Phy-Port vPC, and FabricPath over N7000.

May/2012 - Aug/2014
:   *Core Router Developer* for **[Juniper Networks, Inc.](http://www.juniper.net/)**

As Individual Contributor, develops control-plane infra for proposed new **petabyte scale** multi-chassis router stacking project.

- *[Project Coeus for PTX](https://www.juniper.net/uk/en/products-services/routing/ptx-series/)* is conceptualised as a multi-chassis stackable router solution
 to provide higher port density while protecting existing investments in PTX family of routers. This solution interconnects multiple PTX routers to each other
via new fabric chassis using 400Gbps QSFPs. It can expand into multi-stage CLOS network by layering fabric chassis. Ravi implements the chassis manager support,
inter-chassis topology monitoring, control-plane interconnect and master chassis election for role assignment and data synchronization.
    - Develops innovative method of **reusing IS-IS as loop-free topo-mgmt solution** without overhead of STP
- *[T4000 standalone](http://www.juniper.net/uk/en/products-services/routing/t4000/)* is a high density line-card for T-series core routers. Ravi develops the
 **fault detection, isolation, and recovery framework** for high-speed SERDES based ASIC interconnects in products.

Aug/2011 - May/2012
:   *Security Session Exchange Developer* for **[Stoke Networks, Inc.](http://www.stoke.com/)**

As Individual Contributor, develops statistics harvest infra on Netlogic XLP processors, implements clock synchronization mechanisms for *[SSX3000 Security
 Exchange Gateway](https://www.lightreading.com/stoke-updates-gateway/d/d-id/666148)*.

- Implements 64-bit counter infra over PCIe-aperture mapped from NPU registers onto Management CPU
- Solves packet-engine and DMA issues, optimizes packet-path on XLP for higher throughput.
- Optimizes the packet-path using Netlogic XLP NPUs to achieve Line-rate IPSec Encryption Gateway.

Feb/2007 - Jul/2011
:   *Network Solutions Developer* at **[Continuous Computing, Ltd.](http://www.ccpu.com/)**

As a Technical Leader, delivers **\#2** carrier-grade and **\#2** enterprise-grade solutions mentoring a **team of 6**.

- *[FastPath SCTP](http://www.radisys.com/2010/continuous-computing-optimizes-trillium-sctp-fast-path-to-achieve-unprecedented-10x-performance-improvement/)*
is a carrier-grade, highly optimized, stateful gateway solution. It gives bi-di throughput of **1M pps** of 1500B
SCTP packets over 10G links. It extends 6Wind FastPath stack on NetLogic XLR NPUs. Ravi delivers complex zero-copy
packet forwarding & scheduler, in-place IPSec, DMA and DNS support.

- *[Layer2 HA](http://www.radisys.com/2010/allot-communications-selects-continuous-computing-to-deliver-better-traffic-management-for-network-operators/)*
is an enterprise-grade network resilience solution. It gives **sub-msec** failover, weighted traffic mapping as
hub-n-spoke, and faster convergence by VRRP enhancement. It is implemented as extension to Fulcrum ControlPoint
on Switch and Bonding Driver enhancement on x86 Blades. Ravi delivers entire product, from ideation to deployment,
pens white papers, customer support. It generates **>$3M** revenue.

- *[FlexBalance](http://picmg.opensystemsmedia.com/articles/atca-load-balancing-40-gbps/)* is an enterprise-grade
server load balancer. It does **statistical hashing** of traffic marked by **L4 flows**, MPLS tags, physical port-groups
using DWRR & CBQ schedulers. It is implemented as pattern-match & scheduler enhancement using FFU, TCAM. Ravi delivers
entire product from code to docs single handedly, works with architect and QA in different geographies, helps in
deployment, customer support. Huge commercial success, generated **>$8M** in revenue, and helped in more than **12 design wins**.

- *[LTE ENodeB on Mindspeed ARM processors](http://www.businesswire.com/news/home/20120611005536/en/Mindspeed-Announces-High-Performance-Multi-Core-ARM-Cortex-A-CPU-Based)*
using 4GMX OS. Mindspeed has ARM family of processors with very low power usage. U-CPU/L-CPU dual CPU achitecture is suitable for distributing Phy and stack
layers across two different CPUs, both of which are connected by a message bus. Ravi is tasked with porting, optimization of stack on these low-powered devices

- *[FlexTCA](http://www.businesswire.com/news/home/20090901005489/en/Continuous-Computing-Launches-FlexTCA-3.0-Enhanced-DPI)* is a carrier-grade, service
  availability product that pre-integrates Trillium stacks with GoAhead Saffire middleware to run out-of-box on ATCA chassis. It implements OAM interface over
  SNMP/Web, Compute blade resilience using SAF SAI, Protocol HA using DFTHA layer, Control plane HA using SAF checkpoint service, and Chassis management using
  SAF HPI. Ravi is responsible for design, code and testing of **complex SAF-Trillium integration layer** that represents core value-add of product offering.

- *[UpSuite](http://go.ccpu.com/upSuite)* is a high-availability middleware providing fault identification, isolation, and recovery along with **real-time
  mirroring file-system** for Solaris based servers. It implements heartbeat framework, application monitoring framework, kernel file-system for mirroring, and
  **NIC resiliency driver**. Ravi is involved in doing upgrade of file-system to Solaris 10, supporting zones, and providing bug-fixes on Solaris servers.

Jul/2004 - Jan/2007
:   *Software Consultant* at **[Various Bangalore Startups]**

As a Technology Consultant, he has helped in **feasibility analysis, new tech integration & prototyping/PoC**, *solving design & coding challenges*,
**timebound resolution of critical bugs**, *deployment engineering assistance*, and **Application optimization for scale & performance**.

- *[Talent+](http://www.talentplus.com/)* is a Recruitment Workflow web portal for HR/TAs built using Java Servlets. Ravi integrates AJAX/xmlhttprequest & DOM
  into TalentPlus, at a time when Struts, Spring, and JSP did not have native support for it.
- *[Mission BioFuels Tracking/MBT]* is a company that specializes in producing biofuels as alternate fuels for vehicles in concert with farmers to grow relevant
  seeds. These crops require careful monitoring, timely intervention for pests & growth, for good yield. They employ human agents for its tracking. For tracking
  to be effective, geo-tagged monitoring data from phones of Agents needs to be synced to company servers via computers. Ravi helps with seamless sync of user
  app data to Cloud services using integration of *[Funambol](https://sourceforge.net/projects/funambol/)* sync-server with J2ME app on Symbian S40/S60 phones.


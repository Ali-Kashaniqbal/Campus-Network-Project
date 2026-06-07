# Week 1 Status Report: Campus Network Infrastructure Design

## Executive Summary
During Week 1, our team focused on core requirements analysis, defining team structure, planning the logical IP addressing matrix, and designing the high-level network topology for the University of Cyberia campus network.

## Completed Tasks This Week
* **Project Formulation & Initialization:** Formed a structured 6-member team and signed the Team Contract.
* **Topology Mapping:** Created the complete logical network diagram using draw.io via Mermaid modeling, defining the parameters for VLAN 10, VLAN 20, and VLAN 99.
* **IP Address Allocation:** Finalized the subnet structure (`192.168.10.0/24`, `192.168.20.0/24`, `192.168.99.0/24`) with strict segmentation boundaries.
* **Risk Formulation:** Created the Risk Assessment Matrix outlining technical and coordination mitigations.
* **Repository Setup:** GitHub repository initialized with standard documentation architecture.

## Team Member Contributions
* **Ali Kashan (Project Lead & Git Master):** Handled repository initialization, structural framework guidelines, and weekly report aggregation.
* **Malik Mohsin Sajjad (Network Architect):** Engineered the logical topology diagram layout within draw.io.
* **Ahmad Faraz (Routing & Security Specialist):** Outlined the sub-interface criteria for Router-on-a-Stick deployment.
* **Abdullah (System Administrator):** Defined technical parameters required for hosting the Guest Captive Portal page on Ubuntu Server.
* **Aizaz (Penetration Tester):** Conducted vulnerability analysis for upcoming Layer 2 attack simulations.
* **Muhammad Rauf Saqib (Performance Analyst):** Established performance benchmarking plans for the 5 Mbps traffic-shaping test.

## Plans for Week 2
* Import Cisco IOS images and deploy the base nodes within the GNS3 workspace environment.
* Configure VLANs on the switch and establish Router-on-a-Stick trunk encapsulation (`dot1q`).
* Activate the DHCP scope from the Cisco Router to verify dynamic IP allocation for the Guest VLAN.
* Test all-to-all base ping connectivity before implementing Access Control Lists (ACLs).
* ---
## Week 1 Final Deliverables Summary

### 📂 Repository File Structure Tracker
Our repository has been structured according to standard guidelines to maintain clean commits throughout the 6 weeks:
* `/topology/topology.png` - Exported high-resolution logical diagram from draw.io [Completed]
* `/docs/IP_Addressing_Plan.xlsx` - Detailed network zone assignment and subnets [Completed]
* `/docs/Resource_Acquisition_Report.pdf` - Verification of GNS3, Cisco IOS, and Ubuntu VM setups [Completed]
* `/docs/Risk_Assessment_Matrix.pdf` - Analytical framework identifying system failure parameters and safeguards [Completed]

### 🤝 Group Contract & Coordination Roles
All 6 group members have signed off on the responsibilities below, agreeing to equal distribution of lab work:
1. **Ali Kashan (Project Lead & Git Master):** Directing timeline management, repository architecture, and status compilation.
2. **Malik Mohsin Sajjad (Network Architect):** Responsible for designing structural diagrams and GNS3 layout environments.
3. **Ahmad Faraz (Routing & Security Specialist):** Core network configuration lead for switches, routing encapsulation, and ACL logic.
4. **Abdullah (System Administrator):** In-charge of Ubuntu VM configurations and hosting the local Captive Portal.
5. **Aizaz (Penetration Tester):** Managing Kali Linux deployment, packet captures via Wireshark, and local attack scripts.
6. **Muhammad Rauf Saqib (Performance Analyst):** Executing validation logs, iPerf bandwidth tracking, and metrics compilation.

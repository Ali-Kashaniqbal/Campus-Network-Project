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

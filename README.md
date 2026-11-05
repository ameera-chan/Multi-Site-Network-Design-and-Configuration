# Multi-Site Network Design and Configuration

## Project overview

This academic project models a network upgrade for MegahTech Sdn. Bhd. The design connects the company's Kuala Lumpur (KL) headquarters, Singapore branch, and KL server farm. The prototype was built in Cisco Packet Tracer to organize departments into VLANs, support wireless access in Singapore, and improve network security and availability.

## Sites and departments

- **KL headquarters:** KL_Management, KL_HumanResource (HR), KL_Design, KL_Finance, and KL_R&D
- **Singapore branch:** SG_Delivery, SG_Management, and SG_IT
- **KL server farm:** Internal services for both sites

## Design requirements

The assignment called for a logical topology and device configurations that included:

- VLANs for the departments
- DHCPv4 across multiple LANs, with DHCP required in Singapore and optional in KL
- A Singapore WLC WLAN using a VLAN interface, DHCP, and WPA2
- OSPF and a default static route
- Layer 2 protection using switch port security
- HSRP and EtherChannel
- Basic router and switch configuration
- Internal FTP, DNS, and web services for the KL and Singapore networks

## Project file

Open [KL-SG.pkt](KL-SG.pkt) with Cisco Packet Tracer.

> This is an academic simulation, not a production network deployment.
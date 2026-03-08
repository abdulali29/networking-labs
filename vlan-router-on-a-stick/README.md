# VLAN Router-on-a-Stick Lab

## Objective

The goal of this lab is to configure inter-VLAN routing using the Router-on-a-Stick method with a Cisco router and Layer 2 switch.

## Topology

![Network Topology](topology.png)

## VLANs

| VLAN | Network | Devices |
|-----|--------|--------|
| 2 | 192.168.2.0/24 | PC0, PC1 |
| 3 | 192.168.3.0/24 | PC5, PC6 |
| 4 | 192.168.4.0/24 | PC7, PC8 |

## Technologies

- Cisco Router
- Cisco Switch
- VLAN segmentation
- Router-on-a-Stick


## Router Interfaces

Verification of router subinterfaces:

![Router Interfaces](show_ip_interface_brief.png)

Note: Interface status before VLAN subinterface configuration.


## VLAN 2 Subinterface Configuration

![VLAN2 Configuration](VLAN2_configuration.png)

Note: The router subinterface for VLAN 2 is configured using 802.1Q encapsulation and assigned the IP address 192.168.2.1. Once configured, the interface state changes to **up**, allowing the router to act as the default gateway for VLAN 2.






## Packet Tracer Lab

You can download and open the lab in Cisco Packet Tracer.

[vlan-router-on-a-stick.pkt](vlan-router-on-a-stick.pkt)

Open the Packet Tracer file to explore the full network topology and test the VLAN routing configuration.

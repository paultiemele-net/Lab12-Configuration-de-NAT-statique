# Lab12-Configuration-de-NAT-statique
This repository contains a Cisco IOS configuration showcasing how to implement Static NAT (Network Address Translation) to allow a private LAN host to communicate with an external router using a fixed public IP address. This lab is ideal for anyone learning NAT fundamentals on Cisco devices.
In this lab:

PC1 (10.10.10.2) resides in a private LAN behind Router1.

Router2 is located on an external network (20.20.20.0/24).

Static NAT is used so that PC1 is always translated to the public IP 20.20.20.3 when accessing Router2.

This allows controlled inbound/outbound communication while preserving a consistent public identity for PC1.

The configuration demonstrates:

Inside/Outside NAT interface setup

Static 1-to-1 address translation

Basic DHCP configuration

End-to-end connectivity testing

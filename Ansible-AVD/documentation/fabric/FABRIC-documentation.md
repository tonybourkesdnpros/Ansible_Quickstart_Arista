# FABRIC

# Table of Contents

- [Fabric Switches and Management IP](#fabric-switches-and-management-ip)
  - [Fabric Switches with inband Management IP](#fabric-switches-with-inband-management-ip)
- [Fabric Topology](#fabric-topology)
- [Fabric IP Allocation](#fabric-ip-allocation)
  - [Fabric Point-To-Point Links](#fabric-point-to-point-links)
  - [Point-To-Point Links Node Allocation](#point-to-point-links-node-allocation)
  - [Loopback Interfaces (BGP EVPN Peering)](#loopback-interfaces-bgp-evpn-peering)
  - [Loopback0 Interfaces Node Allocation](#loopback0-interfaces-node-allocation)
  - [VTEP Loopback VXLAN Tunnel Source Interfaces (VTEPs Only)](#vtep-loopback-vxlan-tunnel-source-interfaces-vteps-only)
  - [VTEP Loopback Node allocation](#vtep-loopback-node-allocation)

# Fabric Switches and Management IP

| POD | Type | Node | Management IP | Platform | Provisioned in CloudVision |
| --- | ---- | ---- | ------------- | -------- | -------------------------- |
| FABRIC | l3leaf | leaf1 | 192.168.0.21/24 | - | Provisioned |
| FABRIC | l3leaf | leaf2 | 192.168.0.22/24 | - | Provisioned |
| FABRIC | l3leaf | leaf3 | 192.168.0.23/24 | - | Provisioned |
| FABRIC | l3leaf | leaf4 | 192.168.0.24/24 | - | Provisioned |
| FABRIC | spine | spine1 | 192.168.0.11/24 | - | Provisioned |
| FABRIC | spine | spine2 | 192.168.0.12/24 | - | Provisioned |

> Provision status is based on Ansible inventory declaration and do not represent real status from CloudVision.

## Fabric Switches with inband Management IP
| POD | Type | Node | Management IP | Inband Interface |
| --- | ---- | ---- | ------------- | ---------------- |

# Fabric Topology

| Type | Node | Node Interface | Peer Type | Peer Node | Peer Interface |
| ---- | ---- | -------------- | --------- | ----------| -------------- |
| l3leaf | leaf1 | Ethernet1 | mlag_peer | leaf2 | Ethernet1 |
| l3leaf | leaf1 | Ethernet2 | mlag_peer | leaf2 | Ethernet2 |
| l3leaf | leaf1 | Ethernet3 | spine | spine1 | Ethernet2 |
| l3leaf | leaf1 | Ethernet4 | spine | spine2 | Ethernet2 |
| l3leaf | leaf2 | Ethernet3 | spine | spine1 | Ethernet3 |
| l3leaf | leaf2 | Ethernet4 | spine | spine2 | Ethernet3 |
| l3leaf | leaf3 | Ethernet1 | mlag_peer | leaf4 | Ethernet1 |
| l3leaf | leaf3 | Ethernet2 | mlag_peer | leaf4 | Ethernet2 |
| l3leaf | leaf3 | Ethernet3 | spine | spine1 | Ethernet4 |
| l3leaf | leaf3 | Ethernet4 | spine | spine2 | Ethernet4 |
| l3leaf | leaf4 | Ethernet3 | spine | spine1 | Ethernet5 |
| l3leaf | leaf4 | Ethernet4 | spine | spine2 | Ethernet5 |

# Fabric IP Allocation

## Fabric Point-To-Point Links

| Uplink IPv4 Pool | Available Addresses | Assigned addresses | Assigned Address % |
| ---------------- | ------------------- | ------------------ | ------------------ |
| 192.168.103.0/24 | 256 | 16 | 6.25 % |

## Point-To-Point Links Node Allocation

| Node | Node Interface | Node IP Address | Peer Node | Peer Interface | Peer IP Address |
| ---- | -------------- | --------------- | --------- | -------------- | --------------- |
| leaf1 | Ethernet3 | 192.168.103.1/31 | spine1 | Ethernet2 | 192.168.103.0/31 |
| leaf1 | Ethernet4 | 192.168.103.3/31 | spine2 | Ethernet2 | 192.168.103.2/31 |
| leaf2 | Ethernet3 | 192.168.103.7/31 | spine1 | Ethernet3 | 192.168.103.6/31 |
| leaf2 | Ethernet4 | 192.168.103.9/31 | spine2 | Ethernet3 | 192.168.103.8/31 |
| leaf3 | Ethernet3 | 192.168.103.13/31 | spine1 | Ethernet4 | 192.168.103.12/31 |
| leaf3 | Ethernet4 | 192.168.103.15/31 | spine2 | Ethernet4 | 192.168.103.14/31 |
| leaf4 | Ethernet3 | 192.168.103.19/31 | spine1 | Ethernet5 | 192.168.103.18/31 |
| leaf4 | Ethernet4 | 192.168.103.21/31 | spine2 | Ethernet5 | 192.168.103.20/31 |

## Loopback Interfaces (BGP EVPN Peering)

| Loopback Pool | Available Addresses | Assigned addresses | Assigned Address % |
| ------------- | ------------------- | ------------------ | ------------------ |
| 192.168.101.0/24 | 256 | 6 | 2.35 % |

## Loopback0 Interfaces Node Allocation

| POD | Node | Loopback0 |
| --- | ---- | --------- |
| FABRIC | leaf1 | 192.168.101.1/32 |
| FABRIC | leaf2 | 192.168.101.2/32 |
| FABRIC | leaf3 | 192.168.101.3/32 |
| FABRIC | leaf4 | 192.168.101.4/32 |
| FABRIC | spine1 | 192.168.101.11/32 |
| FABRIC | spine2 | 192.168.101.12/32 |

## VTEP Loopback VXLAN Tunnel Source Interfaces (VTEPs Only)

| VTEP Loopback Pool | Available Addresses | Assigned addresses | Assigned Address % |
| --------------------- | ------------------- | ------------------ | ------------------ |
| 192.168.102.0/24 | 256 | 4 | 1.57 % |

## VTEP Loopback Node allocation

| POD | Node | Loopback1 |
| --- | ---- | --------- |
| FABRIC | leaf1 | 192.168.102.1/32 |
| FABRIC | leaf2 | 192.168.102.1/32 |
| FABRIC | leaf3 | 192.168.102.3/32 |
| FABRIC | leaf4 | 192.168.102.3/32 |

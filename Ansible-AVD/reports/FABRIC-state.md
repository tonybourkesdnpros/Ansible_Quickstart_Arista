
# Validate State Report

**Table of Contents:**

- [Validate State Report](validate-state-report)
  - [Test Results Summary](#test-results-summary)
  - [Failed Test Results Summary](#failed-test-results-summary)
  - [All Test Results](#all-test-results)

## Test Results Summary

### Summary Totals

| Total Tests | Total Tests Passed | Total Tests Failed |
| ----------- | ------------------ | ------------------ |
| 218 | 218 | 0 |

### Summary Totals Devices Under Tests

| DUT | Total Tests | Tests Passed | Tests Failed | Categories Failed |
| --- | ----------- | ------------ | ------------ | ----------------- |
| leaf1 |  43 | 43 | 0 | - |
| leaf2 |  43 | 43 | 0 | - |
| leaf3 |  43 | 43 | 0 | - |
| leaf4 |  43 | 43 | 0 | - |
| spine1 |  23 | 23 | 0 | - |
| spine2 |  23 | 23 | 0 | - |

### Summary Totals Per Category

| Test Category | Total Tests | Tests Passed | Tests Failed |
| ------------- | ----------- | ------------ | ------------ |
| NTP |  6 | 6 | 0 |
| Interface State |  70 | 70 | 0 |
| LLDP Topology |  24 | 24 | 0 |
| MLAG |  4 | 4 | 0 |
| IP Reachability |  16 | 16 | 0 |
| BGP |  42 | 42 | 0 |
| Routing Table |  32 | 32 | 0 |
| Loopback0 Reachability |  24 | 24 | 0 |

## Failed Test Results Summary

| Test ID | Node | Test Category | Test Description | Test | Test Result | Failure Reason |
| ------- | ---- | ------------- | ---------------- | ---- | ----------- | -------------- |

## All Test Results

| Test ID | Node | Test Category | Test Description | Test | Test Result | Failure Reason |
| ------- | ---- | ------------- | ---------------- | ---- | ----------- | -------------- |
| 1 | leaf1 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 2 | leaf2 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 3 | leaf3 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 4 | leaf4 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 5 | spine1 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 6 | spine2 | NTP | Synchronised with NTP server | NTP | PASS | - |
| 7 | leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf2_Ethernet1 | PASS | - |
| 8 | leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf2_Ethernet2 | PASS | - |
| 9 | leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1_Ethernet2 | PASS | - |
| 10 | leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2_Ethernet2 | PASS | - |
| 11 | leaf1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - host1 | PASS | - |
| 12 | leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf1_Ethernet1 | PASS | - |
| 13 | leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf1_Ethernet2 | PASS | - |
| 14 | leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1_Ethernet3 | PASS | - |
| 15 | leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2_Ethernet3 | PASS | - |
| 16 | leaf2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - host1 | PASS | - |
| 17 | leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf4_Ethernet1 | PASS | - |
| 18 | leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf4_Ethernet2 | PASS | - |
| 19 | leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1_Ethernet4 | PASS | - |
| 20 | leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2_Ethernet4 | PASS | - |
| 21 | leaf3 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet6 - host2_Ethernet1 | PASS | - |
| 22 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet1 - MLAG_PEER_leaf3_Ethernet1 | PASS | - |
| 23 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - MLAG_PEER_leaf3_Ethernet2 | PASS | - |
| 24 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_SPINE1_Ethernet5 | PASS | - |
| 25 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_SPINE2_Ethernet5 | PASS | - |
| 26 | leaf4 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet7 - host2_Ethernet2 | PASS | - |
| 27 | spine1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_LEAF1_Ethernet3 | PASS | - |
| 28 | spine1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_LEAF2_Ethernet3 | PASS | - |
| 29 | spine1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_LEAF3_Ethernet3 | PASS | - |
| 30 | spine1 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_LEAF4_Ethernet3 | PASS | - |
| 31 | spine2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet2 - P2P_LINK_TO_LEAF1_Ethernet4 | PASS | - |
| 32 | spine2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet3 - P2P_LINK_TO_LEAF2_Ethernet4 | PASS | - |
| 33 | spine2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet4 - P2P_LINK_TO_LEAF3_Ethernet4 | PASS | - |
| 34 | spine2 | Interface State | Ethernet Interface & Line Protocol == "up" | Ethernet5 - P2P_LINK_TO_LEAF4_Ethernet4 | PASS | - |
| 35 | leaf1 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf2_Po1 | PASS | - |
| 36 | leaf1 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel6 - host1_PortChannel host1 | PASS | - |
| 37 | leaf2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf1_Po1 | PASS | - |
| 38 | leaf2 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel6 - host1_PortChannel host1 | PASS | - |
| 39 | leaf3 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf4_Po1 | PASS | - |
| 40 | leaf3 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel6 - host2_PortChannel host2 | PASS | - |
| 41 | leaf4 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel1 - MLAG_PEER_leaf3_Po1 | PASS | - |
| 42 | leaf4 | Interface State | Port-Channel Interface & Line Protocol == "up" | Port-Channel6 - host2_PortChannel host2 | PASS | - |
| 43 | leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 44 | leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 45 | leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - DMZ | PASS | - |
| 46 | leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Internal | PASS | - |
| 47 | leaf1 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF_A | PASS | - |
| 48 | leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 49 | leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 50 | leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - DMZ | PASS | - |
| 51 | leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Internal | PASS | - |
| 52 | leaf2 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF_A | PASS | - |
| 53 | leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 54 | leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 55 | leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - DMZ | PASS | - |
| 56 | leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Internal | PASS | - |
| 57 | leaf3 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF_A | PASS | - |
| 58 | leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4093 - MLAG_PEER_L3_PEERING | PASS | - |
| 59 | leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan4094 - MLAG_PEER | PASS | - |
| 60 | leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan10 - DMZ | PASS | - |
| 61 | leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan20 - Internal | PASS | - |
| 62 | leaf4 | Interface State | Vlan Interface & Line Protocol == "up" | Vlan3009 - MLAG_PEER_L3_iBGP: vrf VRF_A | PASS | - |
| 63 | leaf1 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 64 | leaf2 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 65 | leaf3 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 66 | leaf4 | Interface State | Vxlan Interface Status & Line Protocol == "up" | Vxlan1 | PASS | - |
| 67 | leaf1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 68 | leaf1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 69 | leaf2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 70 | leaf2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 71 | leaf3 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 72 | leaf3 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 73 | leaf4 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 74 | leaf4 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback1 - VTEP_VXLAN_Tunnel_Source | PASS | - |
| 75 | spine1 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 76 | spine2 | Interface State | Loopback Interface Status & Line Protocol == "up" | Loopback0 - EVPN_Overlay_Peering | PASS | - |
| 77 | leaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf2_Ethernet1 | PASS | - |
| 78 | leaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf2_Ethernet2 | PASS | - |
| 79 | leaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1_Ethernet2 | PASS | - |
| 80 | leaf1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2_Ethernet2 | PASS | - |
| 81 | leaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf1_Ethernet1 | PASS | - |
| 82 | leaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf1_Ethernet2 | PASS | - |
| 83 | leaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1_Ethernet3 | PASS | - |
| 84 | leaf2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2_Ethernet3 | PASS | - |
| 85 | leaf3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf4_Ethernet1 | PASS | - |
| 86 | leaf3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf4_Ethernet2 | PASS | - |
| 87 | leaf3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1_Ethernet4 | PASS | - |
| 88 | leaf3 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2_Ethernet4 | PASS | - |
| 89 | leaf4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet1 - remote: leaf3_Ethernet1 | PASS | - |
| 90 | leaf4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf3_Ethernet2 | PASS | - |
| 91 | leaf4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: spine1_Ethernet5 | PASS | - |
| 92 | leaf4 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: spine2_Ethernet5 | PASS | - |
| 93 | spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf1_Ethernet3 | PASS | - |
| 94 | spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: leaf2_Ethernet3 | PASS | - |
| 95 | spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: leaf3_Ethernet3 | PASS | - |
| 96 | spine1 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: leaf4_Ethernet3 | PASS | - |
| 97 | spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet2 - remote: leaf1_Ethernet4 | PASS | - |
| 98 | spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet3 - remote: leaf2_Ethernet4 | PASS | - |
| 99 | spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet4 - remote: leaf3_Ethernet4 | PASS | - |
| 100 | spine2 | LLDP Topology | LLDP topology - validate peer and interface | local: Ethernet5 - remote: leaf4_Ethernet4 | PASS | - |
| 101 | leaf1 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 102 | leaf2 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 103 | leaf3 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 104 | leaf4 | MLAG | MLAG State active & Status connected | MLAG | PASS | - |
| 105 | leaf1 | IP Reachability | ip reachability test p2p links | Source: leaf1_Ethernet3 - Destination: spine1_Ethernet2 | PASS | - |
| 106 | leaf1 | IP Reachability | ip reachability test p2p links | Source: leaf1_Ethernet4 - Destination: spine2_Ethernet2 | PASS | - |
| 107 | leaf2 | IP Reachability | ip reachability test p2p links | Source: leaf2_Ethernet3 - Destination: spine1_Ethernet3 | PASS | - |
| 108 | leaf2 | IP Reachability | ip reachability test p2p links | Source: leaf2_Ethernet4 - Destination: spine2_Ethernet3 | PASS | - |
| 109 | leaf3 | IP Reachability | ip reachability test p2p links | Source: leaf3_Ethernet3 - Destination: spine1_Ethernet4 | PASS | - |
| 110 | leaf3 | IP Reachability | ip reachability test p2p links | Source: leaf3_Ethernet4 - Destination: spine2_Ethernet4 | PASS | - |
| 111 | leaf4 | IP Reachability | ip reachability test p2p links | Source: leaf4_Ethernet3 - Destination: spine1_Ethernet5 | PASS | - |
| 112 | leaf4 | IP Reachability | ip reachability test p2p links | Source: leaf4_Ethernet4 - Destination: spine2_Ethernet5 | PASS | - |
| 113 | spine1 | IP Reachability | ip reachability test p2p links | Source: spine1_Ethernet2 - Destination: leaf1_Ethernet3 | PASS | - |
| 114 | spine1 | IP Reachability | ip reachability test p2p links | Source: spine1_Ethernet3 - Destination: leaf2_Ethernet3 | PASS | - |
| 115 | spine1 | IP Reachability | ip reachability test p2p links | Source: spine1_Ethernet4 - Destination: leaf3_Ethernet3 | PASS | - |
| 116 | spine1 | IP Reachability | ip reachability test p2p links | Source: spine1_Ethernet5 - Destination: leaf4_Ethernet3 | PASS | - |
| 117 | spine2 | IP Reachability | ip reachability test p2p links | Source: spine2_Ethernet2 - Destination: leaf1_Ethernet4 | PASS | - |
| 118 | spine2 | IP Reachability | ip reachability test p2p links | Source: spine2_Ethernet3 - Destination: leaf2_Ethernet4 | PASS | - |
| 119 | spine2 | IP Reachability | ip reachability test p2p links | Source: spine2_Ethernet4 - Destination: leaf3_Ethernet4 | PASS | - |
| 120 | spine2 | IP Reachability | ip reachability test p2p links | Source: spine2_Ethernet5 - Destination: leaf4_Ethernet4 | PASS | - |
| 121 | leaf1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 122 | leaf2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 123 | leaf3 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 124 | leaf4 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 125 | spine1 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 126 | spine2 | BGP | ArBGP is configured and operating | ArBGP | PASS | - |
| 127 | leaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.1 | PASS | - |
| 128 | leaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.0 | PASS | - |
| 129 | leaf1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.2 | PASS | - |
| 130 | leaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.0 | PASS | - |
| 131 | leaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.6 | PASS | - |
| 132 | leaf2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.8 | PASS | - |
| 133 | leaf3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.5 | PASS | - |
| 134 | leaf3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.12 | PASS | - |
| 135 | leaf3 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.14 | PASS | - |
| 136 | leaf4 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 10.255.251.4 | PASS | - |
| 137 | leaf4 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.18 | PASS | - |
| 138 | leaf4 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.20 | PASS | - |
| 139 | spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.1 | PASS | - |
| 140 | spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.7 | PASS | - |
| 141 | spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.13 | PASS | - |
| 142 | spine1 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.19 | PASS | - |
| 143 | spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.3 | PASS | - |
| 144 | spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.9 | PASS | - |
| 145 | spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.15 | PASS | - |
| 146 | spine2 | BGP | ip bgp peer state established (ipv4) | bgp_neighbor: 192.168.103.21 | PASS | - |
| 147 | leaf1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.11 | PASS | - |
| 148 | leaf1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.12 | PASS | - |
| 149 | leaf2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.11 | PASS | - |
| 150 | leaf2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.12 | PASS | - |
| 151 | leaf3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.11 | PASS | - |
| 152 | leaf3 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.12 | PASS | - |
| 153 | leaf4 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.11 | PASS | - |
| 154 | leaf4 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.12 | PASS | - |
| 155 | spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.1 | PASS | - |
| 156 | spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.2 | PASS | - |
| 157 | spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.3 | PASS | - |
| 158 | spine1 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.4 | PASS | - |
| 159 | spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.1 | PASS | - |
| 160 | spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.2 | PASS | - |
| 161 | spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.3 | PASS | - |
| 162 | spine2 | BGP | bgp evpn peer state established (evpn) | bgp_neighbor: 192.168.101.4 | PASS | - |
| 163 | leaf1 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 164 | leaf1 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 165 | leaf2 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 166 | leaf2 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 167 | leaf3 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 168 | leaf3 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 169 | leaf4 | Routing Table | Remote VTEP address | 192.168.102.1 | PASS | - |
| 170 | leaf4 | Routing Table | Remote VTEP address | 192.168.102.3 | PASS | - |
| 171 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 172 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 173 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 174 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 175 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 176 | leaf1 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 177 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 178 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 179 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 180 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 181 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 182 | leaf2 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 183 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 184 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 185 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 186 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 187 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 188 | leaf3 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 189 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.1 | PASS | - |
| 190 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.2 | PASS | - |
| 191 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.3 | PASS | - |
| 192 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.4 | PASS | - |
| 193 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.11 | PASS | - |
| 194 | leaf4 | Routing Table | Remote Lo0 address | 192.168.101.12 | PASS | - |
| 195 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.1 | PASS | - |
| 196 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.2 | PASS | - |
| 197 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.3 | PASS | - |
| 198 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.4 | PASS | - |
| 199 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.11 | PASS | - |
| 200 | leaf1 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf1 - 192.168.101.1 Destination: 192.168.101.12 | PASS | - |
| 201 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.1 | PASS | - |
| 202 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.2 | PASS | - |
| 203 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.3 | PASS | - |
| 204 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.4 | PASS | - |
| 205 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.11 | PASS | - |
| 206 | leaf2 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf2 - 192.168.101.2 Destination: 192.168.101.12 | PASS | - |
| 207 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.1 | PASS | - |
| 208 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.2 | PASS | - |
| 209 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.3 | PASS | - |
| 210 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.4 | PASS | - |
| 211 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.11 | PASS | - |
| 212 | leaf3 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf3 - 192.168.101.3 Destination: 192.168.101.12 | PASS | - |
| 213 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.1 | PASS | - |
| 214 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.2 | PASS | - |
| 215 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.3 | PASS | - |
| 216 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.4 | PASS | - |
| 217 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.11 | PASS | - |
| 218 | leaf4 | Loopback0 Reachability | Loopback0 Reachability | Source: leaf4 - 192.168.101.4 Destination: 192.168.101.12 | PASS | - |

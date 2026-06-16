# Multi-Site-Network (Static Routing)

# Multi-Site Network Lab — HQ and Branch WAN, VLANs, DHCP, ACLs 

## Current Status

- Built HQ and Branch network sites with separate routers, switches, and client devices.
- Configured VLAN 10 and VLAN 20 at both HQ and Branch locations.
- Configured router-on-a-stick using 802.1Q subinterfaces on both site routers.
- Configured DHCP pools for VLAN 10 and VLAN 20 at both sites.
- Configured a /30 point-to-point WAN link between the HQ and Branch routers.
- Added static routes so HQ and Branch VLANs can communicate across the WAN link.
- Applied extended ACLs to enforce local VLAN segmentation at each site.
- Verified DHCP assignment, routing, trunking, ACL enforcement, and cross-site connectivity.

## Next Phase

- Configure a site-to-site VPN between HQ and Branch routers to secure cross-site traffic.

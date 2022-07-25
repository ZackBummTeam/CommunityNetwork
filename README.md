# CommunityNetwork

## Target
- Building a Playground for BGP and other REAL Internet shit.

## Idea:
- FASTD based VPN between ASNs. (Other Tunnel Protocol by demand)
- Central YAML or JSON Configuration to store Peering participants. 
- EasyAccess VPN for participants behind NAT (maybee openvpn?).


## Design:
- a FASTD mesh VPN, as transport network, with a RFC 1918 subnet (172.31.0.0/24)
- BGP inside the Transport Network to exchange routing informations.
- AS by YAML file
- Looking Glass for Testing
-

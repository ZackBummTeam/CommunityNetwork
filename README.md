# ZackBummNetwork!

## Target
- Building a Playground for BGP and other REAL Internet shit.

## Idea:
- tinc based VPN between ASNs. (Other Tunnel Protocol by demand)
- Central YAML or JSON Configuration to store Peering participants. 
- EasyAccess VPN for participants behind NAT (maybee openvpn?).

## Design:
- a tinc mesh VPN, as transport network, with a RFC 1918 subnet (10.200.0.0/24)
- BGP inside the Transport Network to exchange routing informations.
- AS by YAML file
- Looking Glass for Testing
- nameserver for the TLD .zbn (register your own nameserver, or transfer your zone)
- maybee there will be a shared vm hosting service

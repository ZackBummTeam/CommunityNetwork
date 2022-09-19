# zbna - ZackBumm number authority

This is basicly the analog to the iana. This service will later get a website to search for stuff
___
## AS List

| Organisation | AS                | Notes               |
| ------------ |:----------------- | ------------------- |
| zbn          | AS0               | Core intrastructure |
| delta        | AS42069 - AS42080 |                     |
| h2com        | AS1000-AS1001     |                     |
| roll0r       | AS31337           |                     |
| retro        | AS23420           |                     | 
| 0fr0         | AS2000            |                     | 

- AS0
    - Intrastructure routes
        - v4: 10.200.0.0/24
        - v6: fc00::/64
        
- AS1000
    - Peer
        - v4: 10.200.0.1/24
        - v6: fc00::1eed:beef/64

- AS1001
    - Peer
        - v4: 10.200.0.2/24
        - v6: fc00::1eed:beat/64
    - Routes
        - v4
            - 172.18.0.0/16 
- AS2000
    - Peer
        - v4: 10.200.0.10/24
        - v6: fc00::3066:7230/64
- AS42069
    - Peer
        - v4: 10.200.0.42/24
        - v6: fc00::dc42/64
    - Routes
        - v6
            - fddc::/16
            - fc00:0:1::/64
        - v4
            - 10.2.0.0/24 - central infra
            - 10.75.0.0/16 - vex
            - 10.76.0.0/24 - vex/in0
            - 10.76.1.0/24 - vex/in1
- AS42070
    - Peer
        - v4: 10.200.0.43/24
        - v6: fc00::dc43/64
    - Routes
        - v4:
            - 10.5.0.0/16 - home
            - 10.20.0.0/16 - home/lab
            - 10.21.0.0/24 - home/iot
- AS42071
    - Peer
        - v4: 10.200.0.44/24
        - v6: fc00::dc44/64
    - Routes
        - v4:
            - 172.30.0.0/24 - fsn1-test
        - v6:
            - 2a01:4f8:c012:d8ab::/64
- AS42072
    - Peer
        - v4: 10.200.0.60/24
        - v6: fc00::ae00/64
    - Routes
        - v4
            - 10.10.0.0/16 - ae
            - 10.16.0.0/24 - ae
        - v6
            - fddc:0:ae:14::/64 - ae/ev
- AS42073
    - Peer
        - v4: 10.200.0.61/24
        - v6: fc00::ae01/64
    - Routes
        - v4
            - 10.15.0.0/16 - ae/cloud

___
Orgs - IP ranges
- zbna
    - v4
        - 10.200.0.0/16
        - 10.200.0.0/24 (internal transfer net)
    - v6
        - fc00::/48 (internal transfer net)
- delta
    - v4
        - 10.2.0.0/16 (core infra)
        - 10.5.0.0/16
        - 10.10.0.0/16
        - 10.15.0.0/16
        - 10.16.0.0/16
        - 10.20.0.0/16
        - 10.21.0.0/24
        - 10.75.0.0/16
        - 10.76.0.0/24
        - 10.76.1.0/24
    - v6
        - fc00:0:1::/48 (core infra)
        - fddc::/16
        - fc00:dead:beef::/48
- asrael
    - v4
        - 172.18.0.0/16
    - v6
        - fc00:1eed:beef::/48
- roll0r
    - v6
        - fc00:cafe:babe::/48

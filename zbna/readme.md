# zbna - ZackBumm number authority

This is basicly the analog to the iana. This service will later get a website to search for stuff
___
## AS List

| Organisation | AS                | Notes               |
| ------------ |:----------------- | ------------------- |
| zbn          | AS0               | Core intrastructure |
| delta        | AS42069 - AS42080 |                     |
| h2com        | AS1000            |                     |
| retro        | AS23420           |                     | 
- AS0
    - Intrastructure routes
        - v4: 10.200.0.0/24
        - v6: fc00::/64
- AS42069
    - Peer
        - v4: 10.200.0.42/24
        - v6: fc00::dc42/64
    - Routes
        - v6
            - fddc::/16
        - v4
            - 10.2.0.0/16 - central infra
            - 10.75.0.0/16 - vex
            - 10.76.0.0/24 - vex/in0
            - 10.76.1.0/24 - vex/in1
            - 10.77.0.0/16 - vex/lab
- AS42070
    - Peer
        - v4: 10.200.0.43/24
        - v6: fc00::dc43/64
    - Routes
        - v4:
            - 10.5.0.0/16 - home
            - 10.20.0.0/16 - home/lab
            - 10.21.0.0/16 - home/iot
- AS42071
    - Peer
        - v4: 10.200.0.44/24
        - v6: fc00::dc44/64
    - Routes
        - v4:
            - 172.30.0.0/24 - fsn1-test
- AS42072
    - Peer
        - v4: 10.200.0.60/24
        - v6: fc00::ae00/64
    - Routes
        - v4
            - 10.10.0.0/16 - ae
            - 10.12.0.0/16 - ae/iot
            - 10.250.15.0/24 - ae/enderlog
- AS42073
    - Peer
        - v4: 10.200.0.61/24
        - v6: fc00::ae01/64
    - Routes
        - v4
            - 10.15.0.0/16 - ae/cloud
- AS1000
    - Peer
        - v4: 10.200.0.1/24
        - v6: fc00::1eed:beef/64
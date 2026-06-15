# CNRoutingAssignment

This repository contains the Cisco Packet Tracer files used to complete the required router configurations, static routing, and dynamic routing tasks for the Computer Networks module.

## Student Information

| | |
|---|---|
| **Name** | S.A.S.Hansamal |
| **Student ID** | 39062 |
| **Module** | Computer Networks |
| **Assignment** | Router Configuration and Routing Protocols |

## Repository Contents

### `task01.pkt` — Basic Router Configuration
- Hostname configuration
- Console password setup
- Console login authentication

### `task02.pkt` — Static Routing
- IP addressing across three networks
- Static route configuration on all routers
- Network connectivity testing between all networks

### `task03_with_rip.pkt` — Dynamic Routing (RIP)
- RIPv2 configuration on all routers
- Connectivity verification between all networks

### `task03_with_eigrp.pkt` — Dynamic Routing (EIGRP)
- EIGRP configuration on all routers
- Connectivity verification between all networks

## Testing and Verification

All configurations were tested to ensure proper communication between the connected networks. Verification was carried out using:

- **Ping tests** between every pair of networks
- **Routing table verification** (`show ip route`) on each router
- **Interface status checks** (`show ip interface brief`) to confirm all links were up

Screenshots of the configurations, routing tables, and successful ping results are included in the accompanying assignment report.

## How to Open

1. Install [Cisco Packet Tracer](https://www.netacad.com/cisco-packet-tracer).
2. Download the `.pkt` file you want to review.
3. Open it in Packet Tracer and inspect the device configurations via the **CLI** tab on each router.

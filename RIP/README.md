# RIP v2 Lab

## Objective
Configure and verify **RIPv2** (Routing Information Protocol version 2) for dynamic routing between multiple routers in Cisco Packet Tracer.

## Lab File
- **Packet Tracer File:** `Rip Santosh.pkt`

## Tasks Completed
- Assigned IPv4 addresses to router interfaces
- Enabled RIPv2 on all routers
- Advertised connected networks
- Disabled automatic summarization (`no auto-summary`)
- Verified route learning and connectivity

## Verification Commands
```bash
show ip route
show ip protocols
show ip rip database
ping <destination>
traceroute <destination>

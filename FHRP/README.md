---

### 4. FHRP/README.md (HSRP)

```markdown
# HSRP (FHRP) Lab

## Objective
Configure **Hot Standby Router Protocol (HSRP)** to provide a resilient default gateway for end devices.

## Lab File
- **Packet Tracer File:** `Day 29 Lab - HSRP Configuration (3).pkt`

## Tasks Completed
- Configured two routers in the same HSRP group
- Assigned a Virtual IP address
- Set priority on the preferred (Active) router
- Enabled preemption
- Verified Active and Standby roles

## Verification Commands
```bash
show standby
show standby brief
show ip interface brief
ping <virtual-ip>

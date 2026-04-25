##  Project Notes — Inter-VLAN Routing (Router-on-a-Stick)

### Commands Used
- show vlan brief → Verified VLAN assignments
- show interfaces trunk → Verified trunk configuration
- show ip interface brief → Checked router interfaces
- ping → Tested inter-VLAN communication

---

### Issues Encountered
- Router connected to wrong switch port (used access instead of trunk)
- Missing subinterface for VLAN 20
- Trunk port not configured properly
- Incorrect default gateway configuration

---

### Troubleshooting Steps
1. Verified trunk port using show interfaces trunk
2. Confirmed router subinterfaces:
   - g0/0/0.10
   - g0/0/0.20
3. Checked default gateway on all PCs
4. Ensured correct port used for router connection (Fa0/24)

---

### Key Learning
- VLANs separate networks, routers connect networks
- Trunk ports carry multiple VLANs using 802.1Q tagging
- Subinterfaces allow one router interface to support multiple VLANs

---

### Takeaway
Inter-VLAN routing enables communication between segmented networks using a router
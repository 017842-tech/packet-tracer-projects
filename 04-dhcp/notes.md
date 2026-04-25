##  Project Notes — DHCP (Dynamic Host Configuration Protocol)

### Commands Used
- show ip dhcp binding → Verified assigned IP addresses
- show running-config | section dhcp → Checked DHCP configuration
- ipconfig → Verified IP assignment on PCs
- ping → Tested connectivity

---

### Issues Encountered
- VLAN 10 initially did not receive IP address
- DHCP worked for VLAN 20 but not VLAN 10
- Required DHCP renewal on PCs

---

### Troubleshooting Steps
1. Verified DHCP pools for both VLANs
2. Checked excluded addresses
3. Renewed IP on PCs using DHCP
4. Confirmed router subinterfaces were active
5. Verified VLAN assignments on switch

---

### Key Learning
- DHCP operates per VLAN (per subnet)
- Each VLAN requires its own DHCP pool
- DHCP relies on proper VLAN + routing configuration

---

### Takeaway
DHCP automates IP assignment, making networks scalable and easier to manage
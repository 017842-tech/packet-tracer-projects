##  Project Notes — Multi-Switch VLAN Network

### Commands Used
- show vlan brief
- show interfaces trunk
- show ip interface brief
- show ip dhcp binding
- ping

---

### Issues Encountered
- Router link initially down
- Needed trunk configuration on both switches
- VLANs had to be created on both switches

---

### Troubleshooting Steps
1. Verified trunk links on both switches
2. Confirmed VLAN presence using show vlan brief
3. Checked router subinterfaces
4. Verified DHCP assignments
5. Tested connectivity across switches

---

### Key Learning
- VLANs must exist on all switches
- Trunk links carry VLAN traffic between switches
- Router provides centralized routing and DHCP
- Multi-switch networks improve scalability

---

### Takeaway
This project demonstrates how enterprise networks scale using multiple switches while maintaining VLAN segmentation and centralized routing
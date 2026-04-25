##  Project Notes — VLAN Segmentation

### Commands Used
- show vlan brief → Verified VLAN creation and port assignment
- ping → Tested connectivity within and across VLANs

---

### Issues Encountered
- Devices in different VLANs could not communicate (expected behavior)
- Incorrect VLAN assignment caused communication issues

---

### Troubleshooting Steps
1. Verified VLAN creation (VLAN 10, VLAN 20)
2. Checked port assignments using show vlan brief
3. Tested:
   - Same VLAN → successful ping
   - Different VLAN → failed ping

---

### Key Learning
- VLANs create separate logical networks on the same switch
- Switches do not allow communication between VLANs (Layer 2 limitation)
- Network segmentation improves organization and security

---

### Takeaway
VLANs separate networks, even if devices are physically connected to the same switch
# Networking Task 02 — Network Devices & IP Addressing

**Intern:** Sanjana
**Date:** 06 June 2026
**Organization:** White Band Associates

---

## 📁 Repository Structure

| File | Description |
|------|-------------|
| `screenshots/ipconfig_all.png` | Part C & E — ipconfig /all output |
| `screenshots/nslookup_google.png` | Part E — nslookup google.com output |
| `screenshots/ping_google.png` | Part E — ping google.com output |
| `part_a_network_devices.md` | Part A — Research on 6 network devices |
| `part_b_ip_classification.md` | Part B — Public vs Private IP classification |
| `part_c_understanding_network.md` | Part C — Understanding my own network |
| `part_d_network_diagram.jpeg` | Part D — Communication flow diagram |
| `part_e_command_outputs.md` | Part E — Command outputs with screenshots and answers |

---

## 📋 Summary of Findings

- My device (`Pookie`) has a private IPv4 address of `192.168.1.106` which belongs to the `192.168.0.0/16` private IP range.
- The Default Gateway and DNS Server are both `192.168.1.1` — my router handles both roles.
- `nslookup google.com` returned multiple IPs for Google including `142.250.146.100`, confirming DNS is working correctly.
- Ping to google.com was successful — 4/4 packets received, 0% packet loss, average **7ms** response time.
- Key learning: DNS is the first and most critical step before any internet communication — without it, domain names cannot be resolved to IP addresses.

# Part C — Understanding Your Network

**Submitted by:** Sanjana
**Date:** 06 June 2026

---

**My network details:**
- IPv4 Address: `192.168.1.106`
- Default Gateway: `192.168.1.1`
- DNS Server: `192.168.1.1`

> Screenshot included in `screenshots/ipconfig_all.png`

---

**1. Which IP range does your device belong to?**

My device's IP `192.168.1.106` belongs to the `192.168.0.0/16` private IP range.

**2. Is it Public or Private?**

It is a **Private** IP address. It is only visible within my home network and not accessible directly from the internet.

**3. What role does your router play in your network?**

My router at `192.168.1.1` plays three roles — it acts as the **Default Gateway** (routing traffic between my device and the internet), the **DHCP server** (assigning IP addresses to devices on the network), and the **DNS server** (resolving domain names locally before forwarding to upstream DNS).

**4. What would happen if the DNS server stopped working?**

If the DNS server stopped working, I would not be able to access any website by name. For example, typing `google.com` would fail because my device wouldn't be able to translate it into an IP address. The internet connection itself would still be active but browsing would be impossible without knowing the exact IP address of every website.

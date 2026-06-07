# Part E — Command Outputs

**Submitted by:** Sanjana
**Date:** 06 June 2026

---

## 1. ipconfig /all

![ipconfig output](screenshots/ipconfig_all.png)

---

## 2. nslookup google.com

![nslookup output](screenshots/nslookup_google.png)

---

## 3. ping google.com

![ping output](screenshots/ping_google.png)

---

## Answers

**1. What IP address did DNS return for Google?**

The `nslookup google.com` command returned multiple IP addresses for Google:
`142.250.146.113`, `142.250.146.100`, `142.250.146.139`, `142.250.146.101`, `142.250.146.102`, `142.250.146.138`

Google uses multiple IPs to distribute traffic across its servers worldwide. My device connected to `142.250.146.100` during the ping.

**2. Was the ping successful?**

Yes, all 4 packets were sent and received with 0% packet loss and an average response time of **7ms**.

**3. Why is DNS important before communication begins?**

DNS translates domain names like `google.com` into IP addresses. Without DNS resolving the address first, your device cannot establish any connection to the destination since computers only understand IP addresses, not names.

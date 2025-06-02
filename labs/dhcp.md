---
layout: default
title: Configuring DHCP
---

# 📡 Configuring DHCP

## 🧠 Definition
DHCP (Dynamic Host Configuration Protocol) automatically assigns IP addresses to devices on a network.

## 🔍 Explanation
DHCP reduces manual configuration errors by dynamically assigning IP addresses, subnet masks, and gateways.

## 📘 Real-World Scenario
**Situation**: A user cannot access the internet due to no IP assignment.

**Solution**:
1. Check that DHCP is enabled on the router.
2. Run `ipconfig /release` and `ipconfig /renew`.
3. Restart the DHCP Client service.
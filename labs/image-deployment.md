---
layout: default
title: Windows Image Deployment
---

# 💻 Windows Image Deployment

## 🧠 Definition
Image deployment refers to distributing a pre-configured OS image to multiple machines.

## 🔍 Explanation
Tools like MDT and WDS are used to streamline large-scale OS deployments in enterprise environments.

## 📘 Real-World Scenario
**Situation**: IT must deploy Windows 10 to 100 new laptops.

**Solution**:
1. Use MDT to create a deployment share.
2. Capture a reference image.
3. Deploy the image over PXE boot.
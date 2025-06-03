# 🧪 A+ Labs & Practice Scenarios

This section includes hands-on practice scenarios for the CompTIA A+ certification — focused on practical desktop, networking, hardware, and troubleshooting knowledge.

---

## 🎓 Overview

CompTIA A+ is often the first step into IT careers. These labs simulate real-world help desk, hardware, and OS issues you'll likely face on the job.

---

## 🔧 Lab 1: No Display Output (Hardware)

**Scenario**: A user reports that their desktop turns on, but nothing shows on the monitor.

**Steps to Practice**:
1. Power off and unplug the machine.
2. Open the case and reseat RAM and GPU.
3. Plug in the monitor to onboard graphics if available.
4. Try another known-working monitor and cable.

**Expected Outcome**: Determine if GPU is faulty or if another component (e.g., RAM or PSU) is causing boot failure.

---

## 🌐 Lab 2: No Internet Access (Network Troubleshooting)

**Scenario**: A user can't connect to the internet but the computer shows it's connected to Wi-Fi.

**Steps to Practice**:
1. Use `ipconfig` or `ifconfig` to confirm IP address.
2. Ping `8.8.8.8` to check for external reach.
3. Run `nslookup google.com` to verify DNS resolution.
4. Reboot router or reassign a static IP if needed.

**Expected Outcome**: Restore working internet and document findings.

---

## 🪟 Lab 3: Windows Blue Screen

**Scenario**: Random BSOD with error `MEMORY_MANAGEMENT`.

**Steps to Practice**:
1. Boot into Safe Mode.
2. Run `sfc /scannow` and `chkdsk`.
3. Use Windows Memory Diagnostic Tool.
4. Update all drivers or roll back recent updates.

**Expected Outcome**: Identify and resolve hardware/driver-related crash.

---

## 🛠️ Lab 4: Printer Not Responding

**Scenario**: A shared network printer isn't responding for multiple users.

**Steps to Practice**:
1. Verify power/network connections.
2. Restart print spooler (`services.msc`).
3. Check IP address of printer and test ping.
4. Re-add printer via control panel.

**Expected Outcome**: Restore print services and document steps taken.

---

## 🗃️ Common Commands to Practice

| Command                   | Platform  | Description                              |
|--------------------------|-----------|------------------------------------------|
| `ipconfig /all`          | Windows   | Show IP, DNS, MAC                        |
| `ping`, `tracert`, `nslookup` | All  | Troubleshoot network path and DNS        |
| `sfc /scannow`           | Windows   | Check and repair system files            |
| `diskpart`               | Windows   | Partitioning and volume management       |
| `tasklist`, `taskkill`   | Windows   | View and terminate running tasks         |

---

## 🧠 Extra Credit: Build Your Own Lab

Try setting up a home lab using VirtualBox or VMware:
- Install Windows 10/11 and Ubuntu
- Simulate device drivers, software installs, and malware cleanup
- Connect virtual machines via internal networks

---

## 📢 Public Engagement & Feedback

**Have you encountered these issues?**
- Share your own lab simulations or PC repair stories.
- Post screenshots of your A+ troubleshooting labs.
- Offer your best beginner tip for someone entering IT support.

Let’s build lab mastery — together!


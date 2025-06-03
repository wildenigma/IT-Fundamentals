# 🧪 A+ Labs – Part 2: Real-World Troubleshooting Scenarios

This lab section covers practical, scenario-based issues and step-by-step resolutions. Perfect for help desk or field tech readiness.

---

## 🔧 Scenario 1: PC Won’t Boot

**Symptoms**:  
- No display  
- Fans spin, but no beep  
- Power light is on  

**Checklist & Fix**:  
- ✅ Check power supply and surge protector  
- ✅ Reseat RAM and GPU  
- ✅ Listen for POST beeps  
- ✅ Swap monitor or test with onboard video  
- 🛠️ **Fix**: Reseat components → Clear CMOS → Replace PSU if dead

---

## 🧠 Scenario 2: “No Internet Access” but Connected to Wi-Fi

**Symptoms**:  
- Connected to Wi-Fi but “No Internet” message  
- Can’t load any websites  

**Checklist & Fix**:  
- ✅ Run `ipconfig /all` (Windows) or `ifconfig` (Linux/Mac)  
- ✅ Ping router: `ping 192.168.1.1`  
- ✅ Check DNS: Try `nslookup google.com`  
- 🛠️ **Fix**:  
  - Release/renew IP: `ipconfig /release` → `ipconfig /renew`  
  - Set manual DNS to `8.8.8.8` (Google DNS)  
  - Restart router if needed  

---

## 💽 Scenario 3: Slow Performance

**Symptoms**:  
- Takes forever to boot or open apps  
- High CPU usage  

**Checklist & Fix**:  
- ✅ Task Manager: Look for high CPU/disk usage  
- ✅ Disable startup apps (`msconfig` or Task Manager > Startup)  
- ✅ Run antivirus scan  
- ✅ Check disk health: `chkdsk`  
- 🛠️ **Fix**: Disable bloatware, optimize startup, defragment (HD
 Lab: USB Device Not Recognized

Scenario: A USB flash drive isn’t detected by the system.

Steps:

    Use diskpart and list disk to see if it’s recognized.

    Update USB drivers via Device Manager.

    Try another port or boot into Safe Mode for driver isolation.

🌐 Lab: DNS Issues on a Workstation

Scenario: Websites won’t load, but ping works.

Diagnosis:

    Check DNS resolution:
nslookup www.google.com
Flush DNS:
ipconfig /flushdns

💽 Lab: Full Hard Drive Warning

Scenario: User gets "disk full" message, can’t install apps.

Steps:

    Run:

cleanmgr

    Identify large folders:

Get-PSDrive

    Use Disk Cleanup or Storage Sense.

📢 Public Challenge

Have you faced these problems on your job or PC?

    Try these steps and share screenshots or your outcome.

    What tool or fix saved the day?
📌 Optional Additions Y:
1. Part 3: Diagnostic Tools in Action

    Focused labs using:

        BIOS/UEFI

        chkdsk, sfc /scannow, MemTest86

        Device Manager deep dive

2. Part 4: Preventive Maintenance

    Dust cleaning

    Power supply checks

    OS optimization tools

3. Part 5: Hands-On Printable Checklist

    Markdown-formatted checklists for:

        “First Visit IT Checks”

        “Post-Deployment Review”

        “User Setup Flow”

4. 🖼️ Visuals Folder (Optional):

If you’re generating diagrams using Adobe tools, you can:

    Upload .png or .jpg files into a subfolder:
    fundamentals/A+ labs/images/
![BIOS Menu Example](images/bios-example.png)


# 🌐 TCP/IP & OSI Model Diagrams

Understanding how devices communicate on a network is critical for IT support and cybersecurity. These two models explain that flow.

---

## 📖 Definition: OSI vs TCP/IP

| Model     | Layers | Purpose |
|-----------|--------|---------|
| **OSI**   | 7      | Conceptual model to standardize communication functions |
| **TCP/IP**| 5      | Practical model used in modern networking (Internet-based) |

---

## 🧠 Explanation (Layman's Terms)

Think of network communication like **sending a letter**:
- You write the letter → put it in an envelope → add an address → the post office routes it → it's delivered and read.
- That's what layers in OSI and TCP/IP do — package and deliver data between computers.

---

## 📊 OSI Model: 7 Layers

| Layer | Name              | Device Example     | Protocol Example     |
|-------|-------------------|--------------------|----------------------|
| 7     | Application       | Web browser        | HTTP, FTP            |
| 6     | Presentation      | Data translators   | SSL/TLS, JPEG        |
| 5     | Session           | Connection managers| NetBIOS, RPC         |
| 4     | Transport         | Firewall, OS       | TCP, UDP             |
| 3     | Network           | Router             | IP, ICMP             |
| 2     | Data Link         | Switch, NIC        | Ethernet, ARP        |
| 1     | Physical          | Cables, Wi-Fi      | Electrical/Radio     |

---

## 🌐 TCP/IP Model: 5 Layers

| Layer | OSI Equivalent        | Protocol Examples         |
|-------|------------------------|----------------------------|
| 5     | Application (7–5)      | HTTP, DNS, FTP, SMTP       |
| 4     | Transport (4)          | TCP, UDP                   |
| 3     | Internet (3)           | IP, ICMP                   |
| 2     | Data Link (2)          | Ethernet, Wi-Fi            |
| 1     | Physical (1)           | Copper, Fiber, Wireless    |

---

## 🔁 Real-World Scenario

**Scenario**: You can't reach a website.

**What to Check (Layer by Layer)**:
1. **Physical**: Is the cable plugged in? Wi-Fi signal?
2. **Data Link**: Is the NIC working? Blinking lights?
3. **Network**: Do you have an IP? Can you ping the gateway?
4. **Transport**: Is the port (80/443) open? Are firewalls blocking it?
5. **Application**: Is the browser working? DNS resolving?

---

## ⚙️ Components, Problems, and Fixes

| Component | Layer | Issue                        | Fix                        |
|-----------|-------|------------------------------|----------------------------|
| Ethernet Cable | 1 | Broken or loose             | Replace or reseat cable    |
| Network Interface Card | 2 | Disabled or driver error | Re-enable or reinstall driver |
| Router | 3 | No DHCP, IP conflict              | Reboot or reconfigure      |
| Firewall | 4 | Blocking port or protocol       | Add rule or whitelist app  |
| DNS Server | 5 | Can't resolve domain names     | Use public DNS like 8.8.8.8|

---

## 📈 Diagrams

### OSI Model Stack
7 - Application
6 - Presentation
5 - Session
4 - Transport
3 - Network
2 - Data Link
1 - Physical

### TCP/IP Simplified Stack
5 - Application
4 - Transport
3 - Internet
2 - Data Link
1 - Physical

---

## 💬 Public Discussion / Engagement

- Which layer do you troubleshoot the most?
- Have you memorized the OSI model with mnemonics?
- Share your “can't connect” story and how you fixed it!

---

> 🛠️ File version: `tcp-osi-models.md` • Part of the `Fundamentals > Networking` category

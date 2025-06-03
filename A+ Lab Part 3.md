# 🧪 A+ Labs – Part 3: Command Line Essentials & Practice

The command line is a powerful toolset for support techs. This section provides essential commands and practice scenarios across platforms.

---

## 🖥️ Windows Command Line Tools

| Command           | Function                          | Example                           |
|------------------|-----------------------------------|-----------------------------------|
| `ipconfig`        | Show network config               | `ipconfig /all`                   |
| `ping`            | Test network reachability         | `ping google.com`                 |
| `sfc`             | Check system file integrity       | `sfc /scannow`                    |
| `chkdsk`          | Check disk for errors             | `chkdsk /f`                       |
| `netstat`         | Display network connections       | `netstat -an`                     |
| `tasklist`        | Show running processes            | `tasklist`                        |
| `systeminfo`      | Display system specs              | `systeminfo`                      |

---

## 🐧 Linux/macOS Terminal Commands

| Command           | Function                          | Example                           |
|------------------|-----------------------------------|-----------------------------------|
| `ifconfig` / `ip` | Show network info                 | `ip a` or `ifconfig`              |
| `ping`            | Ping a host                       | `ping -c 4 google.com`            |
| `top` / `htop`    | Show running processes            | `top`                             |
| `df`              | Disk usage                        | `df -h`                           |
| `du`              | Directory space usage             | `du -sh /home/user`               |
| `journalctl`      | View system logs                  | `journalctl -xe`                  |
| `whoami`          | Current user                      | `whoami`                          |

---

## 🧪 Practice Labs

### ⚙️ Lab 1: Diagnose a Network Issue (Windows)
**Problem**: User says they can’t browse websites  
**Steps**:  
- Run `ipconfig /all` to confirm IP info  
- Use `ping 8.8.8.8` and `ping google.com`  
- Check DNS by running `nslookup`  
**Expected Fix**: Set static DNS or restart network adapter

---

### 🐧 Lab 2: Monitor CPU & Disk Usage (Linux)
**Scenario**: Server running slowly  
**Steps**:  
- Use `top` or `htop` to see CPU usage  
- Use `df -h` to check disk usage  
- Clear logs if `/var/log` is full  

---

### 🖼️ Lab 3: Create a Diagnostic Report (Windows)
**Goal**: Build a system overview  
**Steps**:  
- Run `systeminfo`  
- Export to text file: `systeminfo > report.txt`  
- Include output from `tasklist` and `netstat`  

---

## 🧠 Public Engagement

Have a favorite command or shortcut that saved the day?  
Post your best CLI fix or terminal trick here!

Let’s sharpen those command-line skills together. 🔧💻

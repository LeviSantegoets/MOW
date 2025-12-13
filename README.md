# ManOWar — Windows Utility & Network Toolkit  
**Version: 0.36**  
Author: *Levi Santegoets, The Netherlands, email: contact.levisantegoets@gmail.com*

ManOWar is an advanced Windows batch-based toolkit designed to centralize a wide range of system, network, diagnostic, and administrative utilities into a single interactive menu-driven interface.

It includes modules for system information, networking, automation, file operations, and various helper tools aimed at simplifying everyday Windows administration workflows.

> ⚠️ **Access Restriction Notice**  
> The program requires whitelisting of **at least the first two octets of your public IPv4 address** to run.  
>  
> This whitelisting controls **access to the program itself**, *not API or internet-related functions*.  
>  
> Example:  
> If your public IP is `203.44.x.x`, whitelist  
> **`203.44`**

---

## ✨ Features

### 🔧 **System & Administration**
- Detailed system information  
- Process & service utilities  
- Disk and cleanup tools  
- Windows administration shortcuts  
- PowerShell-integrated tasks  

### 🌐 **Networking**
- Network configuration views  
- External IP detection  
- DNS tools  
- Ping, traceroute, and routing utilities  
- Wi-Fi and adapter information  

### 📁 **File & Utility Modules**
- Folder automation  
- Backup helpers  
- File parsing utilities  
- System report helpers  
- Log utilities *(see below)*  

---

## 🚧 **Activity Logging Status**
ManOWar includes a built-in logging engine that is currently **in development**.  
Some modules may not log activity yet, and log formats may change in upcoming versions.

---

## 🔒 **Security Notes**

### **Program Access Control**
ManOWar uses a whitelisting system to ensure only approved public IPv4 ranges can start the program.

This is a lightweight safeguard intended to:
- Prevent unauthorized remote use  
- Limit execution to known IP ranges  
- Provide basic access control without requiring accounts or tokens  

This restriction applies **to launching the program**, not to:
- API usage  
- Online lookups  
- Network queries  

### **Local Execution**
For full functionality:
- Run locally (not from shared/UNC paths)  
- Launch with administrator privileges  
- Leave PowerShell enabled on the system  

---

## 🖥️ **Usage**
1. Download the latest `.bat` release  
2. Ensure your public IPv4 is whitelisted  
3. Right-click → **Run as Administrator**  
4. Navigate using the menu system and on-screen prompts  

---

## 📌 **Requirements**
- Windows 10 or newer  
- Admin rights recommended  
- Internet connection for online modules  
- Whitelisted IPv4 range to start the program  

---

## 🧩 **Project Status**
Active development — upcoming improvements:
- Full activity logging implementation  
- Improved menu structure and UX  
- Extensible plugin-like module system  
- Optional PowerShell backend  
- Better error-handling and diagnostics  

---

## 🤝 **Contributing**
Issues, improvement suggestions, and pull requests are welcome.  
You may also propose new modules or GUI expansions.

---

## 📜 **License**
All rights reserved by the author unless otherwise stated.

---

## 📘 The Story Behind ManOWar

ManOWar began as a simple idea by Levi Santegoets — a Windows and Linux enthusiast who got tired of fixing the same problems over and over. After helping friends, coworkers, and just about anyone who looked confused near a computer, he decided it was time to automate the tasks that people shouldn’t have to do manually.

So Levi built a small set of tools. Then a bigger set. Then a menu system.  
Piece by piece, it grew into the toolkit now known as **ManOWar** — a practical, no-nonsense collection of scripts meant to make Windows administration quicker, cleaner, and less frustrating for everyone.

Levi didn’t make it for fame or attention. He made it because good tools save time, reduce stress, and keep people focused on what actually matters.  
If ManOWar makes someone’s day even slightly easier, he considers that a win.

*And if it breaks something… well, that’s why we have version numbers.* 😄


# ManOWar — Windows Utility & Network Toolkit  
**Version: 0.33**  
Author: *Levi Santegoets, The Netherlands*

ManOWar is an advanced Windows batch-based toolkit designed to centralize a wide range of system, network, diagnostic, and utility functions into a single interactive command-line interface.

It includes modules for system information, network analysis, file operations, administrative automation, security-oriented tools, update helpers, and various utility workflows.  
The script is fully menu-driven and is intended to streamline repetitive administrative tasks.

> ⚠️ **Important Notice — Access Restrictions**  
> To use all online features and remote API-based functionality, users **must whitelist at least the first two octets of their public IPv4 address**.  
> Example:  
> If your IP is `203.44.x.x`, whitelist  
> **`203.44.*.*`**

---

## ✨ Features

### **🔧 System & Administrative Tools**
- System information summaries  
- Process and service utilities  
- System cleanup helpers  
- PowerShell integrations  
- Administrative command shortcuts  
- Local configuration helpers  

### **🌐 Network Utilities**
- IP configuration tools  
- Network lookup utilities  
- External IP detection  
- API-based online queries (requires IP whitelisting)  
- Ping, trace, routing helpers  
- DNS utilities  
- Wi-Fi information tools  

### **📁 File & Data Utilities**
- Automated folder management  
- Backup helpers  
- File parsing utilities  
- Data extraction and formatting  
- Log-related functions (see note below)

### **🚧 Activity Logging (In Development)**
A full activity-logging system is being built, designed to track:
- Module usage  
- Important actions  
- Error events  
- User interactions  

**This feature is not yet complete**, and some logging functions may be placeholders.

---

## 🔒 Security Notes

### **Public IP Whitelisting**
Several modules rely on external API access.  
To enable these functions, the operator must **whitelist the first two octets** of their public IPv4 address.

This is a temporary security measure until a more sophisticated authentication system is implemented.

### **Local Execution Requirement**
Because of Windows security and API permissions:
- Run ManOWar from a **local drive** (not UNC paths).  
- Execute with **administrator privileges** for full functionality.  

---

## 🖥️ Usage

1. Download the latest `.bat` file.  
2. Right-click → **Run as Administrator**.  
3. Navigate using the menu system and on-screen prompts.  
4. Ensure your IP range is whitelisted if using API-based or online modules.

---

## 📌 Requirements
- Windows 10 or higher  
- Administrator privileges recommended  
- Internet connection (for remote utilities)  
- Whitelisted IPv4 range (first two octets)

---

## 🧩 Project Status
ManOWar is an active, evolving project.  
Upcoming work includes:
- Complete activity-logging engine  
- Improved remote API security  
- Menu restructuring for readability  
- Optional PowerShell backend integration  

---

## 🤝 Contributions
Feel free to open issues or submit pull requests.  
Suggestions for modules, optimizations, or menu structure improvements are welcome.

---

## 📜 License
All rights reserved by the author unless stated otherwise.


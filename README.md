# Linux Commands and Shell Scripts Assignment

This repository contains documentation of 20 Linux commands along with three shell scripts developed as part of a practical assignment.  
All commands and scripts were executed and tested on Ubuntu Linux.

---

## 📁 Folder Structure

linux-shell-commands-and-scripts/
│
├── linux_commands/
│   ├── commands.txt
│   ├── command_outputs.txt (optional)
│   ├── *output screenshots*
│
├── scripts/
│   ├── backup.sh
│   ├── monitor.sh
│   ├── download.sh
│   ├── scripts.txt
│   ├── *script screenshots*

---

## 📝 20 Linux Commands Documentation

The documentation includes:
- Syntax  
- Description  
- When & Why the command is used  
- Terminal output screenshots  

Commands covered:
- File Navigation  
- File & Directory Management  
- Permissions  
- Process Monitoring  
- Networking Tools  

All screenshots are included inside the **linux_commands** folder.

---

## 🖥 Shell Scripts Developed

### **1️⃣ backup.sh**
Creates a timestamped backup of a directory.
- Creates backup folder (if missing)
- Adds a timestamp using `date`
- Copies files using `cp -r`

### **2️⃣ monitor.sh**
Logs CPU and memory usage every 5 seconds.
- Uses `top` for CPU load
- Uses `free -h` for memory
- Saves logs to `system_usage.log`

### **3️⃣ download.sh**
Automatically downloads a file using `wget`.
- Defines download URL
- Creates destination folder
- Stores file using `wget -P`

---

## 📷 Screenshots

All screenshots (command outputs + script outputs) are inside:
- `linux_commands/`
- `scripts/`

---

## ✔ Completed By:
**Md Shahjad**  
Course: Linux Shell Scripting  
Submission Date: 16/11/2025

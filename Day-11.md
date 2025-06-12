# **Day 11 – Windows OS Management**

## 📌 Topics Covered:

1. Versions of Windows

2. Download & Install Windows

3. System Access & Navigation

4. File System Overview

5. User Account Management

6. Resource Monitoring

7. Event Logs

8. Server Manager Dashboard

9. Device Manager & Hardware Check

10. Roles & Features

11. Active Directory & Domain Controller

12. Quiz + Homework


<br>

## 1. Versions of Windows

| Edition                | Purpose                 |
| ---------------------- | ----------------------- |
| **Windows 10/11 Home** | Personal/Home use       |
| **Windows Pro**        | Small business features |
| **Windows Server**     | Enterprise server OS    |
| **Windows Education**  | Academic institutions   |

<br>

## 2. Download & Install Windows

* Download from official [Microsoft site](https://www.microsoft.com/software-download/)
* Use tools like:

  * **Rufus** to create bootable USB
  * **VirtualBox/VMware** to install as VM
* Follow the installation wizard:

  * Language & Region
  * Disk partition
  * User setup

<br>

## 3. Windows System Access

* **Start Menu** = Launch programs
* **Settings** = Control system config
* **Control Panel** = Advanced admin tools
* **File Explorer** = Access files & drives
* **Taskbar** = Open apps & pinned shortcuts
* **Search** = Find files/settings instantly

<br>

## 4. File System Overview

| Folder                 | Purpose                     |
| ---------------------- | --------------------------- |
| `C:\`                  | Main system drive           |
| `C:\Program Files`     | Installed software          |
| `C:\Users`             | User profiles & data        |
| `C:\Windows`           | Core OS files               |
| `Temp` & `Recycle Bin` | Temporary and deleted files |

📁 File system type: **NTFS**

<br>

## 5. User Account Management

* **Admin vs. Standard User**
* Add new users via:
  `Settings > Accounts > Family & other users`
* Change password, access levels, lock users
* Use `Control Panel > User Accounts` for advanced settings

<br>

## 6. System Resource Monitoring

Use **Task Manager (Ctrl+Shift+Esc)**:

* Monitor CPU, RAM, Disk, Network usage
* End unresponsive tasks
* Start-up apps list

Also try:

* `Resource Monitor`
* `Performance Monitor`

<br>

## 7. Event Logs

Use **Event Viewer** to trace system activity:

* Logs for Application, Security, System
* Great for troubleshooting & auditing

Shortcut: `Windows + R` → `eventvwr`

<br>

## 8. Server Manager Dashboard (For Windows Server)

* Used for managing server roles, features, and performance
* Dashboard shows status of:

  * Local Server
  * Roles & Features
  * Events
  * Services

<br>

## 9. Device Manager & Hardware Check

Use `Device Manager` to:

* View connected hardware
* Update/uninstall drivers
* Check for issues (yellow warning icons)

Shortcut: `Windows + X > Device Manager`

<br>

## 10. Roles & Features (Windows Server)

Used to install server capabilities like:

* DNS Server
* Web Server (IIS)
* File Server
* Active Directory

Access via **Server Manager > Add Roles and Features**

<br>

## 11. Active Directory & Domain Controller

* **Active Directory (AD)**: Centralized user/computer management
* **Domain Controller (DC)**: Server running AD
* Users login to network using **domain credentials**
* Used in companies and schools for:

  * Authentication
  * Group policies
  * Access control

<br>

### 📝 Quiz (6 Questions)

1. What is the **main system folder** in Windows OS?

        a) /root
        b) C:\Program Files
        c) C:\Users
        d) C:\\

2. What tool shows **CPU, RAM, Disk usage** in real-time?

        a) Event Viewer
        b) Device Manager
        c) Task Manager
        d) Control Panel

3. Which folder stores **user profiles** in Windows?

        a) C:\Windows
        b) C:\System32
        c) C:\Users
        d) C:\Documents

4. What is the **file system** used by Windows OS?

        a) FAT32
        b) ext4
        c) NTFS
        d) xfs

5. What is **Active Directory** used for?

        a) Virus scanning
        b) Media storage
        c) User and computer management
        d) Power management

6. Where can you install **Roles and Features** in Windows Server?

        a) Event Viewer
        b) Server Manager
        c) Task Scheduler
        d) BIOS

<br>

### ✅ Homework Activities

* Install Windows 10/11 on a VM (optional)
* Explore `Settings`, `Control Panel`, and `Task Manager`
* Check your system info: `Win + Pause`
* Try adding a new user account
* Open Event Viewer and browse logs
* OPTIONAL: Watch “Windows OS Explained for Beginners” on YouTube

---
Home: [Main Page](/README.md) | Previous: [Day-10 - Security](/Day-10.md) | Up Next: [Day-12 - Linux OS Management](/Day-12.md)

<br>

### 🤝 Let's Connect!
---

If you enjoy this course, consider:
- Follow me on **[LinkedIn](https://www.linkedin.com/in/thanvir-assif-1b3435203/)**
- Subscribe to my YouTube channels:
        
    * [Thanvir Assif](https://www.youtube.com/@thanvirassif731) 
    * [Learn With Ash - Tamil](https://www.youtube.com/@learnwithashtamil7)

- Book 1:1 guidance via **[Topmate](https://topmate.io/thanvir_assif/)**

---
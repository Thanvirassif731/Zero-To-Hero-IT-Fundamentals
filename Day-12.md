# **Day 12 – Linux OS Management**

### 📌 Topics Covered:

1. What is Linux & Distros

2. Download & Install Linux (CentOS/Ubuntu)

3. Accessing Linux

4. Install PuTTY (for Windows Users)

5. Access Linux via PuTTY

6. Linux File System Structure

7. File System Navigation

8. File/Directory Operations

9. System Utility Commands

10. System Monitoring & Maintenance

11. Quiz + Homework


<br>

## 1. What is Linux?

> **Linux** is an open-source, Unix-like OS used in servers, cloud, networking, cybersecurity, and even smartphones (Android).

**Key Features:**

* Free & open source
* Command-line focused
* Super lightweight & fast
* Used in **data centers, cloud platforms, DevOps, AI/ML environments**

<br>

## 2. Linux Distributions (Distros)

| Distro           | Use Case                             |
| ---------------- | ------------------------------------ |
| **Ubuntu**       | Beginner-friendly, desktop/server    |
| **CentOS/RHEL**  | Enterprise Linux (used in companies) |
| **Debian**       | Stable and base for other distros    |
| **Kali Linux**   | Penetration testing                  |
| **Alpine Linux** | Lightweight containers (Docker)      |

<br>

## 3. Download & Install Linux

✅ Choose Ubuntu or CentOS
Download ISO from:

* [Ubuntu](https://ubuntu.com/download/server)
* [CentOS Stream](https://www.centos.org/centos-stream/)

**Install via:**

* VirtualBox / VMware
* Bootable USB using Rufus (for real hardware)

<br>

## 4. Install PuTTY (for Windows Users)

* Download PuTTY from: [https://www.putty.org](https://www.putty.org)
* Install the `.exe` file
* Used to access Linux VMs via SSH (Secure Shell)

<br>

## 5. Access Linux VM via PuTTY

1. Start your Linux VM
2. Note the IP address: `ip a` or `ifconfig`
3. Open PuTTY, enter IP, and connect via SSH
4. Login with username (`root` or `user`) and password

<br>

## 6. Linux File System Structure

| Folder  | Purpose                    |
| ------- | -------------------------- |
| `/`     | Root directory             |
| `/home` | User directories           |
| `/etc`  | System config files        |
| `/var`  | Logs, cache, mail          |
| `/usr`  | User-installed software    |
| `/bin`  | Essential command binaries |
| `/root` | Root user's home folder    |
| `/tmp`  | Temporary files            |

<br>

## 7. File System Navigation Commands

| Command | Description             |
| ------- | ----------------------- |
| `pwd`   | Print current directory |
| `cd`    | Change directory        |
| `ls`    | List files and folders  |
| `ls -l` | Long listing format     |
| `cd ..` | Go back one directory   |

<br>

## 8. File/Directory Operations

| Command          | Action              |
| ---------------- | ------------------- |
| `touch file.txt` | Create new file     |
| `mkdir folder`   | Create directory    |
| `rm file.txt`    | Delete file         |
| `rm -r folder`   | Delete folder       |
| `cp src dest`    | Copy files          |
| `mv old new`     | Rename or move file |

<br>

## 9. System Utility Commands

| Command   | Purpose                    |
| --------- | -------------------------- |
| `clear`   | Clears terminal screen     |
| `history` | Shows past commands        |
| `man`     | Manual/help pages          |
| `whoami`  | Shows current user         |
| `date`    | Current date & time        |
| `uptime`  | How long system is running |

<br>

## 10. System Monitoring & Maintenance

| Command           | Description            |
| ----------------- | ---------------------- |
| `top`             | Show running processes |
| `df -h`           | Disk space usage       |
| `free -h`         | Memory usage           |
| `uname -a`        | Kernel & system info   |
| `shutdown -h now` | Shutdown the system    |
| `reboot`          | Restart the system     |

<br>

### 📝 Quiz (6 Questions)

1. Which folder contains user files in Linux?

        a) /bin
        b) /home
        c) /etc
        d) /var

2. What does `ls` command do?

        a) Change directory
        b) Delete file
        c) List directory contents
        d) Shut down system

3. Which command shows **running processes**?

        a) free
        b) top
        c) uname
        d) df

4. Which folder stores **system config files**?

        a) /etc
        b) /tmp
        c) /bin
        d) /opt

5. Which command displays the **current working directory**?

        a) pwd
        b) whoami
        c) man
        d) cd

6. What tool allows **SSH access to Linux from Windows**?

        a) Hyper-V
        b) Putty
        c) WinRAR
        d) Chrome

<br>

### ✅ Homework Activities

* Install **Ubuntu Server** or **CentOS Stream** on VirtualBox
* Install PuTTY and try to connect to your VM
* Practice file/folder creation, deletion, and navigation
* Use commands like `ls`, `cd`, `pwd`, `top`, `df -h`, `uptime`
* Watch: “Linux Terminal Commands for Beginners” on YouTube

---
Home: [Main Page](/README.md) | Previous: [Day-11 - Windows OS Management](/Day-11.md) | Up Next: [Day-13 - Troubleshooting Concepts](/Day-13.md)

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
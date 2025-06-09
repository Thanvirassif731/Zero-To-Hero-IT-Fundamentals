# **Day 08 – Computer Storage Basics**

### 📌 Topics Covered:

1. Introduction to Storage
2. How Storage is Measured (KB, MB, GB, TB)
3. Types of Computer Storage
4. RAM vs. SWAP vs. Virtual Memory vs. Cache
5. Hard Disk Drives vs. Solid-State Drives
6. RAID (Redundant Array of Independent Disks)
7. Hardware RAID vs. Software RAID
8. Top Data Storage Vendors
9. Quiz + Activities

---

## 1. Introduction to Storage

> Storage = A place to **save and access data**.

All the files, software, and OS are stored in **some kind of storage device**, like a **Hard Disk, SSD, USB, or Cloud**.

🧠 Analogy: Storage is like your **bookshelf** — you can organize and retrieve info when needed.

<br>

## 2. How Storage is Measured

| Unit   | Full Form    | Size                   |
| ------ | ------------ | ---------------------- |
| 1 Bit  | Binary Digit | Smallest unit (0 or 1) |
| 1 Byte | 8 Bits       | A character            |
| 1 KB   | Kilobyte     | 1024 Bytes             |
| 1 MB   | Megabyte     | 1024 KB                |
| 1 GB   | Gigabyte     | 1024 MB                |
| 1 TB   | Terabyte     | 1024 GB                |
| 1 PB   | Petabyte     | 1024 TB                |

**Example:**

* A Word file = \~50 KB
* A song = \~5 MB
* A movie = \~1–2 GB

<br>

## 3. Types of Computer Storage

| Storage Type  | Example              | Volatile? |
| ------------- | -------------------- | --------- |
| **Primary**   | RAM                  | Yes       |
| **Secondary** | HDD, SSD             | No        |
| **Tertiary**  | Tape drives (backup) | No        |
| **Offline**   | USB, CD/DVD          | No        |

<br>

## 4. RAM vs. SWAP vs. Virtual Memory vs. Cache

| Term               | Function                 | Location                   |
| ------------------ | ------------------------ | -------------------------- |
| **RAM**            | Temporary working memory | Physical hardware          |
| **SWAP**           | Fake RAM on hard disk    | Disk                       |
| **Virtual Memory** | Combined RAM + SWAP      | Disk + RAM                 |
| **Cache**          | Super-fast small memory  | CPU (L1, L2) or disk cache |

🧠 Analogy:

* **RAM** = Your desk
* **SWAP** = Drawer under the desk
* **Cache** = Sticky notes on your screen
* **Storage** = Bookshelf

<br>

## 5. Hard Disk Drive vs. Solid-State Drive

| Feature    | HDD                 | SSD                         |
| ---------- | ------------------- | --------------------------- |
| Speed      | Slower (Mechanical) | Very fast (No moving parts) |
| Durability | Less durable        | More durable                |
| Noise      | Makes sound         | Silent                      |
| Cost       | Cheaper             | Costlier                    |

**Tip:** Most modern laptops use SSDs. Servers may use SSDs + HDD combo.

<br>

## 6. RAID – Redundant Array of Independent Disks

RAID is a **method to combine multiple disks** for better performance or reliability.

| RAID Level | Use Case       | Description                             |
| ---------- | -------------- | --------------------------------------- |
| RAID 0     | Speed          | Data split across disks (No redundancy) |
| RAID 1     | Safety         | Mirrors data (Backup)                   |
| RAID 5     | Balance        | Striping + Parity (Needs 3+ disks)      |
| RAID 10    | Speed + Safety | Combination of RAID 1 + RAID 0          |

<br>

## 7. Hardware RAID vs. Software RAID

| Type              | Managed by           | Performance |
| ----------------- | -------------------- | ----------- |
| **Hardware RAID** | RAID controller card | Better      |
| **Software RAID** | OS handles it        | Cheaper     |

🧠 In production servers, **hardware RAID** is preferred.

<br>

## 8. Top Data Storage Vendors

* **Western Digital (WD)** – HDD, SSD
* **Seagate** – HDD
* **Samsung** – SSD
* **Kingston** – SSD
* **NetApp** – Enterprise storage
* **EMC (Dell)** – Enterprise backup & storage
* **IBM** – Cloud storage and enterprise backup

<br>

### 📝 Quiz (6 Questions)

1. Which one is faster:

        a) HDD
        b) SSD
        c) CD-ROM
        d) Tape

2. How many bytes in 1 MB?

        a) 1000
        b) 1024
        c) 1048576
        d) 2048

3. What type of memory is volatile?

        a) RAM
        b) HDD
        c) SSD
        d) DVD

4. Which RAID level mirrors the data?

        a) RAID 0
        b) RAID 1
        c) RAID 5
        d) RAID 10

5. What is cache memory used for?

        a) Backup
        b) Speeding up CPU tasks
        c) Graphics
        d) Storage

6. Which vendor is known for SSDs?

        a) Samsung
        b) NetApp
        c) EMC
        d) IBM

<br>

### ✅ Homework Ideas

* Check your laptop/PC storage type (HDD or SSD)
* Use Task Manager (Windows) or Activity Monitor (Mac) to check **RAM and Virtual Memory**
* Research: “RAID Levels Explained – Simple Guide”
* OPTIONAL: Try a free cloud storage account (like Google Drive) and check storage limits

---
Home: [Main Page](/README.md) | Previous: [Day-07 - Computer Storage Basics](/Day-07.md) | Up Next: [Day-09 - Virtualization and Cloud](/Day-09.md)

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
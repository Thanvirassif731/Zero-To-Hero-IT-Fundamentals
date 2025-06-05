# **Day 06 – Networking**

## 📌 Topics Covered:

1. How Computers Communicate
2. IP Address (Static vs. DHCP)
3. TCP/IP
4. Gateway
5. Subnet Mask
6. MAC Address
7. OSI Model
8. OSI vs. TCP/IP
9. Protocols and Ports
10. Network Devices (Hub, Switch, Router, etc.)
11. How the Internet Works
12. Quiz + Activities

<br>

## 1. How Computers Communicate

Computers talk using **network protocols**.
They send and receive **data packets** across cables, Wi-Fi, or the internet.

**Analogy**: Think of computers like people speaking different languages. Protocols make sure everyone understands each other.

<br>

## 2. IP Address (Static vs. DHCP)

#### IP Address = Identity of a device in a network

Like a house address, used to send/receive data.

| Type               | Description                        |
| ------------------ | ---------------------------------- |
| **Static IP**      | Manually set; doesn't change       |
| **DHCP (Dynamic)** | Automatically assigned by a router |

Example: Your home printer might use a **static IP**, while your phone uses **DHCP**.

<br>

## 3. TCP/IP – Transmission Control Protocol / Internet Protocol

> This is the core language of the internet.

* **TCP** – Breaks data into packets, ensures delivery
* **IP** – Delivers each packet to the right address

<br>

## 4. Gateway

A **gateway** connects your local network to the **outside world** (like the internet).
Usually, your **home router** is the gateway.

<br>

## 5. Subnet Mask

Used to divide a network into **sub-networks** (subnets).

Think of it like separating departments in a company — each subnet is a group of computers that can communicate internally.

<br>

## 6. MAC Address

> MAC = Media Access Control

* Unique **hardware address** of a device’s network card
* Example: `F0:4D:A2:1C:3E:90`
* Doesn’t change, unlike IP

**Analogy:** MAC is like your **fingerprint**, IP is like your **home address**.

<br>

## 7. OSI Model (7 Layers)

A theoretical model showing **how data flows** from one device to another.

| Layer            | Description             | Example    |
| ---------------- | ----------------------- | ---------- |
| 7 - Application  | End-user interface      | Browser    |
| 6 - Presentation | Data formatting         | Encryption |
| 5 - Session      | Start/stop sessions     | Logins     |
| 4 - Transport    | Break/rebuild data      | TCP/UDP    |
| 3 - Network      | IP address & routing    | IP         |
| 2 - Data Link    | MAC address & switching | Ethernet   |
| 1 - Physical     | Cables, Wi-Fi           | Hardware   |

**Mnemonic**: **A**ll **P**eople **S**eem **T**o **N**eed **D**ata **P**rocessing

<br>

## 8. OSI vs. TCP/IP

| Feature         | OSI Model                                   | TCP/IP Model                  |
| --------------- | ------------------------------------------- | ----------------------------- |
| Layers          | 7                                           | 4                             |
| Use             | Theoretical                                 | Practical, used in real world |
| Layers Combined | Yes (e.g., App + Pres + Sess = Application) | Yes                           |

<br>

## 9. Protocols and Ports

Protocols = Rules for communication
Ports = Virtual doors for traffic

| Protocol | Port | Use                         |
| -------- | ---- | --------------------------- |
| HTTP     | 80   | Web (insecure)              |
| HTTPS    | 443  | Secure web                  |
| FTP      | 21   | File transfer               |
| SSH      | 22   | Secure shell (remote login) |
| DNS      | 53   | Name to IP lookup           |
| SMTP     | 25   | Email sending               |

>Tip: You’ll use ports **a lot** when working with servers and firewalls.

<br>

## 10. Network Devices

| Device           | Function                                        |
| ---------------- | ----------------------------------------------- |
| **Hub**          | Broadcasts data to all (old tech)               |
| **Switch**       | Smarter, sends data only to the intended device |
| **Router**       | Connects networks (home to internet)            |
| **Modem**        | Connects to ISP (Internet Service Provider)     |
| **Access Point** | Extends Wi-Fi range                             |

<br>

## 11. How the Internet Works (Simplified)

1. You type `www.google.com`
2. Your computer asks DNS to find its IP
3. Browser connects to Google’s server using IP
4. Google sends data back via routers & networks
5. Page appears in your browser!

**Analogy:** Like writing a letter → post office → mailbox → delivery.

<br>

## 📝 Quiz (8 Questions)

1. What assigns IPs dynamically?

        a) DNS
        b) Router using DHCP
        c) MAC
        d) Modem

2. Which protocol is secure for web browsing?

        a) HTTP
        b) FTP
        c) HTTPS
        d) SMTP

3. What’s the full form of IP?

        a) Internet Port
        b) Internal Path
        c) Internet Protocol
        d) Internal Protocol

4. What port does SSH use?

        a) 21
        b) 80
        c) 22
        d) 443

5. What is the role of a switch?

        a) Connect to ISP
        b) Send data to all devices
        c) Send data to correct device
        d) Manage internet speed

6. MAC address is stored in:

        a) Software
        b) Hard disk
        c) Network card hardware
        d) Operating system

7. Which OSI layer deals with IP addressing?

        a) Layer 1
        b) Layer 3
        c) Layer 5
        d) Layer 7

8. What does DNS do?

        a) Stores passwords
        b) Manages Wi-Fi
        c) Translates domain names to IP addresses
        d) Encrypts data

<br>

## ✅ Homework Ideas

1. Open `Command Prompt` or `Terminal` and try:

   * `ipconfig` (Windows)
   * `ifconfig` or `ip a` (Linux/macOS)
2. Find your:

   * IP address
   * Gateway
   * Subnet Mask
   * MAC Address
3. Use `nslookup google.com` or `ping google.com`

---
Home: [Main Page](/README.md) | Previous: [Day-05 - Software](/Day-05.md) | Up Next: [Day-07 - Database](/Day-07.md)

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
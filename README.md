# 🦌 Hack The Box - Fawn

![Difficulty](https://img.shields.io/badge/Difficulty-Very_Easy-brightgreen)
![Category](https://img.shields.io/badge/Category-Starting_Point-blue)
![Platform](https://img.shields.io/badge/Platform-Hack_The_Box-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

# 📌 Room Information

| Category | Details |
|----------|---------|
| Platform | Hack The Box |
| Machine | Fawn |
| Difficulty | Very Easy |
| Operating System | Linux |
| Status | ✅ Completed |

---

# 🎯 Objectives

- Learn basic FTP enumeration.
- Identify open ports and running services.
- Understand anonymous FTP authentication.
- Access files on a remote FTP server.
- Capture the flag.

---

# 🛠️ Tools Used

- Kali Linux
- Nmap
- FTP

---

# 🌐 Target Information

| Target | Description |
|---------|-------------|
| Machine | Linux Target |
| Open Port | 21/TCP |
| Service | FTP |

---

# 🔎 Enumeration

## Check Connectivity

```bash
ping <Target-IP>
```

## Scan the Target

```bash
nmap -sV <Target-IP>
```

### Result

| Port | State | Service |
|------|-------|---------|
| 21 | Open | FTP |
```

---

# 🚀 Exploitation

Connect to the FTP service.

```bash
ftp <Target-IP>
```

Login using:

**Username**

```text
anonymous
```

**Password**

```text
anonymous
```

---

# 📂 FTP Enumeration

List available files.

```bash
ls
```

Download the flag.

```bash
get flag.txt
```

Exit the FTP session.

```bash
bye
```

Display the flag.

```bash
cat flag.txt
```

---

# 📚 What I Learned

- Basic FTP Enumeration.
- Identifying FTP services with Nmap.
- Anonymous FTP authentication.
- Downloading files using FTP.
- Basic Linux file handling.

---

# 🔐 Key Takeaways

- FTP is commonly used for file transfer.
- Anonymous login can expose sensitive information if misconfigured.
- Enumeration is the key to discovering accessible services.
- Always verify whether anonymous authentication is enabled.

---

# 💡 Skills Gained

- Nmap
- FTP
- Enumeration
- Linux
- Service Identification
- File Transfer

---

# ✅ Machine Completed Successfully 🎉

---

## 👨‍💻 Author

**Sayed Samy Elbadry**

### 🚀 Web Penetration Testing & Red Team Journey

**Platform:** Hack The Box

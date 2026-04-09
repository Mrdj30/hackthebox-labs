<div align="center">

# 🟥 HackTheBox Academy — Module Writeups

**Hands-on offensive security research | Step-by-step solutions & walkthroughs**

[![Modules Completed](https://img.shields.io/badge/Modules%20Completed-1%2F5-red?style=for-the-badge&logo=hackthebox&logoColor=white)](./hackthebox-labs/)
[![Topics Solved](https://img.shields.io/badge/Topics%20Solved-7-brightgreen?style=for-the-badge)](./hackthebox-labs/web-fuzzing/)
[![Platform](https://img.shields.io/badge/Platform-HackTheBox%20Academy-9fef00?style=for-the-badge&logo=hackthebox&logoColor=black)](https://academy.hackthebox.com/)

*by [Mrdj30](https://github.com/Mrdj30) · Offensive security research & learning*

</div>

---

## 📖 About

This repository contains detailed writeups for [HackTheBox Academy](https://academy.hackthebox.com/) modules — with step-by-step solutions, command breakdowns, screenshots, and key takeaways for each topic.

Whether you're following along or reviewing techniques, these writeups aim to be clear, practical, and educational.

---

## 📊 Progress Overview

| Category | Topics Solved | Status |
|----------|--------------|--------|
| 🔍 Web Fuzzing | 7 / 7 | ✅ Complete |
| **Total** | **7** | **1 module done** |

---

## 📚 Module Index

### ✅ Completed Modules

| # | Module | Topics | Difficulty | Link |
|---|--------|--------|------------|------|
| 1 | 🔍 Web Fuzzing | 7 / 7 ✅ | 🟡 Medium | [View →](./hackthebox-labs/web-fuzzing/) |

### 🔜 Planned Modules

| # | Module | Difficulty | Status |
|---|--------|------------|--------|
| 2 | 🌐 SQL Injection Fundamentals | 🟢 Easy | Coming Soon |
| 3 | 🔐 Authentication Bypass | 🟡 Medium | Coming Soon |
| 4 | 📁 File Upload Vulnerabilities | 🟡 Medium | Coming Soon |
| 5 | 🔌 Command Injection | 🟠 Hard | Coming Soon |

---

## 🗺️ Learning Path

```
[Beginner]     → Web Fuzzing
                    ↓
               SQL Injection Fundamentals
                    ↓
[Intermediate] → Authentication Bypass
                    ↓
               File Upload Vulnerabilities
                    ↓
[Advanced]     → Command Injection
```

Each module builds on the previous one — start from the top and work your way down!

---

## 🛠️ Prerequisites

Before following along with these writeups, make sure you have:

- ✅ **HackTheBox Academy account** — [Sign up free](https://academy.hackthebox.com/)
- ✅ **Kali Linux** or similar offensive security OS (or use [HTB's Pwnbox](https://www.hackthebox.com/blog/introducing-pwnbox))
- ✅ Basic understanding of **HTTP / web protocols**
- ✅ Familiarity with the **Linux command line**

---

## 🔧 Tools Setup

### Install ffuf
```bash
sudo apt install ffuf
# or build from source
go install github.com/ffuf/ffuf/v2@latest
```

### Install Gobuster
```bash
sudo apt install gobuster
```

### Install Feroxbuster
```bash
# Download the latest release binary directly
curl -sLo feroxbuster https://github.com/epi052/feroxbuster/releases/latest/download/x86_64-linux-feroxbuster.zip
unzip x86_64-linux-feroxbuster.zip
chmod +x feroxbuster && sudo mv feroxbuster /usr/local/bin/
# or via cargo (if Rust is installed)
# cargo install feroxbuster
```

### Install SecLists (wordlists)
```bash
sudo apt install seclists
# or clone manually
git clone https://github.com/danielmiessler/SecLists /usr/share/seclists
```

---

## 🧭 How to Navigate

```
(repo root)/                             ← you are here
└── hackthebox-labs/
    └── web-fuzzing/
        ├── README.md                    ← module overview & topic list
        ├── 01-recursive-fuzzing/        ← topic folder
        │   ├── README.md                ← step-by-step solution
        │   └── screenshots/             ← supporting visuals
        ├── 02-parameter-value-fuzzing/
        └── ...
```

Each topic folder contains:
- 📄 **README.md** — Challenge description, steps, commands, and flag
- 📸 **screenshots/** — Visual proof for each step

---

## ⏱️ Estimated Completion Time

| Module | Est. Time |
|--------|-----------|
| 🔍 Web Fuzzing | 3–5 hours |

---

## 🤝 Connect

- 🐙 **GitHub**: [github.com/Mrdj30](https://github.com/Mrdj30)
- 🟥 **HackTheBox**: [app.hackthebox.com/profile/Mrdj30](https://app.hackthebox.com/profile/Mrdj30)

---

<div align="center">

*⭐ Star this repo if you find it useful — it helps others discover it!*

**[🔝 Back to Top](#)**

</div>

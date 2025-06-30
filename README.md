# 🔧 CryptoDai's Universal Bot Environment Setup (All Tech – Ubuntu + Termux)

This guide sets up **all dependencies** required to run any of your bots, including:
- 🐍 Python Bots
- ☕ Java Bots
- 🟨 JavaScript (Node.js) Bots
- 🧬 Git-based Bots
- ⚙️ Shell/Script-based Tools

Supports both **Ubuntu Desktop** and **Android Termux**.

---

## ⚙️ System Requirements

| Language / Tool | Needed For         | Version     |
|------------------|--------------------|--------------|
| Python           | Python bots        | 3.8+         |
| Java             | Java bots          | 17+          |
| Node.js + npm    | JavaScript bots    | 16+          |
| Git              | Repo management    | Latest       |
| Curl / Wget      | File fetching      | Built-in     |
| unzip / tar      | File extraction    | Built-in     |
| pip              | Python packages    | Latest       |
| Termux Extras    | Android CLI        | Updated      |

---

## 🖥️ Ubuntu Desktop Setup

### 1. Update System
```bash
sudo apt update && sudo apt upgrade
````

### 2. Install Git

```bash
sudo apt install git
```

### 3. Install Python + pip

```bash
sudo apt install python3 python3-pip
```

### 4. Install Java (OpenJDK 17+)

```bash
sudo apt install openjdk-21-jdk
```

### 5. Install Node.js + npm

```bash
sudo apt install nodejs npm
```
### 6. Install nano :
```bash
sudo apt update
sudo apt install nano
```

### 7. Optional: Curl, Wget, Unzip

```bash
sudo apt install curl wget unzip
```

---

## 📱 Termux (Android) Setup

### 1. Update Termux

```bash
pkg update && pkg upgrade
```

### 2. Install Git

```bash
pkg install git
```

### 3. Install Python + pip

```bash
pkg install python
pip install --upgrade pip
```

### 4. Install Java (OpenJDK 17)

```bash
pkg install openjdk-21
```

### 5. Install Node.js + npm

```bash
pkg install nodejs
```

### 6. Install nano in Termux or UserLAnd

For Termux:
```bash
pkg update
pkg install nano
```

### 7. Optional Tools

```bash
pkg install curl wget unzip
```

---

## 🔌 How to Run Any Bot

### ✅ Python Bot

```bash
pip install -r requirements.txt
python3 main.py
```

### ✅ Java Bot

```bash
javac MainBot.java
java MainBot
```

### ✅ JavaScript Bot

```bash
npm install
node index.js
```

---

## 📁 Required Files (For All Bots)

Each bot should include:

* `main.py`, `MainBot.java`, or `index.js`
* `requirements.txt` or `package.json`
* `accounts.txt` (multi-login)
* `.env` (credentials/config)
* `sessions/` folder (session cache)
* `README.md` (bot guide)

---

## 👨‍💻 Maintained by Mahesh

Part of the **YetiDAO Bot Suite**
Telegram: [@cryptodai3](https://t.me/cryptodai3)

---

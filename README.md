# Pear Trade Bot Scripts 🚀

This script automates daily check-in (streak claim) on **Pear Trade** — a Web3 rewards platform that uses Twitter OAuth via Privy for authentication.

🔗 Register: [Pear Trade](https://rewards.pear.trade/r/thog399)

---

## ✨ Features Overview

### General Features

- **Multi-Account Support**: Reads Twitter auth tokens from `tokenX.txt` to process multiple accounts in parallel.
- **Colorful CLI**: Uses `colorama` for visually appealing output with box-drawing borders and colored icons.
- **Asynchronous Execution**: Built with `asyncio` for efficient concurrent task processing (configurable thread count).
- **Error Handling**: Comprehensive error catching with retry logic (configurable attempts) for API failures.
- **Bilingual Support**: Supports both English and Vietnamese output.
- **Proxy Support**: Supports SOCKS5/HTTP proxies via `proxies.txt` (`host:port:user:pass` format).

---

### Included Scripts

✨ **Check-in Bot** (`checkin.py`)

- ✅ Automatic daily streak claim
- ✅ Twitter OAuth via Privy — full PKCE flow, no browser needed
- ✅ Pear Trade account sync & authentication
- ✅ Current streak & balance display
- ✅ Daily reward points tracking
- ✅ "Already claimed" detection
- ✅ Proxy & multi-threading support

---

## 🛠️ Prerequisites

Before running the scripts, ensure you have the following installed:

- **Python 3.8+**
- **pip** (Python package manager)
- **Dependencies**: Install via `pip install -r requirements.txt`
- **tokenX.txt**: Add Twitter `auth_token|ct0` pairs (one per line) — obtain from browser cookies after logging into x.com
- **proxies.txt** (optional): Add proxy addresses for network requests

---

## 📦 Installation

1. **Clone or download this repository:**
   ```sh
   git clone https://github.com/thog9/Pear-social.git
   cd Pear-social
   ```

2. **Install Dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

3. **Prepare Input Files:**

   Create `tokenX.txt` in the root directory with Twitter auth tokens (one per line):
   ```
   auth_token_value_1|ct0_value_1
   auth_token_value_2|ct0_value_2
   ```

   Create `proxies.txt` (optional) — one proxy per line:
   ```
   socks5://user:pass@host:port
   http://user:pass@host:port
   host:port:user:pass
   ```

4. **Run:**
   ```sh
   python main.py
   ```
   - Choose a language (Vietnamese / English).
   - Select the script you want to run.

**Language Selection:**
- Choose between Vietnamese (Tiếng Việt) and English.
- All scripts support bilingual output.

---

## 📁 Project Structure

```
Pear-social/
├── main.py             # Central menu system
├── tokenX.txt          # Twitter auth_token|ct0 (one per line)
├── proxies.txt         # Proxies (optional)
├── README.md          # This file
└── scripts/            # Individual scripts
    └── checkin.py      # Task Check-in automation bot

```

---

## 📨 Contact

- **Telegram**: [thog099](https://t.me/thog099)
- **Channel**: [CHANNEL](https://t.me/thogairdrops)
- **Group**: [GROUP CHAT](https://t.me/thogchats)
- **X**: [Thog](https://x.com/thog099)

---

## ☕ Support

Love these scripts? Fuel our work with a coffee!

🔗 BUYMECAFE: [BUY ME CAFE](https://buymecafe.vercel.app/)

🔗 WEBSITE: [BUY SCRIPTS](https://thogtoolhub.com/)

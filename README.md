# ⚡ Vontaroq Bot — Non-Custodial Grid Trading Bot

> **Automated cryptocurrency grid trading on your own exchange account.**

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![Python](https://img.shields.io/badge/Python-3.10%2B-green)
![License](https://img.shields.io/badge/License-Proprietary-red)
![Status](https://img.shields.io/badge/Status-Production%20Ready-brightgreen)

---

## 📖 What is Vontaroq Bot?

Vontaroq is a **non-custodial grid trading bot** that connects to YOUR exchange account via API keys. It places a grid of buy and sell orders to profit from market volatility — all without ever holding your funds.

### Key Features

- ✅ **Non-Custodial** — Your funds stay on YOUR exchange
- ✅ **Grid Trading** — Automated buy-low, sell-high strategy
- ✅ **Multiple Exchanges** — Binance, KuCoin, Kraken, Coinbase
- ✅ **Testnet Support** — Practice with fake money first
- ✅ **Stop-Loss Protection** — Automatic safety triggers
- ✅ **Trailing Stop** — Locks in profits as price rises
- ✅ **Auto-Stop Timer** — Set trading duration (15min - 24hrs)
- ✅ **Session Tracking** — Every trade logged to Supabase
- ✅ **Payment Wall** — Subscription-based access
- ✅ **Security Questions** — 2-factor authentication
- ✅ **Ed25519 Signed** — Code verified before execution

---

## 🚀 Quick Start

### Prerequisites

- Python 3.10+
- A crypto exchange account (Binance recommended)
- Internet connection

### Installation

```bash
# 1. Clone/download this repository
# 2. Install dependencies
pip install requests cryptography streamlit

# 3. Run the bot
python main.py

Login
Choose 1 to Login (or 2 to Create Account)

Enter your username and password

The dashboard opens in your browser

Add your exchange API keys
Start trading!

```

*🔒 Security*

Layer	Protection
API Keys	Fernet AES-128 encrypted
Passwords	HMAC-SHA256 hashed
Code	Ed25519 signed
Tokens	JWT with expiry
Withdrawals	NEVER enabled on API keys
Storage	Supabase with RLS

*⚠️ IMPORTANT*

NEVER enable withdrawal permissions on your API key

Only enable Spot Trading permission

Use Testnet first to practice

Start with small amounts

*🛠️ Tech Stack*

Component	Technology
Backend	Cloudflare Workers
Database	Supabase (PostgreSQL)
Storage	Cloudflare R2
Exchange	CCXT
UI	Streamlit
Auth	Custom JWT + Security Questions

*❓ FAQ*

Q: Do you hold my funds?
A: No. The bot uses YOUR exchange API keys. Funds never leave your exchange account.

Q: Can I lose money?
A: Yes. Grid trading can lose money in trending markets. Always use stop-loss.

Q: Which exchanges are supported?
A: Binance, KuCoin, Kraken, Coinbase (via CCXT).

Q: Is Testnet available?
A: Yes! Binance Testnet is fully supported for practice.

*📞 Support*

Phone: +250 795065789 / +250 794115295

*⚖️ Disclaimer*

Trading cryptocurrency involves significant risk of loss. Past performance does not guarantee future results. This software is provided "as is" without warranty.

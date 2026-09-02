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

# 💸 unMineable Mining Guide 🚀

## 🔍 Overview

**unMineable** is a user-friendly platform that allows you to **mine your favorite non-mineable coins** (like 🐶 SHIB, 🐕 DOGE, 🧬 VET and more) using your **CPU or GPU** through popular mining algorithms such as Ethash, Etchash, KawPow, and RandomX.

This guide will help you set up and start mining in just a few minutes! ⛏️

---

## ✨ Features

✅ Mine popular tokens that aren’t usually mineable  
✅ Supports CPU & GPU mining 💻⚙️  
✅ Auto payouts to your crypto wallet 💰  
✅ Bonus referral system for reduced fees 🎁  

---

## 🧰 Requirements

🔧 A PC with a compatible CPU or GPU  
🔧 Mining software (PhoenixMiner, XMRig, T-Rex, etc.)  
🔧 Your crypto wallet address  

---

## 🚀 Getting Started

### 1️⃣ Choose Your Coin

Go to 👉 [https://unmineable.com](https://unmineable.com) and pick the coin you want to mine.

---

### 2️⃣ Download Mining Software

Depending on the algorithm for your hardware:

- 💎 **Ethash / Etchash (GPU)**: PhoenixMiner / NBMiner  
- 🔥 **KawPow (GPU)**: T-Rex Miner  
- 🧠 **RandomX (CPU)**: XMRig  

> ⚠️ **Always download miners from official or trusted sources** to stay safe!

---

### 3️⃣ Configure the Miner

Edit the `.bat` or `.json` file with your details.

#### 💻 Example: PhoenixMiner (Ethash GPU)

```bash
PhoenixMiner.exe -pool ethash.unmineable.com:3333 -wal COIN:YOUR_ADDRESS.WORKER_NAME#REFCODE -pass x

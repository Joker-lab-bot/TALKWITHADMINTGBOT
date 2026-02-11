# 🤖 Talk to Admin Telegram Bot

A powerful **Telegram support bot** that allows users to communicate directly with admins.

---

## ✨ Features

- User → Admin messaging
- Admin replies with inline buttons
- User block / unblock system
- Broadcast messages
- Anti-spam rate limiting
- MongoDB message logging
- Dynamic admin management
- Single-file bot (easy deploy)

---

## 🛠 Tech Stack

- Python 3.10+
- python-telegram-bot v20
- MongoDB (Motor async driver)
- Railway / VPS compatible

---

## 🚀 Deployment

### 🔹 Railway (Recommended)

1. Fork or upload this repo to GitHub
2. Create a **Railway Project**
3. Add **MongoDB plugin**
4. Add Environment Variables: BOT_TOKEN=xxxx
ADMIN_IDS=12345,67890
MONGO_URL=railway_mongo_url
DB_NAME=telegram_bot
6. 

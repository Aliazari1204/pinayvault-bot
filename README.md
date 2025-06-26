# PinayVault Telegram Bot

## Overview
A “Share to Unlock” Telegram bot. Users must share the bot to unlock access to your vault.

## How to Deploy (Railway)

1. **Click “Deploy to Railway”**  
[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template?template=https://github.com/YOUR_GITHUB_REPO_HERE)

2. **Set Environment Variable**  
- `TOKEN` – 7705698862:AAF5-r4k-VnUmTjNTukCp8tYRGzGZxPhcQo

3. **Start Deployment**  
- Railway will auto-install requirements and start the bot.

4. **Monitoring**  
- Use the Railway dashboard to view logs and status.

## To Run Locally

```bash
pip install -r requirements.txt
python bot/main.py
```

---

**Note:**  
For demo, the “unlock” just saves status in memory. For real usage, you should connect a database (Redis, SQLite, etc.) to track users.  
**Sharing verification** is not fully automatic (Telegram API limits this); users still need to click “I’ve Shared!” after sharing.

---

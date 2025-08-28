# 🚀 Hyper Invite Bot  

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/)  
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)  
[![Status](https://img.shields.io/badge/Status-Active-success.svg)]()  

Hyper Invite Bot is an automation tool for **Clubhouse rooms** that handles **invites, welcome messages, moderation, and audience insights** — keeping your sessions fully managed without manual effort.  

---

## ✨ Features  
- 🎯 **Auto-invite** new users when they join the room  
- 💬 Sends **welcome messages** (only once per user)  
- 🤖 **Helper bots** join when the main bot fails  
- 🔄 Auto-refresh **audience count** (speakers, members, followers, others)  
- 🎙️ Moderator controls via chat commands (`/mute`, `/unmute`)  
- 📝 Dynamic room title updates with **live member stats**  
- 🛡️ Fail-safe: helper bots exit gracefully when not needed  

---

## ⚙️ Requirements  

- Python **3.9+**  
- `requests` library  
- Clubhouse **API Token**  
- Channel ID / Room Link  

Install dependencies:  
```bash
pip install requests

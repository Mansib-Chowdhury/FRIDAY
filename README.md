# 🤖 FRIDAY – A Feature-Rich, Chaotic Discord Bot

**FRIDAY** is a powerful, imperfect, and highly customizable Discord bot created by a much younger version of myself — originally built for a now-defunct server where it once **boosted engagement**, **moderated chats**, and sparked **laughter and learning**.

Though the server is gone, **this code stands as a memory** of how far I’ve come — a blend of creativity, chaos, and curiosity about **Python**, **Discord API**, and **automation**.

---

## 🌟 What Makes FRIDAY Special?

🧠 **Custom Role System (JSON-Based)**
- Users unlock **exclusive, shareable roles** after reaching a minimum Mee6 level
- Level is verified by uploading a screenshot → AI reads the Mee6 leaderboard using **Azure Image AI**
- All roles are stored in a custom **JSON database**
- Roles can include **custom HEX colors**, fully user-defined!

🐳 **Docker-Deployable**
- Fully deployable via **Docker** for ease of testing or production-like environments
- Great for reproducible setups and experimenting

💡 **Learning-Oriented Design**
- Built entirely to learn `discord.py`, APIs, and real bot deployment personally
- Some commands are silly, outdated, or inefficient — left in intentionally to reflect the learning process


---

## ⚙️ Core Features

### 👥 Moderation & Server Utilities
- 🔨 Add / Remove Roles
- ⛔ Timeout Users
- 🧹 Purge Messages
- 📬 ModMail: DMing the bot creates a support channel *(requires server/category IDs)*
- 🕵️ **Snipe**: Recover deleted/edited messages (stored in dictionary cache)
- 🔧 Live Load/Unload of Cogs
- 🖼️ Avatar command
- 📶 Ping checker to diagnose lag

### 🔓 Custom Role & Reward System
- 🎖️ Unlock shareable roles upon meeting Mee6 level requirement
- 🧠 Verified using Azure Image Check AI (for screenshot validation)
- 📄 Roles saved in JSON — simple, fast, and flexible
- 🎨 Custom Color Roles (users can claim any HEX color role)

### 🎮 Fun & Entertainment
- ✂️ Rock Paper Scissors
- 🥴 `,drunkify` – Makes messages sOuNd lIKe tHiS
- 💌 Mod-only DM spam (for harmless chaos)
- 🎭 Reddit scraper for memes and pictures
- 🤗 `,hug` and other friendly commands
- 🧮 Calculator command

### 🔍 Info & Utility
- 🌐 Wikipedia search
- 🖼️ Image scraper
- 💻 Server health checks
- 🎥 Custom streaming status (with editable link)
- 📚 Help command for listing commands and modules
- 🎵 Music playback using `youtube-dl` *(currently broken)*

---

## 🧪 Tech Stack

- 🐍 Python (`discord.py`)
- 📄 JSON (used as a lightweight database)
- 🗃️ Dictionary-based memory cache
- 🧠 Azure AI (OCR for image-based role validation)
- 🐳 Docker (for deployment)

---

## 📝 Setup Notes

- Some features like ModMail, Role Rewards, and Logs require:
  - ✅ Hardcoded **Server IDs**
  - 📁 A valid in server **Category ID** for ModMail
  - More requirements that can be found through checks of error handling 
- **Mee6 level detection** uses image uploads that must clearly show level (bot reads using Azure AI which requires api key creation for authentication)
- Many features are **experimental** and **not optimized** — they reflect hands-on learning
- The bot prefix is **`,`** (comma), and a `,help` command is included
- some apis now might require new keys in the place of old, unusable test keys
- Some commands were added “just for fun” and weren’t cleaned up 😅

---

## 💭 Why This Project Matters

This bot was originally made for a Discord server with more than 1500 people that no longer exists. It served:
- As a **learning ground** for Python and bots
- A **fun playground** for experimenting with APIs and role systems
- A **real tool** for moderation and engagement that was genuinely used by real people

Though imperfect, these files stand as:
- 🧠 A reflection of creative problem solving
- 💪 A testament to progress in logic and backend skills
- 🌱 A stepping stone in becoming a full-stack and AI-focused developer

---

## 🚀 Future Use Cases & Showcase Value

If you're viewing this as part of a portfolio or GitHub exploration:

- It showcases ability to work with:
  - Asynchronous Python
  - External APIs and AI models
  - Discord event-based architecture
  - Docker deployment
  - Role & permission systems
  - JSON/Dict-based lightweight databases
- Demonstrates a curious, self-taught, hands-on approach to real-world programming
- Has potential to be rebuilt into a **production-grade** bot if refined

---

## 🙌 Credits

Made with 💙 by **Mansib (Rexy)**  
For the laughs, the learning, and the memory of a Discord server that once was.

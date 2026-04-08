<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&duration=3000&pause=1000&color=25D366&center=true&vCenter=true&width=600&lines=Firekid+Dex+V1+%F0%9F%94%A5;WhatsApp+Bot+%E2%80%A2+Powered+by+Baileys;Deploy+in+Minutes" alt="Typing SVG" />

<br/>

![Version](https://img.shields.io/badge/version-1.0.0-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)
![Platform](https://img.shields.io/badge/platform-WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)
![Node](https://img.shields.io/badge/node-%3E%3D18-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-orange?style=for-the-badge)

<br/>

> ⚡ A powerful, self-hostable WhatsApp bot built on Baileys — deploy to Render in minutes, no technical experience needed.

</div>

---

## 🚀 Quick Deploy Guide

Follow these **4 simple steps** to get your bot live:

```
STEP 1 → Fork this repo
STEP 2 → Create a Render account
STEP 3 → Download & fill .env
STEP 4 → Deploy & pair your WhatsApp
```

---

## 📋 Step 1 — Fork This Repository

Click the button below to fork this repo to your GitHub account:

<div align="center">

[![Fork Repo](https://img.shields.io/badge/🍴%20Fork%20This%20Repo-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Firekid-is-him/Firekid-Dex-V1/fork)

</div>

> **Don't have a GitHub account?** [Create one free here](https://github.com/signup) — it takes 60 seconds.

After forking, you'll have your own copy of the bot at:
```
https://github.com/YOUR_USERNAME/Firekid-Dex-V1
```

---

## 🌐 Step 2 — Create a Render Account & Deploy

Render is a free cloud platform where your bot will run 24/7.

<div align="center">

[![Deploy to Render](https://img.shields.io/badge/🚀%20Go%20to%20Render-46E3B7?style=for-the-badge&logo=render&logoColor=white)](https://render.com)

</div>

**Once on Render:**

1. Click **"Get Started for Free"** and sign up
2. Click **"Connect GitHub"** to link your GitHub account
   - Or paste your forked repo URL manually:
     ```
     https://github.com/YOUR_USERNAME/Firekid-Dex-V1
     ```
3. Select **"New Web Service"**
4. Choose your forked `Firekid-Dex-V1` repo
5. Leave the default settings (Render auto-detects Node.js)
6. **Don't deploy yet** — you need your `.env` values first ⬇️

---

## ⚙️ Step 3 — Configure Your Environment

### 3a. Download the Example Environment File

<div align="center">

[![Download .env.example](https://img.shields.io/badge/⬇️%20Download%20.env.example-FF6B6B?style=for-the-badge&logo=dotenv&logoColor=white)](https://github.com/Firekid-is-him/Firekid-Dex-V1/raw/main/.env.example)

</div>

Open the file — it looks something like this:

```env
FIREKID_KEY=your_firekid_key_here
SESSION_ID=your_session_id_here
BOT_NAME=Firekid Dex
PREFIX=.
OWNER_NUMBER=2348XXXXXXXXX
```

---

### 3b. Get Your Firekid API Key

Visit the official Firekid website to get your key:

<div align="center">

[![Get Firekid Key](https://img.shields.io/badge/🔑%20firekidofficial.name.ng-FF6600?style=for-the-badge)](https://firekidofficial.name.ng)

</div>

1. Go to [https://firekidofficial.name.ng](https://firekidofficial.name.ng)
2. Create an account or log in
3. Navigate to **Dashboard → API Key**
4. Copy your `FIREKID_KEY` and paste it into your `.env` file

---

### 3c. Get Your WhatsApp Session ID

Your Session ID is how the bot connects to your WhatsApp number.

<div align="center">

[![Get Session ID](https://img.shields.io/badge/📱%20Get%20Session%20ID-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://firekidofficial.name.ng)

</div>

1. Go to [https://firekidofficial.name.ng](https://firekidofficial.name.ng)
2. Log in to your account
3. Click **"Pair Bot"** or **"Get Session ID"**
4. Scan the QR code with your WhatsApp  
   *(WhatsApp → Linked Devices → Link a Device)*
5. Your `SESSION_ID` will be generated — copy it

> ⚠️ **Keep your Session ID private.** Anyone with it can control your bot.

---

## 🏁 Step 4 — Add ENV to Render & Deploy

Back on Render:

1. Go to your Web Service → **"Environment"** tab
2. Click **"Add Environment Variable"**
3. Add all variables from your `.env` file one by one:

| Key | Value |
|-----|-------|
| `FIREKID_KEY` | *Your key from firekidofficial.name.ng* |
| `SESSION_ID` | *Your session ID from firekidofficial.name.ng* |
| `BOT_NAME` | `Firekid Dex` *(or your custom name)* |
| `PREFIX` | `.` |
| `OWNER_NUMBER` | *Your number with country code, e.g. `2348012345678`* |

4. Click **"Save Changes"**
5. Click **"Deploy"** 🚀

Render will build and start your bot. Once it says **"Live"** — your bot is online!

---

## ✅ Verify It's Working

Send this message to your bot on WhatsApp:

```
.menu
```

If the bot replies — **you're live!** 🎉

---

## 🆘 Troubleshooting

| Problem | Fix |
|--------|-----|
| Bot not responding | Check that `SESSION_ID` is set correctly in Render |
| Session expired | Re-pair on [firekidofficial.name.ng](https://firekidofficial.name.ng) and update `SESSION_ID` |
| Render build failing | Make sure you forked the repo correctly and Render is connected to GitHub |
| Invalid Firekid Key | Double-check the key copied from your dashboard |

---

## 🔗 Important Links

| Resource | Link |
|----------|------|
| 🍴 Fork Repo | [github.com/Firekid-is-him/Firekid-Dex-V1/fork](https://github.com/Firekid-is-him/Firekid-Dex-V1/fork) |
| 🌐 Deploy Platform | [render.com](https://render.com) |
| 🔑 Firekid Website | [firekidofficial.name.ng](https://firekidofficial.name.ng) |
| 📦 Source Repo | [github.com/Firekid-is-him/Firekid-Dex-V1](https://github.com/Firekid-is-him/Firekid-Dex-V1) |

---

<div align="center">

Made with ❤️ by **Firekid**

[![Website](https://img.shields.io/badge/🌍%20firekidofficial.name.ng-FF6600?style=for-the-badge)](https://firekidofficial.name.ng)
[![GitHub](https://img.shields.io/badge/GitHub-Firekid--is--him-181717?style=for-the-badge&logo=github)](https://github.com/Firekid-is-him)

*Star ⭐ the repo if this helped you!*

</div>

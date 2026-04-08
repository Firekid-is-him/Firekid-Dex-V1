<div align="center">

<img src="https://i.ibb.co/hJhwwGT0/d2d13a1b-7457-4bbc-9f7b-be32083723ba.jpg" alt="Firekid Dex V1" width="100%" />

<br/><br/>

![Version](https://img.shields.io/badge/version-1.0.0-25D366?style=for-the-badge)
![Platform](https://img.shields.io/badge/WhatsApp-Bot-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)
![Node](https://img.shields.io/badge/Node.js-%3E%3D18-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-orange?style=for-the-badge)

<br/>

A powerful, self-hostable WhatsApp bot built on Baileys.<br/>
Deploy to Render in minutes — no technical experience needed.

<br/>

[![Fork on GitHub](https://img.shields.io/badge/Fork_This_Repo-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Firekid-is-him/Firekid-Dex-V1/fork)
&nbsp;
[![Join Support Group](https://img.shields.io/badge/WhatsApp_Support-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://chat.whatsapp.com/JGI7jOeklfB26dCYeYRr7E?mode=hqctcla)

</div>

---

## Deploy in 4 Steps

```
Step 1  →  Fork this repository
Step 2  →  Create a Render account and connect GitHub
Step 3  →  Get your Session ID and Firekid Key
Step 4  →  Add environment variables and deploy
```

---

## Step 1 — Fork This Repository

Click the button below to fork this repo to your GitHub account.

<div align="center">

[![Fork on GitHub](https://img.shields.io/badge/Fork_This_Repo-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Firekid-is-him/Firekid-Dex-V1/fork)

</div>

Don't have a GitHub account? [Create one free here.](https://github.com/signup)

After forking, your copy will be at:

```
https://github.com/YOUR_USERNAME/Firekid-Dex-V1
```

---

## Step 2 — Create a Render Account

Render is the free cloud platform where your bot will run.

<div align="center">

[![Go to Render](https://img.shields.io/badge/Go_to_Render-46E3B7?style=for-the-badge&logo=render&logoColor=white)](https://render.com)

</div>

1. Sign up at [render.com](https://render.com)
2. Click **New** → **Web Service**
3. Connect your GitHub account and select your forked `Firekid-Dex-V1` repo
   - Or paste your fork URL directly:
     ```
     https://github.com/YOUR_USERNAME/Firekid-Dex-V1
     ```
4. Leave all build settings as default — Render detects Node.js automatically
5. **Do not deploy yet.** Complete Step 3 first.

---

## Step 3 — Get Your Credentials

You need two things: a **Firekid Key** and a **Session ID**. Both come from the Firekid website.

<div align="center">

[![Firekid Website](https://img.shields.io/badge/firekidofficial.name.ng-FF6600?style=for-the-badge&logo=firefoxbrowser&logoColor=white)](https://firekidofficial.name.ng)

</div>

**Get your Firekid Key:**

1. Visit [firekidofficial.name.ng](https://firekidofficial.name.ng) and log in or create an account
2. Go to your **Dashboard**
3. Copy your API key — it starts with `fk_`

**Get your Session ID:**

1. On the same site, click **Pair Bot** or **Get Session ID**
2. Scan the QR code with WhatsApp:
   - Open WhatsApp → **Linked Devices** → **Link a Device**
3. Your Session ID will be generated — copy it (starts with `firekidxmd_`)

> Keep your Session ID private. Anyone with it can control your bot.

---

## Step 4 — Configure and Deploy

### Download the environment file

<div align="center">

[![Download .env.example](https://img.shields.io/badge/Download_.env.example-FF6B6B?style=for-the-badge&logo=dotenv&logoColor=white)](https://github.com/Firekid-is-him/Firekid-Dex-V1/raw/main/.env.example)

</div>

### Add your variables to Render

Go to your Web Service → **Environment** tab → **Add Environment Variable** and fill in the following:

| Variable | Value |
|---|---|
| `SESSION_ID` | Your session ID — starts with `firekidxmd_` |
| `OWNER_NUMBER` | Your number with country code, e.g. `2348012345678` |
| `BOT_MODE` | `prod` |
| `RENDER_EXTERNAL_URL` | Your Render app URL, e.g. `https://your-bot.onrender.com` |
| `PORT` | `3000` |
| `FIREKID_KEY` | Your API key — starts with `fk_` |

Click **Save Changes**, then click **Deploy**.

Once Render shows **Live** — your bot is online.

---

## Verify It's Working

Send any command to your bot on WhatsApp. If it replies, you're live.

Need help? Join the support group:

<div align="center">

[![Join Support Group](https://img.shields.io/badge/Join_Support_Group-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://chat.whatsapp.com/JGI7jOeklfB26dCYeYRr7E?mode=hqctcla)

</div>

---

## Troubleshooting

| Problem | Fix |
|---|---|
| Bot not responding | Confirm `SESSION_ID` is correctly set in Render environment |
| Session expired | Re-pair on firekidofficial.name.ng and update `SESSION_ID` in Render |
| Render build failing | Make sure your fork is properly connected to Render |
| Invalid Firekid Key | Re-copy the key from your dashboard — it must start with `fk_` |
| Wrong owner number | Use full international format with no `+`, e.g. `2348012345678` |

---

## Important Links

| Resource | Link |
|---|---|
| Fork Repo | [github.com/Firekid-is-him/Firekid-Dex-V1/fork](https://github.com/Firekid-is-him/Firekid-Dex-V1/fork) |
| Render | [render.com](https://render.com) |
| Firekid Website | [firekidofficial.name.ng](https://firekidofficial.name.ng) |
| Support Group | [Join on WhatsApp](https://chat.whatsapp.com/JGI7jOeklfB26dCYeYRr7E?mode=hqctcla) |

---

<div align="center">

Made by **Firekid**

[![Website](https://img.shields.io/badge/firekidofficial.name.ng-FF6600?style=for-the-badge&logo=firefoxbrowser&logoColor=white)](https://firekidofficial.name.ng)
&nbsp;
[![GitHub](https://img.shields.io/badge/Firekid--is--him-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Firekid-is-him)

If this helped you, drop a star on the repo.

</div>

# Firekid-Dex-V1

A WhatsApp bot application built with Node.js and the Baileys library.

## ✨ Features

- **WhatsApp Integration**: Connects to WhatsApp using `@whiskeysockets/baileys`.
- **Bot Operations**: Supports various automated bot interactions (specific functionality is managed internally).
- **Session Management**: Maintains connection state and handles reconnections automatically.

## 🛠️ Tech Stack

This project is built using:
- **Node.js**
- **@whiskeysockets/baileys** (WhatsApp Web API wrapper)
- **Express** (HTTP server for health checks/status)
- **node-cache** (In-memory caching)
- **pino** (Logging)
- Media processing tools: **canvas**, **sharp**, **@ffmpeg-installer/ffmpeg**, **node-shazam**

## 📁 Project Structure

```text
Firekid-Dex-V1/
├── src/
│   ├── lib/
│   └── index.js
├── .env.example
├── package.json
└── README.md
```

## 🚀 Getting Started

### Prerequisites

- Node.js installed
- A WhatsApp account for the bot

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Abdurrahman-Sudais/Firekid-Dex-V1.git
   cd Firekid-Dex-V1
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

## ⚙️ Configuration

The application requires environment variables. Copy `.env.example` to `.env` and configure the values:

```bash
cp .env.example .env
```

Example configuration (`.env.example`):
```env
SESSION_ID=firekidxmd_xxxxxxxxxxxx
OWNER_NUMBER=2348012345678
PREFIX=.
BOT_MODE=prod
RENDER_EXTERNAL_URL=https://your-bot.onrender.com
PORT=3000
```

> **Important:** Never commit your actual `.env` file containing sensitive tokens or session IDs to version control.

## ▶️ Usage

Start the bot:
```bash
npm start
```

For development mode (with watch support):
```bash
npm run dev
```

## 👨🏽‍💻 Author

**Abdurrahman Sudais**

- GitHub: [https://github.com/Abdurrahman-Sudais](https://github.com/Abdurrahman-Sudais)
- Portfolio: [https://call-him-sudais.vercel.app](https://call-him-sudais.vercel.app)

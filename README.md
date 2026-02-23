# 🚀 Discord.js v14 Command Handler Template

A professional, modular, and scalable command handler template for Discord bots using **discord.js v14**. This boilerplate is designed to help developers jumpstart their bot development with a clean architecture.

## ✨ Features
- **Modular Commands:** Easily add new commands by creating separate files in the `/commands` directory.
- **Dynamic Event Handling:** Automatically loads events from the `/events` folder.
- **Alias Support:** Supports multiple keywords for a single command.
- **24/7 Uptime:** Includes a built-in Express server to keep your bot alive on hosting services like Replit.
- **Modern Standards:** Fully compatible with Discord.js v14 features like `EmbedBuilder`.

## 🛠️ Tech Stack
- **Runtime:** [Node.js](https://nodejs.org/)
- **Library:** [discord.js v14](https://discord.js.org/)
- **Utility:** Express (for Keep-Alive)

## 📂 Project Structure
```text
├── commands/       # Direct command logic
│   └── example.js
├── events/         # Discord event listeners
│   ├── ready.js    # Bot initialization & command registration
│   └── message.js  # Message-based command handler
├── config.js       # Bot configuration (Token, Prefix)
├── index.js        # Entry point
└── package.json    # Dependencies
```

## ⚙️ Installation
1. Clone the repository: `git clone https://github.com/umutxyp/discordJS-V14.git`
2. Install dependencies: `npm install`
3. Configure `config.js` with your bot token and prefix.
4. Run the bot: `node index.js`

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=30&duration=3000&pause=500&color=FF1493&center=true&vCenter=true&width=500&lines=Aeva+Music+Bot;Premium+Audio+Experience;Next‑Gen+Discord+Music" alt="Typing SVG" />
  <br><br>
  <img src="https://via.placeholder.com/900x250/1a1a2e/FF1493?text=AEVA+MUSIC" alt="Aeva Hero Banner" style="border-radius: 20px; box-shadow: 0 0 20px #FF1493;">
  <br><br>
  <p>
    <a href="https://discord.gg/yourserver"><img src="https://img.shields.io/badge/Discord-Support-5865F2?style=for-the-badge&logo=discord&logoColor=white&color=FF1493&labelColor=1a1a2e"></a>
    <a href="https://github.com/DevSkyros/Aeva-Music"><img src="https://img.shields.io/badge/GitHub-Repo-181717?style=for-the-badge&logo=github&logoColor=white&color=FF1493&labelColor=1a1a2e"></a>
    <img src="https://img.shields.io/badge/Node.js-23%2B-339933?style=for-the-badge&logo=nodedotjs&logoColor=white&color=FF1493&labelColor=1a1a2e">
    <img src="https://img.shields.io/badge/Lavalink-Powered-FF1493?style=for-the-badge&logo=discord&logoColor=white&labelColor=1a1a2e">
  </p>
  <p>
    <img src="https://img.shields.io/github/stars/DevSkyros/Aeva-Music?style=flat-square&color=FF1493&labelColor=1a1a2e&logo=github">
    <img src="https://img.shields.io/github/forks/DevSkyros/Aeva-Music?style=flat-square&color=FF1493&labelColor=1a1a2e&logo=github">
    <img src="https://img.shields.io/github/issues/DevSkyros/Aeva-Music?style=flat-square&color=FF1493&labelColor=1a1a2e&logo=github">
  </p>
</div>

---

## ✨ The Ultimate Music Experience

> **Aeva** isn’t just a music bot – it’s a high‑fidelity audio system for Discord.  
> Designed with a **sleek dark interface**, **millisecond response times**, and **professional‑grade audio filters**.

<div align="center">
  <table>
    <tr>
      <td align="center">🎵 <b>Crystal Clear</b><br>Lavalink streaming</td>
      <td align="center">⚡ <b>Lightning Fast</b><br>Instant slash commands</td>
      <td align="center">🎨 <b>Premium UI</b><br>Glassmorphic embeds</td>
    </tr>
    <tr>
      <td align="center">🎛️ <b>10+ Filters</b><br>Bassboost, 8D, Nightcore</td>
      <td align="center">📂 <b>Multi‑Source</b><br>YouTube, Spotify, SC</td>
      <td align="center">🔄 <b>Smart Queue</b><br>Loop, autoplay, volume</td>
    </tr>
  </table>
</div>

---

## 🚀 Key Features

| Category | Features |
|----------|----------|
| **Audio Quality** | 192kbps+ streaming, equalizer presets, smooth crossfading |
| **Playback Control** | Play, Skip, Pause, Resume, Stop, Loop, Autoplay, Queue, Volume |
| **Filters** | Bassboost, 8D, Vibrato, Nightcore, Vaporwave, Tremolo, Gate |
| **UI/UX** | Now Playing embed with buttons, filter selection menu, rich queue display |
| **Sources** | YouTube, Spotify playlists/tracks, SoundCloud, Twitch, Bandcamp |
| **Stability** | Auto‑reconnect, error handling, MongoDB persistence, 99.9% uptime |

---

## 🎮 Command Reference

```yaml
🎵 Music Commands:
  /play <query>      - Play a song, playlist, or URL
  /skip              - Skip the current track
  /pause             - Pause the music
  /resume            - Resume playback
  /stop              - Stop music and clear queue
  /queue             - View the song queue
  /nowplaying        - Show currently playing track
  /loop              - Toggle loop mode (track/queue/off)
  /volume <1-100>    - Adjust volume
  /filters           - Open the audio effects panel
  /autoplay          - Toggle automatic song recommendations
  /lyrics            - Fetch lyrics for current song

ℹ️ Info Commands:
  /help              - Display interactive help menu
  /about             - Bot information and credits
```

---

🛠️ Installation (Self‑Hosting)

🔧 Requirements

· Node.js v23+ (v20+ works too)
· Lavalink server (v4+ recommended)
· MongoDB (local or Atlas)
· Discord Application with Bot token

📥 Setup

```bash
# 1. Clone the repository
git clone https://github.com/DevSkyros/Aeva-Music.git
cd Aeva-Music

# 2. Install dependencies
npm install

# 3. Create .env file
cat > .env << EOF
TOKEN=your_discord_bot_token
MONGODB_URI=mongodb+srv://user:pass@cluster.mongodb.net/aeva
SPOTIFY_CLIENT_ID=your_spotify_id
SPOTIFY_CLIENT_SECRET=your_spotify_secret
EOF

# 4. Configure Lavalink (edit src/config.js or config.js)
#    Set your node host, port, password

# 5. Start the bot
npm start
```

💡 Tip: Use PM2 for 24/7 hosting: pm2 start src/index.js --name aeva

---

🧰 Tech Stack

<div align="center">
  <img src="https://img.shields.io/badge/Discord.js-v14.14.1-5865F2?style=flat-square&logo=discord&logoColor=white&color=FF1493&labelColor=1a1a2e">
  <img src="https://img.shields.io/badge/Erela.js-v2.3.3-FF1493?style=flat-square&logo=javascript&logoColor=white&labelColor=1a1a2e">
  <img src="https://img.shields.io/badge/MongoDB-Atlas-47A248?style=flat-square&logo=mongodb&logoColor=white&color=FF1493&labelColor=1a1a2e">
  <img src="https://img.shields.io/badge/Lavalink-v4-FF1493?style=flat-square&logo=java&logoColor=white&labelColor=1a1a2e">
</div>

---

📜 License & Credit Protection

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=FF1493&height=120&section=header&text=License%20%26%20Credits&fontSize=25&fontColor=ffffff&animation=fadeIn" width="100%">
</div>

This project is protected under a Custom Credit Protection License – a binding legal notice that safeguards the intellectual property and recognition of the original developer.

🔐 Ownership & Attribution

· All code, assets, design, and branding are the exclusive property of KingX Development.
· The name “Aeva”, the bot’s avatar, banner, and embed designs are original creations and may not be copied or imitated.

❌ Strictly Prohibited Actions

The following actions are expressly forbidden without prior written permission from KingX Development:

# Prohibited Action
1 Removing, altering, or obscuring any credit text (e.g., “Developed by KingX Development”, “Created with ❤️ by KingX”) from any embed, menu, banner, command output, or the bot’s status.
2 Removing or modifying the license header from source code files.
3 Claiming ownership or authorship of the bot, its code, or any derivative work.
4 Selling, renting, sublicensing, or commercially exploiting the bot or its code.
5 Redistributing the bot or any modified version without the original credit text intact.
6 Using the bot’s name, logo, or artwork for any other project without permission.
7 Removing the “© 2026 Aeva Music Project • Created by KingX Development” footer from any help menu or about command.

✅ Permitted Actions

· You may self‑host the bot for personal or server use.
· You may modify the code for internal improvements, as long as all credits remain in place.
· You may contribute to the project via pull requests (with credit given).

⚖️ Legal Enforcement

Violation of any term of this license will result in:

· Immediate DMCA takedown requests to hosting platforms (GitHub, Replit, Glitch, etc.).
· Public blacklisting of your server/bot instance from official support channels.
· Potential legal action for damages if commercial exploitation is involved.

📄 Full License Text (Abridged)

Copyright © 2026 KingX Development. All rights reserved.

Permission is granted to use, copy, modify, and distribute this software only if the original copyright notice, this permission notice, and the credit “Developed by KingX Development” are retained in all copies or substantial portions of the software.

The software is provided “as is”, without warranty of any kind. In no event shall the authors be liable for any claim, damages, or other liability.

Commercial use, removal of credits, or redistribution without attribution is strictly prohibited.

---

🙏 Credits

<div align="center">
  <img src="https://via.placeholder.com/800x100/FF1493/ffffff?text=Developed+with+%E2%9D%A4%EF%B8%8F+by+KingX+Development" alt="Credit Banner" width="800">
</div>

· Lead Developer: KingX Development
· Music Engine: Lavalink & Erela.js
· UI Inspiration: Modern glassmorphism design trends
· Special Thanks: Discord.js community, Lavalink contributors, and all users who support Aeva.

© 2026 Aeva Music Project – Created with passion, precision, and pride.

---

<div align="center">
  <sub>✨ Made with TypeScript, Discord.js, and pure passion ✨</sub>
  <br>
  <sub>⚡ [Report Issue](https://github.com/DevSkyros/Aeva-Music/issues) • [Join Discord](https://discord.gg/yourserver) • [Star on GitHub](https://github.com/DevSkyros/Aeva-Music) ⚡</sub>
  <br><br>
  <img src="https://capsule-render.vercel.app/api?type=waving&color=FF1493&height=80&section=footer" width="100%">
</div>
```

---

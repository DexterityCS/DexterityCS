<div align="center">

```
██████╗ ███████╗██╗  ██╗████████╗███████╗██████╗ ██╗████████╗██╗   ██╗
██╔══██╗██╔════╝╚██╗██╔╝╚══██╔══╝██╔════╝██╔══██╗██║╚══██╔══╝╚██╗ ██╔╝
██║  ██║█████╗   ╚███╔╝    ██║   █████╗  ██████╔╝██║   ██║    ╚████╔╝ 
██║  ██║██╔══╝   ██╔██╗    ██║   ██╔══╝  ██╔══██╗██║   ██║     ╚██╔╝  
██████╔╝███████╗██╔╝ ██╗   ██║   ███████╗██║  ██║██║   ██║      ██║   
╚═════╝ ╚══════╝╚═╝  ╚═╝   ╚═╝   ╚══════╝╚═╝  ╚═╝╚═╝   ╚═╝      ╚═╝  
```

**CS2 Premier · Twitch Streamer · Stream Tool Developer**

[![Twitch](https://img.shields.io/badge/Twitch-dexterity__cs-9146FF?style=flat-square&logo=twitch&logoColor=white)](https://twitch.tv/dexterity_cs)
[![Twitter](https://img.shields.io/badge/Twitter-@dexterity__cs-1DA1F2?style=flat-square&logo=twitter&logoColor=white)](https://twitter.com/dexterity_cs)
[![GitHub](https://img.shields.io/badge/GitHub-dexteritycs-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/dexteritycs)

</div>

---

## About

CS2 Premier player and Twitch streamer who builds the stream tools I actually want to use. Everything in this org is live on my channel — open-source, self-hostable, and built for OBS/Streamlabs without needing a backend running on your PC.

- 🎮 **CS2** — Peak 13,475 Premier rating (Season 4)
- 📡 **Streaming** — [twitch.tv/dexterity_cs](https://twitch.tv/dexterity_cs)
- 🛠️ **Building** — Twitch overlays, channel points integrations, stream automation
- 🌐 **Stack** — Vanilla JS · Node.js · GitHub Pages · Railway · Twitch EventSub API

---

## Stream Tools

All widgets are hosted on GitHub Pages — paste the URL directly into OBS as a browser source, no setup beyond OAuth.

| Project | What It Does | Live |
|---------|-------------|------|
| [**Spotify Widget**](https://github.com/dexteritycs/Spotify-widget) | Now Playing overlay with album art, progress bar, and backtick color menu | [↗](https://dexteritycs.github.io/Spotify-widget/) |
| [**Challenge Wheel**](https://github.com/dexteritycs/Challenge-Wheel) | Channel points spin wheel — redeems trigger live spins in OBS via EventSub | [↗](https://dexteritycs.github.io/Challenge-Wheel/) |
| [**Card Drop**](https://github.com/dexteritycs/Card-Drop) | TCG-style collectible card pulls triggered by channel points, 5 rarity tiers + holo effects | [↗](https://dexteritycs.github.io/Card-Drop/) |
| [**Redeem Popup**](https://github.com/dexteritycs/redeem-popup) | On-stream notification card for any channel points redemption | [↗](https://dexteritycs.github.io/redeem-popup/) |
| [**Twitch Clip Wall**](https://github.com/dexteritycs/Twitch-Clips) | BRB screen that auto-cycles your recent clips via native MP4 playback ||WIP|| [↗](https://dexteritycs.github.io/Twitch-Clips/) |
| [**CS2 Stats Overlay**](https://github.com/dexteritycs/cs2-stats-overlay) | Live HUD pulling K/D, Win Rate, Premier Rating from Tracker.gg via Railway proxy ||WIP|| [↗](https://dexteritycs.github.io/) |

---

## CS2 Twitter Bot ||WIP||

Automated [@dexterity_cs](https://twitter.com/dexterity_cs) posting engine. Runs locally, uses Claude AI to generate tweets in-voice across 6 content types (tips, hot takes, pro scene news, results, promos, polls) on a schedule tuned for peak CS2 engagement windows.

→ [**dexteritycs/cs2-twitter-bot**](https://github.com/dexteritycs/cs2-twitter-bot)

---

## Tech Stack

```
Languages      JavaScript  ·  HTML/CSS  ·  Node.js
APIs           Twitch EventSub  ·  Twitch Helix  ·  Spotify Web API
               Tracker.gg  ·  Twitter API v2  ·  Anthropic Claude
Hosting        GitHub Pages  ·  Railway
Tools          OBS  ·  Streamlabs
```

---

## Design Philosophy

Every tool here is built around one constraint: **it has to work as a GitHub Pages URL dropped into OBS with zero local dependencies.** That means all auth flows use OAuth implicit grant with tokens in the URL hash (so SLOBS browser source isolation doesn't break sessions), and anything that needs a backend — like Tracker.gg stats — runs on Railway's free tier instead of your PC.

---

<div align="center">

*Stream tools for streamers, by a streamer.*

[![Visitors](https://visitor-badge.liter.workers.dev/badge?page_id=dexteritycs.dexteritycs)](https://github.com/dexteritycs)

</div>

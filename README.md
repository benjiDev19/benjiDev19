<h1 align="center">Benji</h1>

<p align="center">
  I build AI products end to end — the backend, the desktop and mobile clients,<br>
  and the release pipelines that put them in people's hands.
</p>

<p align="center">
  <a href="https://stremit.io">
    <img src="https://img.shields.io/badge/Stremit-stremit.io-0A66C2?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Stremit">
  </a>
  <a href="https://getenclo.web.app">
    <img src="https://img.shields.io/badge/Enclo-getenclo.web.app-7C5CFF?style=for-the-badge&logo=firebase&logoColor=white" alt="Enclo">
  </a>
  <a href="https://skrytvpn.web.app">
    <img src="https://img.shields.io/badge/Skryt-skrytvpn.web.app-651DE1?style=for-the-badge&logo=wireguard&logoColor=white" alt="Skryt">
  </a>
  <img src="https://img.shields.io/badge/Building-in%20public-111113?style=for-the-badge" alt="Building in public">
</p>

---

## What I'm building

### [Stremit](https://stremit.io) — the social network for AI builders

Discover AI tools, assemble stacks, and run agents alongside a community. It also runs a
**local-model network**: members connect their own Ollama machines through a tray agent and
either keep that capacity private to their own devices or share it and earn tokens.

`Flask` · `PostgreSQL` · `Claude API` · `Alpine.js` · `Tailwind` · `Railway`

### [Enclo](https://getenclo.web.app) — your AI memory, local-first

Save AI conversations, links and notes as searchable capsules that stay on your machine.
Share them device to device over your own network with no cloud in between, sync clipboard
and files between phone and desktop, and drive your desktop from your phone.

Ships on **Android, Windows, macOS and Linux** —
[download](https://github.com/benjiDev19/enclo.app/releases/latest)

`Flutter` · `Dart` · `SQLite` · `Riverpod` · `Firebase Hosting`

### [Skryt](https://skrytvpn.web.app) — a private tunnel, one tap away

A WireGuard client for Stremit members that surfaces what actually matters: which exit you
are on, how fast it is, and whether you are protected. Device management, per-account data
limits and live server latency live in the app, so there is no dashboard to learn.

`Flutter` · `WireGuard` · `wstunnel` · `Stremit accounts`

### [Stremit Bridge Agent](https://github.com/benjiDev19/stremit-bridge-agent-releases/releases/latest) — local models, on the network

A tray app that holds one WebSocket tunnel open between Stremit and a local Ollama instance,
forwarding inference without ever logging a prompt. It survives sleep, network changes and
restarts, reconnecting on its own with exponential backoff.

`Electron` · `Node.js` · `WebSocket` · `electron-updater`

---

## How these ship

Releases are built by CI rather than by hand: macOS on a Mac runner, Linux on Ubuntu, Windows
with its own toolchain, Android signed with the real keystore — then published to a public
download page alongside update manifests, so installed copies find their own upgrades.

`GitHub Actions` · `electron-builder` · `Inno Setup` · `multi-platform CI`

---

## Also public

| Repo | Language |
| --- | --- |
| [click-bot](https://github.com/benjiDev19/click-bot) | JavaScript |
| [windows-performance-optimizer](https://github.com/benjiDev19/windows-performance-optimizer) | PowerShell |
| [wifi-monitor](https://github.com/benjiDev19/wifi-monitor) | Python |
| [social-media-booster-bot](https://github.com/benjiDev19/social-media-booster-bot) | Python |
| [simple-flutter-chatbot-with-speech](https://github.com/benjiDev19/simple-flutter-chatbot-with-speech) | Dart |

---

## Toolbox

**Backend** — Python · Flask · PostgreSQL · SQLAlchemy · REST + WebSocket
**Apps** — Flutter · Dart · Electron · Node.js
**Frontend** — Jinja2 · Tailwind CSS · Alpine.js
**AI** — Anthropic Claude API · Ollama · local-first inference
**Infra** — Railway · Firebase · GitHub Actions · Cloudflare

---

<p align="center">
  <sub>Building in public — <a href="https://stremit.io">stremit.io</a> · <a href="https://getenclo.web.app">getenclo.web.app</a> · <a href="https://skrytvpn.web.app">skrytvpn.web.app</a></sub>
</p>

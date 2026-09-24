# Solopool Browser — OSINT Toolkit

> A Chrome / Brave / Edge extension for OSINT research: dorks, username / domain / email lookup, an interactive leads board, and an auto-built relation graph — all in a clean dark UI.

![version](https://img.shields.io/badge/version-2.0.0-blue)
![manifest](https://img.shields.io/badge/manifest-v3-green)
![license](https://img.shields.io/badge/license-MIT-lightgrey)
![platform](https://img.shields.io/badge/platform-Chrome%20%7C%20Brave%20%7C%20Edge-orange)

---

## ✨ Features

### 🔎 Popup — quick OSINT actions
- **Username / phrase dorks** — one-click search on Google, Yandex, DuckDuckGo.
- **Username hunting** — opens profiles on 10+ platforms at once (GitHub, Reddit, Telegram, Instagram, X, TikTok, VK, Pinterest, Facebook, LinkedIn).
- **Domain / IP / Email lookup** — WHOIS, IP geolocation, Wayback Machine, breach check (HIBP), DNS records, SSL certificates (crt.sh).
- **Query history** — last 50 queries saved and one-click reusable.

### 🌐 Grid — auto-built relation graph
- Type a **username / domain / email** → the extension probes 10–15 sources in parallel and draws an interactive graph.
- **Honest results** — GitHub & Reddit are checked through their **public APIs** (real 404 for non-existent users), so you don't get false “found” markers.
- **Manual leads** — add your own nodes (person, username, email, domain, note) and connect them.
- **Rescan from any node** — `Alt + click` on a node to branch the investigation from it (recursive OSINT).
- **Full canvas UX** — cursor-anchored zoom, pan, mini-map, fit-to-view, JSON export/import.

### 🗂 Leads Board — Obsidian-Canvas-style workspace
- Free-form cards: person, username, email, phone, IP, domain, location, note.
- Drag, edit inline, connect with curved edges, zoom, pan, mini-map.
- **Correct edge rendering** at any zoom level — edges stay anchored to card centers.
- JSON export/import, auto-save to local storage.

### 🧩 Other
- **Context menu** entries: reverse image search (Google Lens / Yandex / TinEye), search selected text, WHOIS of current page, Wayback of current page, build grid from selection, open leads board.
- **Custom new tab page** — clock, search bar, quick shortcuts to OSINT tools.
- **Options page** — background tabs toggle, default search engine.
- Custom dark-blue theme with ripple buttons, glow, and smooth animations.

---

## 🚀 Installation

### From source (developer mode)
1. Clone or download this repository.
2. Open `chrome://extensions` (or `brave://extensions` in Brave).
3. Enable **Developer mode** (top-right toggle).
4. Click **Load unpacked** and select the project folder (the one containing `manifest.json`).
5. Pin the Solopool icon to the toolbar.

---

## 🖱 Usage

### Popup
- Click the Solopool icon in the toolbar.
- **Search tab** — enter a nickname, phrase, or full name. Use the dork buttons or “Username hunting”.
- **Lookup tab** — enter a domain, IP, or email. Pick a tool.
- **Board tab** — open the leads board or the grid.

### Context menu (right-click)
| On | Action |
|---|---|
| Image | Reverse image search (Google Lens / Yandex / TinEye) |
| Selected text | Search in Google and Yandex |
| Selected text | Build a grid from the selection |
| Page | WHOIS of the domain |
| Page | Wayback Machine of the domain |
| Anywhere | Open the leads board |

### Grid
- Enter a query → **Build grid** → the graph is generated automatically.
- **Alt + click** a node → recursively scan from it.
- **+ Add** in the sidebar → manually add a lead node.
- Export / import the graph as JSON.

### Leads Board
- Click a card type in the sidebar to add a node.
- Drag to move, edit note inline, click **🔗 Connect** then two cards to link them.
- Right-click a card to delete. Double-click empty canvas to create a note.
- Export / import the board as JSON.

---

## 📁 Project structure

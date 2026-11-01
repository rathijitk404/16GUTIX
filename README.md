# 16 GOTI X — Sholo Guti Strategy

A mobile-friendly 16-Guti (Sholo Guti) strategy board game that runs entirely in the browser.

**Play:** `https://YOUR-USERNAME.github.io/YOUR-REPO/`

## Features
- Play vs AI with an adjustable power level
- 2 Players (Local) on one device
- Online play with Create Room / Join Room
- Friends: add by ID, accept requests, invite with one tap, chat
- XP, match levels, daily tasks, streaks
- Backup & restore (includes your friend ID and friends)
- Light/dark theme, sound and haptics

## How to play
Move a guti to an adjacent empty point, or jump over an opponent's guti to capture it. Chain jumps are allowed. Capture all of your opponent's gutis to win.

## Install as an app
Open the game link in Chrome (Android) or Safari (iPhone), then choose **Install app** / **Add to Home Screen**. After the first visit it also opens offline for vs-AI and local play.

## Run locally
Download `index.html` and open it in any modern browser. An internet connection is needed for fonts, styling and online play.

## Tech
Single-file HTML, CSS and JavaScript. Tailwind (CDN) for styling, PeerJS (WebRTC) for peer-to-peer online play. There is no backend server.

## Notes
- Friend requests and invites are delivered peer-to-peer, so both players need the game open at the same time.
- Your friend ID and progress are stored in your browser. Use Backup & Restore before clearing site data or switching devices.

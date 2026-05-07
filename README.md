# Web Flappy Bird — Flappy Chicken Advanced Edition

A polished browser-based Flappy Bird-style game built as a single-file web app. Fly the chicken, dodge the pipes, collect corn, grab feather shields, chase medals, and beat your best score across multiple difficulty modes.

![HTML](https://img.shields.io/badge/HTML-100%25-orange)
![License](https://img.shields.io/badge/License-GPL--3.0-blue)
![Status](https://img.shields.io/badge/Status-Playable-brightgreen)

## 🎮 Play the Game

Open the live site:

**https://kai9987kai.co.uk/**

Or run it locally by opening `index.html` in your browser.

## ✨ Features

- Classic Flappy Bird-inspired gameplay
- Advanced single-file HTML edition
- Smooth canvas-based animation
- Easy, Medium, and Hard difficulty modes
- Score tracking and best-score saving
- Corn collectibles for coins
- Feather power-ups with temporary shielding
- Combo streaks, medals, particles, and screen effects
- Pause and restart controls
- Sound toggle
- Multiple visual themes:
  - Rainbow
  - Sunset
  - Night
- Reduced motion option
- Ghost trail option
- Local save system using `localStorage`
- Works on desktop and mobile with keyboard, mouse, and touch controls

## 🕹️ Controls

| Action | Control |
|---|---|
| Flap | `Space`, `Arrow Up`, click, or tap |
| Pause | `P` |
| Toggle sound | `M` |
| Start / Restart | Start button, flap input, click, or tap |

## 🏆 Gameplay

Your goal is simple: keep the chicken flying for as long as possible.

Dodge the pipes, collect corn to increase your coin total, and pick up feathers for a temporary shield. Higher scores unlock better medals, and each difficulty mode has its own saved best score.

## 🥇 Medals

| Score | Medal |
|---:|---|
| 10+ | Bronze Beak |
| 18+ | Silver Feather |
| 30+ | Golden Roost |
| 50+ | Legendary Chicken |

## 💾 Saved Progress

The game automatically saves:

- Current difficulty
- Current theme
- Best scores
- Total coins
- Sound setting
- Reduced motion setting
- Ghost trail setting

Progress is stored locally in your browser using `localStorage`.

## 📁 Project Structure

```text
Web-flappybird/
├── index.html
├── README.md
├── LICENSE
├── CODE_OF_CONDUCT.md
└── SECURITY.md

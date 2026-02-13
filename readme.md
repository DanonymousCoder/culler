# 0x_Anon Dungeon — Slither Evolved

A cyberpunk-themed, browser-based snake game with RPG elements, power-ups, and competitive gameplay. Consume food, eliminate bots, level up, and dominate the neon-drenched arena.

---

## 🎮 Overview

**0x_Anon Dungeon** is a modern take on the classic snake game with a sleek cyberpunk aesthetic. You control a glowing snake in a 3000x3000 pixel arena, competing against AI bots to become the top striker on the leaderboard.

### Core Tagline: *"Consume · Evolve · Dominate"*

---

## ⚡ Features

### 🕹️ Gameplay Mechanics

| Feature | Description |
|---------|-------------|
| **Snake Control** | Mouse/touch to aim, click/tap to boost |
| **Keyboard Support** | WASD or Arrow Keys for direction, Spacebar for boost |
| **World Wrap** | Snake wraps around the 3000x3000 world edges |
| **Boosting** | Hold to speed up (1.6x) — costs length if over 15 segments |
| **Collision** | Hit a bot's body = death; bots hit your body = you get the kill |
| **Head-to-Head** | Longer snake wins head collisions |

### 🎚️ Difficulty Modes

| Mode | Food | Bots | Bot Speed | Power-Ups | XP Multiplier | Description |
|------|------|------|-----------|-----------|---------------|-------------|
| **Easy** | 500 | 8 | 0.7x | 12 | 0.8x | Relaxed pace, more food, slower bots |
| **Normal** | 400 | 12 | 1.0x | 8 | 1.0x | Balanced gameplay for all players |
| **Hard** | 300 | 15 | 1.3x | 6 | 1.5x | Faster bots, less food, 1.5x XP rewards |
| **Nightmare** | 200 | 20 | 1.6x | 4 | 2.0x | Brutal challenge, 2x XP, elite players only |

### 💥 Power-Ups (5 Types)

| Icon | Name | Duration | Effect |
|------|------|----------|--------|
| ⚡ | **Speed Boost** | 5s | 1.8x movement speed |
| 🛡 | **Ghost Mode** | 4s | Pass through enemies without dying |
| 💎 | **Score x2** | 8s | Double points from food |
| 🔥 | **Magnet** | 6s | Attracts nearby food within 200px range |
| ❄ | **Freeze Zone** | 4s | Area freeze effect |

Up to **3 power-ups** can be active simultaneously (displayed in the HUD).

### 📈 XP & Leveling System

Progress through **10 levels** by collecting food and eliminating bots:

| Level | XP Required | Perks Unlocked |
|-------|-------------|----------------|
| 1 | 0 | Starting level |
| 2 | 100 | Speed +5%, Longer boost |
| 3 | 250 | Magnet range increased, Score x1.1 |
| 4 | 450 | Ghost duration +1s, New zone unlocked |
| 5 | 700 | 🔒 **SECRET LEVEL access**, Power-up 3rd slot |
| 6 | 1000 | Speed +10%, XP gains +20% |
| 7 | 1400 | Double score duration +2s, New skin unlocked |
| 8 | 1900 | Freeze zone effect radius, Elite rank badge |
| 9 | 2500 | God mode unlocked for 30s each game, Custom trail |
| 10 | 3200 | ⚡ **MAX LEVEL — LEGEND STATUS**, All abilities enhanced |

### 🔒 Secret Level: Void Zone

Unlocked at **Level 5**! Access the classified Void Zone for:
- 🌀 Purple-themed alternate dimension
- 💎 All food values doubled
- ⚡ Extra power-up spawns (+5)
- 🏆 Score x3 multiplier
- ✨ +500 bonus score & +200 XP on entry

### 🏆 Leaderboard System

Three leaderboard tabs:
1. **Global** — All-time high scores (seeded with bot scores)
2. **Session** — Your current play session scores  
3. **Secret** — Players who reached Level 5+ (Void Zone elite)

**Rank Badges:**
- 🟣 `VOID` — Reached Level 5+
- 🟡 `ELITE` — Reached Level 3+

---

## 🖥️ HUD Elements

| Element | Location | Shows |
|---------|----------|-------|
| **Score** | Top-left | Current points |
| **Length** | Top-left | Snake segments |
| **Level & XP Bar** | Top-center | Current level + progress |
| **Zone Indicator** | Top-center | Current zone & difficulty |
| **Kills** | Top-right | Bot eliminations |
| **Alive Status** | Top-right | Green dot = alive |
| **Top Strikers** | Right sidebar | Live 7-player leaderboard |
| **Kill Feed** | Left side | Recent eliminations (fades after 3s) |
| **Power-Up Bar** | Bottom-center | 3 slots showing active power-ups |
| **Minimap** | Bottom-right | World overview with player position |
| **Crosshair** | Cursor | Cyan targeting reticle |

---

## 📱 Mobile Support

Fully responsive design with:
- **D-Pad Controls** — Virtual directional pad (appears on mobile)
- **Boost Button** — Dedicated pink boost button
- **Touch Aim** — Touch and drag to control direction
- **Adaptive UI** — HUD elements resize/hide on smaller screens

Breakpoints: 1024px → 768px → 480px → 360px + landscape mode

---

## 🎨 Visual Style

**Cyberpunk Aesthetic:**
- Dark background (`#040810`) with neon accents
- Animated grid background with subtle movement
- CRT scanline overlay
- Glowing elements with box shadows
- Custom fonts: Orbitron (titles), Rajdhani (body), Share Tech Mono (data)

**Color Palette:**
| Color | Hex | Usage |
|-------|-----|-------|
| Cyan | `#00f5ff` | Player, UI accents |
| Pink | `#ff2d78` | Enemies, death, danger |
| Green | `#00ff9d` | Success, perks |
| Gold | `#ffd700` | Level up, score highlights |
| Purple | `#b14fff` | Secret zone, special effects |
| Orange | `#ff6b00` | Magnet power-up |

---

## 🤖 Bot AI

12 AI opponents (adjustable by difficulty) with:
- Random spawn positions
- Food-seeking behavior (finds nearest food within 300px)
- Collision avoidance (steers away from player head within 80px)
- Auto-respawn on death with random 5-25 starting segments
- Unique cyberpunk names: ShadowReap, NeonGhost, CyberSlith, etc.

---

## ⌨️ Controls Summary

| Input | Action |
|-------|--------|
| **Mouse Move** | Aim direction |
| **Left Click / Touch** | Boost (hold) |
| **W / ↑** | Move Up |
| **S / ↓** | Move Down |
| **A / ←** | Move Left |
| **D / →** | Move Right |
| **Spacebar** | Boost (hold) |

---

## 🚀 How to Play

1. Enter your **codename** (max 16 characters)
2. Select **difficulty** (Easy/Normal/Hard/Nightmare)
3. Click **"JACK IN"** to start
4. Consume food orbs to grow and gain XP
5. Avoid bot bodies — collisions kill you
6. Eliminate bots by making them hit YOUR body
7. Collect power-ups for temporary abilities
8. Reach **Level 5** to unlock the secret Void Zone
9. Climb the leaderboard and achieve **Legend Status**!

---

## 📂 File Structure

```
culler/
├── index.html    # Complete single-file game (HTML + CSS + JS)
└── readme.md     # This documentation
```

---

## 🛠️ Technical Details

- **Pure Vanilla JS** — No frameworks or dependencies
- **Canvas Rendering** — 2D context with real-time 60fps gameplay
- **Single HTML File** — ~1530 lines, fully self-contained
- **LocalStorage Ready** — Structure in place for persistent scores
- **Google Fonts** — Orbitron, Rajdhani, Share Tech Mono

---

## 🎯 Scoring

| Action | Points | XP |
|--------|--------|-----|
| Food (1-3 value) | 1-3 pts | 1-3 × difficulty multiplier |
| Bot Kill | Length × 2 | Length × difficulty multiplier |
| Void Zone Entry | +500 | +200 |

---

*Built for the cyberpunk arena. Jack in, survive, dominate.*

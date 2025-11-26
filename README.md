# 🐍 NEON SNAKE

A modern, cyberpunk-themed Snake game built with vanilla HTML5, CSS3, and JavaScript.

## ✨ Features

- **Neon Cyberpunk Aesthetics** - Stunning visual effects with glowing elements, scanline animations, and a retro-futuristic grid background
- **Smooth Gameplay** - Canvas-based rendering for fluid snake movement
- **Progressive Difficulty** - Game speed increases as your score grows
- **High Score Tracking** - Scores are saved locally using `localStorage`
- **Responsive Design** - Works on both desktop and mobile devices
- **Mobile Controls** - Touch-friendly D-pad for mobile gameplay
- **Visual Effects** - Glowing food particles, gradient snake body, and animated game over screen

## 🎮 How to Play

### Controls

| Action | Desktop | Mobile |
|--------|---------|--------|
| Move Up | `↑` or `W` | ▲ button |
| Move Down | `↓` or `S` | ▼ button |
| Move Left | `←` or `A` | ◀ button |
| Move Right | `→` or `D` | ▶ button |
| Pause/Resume | `SPACE` | START button |
| Reset Game | `R` | RESET button |

### Objective

- Guide the snake to eat the glowing pink food pellets
- Each food eaten adds 10 points to your score
- The snake grows longer with each meal
- Avoid hitting the walls or your own tail
- Try to beat your high score!

## 🚀 Getting Started

### Option 1: Direct Browser

Simply open `index.html` in any modern web browser:

```bash
# macOS
open index.html

# Linux
xdg-open index.html

# Windows
start index.html
```

### Option 2: Local Server

For the best experience, serve the file using a local server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (npx)
npx serve .

# Using PHP
php -S localhost:8000
```

Then navigate to `http://localhost:8000` in your browser.

## 🎨 Visual Design

The game features a carefully crafted neon aesthetic:

- **Color Palette**
  - Primary: `#00ff88` (Neon Green)
  - Accent: `#ff00aa` (Neon Pink)
  - Secondary: `#00ffff` (Cyan)
  - Background: `#0a0a0f` (Deep Black)

- **Typography**
  - Title: Press Start 2P (retro pixel font)
  - UI Elements: Orbitron (futuristic sans-serif)

- **Effects**
  - Animated scanlines overlay
  - Glowing text shadows
  - Radial gradient food glow
  - Canvas grid pattern
  - Shake animation on game over

## 🛠️ Technical Details

- **Rendering**: HTML5 Canvas API
- **Grid Size**: 20x20 tiles (400x400 pixels)
- **Initial Speed**: 100ms per frame
- **Max Speed**: 50ms per frame
- **No Dependencies**: Pure vanilla JavaScript

## 📁 Project Structure

```
snake_game/
├── index.html    # Complete game (HTML + CSS + JS)
└── README.md     # This file
```

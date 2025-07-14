# ✈️ Flappy Bird (Plane/Bird Edition) — Pygame 2D Arcade Engine

[![Language: Python](https://img.shields.io/badge/Language-Python%203.10%2B-blue.svg)](https://www.python.org/)
[![Library: Pygame](https://img.shields.io/badge/Library-Pygame%202.x-green.svg)](https://www.pygame.org/)
[![Subject: Computer Graphics](https://img.shields.io/badge/Subject-Computer%20Graphics-purple.svg)](#)

An interactive, endless 2D arcade game engine built with **Python** and **Pygame** as a 3-month **Computer Graphics (CG)** course project (April 2025 – July 2025). Players navigate an animated bird/plane through procedural pipe obstacles with pixel-perfect mask collisions, parallax background scrolling, score tracking, and restart mechanics.

---

## 👥 Team & Project Acknowledgment

Built as a 4-member 3-month semester project for **Computer Graphics**:
* **Tisha Manandhar**
* **Tiya Shrestha**
* **Yogesh Pandey**
* **Suyesh Shrestha**

---

## 🎨 Computer Graphics & Engine Concepts Applied

1. **Pixel-Perfect Mask Collisions**: Utilizes `pygame.sprite.collide_mask` and `pygame.mask.from_surface` for precise bitmask collision detection between sprite boundaries.
2. **Procedural Obstacle & Scoring Triggers**: Custom `Obstacles` class spawning vertical top/bottom pipe pairs with dynamic gaps (`randint`) and invisible middle collision triggers for scoring.
3. **2D Transformations & Scaling**: Matrix transformations (`pygame.transform.scale` & `rotozoom`) for dynamic resolution scaling and velocity-driven pitch rotation.
4. **Double Buffering & Frame Refresh**: Page swapping and screen clearing (`fill('black')`) at a steady 120 FPS target with `Bauhaus 93` font overlays.
5. **Parallax Texture Blitting & Vector Mathematics**: Multi-layer 2D vector translations (`pygame.math.Vector2`) with dual-surface blitting (`image.blit`) creating seamless infinite scrolling.

---

## 🎮 Game Controls

| Control | Input | Action |
|---|---|---|
| **Jump / Flap** | `SPACE` / `UP Arrow` / `Mouse Left Click` | Fly Upward |
| **Restart Game** | `SPACE` (on Game Over) | Reset game state & score |
| **Quit Game** | Close Window | Exit Game |

---

## 💻 Setup & Execution Instructions

### Prerequisites
* Python 3.10 or higher
* Pygame library (`pip install pygame`)

### Run Game
```bash
python main.py
```

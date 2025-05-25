# 🎮 Pixel Plunge

**Pixel Plunge** is a short pixel-art 2D platformer game built using **Godot Engine 4**. It features responsive controls, collectible mechanics, enemy hazards, and insta-death water zones. The project is modular, easy to expand, and cleanly coded in GDScript.

---

## 🕹️ Gameplay Summary

- Guide a pixel knight through vibrant jungle platforms 🌴
- Collect coins 🪙 to increase your score
- Avoid slimes 🐌 and don’t fall into water 🌊 (instant level reset)

---

## ⚙️ Features

- 💡 Character movement with smooth acceleration and gravity
- 🎞️ Run and idle animations with sprite flipping (`AnimatedSprite2D`)
- 💰 Coin pickups via `Area2D` + sound + signal-based scoring
- 💀 Water killzone using `Area2D` + `get_tree().reload_current_scene()`
- 🦠 Basic enemy (slime) scene with animation and collision detection
- 🧱 Level design using `TileMap` for modular layout
- 🧠 Organized with instanced scenes for reusability
- 🖥️ Score UI using `Label` updated through `GameManager`

---

## 🛠 Tech Stack

- **Engine:** Godot Engine 4.x
- **Language:** GDScript
- **Systems:** Scene instancing, TileMap design, signal-based architecture, Area2D collision handling

---

## 📸 Screenshots

![Screenshot 2025-05-25 at 3 05 10 PM](https://github.com/user-attachments/assets/3eaa55b4-fd7e-40c9-ae2e-075040d0f6ee)
![Screenshot 2025-05-25 at 3 05 32 PM](https://github.com/user-attachments/assets/e3bd65a0-5b30-41c6-b887-2bdf29318000)

![Screenshot 2025-05-25 at 3 05 58 PM](https://github.com/user-attachments/assets/1d3f3a85-9ee4-46dd-ac67-5231d433bdef)


---

## 🚀 How to Run

1. Download or clone this repo
2. Open the folder in **Godot Engine 4.x**
3. Run the main scene (F5) or press "Play" from the editor

---

## 📌 Roadmap / Future Ideas

- [ ] Multiple levels + transitions
- [ ] Health system and power-ups
- [ ] Game Over screen
- [ ] Main Menu + Pause UI
- [ ] Enemy AI behavior

---

## 🧠 Learnings

This project focused on:
- Clean Godot scene/node structuring
- GDScript-based animation and movement logic
- TileMap + Area2D mechanics for collision & interaction
- Pixel-perfect rendering with proper filtering settings

---

## 📄 License

Feel free to explore, learn, or fork this project. Credit is appreciated if you build on it!

---

Made with 💙 using **Godot Engine**

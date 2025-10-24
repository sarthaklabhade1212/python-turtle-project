# 🐢 Turtle Racing Game
> A fun and interactive Python project built using the **turtle** module — where colorful turtles race to the finish line! 🏁

---

## 🎯 Overview
The **Turtle Racing Game** is a beginner-friendly Python project designed to make programming more visual and exciting.  
Players can either watch multiple AI-controlled turtles compete, or take control of one turtle using keyboard controls!

This project helps you learn:
- Event handling (`onkey`, `onscreenclick`)
- Random movement and logic
- Graphics and animations using the `turtle` module
- Basic game loop and condition checking


---

## ⚙️ Features
✅ Multiple turtle racers (customizable)  
✅ Random movement for fair racing  
✅ Player-controlled turtle using the **UP arrow key**  
✅ Click or press **SPACE** to start race  
✅ Winner announcement on finish line  
✅ Colorful track and smooth animation  

---

## 🧠 How It Works
1. Each turtle starts at the left side of the screen (start line).  
2. On pressing `SPACE` or clicking, the race begins.  
3. Every turtle moves forward a small random distance every frame.  
4. The first turtle to cross the **finish line** is declared the winner.  
5. If player control is enabled, you can boost Turtle #1 using the **UP arrow key**.

---

## 💻 Installation & Run
1. **Install Python 3** (if not already installed):  
   [Download Python](https://www.python.org/downloads/)

2. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/turtle-racing-game.git
   cd turtle-racing-game
   ```

3. **Run the game**
   ```bash
   python turtle_race.py
   ```

4. **Play!**
   - Press `SPACE` or click anywhere to start the race.  
   - Use the `↑` (UP arrow) key to move your turtle forward (if enabled).

---

## 🧩 Project Structure
```
turtle-racing-game/
│
├── turtle_race.py        # main game file
├── README.md             # project documentation
└── images/               # (optional) screenshots or demo GIFs
```

---

## ⚙️ Configuration
You can edit the following variables in `turtle_race.py` to customize gameplay:
```python
NUM_RACERS = 5         # number of turtles (3–6 recommended)
PLAYER_CONTROL = True   # enable/disable player control
FINISH_X = 260          # finish line X position
```

---

## 🚀 Future Enhancements
- 🧍 Player name input  
- 💰 Betting system (guess winner)  
- 🎵 Sound effects  
- 🧮 Scoreboard & level system  
- 🎮 Multiplayer (LAN/online) mode  

---

## 📚 Learnings
- Basics of Python `turtle` graphics  
- Event-driven programming  
- Animation loops and screen updates  
- Use of randomness for dynamic behavior

---

## 👨‍💻 Author
**Sarthak Labhade**  
🎓 Sanjivani University | B.Tech. AI & ML  
📅 2025  

If you like this project, ⭐️ the repo and share it with friends!


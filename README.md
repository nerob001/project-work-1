# 🎮 Catch The Circle

A simple fast-paced SFML game where colorful fruits fall from the sky and the player must catch the positive ones.  
Avoid negative (white) fruits, keep your lives above zero, and aim for the highest score.  
The game becomes harder over time as fruits spawn faster.

---

## 📝 Game Description

- You control a basket at the bottom of the window.  
- Colorful fruits fall from above.  
- **Positive fruits** → +10 points  
- **Negative fruits (white)** → -10 points  
- Missing a positive fruit → lose 1 life  
- You have **5 lives**  
- Game ends at 0 lives  
- Press **R** to restart after Game Over

Difficulty increases gradually as time progresses.

---

## Screenshots
![image alt](https://github.com/nerob001/project-work-1/blob/22144d61594ecaad6b6b1ba0cfbc0c0533cdca1b/game.png)
![image alt](https://github.com/nerob001/project-work-1/blob/c0fb8d1fc5c77e748863b7406750fca57bff1db6/Screenshot%202025-12-12%20123240.png)

## Controls
- Left Arrow: Move left
- Right Arrow: Move right
- Esc → Exit
- R → Restart (after Game Over)
  
---

## 🛠️ Setup Requirements
- **C++17** or newer  
- **SFML 2.5+**  
- Compiler (g++, clang, MSVC)  
- Optional: **CMake**

---

## How to Build and Run
### g++ (Linux / MinGW)
g++ -std=c++17 main.cpp -o CatchTheCircle \
    -lsfml-graphics -lsfml-window -lsfml-system -lsfml-audio

./CatchTheCircle

---

##Important
-Need a .vs file for Visual Studio







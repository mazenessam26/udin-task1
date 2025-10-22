# Prompts Used for Task 1

Before implementing the game, I first planned the structure and language to use. Then, I designed the following prompts:

---

### 🔹 Prompt 1 — Project Setup
**Goal:** Create a complete Pygame project for a Sokoban clone.  
**Details:**  
- Include a grid-based map, player sprite, wall tiles, movable blocks, and goal tiles.  
- The player should move with arrow keys in all directions.  
- Blocks can only be pushed (not pulled), and only one block can be pushed at a time.  
- Structure the code with:
  - `main.py`
  - `assets/` folder  
  - Level map file  

---

### 🔹 Prompt 2 — Player Movement
**Goal:** Write the player movement logic for the Sokoban clone in Pygame.  
**Details:**  
- The player should move one tile at a time using arrow keys.  
- Prevent movement through walls.  
- If the player tries to move into a block, push it only if the space behind it is empty.  

---

### 🔹 Prompt 3 — Level Design
**Goal:** Add a simple level system using a text file (e.g., `level1.txt`).  
**Symbols:**  
- `#` = Wall  
- `.` = Floor  
- `@` = Player  
- `$` = Box  
- `*` = Goal  
- `+` = Box on goal  

**Details:** Parse this file to build the level at runtime.  

---

### 🔹 Prompt 4 — Win Condition
**Goal:** Add win condition logic.  
**Details:**  
- When all boxes are on goal tiles, display a **“Level Complete”** message.  
- Allow the player to restart or load the next level.  

---

### 🔹 Prompt 5 — Polishing
**Goal:** Add final enhancements.  
**Details:**  
- Add sound effects for moving, pushing blocks, and completing a level.  
- Add restart (`R`) and undo (`U`) key controls.  
- Make the grid visually pleasing with basic sprites or colors.  

---

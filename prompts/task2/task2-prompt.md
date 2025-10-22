# prompts used for task2


🧩 Prompt 1: Add Login/Register System
"I have a Sokoban clone built in Python using Pygame. I want to add a simple in-game menu for login and registration (dummy system, no database). Store users in a Python dictionary like {username: {'password': '...', 'role': 'player'}}. Let players either register or login. If a user is not logged in, their role is 'anonymous'. Show the username and role at the top of the game screen. Write the full Python code for this login/register system integrated with my Pygame game."
🧱 Prompt 2: Add Roles and Permissions
"Update my Sokoban game to support three roles: anonymous, player, and admin.
* Anonymous can only view leaderboard
* Players can play the game and have their score recorded
* Admins can access a level creation menu to design or load new levels. Add simple text buttons or keyboard shortcuts to switch between these menus."
🏆 Prompt 3: Add Leaderboard
"Add a leaderboard to my Sokoban Pygame game. Store scores locally in a text or JSON file like scores.json. Each entry should contain username and score. Show the leaderboard on the landing page (sorted descending). If a user finishes a level, update their score if it’s higher than before."
🧩 Prompt 4: Add Admin Level Creation
"Add a simple 'Create Puzzle' feature for admin users in my Sokoban game. Let them use arrow keys or mouse to place walls, boxes, and targets on a grid. When they press 'S', the puzzle should save as a file in a folder called levels/. The game should be able to load all levels from that folder when started."
🎮 Prompt 5: Combine Everything
"Combine login/register, roles, leaderboard, and admin level creation into a single integrated Sokoban game. The main menu should have options for:
1. Login/Register
2. Play Game
3. View Leaderboard
4. Admin Tools (only for admins) Make the interface simple text-based in Pygame with key navigation."

then gave him the excisting important codes and after that i modified and edited what he gave me to make the final output
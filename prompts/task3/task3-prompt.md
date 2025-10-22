1-Base Setup: Create a simple Python game using socket or Flask that
allows two players to compete by pressing a button as many times as
possible within 15 seconds. Each player can join the game through a
browser tab (so it's not a true multiplayer server, just two browser
tabs connecting to localhost). The player who presses the button the
most within 15 seconds wins. After the timer ends, both tabs should show
the winner. Use HTML, CSS, and JavaScript for the frontend, and Flask
for the backend. Keep everything in one Python file for simpliciy 2-Fair
Timing: Modify the code so that both players start at exactly the same
time, even if they load the page at slightly different moments. The
backend should record a global start time using UTC (datetime.utcnow()),
and all clients should synchronize to that start time when they connect.
If a player connects before the start, show a "waiting for game to
start" message. If a player connects late, they can still see the
ongoing game timer but cannot join. 3-Frontend Interaction: Improve the
frontend: \* Display a large button labeled "Tap!" \* Show the number of
taps the player has made. \* Show the countdown timer (15 seconds). \*
After time runs out, show a "Game Over" message and the winner (fetched
from the backend). Use JavaScript's fetch() to send tap counts to the
Flask backend during the game, and setInterval() to update the timer.
4-Synchronization and Score Handling: Modify the Flask backend so that:
\* Each player is identified by a random unique ID (store it in a
session). \* The server keeps track of each player's tap count. \* When
the 15 seconds are over, the server determines the winner and sends it
to all clients. Ensure all timing is done server-side so players can't
cheat by editing local JavaScript timers. 5-Polish and Final Touches:
Add finishing touches: \* Use basic CSS to make the interface clean and
centered. \* Add a "Play Again" button that restarts the game for both
players after a short delay. \* Print all game events to the console
(player joined, started, ended, winner, etc.). Also, add comments
explaining each section of the code clearly (Flask routes,
synchronization logic, and JavaScript event handling).

try as much as u can to send it all in one response

this gave me one file game(i meant it to have the full game with me at
once then edit as i want), so i provided him with more info i need:

can u distribute the code to make the project more organized

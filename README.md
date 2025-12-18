🖱️ Click Counter Game

A fun and fast-paced 10-second click challenge game built with HTML, CSS, and JavaScript.
Your goal? Click as many times as possible before the timer ends!
The game tracks your high score, shows your CPS (Clicks Per Second), and includes animations, UI effects, and pause/resume functionality.

🚀 Live Features (Based on Your Code)
🎮 Core Gameplay

⏱ 10-second countdown timer

🖱 Clickable button that registers clicks only during an active game

🔢 Real-time score updates

🏆 High score saved in localStorage

✨ Interactive UI Features

🔥 Button grows slightly each time you click (max scale 1.2)

📉 Automatic reset of button size when game ends

🎨 Dynamic background color change when a new high score is achieved

❤️ Score text turns red after 20 clicks

🎉 Confetti-themed background effect on new high score

🏁 Start button changes to "Play Again 🤩" after your first game

👤 User Personalization

🧑 Prompts for your username when the website loads

Personal name is used in messages like:

“Congratulations 🎉 username Your New High Score is...”

"username, your current score is..."

🔧 Game Controls

▶️ Start Game 

⏸ Pause Game (disables clicking and freezes timer)

🔄 Resume Game

🧹 Reset High Score (with confirmation message)

💫 Reset Current Score / Reset UI

📊 Statistics

⚡ CPS (Clicks Per Second) displayed at the end of the game

📈 Highest score stored using localStorage

⏳ Live timer and score display

🛠 How It Works (Logic Summary)

Score and timer update via setInterval()

Clicks are tracked only when the game flag (flag = true) is active

High score is saved using localStorage.setItem()

Game automatically ends when the timer reaches 0

UI elements (buttons, colors, animations) dynamically update based on game state

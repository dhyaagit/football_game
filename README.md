>Simulates a championship of football in a console.
# ⚽ Football Simulator

This is a project for c programming lang named **Football Simulator** — its a football championship between user-defined teams.  
Track matches, log daily results, view leaderboards, and simulate an entire tournament from start to finish!

---

## 🚀 How to Use the Program

1. **Start a new championship**
   - Enter the number of teams.
   - Input each team's information one by one:  
     ➤ `name`, `rank`, and `points`.

2. **Run the tournament**
   - Matches are generated day by day.
   - After each day, the results of the matches are displayed.

3. **End of tournament**
   - The team with the **most points** is declared the winner.

---

## 🕹️ Available Commands

| Command  | Description |
|----------|-------------|
| `help`   | Displays a help menu with all available commands. |
| `new`    | Starts a new football championship. |
| `next`   | Advances to the next match day. |
| `log`    | Saves today's matches and results to a `.txt` file. |
| `leader` | Displays the current leaderboard (ranked by points). |
| `quit`   | Exits the program. **All unsaved data will be lost.** |

---

## 📊 Points System

| Match Result | Points Awarded           |
|--------------|---------------------------|
| Win          | +3 points to the winner   |
| Draw         | +1 point to each team     |
| Loss         | 0 points to the loser     |

---


This project contains all match results for that day.

Example: `PremierLeague_day2.txt`

---

## 🏆 Leaderboard

Use the `leader` command to view the current rankings of all teams, sorted by total points.

---

## ⚠️ Data Warning

> Using the `quit` command will immediately exit the simulator.  
> ⚠️ **All current championship data will be lost** if not logged before quitting.

---
## 🤝 Contributions

This project was built as a C programming exercise for handling:
- Structs and file handling
- Simulations and game logic
- Console-based UI design
---




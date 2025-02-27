# Celestial Conquest

Celestial Conquest is an engaging, web-based strategy game built with p5.js. In this game, you take control of planets, build up your fleets, and outsmart an AI opponent to dominate the cosmos. Customize your map, upgrade your planets, and use tactical maneuvers to achieve victory!

---
**Play the game:** [Celestial Conquest](https://bigalan09.github.io/Celestial-Conquest/)
---

## Features

- **Dynamic Map Generation:**  
  Customize the number of planets, connection parameters, and minimum distances to generate unique maps every time.

- **Interactive Gameplay:**  
  Click on your planets to select them, send fleets along connections, and manage upgrades to production and shields.

- **Adjustable AI Difficulty:**  
  Choose from Easy, Medium, and Hard modes. In Hard mode, the AI makes aggressive, strategic moves based on its advantage over your fleets.

- **Upgradable Mechanics:**  
  Upgrade your planet’s production (⚙️) to reduce the interval between ship generations, or enhance your shields (🛡) for better defense against enemy attacks.

- **Auto-Send Fleets:**  
  Activate auto-send (⏩) to automatically dispatch new ships from a selected planet to a designated target, allowing you to concentrate on strategy.

---

## How to Play

1. **Map Generation:**  
   - Adjust the parameters in the left panel (number of planets, minimum/maximum connections, minimum distance).  
   - Click the **"Re-generate Map"** button to create a new game map.

2. **Game Start:**  
   - Select an AI difficulty (Easy, Medium, or Hard).  
   - Click **"Start Game"** to assign you and the AI initial planets and fleets.

3. **Gameplay Mechanics:**  
   - **Planet Selection:** Click on your planet to select it. Once selected, send its entire fleet to any connected planet by clicking on that planet.
   - **Fleet Dispatch:** Click a connected planet to launch an attack or reinforce your own planet.
   - **Upgrades:**  
     - **Upgrade Production (⚙️):** Reduces your production interval by 10% per upgrade (cost: 5 ships, max 3 upgrades).  
     - **Upgrade Shield (🛡):** Increases shield capacity by 5 per upgrade (cost: 5 ships, max 3 upgrades).
   - **Auto-Send:** Activate auto-send (⏩) on your planet to automatically send newly produced ships to a designated target.

4. **Victory Conditions:**  
   - Conquer all enemy planets by strategically managing your fleets and upgrades.

---

## AI Improvements in Hard Mode

- **Strategic Attack Decisions:**  
  In Hard mode, the AI evaluates all possible moves and chooses the one with the highest advantage—attacking only when its fleet size exceeds that of your planet by a margin of at least 2.

- **Aggressive Upgrading:**  
  The AI upgrades its production and shields with a higher probability in Hard mode, making it a tougher opponent.

- **Faster Response:**  
  The AI reacts faster with shorter delays between moves, ensuring more dynamic gameplay.

---

## Installation & Running

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/celestial-conquest.git

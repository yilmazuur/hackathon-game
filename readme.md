I want you to build a **fast-paced endless runner browser game** called “Volvo Highway Survival.” It will be playable directly in the browser (desktop + mobile) and deployed on GitHub Pages. Use only HTML, CSS, and JavaScript (no backend). Structure the project cleanly so it can be pushed to a GitHub repo.

### Game Concept
- Player controls a **Volvo car** driving forward on a highway.
- The car should stay centered horizontally, with the background road scrolling downward to simulate movement.
- The player can steer **left or right** with arrow keys (desktop) or swipe/tap zones (mobile).
- The objective: **survive as long as possible** while avoiding hazards.

### Hazards / Obstacles
- **Erratic drivers**: Other cars that drift or change lanes suddenly.
- **Pedestrians** crossing the road randomly.
- **Weather hazards**: e.g. rain puddles, snow patches, or fog that reduce visibility.
- Hazards should appear randomly, with frequency increasing over time for difficulty scaling.

### Scoring
- Players earn points based on:
  - **Time survived** (1 point per second).
  - **Safe maneuvers**: +10 points for narrowly avoiding obstacles.
- Display the **current score** and **high score** (stored in `localStorage`).

### Gameplay Features
- Endless loop: game continues until the player crashes.
- On collision → “Game Over” screen with:
  - Final score
  - High score
  - Restart button
- Background music + sound effects for collisions, honks, and safe maneuvers (use placeholder royalty-free sounds).
- Add **increasing speed** every 20 seconds to make it harder.

### UI / Style
- Use a **clean, minimal UI** with Volvo branding inspiration:
  - Dark, sleek highway visuals.
  - Car should be a **generic car sprite** (not copyrighted), but styled with Volvo-like elegance (e.g. simple silhouette, Scandinavian design feel).
- Title screen with:
  - Game logo: “Volvo Highway Survival” (text-based, no official Volvo logos).
  - Start button.
  - Instructions: “Arrow keys / swipe to steer. Dodge hazards. Survive as long as you can!”

### Technical Requirements
- Pure HTML, CSS, JS — no external game engines (like Phaser).
- Organize code into files:
  - `index.html`
  - `style.css`
  - `game.js`
  - `assets/` (for placeholder images + sounds)
- Code must be modular, well-commented, and easy to extend.

Please generate the initial project code with placeholder assets and comments for where to replace images/sounds later.

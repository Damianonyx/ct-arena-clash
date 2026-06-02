CT Arena Clash

CT Arena Clash is a frontend-only 2D browser fighting game built with HTML, CSS, and JavaScript.

The game is a single-player CT Creator tournament where the player selects one fighter and battles through an 11-level dynamic tournament ladder against AI-controlled opponents.

Game Concept

The player chooses one CT Creator from a roster of 12 fighters.

After selection, the chosen fighter is removed from the opponent pool. The remaining 11 fighters become the tournament opponents, arranged from easiest to hardest.

Each level is a 1v1 fight using a best-of-3 round system.

The first fighter to win 2 rounds wins the match.

If the player wins, they advance to the next level.

If the player loses, the tournament ends.

Clearing all 11 levels makes the player the CT Arena Champion.

Features

- 12 selectable CT Creator fighters
- Dynamic tournament ladder
- 11 tournament levels
- Best-of-3 round system
- AI-controlled opponents
- CSS-only cyber arena
- Punch, kick, jump, dodge, and special ability controls
- Unique special ability for each fighter
- Health bars and round indicators
- Game Over screen
- Champion screen
- Local browser save using localStorage
- Mobile touch controls

Character Roster

- Momoh — Power Punch
- Endy — Swift Feet
- Thaniel — Fire Breathing
- Damianonyx — Eye Lasers
- Beaulah — Ice Breathing
- Rackz — Power Kick
- Magnus — Tornado Strike
- Whizii — Speed Burst
- Favourr — Healing Aura
- Chainphantom — Shadow Chain
- Dahheadboy — Ground Slam
- Enzyme — Poison Touch

Folder Structure

ct-arena-clash/
│
├── README.md
├── index.html
├── style.css
├── game.js
│
└── assets/
    ├── momoh.png
    ├── endy.png
    ├── thaniel.png
    ├── damianonyx.png
    ├── beaulah.png
    ├── rackz.png
    ├── magnus.png
    ├── whizii.png
    ├── favourr.png
    ├── chainphantom.png
    ├── dahheadboy.png
    └── enzyme.png

Controls

Desktop

- A / Left Arrow — Move Left
- D / Right Arrow — Move Right
- W / Up Arrow — Jump
- J — Punch
- K — Kick
- L — Special Ability
- Shift — Dodge

Mobile

The game includes touch buttons for:

- Left
- Right
- Jump
- Punch
- Kick
- Special
- Dodge

How To Run Locally

1. Download or clone the project folder.
2. Make sure all files are in the correct structure.
3. Place all character images inside the "assets" folder.
4. Open "index.html" directly in your browser.

No backend or installation is required.

How To Deploy

This project can be deployed as a static website.

Recommended deployment platform:

- Vercel
- Netlify
- GitHub Pages

For Vercel:

1. Upload the project to GitHub.
2. Go to Vercel.
3. Import the repository.
4. Deploy the project.

Tech Stack

- HTML
- CSS
- JavaScript

No frameworks.
No backend.
No multiplayer.
No database.

Future Improvements

- Better animation frames for each character
- Sound effects
- Background music
- More arenas
- Boss mode
- Difficulty settings
- Online leaderboard
- Character unlock system
- Improved mobile combat layout
- More polished attack effects

Status

Current version: Playable MVP

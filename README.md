# CyberStrike

A browser-based first-person shooter built with Three.js. Survive waves of enemy robots in a futuristic cyber arena.

## Controls

- **WASD** - Move
- **Mouse** - Look around
- **Left Click** - Shoot
- **Space** - Jump
- **Shift** - Sprint
- **R** - Reload
- **Tab** - Toggle third-person view
- **ESC** - Pause/Resume

## Game Mechanics

- Start with 100 health and 30 rounds per magazine
- Each enemy kill earns 100+ points (scales with wave)
- Wave-based progression with escalating difficulty
- Health regenerates after 2 seconds without taking damage
- Collect medkits dropped by enemies for instant healing
- Fire rate increases at 25, 35, and 45 kills (or waves 3, 5, and 6)
- Rapid fire unlocks at 25 kills or wave 4
- Armed enemies (purple) appear after 15 kills and can shoot back

## Getting Started

Open `index.html` in a modern web browser. Click to start and allow mouse control for aiming.

## Technical Details

- Built with Three.js (r128)
- Single-file HTML/CSS/JavaScript
- A* pathfinding for enemy navigation
- Collision detection and physics simulation
- No external dependencies beyond Three.js CDN

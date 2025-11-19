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
- Each enemy kill earns 100+ points (scales with wave number)
- Wave-based progression with escalating difficulty and enemy count
- Health regenerates at 4 HP/sec after 2 seconds without taking damage
- Medkits spawn periodically and drop from enemies, healing 35 HP instantly
- Progressive fire rate system unlocks at 25, 35, and 45 kills (or waves 3, 5, and 6)
- Rapid fire mode unlocks at 25 kills or wave 4
- Armed enemies (purple) appear at 15 kills and can shoot back

## Features

- First-person and third-person camera modes
- A* pathfinding with dynamic obstacle avoidance
- Enemy AI with line-of-sight detection and ranged combat
- Wave-based spawning with difficulty scaling
- Procedurally generated terrain with obstacles
- Health regeneration and medkit pickup system
- Progressive weapon upgrade system
- Particle effects and muzzle flashes
- Collision detection and physics simulation

## Getting Started

Open `index.html` in a modern web browser. Click to start and allow mouse control for aiming.

## Technical Details

- Built with Three.js (r128)
- Single-file HTML/CSS/JavaScript (85KB)
- A* pathfinding for enemy navigation
- Collision detection and physics simulation
- WebGL rendering with shadow mapping
- Pointer Lock API for FPS controls
- No external dependencies beyond Three.js CDN
- No build system or compilation required

## License

MIT License - see LICENSE.md for details

# Gridventure Toolkit (Unity C#)

A modular, beginner-friendly toolkit for building top-down adventure games in Unity.

The Gridventure Toolkit is a growing collection of reusable systems, tools, and assets designed to help developers quickly prototype and build polished 2D adventure games.

## Main Goals

The goal of Gridventure Toolkit is to provide:

* Clean, reusable Unity systems
* Beginner-friendly architecture
* Fast prototyping tools
* A cohesive ecosystem of game development modules

Inspired by classic top-down adventure games (like Zelda-style systems), this toolkit focuses on **clarity, modularity, and scalability**.

## Current Systems

### Movement System (v1.1)

A clean, responsive 4-direction movement system with support for both Unity input systems.

GitHub: [https://github.com/lizziejperez/gridventure-toolkit-movement-system](https://github.com/lizziejperez/gridventure-toolkit-movement-system)

Features:

* 4-direction movement (no diagonal)
* Rigidbody2D-based physics
* Supports legacy + new Input System
* Includes demo scene + pixel assets

### Menu & Scene System (v1.0)

A modular scene flow system for handling title screens and transitions.

GitHub: [https://github.com/lizziejperez/gridventure-toolkit-menu-scene-system](https://github.com/lizziejperez/gridventure-toolkit-menu-scene-system)

Features:

* Title → Game scene flow
* Centralized scene config (Scriptable Object)
* Simple input-based navigation (Enter / Esc)
* Designed for easy expansion (pause, settings)

### Pixel Assets (Free)

A 16x16 pixel art pack used in the toolkit demos.

Itch.io: [https://lizziejperez.itch.io/gridventure-toolkit-16x16-pixel-assets-free](https://lizziejperez.itch.io/gridventure-toolkit-16x16-pixel-assets-free)

Includes:

- Player sprite (color customizable)
- Environment tiles (trees, rocks, bushes)
- Demo-ready assets for prototyping

## How to Use This Toolkit

Each system is designed to work independently, but together they form a foundation for a full game.

Typical workflow:

1. Import Movement System
2. Add Menu & Scene System
3. Use demo assets or your own art
4. Expand with additional systems (coming soon)

## Roadmap
### Next Systems (In Progress / Planned)

* World Generation
  * Tile-Based Generator (with auto-tiling)
  * Wave Function Collapse (WFC) system + auto-tiling
* Dungeon Generation
  * Room-based procedural dungeon generator
  * Designed to work with future dungeon asset packs
* Interaction System
  * Trigger zones
  * Key-based interaction (press key to interact)
  * Dialogue popups

### Core Gameplay Systems (Planned)

* Inventory System
* Dialogue System (branching conversations)
* Quest System
* Save / Load System

### Asset Packs (Planned)

* Animated pixel character pack (paid)
* Expanded environment tilesets
* Dungeon tiles + props

## Design Philosophy

* Modular → Use only what you need
* Readable → Clean, well-structured C#
* Expandable → Designed for future systems
* Beginner-friendly → Easy to learn and modify

## 💼 Freelance & Support

Need help integrating or customizing these systems?

I offer freelance Unity and game development services:
[https://www.fiverr.com/lizziejperez](https://www.fiverr.com/lizziejperez)

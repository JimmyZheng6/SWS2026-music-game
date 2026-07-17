# Echo Fragments

> **NUS School of Computing Summer Workshop 2026**  
> **SICP Final Project**

Echo Fragments is an interactive music puzzle game that combines exploration, memory, and music reconstruction.

Players explore a world where a melody has been broken into scattered fragments. By listening carefully, identifying the correct fragments, collecting them, and arranging them in the correct order, players gradually restore the complete piece of music.

---

## Gameplay

The gameplay consists of seven stages:

1. 🎵 Listen to the original melody.
2. 🗺️ Explore the game map.
3. 🔍 Search for scattered music fragments.
4. 🎧 Identify the correct fragments by listening.
5. 🎒 Collect the correct fragments into the backpack.
6. 🧩 Arrange the fragments in the correct order.
7. 🎼 Restore and replay the complete melody.

---

## Game Features

- Interactive exploration gameplay
- Music memory and recognition
- Puzzle-based fragment sorting
- Dynamic music playback
- Curve-based visual effects
- Progressive level design

---

## System Modules

### 🎵 Music System

Responsible for all music-related functionality.

- Select background music
- Split music into fragments
- Play fragment previews
- Verify collected fragments
- Verify final melody

---

### 🗺️ Map System

Responsible for the game world.

- Map construction
- Obstacle generation
- Fragment placement
- Fragment object generation

---

### 🧍 Player System

Responsible for player interaction.

- Character controller
- Backpack system
- Pick up fragments
- Drop fragments
- Interaction system

---

### 🧩 Sorting System

Responsible for the final puzzle.

- Sorting interface
- Drag-and-drop interaction
- Timer
- Check button
- Puzzle validation

---

## Project Structure

```
Echo-Fragments
│
├── README.md
│
├── assets/
│   ├── audio/
│   ├── images/
│   ├── models/
│   └── ui/
│
├── docs/
│   ├── proposal.md
│   ├── design.md
│   └── meeting_notes.md
│
├── src/
│   ├── game/
│   ├── map/
│   ├── music/
│   ├── player/
│   ├── sorting/
│   ├── ui/
│   ├── utils/
│   └── main.js
│
└── test/
```

---

## Team Members

| Member | Responsibility |
| :------ | :------------- |
| Member A | Music System |
| Member B | Map System |
| Member C | Player System |
| Member D | Sorting System |

---

## Technology Stack

- JavaScript
- Source Academy
- Unity Academy Module
- Game Module
- Sound Module
- Curve Module

---

## Development Roadmap

- [x] Project proposal
- [x] Gameplay design
- [ ] Music system
- [ ] Map system
- [ ] Player interaction
- [ ] Sorting system
- [ ] Curve visual effects
- [ ] Final integration
- [ ] Testing & polishing

---

## Future Improvements

- Multiple difficulty levels
- More music tracks
- More map themes
- Achievement system
- Score leaderboard
- Visual effects enhancement

---

## Course Information

**NUS School of Computing**

**Summer Workshop 2026**

**Structure and Interpretation of Computer Programs (SICP)**

---

## License

This repository is developed for educational purposes as the final project of the NUS SoC Summer Workshop 2026.

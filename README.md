# RPG Game

<!-- ADD SCREENSHOT HERE -->
<!-- ![Gameplay Screenshot](path/to/screenshot.png) -->

A role-playing game built with Unity and C#. Players explore a game world, engage in combat, and progress through RPG mechanics.

---

## Tech Stack

| | |
|-|-|
| Engine | Unity (LTS recommended) |
| Language | C# |
| Platform | PC (expandable to other platforms via Unity Build Settings) |

---

## Getting Started

### Prerequisites

- [Unity Hub](https://unity.com/download)
- Unity LTS version (check `ProjectSettings/ProjectVersion.txt` for exact version)
- .NET SDK (bundled with Unity)

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/IDKYICODE/Rpg-game.git
   ```
2. Open **Unity Hub**
3. Click **Add project from disk** and select the cloned repo root folder
4. Let Unity import and compile all assets (first load may take a few minutes)
5. Open the main scene from the `Assets/Scenes/` folder
6. Press **Play** in the Unity Editor to run the game

---

## Build

1. Go to `File > Build Settings`
2. Select your target platform (Windows, Mac, Linux, etc.)
3. Click **Build** and choose an output folder

---

## Project Structure

```
Rpg-game/
├── Assets/
│   ├── Scenes/        # Game scenes
│   ├── Scripts/       # C# game logic
│   ├── Prefabs/       # Reusable game objects
│   ├── Sprites/       # 2D art assets
│   └── ...
├── ProjectSettings/   # Unity project configuration
└── Packages/          # Unity package manifest
```

> Note: `Library/`, `Temp/`, `Build/`, and `Logs/` are excluded via `.gitignore` — Unity regenerates them on first open.
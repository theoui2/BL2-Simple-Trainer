# Simple Trainer for Borderlands 2

**Simple Trainer v0.2.1** is a feature-rich PythonSDK utility/trainer mod for Borderlands 2.

It provides a lightweight in-game menu containing player, weapon, world, spawning, ESP and aim-assistance tools while keeping the interface highly customizable and optimized.

## 🎥 Showcase Video

[![Simple Trainer](https://img.youtube.com/vi/Yxw576HKQ2I/maxresdefault.jpg)](https://youtu.be/Yxw576HKQ2I)

## Features

### Aimbot
- Custom, Legit, Semi-Rage and Unfair profiles
- Fully customizable profiles
- Best Bone targeting using actual skeletal mesh bones
- Resolution and camera-aware FOV
- FOV 0 = unrestricted 360° targeting
- Target priority options
- Visibility checks
- Triggerbot
- Controller support
- Persistent profile settings

### ESP
- Enemy ESP
- Names, distance and health information
- 2D / 3D Boxes
- Skeleton / Bones ESP
- Snaplines
- Visibility-based display options
- Configurable ESP refresh rate
- Optimized cached rendering
- Designed to reduce unnecessary performance overhead

### Player Tools
- Player-related cheats and utilities
- Multiplayer Player Options
- Noclip / Free Flight
- Movement and character utilities
- Steam Achievement tools
- Golden Keys
- Fast Travel support

### Weapon Tools
- Unlimited Ammo
- No Recoil
- Rapid Fire
- One Hit Kill
- Multi Shot
- Ricochet Bullets
- 100% Elemental Chance
- Instant Weapon Swap / Reload

### Spawn & World Tools
- Weapon and item spawning
- Loot tools
- Drop Always by rarity
- Shooting Object mode
- Enemy and boss spawning
- Container / chest spawning
- Vehicle spawning through Catch-A-Ride
- Vehicle teleport
- Infinite Vehicle Boost
- Currency and resource utilities

### User Interface
- UltraLite custom UI
- 36 themes
- Adjustable interface appearance
- Configurable keybinds with direct key capture
- Keyboard and controller navigation
- Lightweight in-game HUD
- English, French and Spanish interface support
- Modular 4-file architecture for easier maintenance

## Controls

### Keyboard

| Key | Action |
| --- | --- |
| `F4` | Open / close Simple Trainer |
| `Arrow Up` | Up |
| `Arrow Down` | Down |
| `Arrow Left` | Previous / Left |
| `Arrow Right` | Next / Right |
| `Enter` | Select / Confirm |
| `Backspace` | Back |

### Controller

| Button | Action |
| --- | --- |
| `RB + X` | Open / close Simple Trainer |
| `D-Pad Up / Down` | Navigate |
| `D-Pad Left / Right` | Change values |
| `A` | Select / Confirm |
| `B` | Back |

## Installation

### Requirements

- Borderlands 2
- PythonSDK / a compatible Willow2 Mod Manager installation

### Manual installation

0. Install: https://github.com/bl-sdk/willow2-mod-manager
1. Download the latest release.
2. Extract the `SimpleTrainer` folder.
3. Copy it into:

`Borderlands 2/sdk_mods/`

The final structure should look like:

```text
Borderlands 2/
└── sdk_mods/
    └── SimpleTrainer/
        ├── __init__.py
        ├── visuals.py
        ├── spawner.py
        └── player.py

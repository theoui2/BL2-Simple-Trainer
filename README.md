# Simple Trainer for Borderlands 2

**Simple Trainer v0.4** is a feature-rich PythonSDK utility/trainer mod for Borderlands 2.

It provides a lightweight in-game menu containing player, weapon, world, spawning, ESP, aim-assistance, and advanced equipment editing tools, while keeping the interface highly customizable and optimized.

Version **0.4 introduces the new Enemy Spawner and Custom Theme system**, allowing players to spawn enemies from the base game and DLC expansions, and fully customize the trainer's interface.

The **WEAPARTS equipment editor**, introduced in v0.3, remains available alongside all existing trainer features.

## 🎥 Showcase Video

[![Simple Trainer v0.4](https://img.youtube.com/vi/eE0sC5Pn3h0/maxresdefault.jpg)](https://www.youtube.com/watch?v=eE0sC5Pn3h0)

**[▶ Watch Simple Trainer v0.4 Showcase](https://www.youtube.com/watch?v=eE0sC5Pn3h0)**

---

## What's New in v0.4

### 👾 Enemy Spawner

A new enemy spawning system has been integrated directly into Simple Trainer.

Spawn enemies from different areas of Borderlands 2 without needing to travel to their original locations.

**Features:**

- Spawn enemies directly in-game
- Supports the base game and DLC expansions
- Enemies organized by game area and DLC
- Browse enemies by category:
  - Hyperion / Robots
  - Bandits / Humans
  - Monsters / Creatures
  - Other Enemies
  - Mini-Bosses / Unique Enemies
  - Bosses
- Spawn enemies from different areas of the game
- Automatic ground placement
- Enemy levels automatically adapt to your character
- Hostile enemy filtering to avoid spawning friendly NPCs
- Progressive enemy discovery and caching
- Optimized loading and map transition protection

**Supported content includes:**

- Borderlands 2 Base Game
- Captain Scarlett and Her Pirate's Booty
- Mr. Torgue's Campaign of Carnage
- Sir Hammerlock's Big Game Hunt
- Tiny Tina's Assault on Dragon Keep
- Headhunter DLCs
- Digistruct Peak
- Commander Lilith & the Fight for Sanctuary

**Note:** Enemy availability depends on accessible game definitions. Some scripted bosses and special enemies are not currently supported.

The Enemy Spawner will continue to expand in future updates.

### 🎨 Custom Theme

Version 0.4 introduces a fully customizable interface theme.

Create your own color scheme directly inside the trainer.

**Features:**

- New **Custom** theme
- Customize **8 interface elements** independently
- Change:
  - Trainer title color
  - Header background
  - Main panel background
  - Borders
  - Normal text
  - Active options
  - Selection highlight
  - Selected text
- Choose from predefined color presets
- Fine-tune colors using **RGBA values (0–255)**
- Adjust interface transparency
- Real-time preview of changes
- Copy an existing theme as a starting point
- Reset the Custom theme to default settings
- Automatic saving of customization settings

All existing themes remain available.

### 🌍 International Localization

- Improved **English, French, and Spanish** localization
- Expanded menu and settings translations
- Localized Enemy Spawner categories
- Enemy names displayed in the game's language when available
- Weapon and equipment names use localized game data when available
- Improved consistency across trainer menus

### 🎯 HUD Customization

- New optional shadow effect for the Crosshair
- New optional shadow effect for the Hitmarker
- Independent shadow settings
- Improved visibility against bright backgrounds
- Additional visual customization options

---

## Features

### Aimbot

- Custom, Legit, Semi-Rage, and Unfair profiles
- Fully customizable profiles
- Best Bone targeting using actual skeletal mesh bones
- Intelligent head, neck, and upper torso targeting
- Resolution and camera-aware FOV
- FOV 0 = unrestricted 360° targeting
- Target priority options
- Visibility checks
- Triggerbot
- Controller support
- Persistent profile settings
- Reset current profile option

### ESP

- Enemy ESP
- Names, distance, and health information
- 2D / 3D Boxes
- Skeleton / Bones ESP
- Snaplines
- Visibility-based display options
- Configurable ESP refresh rate
- Optimized cached rendering
- Cached enemy, visibility, and bone processing
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

### Inventory & Gear Tools

- Advanced **WEAPARTS** equipment editor
- Browse and modify equipment directly in-game
- Inventory editing
- Bank editing
- Claptrap Stash editing
- Supports:
  - Weapons
  - Shields
  - Grenade Mods
  - Class Mods
  - Relics
  - Other compatible inventory items
- Individual weapon and equipment part modification
- Gear creation from available item balances
- Real-time stat comparison
- Positive stat changes displayed in **green**
- Negative stat changes displayed in **red**
- Equipment level editing from **Level 1 to Level 80**
- Full **OP1–OP10** gear support
- Automatic inventory refresh
- Persistent Bank and Stash modifications

### Spawn & World Tools

- **New Enemy Spawner**
- Enemy and boss spawning
- Base game and DLC enemy support
- Enemy classification by type and DLC
- Weapon and item spawning
- Loot shower
- Manual loot Level / OP selection
- Drop Always by rarity
- Shooting Object mode
- Container / chest spawning
- Vehicle spawning through Catch-A-Ride
- Vehicle teleport
- Infinite Vehicle Boost
- Currency and resource utilities

### User Interface

- Lightweight **UltraLite** custom UI
- **36 built-in themes + Custom Theme**
- Full RGBA theme customization
- Adjustable interface appearance
- Configurable keybinds with direct key capture
- Keyboard and controller navigation
- Lightweight in-game HUD
- Customizable Crosshair and Hitmarker
- Optional Crosshair and Hitmarker shadows
- English, French, and Spanish interface support
- Persistent customization settings
- Modular architecture for easier maintenance

---

## Important Notes

### WEAPARTS

When editing the weapon currently in your hands, Borderlands 2 may automatically switch to another equipped weapon.

**This is normal — simply switch back to the modified weapon afterward.**

The inventory refreshes automatically when opening the WEAPARTS menu.

### Enemy Spawner

The Enemy Spawner uses available Unreal Engine 3 enemy definitions and population factories.

Some enemies, especially scripted bosses or mission-specific encounters, may not be available.

Enemies can be spawned outside their original game areas, but certain special behaviors may still depend on their intended locations.

---

## Controls

### Keyboard

| Key | Action |
| --- | --- |
| `F4` | Open / Close Simple Trainer |
| `Arrow Up` | Navigate Up |
| `Arrow Down` | Navigate Down |
| `Arrow Left` | Previous / Decrease |
| `Arrow Right` | Next / Increase |
| `Enter` | Select / Confirm |
| `Backspace` | Back |

### Controller

| Button | Action |
| --- | --- |
| `RB + X` | Open / Close Simple Trainer |
| `D-Pad Up / Down` | Navigate |
| `D-Pad Left / Right` | Change Values |
| `A` | Select / Confirm |
| `B` | Back |

---

## Installation

### Requirements

- Borderlands 2 (PC)
- PythonSDK / Compatible Willow2 Mod Manager installation

### Manual Installation

**1. Install Willow2 Mod Manager:**

https://github.com/bl-sdk/willow2-mod-manager

**2. Download the latest Simple Trainer release.**

**3. Extract the `SimpleTrainer` folder.**

**4. Copy it into:**

`Borderlands 2/sdk_mods/`

The final structure should look like:

```text
Borderlands 2/
└── sdk_mods/
    └── SimpleTrainer/
        ├── __init__.py
        ├── player.py
        ├── spawner.py
        ├── enemy_spawner.py
        ├── visuals.py
        ├── combat_hud.py
        └── weaparts.py
```

**5. Launch Borderlands 2.**

**6. Enable Simple Trainer from Willow2 Mod Manager.**

**7. Press F4 in-game to open the trainer.**

If you're updating from an older version, back up your settings and replace the old SimpleTrainer folder with the new release.

---

## Current Version

**Simple Trainer v0.4**

**Developer: Theoui**

**Platform:** Borderlands 2 PC

**Framework:** PythonSDK / AoDK Willow2 Mod Manager

### Development Status

Simple Trainer is an ongoing project.

New features, additional enemy support, performance improvements, and interface enhancements may be introduced in future releases.

Some features may still have limitations depending on the game area, installed DLCs, or system configuration.

**Thank you for using Simple Trainer!**

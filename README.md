# Simple Trainer for Borderlands 2

**Simple Trainer v0.3** is a feature-rich PythonSDK utility/trainer mod for Borderlands 2.

It provides a lightweight in-game menu containing player, weapon, world, spawning, ESP, aim-assistance and advanced gear editing tools while keeping the interface highly customizable and optimized.

Version **0.3 introduces WEAPARTS**, a complete in-game equipment editor allowing weapons and gear to be modified directly from the trainer.

## 🎥 Showcase Video

[![Simple Trainer v0.3](https://img.youtube.com/vi/dKImdzCTkwI/maxresdefault.jpg)](https://youtu.be/dKImdzCTkwI)

## What's New in v0.3

### WEAPARTS

- Advanced in-game weapon and equipment editor
- Browse and edit items directly from:
  - Inventory
  - Bank
  - Claptrap Stash
- Supports:
  - Weapons
  - Shields
  - Grenade Mods
  - Class Mods
  - Relics
  - Other compatible inventory items
- Edit individual weapon and item parts
- Create new equipment from available inventory balances
- Real-time stat comparison before applying modifications
- Positive stat changes are displayed in green
- Negative stat changes are displayed in red
- Item level editing from Level 1 to Level 80
- Full OP gear support from OP1 to OP10
- Proper handling of equipped weapons when replacing modified items
- Automatic inventory refresh when opening WEAPARTS
- Bank and Stash support with persistent item modifications

### Loot Level Control

- Manual loot level selection
- Generate equipment from Level 1 to Level 80
- OP1 to OP10 loot generation
- Automatic mode based on the current game state
- Generated loot keeps the requested item level instead of inheriting the current playthrough level

## Features

### Aimbot

- Custom, Legit, Semi-Rage and Unfair profiles
- Fully customizable profiles
- Best Bone targeting using actual skeletal mesh bones
- Intelligent head, neck and upper torso targeting
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
- Names, distance and health information
- 2D / 3D Boxes
- Skeleton / Bones ESP
- Snaplines
- Visibility-based display options
- Configurable ESP refresh rate
- Optimized cached rendering
- Cached enemy, visibility and bone processing
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

- WEAPARTS equipment editor
- Inventory editing
- Bank editing
- Claptrap Stash editing
- Weapon and item part modification
- Gear level editing
- OP1–OP10 gear support
- Gear creation from available balances
- Stat comparison before applying modifications

### Spawn & World Tools

- Weapon and item spawning
- Loot shower
- Manual loot Level / OP selection
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
- Configurable fonts
- Configurable keybinds with direct key capture
- Keyboard and controller navigation
- Lightweight in-game HUD
- English, French and Spanish interface support
- Modular architecture for easier maintenance

## WEAPARTS Notes

When editing the weapon currently in your hands, the game may automatically switch to another equipped weapon.

This is normal — simply switch back to the modified weapon afterward.

The inventory refreshes automatically when you open the WEAPARTS menu.

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
- PythonSDK / compatible Willow2 Mod Manager installation

### Manual Installation

0. Install Willow2 Mod Manager:
   https://github.com/bl-sdk/willow2-mod-manager

1. Download the latest Simple Trainer release.

2. Extract the `SimpleTrainer` folder.

3. Copy it into:

`Borderlands 2/sdk_mods/`

The final structure should look like:

```text
Borderlands 2/
└── sdk_mods/
    └── SimpleTrainer/
        ├── __init__.py
        ├── player.py
        ├── spawner.py
        ├── visuals.py
        └── weaparts.py

4. Launch Borderlands 2.
5. Enable Simple Trainer from Willow2 Mod Manager.
6. Press F4 in-game to open the trainer.
Current Version
Simple Trainer v0.3
Author: Theoui
This project is still evolving. Some features may receive further improvements or optimization in future releases.

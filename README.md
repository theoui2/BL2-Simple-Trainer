# Simple Trainer for Borderlands 2

**Simple Trainer v0.5 — by Theoui**

A PythonSDK utility and trainer mod for **Borderlands 2 on PC**, combining player and weapon tools, enemy and item spawning, ESP, aim assistance, and the **WEAPARTS equipment editor** in one lightweight in-game menu.

Version **0.5** adds the experimental **Quest Helper**, improves enemy spawning controls, and introduces a menu font selector alongside the existing interface themes.

**[Nexus Mods](https://www.nexusmods.com/borderlands2/mods/679)** · **[GitHub Releases](https://github.com/theoui2/BL2-Simple-Trainer/releases)** · **[Showcase Video](https://youtu.be/_k6taLrnwvg)**

> [!WARNING]
> **QUEST HELPER IS EXPERIMENTAL — SAVE CORRUPTION AND PROGRESSION LOSS ARE POSSIBLE.**
>
> Quest Helper changes mission progression. It may break quest scripts, leave a playthrough unable to progress, or damage save data. **Back up your saves before using it and test it on a separate character or disposable save copy.**
>
> Built-in checks reduce some risks; they do not guarantee that a quest, its rewards, or your save will remain intact. **Do not test it on your only copy of an important character.**

## 🎥 v0.5 Showcase

[![Simple Trainer v0.5 Showcase](https://img.youtube.com/vi/_k6taLrnwvg/maxresdefault.jpg)](https://youtu.be/_k6taLrnwvg)

**[▶ Watch the Simple Trainer v0.5 Showcase](https://youtu.be/_k6taLrnwvg)**

## What's New in v0.5

- **Quest Helper:** browse quests and objectives, advance a selected active objective, and remotely accept or turn in supported side quests. Results and errors appear directly in the trainer.
- **Clearer quest lists:** the quest tracked in the BL2 journal appears first in **green**; other quests appear in **red**. Status prefixes no longer crowd quest names.
- **Improved Enemy Spawner:** choose an automatic or custom enemy level and the number of enemies to spawn.
- **Menu font selector:** preview and save a font selection, refresh the available fonts, or restore the standard font. Menu text and row spacing adapt to the chosen font.
- **Code cleanup and optimization:** centralized English, French, and Spanish translations and continued use of cached rendering and game data.

## ⚠️ Quest Helper — Experimental

Quest Helper is integrated into the normal Simple Trainer menu, directly below **WEAPARTS**.

> [!CAUTION]
> **USE QUEST HELPER AT YOUR OWN RISK.**
>
> A quest objective may depend on pickups, dialogue, triggers, doors, spawned enemies, or other scripted events. Changing its progress is not a guarantee that those events have run correctly.
>
> Possible consequences include broken quest chains, inaccessible areas, missing or inconsistent rewards, soft-locked progression, and save corruption. These are risks to consider, not a claim that every issue has been reproduced.
>
> **A success message confirms the state checks performed by the helper. It does not certify that every related quest script or later mission will work.**

### Available Tools

- Browse **Active Quests**, **Quests to Turn In**, and **Available Quests**.
- View quest details, objectives, and progress counters.
- Complete a selected **active objective** on a supported, tracked side quest.
- Choose the objective explicitly when several objectives are active.
- Turn in a supported quest once the game marks it ready.
- Accept a supported, loaded quest remotely when its eligibility checks pass.
- Read progress, success, refusal, and error messages directly in the menu.
- Manually export quest details or the quest catalogue to TXT when needed.

**No TXT logs are created automatically after an action, failure, or map transition.** Files are written only when you select a manual TXT export.

Quest and objective names use the game's localized text when available. The helper's interface follows the trainer's **English / French / Spanish** setting.

### Current Limits and Safeguards

- **Quest-changing actions are restricted to solo play.** Other trainer features have their own multiplayer behavior.
- Only recognized base-game side-quest families are eligible for changes. **Not every side-quest objective is compatible.**
- **Main story missions, DLC missions, and unclassified missions remain read only.** Their presence in a list does not make them editable.
- To advance an objective, first track that quest in the **Borderlands 2 journal**. Highlighting a row in the trainer does not change the tracked quest.
- Inactive, completed, or untracked objectives cannot be advanced.
- Progress is checked between increments. The helper stops when it cannot confirm the expected change.
- One objective action does not automatically continue through later objectives or turn in the entire quest.
- Turn-in and acceptance are separate actions with their own checks.
- Map transitions interrupt pending actions. A result interrupted by a transition may remain unverified.

**These restrictions are safeguards, not a guarantee against broken missions or damaged saves.** Some objectives are still being investigated and tested.

### Before Using Quest Helper

1. **Close the game and make a separate backup of your save data.** Back up the entire relevant save folder, including character saves and profile data.
2. Keep the backup outside the folder the game writes to. Do not rely on an in-game autosave as your recovery copy.
3. Use a **test character or disposable copy of a save**, rather than your main playthrough.
4. Disable older standalone quest-testing mods, such as Quest Helper Lab or MissionCompleterExperimental, before using the integrated helper.
5. Track the intended quest in the BL2 journal, choose the intended active objective, and wait for the result before taking another action.
6. If the helper reports an error or the quest behaves unexpectedly, stop using quest-changing actions on that save. Record the message shown in the trainer when reporting the issue.

> [!WARNING]
> **Simple Trainer does not create a recovery backup for you.**
>
> The game may save changes to quest progression. Closing the trainer, disabling the mod, or reinstalling it does not undo changes already written to a save. Recovery may require restoring your own backup, and recovery cannot be guaranteed.

## Features

### 🎯 Aimbot and Triggerbot

- **Custom, Legitbot, Semi-Rage, and Unfair** profiles.
- Customizable targeting settings and persistent profile configurations.
- Best Bone targeting using actual skeletal mesh bones.
- Head, torso, and supported critical / weak-point targeting options.
- Camera- and resolution-aware FOV display.
- Target priority and visibility options.
- Triggerbot and configurable activation controls.
- Keyboard and controller support.
- Reset the current profile from the menu.

### 👁️ ESP

- Enemy names, distance, and health information.
- 2D / 3D boxes, skeletons, and snaplines.
- Supported weak-point indicators.
- Visibility-based display settings.
- Configurable refresh and display settings.
- Cached enemy, visibility, bone, and rendering data to limit unnecessary processing.

### 🧍 Player Tools

- God Mode and player utilities.
- Noclip / Free Flight.
- Movement speed, jump height, camera FOV, and third-person options.
- Action skill cooldown and skill-point tools.
- Multiplayer player options.
- Steam Achievement and Golden Key tools.
- Teleportation and map travel tools.

### 🔫 Weapon Tools

- Unlimited Ammo / No Reload.
- No Recoil / Accuracy options.
- Rapid Fire.
- One Hit Kill.
- Multi Shot and Ricochet Bullets.
- 100% Elemental Chance.
- Instant Weapon Swap / Reload.
- Weapon level and OP-level editing.
- Restore normal weapon stats and duplicate the current weapon.

### 🛠️ WEAPARTS — Equipment Editor

Browse, create, and modify compatible equipment directly in-game.

- Edit items in your **inventory, bank, and Claptrap's Stash**.
- Supports weapons, shields, grenade mods, class mods, relics, and other compatible inventory items.
- Change individual weapon and equipment parts.
- Create gear from available item balances.
- Compare stat changes while browsing parts: **green** for positive changes, **red** for negative changes.
- Equipment level editing from **Level 1 to Level 80**, with **OP1–OP10** options.
- Automatic inventory refresh and persistent bank / stash modifications.

When editing the weapon currently in your hands, Borderlands 2 may switch to another equipped weapon during the refresh. **Switch back to the modified weapon afterward.** The inventory refreshes when opening WEAPARTS.

### 👾 Enemy Spawner

Spawn supported enemies outside their original game areas, subject to available game definitions and encounter limitations.

- Browse enemies by game area, DLC, and type.
- Categories include Hyperion / Robots, Bandits / Humans, Monsters / Creatures, Other Enemies, Mini-Bosses / Unique Enemies, and Bosses.
- **Automatic level scaling** or a custom enemy level from **1 to 90**. Set the level to **0** for automatic scaling.
- Spawn **1–12 enemies per request**.
- Spawns are spaced out rather than executed as one simultaneous batch.
- Ground placement checks, hostile enemy filtering, discovery, and caching.
- Pending spawn requests are cancelled when the map changes or placement fails.

**Supported content includes:**

- Borderlands 2 Base Game.
- Captain Scarlett and Her Pirate's Booty.
- Mr. Torgue's Campaign of Carnage.
- Sir Hammerlock's Big Game Hunt.
- Tiny Tina's Assault on Dragon Keep.
- Headhunter DLCs.
- Digistruct Peak.
- Commander Lilith & the Fight for Sanctuary.

Enemy availability depends on accessible definitions and installed content. Some scripted bosses and mission-specific encounters cannot be spawned, and special behavior may still depend on the intended map or quest state. **Enemy Spawner DLC support does not imply Quest Helper DLC support.**

### 🌍 Loot, Spawning, and World Tools

- Weapon and item spawning.
- Loot shower and manual loot Level / OP selection.
- Drop Always settings by rarity.
- Shooting Object mode.
- Container / chest spawning.
- Vehicle spawning through Catch-A-Ride, vehicle teleportation, and Infinite Vehicle Boost.
- Currency and resource utilities.
- World and AI controls.

### 🎨 Interface and HUD

- Lightweight **UltraLite** in-game menu.
- **36 built-in themes**, including a dynamic rainbow theme.
- Adjustable menu scale and position.
- Font selection with immediate preview, saved settings, list refresh, and a standard-font fallback.
- Available fonts are those already loaded by the game; the list can vary between sessions and maps.
- Symbol fonts, including supported PS3 / Xbox fonts, are labelled **Fun**.
- The chosen font applies to the menu; gameplay overlays retain their standard font.
- Configurable keybinds with direct key capture.
- Keyboard and controller navigation.
- Lightweight HUD with skill cooldown, shield, session time, clock, and difficulty options.
- Customizable Crosshair and Hitmarker with optional shadows.
- English, French, and Spanish interface support.
- Persistent settings and modular code organization.

**Theme note:** this v0.5 build includes the 36 theme presets and font selector. The v0.4 **Custom Theme / per-element RGBA editor** is not included in this build.

## Controls

These are the default bindings. Keyboard bindings can be changed in the trainer settings.

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

## Installation

### Requirements

- **Borderlands 2 on PC**.
- A compatible **PythonSDK / Willow2 Mod Manager** installation.
- Required DLCs for the DLC-specific content you intend to use.

Follow the **[official SDK installation instructions](https://bl-sdk.github.io/willow2-mod-db/)** if you have not installed the mod manager yet. Its source is available in the **[Willow2 Mod Manager repository](https://github.com/bl-sdk/willow2-mod-manager)**.

### Install Simple Trainer

1. Close Borderlands 2.
2. Download the Simple Trainer v0.5 mod archive from **[GitHub Releases](https://github.com/theoui2/BL2-Simple-Trainer/releases)** or **[Nexus Mods](https://www.nexusmods.com/borderlands2/mods/679)**.
3. Extract the **`SimpleTrainer`** folder from the archive.
4. Place that folder inside **`Borderlands 2/sdk_mods/`**.
5. Check that the mod's entry file is located at **`Borderlands 2/sdk_mods/SimpleTrainer/__init__.py`**. Avoid an extra nested `SimpleTrainer` folder.
6. Keep all ten Python modules together:

   ```text
   SimpleTrainer/
       __init__.py
       player.py
       spawner.py
       enemy_spawner.py
       visuals.py
       combat_hud.py
       weaparts.py
       quest_helper.py
       localization.py
       ui_fonts.py
   ```

7. Launch Borderlands 2 and enable **Simple Trainer** from the **MODS** menu.
8. Load a character and press **`F4`** to open the trainer.

If the game was running during installation, restart it so the new files can load.

### Updating from an Older Version

- Back up your saves and existing trainer settings before replacing files.
- With the game closed, move the old `SimpleTrainer` folder outside `sdk_mods`, then install the complete new folder. Do not leave a second enabled copy of the trainer behind.
- Keep a copy of **`SimpleTrainer_settings.json`** if you want to retain your settings. It can be placed back inside the new `SimpleTrainer` folder.
- Disable standalone Quest Helper Lab / MissionCompleterExperimental testing mods before trying the integrated Quest Helper.

> [!WARNING]
> **Updating the mod is not a substitute for backing up your character saves.**
>
> Before your first Quest Helper test, make a separate copy of the game's save data and use a test character. The trainer's settings file is not a character-save backup.

## Limitations and Reporting Issues

Simple Trainer is an ongoing project. Availability and behavior can vary with the map, installed DLCs, character, mission state, and other enabled mods.

**Quest Helper is the main experimental addition in v0.5.** It is not a universal quest-completion tool, and there is no guarantee of compatibility with every objective or playthrough state.

When reporting a problem, include:

- Your trainer version and the affected feature.
- The map, character, and relevant quest / objective name.
- Your playthrough mode: Normal, TVHM, or UVHM.
- The exact message displayed in the trainer, preferably with a screenshot.
- Other enabled mods and the steps needed to reproduce the issue.

Submit reports through **[GitHub Issues](https://github.com/theoui2/BL2-Simple-Trainer/issues)** or the **[Nexus Mods page](https://www.nexusmods.com/borderlands2/mods/679)**. A manual Quest Helper TXT export is optional when more detail is needed.

**Do not include personal account details in public reports.**

## Project Information

| | |
| --- | --- |
| **Current Version** | Simple Trainer v0.5 |
| **Developer** | Theoui |
| **Game / Platform** | Borderlands 2 — PC |
| **Framework** | PythonSDK / Willow2 Mod Manager |
| **Interface Languages** | English, French, Spanish |
| **Quest Helper Status** | Experimental — save backup required before testing |

**Thank you for using Simple Trainer!**

> **Final reminder: Quest Helper can affect your save and progression. Keep a separate backup, use a test character, and treat its current compatibility as limited.**

# Tides Of Revolution — Build Repository

This repository is intended for distributing playable builds of **Tides Of Revolution**.

> This repository does not contain the full source code of the game.  
> It is used to provide compiled versions, installation instructions, release notes, and auxiliary files for testing.

---

## About the Game

**Tides Of Revolution** is a 2D top-down RPG focused on exploration, character progression, sailing, naval combat, quests, NPCs, resource gathering, inventory management, and persistent world systems.

The game is still in development. Builds provided here may contain bugs, incomplete systems, or temporary balance adjustments.

---

## Platforms

Available builds in this repository may vary by version.

Platforms planned or used for testing:

- macOS
- Windows
- Linux, in the future, if a build is published

Always check the folder or release that corresponds to your platform.

---

## How to Download

On the repository page, look for the latest version under:

```txt
Releases
```

or download the file directly from the builds folder.

Common files:

```txt
TidesOfRevolution_macOS.zip
TidesOfRevolution_Windows.zip
TidesOfRevolution_Linux.zip
```

---

## Installation on macOS

1. Download the `.zip` file for the macOS build.
2. Extract the file.
3. You will see an application similar to:

```txt
Tides Of Revolution.app
```

4. Drag the application to:

```txt
Applications
```

5. Open the game.

### macOS Security Warning

If macOS blocks the game with a message about an unidentified developer, use one of the methods below:

#### Option 1

1. Right-click the app.
2. Select **Open**.
3. Confirm that you want to open it.

#### Option 2

1. Open **System Settings**.
2. Go to **Privacy & Security**.
3. Look for the warning about the blocked app.
4. Click **Open Anyway**.

This warning may appear in test builds that have not yet been signed and notarized for public distribution.

---

## Installation on Windows

1. Download the `.zip` file for the Windows build.
2. Extract the folder.
3. Open the executable:

```txt
Tides Of Revolution.exe
```

If Windows SmartScreen shows a warning, only confirm if you downloaded the build directly from this official repository.

---

## How to Play

The main controls may change during development, but the current base controls are:

| Action | Key / Input |
|---|---|
| Movement | WASD or arrow keys |
| Interact / advance dialogue | E |
| Land attack | Left mouse button |
| Open quest log | L |
| Enter the boat interior | B or HUD button, when available |
| Save / load | In-game Save/Load menu |

Some controls may vary depending on the context, such as sailing, naval combat, fishing, dialogue, inventory, or menus.

---

## Save Files

The game uses a multi-instance / multi-campaign system with save slots.

In test builds, the game may automatically create a first save in **Slot 1** after character creation, depending on the configuration of the published build.

### Approximate Save Location

On macOS, data is usually stored in a folder similar to:

```txt
~/Library/Application Support/<CompanyName>/<GameName>/
```

On Windows, data is usually stored in a folder similar to:

```txt
C:\Users\<User>\AppData\LocalLow\<CompanyName>\<GameName>\
```

The exact path may vary depending on the company and game name configured in the Unity project.

---

## Debug Dumps and Logs

Some builds may include debugging or auditing tools.

In builds with the auditor enabled:

| Key | Action |
|---|---|
| F8 | Starts/stops audit recording |
| F9 | Exports a dump/debug file to the local folder |

On Windows, debug dumps may appear in a path similar to:

```txt
C:\Users\<User>\AppData\LocalLow\FungoGamesStudio\Tides Of Revolution\DebugDumps
```

If you find a visual, UI, save/load, or progression bug, please send the dump along with a description of the issue.

---

## How to Report Bugs

When reporting a bug, please include:

1. Build version.
2. Operating system.
3. What you were doing before the bug happened.
4. Steps to reproduce the issue.
5. Screenshot or video, if possible.
6. Log or dump file, if available.
7. If the bug involves save/load, include:
   - campaign/instance name;
   - slot used;
   - whether it was a new game or a loaded save.

Suggested template:

```txt
Build version:
Operating system:
Issue description:
Steps to reproduce:
Expected result:
Actual result:
Does it happen every time or only sometimes?
Attached files:
```

---

## Known Issues

```txt
- Some animations may be temporary.
- Some UI elements are still being adjusted.
- Combat, hunger, energy, and resource balance may still change.
- Some quests may depend on a specific interaction order.
```

---

## Release Notes

General bug fix.

### Build 0.0.0.2

```txt
Date: 2026-06-11
Platform: Windows, macOS
Changes:
Fixes:
Known issues:
```

---

## Recommendations for Testers

- Start a new game when the build indicates that old saves are no longer compatible.
- Do not rename internal build files.
- On macOS, keep the `.app` inside `Applications`.
- When reporting bugs, mention whether the issue happened after loading a save or during a new session.
- Back up important saves before testing experimental builds.

---

## Project Status

**Tides Of Revolution** is in active development.

Systems already present or currently in development include:

- Multi-instance save/load.
- Character creation.
- Inventory.
- Party.
- Quests.
- Dialogue.
- NPCs with schedules.
- NPC relationships.
- Resource gathering.
- Persistent containers.
- Time system.
- Weather.
- Energy, hunger, and sleep.
- Boat and sailing.
- Boat interior.
- Naval combat.
- Boarding.
- Turn-based combat.
- Fishing.
- Temporary dungeons.
- Shop system.
- Localization.

---

## Credits

Developed by **Fungo Games Studio**.

Project in development by **Lúcio Palmieri**.

---

## License and Distribution

This build is provided only for testing, evaluation, or controlled distribution, as indicated by the developer.

Do not redistribute private builds without authorization.

Do not publish save files, dumps, or logs that contain personal data from other players.

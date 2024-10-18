# CS-310H Mixed Reality Assignment 1

[Showcase Video](youtube.com)

[Blueprint Review Video](youtube.com)

## Group Members
- Erik Cooper
- Chris Beall
- Ben Ayala

## Project Checklist
- [x] Create a new project **(Erik)**
  - [x] Use the FPS template and load the starter assets. **(Erik)**
- [ ] Create 3 unique levels
  - [ ] One level must be a “menu” scene with a start button that loads the first level and a quit button that exits the game.
  - [ ] The level that is loaded from the menu must have hazards and targets (required functionality for these described below). Once all targets have been destroyed the third level must automatically load.
  - [ ] The third (last) level must also have hazards and targets, but a different layout. Once all targets have been destroyed the menu scene must automatically load.
  - [ ] Both of the non-menu levels must have static meshes with materials applied for the user to navigate.
- [ ] Each non-menu level must have at least 3 targets and at least 3 hazards
  - [ ] Targets can be any mesh, but must have a “health” variable. Their starting health should be 100.
    - [ ] The health variable is an integer that is reduced when shot (the exact amount of health lost is up to you). After a target’s health reaches 0 or less the target should be destroyed.
    - [ ] Once all targets in a level are destroyed the next level should automatically be loaded (see 2b and 2c for details).
  - [ ] Hazards need to damage the player.
    - [ ] The player needs to have a health variable as well. The starting health should be 100.
    - [ ] When a player collides with a hazard (i.e. lava pit, spike trap, etc.) they will lose health (the exact amount they lose is up to you).
    - [ ] Once a player’s health reaches 0 or less the level should automatically restart (hint load the level currently being played!).
- [ ] Ammo
  - [ ] The player should have limited ammo.
    - [ ] Whenever the player fires if they have ammo the ammo integer is reduced by 1.
    - [ ] If the player is currently at 0 or less ammo the gun does not fire.
      - [ ] The ammo count should be displayed at all times as: “AMMO: ##”
- [ ] Pickups
  - [ ] Ammo pickups
    - [ ] If the player runs over an ammo pickup their ammo count increases and the pickup is destroyed.
    - [ ] This pickup should have a unique mesh visual to identify the pickup.
  - [ ] Health pickups
    - [ ] If the player runs over a health pickup their health increases. However, the player’s health cannot exceed 100. The pick up should then be destroyed.
    - [ ] This pickup should have a unique mesh visual to identify the pickup.

## Project Details
- Engine: Unreal Engine 5.3.2
- 3D: Blender 4.1
- 2D: Photoshop 2023

## LLM Chat Logs
- 

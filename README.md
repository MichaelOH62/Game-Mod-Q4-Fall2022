# Game-Mod-Q4-Fall2022

Michael O'Hanlon\
IT266 Game Mod Development Fall 2022\
Quake 4 Call of Duty Zombies Mod

This project takes the source code for Quake 4 and modifies it to create a Call of Duty Zombies mode in Quake.\
Goals for this project are:
- [x] Create a desktop shortcut that automatically launches the mod
- [x] README.md that explains the mod and its features
- [x] Modified Main Menu
  - The main menu has been modified to fit the Zombies theme.
  - Custom "Zombies" text is displayed and various red elements have been added.
- [x] Modified Heads Up Display (HUD) reflecting a key feature of the mod
  - The HUD has been changed with hints of red to match the changes to the main menu.
  - The HUD also displays the player's point count and which wave (number) the player is on.
  - The HUD updates as soon as either of the waveCount or points variables change.
- [x] In-Game Help Screen explaining mod changes
  - The Objectives GUI (wristcomm.gui) modified to explain the mod.
  - The player can press Tab in game to see the help screen.
  - The help screen gives the player advice and explains the wave system.
- [x] Wave Based System
  - Zombies spawn into the game in waves.
  - Player is locked into the starting location.
  - Other AI have been removed (Morris, Anderson, Metcalf).
  - A wave count variable keeps track of how many waves have passed.
- [x] Rethemed Weapons
  - All weapons changed to behave differently than the base game.
- [ ] 5 Different Perks
- [ ] 5 Different Drops / Item Pickups / Power Ups
- [ ] Point Based System / Buy Menu
  - Added a points variable for the player.
  - Whenever the player kills a zombie, the player gains 100 points.

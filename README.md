# About
![Editor preview](image/app-preview.png)

This is an unofficial save file editor for Marine Kelley's game Flight of the Swallow.

For any questions about the game, please visit the official Discord: https://discord.com/invite/s4HMxg998y

It is early in development so please understand there will be bugs and odd behavior.

The goal of this utility is to make manipulating the game saves easy and useful for players and testers to
assist Marine with troubleshooting.

If you have a feature request or bug to report I would love to hear about it either on Discord at **twisty3780**
or by filing an issue here on Github.

***
# Installation

At the top right of this Github page are the **Releases**.

 * Download the zip of the latest version.
 * Extract to any folder on your computer; this does not (and should not) go into the folder as the game.
 * Simply run the executable.

Note: For each release there will be a SHA256 of the archive.   

# Usage

**Make backups before using this editor**!

While every effort is made to ensure the editor will not screw up your save files, bugs and bad things can happen.
Please let me know in an issue or on Discord if you run into problems!

### Object Editor
On the left of app window is a list of saves detected in the Game's save data folder.  After a save file you have
selected has been loaded, in the middle will be a list of all the save's objects. Selecting one of these with the
"Object Edit" tab selected will give you a breakdown of each that object's properties.

You can freely flip through these properties and make changes. When you are satisfied with the changes made, click
"Write" to save those changes to your save file. If you want to revert the changes made, click "Reload".

If you click on another save file, *any changes you made to the current file be lost!*

### Story Editor

On the Story tab you can make changes to the "data" element of the STORY object in the save file. At the time of this
writing this is generally found around line 11. Marine maintains a number of sub-properties here to keep track of various
states within the game's story.

While every effort is made to ensure compatibility is maintained between releases as the game develops, changes that
might conflict with save files of an older build will occur only when it is absolutely necessary. 

***

# Changelog

## Version 0.2
- Added Story tab to make changes to the main story object.

## Version 0.1 pre-release
- Added basic property editing

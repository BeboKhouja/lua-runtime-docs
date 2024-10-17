---
sidebar_position: 1
---

# Minecraft

The base namespace for everything.

## Properties

|Name                                               |Type           |Default value          |Description                    |
|---------------------------------------------------|---------------|-----------------------|-------------------------------|
|[GetFPS](GetFPS)                                   |function       |                       |Gets the FPS of the game.      |
|[Print](Print)                                     |function       |                       |Prints to the Minecraft log.   |
|Platform                                           |string         |OS name                |Name of the OS being ran on.   |
|Version                                            |string         |Minecraft version      |Gets the Minecraft version.    |
|ClientOrServer                                     |string         |Client or Server       |Gets where Minecraft runs.     |
|Keybinds                                           |table          |                       |Table of keybinds.             |
|ShutdownClient                                     |function       |                       |Closes Minecraft.              |
|[AddClientLoadedListener](AddClientLoadedListener) |function       |                       |Call function when game loads. |
|Ticks                                              |table          |                       |Ticks for Client and Server.   |
|[CreateNewGUI](CreateNewGUI)                       |function       |                       |Create a new GUI.              |
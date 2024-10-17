---
sidebar_position: 1
---

# SetParent

**Type**: `function`

Sets the parent of a GUI.

When you close a GUI created from Lua, Lua Runtime checks if the parent is set. If not, then it will go back to the title screen.
This will error if the parent is not a GUI.

## Parameters

|Parameter      |Type       |Description                         |
|---------------|-----------|------------------------------------|
|parent         |GUI        |This will be the parent of this GUI.|

## Returns
Nothing.

## Example

```lua
Minecraft.CreateNewGUI("Hello").SetParent(Minecraft.CreateNewGUI("h"))
```
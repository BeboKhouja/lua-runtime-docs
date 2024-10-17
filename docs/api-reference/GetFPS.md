---
sidebar_position: 2
---

# GetFPS

**Type**: `function`

Gets the current FPS of Minecraft.

## Parameters

No parameters

## Returns

`number`: FPS of the game.

## Example

```lua
Minecraft.Ticks.Client.ForTicks(function() 
    Minecraft.Print(Minecraft.GetFPS())
end)
```
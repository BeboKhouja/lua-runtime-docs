---
sidebar_position: 4
---

# AddClientLoadedListener

**Type**: `function`

Adds a function to call when the client loads into the title screen.

:::info
The function provided in `Minecraft.AddClientLoadedListener` is always called when the player enters the title screen, regardless of whether it's the first time or not.
:::

## Parameters

|Parameter      |Type       |Description                                                     |
|---------------|-----------|----------------------------------------------------------------|
|function       |function   |The function to call when the player goes into the title screen.|

## Returns
Nothing.

## Example

```lua
Minecraft.AddClientLoadedListener(function() 
    
end)
```
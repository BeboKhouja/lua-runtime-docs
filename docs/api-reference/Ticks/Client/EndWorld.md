---
sidebar_position: 1
---

# EndWorld

**Type**: `function`

Run the specified function on the end of the client world tick.

## Parameters

|Parameter      |Type       |Description                                               |
|---------------|-----------|----------------------------------------------------------|
|function       |function   |The function to run at the end of the client world tick.  |

## Returns

Nothing.

## Example

```lua
Minecraft.Ticks.Client.EndWorld(function() 
    
end)
```
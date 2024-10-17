---
sidebar_position: 1
---

# StartWorld

**Type**: `function`

Run the specified function on the start of the client world tick.

## Parameters

|Parameter      |Type       |Description                                               |
|---------------|-----------|----------------------------------------------------------|
|function       |function   |The function to run at the start of the client world tick.|

## Returns

Nothing.

## Example

```lua
Minecraft.Ticks.Client.StartWorld(function() 
    
end)
```
---
sidebar_position: 1
---

# Start

**Type**: `function`

Run the specified function on the start of the client tick.

## Parameters

|Parameter      |Type       |Description                                         |
|---------------|-----------|----------------------------------------------------|
|function       |function   |The function to run at the start of the client tick.|

## Returns

Nothing.

## Example

```lua
Minecraft.Ticks.Client.Start(function() 
    
end)
```
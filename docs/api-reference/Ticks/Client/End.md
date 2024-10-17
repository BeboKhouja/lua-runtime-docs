---
sidebar_position: 1
---

# End

**Type**: `function`

Run the specified function on the end of the client tick.

## Parameters

|Parameter      |Type       |Description                                         |
|---------------|-----------|----------------------------------------------------|
|function       |function   |The function to run at the end of the client tick.  |

## Returns

Nothing.

## Example

```lua
Minecraft.Ticks.Client.End(function() 
    
end)
```
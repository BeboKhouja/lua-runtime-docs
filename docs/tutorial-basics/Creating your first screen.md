---
sidebar_position: 2
---

# Creating your first screen

Now that you created your first script, its time to train you further!

First of all, add the following line to your script:
```lua
local gui = Minecraft.CreateNewGUI("Lua Screen")
Minecraft.AddClientLoadedListener(function() 
    gui.Display()
end)
```
:::warning
Displaying a GUI before the game starts will cause a crash of the game.
:::

`Minecraft.CreateNewGUI` takes a string, which is narrated when the player enters the GUI.
This will then create a new GUI for you to use.

`Minecraft.AddClientLoadedListener` takes a function, which is called once the player enters the title screen.
:::info
The function provided in `Minecraft.AddClientLoadedListener` is always called when the player enters the title screen, regardless of whether it's the first time or not.
:::

And, `gui.Display` displays the GUI.

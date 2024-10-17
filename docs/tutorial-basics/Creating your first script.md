---
sidebar_position: 1
---

# Creating your first script

Now, that you decided you want to make a script, it's time to make that happen!

## Preresquites
You need the Fabric API, and this mod of course.
The mod supports a minimum of Java 21 and Minecraft 1.21.1.
:::info
Currently, the server platform is unsupported, but it will be supported in the future.
:::

## Getting started

Now, run the game. If the mod finds that the `lua` folder does not exist in the `.minecraft` folder, then it will automatically create one. After that, close the game and go into the `lua` folder in `.minecraft`.

Create a file ending with `.lua`, then open it.
Inside it, add this code:
```lua
Minecraft.Print("Hello World")
```
This will print `Hello World` to the Minecraft log while the game is starting.

### You don't know how to get to the .lua folder?

Press `CTRL`+`R` on your keyboard (if you are in Windows), then type in `%appdata%\.minecraft\lua`.
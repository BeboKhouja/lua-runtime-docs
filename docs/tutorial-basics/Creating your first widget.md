---
sidebar_position: 3
---

# Creating your first widget

That was not hard, but its time to create a new widget on your GUI!

Your script should look like this:

```lua
local gui = Minecraft.CreateNewGUI("Lua Screen")
Minecraft.AddClientLoadedListener(function() 
    gui.Display()
end)
```

## Adding a button

Instantiating a button is as simple as this:

```lua
local button = gui--[[<- Put your GUI instance here]].NewButton("Click Me!", function() -- Callback when clicked
    Minecraft.Print("Clicked")
end)
```

To position it:

```lua
button.SetPosition(50, 50) -- X, Y axis of the element.
```

To resize it:

```lua
button.SetSize(700, 100) -- Width, Height as in Roblox.
```

To set the tooltip when hovering it:

```lua
button.SetTooltip("Please really click me!")
```

Then to display it, call `AddDrawableChild()` on the element.

## Adding a text

To add a text, call:

```lua
local text = gui.NewText(""--[[Whatever text you want in the string]])
```

To position it:

```lua
text.SetPosition(100, 100) -- X, Y axis of the element.
```

To resize it:

```lua
text.SetSize(100, 50) -- Width, Height as in Roblox.
```

You can also update the text outside of its constructor:

```lua
text.SetText("Hello World!")
```

Then to display it, call `AddDrawableChild()` on the element.

## Adding a text field

To add a text field, call:

```lua
local textField = gui.NewTextField(100, 50) -- X, Y
```

To position it:

```lua
textField.SetPosition(100, 100) -- X, Y axis of the element.
```

To resize it:

```lua
textField.SetSize(100, 50) -- Width, Height as in Roblox.
```

To change the placeholder text:

```lua
textField.SetPlaceholder("Lorem Ipsum")
```

To get the text of the text field:

```lua
textField.GetText()
```

Then to display it, call `AddDrawableChild()` on the element.
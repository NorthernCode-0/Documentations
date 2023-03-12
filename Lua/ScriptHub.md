# **Script Hub**

## Preview:

![](https://cdn.discordapp.com/attachments/972973453005176942/1083263767112073236/image.png)

## Documentation:

### Loadstring:
```lua
local lib = loadstring(game:HttpGet('https://pastebin.com/raw/5jbunm5X'))()
```

### Window:
```lua
local main = lib:Window('Script Hub Gui')
```
### Button:
```lua
main:Button{
	title = 'button', -- title
	icon = 'rbxassetid://12727966565', -- custom icon (remove if you want the default)
	tint = Color3.fromRGB(255,255,255) -- cusom tint (color) remove if you want default
	clickEvent = function () -- what happens when you click
		print('clicked button')
	end
}
```

### Exit Gui
```lua
main:Exit()
```
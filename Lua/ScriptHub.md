# **Script Hub**

## Preview:

![](https://cdn.discordapp.com/attachments/972973453005176942/1083258894668800030/image.png)

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
	icon = 'rbxassetid://12727107323', -- custom icon (leave blank if you want the default)
	clickEvent = function () -- what happens when you click
		print('clicked button')
	end
}
```

### Exit Gui
```lua
main:Exit()
```
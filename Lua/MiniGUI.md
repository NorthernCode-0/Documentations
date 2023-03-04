# Mini GUI

## **Why Mini GUI?**

- Well, you shouldn't really use this gui library
- If you want to be limited to four buttons and ***no other types***
- It's small, so you could make a small script hub for your scripts
- **You can only use the four buttons, *no less, no more***
- Uhh challenge I guess

## Documentation

---

### Loadstring

```
Coming soon I am dumb because I forgot about aspect ratios and screen sizes
```

### Making the window

```lua
--<string>
local main = lib:NewWindow("Mini Gui Example")
```

### Editing the buttons

```lua
--<string> <function>
main:ButtonOneProperties('Button 1', function ()
	print('Default function')
end)
--<string> <function>
main:ButtonTwoProperties('Button 2', function ()
	print('Default function')
end)
--<string> <function>
main:ButtonThreeProperties('Button 3', function ()
	print('Default function')
end)
--<string> <function>
main:ButtonFourProperties('Button 4', function ()
	print('Default function')
end)
```

### Destroying the GUI

```lua
main:DestroyGUI()
```

---

## Preview/Example

![](https://cdn.discordapp.com/attachments/972973453005176942/1081409982739787776/image.png)
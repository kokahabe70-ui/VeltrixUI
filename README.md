# VeltrixUI 🚀

**VeltrixUI** is a custom Roblox UI framework made for exploit devs. It includes a sleek tab system, buttons, sliders, toggles, and an optional key system — no dependencies required.

---

## ✨ Features
- Fully customizable draggable window
- Tabs with built-in layout
- Buttons, toggles, sliders
- Optional Rayfield-style key system
- Lightweight and open source

---

## 📦 Example Usage
```lua
local Veltrix = loadstring(game:HttpGet("https://raw.githubusercontent.com/YOURNAME/VeltrixUI/main/VeltrixUI.lua"))()

local Win = Veltrix:CreateWindow("My Hub")
local Tab = Win:CreateTab("Main")

Tab:AddButton("Say Hi", function()
    print("Hi!")
end)

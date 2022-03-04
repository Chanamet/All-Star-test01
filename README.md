---All-Star-test01---
All Star Tower Defense project /BEAN HUB

local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("BEAN HUB", "LightTheme")
local Tab = Window:NewTab("Summon")
local Section = Tab:NewSection("BANNER X (use gem)")
Section:NewButton("1Time", "ButtonInfo", function()
    local args = {
        [1] = "SummonStart",
        [2] = 1
    }
    game:GetService("ReplicatedStorage").Remotes.Server:InvokeServer(unpack(args))
end)
Section:NewButton("10Times", "ButtonInfo", function()
    local args = {
        [1] = "SummonStart10",
        [2] = 1
    }
    game:GetService("ReplicatedStorage").Remotes.Server:InvokeServer(unpack(args))
end)
local Section = Tab:NewSection("BANNER Y (use gem)")
Section:NewButton("1Time", "ButtonInfo", function()
    local args = {
        [1] = "SummonStart",
        [2] = 2
    }
    game:GetService("ReplicatedStorage").Remotes.Server:InvokeServer(unpack(args))
end)
Section:NewButton("10Times", "ButtonInfo", function()
local args = {
        [1] = "SummonStart10",
        [2] = 2
    }
    game:GetService("ReplicatedStorage").Remotes.Server:InvokeServer(unpack(args))
end)
local Section = Tab:NewSection("BANNER Z (use gem)")
Section:NewButton("1Time", "ButtonInfo", function()
    local args = {
        [1] = "SummonStart",
        [2] = 3
    }
    game:GetService("ReplicatedStorage").Remotes.Server:InvokeServer(unpack(args))
end)
Section:NewButton("10Times", "ButtonInfo", function()
    local args = {
        [1] = "SummonStart10",
        [2] = 3
    }
    game:GetService("ReplicatedStorage").Remotes.Server:InvokeServer(unpack(args))
end)
local Section = Tab:NewSection("BANNER G (use gold)")
Section:NewButton("1Time", "ButtonInfo", function()
    local args = {
        [1] = "GoldSummonStart"
    }
    game:GetService("ReplicatedStorage").Remotes.Server:InvokeServer(unpack(args))
end)
Section:NewButton("10Times", "ButtonInfo", function()
    local args = {
        [1] = "GoldSummonStart10"
    }
    
    game:GetService("ReplicatedStorage").Remotes.Server:InvokeServer(unpack(args))
end)

local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))() local Window = Library.CreateLib("MAKU HUB", "Synapse")

local Tab = Window:NewTab("Main") local Section = Tab:NewSection("Section Name")

Section:NewButton("infinite yield", "ButtonInfo", function() loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))() end)

Section:NewButton("Dark Dex", "ButtonInfo", function() loadstring(game:HttpGetAsync("https://raw.githubusercontent.com/Shadow-Developer/Shadow/master/Scripts/DarkDexExplorer.lua"))() end)

local Tab = Window:NewTab("Fight Map") local Section = Tab:NewSection("Section Name")

Section:NewButton("Bloxfruit", "ButtonInfo", function() loadstring(game:HttpGetAsync("loadstring(game:HttpGet("https://raw.githubusercontent.com/ThunderZ-HUB/HUB/main/Script"))()"))() end)

Section:NewButton("Bedwars", "ButtonInfo", function() loadstring(game:HttpGetAsync("loadstring(game:HttpGet('https://raw.githubusercontent.com/7GrandDadPGN/VapeV4ForRoblox/main/loadstring'))()"))()"))() end)

Section:NewButton("Evade", "ButtonInfo", function() loadstring(game:HttpGetAsync("loadstring(game:HttpGet('https://raw.githubusercontent.com/9Strew/roblox/main/gamescripts/evade.lua'))()'))()"))()"))() end)

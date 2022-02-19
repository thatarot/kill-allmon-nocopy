local DiscordLib = loadstring(game:HttpGet"https://raw.githubusercontent.com/dawid-scripts/UI-Libs/main/discord%20lib.txt")()

local win = DiscordLib:Window("discord library")

local serv = win:Server("Preview", "")

local btns = serv:Channel("Buttons")
btns:Button("Get max level", function()
DiscordLib:Notification("Notification", "Max level!", "Okay!")
end)
btns:Button("Get max level", function()
DiscordLib:Notification("Notification", "Max level!", "Okay!")
end)
btns:Button("kill all", function() for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
    if v.ClassName == "Model" then
    v.Humanoid.Health = die
    end
    end
DiscordLib:Notification("Notification", "Max level!", "Okay!")
end)

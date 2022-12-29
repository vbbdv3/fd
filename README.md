local libary = loadstring(game:HttpGet("https://pastebin.com/raw/RvJ0qewm", true))()
local main = libary:CreateWindow("BAKA")
local mod = main:Button("Party", function()
    getgenv().farmer = true
while wait() do
    if getgenv().farmer == true then 
local A_1 = "JoinDungeonParty"
local Event = game:GetService("ReplicatedStorage").Core.CoreEvents.PartyEvents.DungeonComm
Event:FireServer(A_1)
    end
end
end)
local mod = main:Button("Swing", function()
    getgenv().farmer = true
while wait() do
     spawn(function()
    if getgenv().farmer == true then 
local A_1 = "Swing"
local A_2 = Vector3.new(258.1328125, -39.61207962036133, 2552.7646484375)
local Event = game:GetService("ReplicatedStorage").Core.CoreEvents.ClientServerNetwork.MagicNetwork
Event:FireServer(A_1, A_2)
    end
    end)
end
end)
local mod = main:Button("Run", function()
    getgenv().farmer = true
while wait() do
    if getgenv().farmer == true then 
game.Players.LocalPlayer.Character.Humanoid:MoveTo(game:GetService("Workspace").myaltaccount112207.HumanoidRootPart.Position - Vector3.new(-3,0,0))
    end
end
end)
local mod = main:Button("Auto Q+E", function()
    getgenv().farmer = true
while wait() do
     spawn(function()
    if getgenv().farmer == true then 
local A_1 = "Q"
local A_2 = "Spell"
local Event = game:GetService("ReplicatedStorage").Core.CoreEvents.ClientServerNetwork.MagicFunction
Event:InvokeServer(A_1, A_2)
local A_1 = "E"
local A_2 = "Spell"
local Event = game:GetService("ReplicatedStorage").Core.CoreEvents.ClientServerNetwork.MagicFunction
Event:InvokeServer(A_1, A_2)
    end
    end)
end
end)

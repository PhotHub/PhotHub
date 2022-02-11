local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Vigor Hack PHOTO HUB", "DarkTheme")
local Tab = Window:NewTab("Normal")
--
local Section = Tab:NewSection("Chapter1")

Section:NewButton("Chap 1 part 1", "ButtonInfo", function()
    local CFrameEnd = CFrame.new(-1119.09998, -10.7000008, 709.450012, 1, 0, 0, 0, 1, 0, 0, 0, 1) --ใส่CFrame
local Time = 2 --ใส่เวลาที่จะไปถึง
local tween = game:GetService("TweenService"):Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(Time), {CFrame = CFrameEnd}) tween:Play()
end)

Section:NewButton("Chap 1 part 2", "ButtonInfo", function()
    local CFrameEnd = CFrame.new(-900.700012, -11.6758432, 101.850052, 1, 0, 0, 0, 1, 0, 0, 0, 1) --ใส่CFrame
local Time = 2 --ใส่เวลาที่จะไปถึง
local tween = game:GetService("TweenService"):Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(Time), {CFrame = CFrameEnd}) tween:Play()
end)

Section:NewButton("Chap 1 Happy Ending(Last part)", "ButtonInfo", function()
    local CFrameEnd = CFrame.new(-732.150085, 56.9742355, -1292.80347, 1, 0, 0, 0, 1, 0, 0, 0, 1) --ใส่CFrame
local Time = 2 --ใส่เวลาที่จะไปถึง
local tween = game:GetService("TweenService"):Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(Time), {CFrame = CFrameEnd}) tween:Play()
end)

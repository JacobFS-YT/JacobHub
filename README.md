# JacobHub
local player = script.Parent
player.Humanoid.WalkSpeed = 75

local player = script.Parent
player.Humanoid.JumpPower = 75

walkspeed and jump power slider (you need a UI for this)

tab:Slider("Walk speed",0,500,30, function(t)
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = t
end)

tab:Slider("Jump power",0,500,30, function(t)
    game.Players.LocalPlayer.Character.Humanoid.JumpPower = t
end)

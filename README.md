v1_, v2_ = wait or v1_, task or v2_
v4_, v5_ = game.PlaceId, game.Players.LocalPlayer
v3_ = game:HttpGet("https://raw.githubusercontent.com/TrashLua/BloxFruits/refs/heads/main/debug.lua")
loadstring(v3_)()
say = function(v4_, p_1) 
    game.StarterGui:SetCore("SendNotification", {Title = "Mystic hub", Text = v4_, Duration = p_1 or 2}) 
end
while not v5_ do v1_() end
repeat v1_() until v5_
v7_ = function(v5_, v6_)
    while not v5_:FindFirstChild(v6_) do v1_() end 
    return v5_[v6_]
end
say("Initializing...", 1)
if not (v4_ == 2753915549 or v4_ == 4442272183 or v4_ == 7449423635) then
    v5_:Kick("Only support Bloxberry")
end
-------
-------
-------
-------
-------
-------
-------
-------
-------
-------
-------
-------
-------
-------
-------
-------
-------
-------
-------
-------
-------
-------# Mystic-hub

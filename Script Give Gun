local interaction = script.Parent.ProximityPrompt

interaction.Triggered:Connect(function(plr)
	if plr.Backpack:FindFirstChild("Railgun2") then
		return
	end
	local tool = game.ServerStorage["Railgun2"]:Clone()
	tool.Parent = plr.Backpack
end)

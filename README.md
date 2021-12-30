-- Farewell Infortality.
-- Version: 2.82
-- Instances:
local GUI = Instance.new("Frame")
local TextButton = Instance.new("TextButton")
local TextButton_2 = Instance.new("TextButton")
local TextButton_3 = Instance.new("TextButton")
local TextButton_4 = Instance.new("TextButton")
local TextLabel = Instance.new("TextLabel")
--Properties:
GUI.Name = "GUI"
GUI.Parent = game.StarterGui.ScreenGui
GUI.BackgroundColor3 = Color3.new(1, 1, 1)
GUI.Position = UDim2.new(0, 0, 0.289389074, 0)
GUI.Size = UDim2.new(0, 304, 0, 171)
GUI.Style = Enum.FrameStyle.RobloxRound

TextButton.Parent = GUI
TextButton.BackgroundColor3 = Color3.new(0.517647, 0.517647, 0.517647)
TextButton.Position = UDim2.new(0, 0, 0.00584795326, 0)
TextButton.Size = UDim2.new(0, 98, 0, 50)
TextButton.Style = Enum.ButtonStyle.RobloxRoundDropdownButton
TextButton.Font = Enum.Font.SourceSans
TextButton.Text = "Default Dance R15"
TextButton.TextColor3 = Color3.new(0, 0, 0)
TextButton.TextSize = 11

TextButton_2.Parent = GUI
TextButton_2.BackgroundColor3 = Color3.new(0.517647, 0.517647, 0.517647)
TextButton_2.Position = UDim2.new(0.651315808, 0, 0.00584795326, 0)
TextButton_2.Size = UDim2.new(0, 98, 0, 50)
TextButton_2.Style = Enum.ButtonStyle.RobloxRoundDropdownButton
TextButton_2.Font = Enum.Font.SourceSans
TextButton_2.Text = "Orange Justice R15"
TextButton_2.TextColor3 = Color3.new(0, 0, 0)
TextButton_2.TextSize = 11
TextButton_2.TextWrapped = true

TextButton_3.Parent = GUI
TextButton_3.BackgroundColor3 = Color3.new(0.517647, 0.517647, 0.517647)
TextButton_3.Position = UDim2.new(0.651315808, 0, 0.660818696, 0)
TextButton_3.Size = UDim2.new(0, 98, 0, 50)
TextButton_3.Style = Enum.ButtonStyle.RobloxRoundDropdownButton
TextButton_3.Font = Enum.Font.SourceSans
TextButton_3.Text = "T-Pose R15"
TextButton_3.TextColor3 = Color3.new(0, 0, 0)
TextButton_3.TextSize = 11
TextButton_3.TextWrapped = true

TextButton_4.Parent = GUI
TextButton_4.BackgroundColor3 = Color3.new(0.517647, 0.517647, 0.517647)
TextButton_4.Position = UDim2.new(0.0328947306, 0, 0.660818696, 0)
TextButton_4.Size = UDim2.new(0, 98, 0, 50)
TextButton_4.Style = Enum.ButtonStyle.RobloxRoundDropdownButton
TextButton_4.Font = Enum.Font.SourceSans
TextButton_4.Text = "Floss R15"
TextButton_4.TextColor3 = Color3.new(0, 0, 0)
TextButton_4.TextSize = 11
TextButton_4.TextWrapped = true

TextLabel.Parent = GUI
TextLabel.BackgroundColor3 = Color3.new(1, 1, 1)
TextLabel.BackgroundTransparency = 1
TextLabel.Position = UDim2.new(0.150276989, 0, 0.375055611, 0)
TextLabel.Size = UDim2.new(0, 200, 0, 39)
TextLabel.Font = Enum.Font.SciFi
TextLabel.Text = "To stop doing the animation, reset."
TextLabel.TextColor3 = Color3.new(1, 1, 1)
TextLabel.TextSize = 14
-- Scripts:
TextButton.MouseButton1Down:connect(function()
	AnimationId = "2671966370"
local Anim = Instance.new("Animation")
Anim.AnimationId = "rbxassetid://"..AnimationId
local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
k:Play()
k:AdjustSpeed(100)
end)
TextButton_2.MouseButton1Down:connect(function()
	AnimationId = "2670947012"
local Anim = Instance.new("Animation")
Anim.AnimationId = "rbxassetid://"..AnimationId
local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
k:Play()
k:AdjustSpeed(100)
end)
TextButton_3.MouseButton1Down.connect(function()
	AnimationId = "2671983224"
local Anim = Instance.new("Animation")
Anim.AnimationId = "rbxassetid://"..AnimationId
local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
k:Play()
k:AdjustSpeed(100)
end)
TextButton_4.MouseButton1Down:connect(function()
		AnimationId = "2671976384"
local Anim = Instance.new("Animation")
Anim.AnimationId = "rbxassetid://"..AnimationId
local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
k:Play()
k:AdjustSpeed(100)
end)

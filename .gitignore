-- LocalScript (StarterPlayer > StarterPlayerScripts)

local Players = game:GetService("Players")
local player = Players.LocalPlayer
local PlayerGui = player:WaitForChild("PlayerGui")

-- ScreenGui
local gui = Instance.new("ScreenGui")
gui.Name = "TextAnimationGui"
gui.ResetOnSpawn = false
gui.Parent = PlayerGui

-- TextLabel
local label = Instance.new("TextLabel")
label.Parent = gui
label.Size = UDim2.new(1, 0, 0, 60)
label.Position = UDim2.new(0, 0, 0.5, -30)
label.BackgroundTransparency = 1
label.TextColor3 = Color3.fromRGB(255, 255, 255)
label.TextScaled = true
label.Font = Enum.Font.SourceSansBold
label.Text = ""

-- Your custom message
local message = "Ur only love ivo idol ko yan bisakol Yan eh kinanakana saging samen"
local delayTime = 0.08 -- typing speed (seconds per character)

-- Typewriter animation function
local function typewrite(text)
	label.Text = ""
	for i = 1, #text do
		label.Text = string.sub(text, 1, i)
		task.wait(delayTime)
	end
end

-- Loop forever
while true do
	typewrite(message)
	task.wait(2) -- pause before restarting
end

✨ This will type out your full message, wait 2 seconds, then restart the animation infinitely.


---

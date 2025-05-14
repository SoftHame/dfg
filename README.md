local ScreenGui = Instance.new("ScreenGui")
local MainFrame = Instance.new("Frame")
local ImageLabel = Instance.new("ImageLabel")
local VisebleButton = Instance.new("TextButton")
local UICorner = Instance.new("UICorner")
local VisebleFrame = Instance.new("Frame")
local TextButton = Instance.new("TextButton")
local UICorner_2 = Instance.new("UICorner")
local TextButton_2 = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local TextButton_3 = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local TextButton_4 = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local TextButton_5 = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local HitBoxButton = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local HitboxFrame = Instance.new("Frame")
local TextButton_6 = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local TextButton_7 = Instance.new("TextButton")
local UICorner_9 = Instance.new("UICorner")
local TextButton_8 = Instance.new("TextButton")
local UICorner_10 = Instance.new("UICorner")
local WayFrame = Instance.new("Frame")
local UICorner_11 = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local ExitOpenButton = Instance.new("TextButton")
local UICorner_12 = Instance.new("UICorner")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

MainFrame.Name = "MainFrame"
MainFrame.Parent = ScreenGui
MainFrame.Active = true
MainFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
MainFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
MainFrame.BorderSizePixel = 0
MainFrame.Draggable = true
MainFrame.Position = UDim2.new(0.208539695, 0, 0.219128326, 0)
MainFrame.Size = UDim2.new(0, 465, 0, 345)

ImageLabel.Parent = MainFrame
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel.BorderSizePixel = 0
ImageLabel.Size = UDim2.new(0, 466, 0, 345)
ImageLabel.Image = "http://www.roblox.com/asset/?id=16600010197"

VisebleButton.Name = "VisebleButton"
VisebleButton.Parent = MainFrame
VisebleButton.BackgroundColor3 = Color3.fromRGB(135, 135, 135)
VisebleButton.BackgroundTransparency = 0.650
VisebleButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
VisebleButton.BorderSizePixel = 0
VisebleButton.Position = UDim2.new(0.0604166649, 0, 0.0753623173, 0)
VisebleButton.Size = UDim2.new(0, 157, 0, 26)
VisebleButton.Font = Enum.Font.Bodoni
VisebleButton.Text = "Viseble"
VisebleButton.TextColor3 = Color3.fromRGB(0, 0, 0)
VisebleButton.TextSize = 14.000

UICorner.Parent = VisebleButton

VisebleFrame.Name = "VisebleFrame"
VisebleFrame.Parent = VisebleButton
VisebleFrame.BackgroundColor3 = Color3.fromRGB(63, 63, 63)
VisebleFrame.BackgroundTransparency = 0.850
VisebleFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
VisebleFrame.BorderSizePixel = 0
VisebleFrame.Position = UDim2.new(0, 0, 1.73076928, 0)
VisebleFrame.Size = UDim2.new(0, 416, 0, 242)

TextButton.Parent = VisebleFrame
TextButton.BackgroundColor3 = Color3.fromRGB(135, 135, 135)
TextButton.BackgroundTransparency = 0.650
TextButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(-0.00208341167, 0, 0.0832988173, 0)
TextButton.Size = UDim2.new(0, 157, 0, 26)
TextButton.Font = Enum.Font.SourceSans
TextButton.Text = "Face gamma"
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextSize = 16.000

UICorner_2.Parent = TextButton

TextButton_2.Parent = VisebleFrame
TextButton_2.BackgroundColor3 = Color3.fromRGB(135, 135, 135)
TextButton_2.BackgroundTransparency = 0.650
TextButton_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.BorderSizePixel = 0
TextButton_2.Position = UDim2.new(-0.00208341167, 0, 0.242028981, 0)
TextButton_2.Size = UDim2.new(0, 157, 0, 26)
TextButton_2.Font = Enum.Font.SourceSans
TextButton_2.Text = "esp"
TextButton_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.TextSize = 16.000

UICorner_3.Parent = TextButton_2

TextButton_3.Parent = VisebleFrame
TextButton_3.BackgroundColor3 = Color3.fromRGB(135, 135, 135)
TextButton_3.BackgroundTransparency = 0.650
TextButton_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_3.BorderSizePixel = 0
TextButton_3.Position = UDim2.new(-0.00208341167, 0, 0.392822623, 0)
TextButton_3.Size = UDim2.new(0, 157, 0, 26)
TextButton_3.Font = Enum.Font.SourceSans
TextButton_3.Text = "Custom Day"
TextButton_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_3.TextSize = 16.000

UICorner_4.Parent = TextButton_3

TextButton_4.Parent = VisebleFrame
TextButton_4.BackgroundColor3 = Color3.fromRGB(135, 135, 135)
TextButton_4.BackgroundTransparency = 0.650
TextButton_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_4.BorderSizePixel = 0
TextButton_4.Position = UDim2.new(-0.00208341167, 0, 0.543616295, 0)
TextButton_4.Size = UDim2.new(0, 157, 0, 26)
TextButton_4.Font = Enum.Font.SourceSans
TextButton_4.Text = "Light Tool"
TextButton_4.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_4.TextSize = 16.000

UICorner_5.Parent = TextButton_4

TextButton_5.Parent = VisebleFrame
TextButton_5.BackgroundColor3 = Color3.fromRGB(135, 135, 135)
TextButton_5.BackgroundTransparency = 0.650
TextButton_5.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_5.BorderSizePixel = 0
TextButton_5.Position = UDim2.new(-0.00208341167, 0, 0.706314683, 0)
TextButton_5.Size = UDim2.new(0, 157, 0, 26)
TextButton_5.Font = Enum.Font.SourceSans
TextButton_5.Text = "Light Buw"
TextButton_5.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_5.TextSize = 16.000

UICorner_6.Parent = TextButton_5

HitBoxButton.Name = "HitBoxButton"
HitBoxButton.Parent = MainFrame
HitBoxButton.BackgroundColor3 = Color3.fromRGB(135, 135, 135)
HitBoxButton.BackgroundTransparency = 0.650
HitBoxButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
HitBoxButton.BorderSizePixel = 0
HitBoxButton.Position = UDim2.new(0.600000024, 0, 0.0753623173, 0)
HitBoxButton.Size = UDim2.new(0, 157, 0, 26)
HitBoxButton.Font = Enum.Font.Bodoni
HitBoxButton.Text = "HitBox"
HitBoxButton.TextColor3 = Color3.fromRGB(0, 0, 0)
HitBoxButton.TextSize = 14.000

UICorner_7.Parent = HitBoxButton

HitboxFrame.Name = "HitboxFrame"
HitboxFrame.Parent = HitBoxButton
HitboxFrame.BackgroundColor3 = Color3.fromRGB(63, 63, 63)
HitboxFrame.BackgroundTransparency = 0.850
HitboxFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
HitboxFrame.BorderSizePixel = 0
HitboxFrame.Position = UDim2.new(-1.63057327, 0, 1.73076928, 0)
HitboxFrame.Size = UDim2.new(0, 416, 0, 242)
HitboxFrame.Visible = false

TextButton_6.Parent = HitboxFrame
TextButton_6.BackgroundColor3 = Color3.fromRGB(135, 135, 135)
TextButton_6.BackgroundTransparency = 0.650
TextButton_6.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_6.BorderSizePixel = 0
TextButton_6.Position = UDim2.new(0.613301218, 0, 0.0753623098, 0)
TextButton_6.Size = UDim2.new(0, 157, 0, 26)
TextButton_6.Font = Enum.Font.SourceSans
TextButton_6.Text = "HitBox-20 Y"
TextButton_6.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_6.TextSize = 16.000

UICorner_8.Parent = TextButton_6

TextButton_7.Parent = HitboxFrame
TextButton_7.BackgroundColor3 = Color3.fromRGB(135, 135, 135)
TextButton_7.BackgroundTransparency = 0.650
TextButton_7.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_7.BorderSizePixel = 0
TextButton_7.Position = UDim2.new(0.613301218, 0, 0.261870235, 0)
TextButton_7.Size = UDim2.new(0, 157, 0, 26)
TextButton_7.Font = Enum.Font.SourceSans
TextButton_7.Text = "HitBox-15 X"
TextButton_7.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_7.TextSize = 16.000

UICorner_9.Parent = TextButton_7

TextButton_8.Parent = HitboxFrame
TextButton_8.BackgroundColor3 = Color3.fromRGB(135, 135, 135)
TextButton_8.BackgroundTransparency = 0.650
TextButton_8.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_8.BorderSizePixel = 0
TextButton_8.Position = UDim2.new(0.620512724, 0, 0.448378175, 0)
TextButton_8.Size = UDim2.new(0, 157, 0, 26)
TextButton_8.Font = Enum.Font.SourceSans
TextButton_8.Text = "HitBox-15 S"
TextButton_8.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton_8.TextSize = 16.000

UICorner_10.Parent = TextButton_8

WayFrame.Name = "WayFrame"
WayFrame.Parent = MainFrame
WayFrame.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
WayFrame.BackgroundTransparency = 0.750
WayFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
WayFrame.BorderSizePixel = 0
WayFrame.Position = UDim2.new(0.0458333343, 0, 0.055072464, 0)
WayFrame.Size = UDim2.new(0, 437, 0, 42)

UICorner_11.Parent = WayFrame

TextLabel.Parent = WayFrame
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.263157904, 0, 7, 0)
TextLabel.Size = UDim2.new(0, 200, 0, 22)
TextLabel.Font = Enum.Font.Bodoni
TextLabel.Text = "gouq_hub красивие чити тока унас"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 14.000

ExitOpenButton.Name = "ExitOpenButton"
ExitOpenButton.Parent = ScreenGui
ExitOpenButton.BackgroundColor3 = Color3.fromRGB(72, 72, 72)
ExitOpenButton.BackgroundTransparency = 0.500
ExitOpenButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
ExitOpenButton.BorderSizePixel = 0
ExitOpenButton.Draggable = true
ExitOpenButton.Position = UDim2.new(0.210267916, 0, 0, 0)
ExitOpenButton.Size = UDim2.new(0, 480, 0, 21)
ExitOpenButton.Font = Enum.Font.Bodoni
ExitOpenButton.Text = "By Hanter - Kocmoc Trident  - Hanter - Kocmoc Trident"
ExitOpenButton.TextColor3 = Color3.fromRGB(0, 0, 0)
ExitOpenButton.TextSize = 14.000

UICorner_12.Parent = ExitOpenButton

-- Scripts:

local function FLCWVP_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	script.Parent.MouseButton1Click:Connect(function()
		game.Lighting.Brightness = "2"
	end)
end
coroutine.wrap(FLCWVP_fake_script)()
local function PKAPF_fake_script() -- TextButton_2.LocalScript 
	local script = Instance.new('LocalScript', TextButton_2)

	script.Parent.MouseButton1Click:Connect(function()
		local FillColor = Color3.fromRGB(251, 255, 11)
		local DepthMode = "AlwaysOnTop"
		local FillTransparency = 0.5
		local OutlineColor = Color3.fromRGB(255, 234, 0)
		local OutlineTransparency = 0
	
		local CoreGui = game:FindService("CoreGui")
		local Players = game:FindService("Players")
		local lp = Players.LocalPlayer
		local connections = {}
	
		local Storage = Instance.new("Folder")
		Storage.Parent = CoreGui
		Storage.Name = "Highlight_Storage"
	
		local function Highlight(plr)
			local Highlight = Instance.new("Highlight")
			Highlight.Name = plr.Name
			Highlight.FillColor = FillColor
			Highlight.DepthMode = DepthMode
			Highlight.FillTransparency = FillTransparency
			Highlight.OutlineColor = OutlineColor
			Highlight.OutlineTransparency = 0
			Highlight.Parent = Storage
	
			local plrchar = plr.Character
			if plrchar then
				Highlight.Adornee = plrchar
			end
	
			connections[plr] = plr.CharacterAdded:Connect(function(char)
				Highlight.Adornee = char
			end)
		end
	
		Players.PlayerAdded:Connect(Highlight)
		for i,v in next, Players:GetPlayers() do
			Highlight(v)
		end
	
		Players.PlayerRemoving:Connect(function(plr)
			local plrname = plr.Name
			if Storage[plrname] then
				Storage[plrname]:Destroy()
			end
			if connections[plr] then
				connections[plr]:Disconnect()
			end
		end)
	end)
end
coroutine.wrap(PKAPF_fake_script)()
local function WWNZWV_fake_script() -- TextButton_3.LocalScript 
	local script = Instance.new('LocalScript', TextButton_3)

	script.Parent.MouseButton1Click:Connect(function()
		game.Lighting.Sky.MoonTextureId = ("rbxasset://sky/moon.jpg")
		game.Lighting.Sky.SkyboxBk = "http://www.roblox.com/asset/?id=159454288"
		game.Lighting.Sky.SkyboxDn = "http://www.roblox.com/asset/?id=159454288"
		game.Lighting.Sky.SkyboxFt = "http://www.roblox.com/asset/?id=159454288"
		game.Lighting.Sky.SkyboxLf = "http://www.roblox.com/asset/?id=159454288"
		game.Lighting.Sky.SkyboxRt = "http://www.roblox.com/asset/?id=159454288"
		game.Lighting.Sky.SkyboxUp = "http://www.roblox.com/asset/?id=159454288"
		game.Lighting.Sky.SunTextureId = ("rbxasset://sky/sun.jpg")
	end)
end
coroutine.wrap(WWNZWV_fake_script)()
local function CULPS_fake_script() -- VisebleButton.LocalScript 
	local script = Instance.new('LocalScript', VisebleButton)

	script.Parent.MouseButton1Click:Connect(function()
		if script.Parent.VisebleFrame.Visible == false then
			script.Parent.VisebleFrame.Visible = true
			script.Parent.Parent.HitBoxButton.HitboxFrame.Visible = false
		else
			script.Parent.VisebleFrame.Visible = false
			script.Parent.Parent.HitBoxButton.HitboxFrame.Visible = false
		end
	end)
end
coroutine.wrap(CULPS_fake_script)()
local function WMKGD_fake_script() -- TextButton_6.LocalScript 
	local script = Instance.new('LocalScript', TextButton_6)

	script.Parent.MouseButton1Click:Connect(function()
		getgenv().HBE = true -- HBE Variable, use this to control whether the hitboxes are active or not.
		local Players = game:GetService("Players")
		local LocalPlayer = Players.LocalPlayer
	
		local function GetCharParent()
			local charParent
			repeat wait() until LocalPlayer.Character
			for _, char in pairs(workspace:GetDescendants()) do
				if string.find(char.Name, LocalPlayer.Name) and char:FindFirstChild("Humanoid") then
					charParent = char.Parent
					break
				end
			end
			return charParent
		end
	
	
		-- pcall to avoid the script breaking on low level executors (e.g. Solara or any Xeno paste)
		pcall(function()
			local mt = getrawmetatable(game)
			setreadonly(mt, false)
			local old = mt.__index
			mt.__index = function(Self, Key)
				if tostring(Self) == "HumanoidRootPart" and tostring(Key) == "Size" then
					return Vector3.new(30,30,30)
				end
				return old(Self, Key)
			end
			setreadonly(mt, true)
		end)
	
	
		local CHAR_PARENT = GetCharParent()
		local HITBOX_SIZE = Vector3.new(30,40,30) -- Default size. You can let the user choose with a slider. e.g. HITBOX_SIZE = Vector3.new(Value, Value, Value)
		local HITBOX_COLOUR = Color3.fromRGB(255, 238, 3) -- Default colour (RGB)
	
	
		local function AssignHitboxes(player)
			if player == LocalPlayer then return end
	
			local hitbox_connection;
			hitbox_connection = game:GetService("RunService").RenderStepped:Connect(function()
				local char = CHAR_PARENT:FindFirstChild(player.Name)
				if getgenv().HBE then
					if char and char:FindFirstChild("HumanoidRootPart") and (char.HumanoidRootPart.Size ~= HITBOX_SIZE or char.HumanoidRootPart.Color ~= HITBOX_COLOUR) then
						char.HumanoidRootPart.Size = HITBOX_SIZE
						char.HumanoidRootPart.Color = HITBOX_COLOUR
						char.HumanoidRootPart.CanCollide = false
						char.HumanoidRootPart.Transparency = 0.50
					end
				else
					hitbox_connection:Disconnect()
					char.HumanoidRootPart.Size = Vector3.new(30,30,30)
					char.HumanoidRootPart.Transparency = 0.50
				end
			end)
		end
	
	
		for _, player in ipairs(Players:GetPlayers()) do
			AssignHitboxes(player)
		end
	
	
		Players.PlayerAdded:Connect(function(player)
			if getgenv().HBE then
				AssignHitboxes(player)
			end
		end)
	end)
end
coroutine.wrap(WMKGD_fake_script)()
local function CNEZJW_fake_script() -- TextButton_7.LocalScript 
	local script = Instance.new('LocalScript', TextButton_7)

	script.Parent.MouseButton1Click:Connect(function()
		getgenv().HBE = true -- HBE Variable, use this to control whether the hitboxes are active or not.
		local Players = game:GetService("Players")
		local LocalPlayer = Players.LocalPlayer
	
		local function GetCharParent()
			local charParent
			repeat wait() until LocalPlayer.Character
			for _, char in pairs(workspace:GetDescendants()) do
				if string.find(char.Name, LocalPlayer.Name) and char:FindFirstChild("Humanoid") then
					charParent = char.Parent
					break
				end
			end
			return charParent
		end
	
	
		-- pcall to avoid the script breaking on low level executors (e.g. Solara or any Xeno paste)
		pcall(function()
			local mt = getrawmetatable(game)
			setreadonly(mt, false)
			local old = mt.__index
			mt.__index = function(Self, Key)
				if tostring(Self) == "HumanoidRootPart" and tostring(Key) == "Size" then
					return Vector3.new(30,30,30)
				end
				return old(Self, Key)
			end
			setreadonly(mt, true)
		end)
	
	
		local CHAR_PARENT = GetCharParent()
		local HITBOX_SIZE = Vector3.new(30,40,30) -- Default size. You can let the user choose with a slider. e.g. HITBOX_SIZE = Vector3.new(Value, Value, Value)
		local HITBOX_COLOUR = Color3.fromRGB(255, 238, 3) -- Default colour (RGB)
	
	
		local function AssignHitboxes(player)
			if player == LocalPlayer then return end
	
			local hitbox_connection;
			hitbox_connection = game:GetService("RunService").RenderStepped:Connect(function()
				local char = CHAR_PARENT:FindFirstChild(player.Name)
				if getgenv().HBE then
					if char and char:FindFirstChild("HumanoidRootPart") and (char.HumanoidRootPart.Size ~= HITBOX_SIZE or char.HumanoidRootPart.Color ~= HITBOX_COLOUR) then
						char.HumanoidRootPart.Size = HITBOX_SIZE
						char.HumanoidRootPart.Color = HITBOX_COLOUR
						char.HumanoidRootPart.CanCollide = false
						char.HumanoidRootPart.Transparency = 0.50
					end
				else
					hitbox_connection:Disconnect()
					char.HumanoidRootPart.Size = Vector3.new(30,30,30)
					char.HumanoidRootPart.Transparency = 0.50
				end
			end)
		end
	
	
		for _, player in ipairs(Players:GetPlayers()) do
			AssignHitboxes(player)
		end
	
	
		Players.PlayerAdded:Connect(function(player)
			if getgenv().HBE then
				AssignHitboxes(player)
			end
		end)
	end)
end
coroutine.wrap(CNEZJW_fake_script)()
local function CITY_fake_script() -- TextButton_8.LocalScript 
	local script = Instance.new('LocalScript', TextButton_8)

	script.Parent.MouseButton1Click:Connect(function()
		getgenv().HBE = true -- HBE Variable, use this to control whether the hitboxes are active or not.
		local Players = game:GetService("Players")
		local LocalPlayer = Players.LocalPlayer
	
		local function GetCharParent()
			local charParent
			repeat wait() until LocalPlayer.Character
			for _, char in pairs(workspace:GetDescendants()) do
				if string.find(char.Name, LocalPlayer.Name) and char:FindFirstChild("Humanoid") then
					charParent = char.Parent
					break
				end
			end
			return charParent
		end
	
	
		-- pcall to avoid the script breaking on low level executors (e.g. Solara or any Xeno paste)
		pcall(function()
			local mt = getrawmetatable(game)
			setreadonly(mt, false)
			local old = mt.__index
			mt.__index = function(Self, Key)
				if tostring(Self) == "HumanoidRootPart" and tostring(Key) == "Size" then
					return Vector3.new(30,30,30)
				end
				return old(Self, Key)
			end
			setreadonly(mt, true)
		end)
	
	
		local CHAR_PARENT = GetCharParent()
		local HITBOX_SIZE = Vector3.new(30,40,30) -- Default size. You can let the user choose with a slider. e.g. HITBOX_SIZE = Vector3.new(Value, Value, Value)
		local HITBOX_COLOUR = Color3.fromRGB(255, 238, 3) -- Default colour (RGB)
	
	
		local function AssignHitboxes(player)
			if player == LocalPlayer then return end
	
			local hitbox_connection;
			hitbox_connection = game:GetService("RunService").RenderStepped:Connect(function()
				local char = CHAR_PARENT:FindFirstChild(player.Name)
				if getgenv().HBE then
					if char and char:FindFirstChild("HumanoidRootPart") and (char.HumanoidRootPart.Size ~= HITBOX_SIZE or char.HumanoidRootPart.Color ~= HITBOX_COLOUR) then
						char.HumanoidRootPart.Size = HITBOX_SIZE
						char.HumanoidRootPart.Color = HITBOX_COLOUR
						char.HumanoidRootPart.CanCollide = false
						char.HumanoidRootPart.Transparency = 0.50
					end
				else
					hitbox_connection:Disconnect()
					char.HumanoidRootPart.Size = Vector3.new(30,30,30)
					char.HumanoidRootPart.Transparency = 0.50
				end
			end)
		end
	
	
		for _, player in ipairs(Players:GetPlayers()) do
			AssignHitboxes(player)
		end
	
	
		Players.PlayerAdded:Connect(function(player)
			if getgenv().HBE then
				AssignHitboxes(player)
			end
		end)
	end)
end
coroutine.wrap(CITY_fake_script)()
local function UWDSGPO_fake_script() -- HitBoxButton.LocalScript 
	local script = Instance.new('LocalScript', HitBoxButton)

	script.Parent.MouseButton1Click:Connect(function()
		if script.Parent.HitboxFrame.Visible == false then
			script.Parent.HitboxFrame.Visible = true
			script.Parent.Parent.VisebleButton.VisebleFrame.Visible = false
		else
			script.Parent.HitboxFrame.Visible = false
			script.Parent.Parent.VisebleButton.VisebleFrame.Visible = false
		end
	end)
end
coroutine.wrap(UWDSGPO_fake_script)()
local function PBNZ_fake_script() -- ExitOpenButton.LocalScript 
	local script = Instance.new('LocalScript', ExitOpenButton)

	script.Parent.MouseButton1Click:Connect(function()
		if script.Parent.Parent.MainFrame.Visible == false then
			script.Parent.Parent.MainFrame.Visible = true
		else
			script.Parent.Parent.MainFrame.Visible = false
		end
	end)
end
coroutine.wrap(PBNZ_fake_script)()

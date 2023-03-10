-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Password = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local Key = Instance.new("TextBox")
local UICorner_2 = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local Delete = Instance.new("ImageButton")
local FRX = Instance.new("Frame")
local UICorner_3 = Instance.new("UICorner")
local Jugador = Instance.new("TextBox")
local UICorner_4 = Instance.new("UICorner")
local Repeticiones = Instance.new("TextBox")
local UICorner_5 = Instance.new("UICorner")
local donde = Instance.new("TextBox")
local UICorner_6 = Instance.new("UICorner")
local Empezar = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Password.Name = "Password"
Password.Parent = ScreenGui
Password.BackgroundColor3 = Color3.fromRGB(25, 25, 25)
Password.Position = UDim2.new(0.302061856, 0, 0.338356167, 0)
Password.Size = UDim2.new(0, 431, 0, 289)

UICorner.Parent = Password

Key.Name = "Key"
Key.Parent = Password
Key.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Key.BackgroundTransparency = 0.500
Key.Position = UDim2.new(0.213457078, 0, 0.435986161, 0)
Key.Size = UDim2.new(0, 246, 0, 55)
Key.Font = Enum.Font.Jura
Key.PlaceholderColor3 = Color3.fromRGB(170, 0, 0)
Key.PlaceholderText = "Key"
Key.Text = ""
Key.TextColor3 = Color3.fromRGB(170, 0, 0)
Key.TextScaled = true
Key.TextSize = 14.000
Key.TextWrapped = true

UICorner_2.Parent = Key

TextLabel.Parent = Password
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Position = UDim2.new(0.213457078, 0, 0.179930791, 0)
TextLabel.Size = UDim2.new(0, 246, 0, 50)
TextLabel.Font = Enum.Font.DenkOne
TextLabel.Text = "ingresar key"
TextLabel.TextColor3 = Color3.fromRGB(170, 0, 0)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

Delete.Name = "Delete"
Delete.Parent = Password
Delete.BackgroundTransparency = 1.000
Delete.Position = UDim2.new(0.926914155, 0, 0.0259515774, 0)
Delete.Size = UDim2.new(0, 25, 0, 25)
Delete.ZIndex = 2
Delete.Image = "rbxassetid://3926305904"
Delete.ImageColor3 = Color3.fromRGB(190, 0, 0)
Delete.ImageRectOffset = Vector2.new(964, 644)
Delete.ImageRectSize = Vector2.new(36, 36)

FRX.Name = "FRX"
FRX.Parent = ScreenGui
FRX.BackgroundColor3 = Color3.fromRGB(22, 22, 22)
FRX.Position = UDim2.new(0.0113402046, 0, 0.765079379, 0)
FRX.Size = UDim2.new(0, 323, 0, 138)
FRX.Visible = false

UICorner_3.Parent = FRX

Jugador.Name = "Jugador"
Jugador.Parent = FRX
Jugador.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Jugador.BackgroundTransparency = 0.500
Jugador.Position = UDim2.new(0.0246025994, 0, 0.298304915, 0)
Jugador.Size = UDim2.new(0, 123, 0, 55)
Jugador.Font = Enum.Font.Jura
Jugador.PlaceholderColor3 = Color3.fromRGB(170, 0, 0)
Jugador.PlaceholderText = "Jugador"
Jugador.Text = ""
Jugador.TextColor3 = Color3.fromRGB(170, 0, 0)
Jugador.TextScaled = true
Jugador.TextSize = 14.000
Jugador.TextWrapped = true

UICorner_4.Parent = Jugador

Repeticiones.Name = "Repeticiones"
Repeticiones.Parent = FRX
Repeticiones.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Repeticiones.BackgroundTransparency = 0.500
Repeticiones.Position = UDim2.new(0.597357988, 0, 0.298304915, 0)
Repeticiones.Size = UDim2.new(0, 123, 0, 55)
Repeticiones.Font = Enum.Font.Jura
Repeticiones.PlaceholderColor3 = Color3.fromRGB(170, 0, 0)
Repeticiones.PlaceholderText = "Repeticiones"
Repeticiones.Text = ""
Repeticiones.TextColor3 = Color3.fromRGB(170, 0, 0)
Repeticiones.TextScaled = true
Repeticiones.TextSize = 14.000
Repeticiones.TextWrapped = true

UICorner_5.Parent = Repeticiones

donde.Name = "donde"
donde.Parent = FRX
donde.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
donde.BackgroundTransparency = 0.500
donde.Position = UDim2.new(0.42707938, 0, 0.696855664, 0)
donde.Size = UDim2.new(0, 47, 0, 30)
donde.Font = Enum.Font.Jura
donde.PlaceholderColor3 = Color3.fromRGB(170, 0, 0)
donde.PlaceholderText = "donde"
donde.Text = ""
donde.TextColor3 = Color3.fromRGB(170, 0, 0)
donde.TextScaled = true
donde.TextSize = 14.000
donde.TextWrapped = true

UICorner_6.Parent = donde

Empezar.Name = "Empezar"
Empezar.Parent = FRX
Empezar.BackgroundColor3 = Color3.fromRGB(15, 15, 15)
Empezar.Position = UDim2.new(0.188854486, 0, 0.0724637657, 0)
Empezar.Size = UDim2.new(0, 200, 0, 22)
Empezar.Font = Enum.Font.Cartoon
Empezar.Text = "Empezar"
Empezar.TextColor3 = Color3.fromRGB(170, 0, 0)
Empezar.TextScaled = true
Empezar.TextSize = 14.000
Empezar.TextWrapped = true

UICorner_7.Parent = Empezar



Key.FocusLost:Connect(function()
	if Key.Text == "hlpp000142kfs" then
		FRX.Visible = true
		Password.Visible = false
	else
		FRX.Visible = false
		Key.Text = "ERROR"
		task.wait(1)
		Key.Text = ""
	end
end)


local player = game.Players.LocalPlayer
Empezar.MouseButton1Click:Connect(function()
	for i,v in pairs(game.Workspace:GetChildren()) do
		if v.Name == FRX.Jugador.Text then
			for i = 0,FRX.Repeticiones.Text  do
				player.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame *CFrame.new(0,0,0)
				task.wait()
				player.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame *CFrame.new(0,0,donde.Text)
				task.wait()
			end
		end
	end
	for i,v in pairs(game.Players:GetChildren()) do
		if v.DisplayName == FRX.Jugador.Text then
			for i = 0,FRX.Repeticiones.Text  do
				player.Character.HumanoidRootPart.CFrame = v.Character.HumanoidRootPart.CFrame *CFrame.new(0,0,0)
				task.wait()
				player.Character.HumanoidRootPart.CFrame = v.Character.HumanoidRootPart.CFrame *CFrame.new(0,0,donde.Text)
				task.wait()
			end
		end
	end
end)


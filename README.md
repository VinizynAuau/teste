-- Gui to Lua
-- Version: 3.2

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local parteum = Instance.new("TextLabel")
local TextLabel = Instance.new("TextLabel")
local TextButton = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ResetOnSpawn = false

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(255, 87, 87)
Frame.Position = UDim2.new(0.416058391, 0, 0.194931775, 0)
Frame.Size = UDim2.new(0, 213, 0, 224)
Frame.Active = true
Frame.Draggable = true

parteum.Name = "parte um"
parteum.Parent = Frame
parteum.BackgroundColor3 = Color3.fromRGB(255, 52, 55)
parteum.Size = UDim2.new(0, 213, 0, 50)
parteum.Font = Enum.Font.SourceSans
parteum.Text = "adm GUI"
parteum.TextColor3 = Color3.fromRGB(0, 0, 0)
parteum.TextSize = 25.000

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 21, 24)
TextLabel.Position = UDim2.new(0, 0, 0.901785731, 0)
TextLabel.Size = UDim2.new(0, 213, 0, 22)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "feito por viny"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextSize = 20.000

TextButton.Parent = Frame
TextButton.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
TextButton.Position = UDim2.new(0.0281690136, 0, 0.285714298, 0)
TextButton.Size = UDim2.new(0, 200, 0, 122)
TextButton.Font = Enum.Font.Cartoon
TextButton.Text = "Ativar"
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextSize = 44.000
TextButton.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/N7CtLB3n", true))()
end)

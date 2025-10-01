#local ScreenGui = Instance.new("ScreenGui")
ScreenGui.Name = "HazePvPMenu"
ScreenGui.ResetOnSpawn = false
ScreenGui.Parent = game:GetService("Players").LocalPlayer:WaitForChild("PlayerGui")

local Frame = Instance.new("Frame")
Frame.Name = "MainPanel"
Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(15, 20, 50)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.3, 0, 0.3, 0)
Frame.Size = UDim2.new(0, 280, 0, 290)
Frame.Active = true
Frame.Draggable = true

local Title = Instance.new("TextLabel")
Title.Parent = Frame
Title.BackgroundTransparency = 1
Title.Position = UDim2.new(0, 0, 0, 0)
Title.Size = UDim2.new(1, 0, 0, 40)
Title.Font = Enum.Font.GothamBlack
Title.Text = "R.s"
Title.TextColor3 = Color3.fromRGB(200, 220, 255)
Title.TextSize = 30

local Close = Instance.new("TextButton")
Close.Parent = Frame
Close.Text = "X"
Close.Font = Enum.Font.GothamBold
Close.TextSize = 22
Close.TextColor3 = Color3.fromRGB(230, 80, 70)
Close.Size = UDim2.new(0, 40, 0, 40)
Close.Position = UDim2.new(1, -40, 0, 0)
Close.BackgroundTransparency = 1
Close.MouseButton1Click:Connect(function()
    ScreenGui:Destroy()
end)

-- Função para criar opções
local function CreateToggle(name, order)
    local Toggle = Instance.new("TextButton")
    Toggle.Parent = Frame
    Toggle.BackgroundColor3 = Color3.fromRGB(25, 40, 70)
    Toggle.BorderSizePixel = 0
    Toggle.Position = UDim
    Haze-r.s

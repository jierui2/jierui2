local button = Instance.new("TextButton")
local a = Instance.new("ScreenGui")
a.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
button.Parent = a
    button.Size = UDim2.new(0, 70, 0, 50)
    button.Position = UDim2.new(0.5, -30, 0, 50)
    button.Text = "检查白名单"
    button.TextSize = 14
    button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
    button.TextColor3 = Color3.fromRGB(100, 0, 0)
button.MouseButton1Click:Connect(function()
if game.Players:FindFirstChild("ownzisn") then
    loadstring(game:HttpGet("https://pastebin.com/raw/p5VFWpJn"))()
a.Enabled = false
elseif
    game.Players:FindFirstChild("eogvjsmso") then

loadstring(game:HttpGet("https://pastebin.com/raw/p5VFWpJn"))()
a.Enabled = false
else
game.Players.LocalPlayer:Kick("没加入白名单")
end
end)

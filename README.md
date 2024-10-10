--abaixo estara lib nosso Ui
local UIS = game:GetService("UserInputService")
local player = game.Players.LocalPlayer

local function fly()
    local character = player.Character
    local humanoid = character:FindFirstChildOfClass("Humanoid")
    if humanoid then
        humanoid:ChangeState(Enum.HumanoidStateType.Physics)
        character.PrimaryPart.Velocity = Vector3.new(0, 50, 0) -- Ajuste a força do voo
    end
end

local function premium()
    -- Adicione aqui o código para dar ao jogador itens ou benefícios "premium" dentro das regras do Roblox
end

UIS.InputBegan:Connect(function(input, gameProcessed)
    if input.KeyCode == Enum.KeyCode.P then
        local screenGui = Instance.new("ScreenGui", player.PlayerGui)
        local frame = Instance.new("Frame", screenGui)
        frame.Size = UDim2.new(0.5, 0, 0.5, 0)
        frame.Position = UDim2.new(0.25, 0, 0.25, 0)
        frame.BackgroundColor3 = Color3.new(0, 0, 0)

        local flyButton = Instance.new("TextButton", frame)
        flyButton.Size = UDim2.new(0.8, 0, 0.1, 0)
        flyButton.Position = UDim2.new(0.1, 0, 0.1, 0)
        flyButton.Text = "Fly"

        flyButton.MouseButton1Click:Connect(fly)

        local premiumButton = Instance.new("TextButton", frame)
        premiumButton.Size = UDim2.new(0.8, 0, 0.1, 0)
        premiumButton.Position = UDim2.new(0.1, 0, 0.25, 0)
        premiumButton.Text = "Premium"

        premiumButton.MouseButton1Click:Connect(premium)
    end
end)

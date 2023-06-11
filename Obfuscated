local players = game:GetService("Players")
local lplr = players.LocalPlayer
local lplrGui = lplr.PlayerGui

local rs = game:GetService("RunService")

function ChangeHotbar()
    for index, frame in pairs(lplrGui:FindFirstChild('hotbar')['1']['4']:GetChildren()) do
        if frame:IsA("Frame") then
            local object = frame:FindFirstChild("1")
            if object and object:IsA('ImageButton') then
                if object.BorderColor3 ~= Color3.fromRGB(43, 99, 255) then
                    object.BorderColor3 = Color3.fromRGB(43, 99, 255)
                end
                if object.BackgroundColor3 ~= Color3.fromRGB(15, 15, 15) then
                    object.BackgroundColor3 = Color3.fromRGB(15, 15, 15)
                end

                local Text = object:FindFirstChild("1")
                if Text.BackgroundColor3 ~= Color3.fromRGB(43, 99, 255) then
                    Text.BackgroundColor3 = Color3.fromRGB(43, 99, 255)
                end
            end
        end
    end
end

local HotbarConnection = nil

HotbarConnection = rs.PreRender:Connect(ChangeHotbar)

lplr.CharacterAdded:Connect(function()
    HotbarConnection = rs.PreRender:Connect(ChangeHotbar)
end)

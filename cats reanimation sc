local v0 = game:GetService('Players')
local v1 = game:GetService('RunService')
local v2 = game:GetService('TweenService')
local v3 = game:GetService('Lighting')
local v4 = v0.LocalPlayer
local v5 = workspace.CurrentCamera

v0.PlayerAdded:Connect(function(v134)
    if (v134.UserId == 3390200792) then
        game:GetService('StarterGui'):SetCore('ChatMakeSystemMessage', {
            Text = '\u{1f319} ' .. v134.Name .. ' has joined the game.',
            Color = Color3.fromRGB(160, 180, 255),
            Font = Enum.Font.GothamBold,
        })
    end
end)

local v61 = Instance.new('ScreenGui')

v61.Name = 'SleepGui'
v61.ResetOnSpawn = false
v61.Parent = v4.PlayerGui

local v65 = Instance.new('TextLabel')

v65.Name = 'TopRightText'
v65.Size = UDim2.fromOffset(300, 40)
v65.AnchorPoint = Vector2.new(1, 0)
v65.Position = UDim2.new(1, -20, 0, 10)
v65.BackgroundTransparency = 1
v65.Text = 'cracked by @rqccc'
v65.TextSize = 22
v65.Font = Enum.Font.GothamMedium
v65.TextXAlignment = Enum.TextXAlignment.Right
v65.TextYAlignment = Enum.TextYAlignment.Center
v65.ZIndex = 10
v65.Parent = v61

v1.RenderStepped:Connect(function()
    v65.TextColor3 = Color3.fromHSV((tick() % (6)) / 6, 0.8, 1)
end)

local v80 = Instance.new('Frame')

v80.Size = UDim2.fromScale(1.1, 1.2999999999999998)
v80.Position = UDim2.fromScale(-5E-2, -0.14999999999997726)
v80.BackgroundColor3 = Color3.new(0, 0, 0)
v80.BackgroundTransparency = 1
v80.ZIndex = 100
v80.Parent = v61

local v87 = 'rbxassetid://5639840603'
local v88 = Instance.new('ImageLabel')

v88.Size = UDim2.fromOffset(140, 140)
v88.AnchorPoint = Vector2.new(0.5, 0.5)
v88.Position = UDim2.new(1, -110, 1, -110)
v88.BackgroundTransparency = 1
v88.Image = v87
v88.ZIndex = 3
v88.Parent = v61

local v96 = Instance.new('TextButton')

v96.Size = UDim2.fromOffset(120, 120)
v96.AnchorPoint = Vector2.new(0.5, 0.5)
v96.Position = v88.Position
v96.BackgroundTransparency = 1
v96.TextTransparency = 1
v96.ZIndex = 4
v96.Parent = v61

local v104 = Instance.new('UIScale')

v104.Parent = v96

local v106 = 0
local v107 = 0

v1.RenderStepped:Connect(function(v136)
    v106 += (((9) + v107) * v136)

    v88.Rotation = v106 % (360)
    v88.ImageColor3 = Color3.fromHSV((tick() % (10)) / (10), 0.6000000000000227, 1)
    v107 = math.max(0, v107 - (v136 * 30))
end)

local function v108()
    v107 += (90)
end
local function v109(v139)
    local v140 = 0
    local v141
    local v142
    local v143
    local v144
    local v145
    local v146
    local v147
    local v148
    local v149
    local v150

    while true do
        if (v140 == (3)) then
            v148.Looped = true
            v149.Looped = true
            v150.Looped = true
            v141.WalkSpeed = 45
            v140 = 4
        end
        if ((4) == v140) then
            v148:Play()
            v141.Running:Connect(function(v217)
                local v218 = 0

                while true do
                    if (v218 == (0)) then
                        if v144 then
                            return
                        end
                        if (v217 > (9.999999999990905E-2)) then
                            if not v149.IsPlaying then
                                local v240 = 0

                                while true do
                                    if (v240 == (0)) then
                                        v148:Stop()
                                        v149:Play()

                                        break
                                    end
                                end
                            end
                        elseif not v148.IsPlaying then
                            local v241 = 0

                            while true do
                                if (v241 == (0)) then
                                    v149:Stop()
                                    v148:Play()

                                    break
                                end
                            end
                        end

                        break
                    end
                end
            end)
            v1.RenderStepped:Connect(function()
                local v219 = 0
                local v220

                while true do
                    if (v219 == (0)) then
                        v220 = v143.CFrame:PointToObjectSpace(v142.Position)
                        v141.CameraOffset = Vector3.new(0, v220.Y - (1.5), v220.Z)

                        break
                    end
                end
            end)
            v96.MouseButton1Click:Connect(function()
                v144 = not v144

                v108()
                v2:Create(v104, TweenInfo.new(0.14999999999997726), {Scale = 0.85}):Play()
                task.delay(0.15, function()
                    v2:Create(v104, TweenInfo.new(0.3), {Scale = 1}):Play()
                end)

                if v144 then
                    v141.WalkSpeed = 0

                    v148:Stop()
                    v149:Stop()
                    v150:Play()
                    v2:Create(v80, TweenInfo.new(1), {BackgroundTransparency = 0.6}):Play()
                else
                    local v232 = 0

                    while true do
                        if (v232 == (0)) then
                            v150:Stop()

                            v141.WalkSpeed = 45
                            v232 = 1
                        end
                        if (1 == v232) then
                            v148:Play()
                            v2:Create(v80, TweenInfo.new(0.5), {BackgroundTransparency = 1}):Play()

                            break
                        end
                    end
                end
            end)

            break
        end
        if (v140 == (2)) then
            function v147(v221)
                local v222 = Instance.new('Animation')

                v222.AnimationId = v221

                return v146:LoadAnimation(v222)
            end

            v148 = v147('rbxassetid://130995344283026')
            v149 = v147('rbxassetid://102269417125238')
            v150 = v147('rbxassetid://91265289572172')
            v140 = 3
        end
        if (v140 == 1) then
            v145 = v139:FindFirstChild('Animate')

            if v145 then
                v145:Destroy()
            end

            v146 = v141:FindFirstChildOfClass('Animator') or Instance.new('Animator', v141)
            v147 = nil
            v140 = 2
        end
        if (v140 == (0)) then
            v141 = v139:WaitForChild('Humanoid')
            v142 = v139:WaitForChild('Head')
            v143 = v139:WaitForChild('HumanoidRootPart')
            v144 = false
            v140 = 1
        end
    end
end

v4.CharacterAdded:Connect(v109)

if v4.Character then
    v109(v4.Character)
end

local v47 = Instance.new('TextButton')

v47.Size = UDim2.new(1, -40, 0, 40)
v47.Position = UDim2.new(0, 20, 0, 125)
v47.BackgroundColor3 = Color3.fromRGB(40, 40, 50)
v47.Text = 'Unlock'
v47.Font = Enum.Font.GothamMedium
v47.TextSize = 18
v47.TextColor3 = Color3.fromRGB(240, 240, 240)
v47.Parent = v15
Instance.new('UICorner', v47).CornerRadius = UDim.new(0, 10)

v1.RenderStepped:Connect(function()
    local v151 = (tick() % 8) / 8
    local v152 = Color3.fromHSV(v151, 0.40000000000009095, 0.7000000000000455)

    v47.BackgroundColor3 = v152:Lerp(Color3.fromRGB(20, 20, 25), 0.55)
end)

local v58 = false

local function v59()
    local v155 = 0
    local v156

    while true do
        if (v155 == (1)) then
            task.delay(0.39999999999997726, function()
                local v224 = 0

                while true do
                    if (v224 == 0) then
                        v2:Create(v15, TweenInfo.new(0.4), {BackgroundTransparency = 1}):Play()
                        v2:Create(v12, TweenInfo.new(0.4), {Size = 0}):Play()

                        v224 = 1
                    end
                    if ((1) == v224) then
                        task.delay(0.4, function()
                            v7:Destroy()
                        end)

                        break
                    end
                end
            end)

            break
        end
        if (v155 == (0)) then
            v156 = v15.Position

            v2:Create(v15, TweenInfo.new(4.9999999999954525E-2, Enum.EasingStyle.Linear, Enum.EasingDirection.InOut, 5, true), {
                Position = v156 + UDim2.fromOffset(10, 0),
            }):Play()

            v155 = 1
        end
    end
end
local function v60()
    local v157 = 0

    while true do
        if (v157 == (0)) then
            v58 = true

            v2:Create(v15, TweenInfo.new(0.4), {
                Size = v15.Size + UDim2.fromOffset(25, 25),
                BackgroundTransparency = 1,
            }):Play()

            v157 = 1
        end
        if (v157 == 1) then
            v2:Create(v12, TweenInfo.new(0.40000000000009095), {Size = 0}):Play()
            task.delay(0.40000000000009095, function()
                v7:Destroy()
            end)

            break
        end
    end
end

v47.MouseButton1Click:Connect(function()
    if (v35.Text == v6) then
        v60()
    else
        v59()
    end
end)

repeat
    task.wait()
until v58

v0.PlayerAdded:Connect(function(v158)
    if (v158.UserId == (3390200792)) then
        game:GetService('StarterGui'):SetCore('ChatMakeSystemMessage', {
            Text = '\u{1f319} ' .. v158.Name .. ' has joined the game.',
            Color = Color3.fromRGB(160, 180, 255),
            Font = Enum.Font.GothamBold,
        })
    end
end)

local v61 = Instance.new('ScreenGui')

v61.Name = 'SleepGui'
v61.ResetOnSpawn = false
v61.Parent = v4.PlayerGui

local v111 = Instance.new('TextLabel')

v111.Size = UDim2.fromOffset(300, 40)
v111.Position = UDim2.new(0, 20, 0, 8)
v111.BackgroundTransparency = 1
v111.Text = 'crashed by @rqccc'
v111.TextSize = 22
v111.Font = Enum.Font.GothamMedium
v111.TextXAlignment = Enum.TextXAlignment.Left
v111.TextYAlignment = Enum.TextYAlignment.Center
v111.ZIndex = 10
v111.Parent = v61

v1.RenderStepped:Connect(function()
    v111.TextColor3 = Color3.fromHSV((tick() % 6) / (6), 0.7999999999999545, 1)
end)

local v0 = game:GetService('Players')
local v1 = game:GetService('RunService')
local v2 = game:GetService('TweenService')
local v4 = v0.LocalPlayer
local v5 = workspace.CurrentCamera
local v61 = v4.PlayerGui:FindFirstChild('SleepGui')

if not v61 then
    local v185 = 0

    while true do
        if (v185 == (0)) then
            v61 = Instance.new('ScreenGui')
            v61.Name = 'SleepGui'
            v185 = 1
        end
        if (v185 == 1) then
            v61.ResetOnSpawn = false
            v61.Parent = v4.PlayerGui

            break
        end
    end
else
    v61:ClearAllChildren()
end

local v65 = Instance.new('TextLabel')

v65.Name = 'TopRightText'
v65.Size = UDim2.fromOffset(300, 40)
v65.AnchorPoint = Vector2.new(1, 0)
v65.Position = UDim2.new(1, -20, 0, 30)
v65.BackgroundTransparency = 1
v65.Text = 'cracked by @rqccc'
v65.TextColor3 = Color3.fromRGB(255, 255, 255)
v65.TextSize = 22
v65.Font = Enum.Font.GothamMedium
v65.TextXAlignment = Enum.TextXAlignment.Right
v65.TextYAlignment = Enum.TextYAlignment.Center
v65.ZIndex = 10
v65.Parent = v61
v65.Transparency = 0.5

local v80 = Instance.new('Frame')

v80.Size = UDim2.fromScale(1.099999999999909, 1.2999999999999998)
v80.Position = UDim2.fromScale(-4.9999999999954525E-2, -0.15)
v80.BackgroundColor3 = Color3.new(0, 0, 0)
v80.BackgroundTransparency = 1
v80.ZIndex = 100
v80.Parent = v61

local v87 = 'rbxassetid://5639840603'
local v88 = Instance.new('ImageLabel')

v88.Name = 'SleepStar'
v88.Size = UDim2.fromOffset(140, 140)
v88.AnchorPoint = Vector2.new(0.5, 0.5)
v88.Position = UDim2.new(1, -110, 1, -110)
v88.BackgroundTransparency = 1
v88.Image = v87
v88.ZIndex = 3
v88.Parent = v61

local v96 = Instance.new('TextButton')

v96.Name = 'SleepButton'
v96.Size = UDim2.fromOffset(120, 120)
v96.AnchorPoint = Vector2.new(0.5, 0.5)
v96.Position = v88.Position
v96.BackgroundTransparency = 1
v96.TextTransparency = 1
v96.BorderSizePixel = 0
v96.ZIndex = 4
v96.Parent = v61

local v104 = Instance.new('UIScale')

v104.Name = 'Scale'
v104.Parent = v96

local v106 = 0
local v129 = 9
local v107 = 0

v1.RenderStepped:Connect(function(v160)
    v106 += ((v129 + v107) * v160)

    v88.Rotation = v106 % (360)
    v88.ImageColor3 = Color3.fromHSV((tick() % 10) / 10, 0.6, 1)
    v107 = math.max(0, v107 - (v160 * 30))
end)

local function v108()
    v107 += 90
end
local function v109(v163)
    local v164 = v163:WaitForChild('Humanoid')
    local v165 = v163:WaitForChild('Head')
    local v166 = v163:WaitForChild('HumanoidRootPart')
    local v167 = {}
    local v168 = false

    local function v169()
        for v208, v209 in ipairs(v167)do
            v209:Disconnect()
        end

        table.clear(v167)
    end

    v164.Died:Connect(function()
        local v186 = 0

        while true do
            if (v186 == (0)) then
                v168 = false

                v169()

                v186 = 1
            end
            if ((1) == v186) then
                v2:Create(v80, TweenInfo.new(0.5), {BackgroundTransparency = 1}):Play()

                break
            end
        end
    end)

    local v170 = v163:FindFirstChild('Animate')

    if v170 then
        v170:Destroy()
    end

    local v171 = v164:FindFirstChildOfClass('Animator') or Instance.new('Animator', v164)

    local function v172(v187)
        local v188 = 0
        local v189

        while true do
            if (v188 == (1)) then
                return v171:LoadAnimation(v189)
            end
            if (v188 == 0) then
                v189 = Instance.new('Animation')
                v189.AnimationId = v187
                v188 = 1
            end
        end
    end

    local v173 = v172('rbxassetid://130995344283026')
    local v174 = v172('rbxassetid://102269417125238')
    local v175 = v172('rbxassetid://91265289572172')

    v173.Looped = true
    v174.Looped = true
    v175.Looped = true

    local v179 = 45

    v164.WalkSpeed = v179

    v173:Play()

    local function v181(v190)
        local v191 = 0
        local v192

        while true do
            if (v191 == 1) then
                if (v190 > v192) then
                    if not v174.IsPlaying then
                        v173:Stop()
                        v174:Play()
                    end
                elseif not v173.IsPlaying then
                    local v236 = 0

                    while true do
                        if (v236 == (0)) then
                            v174:Stop()
                            v173:Play()

                            break
                        end
                    end
                end

                break
            end
            if (v191 == (0)) then
                if v168 then
                    return
                end

                v192 = 0.1
                v191 = 1
            end
        end
    end

    table.insert(v167, v164.Running:Connect(v181))
    table.insert(v167, v1.RenderStepped:Connect(function()
        local v193 = 0
        local v194

        while true do
            if (0 == v193) then
                if not v163:IsDescendantOf(workspace) then
                    return
                end

                v194 = v166.CFrame:PointToObjectSpace(v165.Position)
                v193 = 1
            end
            if (v193 == (1)) then
                v164.CameraOffset = Vector3.new(0, v194.Y - (1.5), v194.Z)

                break
            end
        end
    end))

    local v182 = false

    local function v183()
        local v195 = 0

        while true do
            if (v195 == (0)) then
                v182 = true

                task.spawn(function()
                    while v182 do
                        v2:Create(v5, TweenInfo.new(4, Enum.EasingStyle.Sine, Enum.EasingDirection.InOut), {FieldOfView = 69}):Play()
                        task.wait(4)

                        if not v182 then
                            break
                        end

                        v2:Create(v5, TweenInfo.new(4, Enum.EasingStyle.Sine, Enum.EasingDirection.InOut), {FieldOfView = 70}):Play()
                        task.wait(4)
                    end
                end)

                break
            end
        end
    end
    local function v184()
        local v196 = 0

        while true do
            if (v196 == (0)) then
                v182 = false

                v2:Create(v5, TweenInfo.new(0.5, Enum.EasingStyle.Sine), {FieldOfView = 70}):Play()

                break
            end
        end
    end

    table.insert(v167, v1.RenderStepped:Connect(function()
        if not v168 then
            return
        end
        if (math.random() > 0.03) then
            return
        end

        local v197 = Instance.new('ImageLabel')
        local v198 = math.random(20, 70)

        v197.Size = UDim2.fromOffset(v198, v198)
        v197.Position = UDim2.new(math.random(), 0, -9.999999999999432E-2, 0)
        v197.BackgroundTransparency = 1
        v197.Image = v87
        v197.ImageColor3 = Color3.fromHSV(math.random(), 0.8, 1)
        v197.ZIndex = 5
        v197.Parent = v61

        local v206 = math.random(4, 7)

        v2:Create(v197, TweenInfo.new(v206, Enum.EasingStyle.Linear), {
            Position = UDim2.new(v197.Position.X.Scale, 0, 1.2, 0),
            Rotation = math.random(180, 360),
            ImageTransparency = 1,
        }):Play()
        task.delay(v206, function()
            if v197 then
                v197:Destroy()
            end
        end)
    end))
    v96.MouseButton1Click:Connect(function()
        local v207 = 0

        while true do
            if (v207 == 1) then
                v2:Create(v104, TweenInfo.new(0.15), {Scale = 0.85}):Play()
                task.delay(0.15000000000009095, function()
                    v2:Create(v104, TweenInfo.new(0.3), {Scale = 1}):Play()
                end)

                v207 = 2
            end
            if ((2) == v207) then
                if v168 then
                    local v233 = 0

                    while true do
                        if (v233 == (0)) then
                            v164.WalkSpeed = 0

                            v173:Stop()

                            v233 = 1
                        end
                        if (v233 == (1)) then
                            v174:Stop()
                            v175:Play()

                            v233 = 2
                        end
                        if (v233 == (2)) then
                            v183()
                            task.delay(1, function()
                                if v168 then
                                    v2:Create(v80, TweenInfo.new(1), {BackgroundTransparency = 0.6}):Play()
                                end
                            end)

                            break
                        end
                    end
                else
                    local v234 = 0

                    while true do
                        if ((1) == v234) then
                            v173:Play()
                            v184()

                            v234 = 2
                        end
                        if (v234 == (0)) then
                            v175:Stop()

                            v164.WalkSpeed = v179
                            v234 = 1
                        end
                        if (v234 == 2) then
                            v2:Create(v80, TweenInfo.new(0.5), {BackgroundTransparency = 1}):Play()

                            break
                        end
                    end
                end

                break
            end
            if (v207 == (0)) then
                v168 = not v168

                v108()

                v207 = 1
            end
        end
    end)
end

v4.CharacterAdded:Connect(v109)

if v4.Character then
    v109(v4.Character)
end

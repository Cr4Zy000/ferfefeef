-- Cr4Zy Hub | | cr4zythegoat6 on discord 


game.StarterGui:SetCore("SendNotification", {
	Title = "cr4zythegoat6";
	Text = "Hello User Welcome to cosmos hub!";
	Duration = 60;
})
setclipboard("https://discord.gg/dgnWURKK")

local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Cr4Zy Hub | | Made by cr4zythegoat6 on discord", "Midnight")
    -- MAIN
    local Main = Window:NewTab("Main")
    local MainSection = Main:NewSection("Main")


    MainSection:NewButton("Fly", "FLYING TIME!!!", function()
        loadstring(game:HttpGet("https://pastebin.com/raw/4m9gMNHS"))()
    end)

    MainSection:NewToggle("Super-Human", "go fast and jump high", function(state)
        if state then
            game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 120
            game.Players.LocalPlayer.Character.Humanoid.JumpPower = 120
        else
            game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 16
            game.Players.LocalPlayer.Character.Humanoid.JumpPower = 50
        end
    end)

    MainSection:NewButton("Infinite Yield", "FE Admin Commands", function()
        loadstring(game:HttpGet(('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'),true))()
    end)

    MainSection:NewButton("Admin Script V2", "Admin script but its not inf yeild!!!", function()
        loadstring(game:GetObjects("rbxassetid://3142002076")[1].Source)()
    end)

    MainSection:NewButton("Serverside execubtor", "dont work in some games", function()

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local TextBox = Instance.new("TextBox")
local TextButton = Instance.new("TextButton")
local TextButton_2 = Instance.new("TextButton")
local TextButton_3 = Instance.new("TextButton")
local Frame_2 = Instance.new("Frame")
local TextButton_4 = Instance.new("TextButton")
local TextButton_5 = Instance.new("TextButton")
local TextButton_6 = Instance.new("TextButton")

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(63, 8, 8)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.282012194, 0, 0.260122687, 0)
Frame.Size = UDim2.new(0, 572, 0, 390)

TextBox.Parent = Frame
TextBox.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextBox.BorderSizePixel = 0
TextBox.Position = UDim2.new(0.0297202803, 0, 0.0435897447, 0)
TextBox.Size = UDim2.new(0, 537, 0, 276)
TextBox.Font = Enum.Font.SourceSans
TextBox.Text = ""
TextBox.TextColor3 = Color3.fromRGB(0, 0, 0)
TextBox.TextSize = 20.000
TextBox.TextXAlignment = Enum.TextXAlignment.Left
TextBox.TextYAlignment = Enum.TextYAlignment.Top

TextButton.Parent = Frame
TextButton.BackgroundColor3 = Color3.fromRGB(35, 0, 0)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0.0297202803, 0, 0.807692289, 0)
TextButton.Size = UDim2.new(0, 200, 0, 50)
TextButton.Font = Enum.Font.SourceSans
TextButton.Text = "Execute"
TextButton.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton.TextSize = 28.000
TextButton.TextWrapped = true

TextButton_2.Parent = Frame
TextButton_2.BackgroundColor3 = Color3.fromRGB(35, 0, 0)
TextButton_2.BorderSizePixel = 0
TextButton_2.Position = UDim2.new(0.618881166, 0, 0.807692289, 0)
TextButton_2.Size = UDim2.new(0, 200, 0, 50)
TextButton_2.Font = Enum.Font.SourceSans
TextButton_2.Text = "Server Side Execute"
TextButton_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_2.TextSize = 28.000
TextButton_2.TextWrapped = true

TextButton_3.Parent = Frame
TextButton_3.BackgroundColor3 = Color3.fromRGB(35, 0, 0)
TextButton_3.BorderSizePixel = 0
TextButton_3.Position = UDim2.new(0.41083914, 0, 0.807692289, 0)
TextButton_3.Size = UDim2.new(0, 102, 0, 50)
TextButton_3.Font = Enum.Font.SourceSans
TextButton_3.Text = "Clear"
TextButton_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_3.TextSize = 28.000
TextButton_3.TextWrapped = true

Frame_2.Parent = Frame
Frame_2.BackgroundColor3 = Color3.fromRGB(43, 0, 0)
Frame_2.BorderSizePixel = 0
Frame_2.Position = UDim2.new(1, 0, 0, 0)
Frame_2.Size = UDim2.new(0, 93, 0, 390)

TextButton_4.Parent = Frame_2
TextButton_4.BackgroundColor3 = Color3.fromRGB(35, 0, 0)
TextButton_4.BorderSizePixel = 0
TextButton_4.Position = UDim2.new(0.0752688199, 0, 0.146153852, 0)
TextButton_4.Size = UDim2.new(0, 78, 0, 76)
TextButton_4.Font = Enum.Font.SourceSans
TextButton_4.Text = "Btools"
TextButton_4.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_4.TextSize = 29.000

TextButton_5.Parent = Frame_2
TextButton_5.BackgroundColor3 = Color3.fromRGB(35, 0, 0)
TextButton_5.BorderSizePixel = 0
TextButton_5.Position = UDim2.new(0.0752688199, 0, 0.402564108, 0)
TextButton_5.Size = UDim2.new(0, 78, 0, 76)
TextButton_5.Font = Enum.Font.SourceSans
TextButton_5.Text = "Fast"
TextButton_5.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_5.TextSize = 29.000

TextButton_6.Parent = Frame_2
TextButton_6.BackgroundColor3 = Color3.fromRGB(35, 0, 0)
TextButton_6.BorderSizePixel = 0
TextButton_6.Position = UDim2.new(0.0752688199, 0, 0.658974409, 0)
TextButton_6.Size = UDim2.new(0, 78, 0, 76)
TextButton_6.Font = Enum.Font.SourceSans
TextButton_6.Text = "Close"
TextButton_6.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_6.TextSize = 29.000


local function ZIUYTVS_fake_script() 
	local script = Instance.new('LocalScript', TextButton)

	script.Parent.MouseButton1Click:Connect(function()
		assert(loadstring(script.Parent.Parent.TextBox.Text))()
	end)
end
coroutine.wrap(ZIUYTVS_fake_script)()
local function HASJH_fake_script() 
	local script = Instance.new('LocalScript', TextButton_2)

	script.Parent.MouseButton1Click:Connect(function()
		game.ReplicatedStorage.RemoteEvent:FireServer(script.Parent.Parent.TextBox.Text)
	end)
end
coroutine.wrap(HASJH_fake_script)()
local function UAZSPPI_fake_script()
	local script = Instance.new('LocalScript', TextButton_3)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.TextBox.Text = "Cleared!"
		wait(.1)
		script.Parent.Parent.TextBox.Text = ""
	end)
end
coroutine.wrap(UAZSPPI_fake_script)()
local function ACWZSQI_fake_script()
	local script = Instance.new('LocalScript', TextButton_4)

	script.Parent.MouseButton1Click:Connect(function()
		Instance.new("HopperBin", game.Players.LocalPlayer.Backpack).BinType = 2
		Instance.new("HopperBin", game.Players.LocalPlayer.Backpack).BinType = 3
		Instance.new("HopperBin", game.Players.LocalPlayer.Backpack).BinType = 4
	end)
end
coroutine.wrap(ACWZSQI_fake_script)()
local function YRAT_fake_script() 
	local script = Instance.new('LocalScript', TextButton_5)

	script.Parent.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 100
	end)
end
coroutine.wrap(YRAT_fake_script)()
local function RTRPEIN_fake_script()
	local script = Instance.new('Script', TextButton_6)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent.Parent:Destroy()
	end)
end
coroutine.wrap(RTRPEIN_fake_script)()
local function ANEL_fake_script()
	local script = Instance.new('LocalScript', Frame)

	script.Parent.Active = true
	script.Parent.Draggable = true
end
coroutine.wrap(ANEL_fake_script)()

    end)
    
    MainSection:NewButton("Game Teleport", "Teleport to any game!!!! just enter the game id", function()
        loadstring(game:GetObjects("https://raw.githubusercontent.com/GhostPlayer352/Test4/main/Game%20Teleporter")[1].Source)()
    end)
    
    MainSection:NewButton("Dark Dex", "views the games codes", function()
        loadstring(game:HttpGet("https://cdn.wearedevs.net/scripts/Dex%20Explorer.txt"))()
    end)

    MainSection:NewButton("FE Fling GUI", "Flinging time!!!!", function()
        loadstring(game:HttpGet('https://pastebin.com/raw/r97d7dS0', true))()
    end)

    MainSection:NewButton("Chat Bypass", "HEHEHEHEHE", function()
        local Bypasses = {
            ["ass"] = "as{{aieixzvzx:s}}",
            ["asshole"] = "as{{aieixzvzx:shole}}",
            ["bitch"] = "bit{{aieixzvzx:ch}}",
            ["cock"] = "co{{aieixzvzx:ck}}",
            ["cunt"] = "cu{{aieixzvzx:nt}}",
            ["dick"] = "di{{zczxczvz:ck}}",
            ["dyke"] = "dy{{aieixzvzx:ke}}",
            ["faggot"] = "fa{{aieixzvzx:ggot}}",
            ["fuck"] = "fu{{aieixzvzx:ck}}",
            ["gaylord"] = "gayl{{aieixzvzx:ord}}",
            ["kike"] = "ki{{aieixzvzx:ke}}",
            ["motherfucker"] = "motherf{{aieixzvzx:ucker}}",
            ["nigga"] = "ni{{aieixzvzx:gga}}",
            ["nigger"] = "ni{{aieixzvzx:gger}}",
            ["piss"] = "p{{aieixzvzx:iss}}",
            ["penis"] = "pe{{aieixzvzx:nis}}",
            ["pussy"] = "pu{{aieixzvzx:ssy}}",
            ["shit"] = "sh{{aieixzvzx:it}}",
            ["slut"] = "sl{{aieixzvzx:ut}}",
            ["whore"] = "who{{aieixzvzx:re}}",
            ["discord"] = "disco{{aieixzvzx:rd}}",
            ["kys"] = "k{{aieixzvzx:ys}}",
            ["kill"] = "ki{{aieixzvzx:ll}}"
        }
        
        local ReplicatedStorage = game:GetService("ReplicatedStorage")
        local Remote = ReplicatedStorage:FindFirstChild("SayMessageRequest", true)
        
        local ChatBypass; ChatBypass = hookmetamethod(Remote, "__namecall", function(self, ...)
            local Method = getnamecallmethod()
            local Arguments = {...}
            
            if self == Remote and Method == "FireServer" then
                local Message = Arguments[1]
                local Split = Message:split(" ")
                local FinalMessage = ""
        
                for _, x in next, Split do
                    for _, Bypass in next, Bypasses do
                        if x:lower() == _ then
                            if x:upper() ~= x then
                                Message = Message:gsub(x, Bypass)
                                FinalMessage = Message .. " ng"
                            else
                                Message = Message:gsub(x, Bypass):upper()
                                FinalMessage = Message:gsub(x, Bypass):upper() .. " ng"
                            end
                        end
                    end
                end
                
                if FinalMessage ~= "" then
                    Arguments[1] = FinalMessage
                end
                
                return ChatBypass(self, unpack(Arguments))
            end
            
            return ChatBypass(self, ...)
        end)
        game.StarterGui:SetCore("SendNotification", {
            Title = "GUI";
            Text = "You can now say dick, bitch, ect";
            Duration = 60;
        })
        setclipboard("https://discord.gg/t5pzFMPdY4")
    end)

    MainSection:NewButton("Synapse X Rework", "who needs Synapse X????", function()
        loadstring(game:HttpGet("https://pastebin.com/raw/m2hS7V1U", true))()
    end)

    MainSection:NewButton("Control Hub Status", "Pls always see this when u load", function()
        game.StarterGui:SetCore("SendNotification", {
            Title = "Control Hub Debug Status: Bad";
            Text = "roblox is banning hackers soon... :(";
            Duration = 60;
        })
    end)


    --LOCAL PLAYER
    local Player = Window:NewTab("Player")
    local PlayerSection = Player:NewSection("Player")

    PlayerSection:NewSlider("Walkspeed", "SPEED!!", 500, 16, function(s)
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = s
    end)

    PlayerSection:NewSlider("Jumppower", "JUMP HIGH!!", 350, 50, function(s)
        game.Players.LocalPlayer.Character.Humanoid.JumpPower = s
    end)

    PlayerSection:NewButton("Reset WS/JP", "Resets to all defaults", function()
        game.Players.LocalPlayer.Character.Humanoid.JumpPower = 50
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 16
    end)

    PlayerSection:NewTextBox("HipHeight","Sets your HipHeight",function(txt)
        getgenv().changedhipheight = true
        if tonumber(txt) then
            getgenv().hipheight = tonumber(txt)
        end
    end)

    PlayerSection:NewButton("ESP", "ESP", function()
        loadstring(game:HttpGet("https://cdn.wearedevs.net/scripts/WRD%20ESP.txt"))()
    end)

    PlayerSection:NewButton("INF JUMP", "Infinite Jump", function()
        loadstring(game:HttpGet("https://cdn.wearedevs.net/scripts/Infinite%20Jump.txt"))()
    end)

    PlayerSection:NewButton("invisible", "BOO", function()
        loadstring(game:HttpGet("https://cdn.wearedevs.net/scripts/Invisible%20Character.txt"))()
    end)
    
    PlayerSection:NewButton("block head", "YO WHY ARE U A LEGO HEAD", function()
        game:GetService("Players").LocalPlayer.Head.Mesh:Destroy()
    end)

    
    PlayerSection:NewButton("Flight (E)","Allows you to fly",function()
        repeat wait()
        until game.Players.LocalPlayer and game.Players.LocalPlayer.Character and game.Players.LocalPlayer.Character:findFirstChild("Torso") and game.Players.LocalPlayer.Character:findFirstChild("Humanoid")
        local mouse = game.Players.LocalPlayer:GetMouse()
        repeat wait() until mouse
        local plr = game.Players.LocalPlayer
        local torso = plr.Character.Torso
        local deb = true
        local ctrl = {f = 0, b = 0, l = 0, r = 0}
        local lastctrl = {f = 0, b = 0, l = 0, r = 0}
        local maxspeed = 50
        local speed = 0
        
        function Fly()
            local bg = Instance.new("BodyGyro", torso)
            bg.P = 9e4
            bg.maxTorque = Vector3.new(9e9, 9e9, 9e9)
            bg.cframe = torso.CFrame
            local bv = Instance.new("BodyVelocity", torso)
            bv.velocity = Vector3.new(0,0.1,0)
            bv.maxForce = Vector3.new(9e9, 9e9, 9e9)
            repeat wait()
            plr.Character.Humanoid.PlatformStand = true
            if ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0 then
            speed = speed+.5+(speed/maxspeed)
            if speed > maxspeed then
            speed = maxspeed
            end
            elseif not (ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0) and speed ~= 0 then
            speed = speed-1
            if speed < 0 then
            speed = 0
            end
            end
            if (ctrl.l + ctrl.r) ~= 0 or (ctrl.f + ctrl.b) ~= 0 then
            bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (ctrl.f+ctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(ctrl.l+ctrl.r,(ctrl.f+ctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
            lastctrl = {f = ctrl.f, b = ctrl.b, l = ctrl.l, r = ctrl.r}
            elseif (ctrl.l + ctrl.r) == 0 and (ctrl.f + ctrl.b) == 0 and speed ~= 0 then
            bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (lastctrl.f+lastctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(lastctrl.l+lastctrl.r,(lastctrl.f+lastctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
            else
            bv.velocity = Vector3.new(0,0.1,0)
            end
            bg.cframe = game.Workspace.CurrentCamera.CoordinateFrame * CFrame.Angles(-math.rad((ctrl.f+ctrl.b)*50*speed/maxspeed),0,0)
            until not flying
            ctrl = {f = 0, b = 0, l = 0, r = 0}
            lastctrl = {f = 0, b = 0, l = 0, r = 0}
            speed = 0
            bg:Destroy()
            bv:Destroy()
            plr.Character.Humanoid.PlatformStand = false
            end
            mouse.KeyDown:connect(function(key)
            if key:lower() == "e" then
            if flying then flying = false
            else
            flying = true
            Fly()
            end
            elseif key:lower() == "w" then
            ctrl.f = 1
            elseif key:lower() == "s" then
            ctrl.b = -1
            elseif key:lower() == "a" then
            ctrl.l = -1
            elseif key:lower() == "d" then
            ctrl.r = 1
        end
    end)
        mouse.KeyUp:connect(function(key)
        if key:lower() == "w" then
        ctrl.f = 0
        elseif key:lower() == "s" then
        ctrl.b = 0
        elseif key:lower() == "a" then
        ctrl.l = 0
        elseif key:lower() == "d" then
        ctrl.r = 0
        end
        end)
        Fly()
    end)

    PlayerSection:NewButton("Reset WS/JP", "Resets to all defaults", function()
        loadstring(game:HttpGet("https://cdn.wearedevs.net/scripts/Gravity%20Switch.txt"))()
    end)

    local PlayerSection = Player:NewSection("Avanced")

    PlayerSection:NewSlider("Walkspeed", "SPEED!!", 10000000000000, 16, function(s)
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = s
    end)

    PlayerSection:NewSlider("Jumppower", "JUMP HIGH!!", 1000000, 50, function(s)
        game.Players.LocalPlayer.Character.Humanoid.JumpPower = s
    end)

    PlayerSection:NewButton("Reset WS/JP", "Resets to all defaults", function()
        game.Players.LocalPlayer.Character.Humanoid.JumpPower = 50
        game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 16
    end)

     PlayerSection:NewButton("Inf Jump", "HOLD JUMP!!!!", function()
        loadstring(game:HttpGet(("https://pastebin.com/raw/djBfk8Li"),true))()
    end)


    --Teleport
    local Teleport = Window:NewTab("Teleport")
    local TeleportSection = Teleport:NewSection("Teleport")
    TeleportSection:NewLabel("You Can Teleport To any player just type in their full name in the box at the bottom left corner")

    TeleportSection:NewLabel("You have to insert the player name and press Q to use")

    TeleportSection:NewButton("(press)Tp to player by insert their name", "insert player name and press Q to PLAYERS", function()


    local ScreenGui = Instance.new("ScreenGui")
    local TextBox = Instance.new("TextBox")
    
   
    
    ScreenGui.Parent = game.CoreGui
    
    TextBox.Parent = ScreenGui
    TextBox.BackgroundColor3 = Color3.new(0.333333, 0.333333, 0.333333)
    TextBox.Position = UDim2.new(0, 0, 1, -25)
    TextBox.Size = UDim2.new(0, 150, 0, 25)
    TextBox.Font = Enum.Font.SourceSans
    TextBox.Text = "Insert Player Name"
    TextBox.TextColor3 = Color3.new(1, 1, 1)
    TextBox.TextScaled = true
    TextBox.TextSize = 14
    TextBox.TextWrapped = true
    
   
    
    
    
    game:GetService("UserInputService").InputBegan:connect(function(key)
    if key.KeyCode == Enum.KeyCode.Q then
    local ooooooof = TextBox.Text
    local plr1 = game.Players.LocalPlayer.Character
    local plr2 = game.Workspace:FindFirstChild(ooooooof)
    plr1.HumanoidRootPart.CFrame = plr2.HumanoidRootPart.CFrame * CFrame.new(0,2,0)
    end
    end)
end)


    --Misc
    local Misc = Window:NewTab("Misc")
    local MiscSection = Misc:NewSection("Misc")

    MiscSection:NewButton("Sword Reach", "Reach thouse bitches!!!", function()
        loadstring(game:HttpGet(("https://pastebin.com/raw/VeMampRh"),true))()
    end)

    MiscSection:NewButton("Aimbot", "i dont like aiming", function()
        loadstring(game:HttpGet("https://cdn.wearedevs.net/scripts/WRD%20Aimbot.txt"))()
    end)

    MiscSection:NewButton("Universal Reach", "OP REACH SCRIPT", function()
        loadstring(game:HttpGet("https://pastebin.com/raw/MEHvVngb"))()
    end)

    MiscSection:NewButton("Remove displayname", "You know what this does", function()
        local Players = game:FindService("Players")

        require(game:GetService("Chat"):WaitForChild("ClientChatModules").ChatSettings).PlayerDisplayNamesEnabled = false
        
        local function rename(character,name)
            repeat task.wait() until character:FindFirstChildWhichIsA("Humanoid")
            character:FindFirstChildWhichIsA("Humanoid").DisplayName = name
        end
        
        for i,v in next, Players:GetPlayers() do
            if v.Character then
                v.DisplayName = v.Name
                rename(v.Character,v.Name)
            end
            v.CharacterAdded:Connect(function(char)
                rename(char,v.Name)
            end)
        end
        
        Players.PlayerAdded:Connect(function(plr)
            plr.DisplayName = plr.Name
            plr.CharacterAdded:Connect(function(char)
                rename(char,plr.Name)
            end)
        end)
    end)

    MiscSection:NewButton("Bring Script", "Finaly a script that works", function()
        loadstring(game:HttpGet('https://pastebin.com/raw/eUwg0n1f'))()
    end)

    MiscSection:NewButton("hitbox Script", "Good for sword games", function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Min1273/n-to/main/README.md"))()
    end)

    MiscSection:NewButton("simple spy", "Good for creating scripts", function()
        loadstring(game:HttpGet("https://pastebin.com/raw/We87LDxW"))()
    end)

    MiscSection:NewButton("Buit in auto clicker", "Clicking time!!!", function()
    loadstring(game:HttpGetAsync("https://raw.githubusercontent.com/JustEzpi/ROBLOX-Scripts/main/ROBLOX_AutoClicker"))()
    end)


    --Other
    local Other = Window:NewTab("Other")
    local OtherSection = Other:NewSection("Other")

    OtherSection:NewButton("Chat Spoofer", "Lets you chat for other people", function()
        loadstring(game:HttpGet(("https://pastebin.com/raw/djBfk8Li"),true))()
    end)

    OtherSection:NewButton("Bypassed Fly", "bird mode", function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Nicuse/RobloxScripts/main/BypassedFly.lua"))() 

        Fly(true)
    end)

    OtherSection:NewButton("Chat Spoofer", "Lets you chat for other people", function()
        loadstring(game:HttpGet(("https://pastebin.com/raw/PXAdj6ED"),true))()
    end)

    OtherSection:NewButton("Set Night", "Sets the game day to night", function()
        lighting = game:GetService("Lighting")
if lighting.TimeOfDay == "00:00:00" then
    lighting.TimeOfDay = 11
else 
    lighting.TimeOfDay = 24
end
    end)

    OtherSection:NewButton("Hydroxide", "VERY OP", function()
        local owner = "Upbolt"
        local branch = "revision"
        
        local function webImport(file)
            return loadstring(game:HttpGetAsync(("https://raw.githubusercontent.com/%s/Hydroxide/%s/%s.lua"):format(owner, branch, file)), file .. '.lua')()
        end
        
        webImport("init")
        webImport("ui/main")
    end)

    OtherSection:NewButton("Chat translator", "It translates the words to English", function()
        loadstring(game:HttpGetAsync("https://i.qts.life/r/ChatInlineTranslator.lua", true))()
        --[[
        af = "Afrikaans",
            sq = "Albanian",
            am = "Amharic",
            ar = "Arabic",
            hy = "Armenian",
            az = "Azerbaijani",
            eu = "Basque",
            be = "Belarusian",
            bn = "Bengali",
            bs = "Bosnian",
            bg = "Bulgarian",
            ca = "Catalan",
            ceb = "Cebuano",
            ny = "Chichewa",
            ['zh-cn'] = "Chinese Simplified",
            ['zh-tw'] = "Chinese Traditional",
            co = "Corsican",
            hr = "Croatian",
            cs = "Czech",
            da = "Danish",
            nl = "Dutch",
            en = "English",
            eo = "Esperanto",
            et = "Estonian",
            tl = "Filipino",
            fi = "Finnish",
            fr = "French",
            fy = "Frisian",
            gl = "Galician",
            ka = "Georgian",
            de = "German",
            el = "Greek",
            gu = "Gujarati",
            ht = "Haitian Creole",
            ha = "Hausa",
            haw = "Hawaiian",
            iw = "Hebrew",
            hi = "Hindi",
            hmn = "Hmong",
            hu = "Hungarian",
            is = "Icelandic",
            ig = "Igbo",
            id = "Indonesian",
            ga = "Irish",
            it = "Italian",
            ja = "Japanese",
            jw = "Javanese",
            kn = "Kannada",
            kk = "Kazakh",
            km = "Khmer",
            ko = "Korean",
            ku = "Kurdish (Kurmanji)",
            ky = "Kyrgyz",
            lo = "Lao",
            la = "Latin",
            lv = "Latvian",
            lt = "Lithuanian",
            lb = "Luxembourgish",
            mk = "Macedonian",
            mg = "Malagasy",
            ms = "Malay",
            ml = "Malayalam",
            mt = "Maltese",
            mi = "Maori",
            mr = "Marathi",
            mn = "Mongolian",
            my = "Myanmar (Burmese)",
            ne = "Nepali",
            no = "Norwegian",
            ps = "Pashto",
            fa = "Persian",
            pl = "Polish",
            pt = "Portuguese",
            pa = "Punjabi",
            ro = "Romanian",
            ru = "Russian",
            sm = "Samoan",
            gd = "Scots Gaelic",
            sr = "Serbian",
            st = "Sesotho",
            sn = "Shona",
            sd = "Sindhi",
            si = "Sinhala",
            sk = "Slovak",
            sl = "Slovenian",
            so = "Somali",
            es = "Spanish",
            su = "Sundanese",
            sw = "Swahili",
            sv = "Swedish",
            tg = "Tajik",
            ta = "Tamil",
            te = "Telugu",
            th = "Thai",
            tr = "Turkish",
            uk = "Ukrainian",
            ur = "Urdu",
            uz = "Uzbek",
            vi = "Vietnamese",
            cy = "Welsh",
            xh = "Xhosa",
            yi = "Yiddish",
            yo = "Yoruba",
            zu = "Zulu"
        --]]
    end)



    --Games
    local Games = Window:NewTab("Games")
    local GamesSection = Games:NewSection("Games")

GamesSection:NewButton("BedWars Hack", "Time to blow up some beds!!!", function()
    loadstring(game:HttpGet(("https://pastebin.com/raw/Spey3BCD"),true))()
end)
GamesSection:NewButton("MM2 script", "murder time!!!", function()
    loadstring(game:HttpGet(("https://pastebin.com/raw/b1XK1zPk"),true))()
end)
GamesSection:NewButton("Build to survive the bombs script", "BOOM!!!", function()
    loadstring(game:HttpGet(("https://pastebin.com/raw/qxj2PJKP"),true))()
end)
GamesSection:NewButton("Shark Bite script", "OMG HERE COMES THE SHAARK!!!", function()
    loadstring(game:HttpGet(("https://pastebin.com/raw/nwcSpyjx"),true))()
end)
GamesSection:NewButton("Brookhaven Script", "Umm idk what to say here just use it and ignore this", function()
    loadstring(game:HttpGet(("https://pastebin.com/raw/hdpw2hxR"),true))()
end)
GamesSection:NewButton("Prison Life Script", "THE GAME THE HAVE SOO MANY HACKERS LMAO ", function()
    loadstring(game:HttpGet(("https://pastebin.com/raw/0AQQcge3"),true))()
end)

GamesSection:NewButton("roblox stay alive and flex your time on others script", "Text Deleated", function()
    loadstring(game:HttpGet(("https://pastebin.com/raw/4hSRGbkk"),true))()
end)

GamesSection:NewButton("Arsenal", "Text Deleated", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/HonestlyDex/DexHub/main/V3.lua"))()
end)

GamesSection:NewButton("Tower of hell", "Text Deleated", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/jiAQF1tc"))()
end)

GamesSection:NewButton("Car Crasher", "Beutiful", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/YwkKw09a"))()
end)

GamesSection:NewButton("Chaos Script", "BLOOD!!!", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/AYMcDFQ1"))()
end)

GamesSection:NewButton("Doors", "Didnt test to um.....", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Vynixius/main/Doors/Script.lua"))()
end)

GamesSection:NewButton("Entry Point ", "Out of ideas", function()
    loadstring(game:HttpGet("https://pastebin.com/raw/2VQEyt1H"))()
end)

GamesSection:NewButton("Da Hood", "Out of ideas", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/AtomGotIce/Scripts/main/Da%20hood%20aim"))()
end)

GamesSection:NewButton("build a boat for Treasure (babft)", "Out of ideas", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Vynixius/main/Build%20A%20Boat%20For%20Treasure/Script.lua"))()
end)

GamesSection:NewButton("jailbreak", "Out of ideas", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Vynixius/main/Jailbreak/Script.lua"))()
end)

GamesSection:NewButton("Impossible Glass Bridge Obby GUI", "Out of ideas", function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/catgirIz/lev-is-a-baddie/main/Cache/ImpossibleGlassBridgeObby.lua"))();
end)


    --Hubs
    local Hubs = Window:NewTab("Hubs")
    local HubsSection = Hubs:NewSection("Hubs")

    HubsSection:NewButton("Op Finality", "Fe gui", function()
        loadstring(game:HttpGet(("https://pastebin.com/raw/bk5J4cyc"),true))()
    end)

    HubsSection:NewButton("Op Finality", "Fe gui", function()
        loadstring(game:HttpGet(("https://pastebin.com/raw/LwQkm563"),true))()
    end)

    HubsSection:NewButton("Owohub", "A universal aimbot script", function()
        loadstring(game:HttpGet(("https://raw.githubusercontent.com/CriShoux/OwlHub/master/OwlHub.txt"),true))()
    end)

    HubsSection:NewButton("DarkHub", "A universal aimbot script(NEED KEY)", function()
        loadstring(game:HttpGet(("https://pastebin.com/raw/rXhsM2ec"),true))()
    end)

    HubsSection:NewButton("CMDX", "Another admin script", function()
        loadstring(game:HttpGet('https://raw.githubusercontent.com/CMD-X/CMD-X/master/Source', true))()
    end)

    HubsSection:NewButton("Funhub", "HEHE BOI", function()
        loadstring(game:HttpGet("https://pastebin.com/raw/3xqzxtYN", true))()
    end)

    HubsSection:NewButton("AuratusX", "SOO MANY SCRIPTS!!!", function()
        while not game:IsLoaded() do
            wait(0.1)
        end
        loadstring(game:HttpGet("https://raw.githubusercontent.com/RealMrQuacks/AuratusX/master/Load", true))()
    end)

    HubsSection:NewButton("DomainX ", "Its Good ", function()
        loadstring(game:HttpGet('https://raw.githubusercontent.com/shlexware/DomainX/main/source',true))()
    end)

    HubsSection:NewButton("backdoor.exe V8", "Dont Ask Me", function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/iK4oS/backdoor.exe/v8/src/main.lua"))();
    end)

    HubsSection:NewButton("backdoor.exe V6X", "Dont Ask Me", function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/iK4oS/backdoor.exe/v6x/source.lua"))();
    end)

    HubsSection:NewButton("[FE] Shiba Hub", "U can find alot of scripts here", function()
        loadstring(game:HttpGet("https://pastebin.com/raw/JJU38GMW"))();
    end)

    HubsSection:NewButton("Malware Hub", "its not really a virus", function()
        loadstring(game:HttpGet('https://gist.githubusercontent.com/H20CalibreYT/462f6e6236a9371130f113def6549bb1/raw/'))()
    end)

    HubsSection:NewButton("Universal Hub", "ALOT OF SCRIPTS!!! YAYYYY", function()
        loadstring(game:HttpGet('https://raw.githubusercontent.com/Dvrknvss/UniversalFEScriptHub/main/Script'))()
    end)


    HubsSection:NewButton("MRDestroyer Hub V2", "DONT COPY MY UI LIBARY", function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/MrDestroyerSkid/Project-Destroyer/main/Destroyer"))()
    end)

    HubsSection:NewButton("LostPoint FE Script Hub", "OOOH", function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/JunglePush/LostPoint/main/LostPointScript"))()
    end)

    HubsSection:NewButton("Shattervast Admin", "A VERY GOOD ADMIN? AM IN!!!!!", function()
        loadstring(game:HttpGet("https://pastebin.com/raw/fBjf9wM5"))()
    end)

    HubsSection:NewButton("Beach Hub", "more like bitch hub", function()
        loadstring(game:HttpGet(('https://raw.githubusercontent.com/bedra45/BeachHub/main/BeachAnimation'),true))()
    end)

    HubsSection:NewButton("RemX", "idk about this one", function()
        loadstring(game:HttpGet(('https://raw.githubusercontent.com/Henry887/RemX-Script-Hub/main/main.lua'),true))()
    end)

    HubsSection:NewButton("VG HUB", "WOW NICE", function()
        loadstring(game:HttpGet('https://raw.githubusercontent.com/1201for/V.G-Hub/main/V.Ghub'))()
    end)

    HubsSection:NewButton("Sniff Hub", "WOW Cool!!!", function()
        loadstring(game:HttpGet('https://raw.githubusercontent.com/2dgeneralspam1/Sniff-Hub/main/Sniff%20Hub'))()
    end)

    HubsSection:NewButton("FE Trolling GUI", "trolling time!!!!", function()
        loadstring(game:HttpGet("https://pastebin.com/raw/wDh1eTdX"))()
    end)

    HubsSection:NewButton("FE Fling GUI", "Flinging time!!!!", function()
        loadstring(game:HttpGet('https://pastebin.com/raw/r97d7dS0', true))()
    end)

    HubsSection:NewButton("1x1x1x1 GUI", "OP!!!!", function()
        loadstring(game:HttpGet("https://pastebin.com/raw/CYye6uA4", true))()
    end)

    HubsSection:NewButton("BackScript Hub", "OP GUI!!!!", function()
        loadstring(game:HttpGet("https://pastebin.com/raw/wYEeYQsD", true))()
    end)


-- Setting
local Setting = Window:NewTab("Setting")
local SettingSection = Setting:NewSection("Setting")

SettingSection:NewKeybind("OpenGUI", "KeybindInfo", Enum.KeyCode.Quote, function()
	Library:ToggleUI()
end)

local SettingSection = Setting:NewSection("Credits")

SettingSection:NewLabel("Owner = cr4zythegoat6")

local SettingSection = Setting:NewSection("Help")

SettingSection:NewLabel("if you have any bugs or need")
SettingSection:NewLabel("help dm cr4zythegoat6 on discord")
SettingSection:NewLabel("-----------------------------------------------")
SettingSection:NewLabel("if you have a idea or something,")
SettingSection:NewLabel("write it on my discord server")
SettingSection:NewLabel("click the button below to copy link")

SettingSection:NewButton("Copy Discord invite", "Copy Discord invite", function()
    setclipboard("https://discord.gg/dgnWURKK")
end)

SettingSection:NewLabel("-----------------------------------------------")
SettingSection:NewLabel("More updates coming soon!!! enjoy!!") 

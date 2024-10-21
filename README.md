local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()

local Window = OrionLib:MakeWindow({Name = "Gui by XoticMercedesAMG", HidePremium = false, SaveConfig = true, ConfigFolder = "Xotic"})

local args = {
    [1] = {
        [1] = "Prefix",
        [2] = "/"
    }
}

game:GetService("ReplicatedStorage"):WaitForChild("HDAdminClient"):WaitForChild("Signals"):WaitForChild("ChangeSetting"):InvokeServer(unpack(args))

OrionLib:MakeNotification({
	Name = "GUI",
	Content = "Prefix has been changed to /",
	Image = "rbxassetid://4483345998",
	Time = 5
})

local Tab = Window:MakeTab({
	Name = "For Gears prefix is ;",
	Icon = "rbxassetid://7733674079",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Coins Lag maker prefix /",
	Callback = function()
      		game.Players:Chat("/gear me 24015579.1")
  	end    
})

Tab:AddButton({
	Name = "Korblox Sword prefix /",
	Callback = function()
      		game.Players:Chat("/gear me 68539623.1")
  	end    
})

Tab:AddButton({
	Name = "Dragons prefix /",
	Callback = function()
      		game.Players:Chat("/gear me 94233391.1")
  	end    
})

Tab:AddButton({
	Name = "Black hole bomb",
	Callback = function()
      		game.Players:Chat(";gear me 28277486")
  	end    
})

Tab:AddButton({
	Name = "Backet(Half OP)",
	Callback = function()
      		game.Players:Chat("/gear 25162389.1")
  	end    
})

Tab:AddButton({
	Name = "Hot potato",
	Callback = function()
      		game.Players:Chat("/gear me 25741198")
  	end    
})

Tab:AddButton({
 Name = "Bazooka(OP)",
 Callback = function()
        game.Players:Chat("/gear me 169602103")
   end    
})

Tab:AddButton({
 Name = "Scroll(Half OP)",
 Callback = function()
        game.Players:Chat("/gear me 125013830")
   end    
})

Tab:AddButton({
 Name = "Triple laser(OP)",
 Callback = function()
        game.Players:Chat("/gear me 115377964")
   end    
})

Tab:AddButton({
 Name = "Tri-Lazer 3000(OP)",
 Callback = function()
        game.Players:Chat("/gear me 139578207")
   end    
})

Tab:AddButton({
 Name = "Rainbow Periastron Sword",
 Callback = function()
        game.Players:Chat("/gear me 159229806.1")
   end    
})

Tab:AddButton({
 Name = "Bone Sword(OP)",
 Callback = function()
        game.Players:Chat("/gear me 95951291.1")
   end    
})

Tab:AddButton({
	Name = "Black Hole Ray(Half OP)",
	Callback = function()
      		game.Players:Chat("/gear me 78005009.1")
  	end    
})

Tab:AddButton({
	Name = "Rocket launcher(Half OP)",
	Callback = function()
      		game.Players:Chat("/gear me 67747912.1")
  	end    
})

Tab:AddButton({
	Name = "Gravity Hummer(Half OP)",
	Callback = function()
      		game.Players:Chat("/gear me 33866846")
  	end    
})

Tab:AddButton({
	Name = "Platform Producer(Half OP)",
	Callback = function()
      		game.Players:Chat("/gear me 34898883.1")
  	end    
})

Tab:AddButton({
	Name = "Bear Gun(Half OP)",
	Callback = function()
      		game.Players:Chat("/gear me 90718350")
  	end    
})

Tab:AddButton({
	Name = "Remote Bomb(OP)",
	Callback = function()
      		game.Players:Chat("/gear me 33383241")
  	end    
})

Tab:AddDropdown({
	Name = "Divine horn",
	Default = "",
	Options = {"Get Divine Horn", "Multi Activation", "Spam Activation"},
	Callback = function(Value)
		if Value == "Get Divine Horn" then
		game.Players:Chat("/gear me 127506257")
		end
		if Value == "Multi Activation" then
		local args = {
    [1] = "DO THE THING!!!"
}

game:GetService("Players").LocalPlayer.Character.KOSSGustHorn.RemoteEvent:FireServer(unpack(args))
		end
		if Value == "Spam Activation" then
		while game:GetService("RunService").RenderStepped:wait() do
		local args = {
    [1] = "DO THE THING!!!"
}

game:GetService("Players").LocalPlayer.Character.KOSSGustHorn.RemoteEvent:FireServer(unpack(args))
		end
		end
	end    
})

Tab:AddButton({
	Name = "Spray Paint(OP)",
	Callback = function()
      		game.Players:Chat(";gear me 80576967")
  	end    
})

Tab:AddButton({
	Name = "Hammer Judges(Half OP)",
	Callback = function()
      		game.Players:Chat(";gear me 1046322934")
  	end    
})

Tab:AddButton({
	Name = "Resize tool(OP)",
	Callback = function()
      		game.Players:Chat("/gear me 16969792")
  	end    
})

Tab:AddButton({
	Name = "Staff of Fire",
	Callback = function()
      		game.Players:Chat("/gear me 32858741")
  	end    
})

Tab:AddButton({
	Name = "Glove(Half OP)",
	Callback = function()
      		game.Players:Chat("/gear me 65469882")
  	end    
})

Tab:AddButton({
 Name = "Thief coin(Half OP)",
 Callback = function()
        game.Players:Chat("/gear me 117544573")
   end    
})

Tab:AddButton({
 Name = "Zombie staff",
 Callback = function()
        game.Players:Chat("/gear me 26421972")
   end    
})

Tab:AddButton({
 Name = "Noclip2 prefix is / ",
 Callback = function()
         game.Players:Chat("/noclip2 me")
   end    
})

Tab:AddButton({
 Name = "Taser(Half OP)",
 Callback = function()
        game.Players:Chat("/gear me 82357123")
   end    
})

Tab:AddDropdown({
	Name = "Snowball",
	Default = "",
	Options = {"Get Snowball", "Spam Snowballs"},
	Callback = function(Value)
		if Value == "Get Snowball" then
		game.Players:Chat(";gear me 19328185")
		end
		if Value == "Spam Snowballs" then
		local LP = game.Players.LocalPlayer
repeat wait() until LP.Character
for i,v in pairs(LP.Backpack:GetChildren()) do
   if v.Name == "Snowball" then
       v.Parent = LP.Character
   end
end
while true do
   wait(0.25)
   for i,v in pairs (LP.Character:GetChildren()) do
       if v.Name == "Snowball" then
           v:Activate()
       end
   end
   task.wait(0.25)
end
		end
	end
})

local Tab = Window:MakeTab({
	Name = "Silent CMD",
	Icon = "rbxassetid://4370318685",
	PremiumOnly = false
})

Tab:AddTextbox({
	Name = "CMD",
	Default = "",
	TextDisappear = true,
	Callback = function(Value)
		game.Players:Chat(";" .. Value .."")
	end	  
})

local Section = Tab:AddSection({
	Name = "For intellectually developed people"
})

Tab:AddTextbox({
	Name = "bring",
	Default = "Username",
	TextDisappear = true,
	Callback = function(Value)
		game.Players:Chat("/bring ".. Value .."")
	end	  
})

local Tab = Window:MakeTab({
	Name = "GUIS",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

Tab:AddButton({
	Name = "Fedoratum admin v2 by xotic",
	Callback = function()
      		loadstring(game:HttpGet("https://raw.githubusercontent.com/zephyr10101/showcases/main/fedoratumadmin",true))()
  	end    
})

Tab:AddButton({
	Name = "Silent CMD",
	Callback = function()
      		loadstring(game:HttpGet("https://pastebin.com/raw/pGe3C71V"))()
  	end    
})

local Tab = Window:MakeTab({
                    Name = "Defense",
                    Icon = "http://www.roblox.com/asset/?id=7734056608",
                    PremiumOnly = false
                })

Tab:AddToggle({
	Name = "Anti slowdown",
	Default = false,
	Callback = function(Value)
		AntiSlowdown = Value
		while AntiSlowdown do
		if game.Players.LocalPlayer.Character.Humanoid.WalkSpeed < 9 then
		game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 16
		end
		if game.Players.LocalPlayer.Character.Humanoid.JumpPower < 25 then
		game.Players.LocalPlayer.Character.Humanoid.JumpPower = 50
		end
		task.wait()
		end
	end    
})

Tab:AddToggle({
	Name = "Anti mute",
	Default = false,
	Callback = function(Value)
		AntiMute = Value
		while AntiMute do
local sgui = game:GetService("StarterGui")
sgui:SetCoreGuiEnabled(Enum.CoreGuiType.Chat, true)
task.wait()
end
	end    
})

Tab:AddToggle({
 Name = "jc after u died",
 Default = false,
 Callback = function(Value)
        AntiKill = Value
        while AntiKill do
        if game:GetService("Players").LocalPlayer.Character.Humanoid.Health == 0 then
        game.Players:Chat("/jc me")
        end
        task.wait(0.01)
        end
   end    
})

Tab:AddToggle({
	Name = "Anti Void",
	Default = false,
	Callback = function(Value)
	AntiVoid = Value
		local part = Instance.new("Part")
part.Name = "AntiFallPart"
part.Size = Vector3.new(50000, 5, 50000)
part.Transparency = 1
part.Anchored = AntiVoid
part.Position = Vector3.new(-1, -100, 66)
part.Parent = game.Workspace
	end 
})

Tab:AddToggle({
	Name = "Anti freeze",
	Default = false,
	Callback = function(Value)
	AntiFreeze = Value
	while AntiFreeze do
	      game.Players:Chat("/thaw")
	task.wait(0.3)
	end
	end    
})

Tab:AddToggle({
	Name = "Leo poo spam",
	Default = false,
	Callback = function(Value)
	AntiJail = Value
	while AntiJail do
	      game.Players:Chat("/poo b1 /re b1")
	task.wait(0.6)
	end
	end    
})

Tab:AddToggle({
	Name = "campfires lag spam",
	Default = false,
	Callback = function(Value)
	AntiControl = Value
	while AntiControl do
	      game.Players:Chat("/gear me 123234510")
	task.wait(0.5)
	end
	end    
})

local Tab = Window:MakeTab({
	Name = "Extra",
	Icon = "rbxassetid://7733955740",
	PremiumOnly = false
})

Tab:AddTextbox({
	Name = "blind",
	Default = "",
	TextDisappear = true,
	Callback = function(Value)
    wait(0.3) 
    game.Players:Chat("/blur ".. Value .."")
wait(0.3)
game.Players:Chat(" " .. Value .."")
wait(0.3)
    game. Players.LocalPlayer.Character.HumanoidRootPart.CFrame = last_pick_sin_mrazy
	end	  
})

Tab:AddTextbox({
	Name = "Tool",
	Default = "",
	TextDisappear = true,
	Callback = function(Value)
		game.Players:Chat("/jump ")
		wait(0.3)
		game.Players:Chat("/tool " .. Value .." all")
	end	  
})

Tab:AddTextbox({
	Name = "fling",
	Default = "",
	TextDisappear = true,
	Callback = function(Value)
		game.Players:Chat("/fling " .. Value .." 0")
		game.Players:Chat("/speed " .. Value .." 0")
		game.Players:Chat("/Speed " .. Value .." 0")
	end	  
})

Tab:AddTextbox({
	Name = "Poo spam",
	Default = "",
	TextDisappear = true,
	Callback = function(Value)
    wait(0.3)
    game.Players:Chat("/poo " .. Value .."")
    game.Players:Chat("/re " .. Value .."")
    game.Players:Chat("" .. Value .."")
    wait(0.3)
    game. Players.LocalPlayer.Character.HumanoidRootPart.CFrame = last_pick_sin_mrazy 
    game.Workspace.Gravity = (0.001)
	end	  
})

Tab:AddTextbox({
	Name = "Void",
	Default = "",
	TextDisappear = true,
	Callback = function(Value)
		game.Players:Chat("/apparate " .. Value .." inf")
		wait()
		game.Players:Chat("/ice " .. Value .." ")
	end	  
})

Tab:AddButton({
 Name = "Drop tools",
 Callback = function()
        for i,v in pairs(game.Players.LocalPlayer.Backpack:GetDescendants()) do
   if v:IsA("Tool")  then
    game:GetService("RunService").RenderStepped:wait()
    v.Parent = game.Players.LocalPlayer.Character
    game:GetService("RunService").RenderStepped:wait()
    v.Parent = game.Workspace
end
end
   end    
})

Tab:AddButton({
 Name = "Multi gear(press E)",
 Callback = function()
        lp = game:GetService("Players").LocalPlayer

game:GetService("UserInputService").InputBegan:Connect(function(key)
 if key.KeyCode == Enum.KeyCode.E then
  for i,tool in pairs(lp.Backpack:GetChildren()) do
   if tool:IsA("Tool") then
    tool.Parent = lp.Character
    tool:Activate()
    task.wait()
    tool.Parent = lp.Backpack
   end
  end
 end
end)
   end    
})

Tab:AddButton({
 Name = "Check item name",
 Callback = function()
        local player = game.Players.LocalPlayer
local function getCurrentItemInHand()
    if player.Character then
        for _, item in pairs(player.Character:GetChildren()) do
            if item:IsA("Tool") then
                return item.Name
            end
        end
    end
    return "No object in hand"
end

print(getCurrentItemInHand())
   end    
})

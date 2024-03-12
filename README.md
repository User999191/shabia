local Luxtl = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Luxware-UI-Library/main/Source.lua"))() 
   
local Luxt = Luxtl.CreateWindow("Celex", 6105620301)    

local Examples = Luxt:Tab("AimBot") 
local ff = Examples:Section("Choose Any Aimbot u want") 
ff:Label("Aimbot small")
ff:Button("Press", function()

	_G.HeadSize = 13
 
	_G.Disabled = true
 
 
game:GetService('RunService').RenderStepped:connect(function()
		if _G.Disabled then
			for i,v in next, game:GetService('Players'):GetPlayers() do
				if v.Name ~= game:GetService('Players').LocalPlayer.Name then
					pcall(function()
						v.Character.HumanoidRootPart.Size = Vector3.new(_G.HeadSize,_G.HeadSize,_G.HeadSize)
						v.Character.HumanoidRootPart.Transparency = 0.8
						v.Character.HumanoidRootPart.BrickColor = BrickColor.new("Purple")
						v.Character.HumanoidRootPart.Material = "Neon"
						v.Character.HumanoidRootPart.CanCollide = false
					end)
				end
			end
		end
	end)
end)

ff:Label("Aimlock")
ff:Button("Press", function()

	_G.HeadSize = 23
 
	_G.Disabled = true
 
 
game:GetService('RunService').RenderStepped:connect(function()
		if _G.Disabled then
			for i,v in next, game:GetService('Players'):GetPlayers() do
				if v.Name ~= game:GetService('Players').LocalPlayer.Name then
					pcall(function()
						v.Character.HumanoidRootPart.Size = Vector3.new(_G.HeadSize,_G.HeadSize,_G.HeadSize)
						v.Character.HumanoidRootPart.Transparency = 0.8
						v.Character.HumanoidRootPart.BrickColor = BrickColor.new("Purple")
						v.Character.HumanoidRootPart.Material = "Neon"
						v.Character.HumanoidRootPart.CanCollide = false
					end)
				end
			end
		end
	end)
end)

ff:Label("Silent Aim")
ff:Button("Press", function()

	_G.HeadSize = 85
 
	_G.Disabled = true
 
 
game:GetService('RunService').RenderStepped:connect(function()
		if _G.Disabled then
			for i,v in next, game:GetService('Players'):GetPlayers() do
				if v.Name ~= game:GetService('Players').LocalPlayer.Name then
					pcall(function()
						v.Character.HumanoidRootPart.Size = Vector3.new(_G.HeadSize,_G.HeadSize,_G.HeadSize)
						v.Character.HumanoidRootPart.Transparency = 0.8
						v.Character.HumanoidRootPart.BrickColor = BrickColor.new("Purple")
						v.Character.HumanoidRootPart.Material = "Neon"
						v.Character.HumanoidRootPart.CanCollide = false
					end)
				end
			end
		end
	end)
end)

ff:Label("Blatant")
ff:Button("Press", function()

	_G.HeadSize = 45
 
	_G.Disabled = true
 
 
game:GetService('RunService').RenderStepped:connect(function()
		if _G.Disabled then
			for i,v in next, game:GetService('Players'):GetPlayers() do
				if v.Name ~= game:GetService('Players').LocalPlayer.Name then
					pcall(function()
						v.Character.HumanoidRootPart.Size = Vector3.new(_G.HeadSize,_G.HeadSize,_G.HeadSize)
						v.Character.HumanoidRootPart.Transparency = 0.8
						v.Character.HumanoidRootPart.BrickColor = BrickColor.new("Purple")
						v.Character.HumanoidRootPart.Material = "Neon"
						v.Character.HumanoidRootPart.CanCollide = false
					end)
				end
			end
		end
	end)
end)

ff:Label("Reset AimBot")
ff:Button("Press", function()

	_G.HeadSize = 4
 
	_G.Disabled = true
 
 
game:GetService('RunService').RenderStepped:connect(function()
		if _G.Disabled then
			for i,v in next, game:GetService('Players'):GetPlayers() do
				if v.Name ~= game:GetService('Players').LocalPlayer.Name then
					pcall(function()
						v.Character.HumanoidRootPart.Size = Vector3.new(_G.HeadSize,_G.HeadSize,_G.HeadSize)
						v.Character.HumanoidRootPart.Transparency = 0.8
						v.Character.HumanoidRootPart.BrickColor = BrickColor.new("Purple")
						v.Character.HumanoidRootPart.Material = "Neon"
						v.Character.HumanoidRootPart.CanCollide = false
					end)
				end
			end
		end
	end)
end)

ff:Label("Arsenal AimBot")

ff:Label("17")
ff:Button("Press", function()

_G.HeadSize = 17
 
	_G.Disabled = true
 
 
game:GetService('RunService').RenderStepped:connect(function()
		if _G.Disabled then
			for i,v in next, game:GetService('Players'):GetPlayers() do
				if v.Name ~= game:GetService('Players').LocalPlayer.Name then
					pcall(function()
						v.Character.HumanoidRootPart.Size = Vector3.new(_G.HeadSize,_G.HeadSize,_G.HeadSize)
						v.Character.HumanoidRootPart.Transparency = 0.9
						v.Character.HumanoidRootPart.BrickColor = BrickColor.new("Blue")
						v.Character.HumanoidRootPart.Material = "Neon"
						v.Character.HumanoidRootPart.CanCollide = false
					end)
				end
			end
		end
	end)
end)

ff:Label("25")
ff:Button("Press", function()

_G.HeadSize = 25
 
	_G.Disabled = true
 
 
game:GetService('RunService').RenderStepped:connect(function()
		if _G.Disabled then
			for i,v in next, game:GetService('Players'):GetPlayers() do
				if v.Name ~= game:GetService('Players').LocalPlayer.Name then
					pcall(function()
						v.Character.HumanoidRootPart.Size = Vector3.new(_G.HeadSize,_G.HeadSize,_G.HeadSize)
						v.Character.HumanoidRootPart.Transparency = 0.9
						v.Character.HumanoidRootPart.BrickColor = BrickColor.new("Blue")
						v.Character.HumanoidRootPart.Material = "Neon"
						v.Character.HumanoidRootPart.CanCollide = false
					end)
				end
			end
		end
	end)
end)

ff:Label("35")
ff:Button("Press", function()

_G.HeadSize = 35
 
	_G.Disabled = true
 
 
game:GetService('RunService').RenderStepped:connect(function()
		if _G.Disabled then
			for i,v in next, game:GetService('Players'):GetPlayers() do
				if v.Name ~= game:GetService('Players').LocalPlayer.Name then
					pcall(function()
						v.Character.HumanoidRootPart.Size = Vector3.new(_G.HeadSize,_G.HeadSize,_G.HeadSize)
						v.Character.HumanoidRootPart.Transparency = 0.9
						v.Character.HumanoidRootPart.BrickColor = BrickColor.new("Blue")
						v.Character.HumanoidRootPart.Material = "Neon"
						v.Character.HumanoidRootPart.CanCollide = false
					end)
				end
			end
		end
	end)
end)

ff:Label("60 speed")
ff:Button("60", function()
game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 60
end)

ff:Label("100 speed")
ff:Button("100", function()
game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 100
end)

local Examples = Luxt:Tab("FF AimBot") 
local ff = Examples:Section("Get u 130 aimbot") 
ff:Label("FreeFire Aimbot")
ff:Button("Press", function()

_G.HeadSize = 130
 
	_G.Disabled = true
 
 
game:GetService('RunService').RenderStepped:connect(function()
		if _G.Disabled then
			for i,v in next, game:GetService('Players'):GetPlayers() do
				if v.Name ~= game:GetService('Players').LocalPlayer.Name then
					pcall(function()
						v.Character.HumanoidRootPart.Size = Vector3.new(_G.HeadSize,_G.HeadSize,_G.HeadSize)
						v.Character.HumanoidRootPart.Transparency = 0.9
						v.Character.HumanoidRootPart.BrickColor = BrickColor.new("Red")
						v.Character.HumanoidRootPart.Material = "neon"
						v.Character.HumanoidRootPart.CanCollide = false
					end)
				end
			end
		end
	end)
end)

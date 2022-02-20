--Made by GordonJimenez
--Thanks to the creators of the FE scripts

--My discord for support/report issues.
--I hope u'll like it :)

local ScreenGui = Instance.new("ScreenGui")
local main = Instance.new("ScrollingFrame")
local label = Instance.new("TextLabel")
local ender = Instance.new("TextButton")
local sonic = Instance.new("TextButton")
local emotes = Instance.new("TextButton")
local joy = Instance.new("TextButton")
local meme = Instance.new("TextButton")
local invis = Instance.new("TextButton")
local sans = Instance.new("TextButton")
local dawg = Instance.new("TextButton")
local l = Instance.new("TextButton")
local table = Instance.new("TextButton")
local squat = Instance.new("TextButton")
local pyramid = Instance.new("TextButton")
local punch = Instance.new("TextButton")
local spider = Instance.new("TextButton")
local flip = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("CoreGui")

main.Name = "main"
main.Parent = ScreenGui
main.Active = true
main.BackgroundColor3 = Color3.fromRGB(90, 90, 90)
main.Position = UDim2.new(0.748822808, 0, 0.425447315, 0)
main.Size = UDim2.new(0, 192, 0, 289)
main.Draggable = true
main.Active = true


label.Name = "label"
label.Parent = main
label.BackgroundColor3 = Color3.fromRGB(79, 79, 79)
label.Position = UDim2.new(-0.046875, 0, -0.000994035741, 0)
label.Size = UDim2.new(0, 200, 0, 50)
label.Font = Enum.Font.Roboto
label.Text = "Xordon V2"
label.TextColor3 = Color3.fromRGB(0, 0, 0)
label.TextSize = 45.000

ender.Name = "ender"
ender.Parent = main
ender.BackgroundColor3 = Color3.fromRGB(85, 85, 85)
ender.Position = UDim2.new(0.125, 0, 0.0668489933, 0)
ender.Size = UDim2.new(0, 134, 0, 32)
ender.Font = Enum.Font.SciFi
ender.Text = "Ender"
ender.TextColor3 = Color3.fromRGB(0, 0, 0)
ender.TextSize = 35.000
ender.MouseButton1Down:connect(function()
	--Subscribe to OrPlayz on YouTube: https://www.youtube.com/channel/UC1UwUVxrjM2Sb4duUoR6zfA
	--Join The Discord: https://discord.gg/ZrMZt5tbu4





	local player = game.Players.LocalPlayer
	local character1 = player.Character
	local mouse = player:GetMouse()

	local fakebody = Instance.new("Part", character1)
	fakebody.Transparency = 1
	fakebody.Anchored = true
	fakebody.CanCollide = false
	fakebody.Position = character1.Head.Position
	wait()
	_G.ReanimationType = "PDeath" --PDeath, Fling, Simple
	_G.Velocity = Vector3.new(36,0,0)
	_G.FlingBlock = true
	_G.FlingBlockTransparency = 1
	_G.HighlightFlingBlock = true
	_G.FlingBlockPosition = "Part"
	_G.HighlightFlingBlockColor = Color3.fromRGB(255,0,0)

	loadstring(game:HttpGet("https://raw.githubusercontent.com/GelatekWasTaken/Reanimation.lua/main/Main/Main.lua"))()
	wait(1)

	mouse.KeyDown:connect(function(key)
		if key == "e" then
			character1.Reanimate.Part.Position = mouse.Hit.p
		end
	end)

	FELOADLIBRARY = {}
	loadstring(game:GetObjects("rbxassetid://5209815302")[1].Source)()
	local FavIDs = {
		340106355, --Nefl Crystals
		927529620, --Dimension
		876981900, --Fantasy
		398987889, --Ordinary Days
		1117396305, --Oh wait, it's you.
		885996042, --Action Winter Journey
		919231299, --Sprawling Idiot Effigy
		743466274, --Good Day Sunshine
		727411183, --Knife Fight
		1402748531, --The Earth Is Counting On You!
		595230126 --Robot Language
	}

	Bypass = "a"
	loadstring(game:GetObjects("rbxassetid://5325226148")[1].Source)()
	wait()
	local plr = game:service'Players'.LocalPlayer
	print('Local User is '..plr.Name)
	local char = character1.Reanimate
	local hum = char.Humanoid
	local ra = char["Right Arm"]
	local la= char["Left Arm"]
	local rl= char["Right Leg"]
	local ll = char["Left Leg"]
	local hed = char.Head
	local root = char.HumanoidRootPart
	local rootj = root.RootJoint
	local tors = char.Torso
	local mouse = plr:GetMouse()
	local RootCF = CFrame.fromEulerAnglesXYZ(-1.57, 0, 3.14)
	local RHCF = CFrame.fromEulerAnglesXYZ(0, 1.6, 0)
	local LHCF = CFrame.fromEulerAnglesXYZ(0, -1.6, 0)
	-------------------------------------------------------
	--Start Good Stuff--
	-------------------------------------------------------
	local CF = CFrame.new
	local angles = CFrame.Angles
	local attack = false
	local Euler = CFrame.fromEulerAnglesXYZ
	local Rad = math.rad
	local IT = Instance.new
	local BrickC = BrickColor.new
	local Cos = math.cos
	local Acos = math.acos
	local Sin = math.sin
	local Asin = math.asin
	local Abs = math.abs
	local Mrandom = math.random
	local Floor = math.floor
	-------------------------------------------------------
	--End Good Stuff--
	-------------------------------------------------------
	local necko = CF(0, 1, 0, -1, -0, -0, 0, 0, 1, 0, 1, 0)
	local RSH, LSH = nil, nil 
	local RW = Instance.new("Weld") 
	local LW = Instance.new("Weld")
	local RH = tors["Right Hip"]
	local LH = tors["Left Hip"]
	local RSH = tors["Right Shoulder"] 
	local LSH = tors["Left Shoulder"] 
	RSH.Parent = nil 
	LSH.Parent = nil 
	RW.Name = "RW"
	RW.Part0 = tors 
	RW.C0 = CF(1.5, 0.5, 0)
	RW.C1 = CF(0, 0.5, 0) 
	RW.Part1 = ra
	RW.Parent = tors 
	LW.Name = "LW"
	LW.Part0 = tors 
	LW.C0 = CF(-1.5, 0.5, 0)
	LW.C1 = CF(0, 0.5, 0) 
	LW.Part1 = la
	LW.Parent = tors
	local Effects = {}


	-------------------------------------------------------
	--Start Important Functions--
	-------------------------------------------------------
	function swait(num)
		if num == 0 or num == nil then
			game:service("RunService").Stepped:wait()
		else
			for i = 0, num do
				game:service("RunService").Stepped:wait()
			end
		end
	end
	function thread(f)
		coroutine.resume(coroutine.create(f))
	end
	function clerp(a, b, t)
		local qa = {
			QuaternionFromCFrame(a)
		}
		local qb = {
			QuaternionFromCFrame(b)
		}
		local ax, ay, az = a.x, a.y, a.z
		local bx, by, bz = b.x, b.y, b.z
		local _t = 1 - t
		return QuaternionToCFrame(_t * ax + t * bx, _t * ay + t * by, _t * az + t * bz, QuaternionSlerp(qa, qb, t))
	end
	function QuaternionFromCFrame(cf)
		local mx, my, mz, m00, m01, m02, m10, m11, m12, m20, m21, m22 = cf:components()
		local trace = m00 + m11 + m22
		if trace > 0 then
			local s = math.sqrt(1 + trace)
			local recip = 0.5 / s
			return (m21 - m12) * recip, (m02 - m20) * recip, (m10 - m01) * recip, s * 0.5
		else
			local i = 0
			if m00 < m11 then
				i = 1
			end
			if m22 > (i == 0 and m00 or m11) then
				i = 2
			end
			if i == 0 then
				local s = math.sqrt(m00 - m11 - m22 + 1)
				local recip = 0.5 / s
				return 0.5 * s, (m10 + m01) * recip, (m20 + m02) * recip, (m21 - m12) * recip
			elseif i == 1 then
				local s = math.sqrt(m11 - m22 - m00 + 1)
				local recip = 0.5 / s
				return (m01 + m10) * recip, 0.5 * s, (m21 + m12) * recip, (m02 - m20) * recip
			elseif i == 2 then
				local s = math.sqrt(m22 - m00 - m11 + 1)
				local recip = 0.5 / s
				return (m02 + m20) * recip, (m12 + m21) * recip, 0.5 * s, (m10 - m01) * recip
			end
		end
	end
	function QuaternionToCFrame(px, py, pz, x, y, z, w)
		local xs, ys, zs = x + x, y + y, z + z
		local wx, wy, wz = w * xs, w * ys, w * zs
		local xx = x * xs
		local xy = x * ys
		local xz = x * zs
		local yy = y * ys
		local yz = y * zs
		local zz = z * zs
		return CFrame.new(px, py, pz, 1 - (yy + zz), xy - wz, xz + wy, xy + wz, 1 - (xx + zz), yz - wx, xz - wy, yz + wx, 1 - (xx + yy))
	end
	function QuaternionSlerp(a, b, t)
		local cosTheta = a[1] * b[1] + a[2] * b[2] + a[3] * b[3] + a[4] * b[4]
		local startInterp, finishInterp
		if cosTheta >= 1.0E-4 then
			if 1 - cosTheta > 1.0E-4 then
				local theta = math.acos(cosTheta)
				local invSinTheta = 1 / Sin(theta)
				startInterp = Sin((1 - t) * theta) * invSinTheta
				finishInterp = Sin(t * theta) * invSinTheta
			else
				startInterp = 1 - t
				finishInterp = t
			end
		elseif 1 + cosTheta > 1.0E-4 then
			local theta = math.acos(-cosTheta)
			local invSinTheta = 1 / Sin(theta)
			startInterp = Sin((t - 1) * theta) * invSinTheta
			finishInterp = Sin(t * theta) * invSinTheta
		else
			startInterp = t - 1
			finishInterp = t
		end
		return a[1] * startInterp + b[1] * finishInterp, a[2] * startInterp + b[2] * finishInterp, a[3] * startInterp + b[3] * finishInterp, a[4] * startInterp + b[4] * finishInterp
	end
	function rayCast(Position, Direction, Range, Ignore)
		return game:service("Workspace"):FindPartOnRay(Ray.new(Position, Direction.unit * (Range or 999.999)), Ignore)
	end

	local Create = FELOADLIBRARY.Create

	-------------------------------------------------------
	--Start Damage Function--
	-------------------------------------------------------
	function Damage(Part, hit, minim, maxim, knockback, Type, Property, Delay, HitSound, HitPitch)
		if hit.Parent == nil then
			return
		end
		local h = hit.Parent:FindFirstChildOfClass("Humanoid")
		for _, v in pairs(hit.Parent:children()) do
			if v:IsA("Humanoid") then
				h = v
			end
		end

		if h ~= nil and hit.Parent.Name ~= char.Name and hit.Parent.Name ~= plr.Name and hit.Parent:FindFirstChild("Torso") ~= nil then
			if hit.Parent:findFirstChild("DebounceHit") ~= nil then
				if hit.Parent.DebounceHit.Value == true then
					return
				end
			end
			local c = Create("ObjectValue"){
				Name = "creator",
				Value = game:service("Players").LocalPlayer,
				Parent = h,
			}
			game:GetService("Debris"):AddItem(c, .5)
			if HitSound ~= nil and HitPitch ~= nil then
				CFuncs.Sound.Create(HitSound, hit, 1, HitPitch) 
			end
			local Damage = math.random(minim, maxim)
			local blocked = false
			local block = hit.Parent:findFirstChild("Block")
			if block ~= nil then
				if block.className == "IntValue" then
					if block.Value > 0 then
						blocked = true
						block.Value = block.Value - 1
						print(block.Value)
					end
				end
			end
			if blocked == false then
				--h.Health = h.Health - Damage
				ShowDamage((Part.CFrame * CFrame.new(0, 0, (Part.Size.Z / 2)).p + Vector3.new(0, 1.5, 0)), -Damage, 1.5, tors.BrickColor.Color)
			else
				--h.Health = h.Health - (Damage / 2)
				ShowDamage((Part.CFrame * CFrame.new(0, 0, (Part.Size.Z / 2)).p + Vector3.new(0, 1.5, 0)), -Damage, 1.5, tors.BrickColor.Color)
			end
			if Type == "Knockdown" then
				local hum = hit.Parent.Humanoid
				hum.PlatformStand = true
				coroutine.resume(coroutine.create(function(HHumanoid)
					swait(1)
					HHumanoid.PlatformStand = false
				end), hum)
				local angle = (hit.Position - (Property.Position + Vector3.new(0, 0, 0))).unit
				local bodvol = Create("BodyVelocity"){
					velocity = angle * knockback,
					P = 5000,
					maxForce = Vector3.new(8e+003, 8e+003, 8e+003),
					Parent = hit,
				}
				local rl = Create("BodyAngularVelocity"){
					P = 3000,
					maxTorque = Vector3.new(500000, 500000, 500000) * 50000000000000,
					angularvelocity = Vector3.new(math.random(-10, 10), math.random(-10, 10), math.random(-10, 10)),
					Parent = hit,
				}
				game:GetService("Debris"):AddItem(bodvol, .5)
				game:GetService("Debris"):AddItem(rl, .5)
			elseif Type == "Normal" then
				local vp = Create("BodyVelocity"){
					P = 500,
					maxForce = Vector3.new(math.huge, 0, math.huge),
					velocity = Property.CFrame.lookVector * knockback + Property.Velocity / 1.05,
				}
				if knockback > 0 then
					vp.Parent = hit.Parent.Torso
				end
				game:GetService("Debris"):AddItem(vp, .5)
			elseif Type == "Up" then
				local bodyVelocity = Create("BodyVelocity"){
					velocity = Vector3.new(0, 20, 0),
					P = 5000,
					maxForce = Vector3.new(8e+003, 8e+003, 8e+003),
					Parent = hit,
				}
				game:GetService("Debris"):AddItem(bodyVelocity, .5)
			elseif Type == "DarkUp" then
				coroutine.resume(coroutine.create(function()
					for i = 0, 1, 0.1 do
						swait()
						Effects.Block.Create(BrickColor.new("Black"), hit.Parent.Torso.CFrame, 5, 5, 5, 1, 1, 1, .08, 1)
					end
				end))
				local bodyVelocity = Create("BodyVelocity"){
					velocity = Vector3.new(0, 20, 0),
					P = 5000,
					maxForce = Vector3.new(8e+003, 8e+003, 8e+003),
					Parent = hit,
				}
				game:GetService("Debris"):AddItem(bodyVelocity, 1)
			elseif Type == "Snare" then
				local bp = Create("BodyPosition"){
					P = 2000,
					D = 100,
					maxForce = Vector3.new(math.huge, math.huge, math.huge),
					position = hit.Parent.Torso.Position,
					Parent = hit.Parent.Torso,
				}
				game:GetService("Debris"):AddItem(bp, 1)
			elseif Type == "Freeze" then
				local BodPos = Create("BodyPosition"){
					P = 50000,
					D = 1000,
					maxForce = Vector3.new(math.huge, math.huge, math.huge),
					position = hit.Parent.Torso.Position,
					Parent = hit.Parent.Torso,
				}
				local BodGy = Create("BodyGyro") {
					maxTorque = Vector3.new(4e+005, 4e+005, 4e+005) * math.huge ,
					P = 20e+003,
					Parent = hit.Parent.Torso,
					cframe = hit.Parent.Torso.CFrame,
				}
				hit.Parent.Torso.Anchored = true
				coroutine.resume(coroutine.create(function(Part) 
					swait(1.5)
					Part.Anchored = false
				end), hit.Parent.Torso)
				game:GetService("Debris"):AddItem(BodPos, 3)
				game:GetService("Debris"):AddItem(BodGy, 3)
			end
			local debounce = Create("BoolValue"){
				Name = "DebounceHit",
				Parent = hit.Parent,
				Value = true,
			}
			game:GetService("Debris"):AddItem(debounce, Delay)
			c = Create("ObjectValue"){
				Name = "creator",
				Value = Player,
				Parent = h,
			}
			game:GetService("Debris"):AddItem(c, .5)
		end
	end
	-------------------------------------------------------
	--End Damage Function--
	-------------------------------------------------------

	-------------------------------------------------------
	--Start Damage Function Customization--
	-------------------------------------------------------
	function ShowDamage(Pos, Text, Time, Color)
		local Rate = (1 / 30)
		local Pos = (Pos or Vector3.new(0, 0, 0))
		local Text = (Text or "")
		local Time = (Time or 2)
		local Color = (Color or Color3.new(1, 0, 1))
		local EffectPart = CFuncs.Part.Create(workspace, "SmoothPlastic", 0, 1, BrickColor.new(Color), "Effect", Vector3.new(0, 0, 0))
		EffectPart.Anchored = true
		local BillboardGui = Create("BillboardGui"){
			Size = UDim2.new(3, 0, 3, 0),
			Adornee = EffectPart,
			Parent = EffectPart,
		}
		local TextLabel = Create("TextLabel"){
			BackgroundTransparency = 1,
			Size = UDim2.new(1, 0, 1, 0),
			Text = Text,
			Font = "Bodoni",
			TextColor3 = Color,
			TextScaled = true,
			TextStrokeColor3 = Color3.fromRGB(0,0,0),
			Parent = BillboardGui,
		}
		game.Debris:AddItem(EffectPart, (Time))
		EffectPart.Parent = game:GetService("Workspace")
		delay(0, function()
			local Frames = (Time / Rate)
			for Frame = 1, Frames do
				wait(Rate)
				local Percent = (Frame / Frames)
				EffectPart.CFrame = CFrame.new(Pos) + Vector3.new(0, Percent, 0)
				TextLabel.TextTransparency = Percent
			end
			if EffectPart and EffectPart.Parent then
				EffectPart:Destroy()
			end
		end)
	end
	-------------------------------------------------------
	--End Damage Function Customization--
	-------------------------------------------------------

	function MagniDamage(Part, magni, mindam, maxdam, knock, Type)
		for _, c in pairs(workspace:children()) do
			local hum = c:findFirstChild("Humanoid")
			if hum ~= nil then
				local head = c:findFirstChild("Head")
				if head ~= nil then
					local targ = head.Position - Part.Position
					local mag = targ.magnitude
					if magni >= mag and c.Name ~= plr.Name then
						Damage(head, head, mindam, maxdam, knock, Type, root, 0.1, "http://www.roblox.com/asset/?id=0", 1.2)
					end
				end
			end
		end
	end


	CFuncs = {
		Part = {
			Create = function(Parent, Material, Reflectance, Transparency, BColor, Name, Size)
				local Part = Create("Part")({
					Parent = Parent,
					Reflectance = Reflectance,
					Transparency = Transparency,
					CanCollide = false,
					Locked = true,
					BrickColor = BrickColor.new(tostring(BColor)),
					Name = Name,
					Size = Size,
					Material = Material
				})
				RemoveOutlines(Part)
				return Part
			end
		},
		Mesh = {
			Create = function(Mesh, Part, MeshType, MeshId, OffSet, Scale)
				local Msh = Create(Mesh)({
					Parent = Part,
					Offset = OffSet,
					Scale = Scale
				})
				if Mesh == "SpecialMesh" then
					Msh.MeshType = MeshType
					Msh.MeshId = MeshId
				end
				return Msh
			end
		},
		Mesh = {
			Create = function(Mesh, Part, MeshType, MeshId, OffSet, Scale)
				local Msh = Create(Mesh)({
					Parent = Part,
					Offset = OffSet,
					Scale = Scale
				})
				if Mesh == "SpecialMesh" then
					Msh.MeshType = MeshType
					Msh.MeshId = MeshId
				end
				return Msh
			end
		},
		Weld = {
			Create = function(Parent, Part0, Part1, C0, C1)
				local Weld = Create("Weld")({
					Parent = Parent,
					Part0 = Part0,
					Part1 = Part1,
					C0 = C0,
					C1 = C1
				})
				return Weld
			end
		},
		Sound = {
			Create = function(id, par, vol, pit)
				coroutine.resume(coroutine.create(function()
					local S = Create("Sound")({
						Volume = vol,
						Pitch = pit or 1,
						SoundId = id,
						Parent = par or workspace
					})
					wait()
					S:play()
					game:GetService("Debris"):AddItem(S, 6)
				end))
			end
		},
		ParticleEmitter = {
			Create = function(Parent, Color1, Color2, LightEmission, Size, Texture, Transparency, ZOffset, Accel, Drag, LockedToPart, VelocityInheritance, EmissionDirection, Enabled, LifeTime, Rate, Rotation, RotSpeed, Speed, VelocitySpread)
				local fp = Create("ParticleEmitter")({
					Parent = Parent,
					Color = ColorSequence.new(Color1, Color2),
					LightEmission = LightEmission,
					Size = Size,
					Texture = Texture,
					Transparency = Transparency,
					ZOffset = ZOffset,
					Acceleration = Accel,
					Drag = Drag,
					LockedToPart = LockedToPart,
					VelocityInheritance = VelocityInheritance,
					EmissionDirection = EmissionDirection,
					Enabled = Enabled,
					Lifetime = LifeTime,
					Rate = Rate,
					Rotation = Rotation,
					RotSpeed = RotSpeed,
					Speed = Speed,
					VelocitySpread = VelocitySpread
				})
				return fp
			end
		}
	}
	function RemoveOutlines(part)
		part.TopSurface, part.BottomSurface, part.LeftSurface, part.RightSurface, part.FrontSurface, part.BackSurface = 10, 10, 10, 10, 10, 10
	end
	function CreatePart(FormFactor, Parent, Material, Reflectance, Transparency, BColor, Name, Size)
		local Part = Create("Part")({
			formFactor = FormFactor,
			Parent = Parent,
			Reflectance = Reflectance,
			Transparency = Transparency,
			CanCollide = false,
			Locked = true,
			BrickColor = BrickColor.new(tostring(BColor)),
			Name = Name,
			Size = Size,
			Material = Material
		})
		RemoveOutlines(Part)
		return Part
	end
	function CreateMesh(Mesh, Part, MeshType, MeshId, OffSet, Scale)
		local Msh = Create(Mesh)({
			Parent = Part,
			Offset = OffSet,
			Scale = Scale
		})
		if Mesh == "SpecialMesh" then
			Msh.MeshType = MeshType
			Msh.MeshId = MeshId
		end
		return Msh
	end
	function CreateWeld(Parent, Part0, Part1, C0, C1)
		local Weld = Create("Weld")({
			Parent = Parent,
			Part0 = Part0,
			Part1 = Part1,
			C0 = C0,
			C1 = C1
		})
		return Weld
	end


	-------------------------------------------------------
	--Start Effect Function--
	-------------------------------------------------------
	EffectModel = Instance.new("Model", char)
	Effects = {
		Block = {
			Create = function(brickcolor, cframe, x1, y1, z1, x3, y3, z3, delay, Type)
				local prt = CFuncs.Part.Create(EffectModel, "SmoothPlastic", 0, 0, brickcolor, "Effect", Vector3.new())
				prt.Anchored = true
				prt.CFrame = cframe
				local msh = CFuncs.Mesh.Create("BlockMesh", prt, "", "", Vector3.new(0, 0, 0), Vector3.new(x1, y1, z1))
				game:GetService("Debris"):AddItem(prt, 10)
				if Type == 1 or Type == nil then
					table.insert(Effects, {
						prt,
						"Block1",
						delay,
						x3,
						y3,
						z3,
						msh
					})
				elseif Type == 2 then
					table.insert(Effects, {
						prt,
						"Block2",
						delay,
						x3,
						y3,
						z3,
						msh
					})
				else
					table.insert(Effects, {
						prt,
						"Block3",
						delay,
						x3,
						y3,
						z3,
						msh
					})
				end
			end
		},
		Sphere = {
			Create = function(brickcolor, cframe, x1, y1, z1, x3, y3, z3, delay)
				local prt = CFuncs.Part.Create(EffectModel, "Neon", 0, 0, brickcolor, "Effect", Vector3.new())
				prt.Anchored = true
				prt.CFrame = cframe
				local msh = CFuncs.Mesh.Create("SpecialMesh", prt, "Sphere", "", Vector3.new(0, 0, 0), Vector3.new(x1, y1, z1))
				game:GetService("Debris"):AddItem(prt, 10)
				table.insert(Effects, {
					prt,
					"Cylinder",
					delay,
					x3,
					y3,
					z3,
					msh
				})
			end
		},
		Cylinder = {
			Create = function(brickcolor, cframe, x1, y1, z1, x3, y3, z3, delay)
				local prt = CFuncs.Part.Create(EffectModel, "SmoothPlastic", 0, 0, brickcolor, "Effect", Vector3.new())
				prt.Anchored = true
				prt.CFrame = cframe
				local msh = CFuncs.Mesh.Create("CylinderMesh", prt, "", "", Vector3.new(0, 0, 0), Vector3.new(x1, y1, z1))
				game:GetService("Debris"):AddItem(prt, 10)
				table.insert(Effects, {
					prt,
					"Cylinder",
					delay,
					x3,
					y3,
					z3,
					msh
				})
			end
		},
		Wave = {
			Create = function(brickcolor, cframe, x1, y1, z1, x3, y3, z3, delay)
				local prt = CFuncs.Part.Create(EffectModel, "Neon", 0, 0, brickcolor, "Effect", Vector3.new())
				prt.Anchored = true
				prt.CFrame = cframe
				local msh = CFuncs.Mesh.Create("SpecialMesh", prt, "FileMesh", "rbxassetid://20329976", Vector3.new(0, 0, 0), Vector3.new(x1 / 60, y1 / 60, z1 / 60))
				game:GetService("Debris"):AddItem(prt, 10)
				table.insert(Effects, {
					prt,
					"Cylinder",
					delay,
					x3 / 60,
					y3 / 60,
					z3 / 60,
					msh
				})
			end
		},
		Ring = {
			Create = function(brickcolor, cframe, x1, y1, z1, x3, y3, z3, delay)
				local prt = CFuncs.Part.Create(EffectModel, "SmoothPlastic", 0, 0, brickcolor, "Effect", Vector3.new())
				prt.Anchored = true
				prt.CFrame = cframe
				local msh = CFuncs.Mesh.Create("SpecialMesh", prt, "FileMesh", "rbxassetid://3270017", Vector3.new(0, 0, 0), Vector3.new(x1, y1, z1))
				game:GetService("Debris"):AddItem(prt, 10)
				table.insert(Effects, {
					prt,
					"Cylinder",
					delay,
					x3,
					y3,
					z3,
					msh
				})
			end
		},
		Break = {
			Create = function(brickcolor, cframe, x1, y1, z1)
				local prt = CFuncs.Part.Create(EffectModel, "Neon", 0, 0, brickcolor, "Effect", Vector3.new(0.5, 0.5, 0.5))
				prt.Anchored = true
				prt.CFrame = cframe * CFrame.fromEulerAnglesXYZ(math.random(-50, 50), math.random(-50, 50), math.random(-50, 50))
				local msh = CFuncs.Mesh.Create("SpecialMesh", prt, "Sphere", "", Vector3.new(0, 0, 0), Vector3.new(x1, y1, z1))
				local num = math.random(10, 50) / 1000
				game:GetService("Debris"):AddItem(prt, 10)
				table.insert(Effects, {
					prt,
					"Shatter",
					num,
					prt.CFrame,
					math.random() - math.random(),
					0,
					math.random(50, 100) / 100
				})
			end
		},
		Spiral = {
			Create = function(brickcolor, cframe, x1, y1, z1, x3, y3, z3, delay)
				local prt = CFuncs.Part.Create(EffectModel, "SmoothPlastic", 0, 0, brickcolor, "Effect", Vector3.new())
				prt.Anchored = true
				prt.CFrame = cframe
				local msh = CFuncs.Mesh.Create("SpecialMesh", prt, "FileMesh", "rbxassetid://1051557", Vector3.new(0, 0, 0), Vector3.new(x1, y1, z1))
				game:GetService("Debris"):AddItem(prt, 10)
				table.insert(Effects, {
					prt,
					"Cylinder",
					delay,
					x3,
					y3,
					z3,
					msh
				})
			end
		},
		Push = {
			Create = function(brickcolor, cframe, x1, y1, z1, x3, y3, z3, delay)
				local prt = CFuncs.Part.Create(EffectModel, "SmoothPlastic", 0, 0, brickcolor, "Effect", Vector3.new())
				prt.Anchored = true
				prt.CFrame = cframe
				local msh = CFuncs.Mesh.Create("SpecialMesh", prt, "FileMesh", "rbxassetid://437347603", Vector3.new(0, 0, 0), Vector3.new(x1, y1, z1))
				game:GetService("Debris"):AddItem(prt, 10)
				table.insert(Effects, {
					prt,
					"Cylinder",
					delay,
					x3,
					y3,
					z3,
					msh
				})
			end
		}
	}
	-------------------------------------------------------
	--End Effect Function--
	-------------------------------------------------------

	function CreateSound(ID, PARENT, VOLUME, PITCH)
		local NSound = nil
		coroutine.resume(coroutine.create(function()
			NSound = Instance.new("Sound", PARENT)
			NSound.Volume = VOLUME
			NSound.Pitch = PITCH
			NSound.SoundId = "http://www.roblox.com/asset/?id="..ID
			swait()
			NSound:play()
			game:GetService("Debris"):AddItem(NSound, 10)
		end))
		return NSound
	end

	function Eviscerate(dude)
		if dude.Name ~= char.Name and dude.Name ~= plr.Name then
			local val = IT("BoolValue", dude)
			val.Name = "IsHit"
			local ds = coroutine.wrap(function()
				wait(0.5)
				target = nil
				coroutine.resume(coroutine.create(function()
					for i, v in pairs(dude:GetChildren()) do
						if v:IsA("Part") or v:IsA("MeshPart") then
							coroutine.resume(coroutine.create(function()
								v.CanCollide = false
								local PartEmmit1 = IT("ParticleEmitter", v)
								PartEmmit1.LightEmission = 1
								PartEmmit1.Texture = "rbxassetid://284205403"
								PartEmmit1.Color = ColorSequence.new(maincolor.Color)
								PartEmmit1.Rate = 150
								PartEmmit1.Lifetime = NumberRange.new(1)
								PartEmmit1.Size = NumberSequence.new({
									NumberSequenceKeypoint.new(0, 0.75, 0),
									NumberSequenceKeypoint.new(1, 0, 0)
								})
								PartEmmit1.Transparency = NumberSequence.new({
									NumberSequenceKeypoint.new(0, 0, 0),
									NumberSequenceKeypoint.new(1, 1, 0)
								})
								PartEmmit1.Speed = NumberRange.new(0, 0)
								PartEmmit1.VelocitySpread = 30000
								PartEmmit1.Rotation = NumberRange.new(-500, 500)
								PartEmmit1.RotSpeed = NumberRange.new(-500, 500)
								local BodPoss = IT("BodyPosition", v)
								BodPoss.P = 3000
								BodPoss.D = 1000
								BodPoss.maxForce = Vector3.new(50000000000, 50000000000, 50000000000)
								BodPoss.position = v.Position + Vector3.new(Mrandom(-15, 15), Mrandom(-15, 15), Mrandom(-15, 15))
								coroutine.resume(coroutine.create(function()
									wait(0.5)
									PartEmmit1.Enabled = false
								end))
							end))
						end
					end
				end))
			end)
			ds()
		end
	end
	function SphereAura(bonuspeed, FastSpeed, type, pos, x1, y1, z1, value, color, outerpos)
		local type = type
		local rng = Instance.new("Part", char)
		rng.Anchored = true
		rng.BrickColor = color
		rng.CanCollide = false
		rng.FormFactor = 3
		rng.Name = "Ring"
		rng.Material = "Neon"
		rng.Size = Vector3.new(1, 1, 1)
		rng.Transparency = 0
		rng.TopSurface = 0
		rng.BottomSurface = 0
		rng.CFrame = pos
		rng.CFrame = rng.CFrame + rng.CFrame.lookVector * outerpos
		local rngm = Instance.new("SpecialMesh", rng)
		rngm.MeshType = "Sphere"
		rngm.Scale = Vector3.new(x1, y1, z1)
		local scaler2 = 1
		local speeder = FastSpeed
		if type == "Add" then
			scaler2 = 1 * value
		elseif type == "Divide" then
			scaler2 = 1 / value
		end
		coroutine.resume(coroutine.create(function()
			for i = 0, 10 / bonuspeed, 0.1 do
				swait()
				if type == "Add" then
					scaler2 = scaler2 - 0.01 * value / bonuspeed
				elseif type == "Divide" then
					scaler2 = scaler2 - 0.01 / value * bonuspeed
				end
				rng.BrickColor = BrickColor.random()
				speeder = speeder - 0.01 * FastSpeed * bonuspeed
				rng.CFrame = rng.CFrame + rng.CFrame.lookVector * speeder * bonuspeed
				rng.Transparency = rng.Transparency + 0.01 * bonuspeed
				rngm.Scale = rngm.Scale + Vector3.new(scaler2 * bonuspeed, scaler2 * bonuspeed, 0)
			end
			rng:Destroy()
		end))
	end

	function FindNearestHead(Position, Distance, SinglePlayer)
		if SinglePlayer then
			return Distance > (SinglePlayer.Torso.CFrame.p - Position).magnitude
		end
		local List = {}
		for i, v in pairs(workspace:GetChildren()) do
			if v:IsA("Model") and v:findFirstChild("Head") and v ~= char and Distance >= (v.Head.Position - Position).magnitude then
				table.insert(List, v)
			end
		end
		return List
	end
	function SoulSteal(dude)
		if dude.Name ~= char.Name and dude.Name ~= plr.Name then
			local val = IT("BoolValue", dude)
			val.Name = "IsHit"
			local torso = (dude:FindFirstChild'Head' or dude:FindFirstChild'Torso' or dude:FindFirstChild'UpperTorso' or dude:FindFirstChild'LowerTorso' or dude:FindFirstChild'HumanoidRootPart')
			local soulst = coroutine.wrap(function()
				local soul = Instance.new("Part",char)
				soul.Size = Vector3.new(1,1,1)
				soul.CanCollide = false
				soul.Anchored = false
				soul.Position = torso.Position
				soul.Transparency = 1
				local PartEmmit1 = IT("ParticleEmitter", soul)
				PartEmmit1.LightEmission = 1
				PartEmmit1.Texture = "rbxassetid://569507414"
				PartEmmit1.Color = ColorSequence.new(maincolor.Color)
				PartEmmit1.Rate = 250
				PartEmmit1.Lifetime = NumberRange.new(1.6)
				PartEmmit1.Size = NumberSequence.new({
					NumberSequenceKeypoint.new(0, 1, 0),
					NumberSequenceKeypoint.new(1, 0, 0)
				})
				PartEmmit1.Transparency = NumberSequence.new({
					NumberSequenceKeypoint.new(0, 0, 0),
					NumberSequenceKeypoint.new(1, 1, 0)
				})
				PartEmmit1.Speed = NumberRange.new(0, 0)
				PartEmmit1.VelocitySpread = 30000
				PartEmmit1.Rotation = NumberRange.new(-360, 360)
				PartEmmit1.RotSpeed = NumberRange.new(-360, 360)
				local BodPoss = IT("BodyPosition", soul)
				BodPoss.P = 3000
				BodPoss.D = 1000
				BodPoss.maxForce = Vector3.new(50000000000, 50000000000, 50000000000)
				BodPoss.position = torso.Position + Vector3.new(Mrandom(-15, 15), Mrandom(-15, 15), Mrandom(-15, 15))
				wait(1.6)
				soul.Touched:connect(function(hit)
					if hit.Parent == char then
						soul:Destroy()
					end
				end)
				wait(1.2)
				while soul do
					swait()
					PartEmmit1.Color = ColorSequence.new(maincolor.Color)
					BodPoss.Position = tors.Position
				end
			end)
			soulst()
		end
	end
	function FaceMouse()
		local   Cam = workspace.CurrentCamera
		return {
			CFrame.new(char.Torso.Position, Vector3.new(mouse.Hit.p.x, char.Torso.Position.y, mouse.Hit.p.z)),
			Vector3.new(mouse.Hit.p.x, mouse.Hit.p.y, mouse.Hit.p.z)
		}
	end
	-------------------------------------------------------
	--End Important Functions--
	-------------------------------------------------------
--[[
        Thanks for using Build-To-Lua by jarredbcv.
]]--

	New = function(Object, Parent, Name, Data)
		local Object = Instance.new(Object)
		for Index, Value in pairs(Data or {}) do
			Object[Index] = Value
		end
		Object.Parent = Parent
		Object.Name = Name
		return Object
	end

	Gaunty = New("Model",char,"Gaunty",{})
	Handle = New("Part",Gaunty,"Handle",{BrickColor = BrickColor.new("Black"),Material = Enum.Material.Metal,FormFactor = Enum.FormFactor.Custom,Size = Vector3.new(1, 1.26999998, 1),CFrame = CFrame.new(-5.67319345, 3.02064276, -77.6615906, 0.999894261, 0.010924357, 0.00963267777, -0.0110270018, 0.999882579, 0.0106679145, -0.00951499958, -0.0107729975, 0.999897003),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.105882, 0.164706, 0.207843),})
	Mesh = New("BlockMesh",Handle,"Mesh",{Scale = Vector3.new(1.03999996, 1, 1.03999996),})
	NeonPart = New("Part",Gaunty,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.13999987, 0.109999999, 0.109999999),CFrame = CFrame.new(-5.82765579, 3.62595344, -77.6579285, -4.74974513e-08, -6.18456397e-10, 1.0000006, -5.58793545e-09, 1.0000006, -1.5279511e-10, -1.0000006, 4.65661287e-09, -4.00468707e-08),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle,C0 = CFrame.new(0, 0, 0, -4.37113883e-08, 0, -1, 0, 1, 0, 1, 0, -4.37113883e-08),C1 = CFrame.new(-0.161155701, 0.603512526, 0.00862884521, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("Part",Gaunty,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.13999987, 0.109999999, 0.109999999),CFrame = CFrame.new(-6.13765526, 3.62595367, -77.6579285, -4.74974513e-08, -6.18456397e-10, 1.0000006, -5.58793545e-09, 1.0000006, -1.5279511e-10, -1.0000006, 4.65661287e-09, -4.00468707e-08),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle,C0 = CFrame.new(0, 0, 0, -4.37113883e-08, 0, -1, 0, 1, 0, 1, 0, -4.37113883e-08),C1 = CFrame.new(-0.471122265, 0.600126028, 0.00564575195, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("Part",Gaunty,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.13999987, 0.109999999, 0.109999999),CFrame = CFrame.new(-5.5176549, 3.62595415, -77.6579285, -4.74974513e-08, -6.18456397e-10, 1.0000006, -5.58793545e-09, 1.0000006, -1.5279511e-10, -1.0000006, 4.65661287e-09, -4.00468707e-08),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle,C0 = CFrame.new(0, 0, 0, -4.37113883e-08, 0, -1, 0, 1, 0, 1, 0, -4.37113883e-08),C1 = CFrame.new(0.148812294, 0.606899738, 0.0116195679, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("Part",Gaunty,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.13999987, 0.109999999, 0.109999999),CFrame = CFrame.new(-5.21765471, 3.62595463, -77.6579285, -4.74974513e-08, -6.18456397e-10, 1.0000006, -5.58793545e-09, 1.0000006, -1.5279511e-10, -1.0000006, 4.65661287e-09, -4.00468707e-08),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle,C0 = CFrame.new(0, 0, 0, -4.37113883e-08, 0, -1, 0, 1, 0, 1, 0, -4.37113883e-08),C1 = CFrame.new(0.448780537, 0.610177517, 0.014503479, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("Part",Gaunty,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.13999987, 0.109999999, 0.109999999),CFrame = CFrame.new(-6.13765526, 2.53595448, -77.6579285, -4.74974513e-08, -6.18456397e-10, 1.0000006, -5.58793545e-09, 1.0000006, -1.5279511e-10, -1.0000006, 4.65661287e-09, -4.00468707e-08),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle,C0 = CFrame.new(0, 0, 0, -4.37113883e-08, 0, -1, 0, 1, 0, 1, 0, -4.37113883e-08),C1 = CFrame.new(-0.459102631, -0.489744425, -0.00598144531, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("Part",Gaunty,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.13999987, 0.109999999, 0.109999999),CFrame = CFrame.new(-5.82765627, 2.53595448, -77.6579285, -4.74974513e-08, -6.18456397e-10, 1.0000006, -5.58793545e-09, 1.0000006, -1.5279511e-10, -1.0000006, 4.65661287e-09, -4.00468707e-08),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle,C0 = CFrame.new(0, 0, 0, -4.37113883e-08, 0, -1, 0, 1, 0, 1, 0, -4.37113883e-08),C1 = CFrame.new(-0.149136543, -0.486357927, -0.00299835205, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("Part",Gaunty,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.13999987, 0.109999999, 0.109999999),CFrame = CFrame.new(-5.51765537, 2.53595448, -77.6579361, -4.74974513e-08, -6.18456397e-10, 1.0000006, -5.58793545e-09, 1.0000006, -1.5279511e-10, -1.0000006, 4.65661287e-09, -4.00468707e-08),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle,C0 = CFrame.new(0, 0, 0, -4.37113883e-08, 0, -1, 0, 1, 0, 1, 0, -4.37113883e-08),C1 = CFrame.new(0.160831451, -0.48297143, -1.52587891e-05, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("Part",Gaunty,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.13999987, 0.109999999, 0.109999999),CFrame = CFrame.new(-5.21765566, 2.53595424, -77.6579361, -4.74974513e-08, -6.18456397e-10, 1.0000006, -5.58793545e-09, 1.0000006, -1.5279511e-10, -1.0000006, 4.65661287e-09, -4.00468707e-08),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle,C0 = CFrame.new(0, 0, 0, -4.37113883e-08, 0, -1, 0, 1, 0, 1, 0, -4.37113883e-08),C1 = CFrame.new(0.460799217, -0.479694128, 0.00286865234, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	Part = New("Part",Gaunty,"Part",{BrickColor = BrickColor.new("Black"),Material = Enum.Material.Metal,FormFactor = Enum.FormFactor.Custom,Size = Vector3.new(1.07999992, 0.279999971, 1.06999993),CFrame = CFrame.new(-5.66865063, 3.64553881, -77.6613617, 0.999894857, 0.0109243635, 0.00963268708, -0.0110270083, 0.999883175, 0.0106679257, -0.00951500144, -0.0107729994, 0.999897599),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.105882, 0.164706, 0.207843),})
	Mesh = New("BlockMesh",Part,"Mesh",{Scale = Vector3.new(1.03999996, 1, 1.03999996),})
	mot = New("Motor",Part,"mot",{Part0 = Part,Part1 = Handle,C0 = CFrame.new(0, 0, 0, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),C1 = CFrame.new(-0.00235080719, 0.624869347, 0.00694274902, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("Part",Gaunty,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,FormFactor = Enum.FormFactor.Custom,Size = Vector3.new(1.08999991, 0.0599999577, 1.07999992),CFrame = CFrame.new(-5.66490126, 3.73544312, -77.6652145, 0.999894857, 0.0109243635, 0.00963268708, -0.0110270083, 0.999883175, 0.0106679257, -0.00951500144, -0.0107729994, 0.999897599),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	Mesh = New("BlockMesh",NeonPart,"Mesh",{Scale = Vector3.new(1.03999996, 1, 1.03999996),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle,C0 = CFrame.new(0, 0, 0, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),C1 = CFrame.new(0.000443935394, 0.714845657, 0.00408172607, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("Part",Gaunty,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,FormFactor = Enum.FormFactor.Custom,Size = Vector3.new(1.08999991, 0.0599999577, 1.07999992),CFrame = CFrame.new(-5.66480446, 3.52554965, -77.65522, 0.999894857, 0.0109243635, 0.00963268708, -0.0110270083, 0.999883175, 0.0106679257, -0.00951500144, -0.0107729994, 0.999897599),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	Mesh = New("BlockMesh",NeonPart,"Mesh",{Scale = Vector3.new(1.03999996, 1, 1.03999996),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle,C0 = CFrame.new(0, 0, 0, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),C1 = CFrame.new(0.00275993347, 0.504870415, 0.0118331909, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	Part = New("Part",Gaunty,"Part",{BrickColor = BrickColor.new("Black"),Material = Enum.Material.Metal,FormFactor = Enum.FormFactor.Custom,Size = Vector3.new(1.07999992, 0.279999971, 1.06999993),CFrame = CFrame.new(-5.6686511, 2.55553746, -77.6613541, 0.999894857, 0.0109243635, 0.00963268708, -0.0110270083, 0.999883175, 0.0106679257, -0.00951500144, -0.0107729994, 0.999897599),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.105882, 0.164706, 0.207843),})
	Mesh = New("BlockMesh",Part,"Mesh",{Scale = Vector3.new(1.03999996, 1, 1.03999996),})
	mot = New("Motor",Part,"mot",{Part0 = Part,Part1 = Handle,C0 = CFrame.new(0, 0, 0, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),C1 = CFrame.new(0.00966835022, -0.465003252, -0.00468444824, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("Part",Gaunty,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,FormFactor = Enum.FormFactor.Custom,Size = Vector3.new(1.08999991, 0.0599999577, 1.07999992),CFrame = CFrame.new(-5.66490126, 2.64544272, -77.6652145, 0.999894857, 0.0109243635, 0.00963268708, -0.0110270083, 0.999883175, 0.0106679257, -0.00951500144, -0.0107729994, 0.999897599),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	Mesh = New("BlockMesh",NeonPart,"Mesh",{Scale = Vector3.new(1.03999996, 1, 1.03999996),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle,C0 = CFrame.new(0, 0, 0, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),C1 = CFrame.new(0.0124630928, -0.375026226, -0.00754547119, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("Part",Gaunty,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,FormFactor = Enum.FormFactor.Custom,Size = Vector3.new(1.08999991, 0.0599999577, 1.07999992),CFrame = CFrame.new(-5.66480494, 2.43554902, -77.65522, 0.999894857, 0.0109243635, 0.00963268708, -0.0110270083, 0.999883175, 0.0106679257, -0.00951500144, -0.0107729994, 0.999897599),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	Mesh = New("BlockMesh",NeonPart,"Mesh",{Scale = Vector3.new(1.03999996, 1, 1.03999996),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle,C0 = CFrame.new(0, 0, 0, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),C1 = CFrame.new(0.0147790909, -0.585001707, 0.000205993652, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("Part",Gaunty,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.12999988, 0.109999999, 0.109999999),CFrame = CFrame.new(-5.67265606, 3.62595463, -78.1079407, 1.0000006, -6.18456397e-10, 3.7252903e-09, -6.18456397e-10, 1.0000006, 4.65661287e-09, 3.7252903e-09, 4.65661287e-09, 1.0000006),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle,C1 = CFrame.new(-0.0018901825, 0.61005497, -0.439842224, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("Part",Gaunty,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.12999988, 0.109999999, 0.109999999),CFrame = CFrame.new(-5.67265606, 3.62595558, -77.8179321, 1.0000006, -6.18456397e-10, 3.7252903e-09, -6.18456397e-10, 1.0000006, 4.65661287e-09, 3.7252903e-09, 4.65661287e-09, 1.0000006),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle,C1 = CFrame.new(-0.00464963913, 0.606931448, -0.149864197, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("Part",Gaunty,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.13999987, 0.109999999, 0.109999999),CFrame = CFrame.new(-5.66765547, 3.62595606, -77.4879303, 1.0000006, -6.18456397e-10, 3.7252903e-09, -6.18456397e-10, 1.0000006, 4.65661287e-09, 3.7252903e-09, 4.65661287e-09, 1.0000006),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle,C1 = CFrame.new(-0.00278997421, 0.603431463, 0.180152893, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("Part",Gaunty,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.13999987, 0.109999999, 0.109999999),CFrame = CFrame.new(-5.66765547, 3.62595654, -77.1979294, 1.0000006, -6.18456397e-10, 3.7252903e-09, -6.18456397e-10, 1.0000006, 4.65661287e-09, 3.7252903e-09, 4.65661287e-09, 1.0000006),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle,C1 = CFrame.new(-0.00554895401, 0.600307703, 0.470123291, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("Part",Gaunty,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.13999987, 0.109999999, 0.109999999),CFrame = CFrame.new(-5.66765547, 2.53595638, -77.1979294, 1.0000006, -6.18456397e-10, 3.7252903e-09, -6.18456397e-10, 1.0000006, 4.65661287e-09, 3.7252903e-09, 4.65661287e-09, 1.0000006),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle,C1 = CFrame.new(0.0064702034, -0.489563704, 0.458496094, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("Part",Gaunty,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.13999987, 0.109999999, 0.109999999),CFrame = CFrame.new(-5.66765547, 2.53595614, -77.4879303, 1.0000006, -6.18456397e-10, 3.7252903e-09, -6.18456397e-10, 1.0000006, 4.65661287e-09, 3.7252903e-09, 4.65661287e-09, 1.0000006),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle,C1 = CFrame.new(0.00922966003, -0.486439705, 0.168525696, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("Part",Gaunty,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.12999988, 0.109999999, 0.109999999),CFrame = CFrame.new(-5.67265558, 2.53595638, -77.8179245, 1.0000006, -6.18456397e-10, 3.7252903e-09, -6.18456397e-10, 1.0000006, 4.65661287e-09, 3.7252903e-09, 4.65661287e-09, 1.0000006),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle,C1 = CFrame.new(0.00736999512, -0.482939243, -0.161483765, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("Part",Gaunty,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.12999988, 0.109999999, 0.109999999),CFrame = CFrame.new(-5.67265606, 2.53595614, -78.1079254, 1.0000006, -6.18456397e-10, 3.7252903e-09, -6.18456397e-10, 1.0000006, 4.65661287e-09, 3.7252903e-09, 4.65661287e-09, 1.0000006),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle,C1 = CFrame.new(0.0101289749, -0.479815245, -0.451454163, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	Part = New("Part",Gaunty,"Part",{BrickColor = BrickColor.new("Black"),Material = Enum.Material.Metal,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.15999985, 0.0700000003, 0.0700000003),CFrame = CFrame.new(-5.66765547, 3.62595677, -77.1979218, 1.0000006, -6.18456397e-10, 3.7252903e-09, -6.18456397e-10, 1.0000006, 4.65661287e-09, 3.7252903e-09, 4.65661287e-09, 1.0000006),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.105882, 0.164706, 0.207843),})
	mot = New("Motor",Part,"mot",{Part0 = Part,Part1 = Handle,C1 = CFrame.new(-0.00554943085, 0.600307941, 0.47013092, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	Part = New("Part",Gaunty,"Part",{BrickColor = BrickColor.new("Black"),Material = Enum.Material.Metal,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.15999985, 0.0700000003, 0.0700000003),CFrame = CFrame.new(-5.66765499, 3.62595701, -77.4879303, 1.0000006, -6.18456397e-10, 3.7252903e-09, -6.18456397e-10, 1.0000006, 4.65661287e-09, 3.7252903e-09, 4.65661287e-09, 1.0000006),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.105882, 0.164706, 0.207843),})
	mot = New("Motor",Part,"mot",{Part0 = Part,Part1 = Handle,C1 = CFrame.new(-0.00278949738, 0.603432655, 0.180152893, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	Part = New("Part",Gaunty,"Part",{BrickColor = BrickColor.new("Black"),Material = Enum.Material.Metal,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.15999985, 0.0700000003, 0.0700000003),CFrame = CFrame.new(-5.66765451, 3.62595749, -77.8179321, 1.0000006, -6.18456397e-10, 3.7252903e-09, -6.18456397e-10, 1.0000006, 4.65661287e-09, 3.7252903e-09, 4.65661287e-09, 1.0000006),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.105882, 0.164706, 0.207843),})
	mot = New("Motor",Part,"mot",{Part0 = Part,Part1 = Handle,C1 = CFrame.new(0.000350952148, 0.606987953, -0.149810791, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	Part = New("Part",Gaunty,"Part",{BrickColor = BrickColor.new("Black"),Material = Enum.Material.Metal,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.15999985, 0.0700000003, 0.0700000003),CFrame = CFrame.new(-5.66765451, 3.62595749, -78.107933, 1.0000006, -6.18456397e-10, 3.7252903e-09, -6.18456397e-10, 1.0000006, 4.65661287e-09, 3.7252903e-09, 4.65661287e-09, 1.0000006),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.105882, 0.164706, 0.207843),})
	mot = New("Motor",Part,"mot",{Part0 = Part,Part1 = Handle,C1 = CFrame.new(0.00311040878, 0.61011219, -0.439788818, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	Part = New("Part",Gaunty,"Part",{BrickColor = BrickColor.new("Black"),Material = Enum.Material.Metal,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.15999985, 0.0700000003, 0.0700000003),CFrame = CFrame.new(-5.66765499, 2.53595734, -78.107933, 1.0000006, -6.18456397e-10, 3.7252903e-09, -6.18456397e-10, 1.0000006, 4.65661287e-09, 3.7252903e-09, 4.65661287e-09, 1.0000006),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.105882, 0.164706, 0.207843),})
	mot = New("Motor",Part,"mot",{Part0 = Part,Part1 = Handle,C1 = CFrame.new(0.0151295662, -0.479759216, -0.451416016, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	Part = New("Part",Gaunty,"Part",{BrickColor = BrickColor.new("Black"),Material = Enum.Material.Metal,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.15999985, 0.0700000003, 0.0700000003),CFrame = CFrame.new(-5.66765499, 2.5359571, -77.8179245, 1.0000006, -6.18456397e-10, 3.7252903e-09, -6.18456397e-10, 1.0000006, 4.65661287e-09, 3.7252903e-09, 4.65661287e-09, 1.0000006),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.105882, 0.164706, 0.207843),})
	mot = New("Motor",Part,"mot",{Part0 = Part,Part1 = Handle,C1 = CFrame.new(0.0123701096, -0.482883692, -0.161437988, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	Part = New("Part",Gaunty,"Part",{BrickColor = BrickColor.new("Black"),Material = Enum.Material.Metal,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.15999985, 0.0700000003, 0.0700000003),CFrame = CFrame.new(-5.66765499, 2.5359571, -77.4879227, 1.0000006, -6.18456397e-10, 3.7252903e-09, -6.18456397e-10, 1.0000006, 4.65661287e-09, 3.7252903e-09, 4.65661287e-09, 1.0000006),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.105882, 0.164706, 0.207843),})
	mot = New("Motor",Part,"mot",{Part0 = Part,Part1 = Handle,C1 = CFrame.new(0.00923013687, -0.48643899, 0.168533325, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	Part = New("Part",Gaunty,"Part",{BrickColor = BrickColor.new("Black"),Material = Enum.Material.Metal,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.15999985, 0.0700000003, 0.0700000003),CFrame = CFrame.new(-5.66765499, 2.53595686, -77.1979218, 1.0000006, -6.18456397e-10, 3.7252903e-09, -6.18456397e-10, 1.0000006, 4.65661287e-09, 3.7252903e-09, 4.65661287e-09, 1.0000006),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.105882, 0.164706, 0.207843),})
	mot = New("Motor",Part,"mot",{Part0 = Part,Part1 = Handle,C1 = CFrame.new(0.00647068024, -0.489563227, 0.458503723, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	Part = New("Part",Gaunty,"Part",{BrickColor = BrickColor.new("Black"),Material = Enum.Material.Metal,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.15999985, 0.0700000003, 0.0700000003),CFrame = CFrame.new(-6.13765478, 3.62595701, -77.6579132, -4.74974513e-08, -6.18456397e-10, 1.0000006, -5.58793545e-09, 1.0000006, -1.5279511e-10, -1.0000006, 4.65661287e-09, -4.00468707e-08),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.105882, 0.164706, 0.207843),})
	mot = New("Motor",Part,"mot",{Part0 = Part,Part1 = Handle,C0 = CFrame.new(0, 0, 0, -4.37113883e-08, 0, -1, 0, 1, 0, 1, 0, -4.37113883e-08),C1 = CFrame.new(-0.471121788, 0.600129128, 0.00566101074, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	Part = New("Part",Gaunty,"Part",{BrickColor = BrickColor.new("Black"),Material = Enum.Material.Metal,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.15999985, 0.0700000003, 0.0700000003),CFrame = CFrame.new(-5.82765484, 3.62595725, -77.6579132, -4.74974513e-08, -6.18456397e-10, 1.0000006, -5.58793545e-09, 1.0000006, -1.5279511e-10, -1.0000006, 4.65661287e-09, -4.00468707e-08),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.105882, 0.164706, 0.207843),})
	mot = New("Motor",Part,"mot",{Part0 = Part,Part1 = Handle,C0 = CFrame.new(0, 0, 0, -4.37113883e-08, 0, -1, 0, 1, 0, 1, 0, -4.37113883e-08),C1 = CFrame.new(-0.161154747, 0.603516102, 0.008644104, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	Part = New("Part",Gaunty,"Part",{BrickColor = BrickColor.new("Black"),Material = Enum.Material.Metal,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.15999985, 0.0700000003, 0.0700000003),CFrame = CFrame.new(-5.51765442, 3.62595773, -77.6579132, -4.74974513e-08, -6.18456397e-10, 1.0000006, -5.58793545e-09, 1.0000006, -1.5279511e-10, -1.0000006, 4.65661287e-09, -4.00468707e-08),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.105882, 0.164706, 0.207843),})
	mot = New("Motor",Part,"mot",{Part0 = Part,Part1 = Handle,C0 = CFrame.new(0, 0, 0, -4.37113883e-08, 0, -1, 0, 1, 0, 1, 0, -4.37113883e-08),C1 = CFrame.new(0.148812771, 0.606903076, 0.0116348267, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	Part = New("Part",Gaunty,"Part",{BrickColor = BrickColor.new("Black"),Material = Enum.Material.Metal,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.15999985, 0.0700000003, 0.0700000003),CFrame = CFrame.new(-5.21765375, 3.6259582, -77.6579132, -4.74974513e-08, -6.18456397e-10, 1.0000006, -5.58793545e-09, 1.0000006, -1.5279511e-10, -1.0000006, 4.65661287e-09, -4.00468707e-08),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.105882, 0.164706, 0.207843),})
	mot = New("Motor",Part,"mot",{Part0 = Part,Part1 = Handle,C0 = CFrame.new(0, 0, 0, -4.37113883e-08, 0, -1, 0, 1, 0, 1, 0, -4.37113883e-08),C1 = CFrame.new(0.44878149, 0.610180855, 0.0145187378, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	Part = New("Part",Gaunty,"Part",{BrickColor = BrickColor.new("Black"),Material = Enum.Material.Metal,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.15999985, 0.0700000003, 0.0700000003),CFrame = CFrame.new(-5.21765327, 2.53595781, -77.6579132, -4.74974513e-08, -6.18456397e-10, 1.0000006, -5.58793545e-09, 1.0000006, -1.5279511e-10, -1.0000006, 4.65661287e-09, -4.00468707e-08),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.105882, 0.164706, 0.207843),})
	mot = New("Motor",Part,"mot",{Part0 = Part,Part1 = Handle,C0 = CFrame.new(0, 0, 0, -4.37113883e-08, 0, -1, 0, 1, 0, 1, 0, -4.37113883e-08),C1 = CFrame.new(0.460801125, -0.47969079, 0.00289154053, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	Part = New("Part",Gaunty,"Part",{BrickColor = BrickColor.new("Black"),Material = Enum.Material.Metal,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.15999985, 0.0700000003, 0.0700000003),CFrame = CFrame.new(-5.51765299, 2.53595757, -77.6579208, -4.74974513e-08, -6.18456397e-10, 1.0000006, -5.58793545e-09, 1.0000006, -1.5279511e-10, -1.0000006, 4.65661287e-09, -4.00468707e-08),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.105882, 0.164706, 0.207843),})
	mot = New("Motor",Part,"mot",{Part0 = Part,Part1 = Handle,C0 = CFrame.new(0, 0, 0, -4.37113883e-08, 0, -1, 0, 1, 0, 1, 0, -4.37113883e-08),C1 = CFrame.new(0.160833359, -0.48296833, 0, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	Part = New("Part",Gaunty,"Part",{BrickColor = BrickColor.new("Black"),Material = Enum.Material.Metal,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.15999985, 0.0700000003, 0.0700000003),CFrame = CFrame.new(-5.82765341, 2.53595734, -77.6579208, -4.74974513e-08, -6.18456397e-10, 1.0000006, -5.58793545e-09, 1.0000006, -1.5279511e-10, -1.0000006, 4.65661287e-09, -4.00468707e-08),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.105882, 0.164706, 0.207843),})
	mot = New("Motor",Part,"mot",{Part0 = Part,Part1 = Handle,C0 = CFrame.new(0, 0, 0, -4.37113883e-08, 0, -1, 0, 1, 0, 1, 0, -4.37113883e-08),C1 = CFrame.new(-0.149133682, -0.486355066, -0.00299072266, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	Part = New("Part",Gaunty,"Part",{BrickColor = BrickColor.new("Black"),Material = Enum.Material.Metal,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.15999985, 0.0700000003, 0.0700000003),CFrame = CFrame.new(-6.13765383, 2.53595734, -77.6579208, -4.74974513e-08, -6.18456397e-10, 1.0000006, -5.58793545e-09, 1.0000006, -1.5279511e-10, -1.0000006, 4.65661287e-09, -4.00468707e-08),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.105882, 0.164706, 0.207843),})
	mot = New("Motor",Part,"mot",{Part0 = Part,Part1 = Handle,C0 = CFrame.new(0, 0, 0, -4.37113883e-08, 0, -1, 0, 1, 0, 1, 0, -4.37113883e-08),C1 = CFrame.new(-0.4591012, -0.489741802, -0.00597381592, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("WedgePart",Gaunty,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,Size = Vector3.new(1.14999998, 0.640000045, 0.25000003),CFrame = CFrame.new(-5.66203499, 3.4509573, -77.7865677, 1.0000006, -6.18456397e-10, 3.7252903e-09, -6.18456397e-10, 1.0000006, 4.65661287e-09, 3.7252903e-09, 4.65661287e-09, 1.0000006),BottomSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle,C1 = CFrame.new(0.00760126114, 0.431732178, -0.120269775, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("WedgePart",Gaunty,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,Size = Vector3.new(1.14999998, 0.640000045, 0.280000031),CFrame = CFrame.new(-5.66203451, 3.45095778, -77.5215683, -1.0000006, -6.18456397e-10, -9.12696123e-08, 6.18456397e-10, 1.0000006, -4.65661287e-09, 8.38190317e-08, 4.65661287e-09, -1.0000006),BottomSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle,C0 = CFrame.new(0, 0, 0, -1, 0, 8.74227766e-08, 0, 1, 0, -8.74227766e-08, 0, -1),C1 = CFrame.new(0.00508022308, 0.428877592, 0.144706726, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("WedgePart",Gaunty,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,Size = Vector3.new(1.14999998, 0.640000045, 0.25000003),CFrame = CFrame.new(-5.66203403, 2.81095791, -77.7865601, -1.0000006, 8.81700544e-08, 3.7252903e-09, -8.69331416e-08, -1.0000006, 4.65661287e-09, -3.7252903e-09, -4.65661287e-09, 1.0000006),BottomSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle,C0 = CFrame.new(0, 0, 0, -1, -8.74227766e-08, 0, 8.74227766e-08, -1, 0, 0, 0, 1),C1 = CFrame.new(0.0146594048, -0.208191872, -0.127082825, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("WedgePart",Gaunty,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,Size = Vector3.new(1.14999998, 0.640000045, 0.280000031),CFrame = CFrame.new(-5.66203356, 2.8209579, -77.5215607, 1.0000006, -8.69331416e-08, 8.38190317e-08, -8.81700544e-08, -1.0000006, -4.65661287e-09, 9.12696123e-08, -4.65661287e-09, -1.0000006),BottomSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle,C0 = CFrame.new(0, 0, 0, 1, -8.74227766e-08, 8.74227766e-08, -8.74227766e-08, -1, -7.64274186e-15, 8.74227766e-08, 0, -1),C1 = CFrame.new(0.0120282173, -0.201047897, 0.137992859, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	Wedge = New("WedgePart",Gaunty,"Wedge",{BrickColor = BrickColor.new("Black"),Size = Vector3.new(1.1099999, 0.569999993, 1.13),CFrame = CFrame.new(-5.6508193, 4.06113148, -77.6620178, -4.74974513e-08, -6.18456397e-10, 1.0000006, -5.58793545e-09, 1.0000006, -1.5279511e-10, -1.0000006, 4.65661287e-09, -4.00468707e-08),BottomSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.105882, 0.164706, 0.207843),})
	mot = New("Motor",Wedge,"mot",{Part0 = Wedge,Part1 = Handle,C0 = CFrame.new(0, 0, 0, -4.37113883e-08, 0, -1, 0, 1, 0, 1, 0, -4.37113883e-08),C1 = CFrame.new(0.0109024048, 1.04061508, 0.010887146, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})

	Gaunty2 = New("Model",char,"Gaunty2",{})
	Handle2 = New("Part",Gaunty2,"Handle2",{BrickColor = BrickColor.new("Black"),Material = Enum.Material.Metal,FormFactor = Enum.FormFactor.Custom,Size = Vector3.new(1, 1.26999998, 1),CFrame = CFrame.new(-5.67319345, 3.02064276, -77.6615906, 0.999894261, 0.010924357, 0.00963267777, -0.0110270018, 0.999882579, 0.0106679145, -0.00951499958, -0.0107729975, 0.999897003),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.105882, 0.164706, 0.207843),})
	Mesh = New("BlockMesh",Handle2,"Mesh",{Scale = Vector3.new(1.03999996, 1, 1.03999996),})
	NeonPart = New("Part",Gaunty2,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.13999987, 0.109999999, 0.109999999),CFrame = CFrame.new(-5.82765579, 3.62595367, -77.6579285, -5.49480319e-08, -2.26282282e-09, 1.00000179, -1.67638063e-08, 1.00000179, -1.8189894e-09, -1.00000179, 1.39698386e-08, -3.25962901e-08),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, -5.12227416e-08, -1.11758709e-08, -1.00000119, -1.44063961e-09, 1.00000119, 9.31322575e-09, 1.00000119, -9.89530236e-10, -3.63215804e-08),C1 = CFrame.new(-0.161155701, 0.603512764, 0.00862884521, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("Part",Gaunty2,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.13999987, 0.109999999, 0.109999999),CFrame = CFrame.new(-6.13765526, 3.62595439, -77.6579285, -5.49480319e-08, -2.26282282e-09, 1.00000179, -1.67638063e-08, 1.00000179, -1.8189894e-09, -1.00000179, 1.39698386e-08, -3.25962901e-08),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, -5.12227416e-08, -1.11758709e-08, -1.00000119, -1.44063961e-09, 1.00000119, 9.31322575e-09, 1.00000119, -9.89530236e-10, -3.63215804e-08),C1 = CFrame.new(-0.471122265, 0.600126743, 0.00564575195, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("Part",Gaunty2,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.13999987, 0.109999999, 0.109999999),CFrame = CFrame.new(-5.51765394, 3.6259551, -77.6579285, -5.49480319e-08, -2.26282282e-09, 1.00000179, -1.67638063e-08, 1.00000179, -1.8189894e-09, -1.00000179, 1.39698386e-08, -3.25962901e-08),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, -5.12227416e-08, -1.11758709e-08, -1.00000119, -1.44063961e-09, 1.00000119, 9.31322575e-09, 1.00000119, -9.89530236e-10, -3.63215804e-08),C1 = CFrame.new(0.148813248, 0.606900692, 0.0116195679, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("Part",Gaunty2,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.13999987, 0.109999999, 0.109999999),CFrame = CFrame.new(-5.21765375, 3.62595558, -77.6579285, -5.49480319e-08, -2.26282282e-09, 1.00000179, -1.67638063e-08, 1.00000179, -1.8189894e-09, -1.00000179, 1.39698386e-08, -3.25962901e-08),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, -5.12227416e-08, -1.11758709e-08, -1.00000119, -1.44063961e-09, 1.00000119, 9.31322575e-09, 1.00000119, -9.89530236e-10, -3.63215804e-08),C1 = CFrame.new(0.44878149, 0.610178471, 0.014503479, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("Part",Gaunty2,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.13999987, 0.109999999, 0.109999999),CFrame = CFrame.new(-6.13765621, 2.535954, -77.6579285, -5.49480319e-08, -2.26282282e-09, 1.00000179, -1.67638063e-08, 1.00000179, -1.8189894e-09, -1.00000179, 1.39698386e-08, -3.25962901e-08),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, -5.12227416e-08, -1.11758709e-08, -1.00000119, -1.44063961e-09, 1.00000119, 9.31322575e-09, 1.00000119, -9.89530236e-10, -3.63215804e-08),C1 = CFrame.new(-0.459103584, -0.489744902, -0.00598144531, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("Part",Gaunty2,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.13999987, 0.109999999, 0.109999999),CFrame = CFrame.new(-5.82765722, 2.535954, -77.6579285, -5.49480319e-08, -2.26282282e-09, 1.00000179, -1.67638063e-08, 1.00000179, -1.8189894e-09, -1.00000179, 1.39698386e-08, -3.25962901e-08),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, -5.12227416e-08, -1.11758709e-08, -1.00000119, -1.44063961e-09, 1.00000119, 9.31322575e-09, 1.00000119, -9.89530236e-10, -3.63215804e-08),C1 = CFrame.new(-0.149137497, -0.486358404, -0.00299835205, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("Part",Gaunty2,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.13999987, 0.109999999, 0.109999999),CFrame = CFrame.new(-5.5176549, 2.53595448, -77.6579514, -5.49480319e-08, -2.26282282e-09, 1.00000179, -1.67638063e-08, 1.00000179, -1.8189894e-09, -1.00000179, 1.39698386e-08, -3.25962901e-08),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, -5.12227416e-08, -1.11758709e-08, -1.00000119, -1.44063961e-09, 1.00000119, 9.31322575e-09, 1.00000119, -9.89530236e-10, -3.63215804e-08),C1 = CFrame.new(0.160831928, -0.482971191, -3.05175781e-05, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("Part",Gaunty2,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.13999987, 0.109999999, 0.109999999),CFrame = CFrame.new(-5.21765566, 2.535954, -77.6579361, -5.49480319e-08, -2.26282282e-09, 1.00000179, -1.67638063e-08, 1.00000179, -1.8189894e-09, -1.00000179, 1.39698386e-08, -3.25962901e-08),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, -5.12227416e-08, -1.11758709e-08, -1.00000119, -1.44063961e-09, 1.00000119, 9.31322575e-09, 1.00000119, -9.89530236e-10, -3.63215804e-08),C1 = CFrame.new(0.460799217, -0.479694366, 0.00286865234, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	Part = New("Part",Gaunty2,"Part",{BrickColor = BrickColor.new("Black"),Material = Enum.Material.Metal,FormFactor = Enum.FormFactor.Custom,Size = Vector3.new(1.07999992, 0.279999971, 1.06999993),CFrame = CFrame.new(-5.66865063, 3.64554, -77.661377, 0.999896049, 0.0109243765, 0.00963270571, -0.0110270213, 0.999884367, 0.010667949, -0.0095150033, -0.0107730031, 0.999898791),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.105882, 0.164706, 0.207843),})
	Mesh = New("BlockMesh",Part,"Mesh",{Scale = Vector3.new(1.03999996, 1, 1.03999996),})
	mot = New("Motor",Part,"mot",{Part0 = Part,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, 0.999895453, -0.0110270148, -0.00951500237, 0.01092437, 0.999883771, -0.0107730012, 0.0096326964, 0.0106679378, 0.999898195),C1 = CFrame.new(-0.00235033035, 0.624870777, 0.00692749023, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("Part",Gaunty2,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,FormFactor = Enum.FormFactor.Custom,Size = Vector3.new(1.08999991, 0.0599999577, 1.07999992),CFrame = CFrame.new(-5.6649003, 3.73544407, -77.6652145, 0.999896049, 0.0109243765, 0.00963270571, -0.0110270213, 0.999884367, 0.010667949, -0.0095150033, -0.0107730031, 0.999898791),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	Mesh = New("BlockMesh",NeonPart,"Mesh",{Scale = Vector3.new(1.03999996, 1, 1.03999996),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, 0.999895453, -0.0110270148, -0.00951500237, 0.01092437, 0.999883771, -0.0107730012, 0.0096326964, 0.0106679378, 0.999898195),C1 = CFrame.new(0.000444412231, 0.714846611, 0.00408172607, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("Part",Gaunty2,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,FormFactor = Enum.FormFactor.Custom,Size = Vector3.new(1.08999991, 0.0599999577, 1.07999992),CFrame = CFrame.new(-5.66480446, 3.5255506, -77.65522, 0.999896049, 0.0109243765, 0.00963270571, -0.0110270213, 0.999884367, 0.010667949, -0.0095150033, -0.0107730031, 0.999898791),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	Mesh = New("BlockMesh",NeonPart,"Mesh",{Scale = Vector3.new(1.03999996, 1, 1.03999996),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, 0.999895453, -0.0110270148, -0.00951500237, 0.01092437, 0.999883771, -0.0107730012, 0.0096326964, 0.0106679378, 0.999898195),C1 = CFrame.new(0.00275993347, 0.504871368, 0.0118331909, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	Part = New("Part",Gaunty2,"Part",{BrickColor = BrickColor.new("Black"),Material = Enum.Material.Metal,FormFactor = Enum.FormFactor.Custom,Size = Vector3.new(1.07999992, 0.279999971, 1.06999993),CFrame = CFrame.new(-5.6686511, 2.55553699, -77.6613541, 0.999896049, 0.0109243765, 0.00963270571, -0.0110270213, 0.999884367, 0.010667949, -0.0095150033, -0.0107730031, 0.999898791),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.105882, 0.164706, 0.207843),})
	Mesh = New("BlockMesh",Part,"Mesh",{Scale = Vector3.new(1.03999996, 1, 1.03999996),})
	mot = New("Motor",Part,"mot",{Part0 = Part,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, 0.999895453, -0.0110270148, -0.00951500237, 0.01092437, 0.999883771, -0.0107730012, 0.0096326964, 0.0106679378, 0.999898195),C1 = CFrame.new(0.00966835022, -0.465003729, -0.00468444824, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("Part",Gaunty2,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,FormFactor = Enum.FormFactor.Custom,Size = Vector3.new(1.08999991, 0.0599999577, 1.07999992),CFrame = CFrame.new(-5.66490126, 2.64544272, -77.6652145, 0.999896049, 0.0109243765, 0.00963270571, -0.0110270213, 0.999884367, 0.010667949, -0.0095150033, -0.0107730031, 0.999898791),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	Mesh = New("BlockMesh",NeonPart,"Mesh",{Scale = Vector3.new(1.03999996, 1, 1.03999996),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, 0.999895453, -0.0110270148, -0.00951500237, 0.01092437, 0.999883771, -0.0107730012, 0.0096326964, 0.0106679378, 0.999898195),C1 = CFrame.new(0.0124630928, -0.375026226, -0.00754547119, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("Part",Gaunty2,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,FormFactor = Enum.FormFactor.Custom,Size = Vector3.new(1.08999991, 0.0599999577, 1.07999992),CFrame = CFrame.new(-5.66480589, 2.43554854, -77.65522, 0.999896049, 0.0109243765, 0.00963270571, -0.0110270213, 0.999884367, 0.010667949, -0.0095150033, -0.0107730031, 0.999898791),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	Mesh = New("BlockMesh",NeonPart,"Mesh",{Scale = Vector3.new(1.03999996, 1, 1.03999996),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, 0.999895453, -0.0110270148, -0.00951500237, 0.01092437, 0.999883771, -0.0107730012, 0.0096326964, 0.0106679378, 0.999898195),C1 = CFrame.new(0.0147781372, -0.585002184, 0.000205993652, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("Part",Gaunty2,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.12999988, 0.109999999, 0.109999999),CFrame = CFrame.new(-5.67265606, 3.62595463, -78.1079407, 1.00000179, -2.26282282e-09, 1.11758709e-08, -2.28465069e-09, 1.00000179, 1.39698386e-08, 1.11758709e-08, 1.39698386e-08, 1.00000179),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, 1.00000119, -1.44791557e-09, 7.4505806e-09, -1.44063961e-09, 1.00000119, 9.31322575e-09, 7.4505806e-09, 9.31322575e-09, 1.00000119),C1 = CFrame.new(-0.0018901825, 0.61005497, -0.439842224, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("Part",Gaunty2,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.12999988, 0.109999999, 0.109999999),CFrame = CFrame.new(-5.67265511, 3.6259563, -77.8179169, 1.00000179, -2.26282282e-09, 1.11758709e-08, -2.28465069e-09, 1.00000179, 1.39698386e-08, 1.11758709e-08, 1.39698386e-08, 1.00000179),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, 1.00000119, -1.44791557e-09, 7.4505806e-09, -1.44063961e-09, 1.00000119, 9.31322575e-09, 7.4505806e-09, 9.31322575e-09, 1.00000119),C1 = CFrame.new(-0.00464916229, 0.606932163, -0.149848938, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("Part",Gaunty2,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.13999987, 0.109999999, 0.109999999),CFrame = CFrame.new(-5.66765451, 3.62595701, -77.4879303, 1.00000179, -2.26282282e-09, 1.11758709e-08, -2.28465069e-09, 1.00000179, 1.39698386e-08, 1.11758709e-08, 1.39698386e-08, 1.00000179),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, 1.00000119, -1.44791557e-09, 7.4505806e-09, -1.44063961e-09, 1.00000119, 9.31322575e-09, 7.4505806e-09, 9.31322575e-09, 1.00000119),C1 = CFrame.new(-0.00278902054, 0.603432655, 0.180152893, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("Part",Gaunty2,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.13999987, 0.109999999, 0.109999999),CFrame = CFrame.new(-5.66765547, 3.62595749, -77.1979294, 1.00000179, -2.26282282e-09, 1.11758709e-08, -2.28465069e-09, 1.00000179, 1.39698386e-08, 1.11758709e-08, 1.39698386e-08, 1.00000179),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, 1.00000119, -1.44791557e-09, 7.4505806e-09, -1.44063961e-09, 1.00000119, 9.31322575e-09, 7.4505806e-09, 9.31322575e-09, 1.00000119),C1 = CFrame.new(-0.00554895401, 0.600308895, 0.470123291, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("Part",Gaunty2,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.13999987, 0.109999999, 0.109999999),CFrame = CFrame.new(-5.66765547, 2.53595638, -77.1979294, 1.00000179, -2.26282282e-09, 1.11758709e-08, -2.28465069e-09, 1.00000179, 1.39698386e-08, 1.11758709e-08, 1.39698386e-08, 1.00000179),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, 1.00000119, -1.44791557e-09, 7.4505806e-09, -1.44063961e-09, 1.00000119, 9.31322575e-09, 7.4505806e-09, 9.31322575e-09, 1.00000119),C1 = CFrame.new(0.0064702034, -0.489563704, 0.458496094, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("Part",Gaunty2,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.13999987, 0.109999999, 0.109999999),CFrame = CFrame.new(-5.66765547, 2.53595614, -77.4879303, 1.00000179, -2.26282282e-09, 1.11758709e-08, -2.28465069e-09, 1.00000179, 1.39698386e-08, 1.11758709e-08, 1.39698386e-08, 1.00000179),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, 1.00000119, -1.44791557e-09, 7.4505806e-09, -1.44063961e-09, 1.00000119, 9.31322575e-09, 7.4505806e-09, 9.31322575e-09, 1.00000119),C1 = CFrame.new(0.00922966003, -0.486439705, 0.168525696, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("Part",Gaunty2,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.12999988, 0.109999999, 0.109999999),CFrame = CFrame.new(-5.67265558, 2.53595638, -77.8179092, 1.00000179, -2.26282282e-09, 1.11758709e-08, -2.28465069e-09, 1.00000179, 1.39698386e-08, 1.11758709e-08, 1.39698386e-08, 1.00000179),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, 1.00000119, -1.44791557e-09, 7.4505806e-09, -1.44063961e-09, 1.00000119, 9.31322575e-09, 7.4505806e-09, 9.31322575e-09, 1.00000119),C1 = CFrame.new(0.00736999512, -0.482939243, -0.161468506, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("Part",Gaunty2,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.12999988, 0.109999999, 0.109999999),CFrame = CFrame.new(-5.67265606, 2.53595567, -78.1079254, 1.00000179, -2.26282282e-09, 1.11758709e-08, -2.28465069e-09, 1.00000179, 1.39698386e-08, 1.11758709e-08, 1.39698386e-08, 1.00000179),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, 1.00000119, -1.44791557e-09, 7.4505806e-09, -1.44063961e-09, 1.00000119, 9.31322575e-09, 7.4505806e-09, 9.31322575e-09, 1.00000119),C1 = CFrame.new(0.0101289749, -0.479815722, -0.451454163, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	Part = New("Part",Gaunty2,"Part",{BrickColor = BrickColor.new("Black"),Material = Enum.Material.Metal,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.15999985, 0.0700000003, 0.0700000003),CFrame = CFrame.new(-5.66765451, 3.62595749, -77.1979218, 1.00000179, -2.26282282e-09, 1.11758709e-08, -2.28465069e-09, 1.00000179, 1.39698386e-08, 1.11758709e-08, 1.39698386e-08, 1.00000179),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.105882, 0.164706, 0.207843),})
	mot = New("Motor",Part,"mot",{Part0 = Part,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, 1.00000119, -1.44791557e-09, 7.4505806e-09, -1.44063961e-09, 1.00000119, 9.31322575e-09, 7.4505806e-09, 9.31322575e-09, 1.00000119),C1 = CFrame.new(-0.00554847717, 0.600308895, 0.47013092, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	Part = New("Part",Gaunty2,"Part",{BrickColor = BrickColor.new("Black"),Material = Enum.Material.Metal,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.15999985, 0.0700000003, 0.0700000003),CFrame = CFrame.new(-5.66765404, 3.62595797, -77.4879303, 1.00000179, -2.26282282e-09, 1.11758709e-08, -2.28465069e-09, 1.00000179, 1.39698386e-08, 1.11758709e-08, 1.39698386e-08, 1.00000179),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.105882, 0.164706, 0.207843),})
	mot = New("Motor",Part,"mot",{Part0 = Part,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, 1.00000119, -1.44791557e-09, 7.4505806e-09, -1.44063961e-09, 1.00000119, 9.31322575e-09, 7.4505806e-09, 9.31322575e-09, 1.00000119),C1 = CFrame.new(-0.0027885437, 0.603433609, 0.180152893, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	Part = New("Part",Gaunty2,"Part",{BrickColor = BrickColor.new("Black"),Material = Enum.Material.Metal,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.15999985, 0.0700000003, 0.0700000003),CFrame = CFrame.new(-5.66765356, 3.6259594, -77.8179321, 1.00000179, -2.26282282e-09, 1.11758709e-08, -2.28465069e-09, 1.00000179, 1.39698386e-08, 1.11758709e-08, 1.39698386e-08, 1.00000179),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.105882, 0.164706, 0.207843),})
	mot = New("Motor",Part,"mot",{Part0 = Part,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, 1.00000119, -1.44791557e-09, 7.4505806e-09, -1.44063961e-09, 1.00000119, 9.31322575e-09, 7.4505806e-09, 9.31322575e-09, 1.00000119),C1 = CFrame.new(0.000351905823, 0.606989861, -0.149810791, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	Part = New("Part",Gaunty2,"Part",{BrickColor = BrickColor.new("Black"),Material = Enum.Material.Metal,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.15999985, 0.0700000003, 0.0700000003),CFrame = CFrame.new(-5.66765356, 3.62595844, -78.107933, 1.00000179, -2.26282282e-09, 1.11758709e-08, -2.28465069e-09, 1.00000179, 1.39698386e-08, 1.11758709e-08, 1.39698386e-08, 1.00000179),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.105882, 0.164706, 0.207843),})
	mot = New("Motor",Part,"mot",{Part0 = Part,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, 1.00000119, -1.44791557e-09, 7.4505806e-09, -1.44063961e-09, 1.00000119, 9.31322575e-09, 7.4505806e-09, 9.31322575e-09, 1.00000119),C1 = CFrame.new(0.00311136246, 0.610113144, -0.439788818, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	Part = New("Part",Gaunty2,"Part",{BrickColor = BrickColor.new("Black"),Material = Enum.Material.Metal,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.15999985, 0.0700000003, 0.0700000003),CFrame = CFrame.new(-5.66765499, 2.53595734, -78.107933, 1.00000179, -2.26282282e-09, 1.11758709e-08, -2.28465069e-09, 1.00000179, 1.39698386e-08, 1.11758709e-08, 1.39698386e-08, 1.00000179),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.105882, 0.164706, 0.207843),})
	mot = New("Motor",Part,"mot",{Part0 = Part,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, 1.00000119, -1.44791557e-09, 7.4505806e-09, -1.44063961e-09, 1.00000119, 9.31322575e-09, 7.4505806e-09, 9.31322575e-09, 1.00000119),C1 = CFrame.new(0.0151295662, -0.479759216, -0.451416016, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	Part = New("Part",Gaunty2,"Part",{BrickColor = BrickColor.new("Black"),Material = Enum.Material.Metal,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.15999985, 0.0700000003, 0.0700000003),CFrame = CFrame.new(-5.66765499, 2.5359571, -77.8179092, 1.00000179, -2.26282282e-09, 1.11758709e-08, -2.28465069e-09, 1.00000179, 1.39698386e-08, 1.11758709e-08, 1.39698386e-08, 1.00000179),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.105882, 0.164706, 0.207843),})
	mot = New("Motor",Part,"mot",{Part0 = Part,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, 1.00000119, -1.44791557e-09, 7.4505806e-09, -1.44063961e-09, 1.00000119, 9.31322575e-09, 7.4505806e-09, 9.31322575e-09, 1.00000119),C1 = CFrame.new(0.0123701096, -0.48288393, -0.161422729, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	Part = New("Part",Gaunty2,"Part",{BrickColor = BrickColor.new("Black"),Material = Enum.Material.Metal,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.15999985, 0.0700000003, 0.0700000003),CFrame = CFrame.new(-5.66765499, 2.5359571, -77.4879227, 1.00000179, -2.26282282e-09, 1.11758709e-08, -2.28465069e-09, 1.00000179, 1.39698386e-08, 1.11758709e-08, 1.39698386e-08, 1.00000179),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.105882, 0.164706, 0.207843),})
	mot = New("Motor",Part,"mot",{Part0 = Part,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, 1.00000119, -1.44791557e-09, 7.4505806e-09, -1.44063961e-09, 1.00000119, 9.31322575e-09, 7.4505806e-09, 9.31322575e-09, 1.00000119),C1 = CFrame.new(0.00923013687, -0.48643899, 0.168533325, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	Part = New("Part",Gaunty2,"Part",{BrickColor = BrickColor.new("Black"),Material = Enum.Material.Metal,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.15999985, 0.0700000003, 0.0700000003),CFrame = CFrame.new(-5.66765499, 2.53595662, -77.1979218, 1.00000179, -2.26282282e-09, 1.11758709e-08, -2.28465069e-09, 1.00000179, 1.39698386e-08, 1.11758709e-08, 1.39698386e-08, 1.00000179),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.105882, 0.164706, 0.207843),})
	mot = New("Motor",Part,"mot",{Part0 = Part,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, 1.00000119, -1.44791557e-09, 7.4505806e-09, -1.44063961e-09, 1.00000119, 9.31322575e-09, 7.4505806e-09, 9.31322575e-09, 1.00000119),C1 = CFrame.new(0.00647068024, -0.489563465, 0.458503723, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	Part = New("Part",Gaunty2,"Part",{BrickColor = BrickColor.new("Black"),Material = Enum.Material.Metal,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.15999985, 0.0700000003, 0.0700000003),CFrame = CFrame.new(-6.13765478, 3.62595797, -77.6579132, -5.49480319e-08, -2.26282282e-09, 1.00000179, -1.67638063e-08, 1.00000179, -1.8189894e-09, -1.00000179, 1.39698386e-08, -3.25962901e-08),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.105882, 0.164706, 0.207843),})
	mot = New("Motor",Part,"mot",{Part0 = Part,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, -5.12227416e-08, -1.11758709e-08, -1.00000119, -1.44063961e-09, 1.00000119, 9.31322575e-09, 1.00000119, -9.89530236e-10, -3.63215804e-08),C1 = CFrame.new(-0.471121788, 0.600130081, 0.00566101074, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	Part = New("Part",Gaunty2,"Part",{BrickColor = BrickColor.new("Black"),Material = Enum.Material.Metal,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.15999985, 0.0700000003, 0.0700000003),CFrame = CFrame.new(-5.82765484, 3.6259582, -77.6579132, -5.49480319e-08, -2.26282282e-09, 1.00000179, -1.67638063e-08, 1.00000179, -1.8189894e-09, -1.00000179, 1.39698386e-08, -3.25962901e-08),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.105882, 0.164706, 0.207843),})
	mot = New("Motor",Part,"mot",{Part0 = Part,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, -5.12227416e-08, -1.11758709e-08, -1.00000119, -1.44063961e-09, 1.00000119, 9.31322575e-09, 1.00000119, -9.89530236e-10, -3.63215804e-08),C1 = CFrame.new(-0.161154747, 0.603517056, 0.008644104, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	Part = New("Part",Gaunty2,"Part",{BrickColor = BrickColor.new("Black"),Material = Enum.Material.Metal,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.15999985, 0.0700000003, 0.0700000003),CFrame = CFrame.new(-5.51765347, 3.62595868, -77.6579132, -5.49480319e-08, -2.26282282e-09, 1.00000179, -1.67638063e-08, 1.00000179, -1.8189894e-09, -1.00000179, 1.39698386e-08, -3.25962901e-08),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.105882, 0.164706, 0.207843),})
	mot = New("Motor",Part,"mot",{Part0 = Part,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, -5.12227416e-08, -1.11758709e-08, -1.00000119, -1.44063961e-09, 1.00000119, 9.31322575e-09, 1.00000119, -9.89530236e-10, -3.63215804e-08),C1 = CFrame.new(0.148813725, 0.60690403, 0.0116348267, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	Part = New("Part",Gaunty2,"Part",{BrickColor = BrickColor.new("Black"),Material = Enum.Material.Metal,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.15999985, 0.0700000003, 0.0700000003),CFrame = CFrame.new(-5.2176528, 3.62595916, -77.6579132, -5.49480319e-08, -2.26282282e-09, 1.00000179, -1.67638063e-08, 1.00000179, -1.8189894e-09, -1.00000179, 1.39698386e-08, -3.25962901e-08),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.105882, 0.164706, 0.207843),})
	mot = New("Motor",Part,"mot",{Part0 = Part,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, -5.12227416e-08, -1.11758709e-08, -1.00000119, -1.44063961e-09, 1.00000119, 9.31322575e-09, 1.00000119, -9.89530236e-10, -3.63215804e-08),C1 = CFrame.new(0.448782444, 0.610181808, 0.0145187378, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	Part = New("Part",Gaunty2,"Part",{BrickColor = BrickColor.new("Black"),Material = Enum.Material.Metal,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.15999985, 0.0700000003, 0.0700000003),CFrame = CFrame.new(-5.21765327, 2.53595757, -77.6579132, -5.49480319e-08, -2.26282282e-09, 1.00000179, -1.67638063e-08, 1.00000179, -1.8189894e-09, -1.00000179, 1.39698386e-08, -3.25962901e-08),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.105882, 0.164706, 0.207843),})
	mot = New("Motor",Part,"mot",{Part0 = Part,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, -5.12227416e-08, -1.11758709e-08, -1.00000119, -1.44063961e-09, 1.00000119, 9.31322575e-09, 1.00000119, -9.89530236e-10, -3.63215804e-08),C1 = CFrame.new(0.460801601, -0.479691029, 0.00289154053, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	Part = New("Part",Gaunty2,"Part",{BrickColor = BrickColor.new("Black"),Material = Enum.Material.Metal,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.15999985, 0.0700000003, 0.0700000003),CFrame = CFrame.new(-5.51765299, 2.53595757, -77.6579361, -5.49480319e-08, -2.26282282e-09, 1.00000179, -1.67638063e-08, 1.00000179, -1.8189894e-09, -1.00000179, 1.39698386e-08, -3.25962901e-08),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.105882, 0.164706, 0.207843),})
	mot = New("Motor",Part,"mot",{Part0 = Part,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, -5.12227416e-08, -1.11758709e-08, -1.00000119, -1.44063961e-09, 1.00000119, 9.31322575e-09, 1.00000119, -9.89530236e-10, -3.63215804e-08),C1 = CFrame.new(0.160833836, -0.48296833, -1.52587891e-05, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	Part = New("Part",Gaunty2,"Part",{BrickColor = BrickColor.new("Black"),Material = Enum.Material.Metal,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.15999985, 0.0700000003, 0.0700000003),CFrame = CFrame.new(-5.82765436, 2.5359571, -77.6579208, -5.49480319e-08, -2.26282282e-09, 1.00000179, -1.67638063e-08, 1.00000179, -1.8189894e-09, -1.00000179, 1.39698386e-08, -3.25962901e-08),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.105882, 0.164706, 0.207843),})
	mot = New("Motor",Part,"mot",{Part0 = Part,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, -5.12227416e-08, -1.11758709e-08, -1.00000119, -1.44063961e-09, 1.00000119, 9.31322575e-09, 1.00000119, -9.89530236e-10, -3.63215804e-08),C1 = CFrame.new(-0.149134636, -0.486355305, -0.00299072266, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	Part = New("Part",Gaunty2,"Part",{BrickColor = BrickColor.new("Black"),Material = Enum.Material.Metal,Shape = Enum.PartType.Cylinder,Size = Vector3.new(1.15999985, 0.0700000003, 0.0700000003),CFrame = CFrame.new(-6.13765478, 2.53595734, -77.6579208, -5.49480319e-08, -2.26282282e-09, 1.00000179, -1.67638063e-08, 1.00000179, -1.8189894e-09, -1.00000179, 1.39698386e-08, -3.25962901e-08),BottomSurface = Enum.SurfaceType.Smooth,TopSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.105882, 0.164706, 0.207843),})
	mot = New("Motor",Part,"mot",{Part0 = Part,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, -5.12227416e-08, -1.11758709e-08, -1.00000119, -1.44063961e-09, 1.00000119, 9.31322575e-09, 1.00000119, -9.89530236e-10, -3.63215804e-08),C1 = CFrame.new(-0.459102154, -0.489741802, -0.00597381592, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("WedgePart",Gaunty2,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,Size = Vector3.new(1.14999998, 0.640000045, 0.25000003),CFrame = CFrame.new(-5.66203403, 3.45095801, -77.7865524, 1.00000179, -2.26282282e-09, 1.11758709e-08, -2.28465069e-09, 1.00000179, 1.39698386e-08, 1.11758709e-08, 1.39698386e-08, 1.00000179),BottomSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, 1.00000119, -1.44791557e-09, 7.4505806e-09, -1.44063961e-09, 1.00000119, 9.31322575e-09, 7.4505806e-09, 9.31322575e-09, 1.00000119),C1 = CFrame.new(0.00760221481, 0.431732655, -0.120254517, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("WedgePart",Gaunty2,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,Size = Vector3.new(1.14999998, 0.640000045, 0.280000031),CFrame = CFrame.new(-5.66203356, 3.45095849, -77.521553, -1.00000179, -2.26282282e-09, -9.87201929e-08, 2.28465069e-09, 1.00000179, -1.39698386e-08, 7.63684511e-08, 1.39698386e-08, -1.00000179),BottomSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, -1.00000119, 1.45519152e-09, 8.00937414e-08, -1.44063961e-09, 1.00000119, 9.31322575e-09, -9.49949026e-08, -9.31322575e-09, -1.00000119),C1 = CFrame.new(0.00508117676, 0.428878307, 0.144721985, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("WedgePart",Gaunty2,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,Size = Vector3.new(1.14999998, 0.640000045, 0.25000003),CFrame = CFrame.new(-5.66203308, 2.81095791, -77.7865601, -1.00000179, 8.98216967e-08, 1.11758709e-08, -8.52742232e-08, -1.00000179, 1.39698386e-08, -1.11758709e-08, -1.39698386e-08, 1.00000179),BottomSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, -1.00000119, -8.61036824e-08, -7.4505806e-09, 8.89922376e-08, -1.00000119, -9.31322575e-09, 7.4505806e-09, 9.31322575e-09, 1.00000119),C1 = CFrame.new(0.0146603584, -0.208191872, -0.127082825, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	NeonPart = New("WedgePart",Gaunty2,"NeonPart",{BrickColor = BrickColor.new("Institutional white"),Material = Enum.Material.Neon,Size = Vector3.new(1.14999998, 0.640000045, 0.280000031),CFrame = CFrame.new(-5.6620326, 2.82095814, -77.5215454, 1.00000179, -8.52887752e-08, 7.63684511e-08, -8.98362487e-08, -1.00000179, -1.39698386e-08, 9.87201929e-08, -1.39698386e-08, -1.00000179),BottomSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.972549, 0.972549, 0.972549),})
	mot = New("Motor",NeonPart,"mot",{Part0 = NeonPart,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, 1.00000119, -8.89995135e-08, 9.49949026e-08, -8.61109584e-08, -1.00000119, -9.31322575e-09, 8.00937414e-08, -9.31322575e-09, -1.00000119),C1 = CFrame.new(0.012029171, -0.201047897, 0.138008118, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})
	Wedge = New("WedgePart",Gaunty2,"Wedge",{BrickColor = BrickColor.new("Black"),Size = Vector3.new(1.1099999, 0.569999993, 1.13),CFrame = CFrame.new(-5.6508193, 4.06113243, -77.6620178, -5.49480319e-08, -2.26282282e-09, 1.00000179, -1.67638063e-08, 1.00000179, -1.8189894e-09, -1.00000179, 1.39698386e-08, -3.25962901e-08),BottomSurface = Enum.SurfaceType.Smooth,Color = Color3.new(0.105882, 0.164706, 0.207843),})
	mot = New("Motor",Wedge,"mot",{Part0 = Wedge,Part1 = Handle2,C0 = CFrame.new(0, 0, 0, -5.12227416e-08, -1.11758709e-08, -1.00000119, -1.44063961e-09, 1.00000119, 9.31322575e-09, 1.00000119, -9.89530236e-10, -3.63215804e-08),C1 = CFrame.new(0.0109024048, 1.04061604, 0.010887146, 0.999894261, -0.0110270018, -0.00951499958, 0.010924357, 0.999882579, -0.0107729975, 0.00963267777, 0.0106679145, 0.999897003),})


	NewInstance = function(instance,parent,properties)
		local inst = Instance.new(instance,parent)
		if(properties)then
			for i,v in next, properties do
				pcall(function() inst[i] = v end)
			end
		end
		return inst;
	end

	local HW = NewInstance('Motor', char, {Part0 = ra, Part1 = Handle, C0 = CF(0,-.51,0)})
	local HW2 = NewInstance('Motor', char, {Part0 = la, Part1 = Handle2, C0 = CF(0,-.51,0) * angles(Rad(0),Rad(180),Rad(0))})

	for _,v in next, Gaunty:children() do
		v.CanCollide = false
	end
	for _,v in next, Gaunty2:children() do
		v.CanCollide = false
	end
	local all, last = {}, nil
	ArmourParts = {}
	NeonParts = {}
	function scan(p)
		for _, v in pairs(p:GetChildren()) do
			if v:IsA("BasePart") then
				if v.BrickColor == BrickColor.new("Black") then
					table.insert(ArmourParts, v)
				end
				if v.BrickColor == BrickColor.new("Institutional white") then
					table.insert(NeonParts, v)
				end
				if last then
					local w = Instance.new("Weld")
					w.Part0, w.Part1 = last, v
					w.C0 = v.CFrame:toObjectSpace(last.CFrame):inverse()
					w.Parent = last
				end
				table.insert(all, v)
				last = v
			end
			scan(v)
		end
	end
	scan(Gaunty)
	local all2, last2 = {}, nil
	ArmourParts2 = {}
	NeonParts2 = {}
	function scan2(p)
		for _, v in pairs(p:GetChildren()) do
			if v:IsA("BasePart") then
				if v.BrickColor == BrickColor.new("Black") then
					table.insert(ArmourParts2, v)
				end
				if v.BrickColor == BrickColor.new("Institutional white") then
					table.insert(NeonParts2, v)
				end
				if last2 then
					local w = Instance.new("Weld")
					w.Part0, w.Part1 = last2, v
					w.C0 = v.CFrame:toObjectSpace(last2.CFrame):inverse()
					w.Parent = last2
				end
				table.insert(all2, v)
				last2 = v
			end
			scan2(v)
		end
	end
	scan2(Gaunty2)
	for i, v in pairs(ArmourParts) do
		v.BrickColor = BrickC("Black")
	end
	for i, v in pairs(NeonParts) do
		v.BrickColor = BrickC("Really red")
	end
	for i, v in pairs(ArmourParts2) do
		v.BrickColor = BrickC("Black")
	end
	for i, v in pairs(NeonParts2) do
		v.BrickColor = BrickC("Really red")
	end
	maincolor = BrickC("Really red")
	-------------------------------------------------------
	--Start Music Option--
	-------------------------------------------------------
	local Music = Instance.new("Sound",char)
	Music.Volume = 2.5
	Music.SoundId = "rbxassetid://550578451"
	Music.Looped = true
	Music.Pitch = 1 --Pitcher
	Music:Play()
	-------------------------------------------------------
	--End Music Option--
	-------------------------------------------------------
	local naeeym2 = Instance.new("BillboardGui",char)
	naeeym2.AlwaysOnTop = true
	naeeym2.Size = UDim2.new(5,35,2,35)
	naeeym2.StudsOffset = Vector3.new(0,2,0)
	naeeym2.Adornee = hed
	naeeym2.Name = "Name"

	local tecks2 = Instance.new("TextLabel",naeeym2)
	tecks2.BackgroundTransparency = 1
	tecks2.TextScaled = true
	tecks2.BorderSizePixel = 0
	tecks2.Text = "Ender"
	tecks2.Font = "Garamond"
	tecks2.TextSize = 30
	tecks2.TextStrokeTransparency = 0
	tecks2.TextColor3 = Color3.new(0,0,0)
	tecks2.TextStrokeColor3 = Color3.new(0, 0, 0)
	tecks2.Size = UDim2.new(1,0,0.5,0)
	tecks2.Parent = naeeym2

	function chatfunc(text, color)
		local chat = coroutine.wrap(function()
			if char:FindFirstChild("TalkingBillBoard") ~= nil then
				char:FindFirstChild("TalkingBillBoard"):destroy()
			end
			local naeeym2 = Instance.new("BillboardGui", char)
			naeeym2.Size = UDim2.new(0, 100, 0, 40)
			naeeym2.StudsOffset = Vector3.new(0, 5, 0)
			naeeym2.Adornee = hed
			naeeym2.Name = "TalkingBillBoard"
			local tecks2 = Instance.new("TextLabel", naeeym2)
			tecks2.BackgroundTransparency = 1
			tecks2.BorderSizePixel = 0
			tecks2.Text = ""
			tecks2.Font = "SciFi"
			tecks2.TextSize = 30
			tecks2.TextStrokeTransparency = 0
			tecks2.TextColor3 = color
			tecks2.TextStrokeColor3 = Color3.new(0, 0, 0)
			tecks2.Size = UDim2.new(1, 0, 0.5, 0)
			local tecks3 = Instance.new("TextLabel", naeeym2)
			tecks3.BackgroundTransparency = 1
			tecks3.BorderSizePixel = 0
			tecks3.Text = ""
			tecks3.Font = "SciFi"
			tecks3.TextSize = 30
			tecks3.TextStrokeTransparency = 0
			tecks3.TextColor3 = Color3.new(0, 0, 0)
			tecks3.TextStrokeColor3 = color
			tecks3.Size = UDim2.new(1, 0, 0.5, 0)
			coroutine.resume(coroutine.create(function()
				while true do
					swait(1)
					tecks2.TextColor3 = BrickColor.random().Color
					tecks3.TextStrokeColor3 = BrickColor.random().Color
					tecks2.Position = UDim2.new(0, math.random(-5, 5), 0, math.random(-5, 5))
					tecks3.Position = UDim2.new(0, math.random(-5, 5), 0, math.random(-5, 5))
					tecks2.Rotation = math.random(-5, 5)
					tecks3.Rotation = math.random(-5, 5)
				end
			end))
			for i = 1, string.len(text) do
				CFuncs.Sound.Create("rbxassetid://274118116", char, 0.25, 0.115)
				tecks2.Text = string.sub(text, 1, i)
				tecks3.Text = string.sub(text, 1, i)
				swait(1)
			end
			wait(1)
			local randomrot = math.random(1, 2)
			if randomrot == 1 then
				for i = 1, 50 do
					swait()
					tecks2.Rotation = tecks2.Rotation - 0.75
					tecks2.TextStrokeTransparency = tecks2.TextStrokeTransparency + 0.04
					tecks2.TextTransparency = tecks2.TextTransparency + 0.04
					tecks3.Rotation = tecks2.Rotation + 0.75
					tecks3.TextStrokeTransparency = tecks2.TextStrokeTransparency + 0.04
					tecks3.TextTransparency = tecks2.TextTransparency + 0.04
				end
			elseif randomrot == 2 then
				for i = 1, 50 do
					swait()
					tecks2.Rotation = tecks2.Rotation + 0.75
					tecks2.TextStrokeTransparency = tecks2.TextStrokeTransparency + 0.04
					tecks2.TextTransparency = tecks2.TextTransparency + 0.04
					tecks3.Rotation = tecks2.Rotation - 0.75
					tecks3.TextStrokeTransparency = tecks2.TextStrokeTransparency + 0.04
					tecks3.TextTransparency = tecks2.TextTransparency + 0.04
				end
			end
			naeeym2:Destroy()
		end)
		chat()
	end
	-------------------------------------------------------
	--Start Attacks N Stuff--
	-------------------------------------------------------
	local sine=0
	function HitboxFunction(Pose, lifetime, siz1, siz2, siz3, Radie, Min, Max, kb, atype)
		local Hitboxpart = Instance.new("Part", EffectModel)
		RemoveOutlines(Hitboxpart)
		Hitboxpart.Size = Vector3.new(siz1, siz2, siz3)
		Hitboxpart.CanCollide = false
		Hitboxpart.Transparency = 1
		Hitboxpart.Anchored = true
		Hitboxpart.CFrame = Pose
		game:GetService("Debris"):AddItem(Hitboxpart, lifetime)
		MagniDamage(Hitboxpart, Radie, Min, Max, kb, atype)
	end
	wait2 = false
	combo = 1
	mouse.Button1Down:connect(function(key)
		if attack == false then
			attack = true
			hum.WalkSpeed = 3.01
			if combo == 1 and wait2 == false then
				wait2 = true
				for i = 0, 1.2, 0.1 do
					swait()
					character1.Reanimate.Part.Position = character1.Reanimate["Torso"].Position
					rootj.C0 = clerp(rootj.C0, RootCF * CFrame.new(0, -0.5, 0) * angles(math.rad(-5), math.rad(0), math.rad(-65)), 0.3)
					tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(math.rad(-10), math.rad(0), math.rad(-65)), 0.1)
					RW.C0 = clerp(RW.C0, CFrame.new(1.5, 0.5, 0.8) * angles(math.rad(90), math.rad(0), math.rad(20)), 0.1)
					LW.C0 = clerp(LW.C0, CFrame.new(-1.5, 0.5, 0) * angles(math.rad(-25), math.rad(0), math.rad(40)), 0.3)
					RH.C0 = clerp(RH.C0, CFrame.new(1, -1, -0.2) * RHCF * angles(math.rad(-2.5), math.rad(0), math.rad(-0)), 0.3)
					LH.C0 = clerp(LH.C0, CFrame.new(-1, -1, 0) * LHCF * angles(math.rad(-2.5), math.rad(15), math.rad(-20)), 0.3)
					character1.Reanimate.Part.Position = character1.Reanimate["Torso"].Position
				end
				CreateSound("138097048", ra, 3, .8)
				HitboxFunction(ra.CFrame, 0.01, 1, 1, 1, 7, 6, 9, 3, "Normal")
				for i = 0, 1.2, 0.1 do
					swait()
					character1.Reanimate.Part.Position = character1.Reanimate["Torso"].Position
					rootj.C0 = clerp(rootj.C0, RootCF * CFrame.new(0, -0.5, 0) * angles(math.rad(5), math.rad(0), math.rad(55)), 0.3)
					tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(math.rad(10), math.rad(0), math.rad(0)), 0.1)
					RW.C0 = clerp(RW.C0, CFrame.new(1.5, 0.5, -0.8) * angles(math.rad(95), math.rad(0), math.rad(40)), 0.1)
					LW.C0 = clerp(LW.C0, CFrame.new(-1.5, 0.5, 0) * angles(math.rad(-25), math.rad(0), math.rad(-10)), 0.3)
					RH.C0 = clerp(RH.C0, CFrame.new(1, -1, 0) * RHCF * angles(math.rad(-2.5), math.rad(-25), math.rad(-17)), 0.3)
					LH.C0 = clerp(LH.C0, CFrame.new(-1, -1, 0) * LHCF * angles(math.rad(-2.5), math.rad(-0), math.rad(0)), 0.3)
					character1.Reanimate.Part.Position = character1.Reanimate["Torso"].Position
				end
				combo = 2
			end
			if combo == 2 and wait2 == false then
				wait2 = true
				for i = 0, 1.2, 0.1 do
					swait()
					character1.Reanimate.Part.Position = character1.Reanimate["Torso"].Position
					rootj.C0 = clerp(rootj.C0, RootCF * CFrame.new(0, -0.5, 0) * angles(math.rad(-5), math.rad(0), math.rad(65)), 0.3)
					tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(math.rad(-10), math.rad(0), math.rad(65)), 0.1)
					RW.C0 = clerp(RW.C0, CFrame.new(1.5, 0.5, 0.8) * angles(math.rad(-25), math.rad(0), math.rad(40)), 0.1)
					LW.C0 = clerp(LW.C0, CFrame.new(-1.5, 0.5, 0) * angles(math.rad(90), math.rad(0), math.rad(20)), 0.3)
					RH.C0 = clerp(RH.C0, CFrame.new(1, -1, -0.2) * RHCF * angles(math.rad(-2.5), math.rad(0), math.rad(-0)), 0.3)
					LH.C0 = clerp(LH.C0, CFrame.new(-1, -1, 0) * LHCF * angles(math.rad(-2.5), math.rad(15), math.rad(-20)), 0.3)
					character1.Reanimate.Part.Position = character1.Reanimate["Torso"].Position
				end
				CreateSound("138097048", ra, 3, .8)
				HitboxFunction(ra.CFrame, 0.01, 1, 1, 1, 7, 6, 9, 3, "Normal")
				for i = 0, 1.2, 0.1 do
					swait()
					character1.Reanimate.Part.Position = character1.Reanimate["Torso"].Position
					rootj.C0 = clerp(rootj.C0, RootCF * CFrame.new(0, -0.5, 0) * angles(math.rad(5), math.rad(0), math.rad(-55)), 0.3)
					tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(math.rad(10), math.rad(0), math.rad(0)), 0.1)
					RW.C0 = clerp(RW.C0, CFrame.new(1.5, 0.5, 0) * angles(math.rad(-25), math.rad(0), math.rad(10)), 0.1)
					LW.C0 = clerp(LW.C0, CFrame.new(-1.5, 0.5, -0.8) * angles(math.rad(95), math.rad(0), math.rad(-40)), 0.3)
					RH.C0 = clerp(RH.C0, CFrame.new(1, -1, 0) * RHCF * angles(math.rad(-2.5), math.rad(-25), math.rad(-17)), 0.3)
					LH.C0 = clerp(LH.C0, CFrame.new(-1, -1, 0) * LHCF * angles(math.rad(-2.5), math.rad(-0), math.rad(0)), 0.3)
					character1.Reanimate.Part.Position = character1.Reanimate["Torso"].Position
				end
				combo = 3
			end
			if combo == 3 and wait2 == false then
				wait2 = true
				for i = 0, 1.2, 0.1 do
					swait()
					character1.Reanimate.Part.Position = character1.Reanimate["Torso"].Position
					rootj.C0 = clerp(rootj.C0, RootCF * CFrame.new(0, -0.5, 0) * angles(math.rad(-5), math.rad(0), math.rad(-35)), 0.3)
					tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(math.rad(-10), math.rad(0), math.rad(0)), 0.1)
					RW.C0 = clerp(RW.C0, CFrame.new(1.5, 0.5, 0.8) * angles(math.rad(90), math.rad(0), math.rad(20)), 0.1)
					LW.C0 = clerp(LW.C0, CFrame.new(-1.5, 0.5, 0) * angles(math.rad(-25), math.rad(0), math.rad(-10)), 0.3)
					RH.C0 = clerp(RH.C0, CFrame.new(1, -1, -0.2) * RHCF * angles(math.rad(-2.5), math.rad(0), math.rad(-0)), 0.3)
					LH.C0 = clerp(LH.C0, CFrame.new(-1, -1, 0) * LHCF * angles(math.rad(-2.5), math.rad(15), math.rad(-20)), 0.3)
					character1.Reanimate.Part.Position = character1.Reanimate["Torso"].Position
				end
				CreateSound("138097048", ra, 3, .8)
				HitboxFunction(ra.CFrame, 0.01, 1, 1, 1, 7, 24, 36, 3, "Normal")
				for i = 0, 1.2, 0.1 do
					swait()
					character1.Reanimate.Part.Position = character1.Reanimate["Torso"].Position
					rootj.C0 = clerp(rootj.C0, RootCF * CFrame.new(0, -0.5, 0) * angles(math.rad(5), math.rad(0), math.rad(35)), 0.3)
					tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(math.rad(10), math.rad(0), math.rad(0)), 0.1)
					RW.C0 = clerp(RW.C0, CFrame.new(1.5, 0.5, -0.8) * angles(math.rad(96), math.rad(0), math.rad(10)), 0.1)
					LW.C0 = clerp(LW.C0, CFrame.new(-1.5, 0.5, 0) * angles(math.rad(-25), math.rad(0), math.rad(-10)), 0.3)
					RH.C0 = clerp(RH.C0, CFrame.new(1, -1, 0) * RHCF * angles(math.rad(-2.5), math.rad(-25), math.rad(-0)), 0.3)
					LH.C0 = clerp(LH.C0, CFrame.new(-1, -1, 0) * LHCF * angles(math.rad(-2.5), math.rad(-0), math.rad(0)), 0.3)
					character1.Reanimate.Part.Position = character1.Reanimate["Torso"].Position
				end
				Effects.Sphere.Create(maincolor, ra.CFrame * CFrame.new(0,-2,0) , 85, 85, 85, 1.1, 1.1, 1.1, 0.02)
				Effects.Ring.Create(maincolor, ra.CFrame * CFrame.new(0,-2,0) , 2, 2, 2, 1.1, 1.1, 1.1, 0.03)
				for i = 0, 2 do
					SphereAura(2, 0.2, "Add", ra.CFrame * CFrame.Angles(math.rad(-90 + math.random(-20, 20)), math.rad(math.random(-20, 20)), math.rad(math.random(-20, 20))), 0.5, 0.5, 5, -0.005, maincolor, 0)
				end
				coroutine.resume(coroutine.create(function() 
					for i = 0,1.8,0.1 do
						swait()
						hum.CameraOffset = Vector3.new(Mrandom(-1,1),0,Mrandom(-1,1))
					end
					for i = 0,1.8,0.1 do
						swait()
						hum.CameraOffset = Vector3.new(0,0,0)
					end
				end))
				HitboxFunction(ra.CFrame, 0.01, 1, 1, 1, 7, 24, 36, 3, "Normal")
				for i = 0, 1.2, 0.1 do
					swait()
					rootj.C0 = clerp(rootj.C0, RootCF * CFrame.new(0, -0.5, 0) * angles(math.rad(5), math.rad(0), math.rad(-35)), 0.3)
					tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(math.rad(10), math.rad(0), math.rad(0)), 0.1)
					RW.C0 = clerp(RW.C0, CFrame.new(1.5, 0.5, -0.8) * angles(math.rad(25), math.rad(0), math.rad(10)), 0.1)
					LW.C0 = clerp(LW.C0, CFrame.new(-1.5, 0.5, 0) * angles(math.rad(-25), math.rad(0), math.rad(-10)), 0.3)
					RH.C0 = clerp(RH.C0, CFrame.new(1, -1, 0) * RHCF * angles(math.rad(-2.5), math.rad(-25), math.rad(-0)), 0.3)
					LH.C0 = clerp(LH.C0, CFrame.new(-1, -1, 0) * LHCF * angles(math.rad(-2.5), math.rad(-0), math.rad(0)), 0.3)
				end
				combo = 4
			end
			if combo == 4 and wait2 == false then
				for i = 0,1.2,0.1 do
					swait()
					rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1 * Cos(sine / 20)) * angles(Rad(-20), Rad(0), Rad(0)), 0.15)
					tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(-20 - 2.5 * Sin(sine / 20)), Rad(0), Rad(0)), 0.3)
					RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-4.5), Rad(0), Rad(-20)), 0.15)
					LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 * Cos(sine / 20), -.4 + 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-6.5), Rad(5 * Cos(sine / 20)), Rad(25)), 0.15)
					RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 20), 0.025 * Cos(sine / 20)) * angles(Rad(200), Rad(0), Rad(25 - 2.5 * Sin(sine / 20))), 0.1)
					LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 20), 0.025 * Cos(sine / 20)) * angles(Rad(200), Rad(0), Rad(-25 + 2.5 * Sin(sine / 20))), 0.1)
				end
				SphereAura(6, 0.3, "Add", root.CFrame * CF(0,-2,0) * angles(Rad(Mrandom(-360, 360)), Rad(Mrandom(-360, 360)), Rad(Mrandom(-360, 360))), 0.5, 0.5, 5, -0.005, maincolor, 0)
				SphereAura(6, 0.3, "Add", root.CFrame * CF(0,-2,0) * angles(Rad(Mrandom(-360, 360)), Rad(Mrandom(-360, 360)), Rad(Mrandom(-360, 360))), 0.5, 0.5, 5, -0.005, maincolor, 0)
				Effects.Sphere.Create(maincolor, root.CFrame * CFrame.new(0,-2,0) , 85, 85, 85, 15.1, 15.1, 15.1, 0.01)
				CreateSound("331666100", char, 10, 1)
				for i, v in pairs(FindNearestHead(tors.CFrame.p, 14.5)) do
					if v:FindFirstChild("Head") then
						SoulSteal(v)
						Eviscerate(v)
					end
				end
				coroutine.resume(coroutine.create(function() 
					for i = 0,1.8,0.1 do
						swait()
						hum.CameraOffset = Vector3.new(Mrandom(-1,1),0,Mrandom(-1,1))
					end
					for i = 0,1.8,0.1 do
						swait()
						hum.CameraOffset = Vector3.new(0,0,0)
					end
				end))
				for i = 1,4.7,0.1 do
					rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -1.4 + 0.1 * Cos(sine / 20)) * angles(Rad(45), Rad(0), Rad(0)), 0.15)
					tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(35), Rad(0), Rad(0)), 0.3)
					RH.C0 = clerp(RH.C0, CF(1, .4 - 0.1 * Cos(sine / 20), -.6 + 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-5), Rad(0), Rad(45)), 0.15)
					LH.C0 = clerp(LH.C0, CF(-1, -0.6 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-5), Rad(0), Rad(-0)), 0.15)
					RW.C0 = clerp(RW.C0, CF(1.2, 0.1 + 0.05 * Sin(sine / 30), -.4 + 0.025 * Cos(sine / 20)) * angles(Rad(65), Rad(0), Rad(-34)), 0.1)
					LW.C0 = clerp(LW.C0, CF(-1.2, 0.1 + 0.05 * Sin(sine / 30), -.4 + 0.025 * Cos(sine / 20)) * angles(Rad(65), Rad(0), Rad(34)), 0.1)
				end
				wait(.6)
				combo = 1
			end
			hum.WalkSpeed = 16
			wait2 = false
			attack = false
		end
	end)
	function Destruction()
		attack = true
		local Ring1 = Instance.new("Part", char)
		Ring1.Anchored = true
		Ring1.BrickColor = maincolor
		Ring1.CanCollide = false
		Ring1.FormFactor = 3
		Ring1.Name = "Ring"
		Ring1.Material = "Neon"
		Ring1.Size = Vector3.new(1, 0.05, 1)
		Ring1.Transparency = 1
		Ring1.TopSurface = 0
		Ring1.BottomSurface = 0
		local Ring1Mesh = Instance.new("SpecialMesh", Ring1)
		Ring1Mesh.MeshType = "Brick"
		Ring1Mesh.Name = "SizeMesh"
		Ring1Mesh.Scale = Vector3.new(0, 1, 0)
		local InnerRing1 = Ring1:Clone()
		InnerRing1.Parent = char
		InnerRing1.Transparency = 0
		InnerRing1.BrickColor = BrickColor.new("New Yeller")
		InnerRing1.Size = Vector3.new(1, 1, 1)
		local InnerRing1Mesh = InnerRing1.SizeMesh
		InnerRing1Mesh.Scale = Vector3.new(0, 0, 0)
		InnerRing1Mesh.MeshType = "Sphere"
		Ring1:Destroy()
		for i = 0, 5, 0.1 do
			swait()
			SphereAura(7, 0.12, "Add", ra.CFrame * CF(0,-2,0) * angles(Rad(Mrandom(-360, 360)), Rad(Mrandom(-360, 360)), Rad(Mrandom(-360, 360))), 0.5, 0.5, 5, -0.005, maincolor, 0)
			SphereAura(7, 0.12, "Add", ra.CFrame * CF(0,-2,0) * angles(Rad(Mrandom(-360, 360)), Rad(Mrandom(-360, 360)), Rad(Mrandom(-360, 360))), 0.5, 0.5, 5, -0.005, BrickC("Institutional white"), 0)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1 * Cos(sine / 20)) * angles(Rad(5), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(-4.5 * Sin(sine / 30)), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-12.5 + 3 * Sin(sine / 20)), Rad(0), Rad(0 + 2.5 * Sin(sine / 20))), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5 + 3 * Sin(sine / 20)), Rad(0), Rad(0 + 2.5 * Sin(sine / 20))), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.1, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(90), Rad(0), Rad(-25)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.1, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(90), Rad(0), Rad(25)), 0.1)
			character1.Reanimate.Part.Position = mouse.Hit.p
			root.CFrame = FaceMouse()[1]
		end
		InnerRing1.Transparency = 1
		InnerRing1.CFrame = root.CFrame * CF(0, 0.5, 0) + root.CFrame.lookVector * 5
		CreateSound("294188875", char, 2.3, 1)
		local a = IT("Part", char)
		a.Name = "Direction"
		a.Anchored = true
		a.BrickColor = maincolor
		a.Material = "Neon"
		a.Transparency = 0
		a.Shape = "Cylinder"
		a.CanCollide = false
		local a2 = IT("Part", char)
		a2.Name = "Direction"
		a2.Anchored = true
		a2.BrickColor = maincolor
		a2.Color = maincolor.Color
		a2.Material = "Neon"
		a2.Transparency = 0.5
		a2.Shape = "Cylinder"
		a2.CanCollide = false
		local ba = IT("Part", char)
		ba.Name = "HitDirect"
		ba.Anchored = true
		ba.BrickColor = maincolor
		ba.Material = "Neon"
		ba.Transparency = 1
		ba.CanCollide = false
		local ray = Ray.new(InnerRing1.CFrame.p, (mouse.Hit.p - InnerRing1.CFrame.p).unit * 1000)
		local ignore = char
		local hit, position, normal = workspace:FindPartOnRay(ray, ignore)
		a.BottomSurface = 10
		a.TopSurface = 10
		a2.BottomSurface = 10
		a2.TopSurface = 10
		local distance = (InnerRing1.CFrame.p - position).magnitude
		a.Size = Vector3.new(distance, 1, 1)
		a.CFrame = CF(InnerRing1.CFrame.p, position) * CF(0, 0, -distance / 2)
		a2.Size = Vector3.new(distance, 1, 1)
		a2.CFrame = CF(InnerRing1.CFrame.p, position) * CF(0, 0, -distance / 2)
		ba.CFrame = CF(InnerRing1.CFrame.p, position) * CF(0, 0, -distance)
		a.CFrame = a.CFrame * angles(0, Rad(90), 0)
		a2.CFrame = a2.CFrame * angles(0, Rad(90), 0)
		game:GetService("Debris"):AddItem(a, 20)
		game:GetService("Debris"):AddItem(a2, 20)
		game:GetService("Debris"):AddItem(ba, 20)
		local msh = Instance.new("SpecialMesh", a)
		msh.MeshType = "Sphere"
		msh.Scale = Vector3.new(1, 25, 25)
		local msh2 = Instance.new("SpecialMesh", a2)
		msh2.MeshType = "Sphere"
		msh2.Scale = Vector3.new(1, 30, 30)
		for i = 0, 10, 0.1 do
			swait()
			character1.Reanimate.Part.Position = mouse.Hit.p
			root.CFrame = FaceMouse()[1]
			hum.CameraOffset = Vector3.new(Mrandom(-1,1),0,Mrandom(-1,1))
			a2.Color = maincolor.Color
			InnerRing1.CFrame = root.CFrame * CF(0, 0.5, 0) + root.CFrame.lookVector * 4
			ray = Ray.new(InnerRing1.CFrame.p, (mouse.Hit.p - InnerRing1.CFrame.p).unit * 1000)
			hit, position, normal = workspace:FindPartOnRay(ray, ignore)
			distance = (InnerRing1.CFrame.p - position).magnitude
			a.Size = Vector3.new(distance, 1, 1)
			a.CFrame = CF(InnerRing1.CFrame.p, position) * CF(0, 0, -distance / 2)
			a2.Size = Vector3.new(distance, 1, 1)
			a2.CFrame = CF(InnerRing1.CFrame.p, position) * CF(0, 0, -distance / 2)
			ba.CFrame = CF(InnerRing1.CFrame.p, position) * CF(0, 0, -distance)
			a.CFrame = a.CFrame * angles(0, Rad(90), 0)
			a2.CFrame = a2.CFrame * angles(0, Rad(90), 0)
			msh.Scale = msh.Scale - Vector3.new(0, 0.25, 0.25)
			msh2.Scale = msh2.Scale - Vector3.new(0, 0.3, 0.3)
			SphereAura(5, 0.15, "Add", ba.CFrame * angles(Rad(Mrandom(-360, 360)), Rad(Mrandom(-360, 360)), Rad(Mrandom(-360, 360))), 15, 15, 25, -0.15, maincolor, 0)
			SphereAura(5, 0.15, "Add", ba.CFrame * angles(Rad(Mrandom(-360, 360)), Rad(Mrandom(-360, 360)), Rad(Mrandom(-360, 360))), 15, 15, 25, -0.15, maincolor, 0)
			for i, v in pairs(FindNearestHead(ba.CFrame.p, 14.5)) do
				if v:FindFirstChild("Head") then
					Eviscerate(v)
					SoulSteal(v)
				end
			end
		end
		a:Destroy()
		a2:Destroy()
		ba:Destroy()
		InnerRing1:Destroy()
		attack = false
		hum.CameraOffset = Vector3.new(0,0,0)
	end
	function BURN_IN_HELL()
		attack = true
		chatfunc("BURN....", BrickColor.random().Color)
		for i = 0,5.2,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1 * Cos(sine / 20)) * angles(Rad(-20), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(-20 - 2.5 * Sin(sine / 20)), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-4.5), Rad(0), Rad(-20)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.3 - 0.1 * Cos(sine / 20), -.4 + 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-6.5), Rad(5 * Cos(sine / 20)), Rad(25)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 20), 0.025 * Cos(sine / 20)) * angles(Rad(135), Rad(0), Rad(-45 - 2.5 * Sin(sine / 20))), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 20), 0.025 * Cos(sine / 20)) * angles(Rad(135), Rad(0), Rad(45 + 2.5 * Sin(sine / 20))), 0.1)
		end 
		chatfunc("IN....", BrickColor.random().Color)
		wait(2)
		CreateSound("331666100", char, 10, 1)
		Effects.Sphere.Create(BrickColor.Random(), root.CFrame * CF(0, -1, 0), 2, 2, 2, 10.6, 10.6, 10.6, 0.05)
		Effects.Sphere.Create(BrickColor.Random(), root.CFrame * CF(0, -1, 0), 2, 2, 2, 10.6, 10.6, 10.6, 0.05)
		Effects.Sphere.Create(BrickColor.Random(), root.CFrame * CF(0, -1, 0), 2, 2, 2, 10.6, 10.6, 10.6, 0.05)
		Effects.Sphere.Create(BrickColor.Random(), root.CFrame * CF(0, -1, 0), 2, 2, 2, 10.6, 10.6, 10.6, 0.05)
		Effects.Sphere.Create(BrickColor.Random(), root.CFrame * CF(0, -1, 0), 2, 2, 2, 10.6, 35.6, 10.6, 0.05)
		Effects.Sphere.Create(BrickColor.Random(), root.CFrame * CF(0, -3, 0), 2, 2, 2, 150.6, .4, 150.6, 0.05)
		chatfunc("HELL!!!!!", BrickColor.random().Color)
		for i, v in pairs(FindNearestHead(tors.CFrame.p, 52.5)) do
			if v:FindFirstChild("Head") then
				Eviscerate(v)
				SoulSteal(v)
			end
		end
		coroutine.resume(coroutine.create(function() 
			for i = 0,2.8,0.1 do
				swait()
				hum.CameraOffset = Vector3.new(Mrandom(-3,3),Mrandom(-3,3),Mrandom(-3,3))
			end
			for i = 0,1.8,0.1 do
				swait()
				hum.CameraOffset = Vector3.new(0,0,0)
			end
		end))
		for i = 0,3.7,0.1 do
			SphereAura(2.5, 0.75, "Add", root.CFrame * CFrame.new(math.random(-52.5, 52.5), -5, math.random(-52.5, 52.5)) * CFrame.Angles(math.rad(90 + math.rad(math.random(-45, 45))), math.rad(math.random(-45, 45)), math.rad(math.random(-45, 45))), 2.5, 2.5, 25, -0.025, BrickColor.random(), 0)
			SphereAura(2.5, 0.75, "Add", root.CFrame * CFrame.new(math.random(-52.5, 52.5), -5, math.random(-52.5, 52.5)) * CFrame.Angles(math.rad(90 + math.rad(math.random(-45, 45))), math.rad(math.random(-45, 45)), math.rad(math.random(-45, 45))), 2.5, 2.5, 25, -0.025, BrickColor.random(), 0)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1 * Cos(sine / 20)) * angles(Rad(20), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(20 - 2.5 * Sin(sine / 20)), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-4.5), Rad(0), Rad(20)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 * Cos(sine / 20), -.4 + 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-6.5), Rad(5 * Cos(sine / 20)), Rad(-25)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 20), 0.025 * Cos(sine / 20)) * angles(Rad(-40), Rad(0), Rad(25 - 2.5 * Sin(sine / 20))), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 20), 0.025 * Cos(sine / 20)) * angles(Rad(-40), Rad(0), Rad(-25 + 2.5 * Sin(sine / 20))), 0.1)
		end
		wait(.6)
		CreateSound("907332997", hed, 10, 1)
		attack = false
	end
	-------------------------------------------------------
	--End Attacks N Stuff--
	-------------------------------------------------------
	mouse.KeyDown:connect(function(key)
		if attack == false then
			if key == 'f' then
				Destruction()
			elseif key == 'r' then
				BURN_IN_HELL()
			elseif key == 't' then
				chatfunc("HM, HM, HAHAHAHAHAHA", BrickColor.random().Color)
				CreateSound("300208779", hed, 10, 1)
			end
		end
	end)






	-------------------------------------------------------
	--Start Animations--
	-------------------------------------------------------
	local equipped = false
	local idle = 0
	local change = 1
	local val = 0
	local toim = 0
	local idleanim = 0.4
	hum.Animator.Parent = nil
	while true do
		swait()
		for i, v in pairs(NeonParts) do
			v.BrickColor = BrickColor.Random()
		end
		for i, v in pairs(NeonParts2) do
			v.BrickColor = BrickColor.Random()
		end
		maincolor = BrickColor.Random()
		Music.Parent = char
		tecks2.TextStrokeColor3 = maincolor.Color
		sine = sine + change
		local torvel = (root.Velocity * Vector3.new(1, 0, 1)).magnitude
		local velderp = root.Velocity.y
		hitfloor, posfloor = rayCast(root.Position, CFrame.new(root.Position, root.Position - Vector3.new(0, 1, 0)).lookVector, 4, char)
		if equipped == true or equipped == false then
			if attack == false then
				idle = idle + 1
			else
				idle = 0
			end
			if 1 < root.Velocity.y and hitfloor == nil then
				Anim = "Jump"
				if attack == false then
					rootj.C0 = clerp(rootj.C0, RootCF * angles(math.min(math.max(root.Velocity.Y/100,-Rad(65)),Rad(65)),0,0),0.3)
					tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(-10), Rad(0), Rad(0)), 0.3)
					RW.C0 = clerp(RW.C0, CF(1.5, 0.5, 0) * angles(math.min(math.max(root.Velocity.Y/100,-Rad(65)),Rad(65)),0,Rad(15)),0.3)
					LW.C0 = clerp(LW.C0, CF(-1.5, 0.5, 0) * angles(math.min(math.max(root.Velocity.Y/100,-Rad(65)),Rad(65)),0,Rad(-15)),0.3)
					LH.C0=clerp(LH.C0, CF(-1,-.4-0.1 * Cos(sine / 20), -.6) * LHCF * angles(Rad(-5), Rad(-0), Rad(20)), 0.15)
					RH.C0=clerp(RH.C0, CF(1,-1-0.1 * Cos(sine / 20), -.3) * angles(Rad(0), Rad(90), Rad(0)), .3)
				end
			elseif -1 > root.Velocity.y and hitfloor == nil then
				Anim = "Fall"
				if attack == false then
					rootj.C0 = clerp(rootj.C0, RootCF * angles(math.min(math.max(root.Velocity.Y/100,-Rad(65)),Rad(65)),0,0),0.3)
					tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(10), Rad(0), Rad(0)), 0.3)
					RW.C0 = clerp(RW.C0, CF(1.5, 0.5, 0) * angles(math.min(math.max(root.Velocity.Y/100,-Rad(65)),Rad(65)),0,Rad(30)),0.3)
					LW.C0 = clerp(LW.C0, CF(-1.5, 0.5, 0) * angles(math.min(math.max(root.Velocity.Y/100,-Rad(65)),Rad(65)),0,Rad(-30)),0.3)
					LH.C0 = clerp(LH.C0, CF(-1,-.4-0.1 * Cos(sine / 20), -.6) * LHCF * angles(Rad(-5), Rad(-0), Rad(20)), 0.15)
					RH.C0 = clerp(RH.C0, CF(1,-1-0.1 * Cos(sine / 20), -.3) * angles(Rad(0), Rad(90), Rad(0)), .3)
				end
			elseif torvel < 1 and hitfloor ~= nil then
				Anim = "Idle"
				change = 1.9
				if attack == false then
					rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1 * Cos(sine / 20)) * angles(Rad(30), Rad(0), Rad(0)), 0.15)
					tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(35 - 2.5 * Sin(sine / 20)), Rad(-5 * Cos(sine / 0.465)), Rad(-5 * Cos(sine / 0.465))), 0.3)
					RH.C0 = clerp(RH.C0, CF(1, -1 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-7.5), Rad(0), Rad(30)), 0.15)
					LH.C0 = clerp(LH.C0, CF(-1, -1 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-7.5), Rad(0), Rad(-30)), 0.15)
					RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 20), 0.025 * Cos(sine / 20)) * angles(Rad(35 - 5 * Cos(sine / 0.465)), Rad(-5 * Cos(sine / 0.465)), Rad(15 + 7 * Sin(sine / 25))), 0.1)
					LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 20), 0.025 * Cos(sine / 20)) * angles(Rad(35 - 5 * Cos(sine / 0.465)), Rad(-5 * Cos(sine / 0.465)), Rad(-15 - 7 * Sin(sine / 25))), 0.1)
				end
			elseif tors.Velocity.magnitude < 50 and hitfloor ~= nil then
				Anim = "Walk"
				change = 1
				if attack == false then
					rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.175 + 0.025 * Cos(sine / 3.5) + -Sin(sine / 3.5) / 7) * angles(Rad(15 - 2.5 * Cos(sine / 3.5)), Rad(0) - root.RotVelocity.Y / 75, Rad(4 * Cos(sine / 7))), 0.15)
					tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(13 - 2.5 * Sin(sine / 7)), Rad(-5 * Cos(sine / 0.465)), Rad(-5 * Cos(sine / 0.465))), 0.3)
					RH.C0 = clerp(RH.C0, CF(1, -0.925 - 0.5 * Cos(sine / 7) / 2, 0.5 * Cos(sine / 7) / 2) * angles(Rad(-15 - 5 * Cos(sine / 7)) - rl.RotVelocity.Y / 75 + -Sin(sine / 7) / 2.5, Rad(90 - 0.1 * Cos(sine / 7)), Rad(0)) * angles(Rad(0 + 0.1 * Cos(sine / 7)), Rad(0), Rad(15)), 0.3)
					LH.C0 = clerp(LH.C0, CF(-1, -0.925 + 0.5 * Cos(sine / 7) / 2, -0.5 * Cos(sine / 7) / 2) * angles(Rad(-15 + 5 * Cos(sine / 7)) + ll.RotVelocity.Y / 75 + Sin(sine / 7) / 2.5, Rad(-90 - 0.1 * Cos(sine / 7)), Rad(0)) * angles(Rad(0 - 0.1 * Cos(sine / 7)), Rad(0), Rad(-15)), 0.3)
					RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 7), 0.025 * Cos(sine / 7)) * angles(Rad(65)  * Cos(sine / 7) , Rad(0), Rad(10 + 7 * Sin(sine / 7)) - ra.RotVelocity.Y / 75), 0.1)
					LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 7), 0.025 * Cos(sine / 7)) * angles(Rad(-65)  * Cos(sine / 7) , Rad(0), Rad(-10 - 7 * Sin(sine / 7)) + la.RotVelocity.Y / 75), 0.1)
				end
			end
		end
		if 0 < #Effects then
			for e = 1, #Effects do
				if Effects[e] ~= nil then
					local Thing = Effects[e]
					if Thing ~= nil then
						local Part = Thing[1]
						local Mode = Thing[2]
						local Delay = Thing[3]
						local IncX = Thing[4]
						local IncY = Thing[5]
						local IncZ = Thing[6]
						if 1 >= Thing[1].Transparency then
							if Thing[2] == "Block1" then
								Thing[1].CFrame = Thing[1].CFrame * CFrame.fromEulerAnglesXYZ(math.random(-50, 50), math.random(-50, 50), math.random(-50, 50))
								local Mesh = Thing[1].Mesh
								Mesh.Scale = Mesh.Scale + Vector3.new(Thing[4], Thing[5], Thing[6])
								Thing[1].Transparency = Thing[1].Transparency + Thing[3]
							elseif Thing[2] == "Block2" then
								Thing[1].CFrame = Thing[1].CFrame + Vector3.new(0, 0, 0)
								local Mesh = Thing[7]
								Mesh.Scale = Mesh.Scale + Vector3.new(Thing[4], Thing[5], Thing[6])
								Thing[1].Transparency = Thing[1].Transparency + Thing[3]
							elseif Thing[2] == "Block3" then
								Thing[1].CFrame = Thing[1].CFrame * CFrame.fromEulerAnglesXYZ(math.random(-50, 50), math.random(-50, 50), math.random(-50, 50)) + Vector3.new(0, 0.15, 0)
								local Mesh = Thing[7]
								Mesh.Scale = Mesh.Scale + Vector3.new(Thing[4], Thing[5], Thing[6])
								Thing[1].Transparency = Thing[1].Transparency + Thing[3]
							elseif Thing[2] == "Cylinder" then
								local Mesh = Thing[1].Mesh
								Mesh.Scale = Mesh.Scale + Vector3.new(Thing[4], Thing[5], Thing[6])
								Thing[1].Transparency = Thing[1].Transparency + Thing[3]
							elseif Thing[2] == "Blood" then
								local Mesh = Thing[7]
								Thing[1].CFrame = Thing[1].CFrame * Vector3.new(0, 0.5, 0)
								Mesh.Scale = Mesh.Scale + Vector3.new(Thing[4], Thing[5], Thing[6])
								Thing[1].Transparency = Thing[1].Transparency + Thing[3]
							elseif Thing[2] == "Elec" then
								local Mesh = Thing[1].Mesh
								Mesh.Scale = Mesh.Scale + Vector3.new(Thing[7], Thing[8], Thing[9])
								Thing[1].Transparency = Thing[1].Transparency + Thing[3]
							elseif Thing[2] == "Disappear" then
								Thing[1].Transparency = Thing[1].Transparency + Thing[3]
							elseif Thing[2] == "Shatter" then
								Thing[1].Transparency = Thing[1].Transparency + Thing[3]
								Thing[4] = Thing[4] * CFrame.new(0, Thing[7], 0)
								Thing[1].CFrame = Thing[4] * CFrame.fromEulerAnglesXYZ(Thing[6], 0, 0)
								Thing[6] = Thing[6] + Thing[5]
							end
						else
							Part.Parent = nil
							table.remove(Effects, e)
						end
					end
				end
			end
		end
	end
	-------------------------------------------------------
	--End Animations And Script--
	-------------------------------------------------------
end)

sonic.Name = "sonic"
sonic.Parent = main
sonic.BackgroundColor3 = Color3.fromRGB(85, 85, 85)
sonic.Position = UDim2.new(0.125, 0, 0.127485171, 0)
sonic.Size = UDim2.new(0, 134, 0, 32)
sonic.Font = Enum.Font.SciFi
sonic.Text = "Sonic"
sonic.TextColor3 = Color3.fromRGB(0, 0, 0)
sonic.TextSize = 35.000
sonic.MouseButton1Down:connect(function()
	--[[KillerDarkness0105's/Codex's Sonic script]]--
	Bypass = "death"
	FELOADLIBRARY = {}
	loadstring(game:GetObjects("rbxassetid://5209815302")[1].Source)()
	loadstring(game:GetObjects("rbxassetid://5325226148")[1].Source)()

	print("Move list")
	print("---------")
	print("Shift = Boost")
	print("Ctrl = Mach Speed Boost")
	print("Q = Left QuickStep, E  = Right QuickStep")
	print("C = Slide, in air to stomp")
	print("Jump Then Hold B near a wall to wallrun")
	print("M to change music, if you're standing still you'll do a special animation!")
	print("Space near a wall to walljump, away from a wall homing attack")

	wait(0.07)
	Player=game:GetService("Players").LocalPlayer
	Character=workspace.non
	PlayerGui=Player.PlayerGui
	Backpack=Player.Backpack
	Torso=Character.Torso
	Head=Character.Head
	Humanoid=Character.Humanoid
	LeftArm=Character["Left Arm"]
	LeftLeg=Character["Left Leg"]
	RightArm=Character["Right Arm"]
	RightLeg=Character["Right Leg"]
	LS=Torso["Left Shoulder"]
	LH=Torso["Left Hip"]
	RS=Torso["Right Shoulder"]
	RH=Torso["Right Hip"]
	Face = Head.face
	Neck=Torso.Neck
	it=Instance.new
	attacktype=1
	attacktype2=1
	vt=Vector3.new
	cf=CFrame.new
	cn=CFrame.new
	euler=CFrame.fromEulerAnglesXYZ
	angles=CFrame.Angles
	combo = 0
	necko=cf(0, 1, 0, -1, -0, -0, 0, 0, 1, 0, 1, 0)
	necko2=cf(0, -0.5, 0, -1, -0, -0, 0, 0, 1, 0, 1, 0)
	LHC0=cf(-1,-1,0,-0,-0,-1,0,1,0,1,0,0)
	LHC1=cf(-0.5,1,0,-0,-0,-1,0,1,0,1,0,0)
	RHC0=cf(1,-1,0,0,0,1,0,1,0,-1,-0,-0)
	RHC1=cf(0.5,1,0,0,0,1,0,1,0,-1,-0,-0)
	RootPart=Character.HumanoidRootPart
	RootJoint=RootPart.RootJoint
	RootCF=euler(-1.57,0,3.14)
	attack = false
	attackdebounce = false
	trispeed=.2
	attackmode='none'
	local idle=0
	local Anim="Idle"
	stance = false
	local ff = 2
	noleg = false
	evadecooldown = false
	Humanoid.Animator.Parent = nil
	equip = false
	local Effects = {}
	attackspeed = 0.14 
	df = false
	Swing = 1
	local sine = 0
	local change = 1
	local val = 0
	local speed = 0
	local rs = game:GetService("RunService").RenderStepped
	cam = workspace.CurrentCamera
	local Create = FELOADLIBRARY.Create
	deb = game:GetService("Debris")
	Face.Transparency = 0
	--Face.Texture = "rbxassetid://176217905" --176217905
	Humanoid.WalkSpeed = 64
	local freefall = 0
	local headsunsound = RootPart:FindFirstChild("Running") or Instance.new("Sound",RootPart)
	headsunsound.SoundId = "rbxassetid://758199523"
	headsunsound.Volume = 2
	local boost = false
	Humanoid.JumpPower = 88
	local musicnum = 1

	local spd = Vector3.new(RootPart.Velocity.x,0,RootPart.Velocity.z).magnitude + 10
	local dir = Vector3.new(RootPart.Velocity.x,0,RootPart.Velocity.z).unit
	local GravPoint = RootPart.Velocity.y
	local NV = Vector3.new(0,0,0)

	music = Instance.new("Sound",RootPart)
	music.Volume = 1
	music.TimePosition = 0
	music.Pitch = 1
	music.SoundId = "rbxassetid://1251555494"
	music.Looped = true
	music:Play()


	boostsound = Instance.new("Sound",RootPart)
	boostsound.Volume = .6
	boostsound.TimePosition = 0
	boostsound.Pitch = 1
	boostsound.SoundId = "rbxassetid://924922553"
	boostsound.Looped = false



	stompsound = Instance.new("Sound",RootPart)
	stompsound.Volume = 2
	stompsound.TimePosition = 0
	stompsound.Pitch = 1
	stompsound.SoundId = "rbxassetid://1295424184"
	stompsound.Looped = false



	so = function(id,par,vol,pit)
		coroutine.resume(coroutine.create(function()
			local sou = Instance.new("Sound",par or workspace)
			sou.Volume=vol
			sou.Pitch=pit or 1
			sou.SoundId=id
			sou:play()
			game:GetService("Debris"):AddItem(sou,8)
		end))
	end

	--save shoulders
	RSH, LSH=nil, nil
	--welds
	RW, LW=Instance.new("Weld"), Instance.new("Weld")
	RW.Name="Right Shoulder" LW.Name="Left Shoulder"
	LH=Torso["Left Hip"]
	RH=Torso["Right Hip"]
	TorsoColor=Torso.BrickColor
	function NoOutline(Part)
		Part.TopSurface,Part.BottomSurface,Part.LeftSurface,Part.RightSurface,Part.FrontSurface,Part.BackSurface = 10,10,10,10,10,10
	end
	player=Player
	ch=Character
	RSH=ch.Torso["Right Shoulder"]
	LSH=ch.Torso["Left Shoulder"]
	--
	RSH.Parent=nil
	LSH.Parent=nil
	--
	RW.Name="Right Shoulder"
	RW.Part0=ch.Torso
	RW.C0=cf(1.5, 0.5, 0) --* CFrame.fromEulerAnglesXYZ(1.3, 0, -0.5)
	RW.C1=cf(0, 0.5, 0)
	RW.Part1=ch["Right Arm"]
	RW.Parent=ch.Torso
	--
	LW.Name="Left Shoulder"
	LW.Part0=ch.Torso
	LW.C0=cf(-1.5, 0.5, 0) --* CFrame.fromEulerAnglesXYZ(1.7, 0, 0.8)
	LW.C1=cf(0, 0.5, 0)
	LW.Part1=ch["Left Arm"]
	LW.Parent=ch.Torso


	newWeld = function(wp0, wp1, wc0x, wc0y, wc0z)
		local wld = Instance.new("Weld", wp1)
		wld.Part0 = wp0
		wld.Part1 = wp1
		wld.C0 = CFrame.new(wc0x, wc0y, wc0z)
	end
	local rs = game:GetService("RunService").RenderStepped

	newWeld(RootPart, Torso, 0, -1, 0)
	Torso.Weld.C1 = CFrame.new(0, -1, 0)
	newWeld(Torso, LeftLeg, -0.5, -1, 0)
	LeftLeg.Weld.C1 = CFrame.new(0, 1, 0)
	newWeld(Torso, RightLeg, 0.5, -1, 0)
	RightLeg.Weld.C1 = CFrame.new(0, 1, 0)

	Player=game:GetService('Players').LocalPlayer
	Character=Player.Character
	mouse=Player:GetMouse()
	m=Instance.new('Model',Character)


	local function weldBetween(a, b)
		local weldd = Instance.new("ManualWeld")
		weldd.Part0 = a
		weldd.Part1 = b
		weldd.C0 = CFrame.new()
		weldd.C1 = b.CFrame:inverse() * a.CFrame
		weldd.Parent = a
		return weldd
	end

	ArtificialHB = Instance.new("BindableEvent", script)
	ArtificialHB.Name = "Heartbeat"

	script:WaitForChild("Heartbeat")

	frame = 1 / 80
	tf = 0
	allowframeloss = false
	tossremainder = false
	lastframe = tick()
	script.Heartbeat:Fire()
	game:GetService("RunService").Heartbeat:connect(function(s, p)
		tf = tf + s
		if tf >= frame then
			if allowframeloss then
				script.Heartbeat:Fire()
				lastframe = tick()
			else
				for i = 1, math.floor(tf / frame) do
					script.Heartbeat:Fire()
				end
				lastframe = tick()
			end
			if tossremainder then
				tf = 0
			else
				tf = tf - frame * math.floor(tf / frame)
			end
		end
	end)

--[[]
		function swait(num)
		    if num == 0 or num == nil then
		        ArtificialHB.Event:wait()
		    else
		        for i = 0, num do
		            ArtificialHB.Event:wait()
		        end
		    end
	end

	]]




	function swait(num)
		if num == 0 or num == nil then
			game:service("RunService").Stepped:wait()
		else
			for i = 0, num do
				game:service("RunService").Stepped:wait()
			end
		end
	end

	function RemoveOutlines(part)
		part.TopSurface, part.BottomSurface, part.LeftSurface, part.RightSurface, part.FrontSurface, part.BackSurface = 10, 10, 10, 10, 10, 10
	end


	part = function(formfactor, parent, reflectance, transparency, brickcolor, name, size)
		local fp = it("Part")
		fp.formFactor = formfactor
		fp.Parent = parent
		fp.Reflectance = reflectance
		fp.Transparency = transparency
		fp.CanCollide = false
		fp.Locked = true
		fp.BrickColor = brickcolor
		fp.Name = name
		fp.Size = size
		fp.Position = Torso.Position
		NoOutline(fp)
		if fp.BrickColor == BrickColor.new("Dark indigo") then
			fp.Material = "Neon"
		else
			if fp.BrickColor == BrickColor.new("Really black") then
				fp.BrickColor = BrickColor.new("Really black")
				fp.Material = "Metal"
			else
				fp.Material = "Neon"
			end
		end
		fp:BreakJoints()
		return fp
	end

	mesh = function(Mesh, part, meshtype, meshid, offset, scale)
		local mesh = it(Mesh)
		mesh.Parent = part
		if Mesh == "SpecialMesh" then
			mesh.MeshType = meshtype
			mesh.MeshId = meshid
		end
		mesh.Offset = offset
		mesh.Scale = scale
		return mesh
	end

	weld = function(parent, part0, part1, c0)
		local weld = it("Weld")
		weld.Parent = parent
		weld.Part0 = part0
		weld.Part1 = part1
		weld.C0 = c0
		return weld
	end

	F1 = Instance.new("Folder", Character)
	F1.Name = "Effects Folder"
	F2 = Instance.new("Folder", F1)
	F2.Name = "Effects"
	Triangle = function(a, b, c)
	end

	MagicBlock = function(brickcolor, cframe, x1, y1, z1, x3, y3, z3, delay)
		local prt = part(3, F2, 0, 0, brickcolor, "Effect", vt())
		prt.Anchored = true
		prt.CanCollide = false
		prt.CFrame = cframe
		prt.Name = "prt"
		msh = mesh("BlockMesh", prt, "", "", vt(0, 0, 0), vt(x1, y1, z1))
		game:GetService("Debris"):AddItem(prt, 5)
		table.insert(Effects, {prt, "Block1", delay, x3, y3, z3})
	end



	MagicCircle = function(brickcolor, cframe, x1, y1, z1, x3, y3, z3, delay)
		local prt = part(3, F2, 0, 0, brickcolor, "Effect", vt())
		prt.Anchored = true
		prt.CanCollide = false
		prt.CFrame = cframe
		prt.Name = "prt"
		local msh = mesh("SpecialMesh", prt, "Sphere", "", vt(0, 0, 0), vt(x1, y1, z1))
		game:GetService("Debris"):AddItem(prt, 5)
		table.insert(Effects, {prt, "Cylinder", delay, x3, y3, z3})
	end

	MagicWave = function(brickcolor, cframe, x1, y1, z1, x3, y3, z3, delay)
		local prt = part(3, F2, 0, 0, brickcolor, "Effect", vt())
		prt.Anchored = true
		prt.CFrame = cframe
		local msh = mesh("SpecialMesh", prt, "FileMesh", "http://www.roblox.com/asset/?id=20329976", vt(0, 0, 0), vt(x1, y1, z1))
		game:GetService("Debris"):AddItem(prt, 5)
		table.insert(Effects, {prt, "Cylinder", delay, x3, y3, z3})
	end

	MagicCylinder = function(brickcolor, cframe, x1, y1, z1, x3, y3, z3, delay)
		local prt = part(3, F2, 0, 0, brickcolor, "Effect", vt(0.2, 0.2, 0.2))
		prt.Anchored = true
		prt.CFrame = cframe
		msh = mesh("SpecialMesh", prt, "Head", "", vt(0, 0, 0), vt(x1, y1, z1))
		game:GetService("Debris"):AddItem(prt, 5)
		Effects[#Effects + 1] = {prt, "Cylinder", delay, x3, y3, z3}
	end

	MagicCylinder2 = function(brickcolor, cframe, x1, y1, z1, x3, y3, z3, delay)
		local prt = part(3, F2, 0, 0, brickcolor, "Effect", vt(0.2, 0.2, 0.2))
		prt.Anchored = true
		prt.CFrame = cframe
		msh = mesh("CylinderMesh", prt, "", "", vt(0, 0, 0), vt(x1, y1, z1))
		game:GetService("Debris"):AddItem(prt, 5)
		Effects[#Effects + 1] = {prt, "Cylinder", delay, x3, y3, z3}
	end

	MagicBlood = function(brickcolor, cframe, x1, y1, z1, x3, y3, z3, delay)
		local prt = part(3, F2, 0, 0, brickcolor, "Effect", vt())
		prt.Anchored = true
		prt.CFrame = cframe
		local msh = mesh("SpecialMesh", prt, "Sphere", "", vt(0, 0, 0), vt(x1, y1, z1))
		game:GetService("Debris"):AddItem(prt, 5)
		table.insert(Effects, {prt, "Blood", delay, x3, y3, z3})
	end

	ElecEffect = function(cff, x, y, z)
		local prt = part(3, F2, 0, 0, BrickColor.new("Dark indigo"), "Part", vt(1, 1, 1))
		prt.Anchored = true
		prt.CFrame = cff * cf(math.random(-x, x), math.random(-y, y), math.random(-z, z))
		prt.CFrame = cf(prt.Position)
		game:GetService("Debris"):AddItem(prt, 2)
		xval = math.random() / 2
		yval = math.random() / 2
		zval = math.random() / 2
		msh = mesh("BlockMesh", prt, "", "", vt(0, 0, 0), vt(xval, yval, zval))
		Effects[#Effects + 1] = {prt, "Elec", 0.1, x, y, z, xval, yval, zval}
	end

	function FindNearestTorso(Position, Distance, SinglePlayer)
		if SinglePlayer then
			return (SinglePlayer.Torso.CFrame.p - Position).magnitude < Distance
		end
		local List = {}
		for i, v in pairs(workspace:GetChildren()) do
			if v:IsA("Model") then
				if v:findFirstChild("Torso") then
					if v ~= Character then
						if (v.Torso.Position - Position).magnitude <= Distance then
							table.insert(List, v)
						end 
					end 
				end 
			end 
		end
		return List
	end


	function CreatePart(Parent, Material, Reflectance, Transparency, BColor, Name, Size)
		local Part = Create("Part"){
			Parent = Parent,
			Reflectance = Reflectance,
			Transparency = Transparency,
			CanCollide = false,
			Locked = true,
			BrickColor = BrickColor.new(tostring(BColor)),
			Name = Name,
			Size = Size,
			Material = Material,
		}
		RemoveOutlines(Part)
		return Part
	end

	function CreateMesh(Mesh, Part, MeshType, MeshId, OffSet, Scale)
		local Msh = Create(Mesh){
			Parent = Part,
			Offset = OffSet,
			Scale = Scale,
		}
		if Mesh == "SpecialMesh" then
			Msh.MeshType = MeshType
			Msh.MeshId = MeshId
		end
		return Msh
	end



	function BlockEffect(brickcolor, cframe, x1, y1, z1, x3, y3, z3, delay, Type)
		local prt = CreatePart(workspace, "Neon", 0, 0, brickcolor, "Effect", Vector3.new())
		prt.Anchored = true
		prt.CFrame = cframe
		local msh = CreateMesh("BlockMesh", prt, "", "", Vector3.new(0, 0, 0), Vector3.new(x1, y1, z1))
		game:GetService("Debris"):AddItem(prt, 10)
		if Type == 1 or Type == nil then
			table.insert(Effects, {
				prt,
				"Block1",
				delay,
				x3,
				y3,
				z3,
				msh
			})
		elseif Type == 2 then
			table.insert(Effects, {
				prt,
				"Block2",
				delay,
				x3,
				y3,
				z3,
				msh
			})
		end
	end

	function SphereEffect(brickcolor, cframe, x1, y1, z1, x3, y3, z3, delay)
		local prt = CreatePart(workspace, "Neon", 0, 0, brickcolor, "Effect", Vector3.new())
		prt.Anchored = true
		prt.CFrame = cframe
		local msh = CreateMesh("SpecialMesh", prt, "Sphere", "", Vector3.new(0, 0, 0), Vector3.new(x1, y1, z1))
		game:GetService("Debris"):AddItem(prt, 10)
		table.insert(Effects, {
			prt,
			"Cylinder",
			delay,
			x3,
			y3,
			z3,
			msh
		})
	end

	function RingEffect(brickcolor, cframe, x1, y1, z1, x3, y3, z3, delay,material)
		local prt=CreatePart(workspace,material,0,0,brickcolor,"Effect",vt(.5,.5,.5))--part(3,workspace,"SmoothPlastic",0,0,brickcolor,"Effect",vt(0.5,0.5,0.5))
		prt.Anchored=true
		prt.CFrame=cframe
		msh=CreateMesh("SpecialMesh",prt,"FileMesh","http://www.roblox.com/asset/?id=3270017",vt(0,0,0),vt(x1,y1,z1))
		game:GetService("Debris"):AddItem(prt,2)
		coroutine.resume(coroutine.create(function(Part,Mesh,num) 
			for i=0,1,delay do
				swait()
				Part.Transparency=i
				Mesh.Scale=Mesh.Scale+vt(x3,y3,z3)
			end
			Part.Parent=nil
		end),prt,msh,(math.random(0,1)+math.random())/5)
	end

	function CylinderEffect(brickcolor, cframe, x1, y1, z1, x3, y3, z3, delay)
		local prt = CreatePart(workspace, "SmoothPlastic", 0, 0, brickcolor, "Effect", Vector3.new())
		prt.Anchored = true
		prt.CFrame = cframe
		local msh = CreateMesh("CylinderMesh", prt, "", "", Vector3.new(0, 0, 0), Vector3.new(x1, y1, z1))
		game:GetService("Debris"):AddItem(prt, 10)
		table.insert(Effects, {
			prt,
			"Cylinder",
			delay,
			x3,
			y3,
			z3,
			msh
		})
	end

	function WaveEffect(brickcolor, cframe, x1, y1, z1, x3, y3, z3, delay)
		local prt = CreatePart(workspace, "Neon", 0, 0, brickcolor, "Effect", Vector3.new())
		prt.Anchored = true
		prt.CFrame = cframe
		local msh = CreateMesh("SpecialMesh", prt, "FileMesh", "rbxassetid://20329976", Vector3.new(0, 0, 0), Vector3.new(x1, y1, z1))
		game:GetService("Debris"):AddItem(prt, 10)
		table.insert(Effects, {
			prt,
			"Cylinder",
			delay,
			x3,
			y3,
			z3,
			msh
		})
	end

	function SpecialEffect(brickcolor, cframe, x1, y1, z1, x3, y3, z3, delay)
		local prt = CreatePart(workspace, "Neon", 0, 0, brickcolor, "Effect", Vector3.new())
		prt.Anchored = true
		prt.CFrame = cframe
		local msh = CreateMesh("SpecialMesh", prt, "FileMesh", "rbxassetid://24388358", Vector3.new(0, 0, 0), Vector3.new(x1, y1, z1))
		game:GetService("Debris"):AddItem(prt, 10)
		table.insert(Effects, {
			prt,
			"Cylinder",
			delay,
			x3,
			y3,
			z3,
			msh
		})
	end


	function MoonEffect(brickcolor, cframe, x1, y1, z1, x3, y3, z3, delay)
		local prt = CreatePart(workspace, "Neon", 0, 0, brickcolor, "Effect", Vector3.new())
		prt.Anchored = true
		prt.CFrame = cframe
		local msh = CreateMesh("SpecialMesh", prt, "FileMesh", "rbxassetid://259403370", Vector3.new(0, 0, 0), Vector3.new(x1, y1, z1))
		game:GetService("Debris"):AddItem(prt, 10)
		table.insert(Effects, {
			prt,
			"Cylinder",
			delay,
			x3,
			y3,
			z3,
			msh
		})
	end

	function HeadEffect(brickcolor, cframe, x1, y1, z1, x3, y3, z3, delay)
		local prt = CreatePart(workspace, "Neon", 0, 0, brickcolor, "Effect", Vector3.new())
		prt.Anchored = true
		prt.CFrame = cframe
		local msh = CreateMesh("SpecialMesh", prt, "Head", "", Vector3.new(0, 0, 0), Vector3.new(x1, y1, z1))
		game:GetService("Debris"):AddItem(prt, 10)
		table.insert(Effects, {
			prt,
			"Cylinder",
			delay,
			x3,
			y3,
			z3,
			msh
		})
	end

	function BreakEffect(brickcolor, cframe, x1, y1, z1)
		local prt = CreatePart(workspace, "Neon", 0, 0, brickcolor, "Effect", Vector3.new(0.5, 0.5, 0.5))
		prt.Anchored = true
		prt.CFrame = cframe * CFrame.fromEulerAnglesXYZ(math.random(-50, 50), math.random(-50, 50), math.random(-50, 50))
		local msh = CreateMesh("SpecialMesh", prt, "Sphere", "", Vector3.new(0, 0, 0), Vector3.new(x1, y1, z1))
		local num = math.random(10, 50) / 1000
		game:GetService("Debris"):AddItem(prt, 10)
		table.insert(Effects, {
			prt,
			"Shatter",
			num,
			prt.CFrame,
			math.random() - math.random(),
			0,
			math.random(50, 100) / 100
		})
	end

	local lerp = function(a, b, t)
		return a * (1 - t) + b * t
	end

	function clerp(a,b,t)
		local qa = {QuaternionFromCFrame(a)}
		local qb = {QuaternionFromCFrame(b)}
		local ax, ay, az = a.x, a.y, a.z
		local bx, by, bz = b.x, b.y, b.z
		local _t = 1-t
		return QuaternionToCFrame(_t*ax + t*bx, _t*ay + t*by, _t*az + t*bz,QuaternionSlerp(qa, qb, t))
	end

	function QuaternionFromCFrame(cf)
		local mx, my, mz, m00, m01, m02, m10, m11, m12, m20, m21, m22 = cf:components()
		local trace = m00 + m11 + m22
		if trace > 0 then
			local s = math.sqrt(1 + trace)
			local recip = 0.5/s
			return (m21-m12)*recip, (m02-m20)*recip, (m10-m01)*recip, s*0.5
		else
			local i = 0
			if m11 > m00 then
				i = 1
			end
			if m22 > (i == 0 and m00 or m11) then
				i = 2
			end
			if i == 0 then
				local s = math.sqrt(m00-m11-m22+1)
				local recip = 0.5/s
				return 0.5*s, (m10+m01)*recip, (m20+m02)*recip, (m21-m12)*recip
			elseif i == 1 then
				local s = math.sqrt(m11-m22-m00+1)
				local recip = 0.5/s
				return (m01+m10)*recip, 0.5*s, (m21+m12)*recip, (m02-m20)*recip
			elseif i == 2 then
				local s = math.sqrt(m22-m00-m11+1)
				local recip = 0.5/s return (m02+m20)*recip, (m12+m21)*recip, 0.5*s, (m10-m01)*recip
			end
		end
	end


	function QuaternionToCFrame(px, py, pz, x, y, z, w)
		local xs, ys, zs = x + x, y + y, z + z
		local wx, wy, wz = w*xs, w*ys, w*zs
		local xx = x*xs
		local xy = x*ys
		local xz = x*zs
		local yy = y*ys
		local yz = y*zs
		local zz = z*zs
		return CFrame.new(px, py, pz,1-(yy+zz), xy - wz, xz + wy,xy + wz, 1-(xx+zz), yz - wx, xz - wy, yz + wx, 1-(xx+yy))
	end
	function QuaternionSlerp(a, b, t)
		local cosTheta = a[1]*b[1] + a[2]*b[2] + a[3]*b[3] + a[4]*b[4]
		local startInterp, finishInterp;
		if cosTheta >= 0.0001 then
			if (1 - cosTheta) > 0.0001 then
				local theta = math.acos(cosTheta)
				local invSinTheta = 1/math.sin(theta)
				startInterp = math.sin((1-t)*theta)*invSinTheta
				finishInterp = math.sin(t*theta)*invSinTheta  
			else
				startInterp = 1-t
				finishInterp = t
			end
		else
			if (1+cosTheta) > 0.0001 then
				local theta = math.acos(-cosTheta)
				local invSinTheta = 1/math.sin(theta)
				startInterp = math.sin((t-1)*theta)*invSinTheta
				finishInterp = math.sin(t*theta)*invSinTheta
			else
				startInterp = t-1
				finishInterp = t
			end
		end
		return a[1]*startInterp + b[1]*finishInterp, a[2]*startInterp + b[2]*finishInterp, a[3]*startInterp + b[3]*finishInterp, a[4]*startInterp + b[4]*finishInterp
	end

	function weld5(part0, part1, c0, c1)
		weeld=Instance.new("Weld", part0)
		weeld.Part0=part0
		weeld.Part1=part1
		weeld.C0=c0
		weeld.C1=c1
		return weeld
	end

	--Example: Torso.Weld.C0 = clerp(Torso.Weld.C0, CFrame.new(0, 0, 0) * CFrame.Angles(math.rad(0), math.rad(0), math.rad(0)), 0.4)

	function rayCast(Pos, Dir, Max, Ignore)  -- Origin Position , Direction, MaxDistance , IgnoreDescendants
		return game:service("Workspace"):FindPartOnRay(Ray.new(Pos, Dir.unit * (Max or 999.999)), Ignore)
	end







	local f = 0
	local b = Instance.new("BlurEffect",cam)
	local    c = Instance.new('PointLight', Torso)
	c.Range = 16
	c.Color = Color3.new(0, 1,1)
	c.Brightness = 1.5
	game:GetService("RunService"):BindToRenderStep("W0tT", 0, function()

		b.Size = b.Size - 4
		if boost == true then
			c.Enabled = true
			cam.FieldOfView = lerp(cam.FieldOfView, 110, 0.5)
			-- cam.FieldOfView = 110
			freefall = 0
			Humanoid.CameraOffset = Humanoid.CameraOffset:lerp(Vector3.new(0,0,3),0.25)
			SphereEffect(BrickColor.new("Cyan"),RightLeg.CFrame*CFrame.new(0,-1,0)*angles(math.random(-180,180),math.random(-180,180),math.random(-180,180)),1.4,12,1.4,2.8,26,2.8,0.07)
			SphereEffect(BrickColor.new("Cyan"),LeftLeg.CFrame*CFrame.new(0,-1,0)*angles(math.random(-180,180),math.random(-180,180),math.random(-180,180)),1.4,12,1.4,2.8,26,2.8,0.07)
			if hitfloor ~= nil and Anim ~= "runIdle" then
				SpecialEffect(BrickColor.new("Cyan"),RootPart.CFrame*CFrame.new(0,-3.4,.78) ,2,2,2, 1.5,1.5,1.5,.09)
			end
		end
		if boost == false then
			cam.FieldOfView = lerp(cam.FieldOfView, 70, 0.076)
			--cam.FieldOfView = 70
			c.Enabled = false
		end
	end)



	mouse.KeyDown:connect(function(key)
		if string.byte(key) == 48 then
			b.Size = 40
			Swing = 2
			freefall = 0

			coroutine.resume(coroutine.create(function()
				for i = 0,1,0.1 do
					swait()
					Humanoid.CameraOffset = Humanoid.CameraOffset:lerp(Vector3.new(math.random(-0.35*1.8,0.35*1.8),math.random(-0.35*1.8,0.35*1.8),math.random(-0.35*1.8,0.35*1.8)),0.24)
				end
			end))
			Humanoid.WalkSpeed = 180
			RootPart.Velocity = RootPart.CFrame.lookVector*150
			RingEffect(BrickColor.new("Cyan"), RootPart.CFrame*CFrame.new(0,0,-9.2) , 1, 1, 1, 8, 8, 8, 0.14,"Neon") 
			boost = true
			boostsound:Play()
		end
	end)

	mouse.KeyUp:connect(function(key)
		if string.byte(key) == 48 then
			Swing = 1
			Humanoid.WalkSpeed = 64
			boost = false
			boostsound:Stop()

		end
	end)




	mouse.KeyDown:connect(function(key)
		if string.byte(key) == 50 then
			b.Size = 40
			freefall = 0
			Swing = 2

			coroutine.resume(coroutine.create(function()
				for i = 0,1,0.1 do
					swait()
					Humanoid.CameraOffset = Humanoid.CameraOffset:lerp(Vector3.new(math.random(-0.35*2.8,0.35*2.8),math.random(-0.35*2.8,0.35*2.8),math.random(-0.35*2.8,0.35*2.8)),0.48)
				end
			end))

			Humanoid.WalkSpeed = 320
			RootPart.Velocity = RootPart.CFrame.lookVector*550
			RingEffect(BrickColor.new("Cyan"), RootPart.CFrame*CFrame.new(0,0,-9.2) , 1, 1, 1, 18, 18, 18, 0.14,"Neon") 
			RingEffect(BrickColor.new("White"), RootPart.CFrame*CFrame.new(0,0,-11.2) , 1, 1, 1, 18, 18, 18, 0.14,"Neon") 
			RingEffect(BrickColor.new("Cyan"), RootPart.CFrame*CFrame.new(0,0,-13.2) , 1, 1, 1, 18, 18, 18, 0.14,"Neon") 
			boost = true
			boostsound:Play()
		end
	end)

	mouse.KeyUp:connect(function(key)
		if string.byte(key) == 50 then
			Swing = 1
			Humanoid.WalkSpeed = 64
			boost = false
			boostsound:Stop()

		end
	end)


	local lastwall = nil
	local jumped = false






	local vwall = false

	mouse.KeyDown:connect(function(key)
		if key == 'b' and hitfloor == nil and attack == false then
			vrun()
		end
	end)


	function vrun()
		local ray = Ray.new(
			RootPart.CFrame.p, RootPart.CFrame.lookVector *2.5
		)
		local hit, position, normal = workspace:FindPartOnRay(ray, character)

		if hit then
			if hit.Parent.Parent ~= Character and hit.Parent ~= Character and hit.Name ~= "prt" and hit.CanCollide == true then
				vwall = true
				local NV = Vector3.new(0,0,0)
				local spd = Vector3.new(RootPart.Velocity.x,0,RootPart.Velocity.z).magnitude + 10
				local dir = Vector3.new(RootPart.Velocity.x,0,RootPart.Velocity.z).unit
				local GravPoint = RootPart.Velocity.y
				local velo = Instance.new("BodyVelocity",Torso)
				velo.MaxForce = Vector3.new(400000,400000,400000)

				attack = true
				while vwall == true and ray and hit do
					swait()
					change = 0.84+ Humanoid.WalkSpeed/132
					if Humanoid.WalkSpeed > 40 and Humanoid.WalkSpeed < 70 then
						velo.Velocity =  Vector3.new(0,40,0)
					end
					if Humanoid.WalkSpeed > 70 and Humanoid.WalkSpeed < 200 then
						velo.Velocity =  Vector3.new(0,80,0)
					end
					if Humanoid.WalkSpeed > 200 then
						velo.Velocity =  Vector3.new(0,130,0)
					end
					ray = Ray.new(
						RootPart.CFrame.p, RootPart.CFrame.lookVector *2.5
					)
					hit, position, normal = workspace:FindPartOnRay(ray, character)
					Torso.Weld.C0 = clerp(Torso.Weld.C0, CFrame.new(0, -1-0.52*math.cos(sine/2), .6) * angles(math.rad(96), math.rad(0), math.rad(0)+ RootPart.RotVelocity.Y / 26), .1)
					Torso.Neck.C0 = clerp(Torso.Neck.C0,necko *angles(math.rad(-11+20*math.sin(sine/2)),math.rad(0),math.rad(0+5*math.sin(sine/4)) + RootPart.RotVelocity.Y / 13),.1)
					RW.C0 = clerp(RW.C0, CFrame.new(1.5, 0.5, 0.1) * angles(math.rad(-90-7*math.sin(sine/4))+ RootPart.RotVelocity.Y / -34, math.rad(0), math.rad(15+2*math.sin(sine/4))- RootPart.RotVelocity.Y / 34),.15)
					LW.C0=clerp(LW.C0,cf(-1.5,0.5,0.1)*angles(math.rad(-90-7*math.sin(sine/4))+ RootPart.RotVelocity.Y / 34,math.rad(0),math.rad(-15+2*math.sin(sine/4))+ RootPart.RotVelocity.Y / -34),.15)
					LeftLeg.Weld.C0 = clerp(LeftLeg.Weld.C0, CFrame.new(-0.5, -1+0.28*math.cos(sine/4), 0-0.32*math.cos(sine/4)) * CFrame.Angles(math.rad(0+104*math.sin(sine/4)), math.rad(0)+ RootPart.RotVelocity.Y / 42, math.rad(0)+ RootPart.RotVelocity.Y / -54), 0.3+ Humanoid.WalkSpeed/272)
					RightLeg.Weld.C0 = clerp(RightLeg.Weld.C0, CFrame.new(0.5, -1-0.28*math.cos(sine/4),0+0.32*math.cos(sine/4)) * CFrame.Angles(math.rad(0-104*math.sin(sine/4)), math.rad(0)+ RootPart.RotVelocity.Y / 42, math.rad(0)- RootPart.RotVelocity.Y / 54), 0.3+ Humanoid.WalkSpeed/272)
				end
				velo:Destroy()
				wait(0.07)

				if vwall == false then

					RootPart.Velocity = -RootPart.CFrame.lookVector*68 + Vector3.new(0,86,0)

--[[]
		for i = 0,5,0.2 do
rs:wait()
Torso.Weld.C0 = clerp(Torso.Weld.C0, CFrame.new(0, -0.79, 0) * CFrame.Angles(math.rad(0+100*i), math.rad(0), math.rad(0)), 0.2)
Torso.Neck.C0 = clerp(Torso.Neck.C0,necko *angles(math.rad(20),math.rad(0),math.rad(0)),.2)
RW.C0 = clerp(RW.C0, CFrame.new(1.5, 0.5, 0) * angles(math.rad(180), math.rad(-60), math.rad(40)),.2)
LW.C0 = clerp(LW.C0, CFrame.new(-1.5, 0.5, 0) * angles(math.rad(180), math.rad(60), math.rad(-40)),.2)
LeftLeg.Weld.C0 = clerp(LeftLeg.Weld.C0, CFrame.new(-0.5, -1, 0) * CFrame.Angles(math.rad(0), math.rad(0), math.rad(0)), 0.2)
RightLeg.Weld.C0 = clerp(RightLeg.Weld.C0, CFrame.new(0.5, -1, 0) * CFrame.Angles(math.rad(0), math.rad(0), math.rad(0)), 0.2)
end
]]


					for i = 0,4,0.1 do
						swait()
						Humanoid.CameraOffset = Vector3.new(0,0,0)
						Torso.Weld.C0 = clerp(Torso.Weld.C0, CFrame.new(0, -1, 0) * CFrame.Angles(math.rad(0+260*i), math.rad(0), math.rad(0)), 0.6)
						Torso.Neck.C0 = clerp(Torso.Neck.C0,necko *angles(math.rad(70),math.rad(0),math.rad(0)),.1)
						RW.C0 = clerp(RW.C0, CFrame.new(.7, -0.22, -0.5) * angles(math.rad(90), math.rad(0), math.rad(-90)), 0.1)
						LW.C0 = clerp(LW.C0, CFrame.new(-.7, -0.22, -0.5) * angles(math.rad(90), math.rad(0), math.rad(90)), 0.1)
						LeftLeg.Weld.C0 = clerp(LeftLeg.Weld.C0, CFrame.new(-0.5, -.34, -0.7) * CFrame.Angles(math.rad(-25), math.rad(0), math.rad(0)), 0.1)
						RightLeg.Weld.C0 = clerp(RightLeg.Weld.C0, CFrame.new(0.5, -.34, -0.7) * CFrame.Angles(math.rad(-25), math.rad(0), math.rad(0)), 0.1)
					end

					attack = false


				end


				if vwall == true then
					RootPart.Velocity = RootPart.CFrame.lookVector*38 + Vector3.new(0,86,0)

--[[]
		for i = 0,5,0.2 do
rs:wait()
Torso.Weld.C0 = clerp(Torso.Weld.C0, CFrame.new(0, -0.79, 0) * CFrame.Angles(math.rad(0+100*i), math.rad(0), math.rad(0)), 0.2)
Torso.Neck.C0 = clerp(Torso.Neck.C0,necko *angles(math.rad(20),math.rad(0),math.rad(0)),.2)
RW.C0 = clerp(RW.C0, CFrame.new(1.5, 0.5, 0) * angles(math.rad(180), math.rad(-60), math.rad(40)),.2)
LW.C0 = clerp(LW.C0, CFrame.new(-1.5, 0.5, 0) * angles(math.rad(180), math.rad(60), math.rad(-40)),.2)
LeftLeg.Weld.C0 = clerp(LeftLeg.Weld.C0, CFrame.new(-0.5, -1, 0) * CFrame.Angles(math.rad(0), math.rad(0), math.rad(0)), 0.2)
RightLeg.Weld.C0 = clerp(RightLeg.Weld.C0, CFrame.new(0.5, -1, 0) * CFrame.Angles(math.rad(0), math.rad(0), math.rad(0)), 0.2)
end
]]


					for i = 0,4,0.15 do
						swait()
						Humanoid.CameraOffset = Vector3.new(0,0,0)
						Torso.Weld.C0 = clerp(Torso.Weld.C0, CFrame.new(0, -1, 0) * CFrame.Angles(math.rad(0-260*i), math.rad(0), math.rad(0)), 0.6)
						Torso.Neck.C0 = clerp(Torso.Neck.C0,necko *angles(math.rad(70),math.rad(0),math.rad(0)),.1)
						RW.C0 = clerp(RW.C0, CFrame.new(.7, -0.22, -0.5) * angles(math.rad(90), math.rad(0), math.rad(-90)), 0.1)
						LW.C0 = clerp(LW.C0, CFrame.new(-.7, -0.22, -0.5) * angles(math.rad(90), math.rad(0), math.rad(90)), 0.1)
						LeftLeg.Weld.C0 = clerp(LeftLeg.Weld.C0, CFrame.new(-0.5, -.34, -0.7) * CFrame.Angles(math.rad(-25), math.rad(0), math.rad(0)), 0.1)
						RightLeg.Weld.C0 = clerp(RightLeg.Weld.C0, CFrame.new(0.5, -.34, -0.7) * CFrame.Angles(math.rad(-25), math.rad(0), math.rad(0)), 0.1)
					end

					attack = false

				end


			end
		end
	end




	mouse.KeyUp:connect(function(key)
		if key == 'b' and vwall == true then
			vwall = false
		end
	end)





	function Ldash()



		evadecooldown = true
		attack = true
		k = math.random(1,2) 
		if k == 1 then
			so("http://www.roblox.com/asset/?id=807766310", Head, 2.5, 1)
		else
			so("http://www.roblox.com/asset/?id=807768137", Head, 2.5, 1)
		end





		--+173.8*i
		for i = 0,.7,0.1 do
			swait()
			Head.Velocity = Head.CFrame.rightVector * -135
			Torso.Weld.C0 = clerp(Torso.Weld.C0, CFrame.new(0, -1, 0) * CFrame.Angles(math.rad(0), math.rad(0), math.rad(32)), 0.2)
			Torso.Neck.C0 = clerp(Torso.Neck.C0,necko *angles(math.rad(0),math.rad(-9),math.rad(-14)),.2)
			RW.C0 = clerp(RW.C0, CFrame.new(1.5, 0.5, -0.2) * angles(math.rad(27), math.rad(0), math.rad(30)),.2)
			LW.C0 = clerp(LW.C0, CFrame.new(-1.5, 0.5, 0) * angles(math.rad(30), math.rad(0), math.rad(30)),.2)
			LeftLeg.Weld.C0 = clerp(LeftLeg.Weld.C0, CFrame.new(-0.5, -1, 0) * CFrame.Angles(math.rad(0), math.rad(0), math.rad(12)), 0.2)
			RightLeg.Weld.C0 = clerp(RightLeg.Weld.C0, CFrame.new(0.5, -1, 0) * CFrame.Angles(math.rad(0), math.rad(0), math.rad(8)), 0.2)
		end

		attack = false
		wait(0.08)
		evadecooldown = false


	end





	function Rdash()



		evadecooldown = true
		attack = true
		k = math.random(1,2) 
		if k == 1 then
			so("http://www.roblox.com/asset/?id=807766310", Head, 2.5, 1)
		else
			so("http://www.roblox.com/asset/?id=807768137", Head, 2.5, 1)
		end





		--+173.8*i
		for i = 0,.7,0.1 do
			swait()
			Head.Velocity = Head.CFrame.rightVector * 135
			Torso.Weld.C0 = clerp(Torso.Weld.C0, CFrame.new(0, -1, 0) * CFrame.Angles(math.rad(0), math.rad(0), math.rad(-32)), 0.2)
			Torso.Neck.C0 = clerp(Torso.Neck.C0,necko *angles(math.rad(0),math.rad(9),math.rad(14)),.2)
			RW.C0 = clerp(RW.C0, CFrame.new(1.5, 0.5, 0) * angles(math.rad(30), math.rad(0), math.rad(-30)),.2)
			LW.C0 = clerp(LW.C0, CFrame.new(-1.5, 0.5, -0.2) * angles(math.rad(27), math.rad(0), math.rad(-30)),.2)
			LeftLeg.Weld.C0 = clerp(LeftLeg.Weld.C0, CFrame.new(-0.5, -1, 0) * CFrame.Angles(math.rad(0), math.rad(0), math.rad(-8)), 0.2)
			RightLeg.Weld.C0 = clerp(RightLeg.Weld.C0, CFrame.new(0.5, -1, 0) * CFrame.Angles(math.rad(0), math.rad(0), math.rad(-12)), 0.2)
		end

		attack = false
		wait(0.08)
		evadecooldown = false


	end
	local sliding = false


	function Slide()

		local spd = Vector3.new(RootPart.Velocity.x,0,RootPart.Velocity.z).magnitude + 10
		spd = spd + 30
		local dir = Vector3.new(RootPart.Velocity.x,0,RootPart.Velocity.z).unit
		local GravPoint = RootPart.Velocity.y
		if spd > 40 and hitfloor ~= nil then
			noleg = true

			attack = true
			k = math.random(1,2) 
			if k == 1 then
				so("http://www.roblox.com/asset/?id=807766310", Head, 2.5, 1)
			else
				so("http://www.roblox.com/asset/?id=807768137", Head, 2.5, 1)
			end










			local NV = Vector3.new(0,0,0)
			local bv = Instance.new("BodyVelocity", Torso)
			bv.maxForce = Vector3.new(1/0,1/0,1/0)
			bv.velocity = dir*spd
			local bg = Instance.new("BodyGyro", Torso)
			bg.maxTorque = Vector3.new(1/0,1/0,1/0)
			bg.cframe = CFrame.new(NV, dir) * CFrame.Angles(math.pi/2.2,0.24,0)
			headsunsound.SoundId = "rbxassetid://1295468446"
			headsunsound.TimePosition = 0

			Humanoid.PlatformStand = true
			while spd > 2 and hitfloor ~= nil and sliding == true do
				swait()
				spd = spd - 0.95
				bv.velocity = dir*spd + Vector3.new(0,0,0)
				bg.cframe = CFrame.new(NV, dir) * CFrame.Angles(math.pi/2.2,0.24,0)
				Torso.Weld.C0 = clerp(Torso.Weld.C0, CFrame.new(0, -2.3, 0) * CFrame.Angles(math.rad(90), math.rad(0), math.rad(12)), 0.2)
				Torso.Neck.C0 = clerp(Torso.Neck.C0,necko *angles(math.rad(34),math.rad(0),math.rad(12)),.2)
				RW.C0 = clerp(RW.C0, CFrame.new(1.5, 0.5, 0) * angles(math.rad(110), math.rad(0), math.rad(70)),.2)
				LW.C0 = clerp(LW.C0, CFrame.new(-1.5, 0.5, -0.2) * angles(math.rad(0), math.rad(0), math.rad(-60)),.2)
				LeftLeg.Weld.C0 = clerp(LeftLeg.Weld.C0, CFrame.new(-0.5, -1, 0) * CFrame.Angles(math.rad(0), math.rad(0), math.rad(0)), 0.2)
				RightLeg.Weld.C0 = clerp(RightLeg.Weld.C0, CFrame.new(0.5, -0.56, -0.2) * CFrame.Angles(math.rad(-24), math.rad(0), math.rad(0)), 0.2)
			end
			bv:Destroy()
			bg:Destroy()
			headsunsound.SoundId = "rbxassetid://758199523"
			headsunsound.TimePosition = 0
			Humanoid.PlatformStand = false
			attack = false
			sliding = false
			wait(0.05)
			evadecooldown = false


		end
	end

	function land()
		attack = true
		RootPart.Velocity = Vector3.new(0,0,0)
		WaveEffect(BrickColor.new("Cyan"), RootPart.CFrame*CFrame.new(0,-1,0) , 1, 1, 1, 3, 0.8, 3, 0.06) 
		so("http://www.roblox.com/asset/?id=1295424585", Torso, 3.5, 1)

		coroutine.resume(coroutine.create(function()
			for i = 0,1,0.1 do
				swait()
				Humanoid.CameraOffset = Humanoid.CameraOffset:lerp(Vector3.new(math.random(-0.55*2.8,0.55*2.8),math.random(-0.55*2.8,0.55*2.8),math.random(-0.55*2.8,0.55*2.8)),0.44)
				Torso.Weld.C0 = clerp(Torso.Weld.C0, CFrame.new(0, -2, 0) * CFrame.Angles(math.rad(-16), math.rad(0), math.rad(0)), 0.5)
				Torso.Neck.C0 = clerp(Torso.Neck.C0,necko *angles(math.rad(7),math.rad(0),math.rad(0)),.5)
				RW.C0 = clerp(RW.C0, CFrame.new(1.5, 0.5, 0) * angles(math.rad(0), math.rad(0), math.rad(87)),.5)
				LW.C0 = clerp(LW.C0, CFrame.new(-1.5, 0.5, -0) * angles(math.rad(0), math.rad(0), math.rad(-87)),.5)
				LeftLeg.Weld.C0 = clerp(LeftLeg.Weld.C0, CFrame.new(-0.5, 0, -0.5) * CFrame.Angles(math.rad(16), math.rad(0), math.rad(0)), 0.5)
				RightLeg.Weld.C0 = clerp(RightLeg.Weld.C0, CFrame.new(0.5, -1.14, 0.2) * CFrame.Angles(math.rad(-17), math.rad(0), math.rad(0)), 0.5)

			end
			attack = false


		end))



	end




	function stomp()
		attack = true
		stompsound:Play()

		while hitfloor == nil do 
			swait()
			b.Size = 12
			WaveEffect(BrickColor.new("Cyan"), LeftLeg.CFrame*CFrame.new(0,-2.4,0) , 1, 1, 1, 0.8, 0.8, 0.8, 0.14) 
			RootPart.Velocity = Vector3.new(0,RootPart.Velocity.y/1.6,0) +Vector3.new(0,-150,0)
			Humanoid.CameraOffset = Humanoid.CameraOffset:lerp(Vector3.new(0,0,0),0.15)
			Torso.Weld.C0 = clerp(Torso.Weld.C0, CFrame.new(0, -1, 0.2) * CFrame.Angles(math.rad(0+4*math.sin(sine/1.3)), math.rad(0), math.rad(0)),0.07)
			RW.C0 = clerp(RW.C0, CFrame.new(1.5, 0.65, 0) * angles(math.rad(0), math.rad(0), math.rad(140+12*math.cos(sine/1.3))), 0.07)
			LW.C0 = clerp(LW.C0, CFrame.new(-1.5, 0.65, 0) * angles(math.rad(0), math.rad(0), math.rad(-140+12*math.cos(sine/1.3))), 0.07)
			Torso.Neck.C0 = clerp(Torso.Neck.C0,necko *angles(math.rad(60+7*math.sin(sine/1.3)),math.rad(0),math.rad(0)),0.07)
			LeftLeg.Weld.C0 = clerp(LeftLeg.Weld.C0, CFrame.new(-0.5, -1+0.17*math.cos(sine/1.3), -0.13) * CFrame.Angles(math.rad(0+4*math.cos(sine/1.3)), math.rad(3), math.rad(0)), 0.1)
			RightLeg.Weld.C0 = clerp(RightLeg.Weld.C0, CFrame.new(0.5, .27+0.17*math.cos(sine/1.3), -0.56) * CFrame.Angles(math.rad(-12+4*math.cos(sine/1.3)), math.rad(0), math.rad(0)), 0.1)

		end
		stompsound:Stop()
		land()


	end


	function changemusic()
		musicnum = musicnum + 1
		music.TimePosition = 0
		local osix = false
		local spd = Vector3.new(RootPart.Velocity.x,0,RootPart.Velocity.z).magnitude
		if musicnum > 14 then
			musicnum = 1
		end
		if musicnum == 1 then
			music.SoundId = "rbxassetid://179029173"
		end
		if musicnum == 2 then
			music.SoundId = "rbxassetid://146443855"
		end
		if musicnum == 3 then
			music.SoundId = "rbxassetid://1342408291" 
		end
		if musicnum == 4 then
			music.SoundId = "rbxassetid://201219416"  
		end
		if musicnum == 5 then
			music.SoundId = "rbxassetid://1390472571" 
		end
		if musicnum == 6 then
			osix = true
			music.SoundId = "rbxassetid://249974783" 
		end
		if musicnum == 7 then
			music.SoundId = "rbxassetid://1851880603"
		end
		if musicnum == 8 then
			music.SoundId = "rbxassetid://412034984"
		end
		if musicnum == 9 then
			music.SoundId = "rbxassetid://536915629"
		end
		if musicnum == 10 then
			music.SoundId = "rbxassetid://1200005861"
		end
		if musicnum == 11 then
			music.SoundId = "rbxassetid://1055930631"
		end
		if musicnum == 12 then
			music.SoundId = "rbxassetid://300269553"
		end
		if musicnum == 13 then
			music.SoundId = "rbxassetid://199897052"
		end
		if musicnum == 14 then
			music.SoundId = "rbxassetid://638115895"  
		end

		if spd < 14 then
			Humanoid.Jump = true

			if osix == false then
				so("rbxassetid://537371462",RootPart,2,1)
			end


			RootPart.Velocity = Vector3.new(0,102,0)
			attack = true
			wait(0.08)
			for i = 0,7,0.1 do
				swait()
				RootPart.Velocity = Vector3.new(0,2,0)
				Humanoid.CameraOffset = Vector3.new(0,0,0)
				Torso.Weld.C0 = clerp(Torso.Weld.C0, CFrame.new(0, -1, 0) * CFrame.Angles(math.rad(0-260*i), math.rad(0), math.rad(0)), 0.6)
				Torso.Neck.C0 = clerp(Torso.Neck.C0,necko *angles(math.rad(70),math.rad(0),math.rad(0)),.1)
				RW.C0 = clerp(RW.C0, CFrame.new(.7, -0.22, -0.5) * angles(math.rad(90), math.rad(0), math.rad(-90)), 0.1)
				LW.C0 = clerp(LW.C0, CFrame.new(-.7, -0.22, -0.5) * angles(math.rad(90), math.rad(0), math.rad(90)), 0.1)
				LeftLeg.Weld.C0 = clerp(LeftLeg.Weld.C0, CFrame.new(-0.5, -.34, -0.7) * CFrame.Angles(math.rad(-25), math.rad(0), math.rad(0)), 0.1)
				RightLeg.Weld.C0 = clerp(RightLeg.Weld.C0, CFrame.new(0.5, -.34, -0.7) * CFrame.Angles(math.rad(-25), math.rad(0), math.rad(0)), 0.1)

			end
			b.Size = 40
			MoonEffect(BrickColor.new("Cyan"), RootPart.CFrame*CFrame.new(0,0,0) , 1, 1, 1, 8, 8, 8, 0.06) 

			if osix == true then
				osix = false
				so("rbxassetid://156821036",RootPart,2,1)
			end

			Torso.Weld.C0 = clerp(Torso.Weld.C0, CFrame.new(0, -3, 0) * CFrame.Angles(math.rad(0), math.rad(0), math.rad(0)), 1)
			for i = 0,5,0.1 do
				swait()
				RootPart.Velocity = Vector3.new(0,3.5,0)
				Humanoid.CameraOffset = Vector3.new(0,0,0)
				Torso.Weld.C0 = clerp(Torso.Weld.C0, CFrame.new(0, -1+0.1*i, 0) * CFrame.Angles(math.rad(0), math.rad(0), math.rad(0)), 0.21)
				Torso.Neck.C0 = clerp(Torso.Neck.C0,necko *angles(math.rad(22-2*i),math.rad(0),math.rad(0)),.21)
				RW.C0 = clerp(RW.C0, CFrame.new(1.5, 0.5+0.09*i, 0) * angles(math.rad(20-6*i), math.rad(0), math.rad(90+13*i)), 0.21)
				LW.C0 = clerp(LW.C0, CFrame.new(-1.0-0.12*i, 0.5, -0.4+0.05*i) * angles(math.rad(20+13*i), math.rad(0), math.rad(20-13*i)), 0.21)
				LeftLeg.Weld.C0 = clerp(LeftLeg.Weld.C0, CFrame.new(-0.5, -1, 0) * CFrame.Angles(math.rad(45+6*i), math.rad(0), math.rad(-22-4*i)), 0.21)
				RightLeg.Weld.C0 = clerp(RightLeg.Weld.C0, CFrame.new(0.5, -1, 0) * CFrame.Angles(math.rad(45+6*i), math.rad(0), math.rad(22+4*i)), 0.21)
			end
			attack = false
		end
	end


	mouse.KeyDown:connect(function(key)
		if key == 'q' and attack == false and evadecooldown == false then
			Ldash()
		end
	end)



	mouse.KeyDown:connect(function(key)
		if key == 'e' and attack == false and evadecooldown == false then
			Rdash()
		end
	end)

	mouse.KeyDown:connect(function(key)
		if key == 'c' and attack == false and evadecooldown == false and hitfloor ~= nil then
			sliding = true
			Slide()
		end
	end)

	mouse.KeyDown:connect(function(key)
		if key == 'c' and attack == false and hitfloor == nil then
			stomp()
		end
	end)


	local walljump = false


	function walljumpp()
		local ray = Ray.new(
			Torso.CFrame.p, RootPart.CFrame.lookVector *5
		)
		local hit, position, normal = workspace:FindPartOnRay(ray, character)

		if hit then
			if  hit.Parent.Parent ~= Character and hit.Parent ~= Character then
				local dir = Vector3.new(RootPart.Velocity.x,0,RootPart.Velocity.z).unit
				GravPoint = 0
				freefall = 0
				walljump = true 
				Humanoid.AutoRotate = false
				local velo = Instance.new("BodyVelocity",Torso)
				velo.MaxForce = Vector3.new(400000,400000,400000)
				--game.Debris:AddItem(velo,0.1)
				attack = true
				while hitfloor == nil and walljump == true and ray and hit  do
					swait()
					freefall = 0
					GravPoint = GravPoint - 0.36
					ray = Ray.new(
						RootPart.CFrame.p, RootPart.CFrame.lookVector *2.5
					)
					hit, position, normal = workspace:FindPartOnRay(ray, character)
					velo.Velocity = vt(0,GravPoint,0)
					Torso.Weld.C0 = clerp(Torso.Weld.C0, CFrame.new(0, -1, 0.9) * CFrame.Angles(math.rad(5), math.rad(90), math.rad(8)), 0.2)
					Torso.Neck.C0 = clerp(Torso.Neck.C0,necko *angles(math.rad(7),math.rad(0),math.rad(86)),.2)
					RW.C0 = clerp(RW.C0, CFrame.new(1.5, 0.5, 0) * angles(math.rad(0), math.rad(0), math.rad(120)),.2)
					LW.C0 = clerp(LW.C0, CFrame.new(-1.5, 0.5, 0) * angles(math.rad(0), math.rad(0), math.rad(-60)),.2)
					LeftLeg.Weld.C0 = clerp(LeftLeg.Weld.C0, CFrame.new(-0.5, -1, 0) * CFrame.Angles(math.rad(-6), math.rad(14), math.rad(-12)), 0.2)
					RightLeg.Weld.C0 = clerp(RightLeg.Weld.C0, CFrame.new(0.5, -1, 0) * CFrame.Angles(math.rad(0), math.rad(0), math.rad(23)), 0.2)
				end
				if walljump == false then
					k = math.random(1,3) 
					if k == 1 then
						so("http://www.roblox.com/asset/?id=800121776", Head, 2.5, 1)
					else if k == 2 then
							so("http://www.roblox.com/asset/?id=804889329", Head, 2.5, 1)
						else if k == 3 then
								so("http://www.roblox.com/asset/?id=804907617", Head, 2.5, 1)
							end
						end
					end

					velo:Destroy()
					attack = false
					coroutine.resume(coroutine.create(function()
						for i = 0,1,0.1 do
							swait()
							Humanoid.CameraOffset = Vector3.new(0,0,0)
							Torso.Weld.C0 = clerp(Torso.Weld.C0, CFrame.new(0, -1, 0) * CFrame.Angles(math.rad(0+260*i), math.rad(0), math.rad(0)), 0.6)
							Torso.Neck.C0 = clerp(Torso.Neck.C0,necko *angles(math.rad(70),math.rad(0),math.rad(0)),.1)
							RW.C0 = clerp(RW.C0, CFrame.new(.7, -0.22, -0.5) * angles(math.rad(90), math.rad(0), math.rad(-90)), 0.1)
							LW.C0 = clerp(LW.C0, CFrame.new(-.7, -0.22, -0.5) * angles(math.rad(90), math.rad(0), math.rad(90)), 0.1)
							LeftLeg.Weld.C0 = clerp(LeftLeg.Weld.C0, CFrame.new(-0.5, -.34, -0.7) * CFrame.Angles(math.rad(-25), math.rad(0), math.rad(0)), 0.1)
							RightLeg.Weld.C0 = clerp(RightLeg.Weld.C0, CFrame.new(0.5, -.34, -0.7) * CFrame.Angles(math.rad(-25), math.rad(0), math.rad(0)), 0.1)
						end
					end))

					Humanoid.AutoRotate = true
					RootPart.Velocity = RootPart.CFrame.lookVector * -137 + Vector3.new(0,136,0)
					wait(0.07)
					RootPart.CFrame = CFrame.new(RootPart.CFrame.p,-RootPart.CFrame.lookVector)
				end
				if walljump == true then
					attack = false
					walljump = false
					Humanoid.AutoRotate = true
					velo:Destroy()
				end
			end
		end
	end


	local homed = nil
	function home()
		if walljump ~= true then
			for i, v in pairs(FindNearestTorso(Torso.CFrame.p, 80)) do
				if v:FindFirstChild('Head') then
					Grabbed = true
					homed = v
				end
			end

			if homed ~= nil and homed:FindFirstChildOfClass("Humanoid").Health > 1 and walljump == false then
				so("http://www.roblox.com/asset/?id=162460823", Head, 1, .8)
				local SBall = Instance.new("Part",Character)
				SBall.Name = "Homing Ball"
				SBall.CanCollide = false
				SBall.Anchored = false
				SBall.Transparency = 0.64
				SBall.CFrame = CFrame.new(RootPart.CFrame.p)
				SBall.BrickColor = BrickColor.new("Toothpaste")
				SBall.Size = Vector3.new(1,1,1)
				SBall.Material = "Neon"
				SBallweld = Instance.new("Weld")
				SBallweld.Parent = SBall
				SBallweld.Part0 = RootPart
				SBallweld.Part1 = SBall
				SBallweld.C1 = CFrame.new(0, 1, 0)*CFrame.Angles(math.rad(0),math.rad(0),math.rad(0))
				SBallweld.Part0 = RootPart
				local SBallmesh = Instance.new("SpecialMesh",SBall)
				SBallmesh.MeshType = "Sphere"
				SBallmesh.Scale = Vector3.new(6,6,6)
				trail = Instance.new("Trail", Character)
				a2 = Instance.new("Attachment", Torso) a2.Position = Vector3.new(0,2,0)
				a3 = Instance.new("Attachment", Torso)a3.Position = Vector3.new(0,-2.5,0)
				trail.Texture = "rbxassetid://0"
				trail.Attachment0 = a2
				trail.Attachment1 = a3
				trail.Lifetime  =  0.353
				trail.MinLength = 0.03
				trail.Transparency = NumberSequence.new({NumberSequenceKeypoint.new(0,0,0),NumberSequenceKeypoint.new(1,1,1)})
				trail.Color = ColorSequence.new(Color3.new(0,1,1), Color3.new(0, 0,0))
				trail.LightEmission = 4.8
				trail.TextureLength = 0.034
				trail.Enabled = true
				attack = true
				local position = Instance.new("BodyPosition",Torso)
				position.P = 68350
				position.maxForce = Vector3.new(math.huge,math.huge,math.huge)

				while homed ~= nil and (homed.Torso.Position-RootPart.Position).magnitude > 8 do
					swait()
					SBall.CFrame = CFrame.new(RootPart.CFrame.p)
					Torso.Weld.C0 = clerp(Torso.Weld.C0, CFrame.new(0, -1, 0) * CFrame.Angles(math.rad(0+420*math.abs(sine/3.2)), math.rad(0), math.rad(0)), 0.6)
					Torso.Neck.C0 = clerp(Torso.Neck.C0,necko *angles(math.rad(70),math.rad(0),math.rad(0)),.1)
					RW.C0 = clerp(RW.C0, CFrame.new(.7, -0.22, -0.5) * angles(math.rad(90), math.rad(0), math.rad(-90)), 0.1)
					LW.C0 = clerp(LW.C0, CFrame.new(-.7, -0.22, -0.5) * angles(math.rad(90), math.rad(0), math.rad(90)), 0.1)
					LeftLeg.Weld.C0 = clerp(LeftLeg.Weld.C0, CFrame.new(-0.5, -.34, -0.7) * CFrame.Angles(math.rad(-25), math.rad(0), math.rad(0)), 0.1)
					RightLeg.Weld.C0 = clerp(RightLeg.Weld.C0, CFrame.new(0.5, -.34, -0.7) * CFrame.Angles(math.rad(-25), math.rad(0), math.rad(0)), 0.1)
					position.Position = homed.Torso.Position + Vector3.new(0,2,0) 
				end
				local bodvol=Instance.new("BodyVelocity")
				bodvol.velocity= RootPart.CFrame.lookVector*240 + Vector3.new(0,30,0)
				bodvol.P= 35200
				bodvol.maxForce=Vector3.new(8e+003, 8e+003, 8e+003)
				bodvol.Parent=homed.Head
				game:GetService("Debris"):AddItem(bodvol, 0.2)
				--homed:FindFirstChildOfClass("Humanoid"):TakeDamage(math.random(10,30))

				position:Destroy()
				trail.Enabled = false
				SBall:Destroy()
				RootPart.Velocity = Vector3.new(0,93.5,0)
				coroutine.resume(coroutine.create(function()
					for i = 0,5,0.26 do
						swait()
						Humanoid.CameraOffset = Vector3.new(0,0,0)
						Torso.Weld.C0 = clerp(Torso.Weld.C0, CFrame.new(0, -1+0.1*i, 0) * CFrame.Angles(math.rad(0), math.rad(0), math.rad(0)), 0.21)
						Torso.Neck.C0 = clerp(Torso.Neck.C0,necko *angles(math.rad(22-2*i),math.rad(0),math.rad(0)),.21)
						RW.C0 = clerp(RW.C0, CFrame.new(1.5, 0.5+0.09*i, 0) * angles(math.rad(20-6*i), math.rad(0), math.rad(90+13*i)), 0.21)
						LW.C0 = clerp(LW.C0, CFrame.new(-1.0-0.12*i, 0.5, -0.4+0.05*i) * angles(math.rad(20+13*i), math.rad(0), math.rad(20-13*i)), 0.21)
						LeftLeg.Weld.C0 = clerp(LeftLeg.Weld.C0, CFrame.new(-0.5, -1, 0) * CFrame.Angles(math.rad(45+6*i), math.rad(0), math.rad(-22-4*i)), 0.21)
						RightLeg.Weld.C0 = clerp(RightLeg.Weld.C0, CFrame.new(0.5, -1, 0) * CFrame.Angles(math.rad(45+6*i), math.rad(0), math.rad(22+4*i)), 0.21)
					end
					homed = nil
					attack = false
				end))

			end

		end


	end

	mouse.KeyDown:connect(function(key)
		wait(0.16)
		if string.byte(key) == 32 and hitfloor == nil and attack == false and walljump == false and Humanoid.Jump == true then
			walljumpp()
		end
		if string.byte(key) == 32 and hitfloor == nil and attack == false and walljump == false and Humanoid.Jump == true then
			home()
		end

		if string.byte(key) == 32 and hitfloor == nil and attack == true and walljump == true then
			walljump = false
		end
	end)



	mouse.KeyDown:connect(function(key)
		if key == 'm' and attack == false then
			changemusic()
		end
	end)

	local MutedMusic = false
	mouse.KeyDown:connect(function(key)
		if key == 'n' then
			if not MutedMusic then
				MutedMusic = true
				music.Volume = 0
			elseif MutedMusic then
				MutedMusic = false
				music.Volume = 1
			end
		end
	end)




	mouse.KeyUp:connect(function(key)
		wait(0.05)
		if key == 'c' and sliding == true then
			sliding = false
		end
	end)
	local look = 0



	while true do
		swait()
		sine = sine + change
		--speed = speed + music.PlaybackLoudness/90
		local torvel=(RootPart.Velocity*Vector3.new(1,0,1)).magnitude
		local velderp=RootPart.Velocity.y
		hitfloor,posfloor=rayCast(RootPart.Position,(CFrame.new(RootPart.Position,RootPart.Position - Vector3.new(0,1,0))).lookVector,4,Character)

		local TiltVelocity = CFrame.new(RootPart.CFrame:vectorToObjectSpace(RootPart.Velocity))

		local rlegray = Ray.new(RightLeg.Position+Vector3.new(0,0.54,0),Vector3.new(0, -1.75, 0))
		local rlegpart, rlegendPoint = workspace:FindPartOnRay(rlegray, Character)

		local llegray = Ray.new(LeftLeg.Position+Vector3.new(0,0.54,0),Vector3.new(0, -1.75, 0))
		local llegpart, llegendPoint = workspace:FindPartOnRay(llegray, Character)

		local waterthing = Ray.new(RootPart.CFrame.p,Vector3.new(0,-1,0))
		local start, position = workspace:FindPartOnRay(waterthing, character)

		if start ~= nil and start.Material == "Water" then

			RootPart.Velocity = RootPart.Velocity + Vector3.new(0,6,0)

		end

		headsunsound.Pitch = 0.76 + Humanoid.WalkSpeed/124
		if torvel<1  and Swing == 2 then
			boost = false
		elseif torvel>1   and Swing == 2 then
			boost = true
			freefall = 0
		end
		if hitfloor ~= nil and freefall < 150 then
			freefall = 0
		end
		if freefall > 150 and hitfloor ~= nil then
			land()
			freefall = 0
		end







		if RootPart.Velocity.y > 1 and hitfloor==nil then
			Anim="Jump"





			if attack==false then
				change = 1
				look = 0
				Humanoid.CameraOffset = Humanoid.CameraOffset:lerp(Vector3.new(0,0,0),0.15)
				Torso.Weld.C0 = clerp(Torso.Weld.C0, CFrame.new(0, -1, 0) * CFrame.Angles(math.rad(4), math.rad(0), math.rad(0)), 0.07)
				Torso.Neck.C0 = clerp(Torso.Neck.C0,necko *angles(math.rad(-10+2.05*math.cos(sine/5)),math.rad(0),math.rad(0)),0.07)
				RW.C0 = clerp(RW.C0, CFrame.new(1.5, 0.5, 0) * angles(math.rad(-20+2.05*math.cos(sine/5)), math.rad(-10), math.rad(50-2.05*math.cos(sine/5))), 0.07)
				LW.C0 = clerp(LW.C0, CFrame.new(-1.5, 0.5, 0) * angles(math.rad(-20+2.05*math.cos(sine/5)), math.rad(-10), math.rad(-50+2.05*math.cos(sine/5))), 0.07)
				RightLeg.Weld.C0 = clerp(RightLeg.Weld.C0, CFrame.new(0.5, -1, -0.6) * CFrame.Angles(math.rad(-25+3.05*math.cos(sine/5)), math.rad(-3), math.rad(0)), 0.1)
				LeftLeg.Weld.C0 = clerp(LeftLeg.Weld.C0, CFrame.new(-0.5, -.47, -0.7) * CFrame.Angles(math.rad(-12+3.05*math.cos(sine/5)), math.rad(0), math.rad(0)), 0.1)
			end

		elseif RootPart.Velocity.y < -1 and freefall <150 and hitfloor==nil then
			Anim="Fall"
			change = 1
			freefall = freefall +0.77


			if attack==false then
				Humanoid.CameraOffset = Humanoid.CameraOffset:lerp(Vector3.new(0,0,0),0.15)
				Torso.Weld.C0 = clerp(Torso.Weld.C0, CFrame.new(0, -1, 0.2) * CFrame.Angles(math.rad(7+4*math.sin(sine/1.3)), math.rad(0), math.rad(0)),0.07)
				RW.C0 = clerp(RW.C0, CFrame.new(1.5, 0.65, 0) * angles(math.rad(0), math.rad(0), math.rad(140+12*math.cos(sine/1.3))), 0.07)
				LW.C0 = clerp(LW.C0, CFrame.new(-1.5, 0.65, 0) * angles(math.rad(0), math.rad(0), math.rad(-140+12*math.cos(sine/1.3))), 0.07)
				Torso.Neck.C0 = clerp(Torso.Neck.C0,necko *angles(math.rad(40+7*math.sin(sine/1.3)),math.rad(0),math.rad(0)),0.07)
				LeftLeg.Weld.C0 = clerp(LeftLeg.Weld.C0, CFrame.new(-0.5, -1+0.17*math.cos(sine/1.3), -0.13) * CFrame.Angles(math.rad(18+7*math.cos(sine/1.3)), math.rad(3), math.rad(0)), 0.1)
				RightLeg.Weld.C0 = clerp(RightLeg.Weld.C0, CFrame.new(0.5, -.37+0.17*math.cos(sine/1.3), -0.2) * CFrame.Angles(math.rad(32+7*math.cos(sine/1.3)), math.rad(0), math.rad(0)), 0.1)
			end



		elseif RootPart.Velocity.y < -1 and freefall > 150 and hitfloor==nil then
			Anim="FreeFall"
			change = 1


			if attack==false then
				Humanoid.CameraOffset = Humanoid.CameraOffset:lerp(Vector3.new(0,0,0),0.15)
				Torso.Weld.C0 = clerp(Torso.Weld.C0, CFrame.new(0, -1, 0.2) * CFrame.Angles(math.rad(-90+3*math.sin(sine/1.3)), math.rad(0), math.rad(0)),0.07)
				RW.C0 = clerp(RW.C0, CFrame.new(1.5, 0.5, 0) * angles(math.rad(14+12*math.cos(sine/1.3)), math.rad(0), math.rad(110)), 0.07)
				LW.C0 = clerp(LW.C0, CFrame.new(-1.5, 0.5, 0) * angles(math.rad(14+12*math.cos(sine/1.3)), math.rad(0), math.rad(-110)), 0.07)
				Torso.Neck.C0 = clerp(Torso.Neck.C0,necko *angles(math.rad(-12+7*math.sin(sine/1.3)),math.rad(0),math.rad(0)),0.07)
				LeftLeg.Weld.C0 = clerp(LeftLeg.Weld.C0, CFrame.new(-0.5, -1+0.17*math.cos(sine/1.3),0.2) * CFrame.Angles(math.rad(-12+4*math.cos(sine/1.3)), math.rad(3), math.rad(-46)), 0.1)
				RightLeg.Weld.C0 = clerp(RightLeg.Weld.C0, CFrame.new(0.5, -1+0.17*math.cos(sine/1.3), 0.2) * CFrame.Angles(math.rad(-12+4*math.cos(sine/1.3)), math.rad(0), math.rad(46)), 0.1)
			end

		elseif torvel<1 and hitfloor~=nil then
			Anim="Idle"
			change = 1
			if attack==false and equip == false then

				Humanoid.CameraOffset = Humanoid.CameraOffset:lerp(Vector3.new(0,0,0),0.15)
				Torso.Weld.C0 = clerp(Torso.Weld.C0, CFrame.new(0, -1-0.04*math.cos(sine/40), -0) * CFrame.Angles(math.rad(0-0.81*math.cos(sine/40)), math.rad(-40), math.rad(0)), 0.1)
				Torso.Neck.C0 = clerp(Torso.Neck.C0,necko *angles(math.rad(0+2.6*math.sin(sine/40)),math.rad(0),math.rad(40)),0.1)
				RW.C0 = clerp(RW.C0, CFrame.new(1.5, 0.55+0.04*math.sin(sine/40), 0-0.04*math.cos(sine/40)) * angles(math.rad(-2+1.3*math.cos(sine/40)), math.rad(0+4*math.sin(sine/40)), math.rad(6.3+2.2*math.cos(sine/40))),0.1)
				LW.C0 = clerp(LW.C0, CFrame.new(-1.5, 0.55+0.04*math.sin(sine/40), 0-0.04*math.cos(sine/40)) * angles(math.rad(2+1.3*math.cos(sine/40)), math.rad(0-4*math.sin(sine/40)), math.rad(-6.3-2.2*math.cos(sine/40))),0.1)
				LeftLeg.Weld.C0 = clerp(LeftLeg.Weld.C0, CFrame.new(-0.5, llegendPoint.Y-LeftLeg.Position.Y+0.04*math.cos(sine/40), 0) * CFrame.Angles(math.rad(0+0.81*math.cos(sine/40)), math.rad(18+0.81*math.cos(sine/40)), math.rad(-2-0.81*math.cos(sine/40))),0.1)
				RightLeg.Weld.C0 = clerp(RightLeg.Weld.C0, CFrame.new(0.57, rlegendPoint.Y-RightLeg.Position.Y+0.04*math.cos(sine/40), 0)  * CFrame.Angles(math.rad(0+0.81*math.cos(sine/40)), math.rad(-2+0.81*math.cos(sine/40)), math.rad(3-0.81*math.cos(sine/40))),0.1)
			end



		elseif torvel>1.5 and torvel<70 and hitfloor~=nil then
			Anim="Walk"
			change = 0.84+ Character.Humanoid.WalkSpeed/132
			look = 0
			if attack==false and equip == false then
				Humanoid.CameraOffset = Humanoid.CameraOffset:lerp(Vector3.new(0,0,0),0.02)
				Torso.Weld.C0 = clerp(Torso.Weld.C0, CFrame.new(0, -1-0.52*math.cos(sine/2), -.8) * angles(math.rad(-26), math.rad(0), math.rad(0)+ RootPart.RotVelocity.Y / 26), .1)
				Torso.Neck.C0 = clerp(Torso.Neck.C0,necko *angles(math.rad(-11+20*math.sin(sine/2)),math.rad(0),math.rad(0+5*math.sin(sine/4)) + RootPart.RotVelocity.Y / 13),.1)
				RW.C0 = clerp(RW.C0, CFrame.new(1.5, 0.5, 0.1) * angles(math.rad(-60-7*math.sin(sine/4))+ RootPart.RotVelocity.Y / -34, math.rad(0), math.rad(15+2*math.sin(sine/4))- RootPart.RotVelocity.Y / 34),.15)
				LW.C0=clerp(LW.C0,cf(-1.5,0.5,0.1)*angles(math.rad(-60-7*math.sin(sine/4))+ RootPart.RotVelocity.Y / 34,math.rad(0),math.rad(-15+2*math.sin(sine/4))+ RootPart.RotVelocity.Y / -34),.15)
				LeftLeg.Weld.C0 = clerp(LeftLeg.Weld.C0, CFrame.new(-0.5, -1+0.28*math.cos(sine/4), 0-0.32*math.cos(sine/4)) * CFrame.Angles(math.rad(0+104*math.sin(sine/4)), math.rad(0)+ RootPart.RotVelocity.Y / 42, math.rad(0)+ RootPart.RotVelocity.Y / -54), 0.3)
				RightLeg.Weld.C0 = clerp(RightLeg.Weld.C0, CFrame.new(0.5, -1-0.28*math.cos(sine/4),0+0.32*math.cos(sine/4)) * CFrame.Angles(math.rad(0-104*math.sin(sine/4)), math.rad(0)+ RootPart.RotVelocity.Y / 42, math.rad(0)- RootPart.RotVelocity.Y / 54), 0.3)
			end


		elseif torvel>=70 and torvel<200 and hitfloor~=nil then
			Anim="Run"
			change = 0.84+ Character.Humanoid.WalkSpeed/142
			if attack==false and equip == false then
				Humanoid.CameraOffset = Humanoid.CameraOffset:lerp(Vector3.new(0,0,0),0.02)
				Torso.Weld.C0 = clerp(Torso.Weld.C0, CFrame.new(0, -1-0.52*math.cos(sine/1.5), -.8) * angles(math.rad(-37), math.rad(0), math.rad(0)+ RootPart.RotVelocity.Y / 26), .1)
				Torso.Neck.C0 = clerp(Torso.Neck.C0,necko *angles(math.rad(-11+25*math.sin(sine/1.5)),math.rad(0),math.rad(0+5*math.sin(sine/3)) + RootPart.RotVelocity.Y / 13),.1)
				RW.C0 = clerp(RW.C0, CFrame.new(1.5, 0.5, 0.3) * angles(math.rad(-72-8*math.sin(sine/1.5))+ RootPart.RotVelocity.Y / -34, math.rad(0), math.rad(1+0*math.cos(sine/3))- RootPart.RotVelocity.Y / 34),.25)
				LW.C0=clerp(LW.C0,cf(-1.5,0.5,0.3)*angles(math.rad(-72-8*math.sin(sine/1.5))+ RootPart.RotVelocity.Y / 34,math.rad(0),math.rad(-1+0*math.cos(sine/3))+ RootPart.RotVelocity.Y / -34),.25)
				LeftLeg.Weld.C0 = clerp(LeftLeg.Weld.C0, CFrame.new(-0.5, -1+0.32*math.cos(sine/3), 0-0.42*math.cos(sine/3)) * CFrame.Angles(math.rad(0+134*math.sin(sine/3)), math.rad(0)+ RootPart.RotVelocity.Y / 42, math.rad(0)+ RootPart.RotVelocity.Y / -54), 0.44)
				RightLeg.Weld.C0 = clerp(RightLeg.Weld.C0, CFrame.new(0.5, -1-0.32*math.cos(sine/3),0+0.42*math.cos(sine/3)) * CFrame.Angles(math.rad(0-134*math.sin(sine/3)), math.rad(0)+ RootPart.RotVelocity.Y / 42, math.rad(0)- RootPart.RotVelocity.Y / 54), 0.44)
			end

		--[[
		if attack==false then
		LeftLeg.Weld.C0 = clerp(LeftLeg.Weld.C0, CFrame.new(-0.5, -1-0.4*math.cos(sine/5.5)/2, 0 *math.sin(sine/6.6)/2) * CFrame.Angles(math.rad(0) + -math.sin(sine/5.5)/1.2, math.rad(0), 0), .8)
		RightLeg.Weld.C0 = clerp(RightLeg.Weld.C0, CFrame.new(0.5, -1+0.4*math.cos(sine/5.5)/2,0 *-math.sin(sine/6.6)/2) * CFrame.Angles(math.rad(0) + math.sin(sine/5.5)/1.2, math.rad(0), 0), .8)
		end
		]]
			if attack==true and noleg == false then
				LeftLeg.Weld.C0 = clerp(LeftLeg.Weld.C0, CFrame.new(-0.5, -1-0.24*math.cos(sine/5), 0.+0.24*math.cos(sine/5)) * CFrame.Angles(math.rad(0-74*math.sin(sine/5)), math.rad(0), math.rad(0)), 0.3)
				RightLeg.Weld.C0 = clerp(RightLeg.Weld.C0, CFrame.new(0.5, -1+0.24*math.cos(sine/5),0.-0.24*math.cos(sine/5)) * CFrame.Angles(math.rad(0+74*math.sin(sine/5)), math.rad(0), math.rad(0)), 0.3)
			end



		elseif torvel>=200 and hitfloor~=nil then
			Anim="MachRun"
			change = 0.84+ Character.Humanoid.WalkSpeed/182
			if attack==false and equip == false then
				Humanoid.CameraOffset = Humanoid.CameraOffset:lerp(Vector3.new(0,0,0),0.02)
				Torso.Weld.C0 = clerp(Torso.Weld.C0, CFrame.new(0, -1-0.52*math.cos(sine/1), -3.8) * angles(math.rad(-44), math.rad(0), math.rad(0)+ RootPart.RotVelocity.Y / 26), .2)
				Torso.Neck.C0 = clerp(Torso.Neck.C0,necko *angles(math.rad(-11+25*math.sin(sine/1)),math.rad(0),math.rad(0+5*math.sin(sine/2)) + RootPart.RotVelocity.Y / 13),.2)
				RW.C0 = clerp(RW.C0, CFrame.new(1.5, 0.5, 0.5) * angles(math.rad(-78-12*math.sin(sine/1))+ RootPart.RotVelocity.Y / -34, math.rad(0), math.rad(-24+0*math.cos(sine/2))- RootPart.RotVelocity.Y / 34),.35)
				LW.C0=clerp(LW.C0,cf(-1.5,0.5,0.5)*angles(math.rad(-78-12*math.sin(sine/1))+ RootPart.RotVelocity.Y / 34,math.rad(0),math.rad(24+0*math.cos(sine/2))+ RootPart.RotVelocity.Y / -34),.35)
				LeftLeg.Weld.C0 = clerp(LeftLeg.Weld.C0, CFrame.new(-0.5, -1+0.42*math.cos(sine/2), 0-0.62*math.cos(sine/2)) * CFrame.Angles(math.rad(0+134*math.sin(sine/2)), math.rad(0)+ RootPart.RotVelocity.Y / 42, math.rad(0)+ RootPart.RotVelocity.Y / -54), 0.52)
				RightLeg.Weld.C0 = clerp(RightLeg.Weld.C0, CFrame.new(0.5, -1-0.42*math.cos(sine/2),0+0.62*math.cos(sine/2)) * CFrame.Angles(math.rad(0-134*math.sin(sine/2)), math.rad(0)+ RootPart.RotVelocity.Y / 42, math.rad(0)- RootPart.RotVelocity.Y / 54), 0.52)
			end



		end









		if 0 < #Effects then
			for e = 1, #Effects do
				if Effects[e] ~= nil then
					local Thing = Effects[e]
					if Thing ~= nil then
						local Part = Thing[1]
						local Mode = Thing[2]
						local Delay = Thing[3]
						local IncX = Thing[4]
						local IncY = Thing[5]
						local IncZ = Thing[6]
						if Thing[1].Transparency <= 1 then
							if Thing[2] == "Block1" then
								Thing[1].CFrame = Thing[1].CFrame * euler(math.random(-50, 50), math.random(-50, 50), math.random(-50, 50))
								Mesh = Thing[1]:FindFirstChild("Mesh")
								if not Mesh then
									Mesh = Instance.new("BlockMesh")
								end
								Mesh.Scale = Mesh.Scale + vt(Thing[4], Thing[5], Thing[6])
								Thing[1].Transparency = Thing[1].Transparency + Thing[3]
							elseif Thing[2] == "Cylinder" then
								Mesh = Thing[1]:FindFirstChild("Mesh")
								if not Mesh then
									Mesh = Instance.new("BlockMesh")
								end
								Mesh.Scale = Mesh.Scale + vt(Thing[4], Thing[5], Thing[6])
								Thing[1].Transparency = Thing[1].Transparency + Thing[3]
							elseif Thing[2] == "Blood" then
								Mesh = Thing[1]:FindFirstChild("Mesh")
								if not Mesh then
									Mesh = Instance.new("BlockMesh")
								end
								Thing[1].CFrame = Thing[1].CFrame * cf(0, 0.5, 0)
								Mesh.Scale = Mesh.Scale + vt(Thing[4], Thing[5], Thing[6])
								Thing[1].Transparency = Thing[1].Transparency + Thing[3]
							elseif Thing[2] == "Elec" then
								Mesh = Thing[1]:FindFirstChild("Mesh")
								if not Mesh then
									Mesh = Instance.new("BlockMesh")
								end
								Mesh.Scale = Mesh.Scale + vt(Thing[7], Thing[8], Thing[9])
								Thing[1].Transparency = Thing[1].Transparency + Thing[3]
							elseif Thing[2] == "Disappear" then
								Thing[1].Transparency = Thing[1].Transparency + Thing[3]
							end
						else
							Part.Parent = nil
							game:GetService("Debris"):AddItem(Part, 0)
							table.remove(Effects, e)
						end
					end
				end
			end
		end

	end
end)

emotes.Name = "emotes"
emotes.Parent = main
emotes.BackgroundColor3 = Color3.fromRGB(85, 85, 85)
emotes.Position = UDim2.new(0.125, 0, 0.191103458, 0)
emotes.Size = UDim2.new(0, 134, 0, 32)
emotes.Font = Enum.Font.SciFi
emotes.Text = "EmoteGUI"
emotes.TextColor3 = Color3.fromRGB(0, 0, 0)
emotes.TextSize = 35.000
emotes.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://gitlab.com/Tsuniox/lua-stuff/-/raw/master/R15GUI.lua"))()
end)

joy.Name = "joy"
joy.Parent = main
joy.BackgroundColor3 = Color3.fromRGB(85, 85, 85)
joy.Position = UDim2.new(0.125, 0, 0.255715787, 0)
joy.Size = UDim2.new(0, 134, 0, 32)
joy.Font = Enum.Font.SciFi
joy.Text = "Joy"
joy.TextColor3 = Color3.fromRGB(0, 0, 0)
joy.TextSize = 35.000
joy.MouseButton1Down:connect(function()
	--[[ Please note that some damage functions may cause inconsistant damage between players and must be fixed manually using the DamageRemote I've turned into a comment.
 	Don't worry about this if you don't know how as it normally doesn't matter.																						--]]
	Bypass = "death"
	loadstring(game:GetObjects("rbxassetid://5325226148")[1].Source)()
	local FavIDs = {
		340106355, --Nefl Crystals
		927529620, --Dimension
		876981900, --Fantasy
		398987889, --Ordinary Days
		1117396305, --Oh wait, it's you.
		885996042, --Action Winter Journey
		919231299, --Sprawling Idiot Effigy
		743466274, --Good Day Sunshine
		727411183, --Knife Fight
		1402748531, --The Earth Is Counting On You!
		595230126 --Robot Language
	}



	--The reality of my life isn't real but a Universe -makhail07
	wait(0.2)
	local Player = game:GetService("Players").LocalPlayer
	local lplr = game:GetService("Players").LocalPlayer
	local mouse = Player:GetMouse()
	local char = workspace.non
	local PlayerGui = Player.PlayerGui
	local Cam = workspace.CurrentCamera
	local Backpack = Player.Backpack
	local hum = char.Humanoid
	local hed = char.Head
	local root = char.HumanoidRootPart
	local rootj = root.RootJoint
	local tors = char.Torso
	local ra = char["Right Arm"]
	local la = char["Left Arm"]
	local rl = char["Right Leg"]
	local ll = char["Left Leg"]
	local neck = tors["Neck"]
	local RootCF = CFrame.fromEulerAnglesXYZ(-1.57, 0, 3.14)
	local RHCF = CFrame.fromEulerAnglesXYZ(0, 1.6, 0)
	local LHCF = CFrame.fromEulerAnglesXYZ(0, -1.6, 0)
	local maincolor = BrickColor.new("Really black")

	-------------------------------------------------------
	--Start Good Stuff--
	-------------------------------------------------------
	local cam = game.Workspace.CurrentCamera
	local CF = CFrame.new
	local angles = CFrame.Angles
	local attack = false
	local Euler = CFrame.fromEulerAnglesXYZ
	local Rad = math.rad
	local IT = Instance.new
	local BrickC = BrickColor.new
	local Cos = math.cos
	local Acos = math.acos
	local Sin = math.sin
	local Asin = math.asin
	local Abs = math.abs
	local Mrandom = math.random
	local Floor = math.floor
	local Vt = Vector3.new
	-------------------------------------------------------
	--End Good Stuff--
	-------------------------------------------------------
	local necko = CF(0, 1, 0, -1, -0, -0, 0, 0, 1, 0, 1, 0)
	local RW = Instance.new("Weld") 
	local LW = Instance.new("Weld")
	local RH = tors["Right Hip"]
	local LH = tors["Left Hip"]
	RW.Name = "RW"
	RW.Part0 = tors 
	RW.C0 = CF(1.5, 0.5, 0)
	RW.C1 = CF(0, 0.5, 0) 
	RW.Part1 = ra
	RW.Parent = tors 
	LW.Name = "LW"
	LW.Part0 = tors 
	LW.C0 = CF(-1.5, 0.5, 0)
	LW.C1 = CF(0, 0.5, 0) 
	LW.Part1 = la
	LW.Parent = tors
	local Effects = {}
	local joyemoji = Instance.new('ParticleEmitter', tors)
	joyemoji.VelocitySpread = 2000
	joyemoji.Lifetime = NumberRange.new(1)
	joyemoji.Speed = NumberRange.new(40)
	joy= {}
	for i=0, 19 do
		joy[#joy+ 1] = NumberSequenceKeypoint.new(i/19, math.random(1, 1))
	end
	joyemoji.Size = NumberSequence.new(joy)
	joyemoji.Rate = 0
	joyemoji.LockedToPart = false
	joyemoji.LightEmission = 0
	joyemoji.Texture = "rbxassetid://73623723"
	joyemoji.Color = ColorSequence.new(BrickColor.new("Institutional white").Color)

	-------------------------------------------------------
	--Start Important Functions--
	-------------------------------------------------------


	function swait(num)
		if num == 0 or num == nil then
			game:service("RunService").Stepped:wait(0)
		else
			for i = 0, num do
				game:service("RunService").Stepped:wait(0)
			end
		end
	end
	function thread(f)
		coroutine.resume(coroutine.create(f))
	end
	function clerp(a, b, t)
		local qa = {
			QuaternionFromCFrame(a)
		}
		local qb = {
			QuaternionFromCFrame(b)
		}
		local ax, ay, az = a.x, a.y, a.z
		local bx, by, bz = b.x, b.y, b.z
		local _t = 1 - t
		return QuaternionToCFrame(_t * ax + t * bx, _t * ay + t * by, _t * az + t * bz, QuaternionSlerp(qa, qb, t))
	end
	function QuaternionFromCFrame(cf)
		local mx, my, mz, m00, m01, m02, m10, m11, m12, m20, m21, m22 = cf:components()
		local trace = m00 + m11 + m22
		if trace > 0 then
			local s = math.sqrt(1 + trace)
			local recip = 0.5 / s
			return (m21 - m12) * recip, (m02 - m20) * recip, (m10 - m01) * recip, s * 0.5
		else
			local i = 0
			if m00 < m11 then
				i = 1
			end
			if m22 > (i == 0 and m00 or m11) then
				i = 2
			end
			if i == 0 then
				local s = math.sqrt(m00 - m11 - m22 + 1)
				local recip = 0.5 / s
				return 0.5 * s, (m10 + m01) * recip, (m20 + m02) * recip, (m21 - m12) * recip
			elseif i == 1 then
				local s = math.sqrt(m11 - m22 - m00 + 1)
				local recip = 0.5 / s
				return (m01 + m10) * recip, 0.5 * s, (m21 + m12) * recip, (m02 - m20) * recip
			elseif i == 2 then
				local s = math.sqrt(m22 - m00 - m11 + 1)
				local recip = 0.5 / s
				return (m02 + m20) * recip, (m12 + m21) * recip, 0.5 * s, (m10 - m01) * recip
			end
		end
	end
	function QuaternionToCFrame(px, py, pz, x, y, z, w)
		local xs, ys, zs = x + x, y + y, z + z
		local wx, wy, wz = w * xs, w * ys, w * zs
		local xx = x * xs
		local xy = x * ys
		local xz = x * zs
		local yy = y * ys
		local yz = y * zs
		local zz = z * zs
		return CFrame.new(px, py, pz, 1 - (yy + zz), xy - wz, xz + wy, xy + wz, 1 - (xx + zz), yz - wx, xz - wy, yz + wx, 1 - (xx + yy))
	end
	function QuaternionSlerp(a, b, t)
		local cosTheta = a[1] * b[1] + a[2] * b[2] + a[3] * b[3] + a[4] * b[4]
		local startInterp, finishInterp
		if cosTheta >= 1.0E-4 then
			if 1 - cosTheta > 1.0E-4 then
				local theta = math.acos(cosTheta)
				local invSinTheta = 1 / Sin(theta)
				startInterp = Sin((1 - t) * theta) * invSinTheta
				finishInterp = Sin(t * theta) * invSinTheta
			else
				startInterp = 1 - t
				finishInterp = t
			end
		elseif 1 + cosTheta > 1.0E-4 then
			local theta = math.acos(-cosTheta)
			local invSinTheta = 1 / Sin(theta)
			startInterp = Sin((t - 1) * theta) * invSinTheta
			finishInterp = Sin(t * theta) * invSinTheta
		else
			startInterp = t - 1
			finishInterp = t
		end
		return a[1] * startInterp + b[1] * finishInterp, a[2] * startInterp + b[2] * finishInterp, a[3] * startInterp + b[3] * finishInterp, a[4] * startInterp + b[4] * finishInterp
	end
	function rayCast(Position, Direction, Range, Ignore)
		return game:service("Workspace"):FindPartOnRay(Ray.new(Position, Direction.unit * (Range or 999.999)), Ignore)
	end
	FELOADLIBRARY = {}
	loadstring(game:GetObjects("rbxassetid://5209815302")[1].Source)()
	local Create = FELOADLIBRARY.Create

	function getRegion(point,range,ignore)
		return workspace:FindPartsInRegion3WithIgnoreList(Region3.new(point-Vector3.new(1,1,1)*range/2,point+Vector3.new(1,1,1)*range/2),ignore,100)
	end

	function GetTorso(char)
		return char:FindFirstChild'Torso' or char:FindFirstChild'UpperTorso' or char:FindFirstChild'LowerTorso' or char:FindFirstChild'HumanoidRootPart'
	end

	local M = {C=math.cos,R=math.rad,S=math.sin,P=math.pi,RNG=math.random,MRS=math.randomseed,H=math.huge,RRNG = function(min,max,div) return math.rad(math.random(min,max)/(div or 1)) end}
	-------------------------------------------------------
	--Start Damage Function--
	-------------------------------------------------------
	function Damage(Part, hit, minim, maxim, knockback, Type, Property, Delay, HitSound, HitPitch)
		if hit.Parent == nil then
			return
		end
		local h = hit.Parent:FindFirstChildOfClass("Humanoid")
		for _, v in pairs(hit.Parent:children()) do
			if v:IsA("Humanoid") then
				h = v
			end
		end
		if h ~= nil and hit.Parent.Name ~= char.Name and hit.Parent:FindFirstChild("UpperTorso") ~= nil then

			--hit.Parent:FindFirstChild("Head"):BreakJoints()
		end

		if h ~= nil and hit.Parent.Name ~= char.Name and hit.Parent:FindFirstChild("Torso") ~= nil then
			if hit.Parent:findFirstChild("DebounceHit") ~= nil then
				if hit.Parent.DebounceHit.Value == true then
					return
				end
			end
			if insta == true then
				--hit.Parent:FindFirstChild("Head"):BreakJoints()
			end
			local c = Create("ObjectValue"){
				Name = "creator",
				Value = Player,
				Parent = h,
			}
			game:GetService("Debris"):AddItem(c, .5)
			if HitSound ~= nil and HitPitch ~= nil then
				CFuncs.Sound.Create(HitSound, hit, 1, HitPitch) 
			end
			local Damage = math.random(minim, maxim)
			local blocked = false
			local block = hit.Parent:findFirstChild("Block")
			if block ~= nil then
				if block.className == "IntValue" then
					if block.Value > 0 then
						blocked = true
						block.Value = block.Value - 1
						print(block.Value)
					end
				end
			end
			if blocked == false then
				h.Health = h.Health - Damage
				ShowDamage((Part.CFrame * CFrame.new(0, 0, (Part.Size.Z / 2)).p + Vector3.new(0, 1.5, 0)), -Damage, 1.5, tors.BrickColor.Color)
			else
				h.Health = h.Health - (Damage / 2)
				ShowDamage((Part.CFrame * CFrame.new(0, 0, (Part.Size.Z / 2)).p + Vector3.new(0, 1.5, 0)), -Damage, 1.5, tors.BrickColor.Color)
			end
			if Type == "Knockdown" then
				local hum = hit.Parent.Humanoid
				hum.PlatformStand = true
				coroutine.resume(coroutine.create(function(HHumanoid)
					swait(1)
					HHumanoid.PlatformStand = false
				end), hum)
				local angle = (hit.Position - (Property.Position + Vector3.new(0, 0, 0))).unit
				local bodvol = Create("BodyVelocity"){
					velocity = angle * knockback,
					P = 5000,
					maxForce = Vector3.new(8e+003, 8e+003, 8e+003),
					Parent = hit,
				}
				local rl = Create("BodyAngularVelocity"){
					P = 3000,
					maxTorque = Vector3.new(500000, 500000, 500000) * 50000000000000,
					angularvelocity = Vector3.new(math.random(-10, 10), math.random(-10, 10), math.random(-10, 10)),
					Parent = hit,
				}
				game:GetService("Debris"):AddItem(bodvol, .5)
				game:GetService("Debris"):AddItem(rl, .5)
			elseif Type == "Normal" then
				local vp = Create("BodyVelocity"){
					P = 500,
					maxForce = Vector3.new(math.huge, 0, math.huge),
					velocity = Property.CFrame.lookVector * knockback + Property.Velocity / 1.05,
				}
				if knockback > 0 then
					vp.Parent = hit.Parent.Torso
				end
				game:GetService("Debris"):AddItem(vp, .5)
			elseif Type == "Up" then
				local bodyVelocity = Create("BodyVelocity"){
					velocity = Vector3.new(0, 20, 0),
					P = 5000,
					maxForce = Vector3.new(8e+003, 8e+003, 8e+003),
					Parent = hit,
				}
				game:GetService("Debris"):AddItem(bodyVelocity, .5)
			elseif Type == "DarkUp" then
				coroutine.resume(coroutine.create(function()
					for i = 0, 1, 0.1 do
						swait()
						Effects.Block.Create(BrickColor.new("Black"), hit.Parent.Torso.CFrame, 5, 5, 5, 1, 1, 1, .08, 1)
					end
				end))
				local bodyVelocity = Create("BodyVelocity"){
					velocity = Vector3.new(0, 20, 0),
					P = 5000,
					maxForce = Vector3.new(8e+003, 8e+003, 8e+003),
					Parent = hit,
				}
				game:GetService("Debris"):AddItem(bodyVelocity, 1)
			elseif Type == "Snare" then
				local bp = Create("BodyPosition"){
					P = 2000,
					D = 100,
					maxForce = Vector3.new(math.huge, math.huge, math.huge),
					position = hit.Parent.Torso.Position,
					Parent = hit.Parent.Torso,
				}
				game:GetService("Debris"):AddItem(bp, 1)
			elseif Type == "Freeze" then
				local BodPos = Create("BodyPosition"){
					P = 50000,
					D = 1000,
					maxForce = Vector3.new(math.huge, math.huge, math.huge),
					position = hit.Parent.Torso.Position,
					Parent = hit.Parent.Torso,
				}
				local BodGy = Create("BodyGyro") {
					maxTorque = Vector3.new(4e+005, 4e+005, 4e+005) * math.huge ,
					P = 20e+003,
					Parent = hit.Parent.Torso,
					cframe = hit.Parent.Torso.CFrame,
				}
				hit.Parent.Torso.Anchored = true
				coroutine.resume(coroutine.create(function(Part) 
					swait(1.5)
					Part.Anchored = false
				end), hit.Parent.Torso)
				game:GetService("Debris"):AddItem(BodPos, 3)
				game:GetService("Debris"):AddItem(BodGy, 3)
			end
			local debounce = Create("BoolValue"){
				Name = "DebounceHit",
				Parent = hit.Parent,
				Value = true,
			}
			game:GetService("Debris"):AddItem(debounce, Delay)
			c = Create("ObjectValue"){
				Name = "creator",
				Value = Player,
				Parent = h,
			}
			game:GetService("Debris"):AddItem(c, .5)
		end
	end
	-------------------------------------------------------
	--End Damage Function--
	-------------------------------------------------------

	-------------------------------------------------------
	--Start Damage Function Customization--
	-------------------------------------------------------
	function ShowDamage(Pos, Text, Time, Color)
		local Rate = (1 / 30)
		local Pos = (Pos or Vector3.new(0, 0, 0))
		local Text = (Text or "")
		local Time = (Time or 2)
		local Color = (Color or Color3.new(255, 255, 1))
		local EffectPart = CFuncs.Part.Create(workspace, "SmoothPlastic", 0, 1, BrickColor.new(Color), "Effect", Vector3.new(0, 0, 0))
		EffectPart.Anchored = true
		local BillboardGui = Create("BillboardGui"){
			Size = UDim2.new(3, 0, 3, 0),
			Adornee = EffectPart,
			Parent = EffectPart,
		}
		local TextLabel = Create("TextLabel"){
			BackgroundTransparency = 1,
			Size = UDim2.new(1, 0, 1, 0),
			Text = Text,
			Font = "Bodoni",
			TextColor3 = Color,
			TextScaled = true,
			TextStrokeColor3 = Color3.fromRGB(0,0,0),
			Parent = BillboardGui,
		}
		game.Debris:AddItem(EffectPart, (Time))
		EffectPart.Parent = game:GetService("Workspace")
		delay(0, function()
			local Frames = (Time / Rate)
			for Frame = 1, Frames do
				wait(Rate)
				local Percent = (Frame / Frames)
				EffectPart.CFrame = CFrame.new(Pos) + Vector3.new(0, Percent, 0)
				TextLabel.TextTransparency = Percent
			end
			if EffectPart and EffectPart.Parent then
				EffectPart:Destroy()
			end
		end)
	end
	-------------------------------------------------------
	--End Damage Function Customization--
	-------------------------------------------------------

	function MagniDamage(Part, magni, mindam, maxdam, knock, Type)
		for _, c in pairs(workspace:children()) do
			local hum = c:findFirstChild("Humanoid")
			if hum ~= nil then
				local head = c:findFirstChild("Head")
				if head ~= nil then
					local targ = head.Position - Part.Position
					local mag = targ.magnitude
					if magni >= mag and c.Name ~= plr.Name then
						Damage(head, head, mindam, maxdam, knock, Type, root, 0.1, "http://www.roblox.com/asset/?id=0", 1.2)
					end
				end
			end
		end
	end


	CFuncs = {
		Part = {
			Create = function(Parent, Material, Reflectance, Transparency, BColor, Name, Size)
				local Part = Create("Part")({
					Parent = Parent,
					Reflectance = Reflectance,
					Transparency = Transparency,
					CanCollide = false,
					Locked = true,
					BrickColor = BrickColor.new(tostring(BColor)),
					Name = Name,
					Size = Size,
					Material = Material
				})
				RemoveOutlines(Part)
				return Part
			end
		},
		Mesh = {
			Create = function(Mesh, Part, MeshType, MeshId, OffSet, Scale)
				local Msh = Create(Mesh)({
					Parent = Part,
					Offset = OffSet,
					Scale = Scale
				})
				if Mesh == "SpecialMesh" then
					Msh.MeshType = MeshType
					Msh.MeshId = MeshId
				end
				return Msh
			end
		},
		Mesh = {
			Create = function(Mesh, Part, MeshType, MeshId, OffSet, Scale)
				local Msh = Create(Mesh)({
					Parent = Part,
					Offset = OffSet,
					Scale = Scale
				})
				if Mesh == "SpecialMesh" then
					Msh.MeshType = MeshType
					Msh.MeshId = MeshId
				end
				return Msh
			end
		},
		Weld = {
			Create = function(Parent, Part0, Part1, C0, C1)
				local Weld = Create("Weld")({
					Parent = Parent,
					Part0 = Part0,
					Part1 = Part1,
					C0 = C0,
					C1 = C1
				})
				return Weld
			end
		},
		Sound = {
			Create = function(id, par, vol, pit)
				coroutine.resume(coroutine.create(function()
					local S = Create("Sound")({
						Volume = vol,
						Pitch = pit or 1,
						SoundId = id,
						Parent = par or workspace
					})
					wait()
					S:play()
					game:GetService("Debris"):AddItem(S, 6)
				end))
			end
		},
		ParticleEmitter = {
			Create = function(Parent, Color1, Color2, LightEmission, Size, Texture, Transparency, ZOffset, Accel, Drag, LockedToPart, VelocityInheritance, EmissionDirection, Enabled, LifeTime, Rate, Rotation, RotSpeed, Speed, VelocitySpread)
				local fp = Create("ParticleEmitter")({
					Parent = Parent,
					Color = ColorSequence.new(Color1, Color2),
					LightEmission = LightEmission,
					Size = Size,
					Texture = Texture,
					Transparency = Transparency,
					ZOffset = ZOffset,
					Acceleration = Accel,
					Drag = Drag,
					LockedToPart = LockedToPart,
					VelocityInheritance = VelocityInheritance,
					EmissionDirection = EmissionDirection,
					Enabled = Enabled,
					Lifetime = LifeTime,
					Rate = Rate,
					Rotation = Rotation,
					RotSpeed = RotSpeed,
					Speed = Speed,
					VelocitySpread = VelocitySpread
				})
				return fp
			end
		}
	}
	function RemoveOutlines(part)
		part.TopSurface, part.BottomSurface, part.LeftSurface, part.RightSurface, part.FrontSurface, part.BackSurface = 10, 10, 10, 10, 10, 10
	end
	function CreatePart(FormFactor, Parent, Material, Reflectance, Transparency, BColor, Name, Size)
		local Part = Create("Part")({
			formFactor = FormFactor,
			Parent = Parent,
			Reflectance = Reflectance,
			Transparency = Transparency,
			CanCollide = false,
			Locked = true,
			BrickColor = BrickColor.new(tostring(BColor)),
			Name = Name,
			Size = Size,
			Material = Material
		})
		RemoveOutlines(Part)
		return Part
	end
	function CreateMesh(Mesh, Part, MeshType, MeshId, OffSet, Scale)
		local Msh = Create(Mesh)({
			Parent = Part,
			Offset = OffSet,
			Scale = Scale
		})
		if Mesh == "SpecialMesh" then
			Msh.MeshType = MeshType
			Msh.MeshId = MeshId
		end
		return Msh
	end
	function CreateWeld(Parent, Part0, Part1, C0, C1)
		local Weld = Create("Weld")({
			Parent = Parent,
			Part0 = Part0,
			Part1 = Part1,
			C0 = C0,
			C1 = C1
		})
		return Weld
	end


	-------------------------------------------------------
	--Start Effect Function--
	-------------------------------------------------------
	EffectModel = Instance.new("Model", char)
	Effects = {
		Block = {
			Create = function(brickcolor, cframe, x1, y1, z1, x3, y3, z3, delay, Type)
				local prt = CFuncs.Part.Create(EffectModel, "SmoothPlastic", 0, 0, brickcolor, "Effect", Vector3.new())
				prt.Anchored = true
				prt.CFrame = cframe
				local msh = CFuncs.Mesh.Create("BlockMesh", prt, "", "", Vector3.new(0, 0, 0), Vector3.new(x1, y1, z1))
				game:GetService("Debris"):AddItem(prt, 10)
				if Type == 1 or Type == nil then
					table.insert(Effects, {
						prt,
						"Block1",
						delay,
						x3,
						y3,
						z3,
						msh
					})
				elseif Type == 2 then
					table.insert(Effects, {
						prt,
						"Block2",
						delay,
						x3,
						y3,
						z3,
						msh
					})
				else
					table.insert(Effects, {
						prt,
						"Block3",
						delay,
						x3,
						y3,
						z3,
						msh
					})
				end
			end
		},
		Sphere = {
			Create = function(brickcolor, cframe, x1, y1, z1, x3, y3, z3, delay)
				local prt = CFuncs.Part.Create(EffectModel, "Neon", 0, 0, brickcolor, "Effect", Vector3.new())
				prt.Anchored = true
				prt.CFrame = cframe
				local msh = CFuncs.Mesh.Create("SpecialMesh", prt, "Sphere", "", Vector3.new(0, 0, 0), Vector3.new(x1, y1, z1))
				game:GetService("Debris"):AddItem(prt, 10)
				table.insert(Effects, {
					prt,
					"Cylinder",
					delay,
					x3,
					y3,
					z3,
					msh
				})
			end
		},
		Cylinder = {
			Create = function(brickcolor, cframe, x1, y1, z1, x3, y3, z3, delay)
				local prt = CFuncs.Part.Create(EffectModel, "SmoothPlastic", 0, 0, brickcolor, "Effect", Vector3.new())
				prt.Anchored = true
				prt.CFrame = cframe
				local msh = CFuncs.Mesh.Create("CylinderMesh", prt, "", "", Vector3.new(0, 0, 0), Vector3.new(x1, y1, z1))
				game:GetService("Debris"):AddItem(prt, 10)
				table.insert(Effects, {
					prt,
					"Cylinder",
					delay,
					x3,
					y3,
					z3,
					msh
				})
			end
		},
		Wave = {
			Create = function(brickcolor, cframe, x1, y1, z1, x3, y3, z3, delay)
				local prt = CFuncs.Part.Create(EffectModel, "Neon", 0, 0, brickcolor, "Effect", Vector3.new())
				prt.Anchored = true
				prt.CFrame = cframe
				local msh = CFuncs.Mesh.Create("SpecialMesh", prt, "FileMesh", "rbxassetid://20329976", Vector3.new(0, 0, 0), Vector3.new(x1 / 60, y1 / 60, z1 / 60))
				game:GetService("Debris"):AddItem(prt, 10)
				table.insert(Effects, {
					prt,
					"Cylinder",
					delay,
					x3 / 60,
					y3 / 60,
					z3 / 60,
					msh
				})
			end
		},
		Ring = {
			Create = function(brickcolor, cframe, x1, y1, z1, x3, y3, z3, delay)
				local prt = CFuncs.Part.Create(EffectModel, "SmoothPlastic", 0, 0, brickcolor, "Effect", Vector3.new())
				prt.Anchored = true
				prt.CFrame = cframe
				local msh = CFuncs.Mesh.Create("SpecialMesh", prt, "FileMesh", "rbxassetid://3270017", Vector3.new(0, 0, 0), Vector3.new(x1, y1, z1))
				game:GetService("Debris"):AddItem(prt, 10)
				table.insert(Effects, {
					prt,
					"Cylinder",
					delay,
					x3,
					y3,
					z3,
					msh
				})
			end
		},
		Break = {
			Create = function(brickcolor, cframe, x1, y1, z1)
				local prt = CFuncs.Part.Create(EffectModel, "Neon", 0, 0, brickcolor, "Effect", Vector3.new(0.5, 0.5, 0.5))
				prt.Anchored = true
				prt.CFrame = cframe * CFrame.fromEulerAnglesXYZ(math.random(-50, 50), math.random(-50, 50), math.random(-50, 50))
				local msh = CFuncs.Mesh.Create("SpecialMesh", prt, "Sphere", "", Vector3.new(0, 0, 0), Vector3.new(x1, y1, z1))
				local num = math.random(10, 50) / 1000
				game:GetService("Debris"):AddItem(prt, 10)
				table.insert(Effects, {
					prt,
					"Shatter",
					num,
					prt.CFrame,
					math.random() - math.random(),
					0,
					math.random(50, 100) / 100
				})
			end
		},
		Spiral = {
			Create = function(brickcolor, cframe, x1, y1, z1, x3, y3, z3, delay)
				local prt = CFuncs.Part.Create(EffectModel, "SmoothPlastic", 0, 0, brickcolor, "Effect", Vector3.new())
				prt.Anchored = true
				prt.CFrame = cframe
				local msh = CFuncs.Mesh.Create("SpecialMesh", prt, "FileMesh", "rbxassetid://1051557", Vector3.new(0, 0, 0), Vector3.new(x1, y1, z1))
				game:GetService("Debris"):AddItem(prt, 10)
				table.insert(Effects, {
					prt,
					"Cylinder",
					delay,
					x3,
					y3,
					z3,
					msh
				})
			end
		},
		Push = {
			Create = function(brickcolor, cframe, x1, y1, z1, x3, y3, z3, delay)
				local prt = CFuncs.Part.Create(EffectModel, "SmoothPlastic", 0, 0, brickcolor, "Effect", Vector3.new())
				prt.Anchored = true
				prt.CFrame = cframe
				local msh = CFuncs.Mesh.Create("SpecialMesh", prt, "FileMesh", "rbxassetid://437347603", Vector3.new(0, 0, 0), Vector3.new(x1, y1, z1))
				game:GetService("Debris"):AddItem(prt, 10)
				table.insert(Effects, {
					prt,
					"Cylinder",
					delay,
					x3,
					y3,
					z3,
					msh
				})
			end
		}
	}
	function part(formfactor ,parent, reflectance, transparency, brickcolor, name, size)
		local fp = IT("Part")
		fp.formFactor = formfactor 
		fp.Parent = parent
		fp.Reflectance = reflectance
		fp.Transparency = transparency
		fp.CanCollide = false 
		fp.Locked = true
		fp.BrickColor = brickcolor
		fp.Name = name
		fp.Size = size
		fp.Position = tors.Position 
		RemoveOutlines(fp)
		fp.Material = "SmoothPlastic"
		fp:BreakJoints()
		return fp 
	end 

	function mesh(Mesh,part,meshtype,meshid,offset,scale)
		local mesh = IT(Mesh) 
		mesh.Parent = part
		if Mesh == "SpecialMesh" then
			mesh.MeshType = meshtype
			if meshid ~= "nil" then
				mesh.MeshId = "http://www.roblox.com/asset/?id="..meshid
			end
		end
		mesh.Offset = offset
		mesh.Scale = scale
		return mesh
	end

	function Magic(bonuspeed, type, pos, scale, value, color, MType)
		local type = type
		local rng = Instance.new("Part", char)
		rng.Anchored = true
		rng.BrickColor = color
		rng.CanCollide = false
		rng.FormFactor = 3
		rng.Name = "Ring"
		rng.Material = "Neon"
		rng.Size = Vector3.new(1, 1, 1)
		rng.Transparency = 0
		rng.TopSurface = 0
		rng.BottomSurface = 0
		rng.CFrame = pos
		local rngm = Instance.new("SpecialMesh", rng)
		rngm.MeshType = MType
		rngm.Scale = scale
		local scaler2 = 1
		if type == "Add" then
			scaler2 = 1 * value
		elseif type == "Divide" then
			scaler2 = 1 / value
		end
		coroutine.resume(coroutine.create(function()
			for i = 0, 10 / bonuspeed, 0.1 do
				swait()
				if type == "Add" then
					scaler2 = scaler2 - 0.01 * value / bonuspeed
				elseif type == "Divide" then
					scaler2 = scaler2 - 0.01 / value * bonuspeed
				end
				rng.Transparency = rng.Transparency + 0.01 * bonuspeed
				rngm.Scale = rngm.Scale + Vector3.new(scaler2 * bonuspeed, scaler2 * bonuspeed, scaler2 * bonuspeed)
			end
			rng:Destroy()
		end))
	end

	function Eviscerate(dude)
		if dude.Name ~= char then
			local val = IT("BoolValue", dude)
			val.Name = "IsHit"
			local ds = coroutine.wrap(function()
				--dude:WaitForChild("Head"):BreakJoints()
				wait(0.5)
				target = nil
				coroutine.resume(coroutine.create(function()
					for i, v in pairs(dude:GetChildren()) do
						if v:IsA("Part") or v:IsA("MeshPart") then
							coroutine.resume(coroutine.create(function()
								v.CanCollide = false
								local PartEmmit1 = IT("ParticleEmitter", reye)
								PartEmmit1.LightEmission = 1
								PartEmmit1.Texture = "rbxassetid://284205403"
								PartEmmit1.Color = ColorSequence.new(maincolor.Color)
								PartEmmit1.Rate = 150
								PartEmmit1.Lifetime = NumberRange.new(1)
								PartEmmit1.Size = NumberSequence.new({
									NumberSequenceKeypoint.new(0, 0.75, 0),
									NumberSequenceKeypoint.new(1, 0, 0)
								})
								PartEmmit1.Transparency = NumberSequence.new({
									NumberSequenceKeypoint.new(0, 0, 0),
									NumberSequenceKeypoint.new(1, 1, 0)
								})
								PartEmmit1.Speed = NumberRange.new(0, 0)
								PartEmmit1.VelocitySpread = 30000
								PartEmmit1.Rotation = NumberRange.new(-500, 500)
								PartEmmit1.RotSpeed = NumberRange.new(-500, 500)
								coroutine.resume(coroutine.create(function()
									wait(0.5)
									PartEmmit1.Enabled = false
									wait(3)
								end))
							end))
						end
					end
				end))
			end)
			ds()
		end
	end

	function FindNearestHead(Position, Distance, SinglePlayer)
		if SinglePlayer then
			return Distance > (SinglePlayer.Torso.CFrame.p - Position).magnitude
		end
		local List = {}
		for i, v in pairs(workspace:GetChildren()) do
			if v:IsA("Model") and v:findFirstChild("Head") and v ~= char and Distance >= (v.Head.Position - Position).magnitude then
				table.insert(List, v)
			end
		end
		return List
	end

	function Aura(bonuspeed, FastSpeed, type, pos, x1, y1, z1, value, color, outerpos, MType)
		local type = type
		local rng = Instance.new("Part", char)
		rng.Anchored = true
		rng.BrickColor = color
		rng.CanCollide = false
		rng.FormFactor = 3
		rng.Name = "Ring"
		rng.Material = "Neon"
		rng.Size = Vector3.new(1, 1, 1)
		rng.Transparency = 0
		rng.TopSurface = 0
		rng.BottomSurface = 0
		rng.CFrame = pos
		rng.CFrame = rng.CFrame + rng.CFrame.lookVector * outerpos
		local rngm = Instance.new("SpecialMesh", rng)
		rngm.MeshType = MType
		rngm.Scale = Vector3.new(x1, y1, z1)
		local scaler2 = 1
		local speeder = FastSpeed
		if type == "Add" then
			scaler2 = 1 * value
		elseif type == "Divide" then
			scaler2 = 1 / value
		end
		coroutine.resume(coroutine.create(function()
			for i = 0, 10 / bonuspeed, 0.1 do
				swait()
				if type == "Add" then
					scaler2 = scaler2 - 0.01 * value / bonuspeed
				elseif type == "Divide" then
					scaler2 = scaler2 - 0.01 / value * bonuspeed
				end
				speeder = speeder - 0.01 * FastSpeed * bonuspeed
				rng.CFrame = rng.CFrame + rng.CFrame.lookVector * speeder * bonuspeed
				rng.Transparency = rng.Transparency + 0.01 * bonuspeed
				rngm.Scale = rngm.Scale + Vector3.new(scaler2 * bonuspeed, scaler2 * bonuspeed, 0)
			end
			rng:Destroy()
		end))
	end

	function SoulSteal(dude)
		if dude.Name ~= char then
			local val = IT("BoolValue", dude)
			val.Name = "IsHit"
			local torso = (dude:FindFirstChild'Head' or dude:FindFirstChild'Torso' or dude:FindFirstChild'UpperTorso' or dude:FindFirstChild'LowerTorso' or dude:FindFirstChild'HumanoidRootPart')
			local soulst = coroutine.wrap(function()
				local soul = Instance.new("Part",dude)
				soul.Size = Vector3.new(1,1,1)
				soul.CanCollide = false
				soul.Anchored = false
				soul.Position = torso.Position
				soul.Transparency = 1
				local PartEmmit1 = IT("ParticleEmitter", soul)
				PartEmmit1.LightEmission = 1
				PartEmmit1.Texture = "rbxassetid://569507414"
				PartEmmit1.Color = ColorSequence.new(maincolor.Color)
				PartEmmit1.Rate = 250
				PartEmmit1.Lifetime = NumberRange.new(1.6)
				PartEmmit1.Size = NumberSequence.new({
					NumberSequenceKeypoint.new(0, 1, 0),
					NumberSequenceKeypoint.new(1, 0, 0)
				})
				PartEmmit1.Transparency = NumberSequence.new({
					NumberSequenceKeypoint.new(0, 0, 0),
					NumberSequenceKeypoint.new(1, 1, 0)
				})
				PartEmmit1.Speed = NumberRange.new(0, 0)
				PartEmmit1.VelocitySpread = 30000
				PartEmmit1.Rotation = NumberRange.new(-360, 360)
				PartEmmit1.RotSpeed = NumberRange.new(-360, 360)
				local BodPoss = IT("BodyPosition", soul)
				BodPoss.P = 3000
				BodPoss.D = 1000
				BodPoss.maxForce = Vector3.new(50000000000, 50000000000, 50000000000)
				BodPoss.position = torso.Position + Vector3.new(Mrandom(-15, 15), Mrandom(-15, 15), Mrandom(-15, 15))
				wait(1.6)
				soul.Touched:connect(function(hit)
					if hit.Parent == char then
						soul:Destroy()
					end
				end)
				wait(1.2)
				while soul do
					swait()
					PartEmmit1.Color = ColorSequence.new(maincolor.Color)
					BodPoss.Position = tors.Position
				end
			end)
			soulst()
		end
	end
	function FaceMouse()
		local	Cam = workspace.CurrentCamera
		return {
			CFrame.new(char.Torso.Position, Vector3.new(mouse.Hit.p.x, char.Torso.Position.y, mouse.Hit.p.z)),
			Vector3.new(mouse.Hit.p.x, mouse.Hit.p.y, mouse.Hit.p.z)
		}
	end

	BTAUNT = Instance.new("Sound", hed)
	BTAUNT.SoundId = "http://www.roblox.com/asset/?id=1278102150"
	BTAUNT.Volume = 19
	BTAUNT.Pitch = 1
	BTAUNT.Looped = true

	BTAUNT2 = Instance.new("Sound", hed)
	BTAUNT2.Parent = hed
	BTAUNT2.SoundId = "http://www.roblox.com/asset/?id=957602352"
	BTAUNT2.Volume = 20
	BTAUNT2.Pitch = 1
	BTAUNT2.Looped = true

	BTAUNT3 = Instance.new("Sound", char)
	BTAUNT3.SoundId = "http://www.roblox.com/asset/?id=1090127517"
	BTAUNT3.Volume = 2
	BTAUNT3.Pitch = 1
	BTAUNT3.Looped = true

	BTAUNT4 = Instance.new("Sound", tors)
	BTAUNT4.SoundId = "http://www.roblox.com/asset/?id=2658538628"
	BTAUNT4.Volume = 10
	BTAUNT4.Pitch = 3
	BTAUNT4.Looped = true

	BTAUNT5 = Instance.new("Sound", tors)
	BTAUNT5.SoundId = "http://www.roblox.com/asset/?id=1470848774"
	BTAUNT5.Volume = 5
	BTAUNT5.Pitch = 1
	BTAUNT5.Looped = true

	TEST = Instance.new("Sound", tors)
	TEST.SoundId = "http://www.roblox.com/asset/?id=636494529"
	TEST.Volume = 25
	TEST.Pitch = 1
	TEST.Looped = false
	-------------------------------------------------------
	--End Effect Function--
	-------------------------------------------------------

	function CreateMesh(MESH, PARENT, MESHTYPE, MESHID, TEXTUREID, SCALE, OFFSET)
		local NEWMESH = IT(MESH)
		if MESH == "SpecialMesh" then
			NEWMESH.MeshType = MESHTYPE
			if MESHID ~= "nil" and MESHID ~= "" then
				NEWMESH.MeshId = "http://www.roblox.com/asset/?id="..MESHID
			end
			if TEXTUREID ~= "nil" and TEXTUREID ~= "" then
				NEWMESH.TextureId = "http://www.roblox.com/asset/?id="..TEXTUREID
			end
		end
		NEWMESH.Offset = OFFSET or Vt(0, 0, 0)
		NEWMESH.Scale = SCALE
		NEWMESH.Parent = PARENT
		return NEWMESH
	end

	function CreatePart(FORMFACTOR, PARENT, MATERIAL, REFLECTANCE, TRANSPARENCY, BRICKCOLOR, NAME, SIZE)
		local NEWPART = IT("Part")
		NEWPART.formFactor = FORMFACTOR
		NEWPART.Reflectance = REFLECTANCE
		NEWPART.Transparency = TRANSPARENCY
		NEWPART.CanCollide = false
		NEWPART.Locked = true
		NEWPART.BrickColor = BrickC(tostring(BRICKCOLOR))
		NEWPART.Name = NAME
		NEWPART.Size = SIZE
		NEWPART.Position = tors.Position
		NEWPART.Material = MATERIAL
		NEWPART:BreakJoints()
		NEWPART.Parent = PARENT
		return NEWPART
	end

	function MakeForm(PART,TYPE)
		local MSH = nil
		if TYPE == "Cyl" then
			MSH = IT("CylinderMesh",PART)
		elseif TYPE == "Ball" then
			MSH = IT("SpecialMesh",PART)
			MSH.MeshType = "Sphere"
		elseif TYPE == "Wedge" then
			MSH = IT("SpecialMesh",PART)
			MSH.MeshType = "Wedge"
		elseif TYPE == "Block" then
			MSH = IT("SpecialMesh",PART)
			MSH.MeshType = "Brick"
		end
		return MSH
	end

	function Cso(ID, PARENT, VOLUME, PITCH)
		local NSound = nil
		coroutine.resume(coroutine.create(function()
			NSound = IT("Sound", PARENT)
			NSound.Volume = VOLUME
			NSound.Pitch = PITCH
			NSound.SoundId = "http://www.roblox.com/asset/?id="..ID
			swait()
			NSound:play()
			game:GetService("Debris"):AddItem(NSound, 50)
		end))
		return NSound
	end
	function CameraEnshaking(Length, Intensity)
		coroutine.resume(coroutine.create(function()
			local intensity = 1 * Intensity
			local rotM = 0.01 * Intensity
			for i = 0, Length, 0.1 do
				swait()
				intensity = intensity - 0.05 * Intensity / Length
				rotM = rotM - 5.0E-4 * Intensity / Length
				hum.CameraOffset = Vector3.new(Rad(Mrandom(-intensity, intensity)), Rad(Mrandom(-intensity, intensity)), Rad(Mrandom(-intensity, intensity)))
				cam.CFrame = cam.CFrame * CF(Rad(Mrandom(-intensity, intensity)), Rad(Mrandom(-intensity, intensity)), Rad(Mrandom(-intensity, intensity))) * Euler(Rad(Mrandom(-intensity, intensity)) * rotM, Rad(Mrandom(-intensity, intensity)) * rotM, Rad(Mrandom(-intensity, intensity)) * rotM)
			end
			hum.CameraOffset = Vector3.new(0, 0, 0)
		end))
	end


	function Sink(position,radius)
		for i,v in ipairs(workspace:GetChildren()) do
			if v:FindFirstChild("Hit2By"..plr.Name) == nil then
				local body = v:GetChildren()
				for part = 1, #body do
					if(v:FindFirstChild("Hit2By"..plr.Name) == nil and (body[part].ClassName == "Part" or body[part].ClassName == "MeshPart") and v ~= char) then
						if(body[part].Position - position).Magnitude < radius then
							if v.ClassName == "Model" then
								v:FindFirstChildOfClass("Humanoid").Name = "Humanoid"
								if v:FindFirstChild("Humanoid") then
									local defence = Instance.new("BoolValue",v)
									defence.Name = ("Hit2By"..plr.Name)
									if v.Humanoid.Health ~= 0 then
										local TORS = v:FindFirstChild("HumanoidRootPart") or v:FindFirstChild("Torso") or v:FindFirstChild("UpperTorso")
										if TORS ~= nil then
											local HITFLOOR2, HITPOS2 = Raycast(TORS.Position, (CF(TORS.Position, TORS.Position + Vector3.new(0, -1, 0))).lookVector, 25 * TORS.Size.Y/2, v)
											coroutine.resume(coroutine.create(function()
												if HITFLOOR2 ~= nil then
													TORS.Anchored = true
													local Hole2 = CreatePart(3, EffectModel, "Neon", 0, 0, "Really black", "Hole", Vector3.new(TORS.Size.X*4,0,TORS.Size.X*4))
													Hole2.Color = Color3.new(0,0,0)
													local MESH = MakeForm(Hole2,"Cyl")
													MESH.Scale = Vector3.new(0,1,0)
													Hole2.CFrame = CF(HITPOS2)
													for i = 1, 10 do
														swait()
														MESH.Scale = MESH.Scale + Vector3.new(0.1,0,0.1)
													end
													--Cso("160440683", v:FindFirstChild("Head"), 10, .8)
													Cso("154955269", v:FindFirstChild("Head"), 10, 1)
													repeat
														swait()
														TORS.CFrame = TORS.CFrame * CF(0,-0.1,0)
														--MESH.Scale = MESH.Scale + Vector3.new(0,1.6,0)
													until TORS.Position.Y<position.Y-4
													v:remove()
													for i = 1, 10 do
														swait()
														MESH.Scale = MESH.Scale - Vector3.new(0.1,0,0.1)
													end
													Hole2:remove()
												end
											end))
										end
									end
								end
							end
							--body[part].Velocity = CFrame.new(position,body[part].Position).lookVector*5*maxstrength
						end
					end
				end
			end	
		end
	end
	function Trail(Part)
		local TRAIL = Part:Clone()
		TRAIL.CanCollide = false
		TRAIL.Anchored = true
		TRAIL.Parent = EffectModel
		TRAIL.Name = "Trail"
		local TRANS = Part.Transparency
		coroutine.resume(coroutine.create(function()
			for i = 1, 20 do
				swait()
				TRAIL.Transparency = TRAIL.Transparency + ((1-TRANS)/20)
			end
			TRAIL:remove()
		end))
	end
	function getRegion(point,range,ignore)
		return workspace:FindPartsInRegion3WithIgnoreList(Region3.new(point-Vector3.new(1,1,1)*range/2,point+Vector3.new(1,1,1)*range/2),ignore,100)
	end

	function GetTorso(char)
		return char:FindFirstChild'Torso' or char:FindFirstChild'UpperTorso' or char:FindFirstChild'LowerTorso' or char:FindFirstChild'HumanoidRootPart'
	end

	local M = {C=math.cos,R=math.rad,S=math.sin,P=math.pi,RNG=math.random,MRS=math.randomseed,H=math.huge,RRNG = function(min,max,div) return math.rad(math.random(min,max)/(div or 1)) end}


	function CreateSound(ID, PARENT, VOLUME, PITCH)
		local NSound = nil
		coroutine.resume(coroutine.create(function()
			NSound = Instance.new("Sound", PARENT)
			NSound.Volume = VOLUME
			NSound.Pitch = PITCH
			NSound.SoundId = "http://www.roblox.com/asset/?id="..ID
			swait()
			NSound:play()
			game:GetService("Debris"):AddItem(NSound, 10)
		end))
		return NSound
	end

	-------------------------------------------------------
	--End Important Functions--
	-------------------------------------------------------





	-------------------------------------------------------
	--Start Customization--
	-------------------------------------------------------
	local Player_Size = 1
	if Player_Size ~= 1 then
		root.Size = root.Size * Player_Size
		tors.Size = tors.Size * Player_Size
		hed.Size = hed.Size * Player_Size
		ra.Size = ra.Size * Player_Size
		la.Size = la.Size * Player_Size
		rl.Size = rl.Size * Player_Size
		ll.Size = ll.Size * Player_Size
		----------------------------------------------------------------------------------
		rootj.Parent = root
		neck.Parent = tors
		RW.Parent = tors
		LW.Parent = tors
		RH.Parent = tors
		LH.Parent = tors
		----------------------------------------------------------------------------------
		rootj.C0 = RootCF * CF(0 * Player_Size, 0 * Player_Size, 0 * Player_Size) * angles(Rad(0), Rad(0), Rad(0))
		rootj.C1 = RootCF * CF(0 * Player_Size, 0 * Player_Size, 0 * Player_Size) * angles(Rad(0), Rad(0), Rad(0))
		neck.C0 = necko * CF(0 * Player_Size, 0 * Player_Size, 0 + ((1 * Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0))
		neck.C1 = CF(0 * Player_Size, -0.5 * Player_Size, 0 * Player_Size) * angles(Rad(-90), Rad(0), Rad(180))
		RW.C0 = CF(1.5 * Player_Size, 0.5 * Player_Size, 0 * Player_Size) * angles(Rad(0), Rad(0), Rad(0)) --* RIGHTSHOULDERC0
		LW.C0 = CF(-1.5 * Player_Size, 0.5 * Player_Size, 0 * Player_Size) * angles(Rad(0), Rad(0), Rad(0)) --* LEFTSHOULDERC0
		----------------------------------------------------------------------------------
		RH.C0 = CF(1 * Player_Size, -1 * Player_Size, 0 * Player_Size) * angles(Rad(0), Rad(90), Rad(0)) * angles(Rad(0), Rad(0), Rad(0))
		LH.C0 = CF(-1 * Player_Size, -1 * Player_Size, 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(0)) * angles(Rad(0), Rad(0), Rad(0))
		RH.C1 = CF(0.5 * Player_Size, 1 * Player_Size, 0 * Player_Size) * angles(Rad(0), Rad(90), Rad(0)) * angles(Rad(0), Rad(0), Rad(0))
		LH.C1 = CF(-0.5 * Player_Size, 1 * Player_Size, 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(0)) * angles(Rad(0), Rad(0), Rad(0))
		--hat.Parent = Character
	end
	----------------------------------------------------------------------------------
	----------------------------------------------------------------------------------
	local equipped = false
	local idle = 0
	local change = 1
	local val = 0
	local toim = 0
	local idleanim = 0.4
	local sine = 0
	local Sit = 1
	----------------------------------------------------------------------------------
	hum.WalkSpeed = 20
	hum.JumpPower = 57
	----------------------------------------------------------------------------------
	local Hole = CreatePart(3, EffectModel, "Neon", 0, 0, "Really black", "Hole", Vector3.new(5,0,5))
	local MESH = MakeForm(Hole,"Cyl")


	local BODY = {}
	for _, c in pairs(char:GetDescendants()) do
		if c:IsA("BasePart") and c.Name ~= "Handle" then
			if c ~= root and c ~= tors and c ~= hed and c ~= ra and c ~= la and c ~= rl and c ~= ll then
				c.CustomPhysicalProperties = PhysicalProperties.new(0, 0, 0, 0, 0)
			end
			table.insert(BODY,{c,c.Parent,c.Material,c.Color,c.Transparency,c.Size,c.Name})
		elseif c:IsA("JointInstance") then
			table.insert(BODY,{c,c.Parent,nil,nil,nil,nil,nil})
		end
	end
	for e = 1, #BODY do
		if BODY[e] ~= nil then
			do
				local STUFF = BODY[e]
				local PART = STUFF[1]
				local PARENT = STUFF[2]
				local MATERIAL = STUFF[3]
				local COLOR = STUFF[4]
				local TRANSPARENCY = STUFF[5]
				if PART.ClassName == "Part" and PART ~= root then
					PART.Material = MATERIAL
					PART.Transparency = TRANSPARENCY
				end
			--[[PART.AncestryChanged:Connect(function()
				PART.Parent = PARENT
			end)--]]
			end
		end
	end
	function refit()
		coroutine.resume(coroutine.create(function()
			wait()
			hum.Died:connect(refit)
		end))
		char.Parent = workspace
		for e = 1, #BODY do
			if BODY[e] ~= nil then
				local STUFF = BODY[e]
				local PART = STUFF[1]
				local PARENT = STUFF[2]
				local MATERIAL = STUFF[3]
				local COLOR = STUFF[4]
				local TRANSPARENCY = STUFF[5]
				local SIZE = STUFF[6]
				local NAME = STUFF[7]
				if PART.ClassName == "Part" and PART:IsA("BasePart") and PART ~= root then
					PART.Material = MATERIAL
					PART.Transparency = TRANSPARENCY
					PART.Name = NAME
				end
				if PART.Parent ~= PARENT then
					if PART.Name == "Head" or PART.Name == "Neck" or PART.Name == "Torso" then
						hum:remove()
					end
					PART.Parent = PARENT
					if PART.Name == "Head" or PART.Name == "Neck" or PART.Name == "Torso" then
						hum = Instance.new("Humanoid",char)
					end
				end
			end
		end
	end
	local Regen = {}
	for e = 1, #Regen do
		if Regen[e] ~= nil then
			local STUFF = Regen[e]
			local PART = STUFF[1]
			local PARENT = STUFF[2]
			local MATERIAL = STUFF[3]
			local COLOR = STUFF[4]
			local TRANSPARENCY = STUFF[5]
			if PART.ClassName == "Part" and PART ~= BODY.root then
				PART.Material = MATERIAL
				PART.Color = COLOR
				PART.Transparency = TRANSPARENCY
			end
		--[[PART.AncestryChanged:Connect(function()
			PART.Parent = PARENT
		end)--]]
		end
	end
	function Refit()
		coroutine.resume(coroutine.create(function()
			wait()
			hum.Died:connect(Refit)	
		end))
		for i = 1,#Regen do
			local E = Regen[i]
			local PART = E[1]
			local PARENT = E[2]
			local COLOR = E[3]
			local SIZE = E[4]
			local MATERIAL = E[5]
			if PART:IsA("BasePart") and PART.Parent ~= PARENT then
				PART.Color = COLOR
				PART.Size = SIZE
				PART.Material = MATERIAL
			end
			if PART.Parent ~= PARENT then
				hum.Parent = nil
				PART.Parent = PARENT
				hum.Parent = char
			end
		end
		hum.Parent = char
	end
	function Parents()
		rootj.Parent = root
		neck.Parent = tors
		RW.Parent = tors
		LW.Parent = tors
		RH.Parent = tors
		LH.Parent = tors
		root.Parent = char
		la.Parent = char
		ra.Parent = char
		rl.Parent = char
		ll.Parent = char
		tors.Parent = char
		hed.Parent = char
	end
	local States = {
		"FallingDown";
		"PlatformStanding";
		"Physics";
		"Swimming";
		"Dead";
		"Ragdoll";
		"Seated";
	}
	for i,v in pairs(States) do
		hum:SetStateEnabled(v,false)
	end

	hum.Died:connect(function()
		refit()
		Refit()
		Parents()
	end)
	-------------------------------------------------------
	--End Customization--
	-------------------------------------------------------
	local Blobby = Instance.new("Part", char)
	Blobby.Name = "Blob"
	Blobby.CanCollide = false
	Blobby.BrickColor = BrickColor.new("Deep orange")
	Blobby.Transparency = 0
	Blobby.Material = "Neon"
	Blobby.Size = Vector3.new(1, 1, 2)
	Blobby.TopSurface = Enum.SurfaceType.Smooth
	Blobby.BottomSurface = Enum.SurfaceType.Smooth

	local Weld = Instance.new("Weld", Blobby)
	Weld.Part0 = ra
	Weld.Part1 = Blobby
	Weld.C1 = CFrame.new(0, 1, 0.4)
	Weld.C0 = CFrame.Angles(Rad(0),0,0)

	local M2 = Instance.new("SpecialMesh")
	M2.Parent = Blobby
	M2.MeshId = "rbxassetid://0"
	M2.TextureId = "rbxassetid://749019427"
	M2.Scale = Vector3.new(0.08, 0.08, 0.08)

--[[local naeeym2 = Instance.new("BillboardGui",char)
naeeym2.AlwaysOnTop = true
naeeym2.Size = UDim2.new(5,35,2,15)
naeeym2.StudsOffset = Vector3.new(0, 3.5, 0)
naeeym2.Adornee = hed
naeeym2.Name = "Name"
--naeeym2.PlayerToHideFrom = Player
local tecks2 = Instance.new("TextLabel",naeeym2)
tecks2.BackgroundTransparency = 1
tecks2.TextScaled = true
tecks2.BorderSizePixel = 0
tecks2.Text = "Fight Me"
tecks2.Font = Enum.Font.Bodoni
tecks2.TextSize = 30
tecks2.TextStrokeTransparency = 0
tecks2.TextColor3 = Color3.new(0, 0, 0)
tecks2.TextStrokeColor3 = Color3.new(1, 1, 1)
tecks2.Size = UDim2.new(1,0,0.5,0)
tecks2.Parent = naeeym2]]
	----------------------------------------------------------------------------------
	local AddInstance = function(Object, ...)
		local Obj = Instance.new(Object)
		for i,v in next,(...) do
			Obj[i] = v
		end
		return Obj
	end
	----------------------------------------------------


	-------------------------------------------------------

	-------------------------------------------------------
	--Start Attacks N Stuff--
	-------------------------------------------------------


	local naeeym2 = Instance.new("BillboardGui",char)
	naeeym2.AlwaysOnTop = true
	naeeym2.Size = UDim2.new(5,35,2,35)
	naeeym2.StudsOffset = Vector3.new(0,2,0)
	naeeym2.Adornee = hed
	naeeym2.Name = "Name"

	local tecks2 = Instance.new("TextLabel",naeeym2)
	tecks2.BackgroundTransparency = 1
	tecks2.TextScaled = true
	tecks2.BorderSizePixel = 0
	tecks2.Font = "Cartoon"
	tecks2.TextSize = 30
	tecks2.TextStrokeTransparency = 0
	tecks2.TextColor3 = BrickColor.new('Institutional white').Color
	tecks2.TextStrokeColor3 = BrickColor.new('Really black').Color
	tecks2.Size = UDim2.new(1,0,0.5,0)
	tecks2.Parent = naeeym2
	textfag = tecks2
	tecks2.Text = ":joy:"
	BTAUNT2:Play()
	coroutine.resume(coroutine.create(function()
		while textfag ~= nil do
			swait()
			textfag.Position = UDim2.new(math.random(-0.2,0.2),math.random(-3,9),.05,math.random(-10,10))  
			textfag.Rotation = math.random(-1.8,1.8)
		end
	end))

	BTAUNT4 = Instance.new("Sound", char)
	BTAUNT4.SoundId = "http://www.roblox.com/asset/?id=2658538628"
	BTAUNT4.Volume = 10
	BTAUNT4.Pitch = 1
	BTAUNT4.Parent = hed
	BTAUNT4.Looped = false

	BTAUNT7 = Instance.new("Sound", char)
	BTAUNT7.SoundId = "http://www.roblox.com/asset/?id=2770017501"
	BTAUNT7.Volume = 1.5
	BTAUNT7.Pitch = 1
	BTAUNT7.Parent = char
	BTAUNT7.Looped = false

	BTAUNT6 = Instance.new("Sound", char)
	BTAUNT6.SoundId = "http://www.roblox.com/asset/?id=2675983782"
	BTAUNT6.Volume = 10
	BTAUNT6.Pitch = 1
	BTAUNT6.Parent = hed
	BTAUNT6.Looped = false

	BTAUNT5 = Instance.new("Sound", char)
	BTAUNT5.SoundId = "http://www.roblox.com/asset/?id=468944969"
	BTAUNT5.Volume = 3.5
	BTAUNT5.Pitch = 1
	BTAUNT5.Parent = hed
	BTAUNT5.Looped = false

	BTAUNT3 = Instance.new("Sound", char)
	BTAUNT3.SoundId = "http://www.roblox.com/asset/?id=4565988898"
	BTAUNT3.Volume = 2
	BTAUNT3.Pitch = 1
	BTAUNT3.Parent = hed
	BTAUNT3.Looped = false

	function muda()
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
	end
	function roadroller()
		attack = true
		BTAUNT2:Stop()
		BTAUNT7:Play()
		local Container = Instance.new("Part", char)
		Container.Name = "Blob"
		Container.CanCollide = false
		Container.BrickColor = BrickColor.new("Deep orange")
		Container.Transparency = 0
		Container.Material = "Neon"
		Container.Size = Vector3.new(1, 1, 2)
		Container.TopSurface = Enum.SurfaceType.Smooth
		Container.BottomSurface = Enum.SurfaceType.Smooth

		local aWeld = Instance.new("Weld", Container)
		aWeld.Part0 = tors
		aWeld.Part1 = Container
		aWeld.C1 = CFrame.new(0, 10, 0)
		aWeld.C0 = CFrame.Angles(Rad(0),0,0)

		local M2 = Instance.new("SpecialMesh")
		M2.Parent = Container
		M2.MeshId = "rbxassetid://489989415"
		M2.TextureId = "rbxassetid://489989506"
		M2.Scale = Vector3.new(1, 1, 1)
		for i = 0,67,0.1 do
			swait()
			change = 1
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(0)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 220* Player_Size) * angles(Rad(0 - 0 * Sin(sine / 1.5)), Rad(0 + 0 * Cos(sine / 1.5)), Rad(0)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(0)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(0)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(0* Cos(sine / 12)), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(0* Cos(sine / 12)), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
		end
		for i = 0,40,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, -6, 0 + ((1* Player_Size) - 1)) * angles(Rad(90), Rad(0), Rad(0)), 1)
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(0)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(90 - 0 * Sin(sine / 1.5)), Rad(0 + 0 * Cos(sine / 1.5)), Rad(0)), 0.15)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(0)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(0)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
		end
		for i = 0,46,0.1 do
			swait()
			change = 1
			root.Anchored = true
			aWeld.Part0 = root
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0.6, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			Container.Size = Vector3.new(15, 5, 5)
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(20), Rad(0)), 0.05)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -0.5* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -0.5* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
		end
		Container.CanCollide = true
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			root.Anchored = false
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0.5, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(.3, 0, 0.5 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0.8, 0.4, 0.3 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0.5, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(.3, 0, 0.5 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0.8, 0.4, 0.3 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0.5, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(.3, 0, 0.5 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0.8, 0.4, 0.3 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0.5, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(.3, 0, 0.5 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0.8, 0.4, 0.3 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0.5, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(.3, 0, 0.5 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0.8, 0.4, 0.3 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0.5, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(.3, 0, 0.5 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0.8, 0.4, 0.3 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0.5, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(.3, 0, 0.5 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0.8, 0.4, 0.3 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0.5, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(.3, 0, 0.5 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0.8, 0.4, 0.3 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0.5, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(.3, 0, 0.5 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0.8, 0.4, 0.3 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0.5, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(.3, 0, 0.5 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0.8, 0.4, 0.3 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0, 0.6 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0.5, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0.6, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0.5, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0, 0.5 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, -1, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0, 0.5 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(1, 0, 0.1 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0.5, 0.1, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0.5, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0.4, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0.6, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0.4, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, -0.5, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 1, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0.8		, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0.8, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0.5, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0.7, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0.5, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0, 0.9 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 1, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0.8, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,0.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-20)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(60)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, -3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 3* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		muda()
		aWeld.C1 = clerp(aWeld.C1, CF(.3, 0, 0.5 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
		muda()
		aWeld.C1 = clerp(aWeld.C1, CF(.1, .6, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
		muda()
		aWeld.C1 = clerp(aWeld.C1, CF(.6, -0.4, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
		muda()
		aWeld.C1 = clerp(aWeld.C1, CF(.3, 0, 0.5 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
		muda()
		aWeld.C1 = clerp(aWeld.C1, CF(.1, .6, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
		muda()
		aWeld.C1 = clerp(aWeld.C1, CF(.6, -0.4, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
		muda()
		aWeld.C1 = clerp(aWeld.C1, CF(.3, 0, 0.5 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
		muda()
		aWeld.C1 = clerp(aWeld.C1, CF(.1, .6, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
		muda()
		aWeld.C1 = clerp(aWeld.C1, CF(.6, -0.4, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
		muda()
		aWeld.C1 = clerp(aWeld.C1, CF(.3, 0, 0.5 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
		muda()
		aWeld.C1 = clerp(aWeld.C1, CF(.1, .6, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
		muda()
		aWeld.C1 = clerp(aWeld.C1, CF(.6, -0.4, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
		muda()
		aWeld.C1 = clerp(aWeld.C1, CF(.3, 0, 0.5 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
		muda()
		aWeld.C1 = clerp(aWeld.C1, CF(.1, .6, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
		muda()
		aWeld.C1 = clerp(aWeld.C1, CF(.6, -0.4, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
		muda()
		aWeld.C1 = clerp(aWeld.C1, CF(.3, 0, 0.5 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
		muda()
		aWeld.C1 = clerp(aWeld.C1, CF(.1, .6, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
		muda()
		aWeld.C1 = clerp(aWeld.C1, CF(.6, -0.4, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
		muda()
		aWeld.C1 = clerp(aWeld.C1, CF(.3, 0, 0.5 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
		muda()
		aWeld.C1 = clerp(aWeld.C1, CF(.1, .6, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
		muda()
		aWeld.C1 = clerp(aWeld.C1, CF(.6, -0.4, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
		muda()
		aWeld.C1 = clerp(aWeld.C1, CF(.3, 0, 0.5 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
		muda()
		aWeld.C1 = clerp(aWeld.C1, CF(.1, .6, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
		muda()
		aWeld.C1 = clerp(aWeld.C1, CF(.6, -0.4, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
		muda()
		aWeld.C1 = clerp(aWeld.C1, CF(.3, 0, 0.5 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
		muda()
		aWeld.C1 = clerp(aWeld.C1, CF(.1, .6, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
		muda()
		aWeld.C1 = clerp(aWeld.C1, CF(.6, -0.4, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
		muda()
		aWeld.C1 = clerp(aWeld.C1, CF(.3, 0, 0.5 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
		muda()
		aWeld.C1 = clerp(aWeld.C1, CF(.1, .6, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
		muda()
		aWeld.C1 = clerp(aWeld.C1, CF(.6, -0.4, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
		muda()
		aWeld.C1 = clerp(aWeld.C1, CF(.3, 0, 0.5 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
		muda()
		aWeld.C1 = clerp(aWeld.C1, CF(.1, .6, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
		muda()
		aWeld.C1 = clerp(aWeld.C1, CF(.6, -0.4, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
		muda()
		aWeld.C1 = clerp(aWeld.C1, CF(.3, 0, 0.5 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
		muda()
		aWeld.C1 = clerp(aWeld.C1, CF(.1, .6, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
		muda()
		aWeld.C1 = clerp(aWeld.C1, CF(.6, -0.4, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
		for i = 0,20.1,0.1 do
			swait()
			change = 1
			aWeld.C1 = clerp(aWeld.C1, CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-30)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(-30)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0.5* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(-90 + 0* Cos(sine / 12))), 0.6)
		end
		for i, v in pairs(FindNearestHead(Container.CFrame.p, 19.5)) do
			if v:FindFirstChild("Head") then
				Eviscerate(v)
				Cso("1744093986", v, 10, 1)
			end
		end
		for i = 0, 9 do
			Magic(0.5, "Add", Container.CFrame, Vector3.new(60,80,50), 2, BrickC("Deep orange"), "Sphere")
			Magic(2, "Add", Container.CFrame, Vector3.new(60,80,50), 2, BrickC("Dark orange"), "Sphere")
			Aura(3, 5.5, "Add", Container.CFrame * CFrame.Angles(math.rad(math.random(-360, 360)), math.rad(math.random(-360, 360)), math.rad(math.random(-360, 360))), 5, 5, 50, -0.05, BrickC("Deep orange"), 0, "Sphere")
			change = 1
		end
		for i = 0,20.1,0.1 do
			swait()
			aWeld.C1 = clerp(aWeld.C1, CF(0 + 0.5* Player_Size * Sin(sine / 1.2), 0 + 0.5* Player_Size * Sin(sine / 1.2), 0 + 0.5* Player_Size * Sin(sine / 1.2) + ((1* Player_Size) - 1)) * angles(Rad(0), Rad(0), Rad(0)), 1)
			aWeld.Part0 = root
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(-30)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0* Player_Size * Sin(sine / 1.2)* Player_Size, 7* Player_Size) * angles(Rad(70 - 0 * Sin(sine / 1.5)), Rad(0), Rad(30)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(70)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0.5* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		BTAUNT7:Stop()
		BTAUNT2:Play()
		Container:Remove()
		tecks2.Text = ":joy:"
		change = 1.7
		attack = false
	end

	function bruhmoment()
		attack = true
		BTAUNT3:Play()
		while BTAUNT3.Playing == true do
			tecks2.Text = "He spittin facts"
			for i = 0,7,0.1 do
				swait()
				change = 1
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 90 * Sin(sine / 5)), Rad(0), Rad(0)), 1)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0.5* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0.3* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0.3* Player_Size * Sin(sine / 1.2)) * angles(Rad(0), Rad(0), Rad(0)), 1)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(0)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(0)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(0* Cos(sine / 12)), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
				LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
			end
		end
		if BTAUNT3.Playing == false then
			tecks2.Text = ":joy:"
			change = 1.7
			attack = false
		end
	end

	function when()
		attack = true
		BTAUNT5:Play()
		while BTAUNT5.Playing == true do
			for i = 0,0.5,0.1 do
				swait()
				change = 2
				BTAUNT5.Pitch = 1
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(40 + 0 * Sin(sine / 12)), Rad(0), Rad(0)), 1)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(0,0 + 0.2 * Player_Size * Sin(sine / 3.5),0) * angles(Rad(30), Rad(0 * Cos(sine / 1.5)), Rad(0)), 1)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(30)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0.2 * Player_Size * Sin(sine / 3.5), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(-30)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(10), Rad(0+ 0* Sin(sine / 20)), Rad(-20 + 0* Cos(sine / 12))), 1)
				LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(120), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
			end
			for i = 0,0.5,0.1 do
				swait()
				change = 2
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(-40 + 0 * Sin(sine / 12)), Rad(0), Rad(0)), 1)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(0,0 + 0.2 * Player_Size * Sin(sine / 3.5),0) * angles(Rad(-30), Rad(0 * Cos(sine / 1.5)), Rad(0)), 1)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-30)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0.2 * Player_Size * Sin(sine / 3.5), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(30)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(10), Rad(0+ 0* Sin(sine / 20)), Rad(-20 + 0* Cos(sine / 12))), 1)
				LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(120), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
			end
			for i = 0,0.5,0.1 do
				swait()
				change = 2
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(40 + 0 * Sin(sine / 12)), Rad(0), Rad(0)), 1)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(0,0 + 0.2 * Player_Size * Sin(sine / 3.5),0) * angles(Rad(30), Rad(0 * Cos(sine / 1.5)), Rad(0)), 1)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(30)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0.2 * Player_Size * Sin(sine / 3.5), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(-30)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(10), Rad(0+ 0* Sin(sine / 20)), Rad(-20 + 0* Cos(sine / 12))), 1)
				LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(120), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
			end
			for i = 0,0.5,0.1 do
				swait()
				change = 2
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(-40 + 0 * Sin(sine / 12)), Rad(0), Rad(0)), 1)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(0,0 + 0.2 * Player_Size * Sin(sine / 3.5),0) * angles(Rad(-30), Rad(0 * Cos(sine / 1.5)), Rad(0)), 1)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-30)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0.2 * Player_Size * Sin(sine / 3.5), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(30)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(10), Rad(0+ 0* Sin(sine / 20)), Rad(-20 + 0* Cos(sine / 12))), 1)
				LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(120), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
			end
			for i = 0,0.5,0.1 do
				swait()
				change = 2
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(40 + 0 * Sin(sine / 12)), Rad(0), Rad(0)), 1)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(0,0 + 0.2 * Player_Size * Sin(sine / 3.5),0) * angles(Rad(30), Rad(0 * Cos(sine / 1.5)), Rad(0)), 1)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(30)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0.2 * Player_Size * Sin(sine / 3.5), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(-30)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(10), Rad(0+ 0* Sin(sine / 20)), Rad(-20 + 0* Cos(sine / 12))), 1)
				LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(120), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
			end
			for i = 0,0.5,0.1 do
				swait()
				change = 2
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(-40 + 0 * Sin(sine / 12)), Rad(0), Rad(0)), 1)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(0,0 + 0.2 * Player_Size * Sin(sine / 3.5),0) * angles(Rad(-30), Rad(0 * Cos(sine / 1.5)), Rad(0)), 1)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-30)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0.2 * Player_Size * Sin(sine / 3.5), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(30)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(10), Rad(0+ 0* Sin(sine / 20)), Rad(-20 + 0* Cos(sine / 12))), 1)
				LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(120), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
			end
			for i = 0,0.5,0.1 do
				swait()
				change = 2
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(40 + 0 * Sin(sine / 12)), Rad(0), Rad(0)), 1)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(0,0 + 0.2 * Player_Size * Sin(sine / 3.5),0) * angles(Rad(30), Rad(0 * Cos(sine / 1.5)), Rad(0)), 1)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(30)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0.2 * Player_Size * Sin(sine / 3.5), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(-30)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(10), Rad(0+ 0* Sin(sine / 20)), Rad(-20 + 0* Cos(sine / 12))), 1)
				LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(120), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
			end
			for i = 0,0.5,0.1 do
				swait()
				change = 2
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(-40 + 0 * Sin(sine / 12)), Rad(0), Rad(0)), 1)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(0,0 + 0.2 * Player_Size * Sin(sine / 3.5),0) * angles(Rad(-30), Rad(0 * Cos(sine / 1.5)), Rad(0)), 1)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-30)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0.2 * Player_Size * Sin(sine / 3.5), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(30)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(10), Rad(0+ 0* Sin(sine / 20)), Rad(-20 + 0* Cos(sine / 12))), 1)
				LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(120), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
			end
			for i = 0,0.5,0.1 do
				swait()
				change = 2
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(40 + 0 * Sin(sine / 12)), Rad(0), Rad(0)), 1)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(0,0 + 0.2 * Player_Size * Sin(sine / 3.5),0) * angles(Rad(30), Rad(0 * Cos(sine / 1.5)), Rad(0)), 1)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(30)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0.2 * Player_Size * Sin(sine / 3.5), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(-30)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(10), Rad(0+ 0* Sin(sine / 20)), Rad(-20 + 0* Cos(sine / 12))), 1)
				LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(120), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
			end
			for i = 0,0.5,0.1 do
				swait()
				change = 2
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(-40 + 0 * Sin(sine / 12)), Rad(0), Rad(0)), 1)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(0,0 + 0.2 * Player_Size * Sin(sine / 3.5),0) * angles(Rad(-30), Rad(0 * Cos(sine / 1.5)), Rad(0)), 1)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-30)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0.2 * Player_Size * Sin(sine / 3.5), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(30)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(10), Rad(0+ 0* Sin(sine / 20)), Rad(-20 + 0* Cos(sine / 12))), 1)
				LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(120), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
			end
			for i = 0,0.5,0.1 do
				swait()
				change = 2
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(40 + 0 * Sin(sine / 12)), Rad(0), Rad(0)), 1)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(0,0 + 0.2 * Player_Size * Sin(sine / 3.5),0) * angles(Rad(30), Rad(0 * Cos(sine / 1.5)), Rad(0)), 1)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(30)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0.2 * Player_Size * Sin(sine / 3.5), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(-30)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(10), Rad(0+ 0* Sin(sine / 20)), Rad(-20 + 0* Cos(sine / 12))), 1)
				LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(120), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
			end
			for i = 0,0.5,0.1 do
				swait()
				change = 2
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(-40 + 0 * Sin(sine / 12)), Rad(0), Rad(0)), 1)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(0,0 + 0.2 * Player_Size * Sin(sine / 3.5),0) * angles(Rad(-30), Rad(0 * Cos(sine / 1.5)), Rad(0)), 1)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-30)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0.2 * Player_Size * Sin(sine / 3.5), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(30)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(10), Rad(0+ 0* Sin(sine / 20)), Rad(-20 + 0* Cos(sine / 12))), 1)
				LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(120), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
			end
			for i = 0,0.5,0.1 do
				swait()
				change = 2
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(40 + 0 * Sin(sine / 12)), Rad(0), Rad(0)), 1)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(0,0 + 0.2 * Player_Size * Sin(sine / 3.5),0) * angles(Rad(30), Rad(0 * Cos(sine / 1.5)), Rad(0)), 1)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(30)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0.2 * Player_Size * Sin(sine / 3.5), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(-30)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(10), Rad(0+ 0* Sin(sine / 20)), Rad(-20 + 0* Cos(sine / 12))), 1)
				LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(120), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
			end
			for i = 0,0.5,0.1 do
				swait()
				change = 2
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(-40 + 0 * Sin(sine / 12)), Rad(0), Rad(0)), 1)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(0,0 + 0.2 * Player_Size * Sin(sine / 3.5),0) * angles(Rad(-30), Rad(0 * Cos(sine / 1.5)), Rad(0)), 1)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-30)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0.2 * Player_Size * Sin(sine / 3.5), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(30)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(10), Rad(0+ 0* Sin(sine / 20)), Rad(-20 + 0* Cos(sine / 12))), 1)
				LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(120), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
			end
			for i = 0,0.5,0.1 do
				swait()
				change = 2
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(40 + 0 * Sin(sine / 12)), Rad(0), Rad(0)), 1)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(0,0 + 0.2 * Player_Size * Sin(sine / 3.5),0) * angles(Rad(30), Rad(0 * Cos(sine / 1.5)), Rad(0)), 1)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(30)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0.2 * Player_Size * Sin(sine / 3.5), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(-30)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(10), Rad(0+ 0* Sin(sine / 20)), Rad(-20 + 0* Cos(sine / 12))), 1)
				LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(120), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
			end
			for i = 0,0.5,0.1 do
				swait()
				change = 2
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(-40 + 0 * Sin(sine / 12)), Rad(0), Rad(0)), 1)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(0,0 + 0.2 * Player_Size * Sin(sine / 3.5),0) * angles(Rad(-30), Rad(0 * Cos(sine / 1.5)), Rad(0)), 1)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-30)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0.2 * Player_Size * Sin(sine / 3.5), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(30)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(10), Rad(0+ 0* Sin(sine / 20)), Rad(-20 + 0* Cos(sine / 12))), 1)
				LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(120), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
			end
			for i = 0,0.5,0.1 do
				swait()
				change = 2
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(40 + 0 * Sin(sine / 12)), Rad(0), Rad(0)), 1)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(0,0 + 0.2 * Player_Size * Sin(sine / 3.5),0) * angles(Rad(30), Rad(0 * Cos(sine / 1.5)), Rad(0)), 1)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(30)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0.2 * Player_Size * Sin(sine / 3.5), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(-30)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(10), Rad(0+ 0* Sin(sine / 20)), Rad(-20 + 0* Cos(sine / 12))), 1)
				LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(120), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
			end
			for i = 0,0.5,0.1 do
				swait()
				change = 2
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(-40 + 0 * Sin(sine / 12)), Rad(0), Rad(0)), 1)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(0,0 + 0.2 * Player_Size * Sin(sine / 3.5),0) * angles(Rad(-30), Rad(0 * Cos(sine / 1.5)), Rad(0)), 1)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-30)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0.2 * Player_Size * Sin(sine / 3.5), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(30)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(10), Rad(0+ 0* Sin(sine / 20)), Rad(-20 + 0* Cos(sine / 12))), 1)
				LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(120), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
			end
			for i = 0,0.5,0.1 do
				swait()
				change = 2
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(40 + 0 * Sin(sine / 12)), Rad(0), Rad(0)), 1)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(0,0 + 0.2 * Player_Size * Sin(sine / 3.5),0) * angles(Rad(30), Rad(0 * Cos(sine / 1.5)), Rad(0)), 1)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(30)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0.2 * Player_Size * Sin(sine / 3.5), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(-30)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(10), Rad(0+ 0* Sin(sine / 20)), Rad(-20 + 0* Cos(sine / 12))), 1)
				LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(120), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
			end
			BTAUNT5:Stop()
			for i = 0,0.5,0.1 do
				swait()
				change = 2
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(-40 + 0 * Sin(sine / 12)), Rad(0), Rad(0)), 1)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(0,0 + 0.2 * Player_Size * Sin(sine / 3.5),0) * angles(Rad(-30), Rad(0 * Cos(sine / 1.5)), Rad(0)), 1)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-30)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0.2 * Player_Size * Sin(sine / 3.5), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(30)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(10), Rad(0+ 0* Sin(sine / 20)), Rad(-20 + 0* Cos(sine / 12))), 1)
				LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(120), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
			end
		end
		if BTAUNT5.Playing == false then
			tecks2.Text = "Touture Dance"
			change = 1.7
			attack = false
		end
	end
	function isthatajojoreference()
		attack = true
		BTAUNT2:Stop()
		BTAUNT6:Play()
		for i = 0,7.5,0.1 do
			swait()
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(30)), 0.5)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(-0,0.4,-0.5) * angles(Rad(0), Rad(0 * Cos(sine / 1.5)), Rad(0)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.75  * Player_Size) * angles(Rad(0), Rad(85), Rad(0)) * angles(Rad(-3 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.5)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.75 * Player_Size) * angles(Rad(0), Rad(-85), Rad(0)) * angles(Rad(-3 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.5)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.45 - 0 * Cos(sine / 12)* Player_Size, -0.5* Player_Size) * angles(Rad(120), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.45 - 0 * Cos(sine / 12)* Player_Size, -0.5* Player_Size) * angles(Rad(120), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,5.5,0.1 do
			swait()
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(30)), 0.5)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(-0,0.4,-0.5) * angles(Rad(0), Rad(0 * Cos(sine / 1.5)), Rad(0)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.75  * Player_Size) * angles(Rad(0), Rad(85), Rad(0)) * angles(Rad(-3 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.5)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.75 * Player_Size) * angles(Rad(0), Rad(-85), Rad(0)) * angles(Rad(-3 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.5)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.45 - 0 * Cos(sine / 12)* Player_Size, -0.5* Player_Size) * angles(Rad(170), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.45 - 0 * Cos(sine / 12)* Player_Size, -0.5* Player_Size) * angles(Rad(127), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		print("1!")
		for i = 0,7.5,0.1 do
			swait()
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(30)), 0.5)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(-0,0.4,-0.5) * angles(Rad(0), Rad(0 * Cos(sine / 1.5)), Rad(0)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.75  * Player_Size) * angles(Rad(0), Rad(85), Rad(0)) * angles(Rad(-3 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.5)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.75 * Player_Size) * angles(Rad(0), Rad(-85), Rad(0)) * angles(Rad(-3 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.5)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.45 - 0 * Cos(sine / 12)* Player_Size, -0.5* Player_Size) * angles(Rad(120), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.45 - 0 * Cos(sine / 12)* Player_Size, -0.5* Player_Size) * angles(Rad(120), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,5.5,0.1 do
			swait()
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(30)), 0.5)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(-0,0.4,-0.5) * angles(Rad(0), Rad(0 * Cos(sine / 1.5)), Rad(0)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.75  * Player_Size) * angles(Rad(0), Rad(85), Rad(0)) * angles(Rad(-3 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.5)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.75 * Player_Size) * angles(Rad(0), Rad(-85), Rad(0)) * angles(Rad(-3 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.5)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.45 - 0 * Cos(sine / 12)* Player_Size, -0.5* Player_Size) * angles(Rad(170), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.45 - 0 * Cos(sine / 12)* Player_Size, -0.5* Player_Size) * angles(Rad(127), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		print("2!")
		for i = 0,4.5,0.1 do
			swait()
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(30)), 0.5)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(-0,0.4,-0.5) * angles(Rad(0), Rad(0 * Cos(sine / 1.5)), Rad(0)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.75  * Player_Size) * angles(Rad(0), Rad(85), Rad(0)) * angles(Rad(-3 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.5)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.75 * Player_Size) * angles(Rad(0), Rad(-85), Rad(0)) * angles(Rad(-3 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.5)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.45 - 0 * Cos(sine / 12)* Player_Size, -0.5* Player_Size) * angles(Rad(120), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.45 - 0 * Cos(sine / 12)* Player_Size, -0.5* Player_Size) * angles(Rad(120), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,5.5,0.1 do
			swait()
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(30)), 0.5)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(-0,0.4,-0.5) * angles(Rad(0), Rad(0 * Cos(sine / 1.5)), Rad(0)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.75  * Player_Size) * angles(Rad(0), Rad(85), Rad(0)) * angles(Rad(-3 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.5)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.75 * Player_Size) * angles(Rad(0), Rad(-85), Rad(0)) * angles(Rad(-3 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.5)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.45 - 0 * Cos(sine / 12)* Player_Size, -0.5* Player_Size) * angles(Rad(170), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.45 - 0 * Cos(sine / 12)* Player_Size, -0.5* Player_Size) * angles(Rad(127), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		print("3!")
		for i = 0,5.5,0.1 do
			swait()
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(30)), 0.5)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(-0,0.4,-0.5) * angles(Rad(0), Rad(0 * Cos(sine / 1.5)), Rad(0)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.75  * Player_Size) * angles(Rad(0), Rad(85), Rad(0)) * angles(Rad(-3 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.5)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.75 * Player_Size) * angles(Rad(0), Rad(-85), Rad(0)) * angles(Rad(-3 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.5)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.45 - 0 * Cos(sine / 12)* Player_Size, -0.5* Player_Size) * angles(Rad(120), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.45 - 0 * Cos(sine / 12)* Player_Size, -0.5* Player_Size) * angles(Rad(120), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		for i = 0,5.5,0.1 do
			swait()
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(30)), 0.5)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(-0,0.4,-0.5) * angles(Rad(0), Rad(0 * Cos(sine / 1.5)), Rad(0)), 0.6)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.75  * Player_Size) * angles(Rad(0), Rad(85), Rad(0)) * angles(Rad(-3 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.5)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.75 * Player_Size) * angles(Rad(0), Rad(-85), Rad(0)) * angles(Rad(-3 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.5)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.45 - 0 * Cos(sine / 12)* Player_Size, -0.5* Player_Size) * angles(Rad(170), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.45 - 0 * Cos(sine / 12)* Player_Size, -0.5* Player_Size) * angles(Rad(127), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
		end
		print("4!")
		while BTAUNT6.Playing == true do
			for i = 0,2.5,0.1 do
				swait()
				change = 1
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(30)), 0.5)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(0,0,0) * angles(Rad(0), Rad(0 * Cos(sine / 1.5)), Rad(0)), 0.1)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), 0  * Player_Size) * angles(Rad(0), Rad(75), Rad(-0)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.5)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), 0 * Player_Size) * angles(Rad(0), Rad(-75), Rad(0)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.5)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, -0.1 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(10), Rad(0+ 0* Sin(sine / 20)), Rad(130 + 0* Cos(sine / 12))), 0.5)
				LW.C0 = clerp(LW.C0, CF(-1.4* Player_Size, 0.25 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(10), Rad(0+ 0* Sin(sine / 20)), Rad(40 + 0* Cos(sine / 12))), 0.5)
			end
			for i = 0,0.5,0.1 do
				swait()
				change = 1
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(30)), 0.5)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(0.5,0,0) * angles(Rad(0), Rad(0 * Cos(sine / 1.5)), Rad(0)), 0.6)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), 0  * Player_Size) * angles(Rad(0), Rad(75), Rad(-0)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.5)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), 0 * Player_Size) * angles(Rad(0), Rad(-75), Rad(0)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.5)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, -0.15 - 0 * Cos(sine / 12)* Player_Size, -0.3* Player_Size) * angles(Rad(10), Rad(0+ 0* Sin(sine / 20)), Rad(120 + 0* Cos(sine / 12))), 0.5)
				LW.C0 = clerp(LW.C0, CF(-1.8* Player_Size, 0.25 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(10), Rad(0+ 0* Sin(sine / 20)), Rad(40 + 0* Cos(sine / 12))), 0.5)
			end
			for i = 0,2.7,0.1 do
				swait()
				change = 1
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(10 + 0 * Sin(sine / 12)), Rad(0), Rad(60)), 0.5)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(-1,-1,-0.2) * angles(Rad(10), Rad(0 * Cos(sine / 1.5)), Rad(0)), 0.1)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.5  * Player_Size) * angles(Rad(0), Rad(97), Rad(10)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.5)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.5 * Player_Size) * angles(Rad(0), Rad(-97), Rad(-10)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.5)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0 - 0 * Cos(sine / 12)* Player_Size, -0* Player_Size) * angles(Rad(10), Rad(0+ 0* Sin(sine / 20)), Rad(170 + 0* Cos(sine / 12))), 0.5)
				LW.C0 = clerp(LW.C0, CF(-1.8* Player_Size, 0.25 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(10), Rad(0+ 0* Sin(sine / 20)), Rad(40 + 0* Cos(sine / 12))), 0.5)
			end
			for i = 0,0.5,0.1 do
				swait()
				change = 1
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(10 + 0 * Sin(sine / 12)), Rad(0), Rad(60)), 0.5)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(-0.5,-1,-0.2) * angles(Rad(10), Rad(0 * Cos(sine / 1.5)), Rad(0)), 0.6)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.5  * Player_Size) * angles(Rad(0), Rad(97), Rad(10)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.5)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.5 * Player_Size) * angles(Rad(0), Rad(-97), Rad(-10)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.5)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, -0.15 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(10), Rad(0+ 0* Sin(sine / 20)), Rad(120 + 0* Cos(sine / 12))), 0.5)
				LW.C0 = clerp(LW.C0, CF(-1.8* Player_Size, 0.25 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(10), Rad(0+ 0* Sin(sine / 20)), Rad(40 + 0* Cos(sine / 12))), 0.5)
			end
			for i = 0,2.5,0.1 do
				swait()
				change = 1
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(30)), 0.5)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(-1,0,0) * angles(Rad(0), Rad(0 * Cos(sine / 1.5)), Rad(0)), 0.1)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), 0  * Player_Size) * angles(Rad(0), Rad(75), Rad(-0)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.5)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), 0 * Player_Size) * angles(Rad(0), Rad(-75), Rad(0)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.5)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, -0.25 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(10), Rad(0+ 0* Sin(sine / 20)), Rad(130 + 0* Cos(sine / 12))), 0.5)
				LW.C0 = clerp(LW.C0, CF(-1.8* Player_Size, 0.25 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(10), Rad(0+ 0* Sin(sine / 20)), Rad(40 + 0* Cos(sine / 12))), 0.5)
			end
			for i = 0,2.7,0.1 do
				swait()
				change = 1
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(10 + 0 * Sin(sine / 12)), Rad(0), Rad(60)), 0.5)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(-2,-1,-0.2) * angles(Rad(10), Rad(0 * Cos(sine / 1.5)), Rad(0)), 0.1)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.5  * Player_Size) * angles(Rad(0), Rad(97), Rad(10)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.5)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.5 * Player_Size) * angles(Rad(0), Rad(-97), Rad(-10)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.5)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.25 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(10), Rad(0+ 0* Sin(sine / 20)), Rad(170 + 0* Cos(sine / 12))), 0.5)
				LW.C0 = clerp(LW.C0, CF(-1.8* Player_Size, 0.25 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(10), Rad(0+ 0* Sin(sine / 20)), Rad(40 + 0* Cos(sine / 12))), 0.5)
			end
			for i = 0,1.7,0.1 do
				swait()
				change = 1
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(30 + 0 * Sin(sine / 12)), Rad(0), Rad(0)), 0.5)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(-2,0.4,-0.5) * angles(Rad(30), Rad(0 * Cos(sine / 1.5)), Rad(0)), 0.1)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -0.6 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.75  * Player_Size) * angles(Rad(0), Rad(85), Rad(30)) * angles(Rad(-3 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.5)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -0.6 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.75 * Player_Size) * angles(Rad(0), Rad(-85), Rad(-30)) * angles(Rad(-3 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.5)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.45 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(150), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.5)
				LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.45 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(150), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.5)
			end
			for i = 0,2,0.1 do
				swait()
				change = 1
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(-30 + 0 * Sin(sine / 12)), Rad(0), Rad(0)), 0.5)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(-2,0.4,-0.5) * angles(Rad(-30), Rad(0 * Cos(sine / 1.5)), Rad(0)), 0.6)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.75  * Player_Size) * angles(Rad(0), Rad(85), Rad(-30)) * angles(Rad(-3 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.5)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.75 * Player_Size) * angles(Rad(0), Rad(-85), Rad(30)) * angles(Rad(-3 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.5)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.45 - 0 * Cos(sine / 12)* Player_Size, -0.5* Player_Size) * angles(Rad(60), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
				LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.45 - 0 * Cos(sine / 12)* Player_Size, -0.5* Player_Size) * angles(Rad(60), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 0.6)
			end
			for i = 0,3.4,0.1 do
				swait()
				change = 1
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(-30 + 0 * Sin(sine / 12)), Rad(0), Rad(-40)), 0.1)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(-2,0.4,-0.1) * angles(Rad(30), Rad(0 * Cos(sine / 1.5)), Rad(0)), 0.1)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1.5 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.75  * Player_Size) * angles(Rad(-40), Rad(85), Rad(30)) * angles(Rad(30 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.1)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.75 * Player_Size) * angles(Rad(0), Rad(-85), Rad(-30)) * angles(Rad(20 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.1)
				RW.C0 = clerp(RW.C0, CF(0.8* Player_Size, -0.5 - 0 * Cos(sine / 12)* Player_Size, -0.8* Player_Size) * angles(Rad(60), Rad(0+ 0* Sin(sine / 20)), Rad(-50 + 0* Cos(sine / 12))), 0.1)
				LW.C0 = clerp(LW.C0, CF(0.2* Player_Size, 0.65 - 0 * Cos(sine / 12)* Player_Size, -0.5* Player_Size) * angles(Rad(60), Rad(0+ 0* Sin(sine / 20)), Rad(120 + 0* Cos(sine / 12))), 0.1)
			end
			for i = 0,0.5,0.1 do
				swait()
				change = 1
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(40)), 1)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(-2,0.4,0.8) * angles(Rad(0), Rad(0 * Cos(sine / 1.5)), Rad(-50)), 1)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0  * Player_Size) * angles(Rad(0), Rad(85), Rad(0)) * angles(Rad(-3 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0 * Player_Size) * angles(Rad(0), Rad(-85), Rad(0)) * angles(Rad(-3 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.45 - 0 * Cos(sine / 12)* Player_Size, -0.5* Player_Size) * angles(Rad(0), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
				LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.45 - 0 * Cos(sine / 12)* Player_Size, -0.5* Player_Size) * angles(Rad(0), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
			end
			for i = 0,0.2,0.1 do
				swait()
				change = 1
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(40)), 1)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(-1,0.4,0.8) * angles(Rad(0), Rad(0 * Cos(sine / 1.5)), Rad(-100)), 0.6)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0  * Player_Size) * angles(Rad(0), Rad(85), Rad(0)) * angles(Rad(-3 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0 * Player_Size) * angles(Rad(0), Rad(-85), Rad(0)) * angles(Rad(-3 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.45 - 0 * Cos(sine / 12)* Player_Size, -0* Player_Size) * angles(Rad(0), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
				LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.45 - 0 * Cos(sine / 12)* Player_Size, -0* Player_Size) * angles(Rad(0), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
			end
			for i = 0,0.4,0.1 do
				swait()
				change = 1
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(40)), 1)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(0,0.4,0.2) * angles(Rad(0), Rad(0 * Cos(sine / 1.5)), Rad(-150)), 0.6)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0  * Player_Size) * angles(Rad(0), Rad(85), Rad(0)) * angles(Rad(-3 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0 * Player_Size) * angles(Rad(0), Rad(-85), Rad(0)) * angles(Rad(-3 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.45 - 0 * Cos(sine / 12)* Player_Size, -0* Player_Size) * angles(Rad(0), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
				LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.45 - 0 * Cos(sine / 12)* Player_Size, -0* Player_Size) * angles(Rad(0), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
			end
			for i = 0,0.4,0.1 do
				swait()
				change = 1
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(40)), 1)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(0,0.4,0) * angles(Rad(-30), Rad(0 * Cos(sine / 1.5)), Rad(0)), 0.6)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0  * Player_Size) * angles(Rad(0), Rad(85), Rad(0)) * angles(Rad(-3 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0 * Player_Size) * angles(Rad(0), Rad(-85), Rad(0)) * angles(Rad(-3 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.45 - 0 * Cos(sine / 12)* Player_Size, -0* Player_Size) * angles(Rad(0), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
				LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.45 - 0 * Cos(sine / 12)* Player_Size, -0* Player_Size) * angles(Rad(0), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
			end
			for i = 0,1.7,0.1 do
				swait()
				change = 1
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(30 + 0 * Sin(sine / 12)), Rad(0), Rad(10)), 0.5)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(.8,0.4,-0) * angles(Rad(0), Rad(0 * Cos(sine / 1.5)), Rad(0)), 0.1)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1* Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.15  * Player_Size) * angles(Rad(0), Rad(85), Rad(0)) * angles(Rad(-3 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.5)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.15 * Player_Size) * angles(Rad(0), Rad(-85), Rad(0)) * angles(Rad(-3 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.5)
				RW.C0 = clerp(RW.C0, CF(1.2* Player_Size, 0.45 - 0 * Cos(sine / 12)* Player_Size, -0.5* Player_Size) * angles(Rad(0), Rad(0+ 0* Sin(sine / 20)), Rad(-30 + 0* Cos(sine / 12))), 0.5)
				LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.15 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(0), Rad(0+ 0* Sin(sine / 20)), Rad(-130 + 0* Cos(sine / 12))), 0.5)
			end
			for i = 0,1.7,0.1 do
				swait()
				change = 1
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(30 + 0 * Sin(sine / 12)), Rad(0), Rad(30)), 0.5)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(1,0.4,-0) * angles(Rad(0), Rad(0 * Cos(sine / 1.5)), Rad(0)), 0.1)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1* Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.15  * Player_Size) * angles(Rad(0), Rad(95), Rad(0)) * angles(Rad(-23 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.5)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1* Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.15 * Player_Size) * angles(Rad(0), Rad(-95), Rad(0)) * angles(Rad(-23 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.5)
				RW.C0 = clerp(RW.C0, CF(1.2* Player_Size, 0.45 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(0), Rad(0+ 0* Sin(sine / 20)), Rad(-30 + 0* Cos(sine / 12))), 0.5)
				LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.15 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(0), Rad(0+ 0* Sin(sine / 20)), Rad(-60 + 0* Cos(sine / 12))), 0.5)
			end
			for i = 0,1.7,0.1 do
				swait()
				change = 1
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(30 + 0 * Sin(sine / 12)), Rad(0), Rad(10)), 0.5)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(1.5,0.4,-0) * angles(Rad(0), Rad(0 * Cos(sine / 1.5)), Rad(0)), 0.1)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1* Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.15  * Player_Size) * angles(Rad(0), Rad(85), Rad(0)) * angles(Rad(-3 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.5)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1* Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.15 * Player_Size) * angles(Rad(0), Rad(-85), Rad(0)) * angles(Rad(-3 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.5)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.45 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(0), Rad(0+ 0* Sin(sine / 20)), Rad(-30 + 0* Cos(sine / 12))), 0.5)
				LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.15 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(0), Rad(0+ 0* Sin(sine / 20)), Rad(-130 + 0* Cos(sine / 12))), 0.5)
			end
			for i = 0,1.7,0.1 do
				swait()
				change = 1
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(-40 + 0 * Sin(sine / 12)), Rad(0), Rad(0)), 0.5)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(1.5,0.4,-0) * angles(Rad(20), Rad(0 * Cos(sine / 1.5)), Rad(0)), 0.7)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1* Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.55  * Player_Size) * angles(Rad(0), Rad(85), Rad(20)) * angles(Rad(-13 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.5)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1* Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.55 * Player_Size) * angles(Rad(0), Rad(-85), Rad(-20)) * angles(Rad(-13 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.5)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.85 - 0 * Cos(sine / 12)* Player_Size, -0.2* Player_Size) * angles(Rad(0), Rad(0+ 0* Sin(sine / 20)), Rad(-40 + 0* Cos(sine / 12))), 0.5)
				LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.85 - 0 * Cos(sine / 12)* Player_Size, -0.2* Player_Size) * angles(Rad(0), Rad(0+ 0* Sin(sine / 20)), Rad(40 + 0* Cos(sine / 12))), 0.5)
			end
			for i = 0,0.7,0.1 do
				swait()
				change = 1
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(30 + 0 * Sin(sine / 12)), Rad(0), Rad(0)), 0.5)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(1.5,0.4,-0) * angles(Rad(30), Rad(0 * Cos(sine / 1.5)), Rad(0)), 0.1)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1* Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.55  * Player_Size) * angles(Rad(0), Rad(85), Rad(30)) * angles(Rad(-13 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.1)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1* Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.55 * Player_Size) * angles(Rad(0), Rad(-85), Rad(-30)) * angles(Rad(-13 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.1)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.35 - 0 * Cos(sine / 12)* Player_Size, -0.2* Player_Size) * angles(Rad(0), Rad(0+ 0* Sin(sine / 20)), Rad(-40 + 0* Cos(sine / 12))), 0.5)
				LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.35 - 0 * Cos(sine / 12)* Player_Size, -0.2* Player_Size) * angles(Rad(0), Rad(0+ 0* Sin(sine / 20)), Rad(40 + 0* Cos(sine / 12))), 0.5)
			end
			for i = 0,1.7,0.1 do
				swait()
				change = 1
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(0)), 0.5)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(1.5,0.4,-0) * angles(Rad(0), Rad(0 * Cos(sine / 1.5)), Rad(0)), 0.1)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1* Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.55  * Player_Size) * angles(Rad(0), Rad(85), Rad(-0)) * angles(Rad(-13 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.1)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1* Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.55 * Player_Size) * angles(Rad(0), Rad(-85), Rad(0)) * angles(Rad(-13 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.1)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.85 - 0 * Cos(sine / 12)* Player_Size, -0.2* Player_Size) * angles(Rad(0), Rad(0+ 0* Sin(sine / 20)), Rad(-40 + 0* Cos(sine / 12))), 0.5)
				LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.85 - 0 * Cos(sine / 12)* Player_Size, -0.2* Player_Size) * angles(Rad(0), Rad(0+ 0* Sin(sine / 20)), Rad(40 + 0* Cos(sine / 12))), 0.5)
			end
			for i = 0,1,0.1 do
				swait()
				change = 1
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(30 + 0 * Sin(sine / 12)), Rad(0), Rad(0)), 0.5)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(1.5,0.4,-0) * angles(Rad(30), Rad(0 * Cos(sine / 1.5)), Rad(0)), 0.1)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1* Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.55  * Player_Size) * angles(Rad(0), Rad(85), Rad(30)) * angles(Rad(-13 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.1)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1* Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.55 * Player_Size) * angles(Rad(0), Rad(-85), Rad(-30)) * angles(Rad(-13 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.1)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.15 - 0 * Cos(sine / 12)* Player_Size, -0.2* Player_Size) * angles(Rad(0), Rad(0+ 0* Sin(sine / 20)), Rad(-30 + 0* Cos(sine / 12))), 0.5)
				LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.15 - 0 * Cos(sine / 12)* Player_Size, -0.2* Player_Size) * angles(Rad(0), Rad(0+ 0* Sin(sine / 20)), Rad(30 + 0* Cos(sine / 12))), 0.5)
			end
			for i = 0,0.7,0.1 do
				swait()
				change = 1
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(30 + 0 * Sin(sine / 12)), Rad(0), Rad(0)), 0.5)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(1.2,0.4,-0) * angles(Rad(30), Rad(0 * Cos(sine / 1.5)), Rad(0)), 0.1)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1* Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.55  * Player_Size) * angles(Rad(0), Rad(85), Rad(30)) * angles(Rad(-13 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.1)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1* Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.55 * Player_Size) * angles(Rad(0), Rad(-85), Rad(-30)) * angles(Rad(-13 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.1)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.35 - 0 * Cos(sine / 12)* Player_Size, -0.2* Player_Size) * angles(Rad(0), Rad(0+ 0* Sin(sine / 20)), Rad(-40 + 0* Cos(sine / 12))), 0.5)
				LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.35 - 0 * Cos(sine / 12)* Player_Size, -0.2* Player_Size) * angles(Rad(0), Rad(0+ 0* Sin(sine / 20)), Rad(40 + 0* Cos(sine / 12))), 0.5)
			end
			for i = 0,2.7,0.1 do
				swait()
				change = 1
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(0)), 0.5)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(1.8,0.4,-0) * angles(Rad(0), Rad(0 * Cos(sine / 1.5)), Rad(0)), 0.1)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1* Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.55  * Player_Size) * angles(Rad(0), Rad(85), Rad(-0)) * angles(Rad(-13 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.1)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1* Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.55 * Player_Size) * angles(Rad(0), Rad(-85), Rad(0)) * angles(Rad(-13 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.1)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.85 - 0 * Cos(sine / 12)* Player_Size, -0.2* Player_Size) * angles(Rad(0), Rad(0+ 0* Sin(sine / 20)), Rad(-40 + 0* Cos(sine / 12))), 0.5)
				LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.85 - 0 * Cos(sine / 12)* Player_Size, -0.2* Player_Size) * angles(Rad(0), Rad(0+ 0* Sin(sine / 20)), Rad(40 + 0* Cos(sine / 12))), 0.5)
			end
			for i = 0,2,0.1 do
				swait()
				change = 1
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(30 + 0 * Sin(sine / 12)), Rad(0), Rad(0)), 0.5)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(1.2,0.4,-0) * angles(Rad(30), Rad(0 * Cos(sine / 1.5)), Rad(0)), 0.1)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1* Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.55  * Player_Size) * angles(Rad(0), Rad(85), Rad(30)) * angles(Rad(-13 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.1)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1* Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.55 * Player_Size) * angles(Rad(0), Rad(-85), Rad(-30)) * angles(Rad(-13 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.1)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.15 - 0 * Cos(sine / 12)* Player_Size, -0.2* Player_Size) * angles(Rad(0), Rad(0+ 0* Sin(sine / 20)), Rad(-30 + 0* Cos(sine / 12))), 0.5)
				LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.15 - 0 * Cos(sine / 12)* Player_Size, -0.2* Player_Size) * angles(Rad(0), Rad(0+ 0* Sin(sine / 20)), Rad(30 + 0* Cos(sine / 12))), 0.5)
			end
			for i = 0,3.4,0.1 do
				swait()
				change = 1
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(-30 + 0 * Sin(sine / 12)), Rad(0), Rad(40)), 0.1)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(1.5,0.4,-0) * angles(Rad(30), Rad(0 * Cos(sine / 1.5)), Rad(0)), 0.1)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1.5 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.75  * Player_Size) * angles(Rad(-40), Rad(85), Rad(30)) * angles(Rad(30 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.1)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0.75 * Player_Size) * angles(Rad(0), Rad(-85), Rad(-30)) * angles(Rad(20 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 0.1)
				RW.C0 = clerp(RW.C0, CF(0.8* Player_Size, -0.5 - 0 * Cos(sine / 12)* Player_Size, -0.8* Player_Size) * angles(Rad(60), Rad(0+ 0* Sin(sine / 20)), Rad(-50 + 0* Cos(sine / 12))), 0.1)
				LW.C0 = clerp(LW.C0, CF(0.2* Player_Size, 0.65 - 0 * Cos(sine / 12)* Player_Size, -0.5* Player_Size) * angles(Rad(60), Rad(0+ 0* Sin(sine / 20)), Rad(120 + 0* Cos(sine / 12))), 0.1)
			end
			for i = 0,0.5,0.1 do
				swait()
				change = 1
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(40)), 1)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(1,0.4,0.8) * angles(Rad(0), Rad(0 * Cos(sine / 1.5)), Rad(-50)), 1)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0  * Player_Size) * angles(Rad(0), Rad(85), Rad(0)) * angles(Rad(-3 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0 * Player_Size) * angles(Rad(0), Rad(-85), Rad(0)) * angles(Rad(-3 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.45 - 0 * Cos(sine / 12)* Player_Size, -0.5* Player_Size) * angles(Rad(0), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
				LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.45 - 0 * Cos(sine / 12)* Player_Size, -0.5* Player_Size) * angles(Rad(0), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
			end
			for i = 0,0.2,0.1 do
				swait()
				change = 1
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(40)), 1)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(0.5,0.4,0.8) * angles(Rad(0), Rad(0 * Cos(sine / 1.5)), Rad(-100)), 0.6)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0  * Player_Size) * angles(Rad(0), Rad(85), Rad(0)) * angles(Rad(-3 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0 * Player_Size) * angles(Rad(0), Rad(-85), Rad(0)) * angles(Rad(-3 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.45 - 0 * Cos(sine / 12)* Player_Size, -0* Player_Size) * angles(Rad(0), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
				LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.45 - 0 * Cos(sine / 12)* Player_Size, -0* Player_Size) * angles(Rad(0), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
			end
			for i = 0,0.4,0.1 do
				swait()
				change = 1
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(40)), 1)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(0,0.4,0.2) * angles(Rad(0), Rad(0 * Cos(sine / 1.5)), Rad(-150)), 0.6)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0  * Player_Size) * angles(Rad(0), Rad(85), Rad(0)) * angles(Rad(-3 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0 * Player_Size) * angles(Rad(0), Rad(-85), Rad(0)) * angles(Rad(-3 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.45 - 0 * Cos(sine / 12)* Player_Size, -0* Player_Size) * angles(Rad(0), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
				LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.45 - 0 * Cos(sine / 12)* Player_Size, -0* Player_Size) * angles(Rad(0), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
			end
			for i = 0,0.4,0.1 do
				swait()
				change = 1
				neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(40)), 1)
				rootj.C0 = clerp(rootj.C0, RootCF * CF(0,0.4,0) * angles(Rad(-30), Rad(0 * Cos(sine / 1.5)), Rad(0)), 0.6)
				RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0  * Player_Size) * angles(Rad(0), Rad(85), Rad(0)) * angles(Rad(-3 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 3.5), -0 * Player_Size) * angles(Rad(0), Rad(-85), Rad(0)) * angles(Rad(-3 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
				RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.45 - 0 * Cos(sine / 12)* Player_Size, -0* Player_Size) * angles(Rad(0), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
				LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.45 - 0 * Cos(sine / 12)* Player_Size, -0* Player_Size) * angles(Rad(0), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
			end
		end
		BTAUNT2:Play()
		attack = false
	end


	function discord()
		attack = true
		BTAUNT2:Stop()
		tecks2.Text = "car noises"
		hum.WalkSpeed = 100
		BTAUNT4:Play()
		la.Transparency = 1
		ra.Transparency = 1
		for i = 0,17,0.1 do
			swait()
			change = 1
			neck.C0 = clerp(neck.C0, necko* CF(0, -0.6, -1.5 + ((1* Player_Size) - 1)) * angles(Rad(90 + 0 * Sin(sine / 12)), Rad(0), Rad(0)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0,-2.6,-2) * angles(Rad(-90), Rad(0 + 10 * Cos(sine / 1.5)), Rad(0)), 1)
			RH.C0 = clerp(RH.C0, CF(1.8 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0.7  * Player_Size) * angles(Rad(0), Rad(90), Rad(-180)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1.8 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0.7 * Player_Size) * angles(Rad(0), Rad(-90), Rad(180)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(0* Player_Size, -1.55 - 0 * Cos(sine / 12)* Player_Size, -0.7* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
			LW.C0 = clerp(LW.C0, CF(-0* Player_Size, -2.55 - 0 * Cos(sine / 12)* Player_Size, -0.7* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
		end
		for i = 0,97,0.05 do
			swait()
			change = 1
			neck.C0 = clerp(neck.C0, necko* CF(0, -0.6, -1.5 + ((1* Player_Size) - 1)) * angles(Rad(90 + 0 * Sin(sine / 12)), Rad(0), Rad(0)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0,-2.6,-2) * angles(Rad(-90), Rad(0 + 10 * Cos(sine / 1.5)), Rad(0)), 1)
			RH.C0 = clerp(RH.C0, CF(1.8 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0.7  * Player_Size) * angles(Rad(0), Rad(90), Rad(-180)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1.8 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0.7 * Player_Size) * angles(Rad(0), Rad(-90), Rad(180)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(0* Player_Size, -1.55 - 0 * Cos(sine / 12)* Player_Size, -0.7* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
			LW.C0 = clerp(LW.C0, CF(-0* Player_Size, -2.55 - 0 * Cos(sine / 12)* Player_Size, -0.7* Player_Size) * angles(Rad(90), Rad(0+ 0* Sin(sine / 20)), Rad(0 + 0* Cos(sine / 12))), 1)
		end
		BTAUNT4:Stop()
		hum.WalkSpeed = 20
		la.Transparency = 0
		ra.Transparency = 0
		tecks2.Text = ":joy:"
		BTAUNT2:Play()
		change = 1.7
		attack = false
	end

	function E()
		attack = true
		Cso("1937272483", hed, 10, 1)
		tecks2.Text = "E"
		for i = 0,7,0.1 do
			swait()
			change = 1
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(0)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0.5* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0.3* Player_Size * Sin(sine / 1.2)* Player_Size, 0.8 + 0.3* Player_Size * Sin(sine / 1.2)) * angles(Rad(0 - 10 * Sin(sine / 1.5)), Rad(0 + 10 * Cos(sine / 1.5)), Rad(0)), 1)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(0)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(0)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(0* Cos(sine / 12)), Rad(0+ 0* Sin(sine / 20)), Rad(90 + 0* Cos(sine / 12))), 1)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(0* Cos(sine / 12)), Rad(0+ 0* Sin(sine / 20)), Rad(-90 + 0* Cos(sine / 12))), 1)
		end
		tecks2.Text = ":joy:"
		change = 1.7
		attack = false
	end




	function bruh()
		attack = true
		Cso("4615152991", hed, 10, 1)
		tecks2.Text = "me going to the poop dimension"
		for i = 0,7,0.1 do
			swait()
			change = 1
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(0)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0.5* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0.3* Player_Size * Sin(sine / 1.2)* Player_Size, 0.8 + 0.3* Player_Size * Sin(sine / 1.2)) * angles(Rad(-70 - 10 * Sin(sine / 1.5)), Rad(0 + 10 * Cos(sine / 1.5)), Rad(0)), 0.11)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-50)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(50)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(-70), Rad(0+ 0* Sin(sine / 20)), Rad(20 + 0* Cos(sine / 12))), 1)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(-70), Rad(0+ 0* Sin(sine / 20)), Rad(-20 + 0* Cos(sine / 12))), 1)
		end
		for i = 0,7,0.1 do
			swait()
			change = 1
			neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(0 + 0 * Sin(sine / 12)), Rad(0), Rad(0)), 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0 + 0.5* Player_Size * Sin(sine / 1.2)* Player_Size, 0 + 0.3* Player_Size * Sin(sine / 1.2)* Player_Size, 45.8 + 0* Player_Size * Sin(sine / 1.2)) * angles(Rad(-70 - 10 * Sin(sine / 1.5)), Rad(0 + 10 * Cos(sine / 1.5)), Rad(0)), 0.03)
			RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0  * Player_Size) * angles(Rad(0), Rad(90), Rad(-50)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0 * Player_Size * Sin(sine / 12), 0 * Player_Size) * angles(Rad(0), Rad(-90), Rad(50)) * angles(Rad(0 - 0 * Cos(sine / 12)), Rad(0), Rad(0)), 1)
			RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(-70), Rad(0+ 0* Sin(sine / 20)), Rad(20 + 0* Cos(sine / 12))), 1)
			LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(-70), Rad(0+ 0* Sin(sine / 20)), Rad(-20 + 0* Cos(sine / 12))), 1)
		end
		tecks2.Text = ":joy:"
		change = 1.7
		attack = false
	end
	local Head1 = Instance.new("Part", char)
	Head1.Name = "Blob"
	Head1.CanCollide = false
	Head1.BrickColor = BrickColor.new("Really black")
	Head1.Transparency = 1
	Head1.Material = "Plastic"
	Head1.Size = Vector3.new(1, 1, 1)
	Head1.TopSurface = Enum.SurfaceType.Smooth
	Head1.BottomSurface = Enum.SurfaceType.Smooth

	local Weld = Instance.new("Weld", Head1)
	Weld.Part0 = tors
	Weld.Part1 = Head1
	Weld.C1 = CFrame.new(0, 0, 0)
	Weld.C0 = CFrame.Angles(Rad(0),0,0)

	local M3 = Instance.new("SpecialMesh")
	M3.Parent = Head1
	M3.MeshType = "Brick"
	M3.Scale = Vector3.new(5, 5, 5)
	face1 = Instance.new("Decal", Head1)
	face1.Face = "Front"
	face1.Transparency = 1
	face1.Texture = "rbxassetid://153159982"


	-------------------------------------------------------
	--End Attacks N Stuff--
	-------------------------------------------------------
	mouse.KeyDown:connect(function(key)
		if attack == false then
			if key == "e" then
				E()
			elseif key == "z" then
				bruh()
			elseif key == "t" then
				face1.Transparency = 0
				Head1.Transparency = 0
				Cso("1747834381", hed, 10, 1)
				BTAUNT2:Stop()
				wait(19) 
				Cso("3173571164", hed, 10, 1)
				Head1.Transparency = 1
				face1.Transparency = 1
				wait(19)
				BTAUNT2:Play()
			elseif key == "r" then
				roadroller()
			elseif key == "x" then
				bruhmoment()
			elseif key == "c" then
				discord()
			elseif key == "v" then
				when()
			elseif key == "f" then
				isthatajojoreference()
			end
		end
	end)

	local FakeVel = Vector3.new(0,0,0)
	if lplr == Player then
		spawn(function()
			while true do
				local Positions = {}
				local Speeds = {}
				for i = 1,10 do
					table.insert(Positions, root.CFrame)
					table.insert(Speeds, root.Velocity)
					swait()
				end
			end
		end)
	end

	if lplr ~= Player then
		local Last = root.Position
		Mover.OnClientEvent:Connect(function(v, Speed)
			for i,v2 in pairs(v) do
				FakeVel = Speed[i]
				if v[i].p ~= Last then
					if MoverSpeed.Value == "Remote" then
						root.CFrame = v[i]
					end
					Last = v[i].p
					swait()
				end
			end
		end)
		spawn(function()
			while true do
				game:GetService("RunService").RenderStepped:wait()
				FakeRoot = workspace.Terrain:WaitForChild(Player.Name.." char tracker")
				if MoverSpeed.Value == "Smooth" then
					root.CFrame = FakeRoot.CFrame
				end
			end
		end)
	end

	-------------------------------------------------------
	--Start Damage Function--
	-------------------------------------------------------
	function PixelBlock(bonuspeed,FastSpeed,type,pos,x1,y1,z1,value,color,outerpos) --Thanks, Star Glitcher!
		local type = type
		local rng = Instance.new("Part", char)
		rng.Anchored = true
		rng.BrickColor = color
		rng.CanCollide = false
		rng.FormFactor = 3
		rng.Name = "Ring"
		rng.Material = "Neon"
		rng.Size = Vector3.new(1, 1, 1)
		rng.Transparency = 0
		rng.TopSurface = 0
		rng.BottomSurface = 0
		rng.CFrame = pos
		rng.CFrame = rng.CFrame + rng.CFrame.lookVector*outerpos
		local rngm = Instance.new("SpecialMesh", rng)
		rngm.MeshType = "Brick"
		if rainbowmode == true then
			rng.Color = Color3.new(r/255,g/255,b/255)
		end
		local scaler2 = 1
		local speeder = FastSpeed/10
		if type == "Add" then
			scaler2 = 1*value
		elseif type == "Divide" then
			scaler2 = 1/value
		end
		coroutine.resume(coroutine.create(function()
			for i = 0,10/bonuspeed,0.1 do
				swait()
				if type == "Add" then
					scaler2 = scaler2 - 0.01*value/bonuspeed
				elseif type == "Divide" then
					scaler2 = scaler2 - 0.01/value*bonuspeed
				end
				speeder = speeder - 0.01*FastSpeed*bonuspeed/10
				rng.CFrame = rng.CFrame + rng.CFrame.lookVector*speeder*bonuspeed
				rng.Transparency = rng.Transparency + 0.01*bonuspeed
			end
			rng:Destroy()
		end))
	end

	function Damage(Part, hit, minim, maxim, knockback, Type, Property, Delay, HitSound, HitPitch)
		if hit.Parent == nil then
			return
		end
		local h = hit.Parent:FindFirstChildOfClass("Humanoid")
		for _, v in pairs(hit.Parent:children()) do
			if v:IsA("Humanoid") then
				h = v
			end
		end
		if h ~= nil and hit.Parent.Name ~= char.Name and hit.Parent:FindFirstChild("UpperTorso") ~= nil then

			hit.Parent:FindFirstChild("Head"):BreakJoints()
		end

		if h ~= nil and hit.Parent.Name ~= char.Name and hit.Parent:FindFirstChild("Torso") ~= nil then
			if hit.Parent:findFirstChild("DebounceHit") ~= nil then
				if hit.Parent.DebounceHit.Value == true then
					return
				end
			end
			if insta == true then
				hit.Parent:FindFirstChild("Head"):BreakJoints()
			end
			local c = Create("ObjectValue"){
				Name = "creator",
				Value = Player,
				Parent = h,
			}
			game:GetService("Debris"):AddItem(c, .5)
			if HitSound ~= nil and HitPitch ~= nil then
				CFuncs.Sound.Create(HitSound, hit, 1, HitPitch) 
			end
			local Damage = math.random(minim, maxim)
			local blocked = false
			local block = hit.Parent:findFirstChild("Block")
			if block ~= nil then
				if block.className == "IntValue" then
					if block.Value > 0 then
						blocked = true
						block.Value = block.Value - 1
						print(block.Value)
					end
				end
			end
			if blocked == false then
				--h.Health = h.Health - Damage
				ShowDamage((Part.CFrame * CFrame.new(0, 0, (Part.Size.Z / 2)).p + Vector3.new(0, 1.5, 0)), -Damage, 1.5, tors.BrickColor.Color)
			else
				--h.Health = h.Health - (Damage / 2)
				ShowDamage((Part.CFrame * CFrame.new(0, 0, (Part.Size.Z / 2)).p + Vector3.new(0, 1.5, 0)), -Damage, 1.5, tors.BrickColor.Color)
			end
			if Type == "Knockdown" then
				local hum = hit.Parent.Humanoid
				hum.PlatformStand = true
				coroutine.resume(coroutine.create(function(HHumanoid)
					swait(1)
					HHumanoid.PlatformStand = false
				end), hum)
				local angle = (hit.Position - (Property.Position + Vector3.new(0, 0, 0))).unit
				local bodvol = Create("BodyVelocity"){
					velocity = angle * knockback,
					P = 5000,
					maxForce = Vector3.new(8e+003, 8e+003, 8e+003),
					Parent = hit,
				}
				local rl = Create("BodyAngularVelocity"){
					P = 3000,
					maxTorque = Vector3.new(500000, 500000, 500000) * 50000000000000,
					angularvelocity = Vector3.new(math.random(-10, 10), math.random(-10, 10), math.random(-10, 10)),
					Parent = hit,
				}
				game:GetService("Debris"):AddItem(bodvol, .5)
				game:GetService("Debris"):AddItem(rl, .5)
			elseif Type == "Normal" then
				local vp = Create("BodyVelocity"){
					P = 500,
					maxForce = Vector3.new(math.huge, 0, math.huge),
					velocity = Property.CFrame.lookVector * knockback + Property.Velocity / 1.05,
				}
				if knockback > 0 then
					vp.Parent = hit.Parent.Torso
				end
				game:GetService("Debris"):AddItem(vp, .5)
			elseif Type == "Up" then
				local bodyVelocity = Create("BodyVelocity"){
					velocity = Vector3.new(0, 20, 0),
					P = 5000,
					maxForce = Vector3.new(8e+003, 8e+003, 8e+003),
					Parent = hit,
				}
				game:GetService("Debris"):AddItem(bodyVelocity, .5)
			elseif Type == "DarkUp" then
				coroutine.resume(coroutine.create(function()
					for i = 0, 1, 0.1 do
						swait()
						Effects.Block.Create(BrickColor.new("Royal purple"), hit.Parent.Torso.CFrame, 5, 5, 5, 1, 1, 1, .08, 1)
					end
				end))
				local bodyVelocity = Create("BodyVelocity"){
					velocity = Vector3.new(0, 20, 0),
					P = 5000,
					maxForce = Vector3.new(8e+003, 8e+003, 8e+003),
					Parent = hit,
				}
				game:GetService("Debris"):AddItem(bodyVelocity, 1)
			elseif Type == "Snare" then
				local bp = Create("BodyPosition"){
					P = 2000,
					D = 100,
					maxForce = Vector3.new(math.huge, math.huge, math.huge),
					position = hit.Parent.Torso.Position,
					Parent = hit.Parent.Torso,
				}
				game:GetService("Debris"):AddItem(bp, 1)
			elseif Type == "Freeze" then
				local BodPos = Create("BodyPosition"){
					P = 50000,
					D = 1000,
					maxForce = Vector3.new(math.huge, math.huge, math.huge),
					position = hit.Parent.Torso.Position,
					Parent = hit.Parent.Torso,
				}
				local BodGy = Create("BodyGyro") {
					maxTorque = Vector3.new(4e+005, 4e+005, 4e+005) * math.huge ,
					P = 20e+003,
					Parent = hit.Parent.Torso,
					cframe = hit.Parent.Torso.CFrame,
				}
				hit.Parent.Torso.Anchored = true
				coroutine.resume(coroutine.create(function(Part) 
					swait(1.5)
					Part.Anchored = false
				end), hit.Parent.Torso)
				game:GetService("Debris"):AddItem(BodPos, 3)
				game:GetService("Debris"):AddItem(BodGy, 3)
			end
			local debounce = Create("BoolValue"){
				Name = "DebounceHit",
				Parent = hit.Parent,
				Value = true,
			}
			game:GetService("Debris"):AddItem(debounce, Delay)
			c = Create("ObjectValue"){
				Name = "creator",
				Value = Player,
				Parent = h,
			}
			game:GetService("Debris"):AddItem(c, .5)
		end
	end

	function damage(range,mindam,maxdam,pos)
		if true then return end
	end
	-------------------------------------------------------
	--End Damage Function--
	-------------------------------------------------------

	-------------------------------------------------------
	--Start Animations--
	-------------------------------------------------------
	print("By XandersAltAccount1")
	while true do
		swait()
		sine = sine + change
		local torvel = (FakeVel * Vector3.new(1, 0, 1)).magnitude
		local velderp = FakeVel.y
		if lplr == plr then
			torvel = (root.Velocity * Vt(1, 0, 1)).magnitude
			velderp = root.Velocity.y
		end
		hitfloor, posfloor = rayCast(root.Position, CFrame.new(root.Position, root.Position - Vector3.new(0, 1, 0)).lookVector, 4* Player_Size, char)
		if equipped == true or equipped == false then
			if attack == false then
				idle = idle + 1
			else
				idle = 0
			end
			if 1 < root.Velocity.y and hitfloor == nil then
				Anim = "Jump"
				if attack == false then
					rootj.C0 = clerp(rootj.C0, RootCF * CF(0* Player_Size, 0* Player_Size, 0.9 + 0.5* Player_Size * Cos(sine / -15)) * angles(Rad(0), Rad(0), Rad(0)), 0.17)
					neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(10 - 2.5 * Sin(sine / 30)), Rad(0), Rad(0)), 0.3)
					RH.C0 = clerp(RH.C0, CF(1* Player_Size, -.2 - 0.1 * Cos(sine / 20)* Player_Size, -.3* Player_Size) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
					LH.C0 = clerp(LH.C0, CF(-1* Player_Size, -.9 - 0.1 * Cos(sine / 20), -.5* Player_Size) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
					RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.5 + 0.02 * Sin(sine / 20)* Player_Size, 0* Player_Size) * angles(Rad(25), Rad(-.6), Rad(13 + 4.5 * Sin(sine / 20))), 0.1)
					LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.5 + 0.02 * Sin(sine / 20)* Player_Size, 0* Player_Size) * angles(Rad(25), Rad(-.6), Rad(-13 - 4.5 * Sin(sine / 20))), 0.1)
				end
			elseif -1 > root.Velocity.y and hitfloor == nil then
				Anim = "Fall"
				if attack == false then
					rootj.C0 = clerp(rootj.C0, RootCF * CF(0* Player_Size, 0* Player_Size, -0.1 + 0.1 * Cos(sine / 20)* Player_Size) * angles(Rad(24), Rad(0), Rad(0)), 0.15)
					neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(10 - 2.5 * Sin(sine / 30)), Rad(0), Rad(0)), 0.3)
					RH.C0 = clerp(RH.C0, CF(1* Player_Size, -1 - 0.1 * Cos(sine / 20)* Player_Size, -.3* Player_Size) * RHCF * angles(Rad(-3.5), Rad(0), Rad(0)), 0.15)
					LH.C0 = clerp(LH.C0, CF(-1* Player_Size, -.8 - 0.1 * Cos(sine / 20)* Player_Size, -.3* Player_Size) * LHCF * angles(Rad(-3.5), Rad(0), Rad(0)), 0.15)
					RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.5 + 0.02 * Sin(sine / 20)* Player_Size, 0* Player_Size) * angles(Rad(65), Rad(-.6), Rad(45 + 4.5 * Sin(sine / 20))), 0.1)
					LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.5 + 0.02 * Sin(sine / 20)* Player_Size, 0* Player_Size) * angles(Rad(55), Rad(-.6), Rad(-45 - 4.5 * Sin(sine / 20))), 0.1)
				end
			elseif torvel < 1 and hitfloor ~= nil then
				Anim = "Idle"
				change = 1.75
				if attack == false then
					neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(-10 + 12.5 * Sin(sine / 12)), Rad(0), Rad(0)), 0.3)
					rootj.C0 = clerp(rootj.C0, RootCF * CF(0* Player_Size, 0* Player_Size, -0.1 + 0.3* Player_Size * Sin(sine / 12)) * angles(Rad(0 - 0 * Sin(sine / 20)), Rad(0 + 0 * Cos(sine / 20)), Rad(0)), 0.35)
					RH.C0 = clerp(RH.C0, CF(1 * Player_Size, -1 * Player_Size - 0.3 * Player_Size * Sin(sine / 12), -0.5  * Player_Size) * angles(Rad(0), Rad(76), Rad(-10)) * angles(Rad(-13 - -7 * Cos(sine / 12)), Rad(0), Rad(0)), 0.35)
					LH.C0 = clerp(LH.C0, CF(-1 * Player_Size, -1 * Player_Size - 0.3 * Player_Size * Sin(sine / 12), -0.5 * Player_Size) * angles(Rad(0), Rad(-76), Rad(10)) * angles(Rad(-13 - -7 * Cos(sine / 12)), Rad(0), Rad(0)), 0.35)
					RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.55 - 0.15 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(10* Cos(sine / 12)), Rad(0+ 0* Sin(sine / 20)), Rad(10 + -12.5 * Cos(sine / 12))), 0.12)
					LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.55 - 0.15 * Cos(sine / 12)* Player_Size, 0* Player_Size) * angles(Rad(10* Cos(sine / 12)), Rad(0+ 0* Sin(sine / 20)), Rad(-10 + 12.5 * Cos(sine / 12))), 0.12)
				end
			elseif torvel > 2 and torvel < 25 and hitfloor ~= nil then
				Anim = "Walk"
				change = 1.3
				if attack == false then
					rootj.C0 = clerp(rootj.C0, RootCF * CF(0* Player_Size, 0* Player_Size, 0.375 + -0.73 * Sin(sine / 3.5) + -Sin(sine / 3.5) / 1* Player_Size) * angles(Rad(-3 - 32.5 * Cos(sine / 3.5)), Rad(0) - root.RotVelocity.Y / 75, Rad(1 * Cos(sine / 7))), 0.15)
					neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(30 * Sin(sine / 3.5)), Rad(0), Rad(0 * Cos(sine / 7)) - hed.RotVelocity.Y / 15), 0.3)
					RH.C0 = clerp(RH.C0, CF(1* Player_Size, -0.8 - 1 * Cos(sine / 7) / 2* Player_Size, 0.8 * Cos(sine / 7) / 0.7* Player_Size)  * angles(Rad(-10 - 25 * Cos(sine / 7)) - rl.RotVelocity.Y / 75 + -Sin(sine / 7) / 2, Rad(90 - 15 * Cos(sine / 7)), Rad(0)) * angles(Rad(0 + 2 * Cos(sine / 7)), Rad(0), Rad(-0)), 0.3)
					LH.C0 = clerp(LH.C0, CF(-1* Player_Size, -0.8 + 1 * Cos(sine / 7) / 2* Player_Size, -0.8 * Cos(sine / 7) / 0.7* Player_Size) * angles(Rad(-10 + 25 * Cos(sine / 7)) + ll.RotVelocity.Y / 75 + Sin(sine / 7) / 2, Rad(-90 - 15 * Cos(sine / 7)), Rad(0)) * angles(Rad(0 - 2 * Cos(sine / 7)), Rad(0), Rad(0)), 0.3)
					RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.5 + 0.05 * Sin(sine / 7)* Player_Size, 0* Player_Size) * angles(Rad(137)  * Cos(sine / 7) , Rad(10 * Cos(sine / 7)), Rad(0) - ra.RotVelocity.Y / 75), 0.1)
					LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.5 + 0.05 * Sin(sine / 7)* Player_Size, 0* Player_Size) * angles(Rad(-137)  * Cos(sine / 7) , Rad(10 * Cos(sine / 7)) ,	Rad(0) + la.RotVelocity.Y / 75), 0.1)
				end
			elseif torvel >= 25 and hitfloor ~= nil then
				Anim = "Sprint"
				change = 1.35
				if attack == false then
					rootj.C0 = clerp(rootj.C0, RootCF * CF(0* Player_Size, 0* Player_Size, -0.175 + 0.13 * Cos(sine / 3.5) + -Sin(sine / 3.5) / 7* Player_Size) * angles(Rad(23 - 2.5 * Cos(sine / 3.5)), Rad(0) - root.RotVelocity.Y / 75, Rad(15 * Cos(sine / 7))), 0.15)
					neck.C0 = clerp(neck.C0, necko* CF(0, 0, 0 + ((1* Player_Size) - 1)) * angles(Rad(-10), Rad(0), Rad(0) - hed.RotVelocity.Y / 15), 0.3)
					RH.C0 = clerp(RH.C0, CF(1* Player_Size, -0.8 - 0.5 * Cos(sine / 7) / 2* Player_Size, 0.6 * Cos(sine / 7) / 2* Player_Size)  * angles(Rad(-10 - 25 * Cos(sine / 7)) - rl.RotVelocity.Y / 75 + -Sin(sine / 7) / 2.5, Rad(90 - 15 * Cos(sine / 7)), Rad(0)) * angles(Rad(0 + 2 * Cos(sine / 7)), Rad(0), Rad(20)), 0.3)
					LH.C0 = clerp(LH.C0, CF(-1* Player_Size, -0.8 + 0.5 * Cos(sine / 7) / 2* Player_Size, -0.6 * Cos(sine / 7) / 2* Player_Size) * angles(Rad(-10 + 25 * Cos(sine / 7)) + ll.RotVelocity.Y / 75 + Sin(sine / 7) / 2.5, Rad(-90 - 15 * Cos(sine / 7)), Rad(0)) * angles(Rad(0 - 2 * Cos(sine / 7)), Rad(0), Rad(-20)), 0.3)
					RW.C0 = clerp(RW.C0, CF(1.5* Player_Size, 0.5 + 0.05 * Sin(sine / 7)* Player_Size, 0* Player_Size) * angles(Rad(57)  * Cos(sine / 7) , Rad(10 * Cos(sine / 7)), Rad(0) - ra.RotVelocity.Y / 75), 0.1)
					LW.C0 = clerp(LW.C0, CF(-1.5* Player_Size, 0.5 + 0.05 * Sin(sine / 7)* Player_Size, 0* Player_Size) * angles(Rad(-57)  * Cos(sine / 7) , Rad(10 * Cos(sine / 7)) ,	Rad(0) + la.RotVelocity.Y / 75), 0.1)
				end
			end
		end
		refit()
		Refit()
		Parents()
		if 0 < #Effects then
			for e = 1, #Effects do
				if Effects[e] ~= nil then
					local Thing = Effects[e]
					if Thing ~= nil then
						local Part = Thing[1]
						local Mode = Thing[2]
						local Delay = Thing[3]
						local IncX = Thing[4]
						local IncY = Thing[5]
						local IncZ = Thing[6]
						if 1 >= Thing[1].Transparency then
							if Thing[2] == "Block1" then
								Thing[1].CFrame = Thing[1].CFrame * CFrame.fromEulerAnglesXYZ(math.random(-50, 50), math.random(-50, 50), math.random(-50, 50))
								local Mesh = Thing[1].Mesh
								Mesh.Scale = Mesh.Scale + Vector3.new(Thing[4], Thing[5], Thing[6])
								Thing[1].Transparency = Thing[1].Transparency + Thing[3]
							elseif Thing[2] == "Block2" then
								Thing[1].CFrame = Thing[1].CFrame + Vector3.new(0, 0, 0)
								local Mesh = Thing[7]
								Mesh.Scale = Mesh.Scale + Vector3.new(Thing[4], Thing[5], Thing[6])
								Thing[1].Transparency = Thing[1].Transparency + Thing[3]
							elseif Thing[2] == "Block3" then
								Thing[1].CFrame = Thing[1].CFrame * CFrame.fromEulerAnglesXYZ(math.random(-50, 50), math.random(-50, 50), math.random(-50, 50)) + Vector3.new(0, 0.15, 0)
								local Mesh = Thing[7]
								Mesh.Scale = Mesh.Scale + Vector3.new(Thing[4], Thing[5], Thing[6])
								Thing[1].Transparency = Thing[1].Transparency + Thing[3]
							elseif Thing[2] == "Cylinder" then
								local Mesh = Thing[1].Mesh
								Mesh.Scale = Mesh.Scale + Vector3.new(Thing[4], Thing[5], Thing[6])
								Thing[1].Transparency = Thing[1].Transparency + Thing[3]
							elseif Thing[2] == "Blood" then
								local Mesh = Thing[7]
								Thing[1].CFrame = Thing[1].CFrame * Vector3.new(0, 0.5, 0)
								Mesh.Scale = Mesh.Scale + Vector3.new(Thing[4], Thing[5], Thing[6])
								Thing[1].Transparency = Thing[1].Transparency + Thing[3]
							elseif Thing[2] == "Elec" then
								local Mesh = Thing[1].Mesh
								Mesh.Scale = Mesh.Scale + Vector3.new(Thing[7], Thing[8], Thing[9])
								Thing[1].Transparency = Thing[1].Transparency + Thing[3]
							elseif Thing[2] == "Disappear" then
								Thing[1].Transparency = Thing[1].Transparency + Thing[3]
							elseif Thing[2] == "Shatter" then
								Thing[1].Transparency = Thing[1].Transparency + Thing[3]
								Thing[4] = Thing[4] * CFrame.new(0, Thing[7], 0)
								Thing[1].CFrame = Thing[4] * CFrame.fromEulerAnglesXYZ(Thing[6], 0, 0)
								Thing[6] = Thing[6] + Thing[5]
							end
						else
							Part.Parent = nil
							table.remove(Effects, e)
						end
					end
				end
			end
		end
	end
	-----------------------------------------------------
end)

meme.Name = "meme"
meme.Parent = main
meme.BackgroundColor3 = Color3.fromRGB(85, 85, 85)
meme.Position = UDim2.new(0.125, 0, 0.318340033, 0)
meme.Size = UDim2.new(0, 134, 0, 32)
meme.Font = Enum.Font.SciFi
meme.Text = "mEmE"
meme.TextColor3 = Color3.fromRGB(0, 0, 0)
meme.TextSize = 35.000
meme.MouseButton1Down:connect(function()
	-----------------------
	--MemeusV2--
	-------------------------------------------------------
	--A script By makhail07

	--This edit by 2003boobear

	--Discord Creterisk#2958 (not 2003boobear's discord)
	-------------------------------------------------------

	local FavIDs = {
		340106355, --Nefl Crystals
		927529620, --Dimension
		876981900, --Fantasy
		398987889, --Ordinary Days
		1117396305, --Oh wait, it's you.
		885996042, --Action Winter Journey
		919231299, --Sprawling Idiot Effigy
		743466274, --Good Day Sunshine
		727411183, --Knife Fight
		1402748531, --The Earth Is Counting On You!
		595230126 --Robot Language
	}

	FELOADLIBRARY = {}
	loadstring(game:GetObjects("rbxassetid://5209815302")[1].Source)()
	Bypass = "death"
	loadstring(game:GetObjects("rbxassetid://5325226148")[1].Source)()

	--The reality of my life isn't real but a Universe -makhail07
	wait()
	local Player = game.Players.localPlayer
	local Character = workspace.non
	local plr = game:service'Players'.LocalPlayer
	local Humanoid = Character.Humanoid
	local char = Character
	local hum = char.Humanoid
	local ra = char["Right Arm"]
	local la= char["Left Arm"]
	local rl= char["Right Leg"]
	local ll = char["Left Leg"]
	local hed = char.Head
	local root = char.HumanoidRootPart
	local rootj = root.RootJoint
	local tors = char.Torso
	local mouse = plr:GetMouse()
	local RootCF = CFrame.fromEulerAnglesXYZ(-1.57, 0, 3.14)
	local RHCF = CFrame.fromEulerAnglesXYZ(0, 1.6, 0)
	local LHCF = CFrame.fromEulerAnglesXYZ(0, -1.6, 0)
	local cam = game.Workspace.CurrentCamera
	trazx = Instance.new("ParticleEmitter")
	c = game.Players.LocalPlayer.Character

	--where i put all the warn things

	warn ("Well Look at that, I finished it.")
	--Looks Like you decided to look though the script. Well, Hello.
	warn ("I had a fun time making this edit.")
	--I Really DID have fun editing this.
	warn ("I hope you Enjoy this. Go have Fun!")
	--Just don't abuse.
	warn ("Also, the original MemeusV2 was made by makhail07.")
	--Support makhail07 for making the original!
	warn ("This edit was made by me, 2003boobear.")
	--This is one of my best edits BY FAR, though.
	Character.Head.face.Texture = "rbxassetid://620619801"

	-------------------------------------------------------
	--Start Good Stuff--
	-------------------------------------------------------
	CF = CFrame.new
	angles = CFrame.Angles
	attack = false
	timetofly = true
	Euler = CFrame.fromEulerAnglesXYZ
	Rad = math.rad
	IT = Instance.new
	BrickC = BrickColor.new
	Cos = math.cos
	Acos = math.acos
	Sin = math.sin
	Asin = math.asin
	Abs = math.abs
	Mrandom = math.random
	Floor = math.floor
	random = math.random
	radian = math.rad
	Vec3 = Vector3.new
	cFrame = CFrame.new
	Euler = CFrame.fromEulerAnglesXYZ
	-------------------------------------------------------
	--End Good Stuff--
	-------------------------------------------------------
	necko = CF(0, 1, 0, -1, -0, -0, 0, 0, 1, 0, 1, 0)
	RSH, LSH = nil, nil 
	RW = Instance.new("Weld") 
	LW = Instance.new("Weld")
	RH = tors["Right Hip"]
	LH = tors["Left Hip"]
	RSH = tors["Right Shoulder"] 
	LSH = tors["Left Shoulder"] 
	RSH.Parent = nil 
	LSH.Parent = nil 
	RW.Name = "RW"
	RW.Part0 = tors 
	RW.C0 = CF(1.5, 0.5, 0)
	RW.C1 = CF(0, 0.5, 0) 
	RW.Part1 = ra
	RW.Parent = tors 
	LW.Name = "LW"
	LW.Part0 = tors 
	LW.C0 = CF(-1.5, 0.5, 0)
	LW.C1 = CF(0, 0.5, 0) 
	LW.Part1 = la
	LW.Parent = tors
	Effects = {}

	-------------------------------------------------------
	--Start HeartBeat--
	-------------------------------------------------------
	ArtificialHB = Instance.new("BindableEvent", script)
	ArtificialHB.Name = "Heartbeat"
	script:WaitForChild("Heartbeat")

	frame = 1 / 60
	tf = 0
	allowframeloss = false
	tossremainder = false


	lastframe = tick()
	script.Heartbeat:Fire()


	game:GetService("RunService").Heartbeat:connect(function(s, p)
		tf = tf + s
		if tf >= frame then
			if allowframeloss then
				script.Heartbeat:Fire()
				lastframe = tick()
			else
				for i = 1, math.floor(tf / frame) do
					script.Heartbeat:Fire()
				end
				lastframe = tick()
			end
			if tossremainder then
				tf = 0
			else
				tf = tf - frame * math.floor(tf / frame)
			end
		end
	end)
	-------------------------------------------------------
	--End HeartBeat--
	-------------------------------------------------------

	function CameraEnshaking(Length, Intensity) --Took Straight from StarGlitcher!
		coroutine.resume(coroutine.create(function()
			local intensity = 1 * Intensity
			local rotM = 0.01 * Intensity
			for i = 0, Length, 0.1 do
				swait()
				intensity = intensity - 0.05 * Intensity / Length
				rotM = rotM - 5.0E-4 * Intensity / Length
				hum.CameraOffset = Vec3(radian(random(-intensity, intensity)), radian(random(-intensity, intensity)), radian(random(-intensity, intensity)))
				cam.CFrame = cam.CFrame * cFrame(radian(random(-intensity, intensity)), radian(random(-intensity, intensity)), radian(random(-intensity, intensity))) * Euler(radian(random(-intensity, intensity)) * rotM, radian(random(-intensity, intensity)) * rotM, radian(random(-intensity, intensity)) * rotM)
			end
			Humanoid.CameraOffset = Vec3(0, 0, 0)
		end))
	end

	local joyemoji = Instance.new('ParticleEmitter', tors)
	joyemoji.VelocitySpread = 2000
	joyemoji.Lifetime = NumberRange.new(1)
	joyemoji.Speed = NumberRange.new(40)
	joy= {}
	for i=0, 19 do
		joy[#joy+ 1] = NumberSequenceKeypoint.new(i/19, math.random(1, 1))
	end
	joyemoji.Size = NumberSequence.new(joy)
	joyemoji.Rate = 0
	joyemoji.LockedToPart = false
	joyemoji.LightEmission = 0
	joyemoji.Texture = "rbxassetid://1176402123"
	joyemoji.Color = ColorSequence.new(BrickColor.new("Institutional white").Color)


	local LIT = Instance.new('ParticleEmitter', tors)
	LIT.VelocitySpread = 2000
	LIT.Lifetime = NumberRange.new(1)
	LIT.Speed = NumberRange.new(45)
	nani= {}
	for i=0, 19 do
		nani[#nani+ 1] = NumberSequenceKeypoint.new(i/19, math.random(1, 1))
	end
	LIT.Size = NumberSequence.new(nani)
	LIT.Rate = 0
	LIT.LockedToPart = false
	LIT.LightEmission = 0
	LIT.Texture = "rbxassetid://1492670151"
	LIT.Color = ColorSequence.new(BrickColor.new("Institutional white").Color)

	local toast = Instance.new('ParticleEmitter', tors)
	toast.VelocitySpread = 2000
	toast.Lifetime = NumberRange.new(1)
	toast.Speed = NumberRange.new(60)
	toasterstoasttoast= {}
	for i=0, 19 do
		toasterstoasttoast[#toasterstoasttoast+ 1] = NumberSequenceKeypoint.new(i/19, math.random(1, 1))
	end
	toast.Size = NumberSequence.new(toasterstoasttoast)
	toast.Rate = 0
	toast.LockedToPart = false
	toast.LightEmission = 0
	toast.Texture = "rbxassetid://436096230"
	toast.Color = ColorSequence.new(BrickColor.new("Institutional white").Color)

	local ok = Instance.new('ParticleEmitter', tors)
	ok.VelocitySpread = 2000
	ok.Lifetime = NumberRange.new(1)
	ok.Speed = NumberRange.new(50)
	cool= {}
	for i=0, 19 do
		cool[#cool+ 1] = NumberSequenceKeypoint.new(i/19, math.random(1, 1))
	end
	ok.Size = NumberSequence.new(cool)
	ok.Rate = 0
	ok.LockedToPart = false
	ok.LightEmission = 0
	ok.Texture = "rbxassetid://636768448"
	ok.Color = ColorSequence.new(BrickColor.new("Institutional white").Color)

	-------------------------------------------------------
	--Start Kyu's shitty stuff--
	-------------------------------------------------------

	function ragdoll(model)
		local char = model
		torso = char.HumanoidRootPart
		torso2 = char.Torso
		LW.Parent = nil
		RW.Parent = nil
		LH.Parent = nil
		RH.Parent = nil
		if hum ~= nil then
			hum.PlatformStand = true
		end

		local Head = char:FindFirstChild("Head")
		if Head then
			local Neck = Instance.new("Weld")
			Neck.Name = "Neck"
			Neck.Part0 = torso
			Neck.Part1 = Head
			Neck.C0 = CFrame.new(0, 1.5, 0)
			Neck.C1 = CFrame.new()
			Neck.Parent = torso
		end
		local Limb = char:FindFirstChild("Right Arm")
		if Limb then

			Limb.CFrame = torso.CFrame * CFrame.new(1.5, 0, 0)
			local Joint = Instance.new("Glue")
			Joint.Name = "RightShoulder"
			Joint.Part0 = torso
			Joint.Part1 = Limb
			Joint.C0 = CFrame.new(1.5, 0.5, 0, 0, 0, 1, 0, 1, 0, -1, -0, -0)
			Joint.C1 = CFrame.new(-0, 0.5, 0, 0, 0, 1, 0, 1, 0, -1, -0, -0)
			Joint.Parent = torso

			local B = Instance.new("Part")
			B.TopSurface = 0
			B.BottomSurface = 0
			B.formFactor = "Symmetric"
			B.Size = Vector3.new(1, 1, 1)
			B.Transparency = 1
			B.CFrame = Limb.CFrame * CFrame.new(0, -0.5, 0)
			B.Parent = char
			local W = Instance.new("Weld")
			W.Part0 = Limb
			W.Part1 = B
			W.C0 = CFrame.new(0, -0.5, 0)
			W.Parent = Limb

		end
		local Limb = char:FindFirstChild("Left Arm")
		if Limb then

			Limb.CFrame = torso.CFrame * CFrame.new(-1.5, 0, 0)
			local Joint = Instance.new("Glue")
			Joint.Name = "LeftShoulder"
			Joint.Part0 = torso
			Joint.Part1 = Limb
			Joint.C0 = CFrame.new(-1.5, 0.5, 0, -0, -0, -1, 0, 1, 0, 1, 0, 0)
			Joint.C1 = CFrame.new(0, 0.5, 0, -0, -0, -1, 0, 1, 0, 1, 0, 0)
			Joint.Parent = torso

			local B = Instance.new("Part")
			B.TopSurface = 0
			B.BottomSurface = 0
			B.formFactor = "Symmetric"
			B.Size = Vector3.new(1, 1, 1)
			B.Transparency = 1
			B.CFrame = Limb.CFrame * CFrame.new(0, -0.5, 0)
			B.Parent = char
			local W = Instance.new("Weld")
			W.Part0 = Limb
			W.Part1 = B
			W.C0 = CFrame.new(0, -0.5, 0)
			W.Parent = Limb

		end
		local Limb = char:FindFirstChild("Right Leg")
		if Limb then

			Limb.CFrame = torso.CFrame * CFrame.new(0.5, -2, 0)
			local Joint = Instance.new("Glue")
			Joint.Name = "RightHip"
			Joint.Part0 = torso
			Joint.Part1 = Limb
			Joint.C0 = CFrame.new(0.5, -1, 0, 0, 0, 1, 0, 1, 0, -1, -0, -0)
			Joint.C1 = CFrame.new(0, 1, 0, 0, 0, 1, 0, 1, 0, -1, -0, -0)
			Joint.Parent = torso

			local B = Instance.new("Part")
			B.TopSurface = 0
			B.BottomSurface = 0
			B.formFactor = "Symmetric"
			B.Size = Vector3.new(1, 1, 1)
			B.Transparency = 1
			B.CFrame = Limb.CFrame * CFrame.new(0, -0.5, 0)
			B.Parent = char
			local W = Instance.new("Weld")
			W.Part0 = Limb
			W.Part1 = B
			W.C0 = CFrame.new(0, -0.5, 0)
			W.Parent = Limb

		end
		local Limb = char:FindFirstChild("Left Leg")
		if Limb then

			Limb.CFrame = torso.CFrame * CFrame.new(-0.5, -2, 0)
			local Joint = Instance.new("Glue")
			Joint.Name = "LeftHip"
			Joint.Part0 = torso
			Joint.Part1 = Limb
			Joint.C0 = CFrame.new(-0.5, -1, 0, -0, -0, -1, 0, 1, 0, 1, 0, 0)
			Joint.C1 = CFrame.new(-0, 1, 0, -0, -0, -1, 0, 1, 0, 1, 0, 0)
			Joint.Parent = torso

			local B = Instance.new("Part")
			B.TopSurface = 0
			B.BottomSurface = 0
			B.formFactor = "Symmetric"
			B.Size = Vector3.new(1, 1, 1)
			B.Transparency = 1
			B.CFrame = Limb.CFrame * CFrame.new(0, -0.5, 0)
			B.Parent = char
			local W = Instance.new("Weld")
			W.Part0 = Limb
			W.Part1 = B
			W.C0 = CFrame.new(0, -0.5, 0)
			W.Parent = Limb

		end
		--[
		local Bar = Instance.new("Part")
		Bar.TopSurface = 0
		Bar.BottomSurface = 0
		Bar.formFactor = "Symmetric"
		Bar.Size = Vector3.new(1, 1, 1)
		Bar.Transparency = 1
		Bar.CFrame = torso.CFrame * CFrame.new(0, 0.5, 0)
		Bar.Parent = char
		local Weld = Instance.new("Weld")
		Weld.Part0 = torso
		Weld.Part1 = Bar
		Weld.C0 = CFrame.new(0, 0.5, 0)
		Weld.Parent = torso
		--]]

		torso.CFrame = CFrame.new(torso.Position)*CFrame.Angles(math.rad(20),math.rad(torso.Orientation.Y),math.rad(torso.Orientation.Z))

	end

	-------------------------------------------------------
	--End Kyu's shitty stuff--
	-------------------------------------------------------

	-------------------------------------------------------
	--Start Important Functions--
	-------------------------------------------------------
	function swait(num)
		if num == 0 or num == nil then
			game:service("RunService").Stepped:wait(0)
		else
			for i = 0, num do
				game:service("RunService").Stepped:wait(0)
			end
		end
	end
	function thread(f)
		coroutine.resume(coroutine.create(f))
	end
	function clerp(a, b, t)
		local qa = {
			QuaternionFromCFrame(a)
		}
		local qb = {
			QuaternionFromCFrame(b)
		}
		local ax, ay, az = a.x, a.y, a.z
		local bx, by, bz = b.x, b.y, b.z
		local _t = 1 - t
		return QuaternionToCFrame(_t * ax + t * bx, _t * ay + t * by, _t * az + t * bz, QuaternionSlerp(qa, qb, t))
	end
	function QuaternionFromCFrame(cf)
		local mx, my, mz, m00, m01, m02, m10, m11, m12, m20, m21, m22 = cf:components()
		local trace = m00 + m11 + m22
		if trace > 0 then
			local s = math.sqrt(1 + trace)
			local recip = 0.5 / s
			return (m21 - m12) * recip, (m02 - m20) * recip, (m10 - m01) * recip, s * 0.5
		else
			local i = 0
			if m00 < m11 then
				i = 1
			end
			if m22 > (i == 0 and m00 or m11) then
				i = 2
			end
			if i == 0 then
				local s = math.sqrt(m00 - m11 - m22 + 1)
				local recip = 0.5 / s
				return 0.5 * s, (m10 + m01) * recip, (m20 + m02) * recip, (m21 - m12) * recip
			elseif i == 1 then
				local s = math.sqrt(m11 - m22 - m00 + 1)
				local recip = 0.5 / s
				return (m01 + m10) * recip, 0.5 * s, (m21 + m12) * recip, (m02 - m20) * recip
			elseif i == 2 then
				local s = math.sqrt(m22 - m00 - m11 + 1)
				local recip = 0.5 / s
				return (m02 + m20) * recip, (m12 + m21) * recip, 0.5 * s, (m10 - m01) * recip
			end
		end
	end
	function QuaternionToCFrame(px, py, pz, x, y, z, w)
		local xs, ys, zs = x + x, y + y, z + z
		local wx, wy, wz = w * xs, w * ys, w * zs
		local xx = x * xs
		local xy = x * ys
		local xz = x * zs
		local yy = y * ys
		local yz = y * zs
		local zz = z * zs
		return CFrame.new(px, py, pz, 1 - (yy + zz), xy - wz, xz + wy, xy + wz, 1 - (xx + zz), yz - wx, xz - wy, yz + wx, 1 - (xx + yy))
	end
	function QuaternionSlerp(a, b, t)
		local cosTheta = a[1] * b[1] + a[2] * b[2] + a[3] * b[3] + a[4] * b[4]
		local startInterp, finishInterp
		if cosTheta >= 1.0E-4 then
			if 1 - cosTheta > 1.0E-4 then
				local theta = math.acos(cosTheta)
				local invSinTheta = 1 / Sin(theta)
				startInterp = Sin((1 - t) * theta) * invSinTheta
				finishInterp = Sin(t * theta) * invSinTheta
			else
				startInterp = 1 - t
				finishInterp = t
			end
		elseif 1 + cosTheta > 1.0E-4 then
			local theta = math.acos(-cosTheta)
			local invSinTheta = 1 / Sin(theta)
			startInterp = Sin((t - 1) * theta) * invSinTheta
			finishInterp = Sin(t * theta) * invSinTheta
		else
			startInterp = t - 1
			finishInterp = t
		end
		return a[1] * startInterp + b[1] * finishInterp, a[2] * startInterp + b[2] * finishInterp, a[3] * startInterp + b[3] * finishInterp, a[4] * startInterp + b[4] * finishInterp
	end
	function rayCast(Position, Direction, Range, Ignore)
		return game:service("Workspace"):FindPartOnRay(Ray.new(Position, Direction.unit * (Range or 999.999)), Ignore)
	end

	local Create = FELOADLIBRARY.Create

	-------------------------------------------------------
	--Start Damage Function--
	-------------------------------------------------------
	function Damage(Part, hit, minim, maxim, knockback, Type, Property, Delay, HitSound, HitPitch)
		if hit.Parent == nil then
			return
		end
		local h = hit.Parent:FindFirstChildOfClass("Humanoid")
		for _, v in pairs(hit.Parent:children()) do
			if v:IsA("Humanoid") then
				h = v
			end
		end

		if h ~= nil and hit.Parent.Name ~= char.Name and hit.Parent:FindFirstChild("Torso") ~= nil then
			if hit.Parent:findFirstChild("DebounceHit") ~= nil then
				if hit.Parent.DebounceHit.Value == true then
					return
				end
			end
			local c = Create("ObjectValue"){
				Name = "creator",
				Value = game:service("Players").LocalPlayer,
				Parent = h,
			}
			game:GetService("Debris"):AddItem(c, .5)
			if HitSound ~= nil and HitPitch ~= nil then
				CFuncs.Sound.Create(HitSound, hit, 1, HitPitch) 
			end
			local Damage = math.random(minim, maxim)
			local blocked = false
			local block = hit.Parent:findFirstChild("Block")
			if block ~= nil then
				if block.className == "IntValue" then
					if block.Value > 0 then
						blocked = true
						block.Value = block.Value - 1
					end
				end
			end
			if blocked == false then
				ShowDamage((Part.CFrame * CFrame.new(0, 0, (Part.Size.Z / 2)).p + Vector3.new(0, 1.5, 0)), -Damage, 1.5, tors.BrickColor.Color)
			else
				ShowDamage((Part.CFrame * CFrame.new(0, 0, (Part.Size.Z / 2)).p + Vector3.new(0, 1.5, 0)), -Damage, 1.5, tors.BrickColor.Color)
			end
			if Type == "Knockdown" then
				local hum = hit.Parent.Humanoid
				hum.PlatformStand = true
				coroutine.resume(coroutine.create(function(HHumanoid)
					swait(1)
					HHumanoid.PlatformStand = false
				end), hum)
				local angle = (hit.Position - (Property.Position + Vector3.new(0, 0, 0))).unit
				local bodvol = Create("BodyVelocity"){
					velocity = angle * knockback,
					P = 5000,
					maxForce = Vector3.new(8e+003, 8e+003, 8e+003),
					Parent = hit,
				}
				local rl = Create("BodyAngularVelocity"){
					P = 3000,
					maxTorque = Vector3.new(500000, 500000, 500000) * 50000000000000,
					angularvelocity = Vector3.new(math.random(-10, 10), math.random(-10, 10), math.random(-10, 10)),
					Parent = hit,
				}
				game:GetService("Debris"):AddItem(bodvol, .5)
				game:GetService("Debris"):AddItem(rl, .5)
			elseif Type == "Normal" then
				local vp = Create("BodyVelocity"){
					P = 500,
					maxForce = Vector3.new(math.huge, 0, math.huge),
					velocity = Property.CFrame.lookVector * knockback + Property.Velocity / 1.05,
				}
				if knockback > 0 then
					vp.Parent = hit.Parent.Torso
				end
				game:GetService("Debris"):AddItem(vp, .5)
			elseif Type == "Up" then
				local bodyVelocity = Create("BodyVelocity"){
					velocity = Vector3.new(0, 20, 0),
					P = 5000,
					maxForce = Vector3.new(8e+003, 8e+003, 8e+003),
					Parent = hit,
				}
				game:GetService("Debris"):AddItem(bodyVelocity, .5)
			elseif Type == "DarkUp" then
				coroutine.resume(coroutine.create(function()
					for i = 0, 1, 0.1 do
						swait()
						Effects.Block.Create(BrickColor.new("Black"), hit.Parent.Torso.CFrame, 5, 5, 5, 1, 1, 1, .08, 1)
					end
				end))
				local bodyVelocity = Create("BodyVelocity"){
					velocity = Vector3.new(0, 20, 0),
					P = 5000,
					maxForce = Vector3.new(8e+003, 8e+003, 8e+003),
					Parent = hit,
				}
				game:GetService("Debris"):AddItem(bodyVelocity, 1)
			elseif Type == "Snare" then
				local bp = Create("BodyPosition"){
					P = 2000,
					D = 100,
					maxForce = Vector3.new(math.huge, math.huge, math.huge),
					position = hit.Parent.Torso.Position,
					Parent = hit.Parent.Torso,
				}
				game:GetService("Debris"):AddItem(bp, 1)
			elseif Type == "Freeze" then
				local BodPos = Create("BodyPosition"){
					P = 50000,
					D = 1000,
					maxForce = Vector3.new(math.huge, math.huge, math.huge),
					position = hit.Parent.Torso.Position,
					Parent = hit.Parent.Torso,
				}
				local BodGy = Create("BodyGyro") {
					maxTorque = Vector3.new(4e+005, 4e+005, 4e+005) * math.huge ,
					P = 20e+003,
					Parent = hit.Parent.Torso,
					cframe = hit.Parent.Torso.CFrame,
				}
				hit.Parent.Torso.Anchored = true
				coroutine.resume(coroutine.create(function(Part) 
					swait(1.5)
					Part.Anchored = false
				end), hit.Parent.Torso)
				game:GetService("Debris"):AddItem(BodPos, 3)
				game:GetService("Debris"):AddItem(BodGy, 3)
			end
			local debounce = Create("BoolValue"){
				Name = "DebounceHit",
				Parent = hit.Parent,
				Value = true,
			}
			game:GetService("Debris"):AddItem(debounce, Delay)
			c = Create("ObjectValue"){
				Name = "creator",
				Value = Player,
				Parent = h,
			}
			game:GetService("Debris"):AddItem(c, .5)
		end
	end
	-------------------------------------------------------
	--End Damage Function--
	-------------------------------------------------------

	-------------------------------------------------------
	--Start Damage Function Customization--
	-------------------------------------------------------
	function ShowDamage(Pos, Text, Time, Color)
		local Rate = (1 / 30)
		local Pos = (Pos or Vector3.new(0, 0, 0))
		local Text = (Text or "")
		local Time = (Time or 2)
		local Color = (Color or Color3.new(1, 0, 1))
		local EffectPart = CFuncs.Part.Create(workspace, "SmoothPlastic", 0, 1, BrickColor.new(Color), "Effect", Vector3.new(0, 0, 0))
		EffectPart.Anchored = true
		local BillboardGui = Create("BillboardGui"){
			Size = UDim2.new(3, 0, 3, 0),
			Adornee = EffectPart,
			Parent = EffectPart,
		}
		local TextLabel = Create("TextLabel"){
			BackgroundTransparency = 1,
			Size = UDim2.new(1, 0, 1, 0),
			Text = Text,
			Font = "Highway",
			TextColor3 = Color,
			TextScaled = true,
			Parent = BillboardGui,
		}
		game.Debris:AddItem(EffectPart, (Time))
		EffectPart.Parent = game:GetService("Workspace")
		delay(0, function()
			local Frames = (Time / Rate)
			for Frame = 1, Frames do
				wait(Rate)
				local Percent = (Frame / Frames)
				EffectPart.CFrame = CFrame.new(Pos) + Vector3.new(0, Percent, 0)
				TextLabel.TextTransparency = Percent
			end
			if EffectPart and EffectPart.Parent then
				EffectPart:Destroy()
			end
		end)
	end
	-------------------------------------------------------
	--End Damage Function Customization--
	-------------------------------------------------------

	function MagniDamage(Part, magni, mindam, maxdam, knock, Type)
		for _, c in pairs(workspace:children()) do
			local hum = c:findFirstChild("Humanoid")
			if hum ~= nil then
				local head = c:findFirstChild("Head")
				if head ~= nil then
					local targ = head.Position - Part.Position
					local mag = targ.magnitude
					if magni >= mag and c.Name ~= plr.Name then
						Damage(head, head, mindam, maxdam, knock, Type, root, 0.1, "http://www.roblox.com/asset/?id=231917784", 1.2)
					end
				end
			end
		end
	end


	CFuncs = {
		Part = {
			Create = function(Parent, Material, Reflectance, Transparency, BColor, Name, Size)
				local Part = Create("Part")({
					Parent = Parent,
					Reflectance = Reflectance,
					Transparency = Transparency,
					CanCollide = false,
					Locked = true,
					BrickColor = BrickColor.new(tostring(BColor)),
					Name = Name,
					Size = Size,
					Material = Material
				})
				RemoveOutlines(Part)
				return Part
			end
		},
		Mesh = {
			Create = function(Mesh, Part, MeshType, MeshId, OffSet, Scale)
				local Msh = Create(Mesh)({
					Parent = Part,
					Offset = OffSet,
					Scale = Scale
				})
				if Mesh == "SpecialMesh" then
					Msh.MeshType = MeshType
					Msh.MeshId = MeshId
				end
				return Msh
			end
		},
		Mesh = {
			Create = function(Mesh, Part, MeshType, MeshId, OffSet, Scale)
				local Msh = Create(Mesh)({
					Parent = Part,
					Offset = OffSet,
					Scale = Scale
				})
				if Mesh == "SpecialMesh" then
					Msh.MeshType = MeshType
					Msh.MeshId = MeshId
				end
				return Msh
			end
		},
		Weld = {
			Create = function(Parent, Part0, Part1, C0, C1)
				local Weld = Create("Weld")({
					Parent = Parent,
					Part0 = Part0,
					Part1 = Part1,
					C0 = C0,
					C1 = C1
				})
				return Weld
			end
		},
		Sound = {
			Create = function(id, par, vol, pit)
				coroutine.resume(coroutine.create(function()
					local S = Create("Sound")({
						Volume = vol,
						Pitch = pit or 1,
						SoundId = id,
						Parent = par or workspace
					})
					wait()
					S:play()
					game:GetService("Debris"):AddItem(S, 6)
				end))
			end
		},
		ParticleEmitter = {
			Create = function(Parent, Color1, Color2, LightEmission, Size, Texture, Transparency, ZOffset, Accel, Drag, LockedToPart, VelocityInheritance, EmissionDirection, Enabled, LifeTime, Rate, Rotation, RotSpeed, Speed, VelocitySpread)
				local fp = Create("ParticleEmitter")({
					Parent = Parent,
					Color = ColorSequence.new(Color1, Color2),
					LightEmission = LightEmission,
					Size = Size,
					Texture = Texture,
					Transparency = Transparency,
					ZOffset = ZOffset,
					Acceleration = Accel,
					Drag = Drag,
					LockedToPart = LockedToPart,
					VelocityInheritance = VelocityInheritance,
					EmissionDirection = EmissionDirection,
					Enabled = Enabled,
					Lifetime = LifeTime,
					Rate = Rate,
					Rotation = Rotation,
					RotSpeed = RotSpeed,
					Speed = Speed,
					VelocitySpread = VelocitySpread
				})
				return fp
			end
		}
	}
	function RemoveOutlines(part)
		part.TopSurface, part.BottomSurface, part.LeftSurface, part.RightSurface, part.FrontSurface, part.BackSurface = 10, 10, 10, 10, 10, 10
	end
	function CreatePart(FormFactor, Parent, Material, Reflectance, Transparency, BColor, Name, Size)
		local Part = Create("Part")({
			formFactor = FormFactor,
			Parent = Parent,
			Reflectance = Reflectance,
			Transparency = Transparency,
			CanCollide = false,
			Locked = true,
			BrickColor = BrickColor.new(tostring(BColor)),
			Name = Name,
			Size = Size,
			Material = Material
		})
		RemoveOutlines(Part)
		return Part
	end
	function CreateMesh(Mesh, Part, MeshType, MeshId, OffSet, Scale)
		local Msh = Create(Mesh)({
			Parent = Part,
			Offset = OffSet,
			Scale = Scale
		})
		if Mesh == "SpecialMesh" then
			Msh.MeshType = MeshType
			Msh.MeshId = MeshId
		end
		return Msh
	end
	function CreateWeld(Parent, Part0, Part1, C0, C1)
		local Weld = Create("Weld")({
			Parent = Parent,
			Part0 = Part0,
			Part1 = Part1,
			C0 = C0,
			C1 = C1
		})
		return Weld
	end


	-------------------------------------------------------
	--Start Effect Function--
	-------------------------------------------------------
	EffectModel = Instance.new("Model", char)
	Effects = {
		Block = {
			Create = function(brickcolor, cframe, x1, y1, z1, x3, y3, z3, delay, Type)
				local prt = CFuncs.Part.Create(EffectModel, "SmoothPlastic", 0, 0, brickcolor, "Effect", Vector3.new())
				prt.Anchored = true
				prt.CFrame = cframe
				local msh = CFuncs.Mesh.Create("BlockMesh", prt, "", "", Vector3.new(0, 0, 0), Vector3.new(x1, y1, z1))
				game:GetService("Debris"):AddItem(prt, 10)
				if Type == 1 or Type == nil then
					table.insert(Effects, {
						prt,
						"Block1",
						delay,
						x3,
						y3,
						z3,
						msh
					})
				elseif Type == 2 then
					table.insert(Effects, {
						prt,
						"Block2",
						delay,
						x3,
						y3,
						z3,
						msh
					})
				else
					table.insert(Effects, {
						prt,
						"Block3",
						delay,
						x3,
						y3,
						z3,
						msh
					})
				end
			end
		},
		Sphere = {
			Create = function(brickcolor, cframe, x1, y1, z1, x3, y3, z3, delay)
				local prt = CFuncs.Part.Create(EffectModel, "Neon", 0, 0, brickcolor, "Effect", Vector3.new())
				prt.Anchored = true
				prt.CFrame = cframe
				local msh = CFuncs.Mesh.Create("SpecialMesh", prt, "Sphere", "", Vector3.new(0,0,0), Vector3.new(x1, y1, z1))
				game:GetService("Debris"):AddItem(prt, 10)
				table.insert(Effects, {
					prt,
					"Cylinder",
					delay,
					x3,
					y3,
					z3,
					msh
				})
			end
		},
		Cylinder = {
			Create = function(brickcolor, cframe, x1, y1, z1, x3, y3, z3, delay)
				local prt = CFuncs.Part.Create(EffectModel, "SmoothPlastic", 0, 0, brickcolor, "Effect", Vector3.new())
				prt.Anchored = true
				prt.CFrame = cframe
				local msh = CFuncs.Mesh.Create("CylinderMesh", prt, "", "", Vector3.new(0, 0, 0), Vector3.new(x1, y1, z1))
				game:GetService("Debris"):AddItem(prt, 10)
				table.insert(Effects, {
					prt,
					"Cylinder",
					delay,
					x3,
					y3,
					z3,
					msh
				})
			end
		},
		Wave = {
			Create = function(brickcolor, cframe, x1, y1, z1, x3, y3, z3, delay)
				local prt = CFuncs.Part.Create(EffectModel, "Neon", 0, 0, brickcolor, "Effect", Vector3.new())
				prt.Anchored = true
				prt.CFrame = cframe
				local msh = CFuncs.Mesh.Create("SpecialMesh", prt, "FileMesh", "rbxassetid://20329976", Vector3.new(0, 0, 0), Vector3.new(x1 / 60, y1 / 60, z1 / 60))
				game:GetService("Debris"):AddItem(prt, 10)
				table.insert(Effects, {
					prt,
					"Cylinder",
					delay,
					x3 / 60,
					y3 / 60,
					z3 / 60,
					msh
				})
			end
		},
		Ring = {
			Create = function(brickcolor, cframe, x1, y1, z1, x3, y3, z3, delay)
				local prt = CFuncs.Part.Create(EffectModel, "SmoothPlastic", 0, 0, brickcolor, "Effect", Vector3.new())
				prt.Anchored = true
				prt.CFrame = cframe
				local msh = CFuncs.Mesh.Create("SpecialMesh", prt, "FileMesh", "rbxassetid://3270017", Vector3.new(0, 0, 0), Vector3.new(x1, y1, z1))
				game:GetService("Debris"):AddItem(prt, 10)
				table.insert(Effects, {
					prt,
					"Cylinder",
					delay,
					x3,
					y3,
					z3,
					msh
				})
			end
		},
		Break = {
			Create = function(brickcolor, cframe, x1, y1, z1)
				local prt = CFuncs.Part.Create(EffectModel, "Neon", 0, 0, brickcolor, "Effect", Vector3.new(0.5, 0.5, 0.5))
				prt.Anchored = true
				prt.CFrame = cframe * CFrame.fromEulerAnglesXYZ(math.random(-50, 50), math.random(-50, 50), math.random(-50, 50))
				local msh = CFuncs.Mesh.Create("SpecialMesh", prt, "Sphere", "", Vector3.new(0, 0, 0), Vector3.new(x1, y1, z1))
				local num = math.random(10, 50) / 1000
				game:GetService("Debris"):AddItem(prt, 10)
				table.insert(Effects, {
					prt,
					"Shatter",
					num,
					prt.CFrame,
					math.random() - math.random(),
					0,
					math.random(50, 100) / 100
				})
			end
		},
		Spiral = {
			Create = function(brickcolor, cframe, x1, y1, z1, x3, y3, z3, delay)
				local prt = CFuncs.Part.Create(EffectModel, "SmoothPlastic", 0, 0, brickcolor, "Effect", Vector3.new())
				prt.Anchored = true
				prt.CFrame = cframe
				local msh = CFuncs.Mesh.Create("SpecialMesh", prt, "FileMesh", "rbxassetid://1051557", Vector3.new(0, 0, 0), Vector3.new(x1, y1, z1))
				game:GetService("Debris"):AddItem(prt, 10)
				table.insert(Effects, {
					prt,
					"Cylinder",
					delay,
					x3,
					y3,
					z3,
					msh
				})
			end
		},
		Push = {
			Create = function(brickcolor, cframe, x1, y1, z1, x3, y3, z3, delay)
				local prt = CFuncs.Part.Create(EffectModel, "SmoothPlastic", 0, 0, brickcolor, "Effect", Vector3.new())
				prt.Anchored = true
				prt.CFrame = cframe
				local msh = CFuncs.Mesh.Create("SpecialMesh", prt, "FileMesh", "rbxassetid://437347603", Vector3.new(0, 0, 0), Vector3.new(x1, y1, z1))
				game:GetService("Debris"):AddItem(prt, 10)
				table.insert(Effects, {
					prt,
					"Cylinder",
					delay,
					x3,
					y3,
					z3,
					msh
				})
			end
		}
	}
	-------------------------------------------------------
	--End Effect Function--
	-------------------------------------------------------

	function CreateSound(ID, PARENT, VOLUME, PITCH) --Very important.
		local NSound = nil
		coroutine.resume(coroutine.create(function()
			NSound = Instance.new("Sound", PARENT)
			NSound.Volume = VOLUME
			NSound.Pitch = PITCH
			NSound.SoundId = "http://www.roblox.com/asset/?id="..ID
			swait()
			NSound:play()
			game:GetService("Debris"):AddItem(NSound, 10)
		end))
		return NSound
	end





	-------------------------------------------------------
	--End Important Functions--
	-------------------------------------------------------

	chargeup = Instance.new("Sound", hed)
	chargeup.SoundId = "http://www.roblox.com/asset/?id=527276541"
	chargeup.Volume = 10
	chargeup.Pitch = 1
	chargeup.Looped = true
	chargeup.TimePosition = 1

	meme = Instance.new("Sound", hed)
	meme.SoundId = "http://www.roblox.com/asset/?id=291151190"
	meme.Volume = 10
	meme.Pitch = 1
	meme.Looped = true
	meme.TimePosition = 1

	local ohno = Instance.new("Sound")
	ohno.Parent = hed
	ohno.Volume = 10
	ohno.Pitch = 1
	ohno.Looped = true

	local bass = Instance.new("Sound") --why
	bass.Parent = hed
	bass.Volume = 7
	bass.Pitch = 1
	bass.SoundId = "http://www.roblox.com/asset/?id=1087356234"
	bass.Looped = true

	Cause_Im_having_a_good_time_having_a_good_time = Instance.new("Sound", hed) --DONT STOP ME NOOOOOOOOOWWWWWWWW
	Cause_Im_having_a_good_time_having_a_good_time.SoundId = "http://www.roblox.com/asset/?id=672104253"
	Cause_Im_having_a_good_time_having_a_good_time.Volume = 10
	Cause_Im_having_a_good_time_having_a_good_time.Pitch = 1
	Cause_Im_having_a_good_time_having_a_good_time.Looped = false
	Cause_Im_having_a_good_time_having_a_good_time.TimePosition = 35.3

	STHAP = Instance.new("Sound", hed)
	STHAP.SoundId = "http://www.roblox.com/asset/?id=1591656314"
	STHAP.Volume = 10
	STHAP.Pitch = 1
	STHAP.Looped = false

	forevergone = Instance.new("Sound", tors)
	forevergone.SoundId = "http://www.roblox.com/asset/?id=1286436928"
	forevergone.Volume = 10
	forevergone.Pitch = 1
	forevergone.Looped = true
	forevergone.TimePosition = 24

	-------------------------------------------------------
	--Start Music Option--
	-------------------------------------------------------
	local Music = Instance.new("Sound",tors)
	Music.Volume = 2.5
	Music.SoundId = "rbxassetid://"
	Music.Looped = true
	Music.Pitch = 1 --Pitcher
	Music:Play()
	-------------------------------------------------------
	--End Music Option--
	-------------------------------------------------------
	--hi fat >:)
	-------------------------------------------------------
	--Start Attacks N Stuff--
	-------------------------------------------------------
	local sine=0
	function HitboxFunction(Pose, lifetime, siz1, siz2, siz3, Radie, Min, Max, kb, atype)
		local Hitboxpart = Instance.new("Part", EffectModel)
		RemoveOutlines(Hitboxpart)
		Hitboxpart.Size = Vector3.new(siz1, siz2, siz3)
		Hitboxpart.CanCollide = false
		Hitboxpart.Transparency = 1
		Hitboxpart.Anchored = true
		Hitboxpart.CFrame = Pose
		game:GetService("Debris"):AddItem(Hitboxpart, lifetime)
		MagniDamage(Hitboxpart, Radie, Min, Max, kb, atype)
	end
	function GEtOuT()
		attack = true
		hum.WalkSpeed = 10
		Character.Head.face.Texture = "rbxassetid://494811799"
		CreateSound("814652778", hed, 10, 1)
		CreateSound("537371462", hed, 10, 1)
		local vel3 = Instance.new("BodyVelocity",tors)
		vel3.Velocity = Vector3.new(0,25,0)
		vel3.MaxForce = Vector3.new(10000000,10000000,10000000)
		for i = 0,12,0.1 do
			swait()
			CameraEnshaking(1, 2)
			HitboxFunction(ll.CFrame, 0.01, 1, 1, 1, 7, 20, 99, 53, "Knockdown")
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(0-255.45*i)), 0.3)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(-40), Rad(0), Rad(0)), 0.3)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5, 0) * angles(Rad(30), Rad(0), Rad(20)), 0.3)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5, 0) * angles(Rad(-20), Rad(0), Rad(-30)), 0.3)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 * Cos(sine / 20), -0.3) * LHCF * angles(Rad(-5), Rad(0), Rad(20)), 0.15)
			RH.C0 = clerp(RH.C0, CF(1, -1, 0.3) * angles(Rad(0), Rad(90), Rad(-20)), 0.3)
		end
		vel3:Destroy()
		Character.Head.face.Texture = "rbxassetid://620619801"
		attack = false
		Humanoid.JumpPower = 50
		hum.WalkSpeed = 16
	end

	function GEtOuT2()
		attack = true
		hum.WalkSpeed = 10
		Humanoid.JumpPower = 0
		Character.Head.face.Texture = "rbxassetid://494811799"
		CreateSound("814652778", hed, 10, 1)
		CreateSound("537371462", hed, 10, 1)
		root.Velocity = root.CFrame.lookVector * 20
		for i = 0,12,0.1 do
			swait()
			CameraEnshaking(1, 2)
			root.Velocity = root.CFrame.lookVector * 50
			HitboxFunction(ll.CFrame, 0.01, 1, 1, 1, 7, 10, 50, 53, "Knockdown")
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1 * Cos(sine / 20)) * angles(Rad(90), Rad(0), Rad(0-255.45*i)), 0.3)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(-40), Rad(0), Rad(0)), 0.3)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5, 0) * angles(Rad(30), Rad(0), Rad(20)), 0.3)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5, 0) * angles(Rad(-20), Rad(0), Rad(-30)), 0.3)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 * Cos(sine / 20), -0.3) * LHCF * angles(Rad(-5), Rad(0), Rad(20)), 0.15)
			RH.C0 = clerp(RH.C0, CF(1, -1, 0.3) * angles(Rad(0), Rad(90), Rad(-20)), 0.3)
		end
		Character.Head.face.Texture = "rbxassetid://620619801"
		attack = false
		Humanoid.JumpPower = 50
		hum.WalkSpeed = 16
	end
	function Flight() --wowthatsdiffrent
		attack = true
		Character.Head.face.Texture = "rbxassetid://269748407"
		local ColorsArray ={ColorSequenceKeypoint.new(0, Color3.new(1,0,0)),
			ColorSequenceKeypoint.new(0.16, Color3.new(1,1,1)),
			ColorSequenceKeypoint.new(0.32, Color3.new(0,0,1)),
			ColorSequenceKeypoint.new(0.48, Color3.new(1,1,1)),
			ColorSequenceKeypoint.new(0.64, Color3.new(1,0,0)),
			ColorSequenceKeypoint.new(0.80, Color3.new(1,1,1)),
			ColorSequenceKeypoint.new(0.96, Color3.new(0,0,1)),
			ColorSequenceKeypoint.new(1, Color3.new(1,1,1))}
		local vel4 = Instance.new("BodyVelocity",ll)
		vel4.Velocity = Vector3.new(0,4,0)
		vel4.MaxForce = Vector3.new(10000000,10000000,10000000)
		local Atch3 = Instance.new("Attachment",ll)Atch3.Position = Vector3.new(0,0.6,0)
		local Atch4 = Instance.new("Attachment",ll)Atch4.Position = Vector3.new(0,-0.6,0)
		local Trail2 = Instance.new("Trail",ll)Trail2.Attachment0 = Atch3 Trail2.Attachment1 = Atch4
		Trail2.Texture = "rbxassetid://22636887" Trail2.Lifetime = 0.2 Trail2.Transparency = NumberSequence.new({NumberSequenceKeypoint.new(0,0,0),NumberSequenceKeypoint.new(1,0,0)})
		Trail2.Color = ColorSequence.new(ColorsArray) Trail2.LightEmission = 1 
		Trail2.Enabled = true
		local Atch5 = Instance.new("Attachment",rl)Atch5.Position = Vector3.new(0,0.6,0)
		local Atch6 = Instance.new("Attachment",rl)Atch6.Position = Vector3.new(0,-0.6,0)
		local Trail3 = Instance.new("Trail",rl)Trail3.Attachment0 = Atch5 Trail3.Attachment1 = Atch6
		Trail3.Texture = "rbxassetid://22636887" Trail3.Lifetime = 0.2 Trail3.Transparency = NumberSequence.new({NumberSequenceKeypoint.new(0,0,0),NumberSequenceKeypoint.new(1,0,0)})
		Trail3.Color = ColorSequence.new(ColorsArray) Trail3.LightEmission = 1 
		Trail3.Enabled = true
		local Atch7 = Instance.new("Attachment",ra)Atch7.Position = Vector3.new(0,0.6,0)
		local Atch8 = Instance.new("Attachment",ra)Atch8.Position = Vector3.new(0,-0.6,0)
		local Trail4 = Instance.new("Trail",ra)Trail4.Attachment0 = Atch7 Trail4.Attachment1 = Atch8
		Trail4.Texture = "rbxassetid://22636887" Trail4.Lifetime = 0.2 Trail4.Transparency = NumberSequence.new({NumberSequenceKeypoint.new(0,0,0),NumberSequenceKeypoint.new(1,0,0)})
		Trail4.Color = ColorSequence.new(ColorsArray) Trail4.LightEmission = 1 
		Trail4.Enabled = true
		local Atch9 = Instance.new("Attachment",la)Atch9.Position = Vector3.new(0,0.6,0)
		local Atch10 = Instance.new("Attachment",la)Atch10.Position = Vector3.new(0,-0.6,0)
		local Trail5 = Instance.new("Trail",la)Trail5.Attachment0 = Atch9 Trail5.Attachment1 = Atch10
		Trail5.Texture = "rbxassetid://22636887" Trail5.Lifetime = 0.2 Trail5.Transparency = NumberSequence.new({NumberSequenceKeypoint.new(0,0,0),NumberSequenceKeypoint.new(1,0,0)})
		Trail5.Color = ColorSequence.new(ColorsArray) Trail5.LightEmission = 1 
		Trail5.Enabled = true
		local Atch1 = Instance.new("Attachment",Torso)Atch1.Position = Vector3.new(0,2,0)
		local Atch2 = Instance.new("Attachment",Torso)Atch2.Position = Vector3.new(0,-2.5,0)
		local Trail = Instance.new("Trail",Torso)Trail.Attachment0 = Atch1 Trail.Attachment1 = Atch2
		Trail.Texture = "rbxassetid://22636887" Trail.Lifetime = 0.2 Trail.Transparency = NumberSequence.new({NumberSequenceKeypoint.new(0,0,0),NumberSequenceKeypoint.new(1,0,0)})
		Trail.Color = ColorSequence.new(ColorsArray) Trail.LightEmission = 1 
		Trail.Enabled = false
		ragdoll(char)
		wait(1)
		Character.Head.face.Texture = "rbxassetid://249062487"
		CreateSound("948494432", hed, 10, 1)
		wait(2)
		Character.Head.face.Texture = "rbxassetid://269748407"
		CreateSound("633394595", hed, 10, 1)
		wait(2)
		Character.Head.face.Texture = "rbxassetid://494811799"
		STHAP:play()
		wait(11)
		forevergone:play()
	end

	function OBJECTION()
		attack = true
		hum.WalkSpeed = 10
		Character.Head.face.Texture = "rbxassetid://55831869"
		CreateSound("330859085", hed, 10, 1)
		for i = 0,8,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.2) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(180), Rad(0), Rad(5)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(-5)), 0.1)
		end
		attack = false
		Character.Head.face.Texture = "rbxassetid://620619801"
		hum.WalkSpeed = 16
	end

	function Hello()
		attack = true
		hum.WalkSpeed = 10
		Character.Head.face.Texture = "rbxassetid://334668738"
		CreateSound("855338765", hed, 10, 0.9)
		for i = 0,3,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.2) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(0)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(180), Rad(20), Rad(-5)), 0.1)
		end
		attack = false
		Character.Head.face.Texture = "rbxassetid://620619801"
		hum.WalkSpeed = 16
	end

	function Victory()
		attack = true
		hum.WalkSpeed = 1.01
		Character.Head.face.Texture = "rbxassetid://616284160"
		Humanoid.Jump = true
		CreateSound("130834939", hed, 10, 1)
		for i = 0,3.7,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.2) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(-40)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(-40)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(0)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 1 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(180), Rad(20), Rad(-5)), 0.1)
		end
		Humanoid.Jump = true
		for i = 0,3.7,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.2) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(40)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(40)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 1 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(-180), Rad(-25), Rad(5)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 1 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(-0)), 0.1)
		end
		Humanoid.Jump = true
		for i = 0,3.7,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.2) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(-40)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(-40)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(0)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 1 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(180), Rad(20), Rad(-5)), 0.1)
		end
		Humanoid.Jump = true
		for i = 0,3.7,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.2) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(40)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(40)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 1 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(-180), Rad(-25), Rad(5)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 1 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(-0)), 0.1)
		end
		Humanoid.Jump = true
		for i = 0,3.7,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.2) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(-40)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(-40)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(0)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 1 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(180), Rad(20), Rad(-5)), 0.1)
		end
		attack = false
		Character.Head.face.Texture = "rbxassetid://620619801"
		hum.WalkSpeed = 16
	end

	function ShutTheHellUp()
		attack = true
		hum.WalkSpeed = 2.01
		Character.Head.face.Texture = "rbxassetid://963148419"
		CreateSound("336377340", hed, 10, 1)
		for i = 0,3,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(90), Rad(0), Rad(5)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(-5)), 0.1)
		end
		for i = 0,1.2,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(20), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(90), Rad(0), Rad(5)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(-5)), 0.1)
		end
		for i = 0,1.2,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(-5), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(90), Rad(0), Rad(5)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(-5)), 0.1)
		end
		for i = 0,1.2,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.2) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(20), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(90), Rad(0), Rad(5)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(-5)), 0.1)
		end
		for i = 0,1.2,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.2) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(-5), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(90), Rad(0), Rad(5)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(-5)), 0.1)
		end
		for i = 0,2,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(120), Rad(0), Rad(5)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(-5)), 0.1)
		end
		for i = 0,2,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(90), Rad(0), Rad(5)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(-5)), 0.1)
		end
		hum.WalkSpeed = 16
		Character.Head.face.Texture = "rbxassetid://620619801"
		attack = false
	end

	function SpinMeDad() --YOU SPIN ME RIGHT ROUND BABY RIGHT ROUND
		attack = true
		hum.WalkSpeed = 5
		Humanoid.JumpPower = 175
		Character.Head.face.Texture = "rbxassetid://1223903433"
		CreateSound("145799973", hed, 10, 1)
		local vel2 = Instance.new("BodyVelocity",tors)
		vel2.Velocity = Vector3.new(0,1.2,0)
		vel2.MaxForce = Vector3.new(10000000,10000000,10000000)
		for i = 0,60,0.1 do
			HitboxFunction(ll.CFrame, 0.01, 1, 1, 1, 7, 5, 20, 53, "Knockdown")
			swait()
			CameraEnshaking(1, 1)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0-255.45*i)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(90)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(-90)), 0.1)
		end
		hum.WalkSpeed = 16
		vel2:Destroy()
		Character.Head.face.Texture = "rbxassetid://620619801"
		Humanoid.JumpPower = 50
		attack = false
	end

	function EndMySufferingV2() --why
		attack = true
		hum.WalkSpeed = 1.01
		Character.Head.face.Texture = "rbxassetid://202210455"
		local A = math.random(1,5)
		if A == 1 then
			meme.SoundId = "rbxassetid://295810519"
		end
		if A == 2 then
			meme.SoundId = "rbxassetid://1124778077"
		end
		if A == 3 then
			meme.SoundId = "rbxassetid://464157070"
		end
		if A == 4 then
			meme.SoundId = "rbxassetid://146334595"
		end
		if A == 5 then
			meme.SoundId = "rbxassetid://145536915"
		end
		meme:Play()
		bass:Play()
		joyemoji.Rate = 70
		LIT.Rate = 70
		ok.Rate = 70
		toast.Rate = 70

		for i = 0,50,0.1 do
			swait()
			CameraEnshaking(1, 10)
			bass.Parent = hed
			meme.Parent = hed
			rootj.C0=clerp(rootj.C0,RootCF*CF(0,0,-0.1+0.1*math.cos(sine/20))*angles(math.rad(15),math.rad(-10),math.rad(0)),0.15)
			tors.Neck.C0=clerp(tors.Neck.C0,necko*angles(math.rad(35),math.rad(0),math.rad(0)),.3)
			RH.C0=clerp(RH.C0,CF(1,-.9-0.1*math.cos(sine/20),.025*math.cos(sine/20))*RHCF*angles(math.rad(-5),math.rad(0),math.rad(0)),0.15)
			LH.C0=clerp(LH.C0,CF(-1,-.9-0.1*math.cos(sine/20),.025*math.cos(sine/20))*LHCF*angles(math.rad(-5),math.rad(-0),math.rad(-20)),0.15)
			RW.C0 = clerp(RW.C0, CFrame.new(1.1, 0.5+0.1*math.sin(sine/30), -0.6) * angles(math.rad(-0), math.rad(10), math.rad(-110)), 0.1)
			LW.C0 = clerp(LW.C0, CFrame.new(-1.5, 0.5+0.1*math.sin(sine/30), 0.055*math.cos(sine/20)) * angles(math.rad(-0), math.rad(-10), math.rad(-105)), 0.1)
		end
		bass:Stop()
		meme:Stop()
		joyemoji.Rate = 0
		LIT.Rate = 0
		ok.Rate = 0
		toast.Rate = 0
		Character.Head.face.Texture = "rbxassetid://620619801"
		attack = false
		hum.WalkSpeed = 16
	end

	function HELP()
		attack = true
		hum.WalkSpeed = 1.01
		Character.Head.face.Texture = "rbxassetid://307972876"
		CreateSound("1123321019", hed, 10, 1)
		for i = 0,15,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(0.7, -0.01 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-0.7, -0.01 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(0.9, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(0)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-0.9, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(0)), 0.1)
		end
		CreateSound("198462271", hed, 10, 1)
		for i = 0,8,0.1 do
			Character.Head.face.Texture = "rbxassetid://341497730"
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(0.7, -0.01 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-0.7, -0.01 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(0.9, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(0)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-0.9, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(0)), 0.1)
		end
		for i = 0,8,0.1 do
			Character.Head.face.Texture = "rbxassetid://341497730"
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(60), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(0.7, -0.01 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-0.7, -0.01 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(0.9, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(0)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-0.9, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(0)), 0.1)
		end
		CreateSound("948494432", hed, 10, 1)
		for i = 0,7.5,0.1 do
			Character.Head.face.Texture = "rbxassetid://249062487"
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(60), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(0.7, -0.01 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-0.7, -0.01 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(0.9, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(0)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-0.9, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(0)), 0.1)
		end
		CreateSound("1542642349", hed, 10, 1)
		for i = 0,10,0.1 do
			Character.Head.face.Texture = "rbxassetid://270636807"
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(0.7, -0.01 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-0.7, -0.01 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(0.9, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(0)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-0.9, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(0)), 0.1)
		end
		CreateSound("269597232", hed, 10, 1)
		for i = 0,6,0.1 do
			Character.Head.face.Texture = "rbxassetid://265057155"
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(0.7, -0.01 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-0.7, -0.01 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(0.9, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(0)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-0.9, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(0)), 0.1)
		end
		attack = false
		Character.Head.face.Texture = "rbxassetid://620619801"
		hum.WalkSpeed = 16
	end

	function Choose()
		attack = true
		hum.WalkSpeed = 1.01
		Character.Head.face.Texture = "rbxassetid://374187112"
		CreateSound("130784263", hed, 10, 1)
		for i = 0,4,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(110), Rad(0), Rad(0)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(110), Rad(0), Rad(0)), 0.1)
		end
		for i = 0,5,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(35), Rad(0), Rad(-10)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(35), Rad(0), Rad(10)), 0.1)
		end
		attack = false
		Character.Head.face.Texture = "rbxassetid://620619801"
		hum.WalkSpeed = 16
	end

	function slap()
		attack = true
		hum.WalkSpeed = 10
		CreateSound("146163534", hed, 10, 1)
		Character.Head.face.Texture = "rbxassetid://293603561"
		CameraEnshaking(1, 2)
		for i = 0,4,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(20), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(20), Rad(0), Rad(5)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(115 + 4), Rad(45), Rad(50)), 0.1)
		end
		Character.Head.face.Texture = "rbxassetid://620619801"
		attack = false
		hum.WalkSpeed = 16
	end

	function MYSPAGHETTTTTTT() --ow
		attack = true
		hum.WalkSpeed = 1.01
		CreateSound("1282149571", hed, 10, 1)
		Character.Head.face.Texture = "rbxassetid://1329282756"
		CameraEnshaking(1, 2.2)
		for i = 0,4,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(20), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(20), Rad(0), Rad(5)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(115 + 4), Rad(45), Rad(50)), 0.1)
		end
		for i = 0,5,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(110), Rad(0), Rad(0)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(110), Rad(0), Rad(0)), 0.1)
		end
		for i = 0,6,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(35), Rad(0), Rad(-10)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(35), Rad(0), Rad(10)), 0.1)
		end
		attack = false
		Character.Head.face.Texture = "rbxassetid://620619801"
		hum.WalkSpeed = 16
	end


	function dead()
		attack = true
		hum.WalkSpeed = 0.20
		CreateSound("137225991", hed, 10, 1)
		Character.Head.face.Texture = "rbxassetid://297512410"
		for i = 0,1.1,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(-0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(90)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(-90)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 1 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(140)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 1 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(-140)), 0.1)
		end
		for i = 0,1.1,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(90), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(-0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(90)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(-90)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 1 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(140)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 1 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(-140)), 0.1)
		end
		for i = 0,1.1,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(180), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(-0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(90)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(-90)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 1 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(140)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 1 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(-140)), 0.1)
		end
		for i = 0,1.1,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(270), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(-0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(90)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(-90)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 1 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(140)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 1 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(-140)), 0.1)
		end
		for i = 0,1.1,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(-0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(90)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(-90)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 1 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(140)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 1 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(-140)), 0.1)
		end
		for i = 0,1.1,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(90), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(-0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(90)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(-90)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 1 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(140)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 1 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(-140)), 0.1)
		end
		for i = 0,1.1,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(180), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(-0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(90)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(-90)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 1 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(140)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 1 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(-140)), 0.1)
		end
		for i = 0,1.1,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(270), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(-0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(90)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(-90)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 1 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(140)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 1 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(-140)), 0.1)
		end
		for i = 0,1.1,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(-0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(90)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(-90)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 1 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(140)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 1 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(-140)), 0.1)
		end
		Character.Head.face.Texture = "rbxassetid://273309187"
		for i = 0,9,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -2.59 + 0.1) * angles(Rad(-90), Rad(90), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(-0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(-0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(30)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(-30)), 0.1)
		end
		attack = false
		Character.Head.face.Texture = "rbxassetid://620619801"
		hum.WalkSpeed = 16
	end

	function hap() --much hap
		attack = true
		hum.WalkSpeed = 0.10
		CreateSound("363808674", hed, 10, 1)
		Character.Head.face.Texture = "rbxassetid://315792941"
		for i = 0,12,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(-0), Rad(0), Rad(180)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(0)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(-0)), 0.1)
		end
		CreateSound("233168827", hed, 10, 1)
		Character.Head.face.Texture = "rbxassetid://335761015"
		for i = 0,10,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(-0), Rad(0), Rad(180)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(0)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(-0)), 0.1)
		end
		CreateSound("363808674", hed, 10, 1)
		attack = false
		Character.Head.face.Texture = "rbxassetid://620619801"
		hum.WalkSpeed = 16
	end

	function HAAAAA() --KONO POWA
		attack = true
		hum.WalkSpeed = 1.01
		Character.Head.face.Texture = "rbxassetid://305068389"
		chargeup.Pitch = 1
		for i = 0,7,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 1 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(150), Rad(0), Rad(0)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 1 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(150), Rad(0), Rad(-0)), 0.1)
		end
		Character.Head.face.Texture = "rbxassetid://313921371"
		chargeup:play()
		for i = 0,30,0.1 do
			swait()
			CameraEnshaking(1, 2)
			chargeup.Parent = hed
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(15), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1.1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-20), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1.1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-20), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.4, 0.0000000005 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(150), Rad(0), Rad(0)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.4, 0.0000000005 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(150), Rad(0), Rad(-0)), 0.1)
		end
		chargeup:stop()
		chargeup.Pitch = 1.1
		chargeup.TimePosition = 1
		chargeup:play()
		Character.Head.face.Texture = "rbxassetid://304942859"
		for i, v in pairs(c:children()) do
			if v.ClassName == "Part" then
				local tra = trazx:clone()
				tra.Parent = v
				tra.LightEmission = 1
				tra.Color = ColorSequence.new(Color3.new(0, 0.6666666666666666, 1))
				tra.Rate = 15
				tra.Rotation = NumberRange.new(-5, 5)
				tra.Lifetime = NumberRange.new(1.5, 2)
				tra.Size = NumberSequence.new({
					NumberSequenceKeypoint.new(0, 0.1, 0),
					NumberSequenceKeypoint.new(1, 0, 0)
				})
				tra.Transparency = NumberSequence.new({
					NumberSequenceKeypoint.new(0, 1, 0),
					NumberSequenceKeypoint.new(0.135, 0, 0),
					NumberSequenceKeypoint.new(0.875, 0, 0),
					NumberSequenceKeypoint.new(1, 1, 0)
				})
				tra.Speed = NumberRange.new(0.5)
				tra.VelocitySpread = 360
				tra.VelocityInheritance = 0.5
				tra.ZOffset = 2
				tra.Acceleration = Vector3.new(0, 2.5, 0)
			end
		end
		local tra = trazx:clone()
		tra.Parent = c.HumanoidRootPart
		tra.Texture = "rbxassetid://347730682"
		tra.LightEmission = 0.8
		tra.Color = ColorSequence.new(Color3.new(0, 0.6666666666666666, 1))
		tra.Rate = 250
		tra.Rotation = NumberRange.new(-5, 5)
		tra.Lifetime = NumberRange.new(0.75)
		tra.Size = NumberSequence.new({
			NumberSequenceKeypoint.new(0, 4.81, 0.875),
			NumberSequenceKeypoint.new(1, 2.13, 0.875)
		})
		tra.Transparency = NumberSequence.new({
			NumberSequenceKeypoint.new(0, 1, 0),
			NumberSequenceKeypoint.new(0.0399, 0.85, 0),
			NumberSequenceKeypoint.new(0.394, 0.9, 0),
			NumberSequenceKeypoint.new(0.699, 1, 0),
			NumberSequenceKeypoint.new(1, 1, 0)
		})
		tra.Speed = NumberRange.new(15)
		tra.VelocitySpread = 360
		tra.VelocityInheritance = 0.5
		tra.ZOffset = 3.5
		tra.Acceleration = Vector3.new(0, 25, 0)
		for i = 0,35,0.1 do
			swait()
			ohno.Parent = hed
			CameraEnshaking(1, 3)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(60), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1.1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-20), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1.1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-20), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.4, 0.0000000005 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(150), Rad(0), Rad(0)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.4, 0.0000000005 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(150), Rad(0), Rad(-0)), 0.1)
		end
		chargeup:stop()
		chargeup.Pitch = 1.3
		chargeup.TimePosition = 1
		chargeup:play()
		tra:Destroy()
		tra:Destroy()
		Character.Head.face.Texture = "rbxassetid://280233855"
		local tra = trazx:clone()
		tra.Parent = c.HumanoidRootPart
		tra.Texture = "rbxassetid://347730682"
		tra.LightEmission = 0.8
		tra.Color = ColorSequence.new(Color3.new(1, 0, 0))
		tra.Rate = 250
		tra.Rotation = NumberRange.new(-5, 5)
		tra.Lifetime = NumberRange.new(0.3)
		tra.Size = NumberSequence.new({
			NumberSequenceKeypoint.new(0, 8, 0.875),
			NumberSequenceKeypoint.new(1, 10, 0.875)
		})
		tra.Transparency = NumberSequence.new({
			NumberSequenceKeypoint.new(0, 1, 0),
			NumberSequenceKeypoint.new(0.0399, 0.531, 0),
			NumberSequenceKeypoint.new(0.394, 0.906, 0),
			NumberSequenceKeypoint.new(0.699, 1, 0),
			NumberSequenceKeypoint.new(1, 1, 0)
		})
		for i = 0,32,0.1 do
			swait()
			CameraEnshaking(1, 5)
			chargeup.Parent = hed
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(-65), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1.1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-20), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1.1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-20), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.4, 0.0000000005 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(150), Rad(0), Rad(0)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.4, 0.0000000005 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(150), Rad(0), Rad(-0)), 0.1)
		end
		chargeup:stop()
		CreateSound("681582832", hed, 10, 1)
		game.Players.LocalPlayer.Character:BreakJoints()
		local S = Instance.new("Explosion",workspace)    
		S.Position = tors.Position
		S.BlastPressure = 9
		S.BlastRadius = 30
		S.ExplosionType = 0
		attack = false
		hum.WalkSpeed = 16
		Character.Head.face.Texture = "rbxassetid://295197013"
		tra:Destroy()
		CameraEnshaking(4, 30)
		error("WARNING, TO MUCH ENERGY.")
	end

	function NEN()
		attack = true
		hum.WalkSpeed = 1.01
		CreateSound("230292011", hed, 10, 1)
		Character.Head.face.Texture = "rbxassetid://705269463"
		for i = 0,4,0.1 do
			swait()
			CameraEnshaking(1, 3)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(-90), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(120)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(-120)), 0.1)
		end
		attack = false
		Character.Head.face.Texture = "rbxassetid://620619801"
		hum.WalkSpeed = 16
	end

	function FLYSKYHIGH()
		attack = true
		timetofly = false
		hum.WalkSpeed = 0.05
		Character.Head.face.Texture = "rbxassetid://705269463"
		Cause_Im_having_a_good_time_having_a_good_time:Play()
		Cause_Im_having_a_good_time_having_a_good_time.TimePosition = 35.3
		Humanoid.JumpPower = 0
		for i = 0,300,0.1 do --thatsalongtime
			swait()
			CameraEnshaking(1, 7)
			HitboxFunction(ll.CFrame, 0.01, 1, 1, 1, 7, 75, 500, 100, "Knockdown")
			Cause_Im_having_a_good_time_having_a_good_time.Parent = hed
			root.Velocity = root.CFrame.lookVector * 225
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(-0-255.45*i), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0-255.45*i)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0-255.45*i)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(-75), Rad(0), Rad(0)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(-75), Rad(0), Rad(0)), 0.1)
		end
		Cause_Im_having_a_good_time_having_a_good_time:Stop()
		attack = false
		Humanoid.JumpPower = 50
		Character.Head.face.Texture = "rbxassetid://620619801"
		hum.WalkSpeed = 16
		wait(45)
		timetofly = true
		warn("You can FLY SKY HIGH Now! Go Nuts!") --please dont go nuts
	end


	function highnoon()
		attack = true
		hum.WalkSpeed = 1.01
		CreateSound("495316660", hed, 10, 1)
		Character.Head.face.Texture = "rbxassetid://155195214"
		CameraEnshaking(2, 4)
		local Blobby = Instance.new("Part", char)
		Blobby.Name = "Blob"
		Blobby.CanCollide = false
		Blobby.BrickColor = BrickColor.new("Really black")
		Blobby.Transparency = 0
		Blobby.Material = "Plastic"
		Blobby.Size = Vector3.new(1, 1, 2)
		Blobby.TopSurface = Enum.SurfaceType.Smooth
		Blobby.BottomSurface = Enum.SurfaceType.Smooth

		local Weld = Instance.new("Weld", Blobby)
		Weld.Part0 = ra
		Weld.Part1 = Blobby
		Weld.C1 = CFrame.new(0, -.4, -1.6) *angles(Rad(180), Rad(0), Rad(180))
		Weld.C0 = CFrame.Angles(math.rad(-90),0,0)

		local M2 = Instance.new("SpecialMesh")
		M2.Parent = Blobby
		M2.MeshId = "http://www.roblox.com/asset/?id=432256490"
		M2.TextureId = "http://www.roblox.com/asset/?id=432256526"
		M2.Scale = Vector3.new(.002, .002, .002)
		for i = 0,7.75,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(90)), 0.2)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(30), Rad(0), Rad(0)), 0.2)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.2)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.2)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(-.6), Rad(180)), 0.2)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(-45), Rad(-.6), Rad(136 - 4.5 * Sin(sine / 20))), 0.2)
		end
		for i = 0,16.5,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(90)), 0.2)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(30), Rad(0), Rad(0)), 0.2)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.2)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.2)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(-.6), Rad(90)), 0.2)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(-45), Rad(-.6), Rad(136 - 4.5 * Sin(sine / 20))), 0.2)
		end
		Blobby.Transparency = 1
		Blobby:Destroy()
		attack = false
		Character.Head.face.Texture = "rbxassetid://620619801"
		hum.WalkSpeed = 16
	end

	function somuchcancerwhy() --o no
		attack = true
		hum.WalkSpeed = 0.10
		Character.Head.face.Texture = "rbxassetid://315074049"
		local A = math.random(1,13)
		if A == 1 then
			ohno.SoundId = "rbxassetid://295810519"
			ohno.TimePosition = 1
		end
		if A == 2 then
			ohno.SoundId = "rbxassetid://488472970"
			ohno.TimePosition = 2
		end
		if A == 3 then
			ohno.SoundId = "rbxassetid://917045199"
			ohno.TimePosition = 3
		end
		if A == 4 then
			ohno.SoundId = "rbxassetid://324205173"
			ohno.TimePosition = 1
		end
		if A == 5 then
			ohno.SoundId = "rbxassetid://376134741"
			ohno.TimePosition = 8
		end
		if A == 6 then
			ohno.SoundId = "rbxassetid://164147183"
			ohno.TimePosition = 0
		end
		if A == 7 then
			ohno.SoundId = "rbxassetid://825526716"
			ohno.TimePosition = 1
		end
		if A == 8 then
			ohno.SoundId = "rbxassetid://185460366"
			ohno.TimePosition = 0
		end
		if A == 9 then
			ohno.SoundId = "rbxassetid://273319633"
			ohno.TimePosition = 1
		end
		if A == 10 then
			ohno.SoundId = "rbxassetid://506212392"
			ohno.TimePosition = 2
		end
		if A == 11 then
			ohno.SoundId = "rbxassetid://708297448"
			ohno.TimePosition = 4
		end
		if A == 12 then
			ohno.SoundId = "rbxassetid://497199103"
			ohno.TimePosition = 9
		end
		if A == 13 then
			ohno.SoundId = "rbxassetid://152833989"
			ohno.TimePosition = 1
		end
		ohno:Play()
		for i = 0,100,0.1 do
			swait()
			CameraEnshaking(2, 3)
			ohno.Parent = hed
			char.Torso.Neck.C0 = char.Torso.Neck.C0 * CFrame.Angles(math.random(-10,10),math.random(-10,10),math.random(-10,10))
		end
		attack = false
		ohno:Stop()
		Character.Head.face.Texture = "rbxassetid://620619801"
		hum.WalkSpeed = 16
	end

	function WRY() --WRYYYYYYY
		attack = true
		hum.WalkSpeed = 0.30
		CreateSound("794081034", hed, 10, 1)
		Character.Head.face.Texture = "rbxassetid://396389196"
		for i = 0,2,0.1 do
			swait()
			CameraEnshaking(1, 2)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(30), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(140), Rad(60)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(-140), Rad(-60)), 0.1)
		end
		for i = 0,14.7,0.1 do
			swait()
			CameraEnshaking(1, 3)
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 1, -1 + 0.1) * angles(Rad(-75), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(65), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1.1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(-70)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1.1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(70)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(45), Rad(0), Rad(40)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(45), Rad(-0), Rad(-40)), 0.1)
		end
		attack = false
		Character.Head.face.Texture = "rbxassetid://620619801"
		hum.WalkSpeed = 16
	end

	function BOI()
		attack = true
		hum.WalkSpeed = 1.01
		CreateSound("390901873", hed, 10, 1)
		Character.Head.face.Texture = "rbxassetid://282463320"
		for i = 0,4,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(50), Rad(90)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(-50), Rad(-90)), 0.1)
		end
		for i = 0,4,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(30), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(140), Rad(60)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(-140), Rad(-60)), 0.1)
		end
		attack = false
		Character.Head.face.Texture = "rbxassetid://620619801"
		hum.WalkSpeed = 16
	end

	function WhatHuh()
		attack = true
		hum.WalkSpeed = 1.01
		CreateSound("130766865", hed, 10, 1)
		Character.Head.face.Texture = "rbxassetid://276732672"
		for i = 0,4,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(0), Rad(26), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(120)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(-120)), 0.1)
		end
		for i = 0,6.7,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(0), Rad(-26), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(120)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(-120)), 0.1)
		end
		for i = 0,8.1,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(0), Rad(26), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(120)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(-120)), 0.1)
		end
		for i = 0,1,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(40), Rad(-26), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(120)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(-120)), 0.1)
		end
		for i = 0,1,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(40), Rad(26), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(120)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(-120)), 0.1)
		end
		for i = 0,4,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(0), Rad(-26), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(120)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(-120)), 0.1)
		end
		attack = false
		Character.Head.face.Texture = "rbxassetid://620619801"
		hum.WalkSpeed = 16
	end

	function NothingPersonal()
		if mouse.Target.Parent ~= char and mouse.Target.Parent.Parent ~= char and mouse.Target.Parent:FindFirstChildOfClass("Humanoid") ~= nil then
			local HITBODY = mouse.Target.Parent
			local TORS = HITBODY:FindFirstChild("Torso") or HITBODY:FindFirstChild("UpperTorso")
			local HEAD = HITBODY:FindFirstChild("Head")
			local HUMAN = mouse.Target.Parent:FindFirstChildOfClass("Humanoid")
			if TORS ~= nil and HUMAN ~= nil then
				attack = true
				root.CFrame = TORS.CFrame * CFrame.new(-1,0,3)
				TORS.Anchored = true
				hum.WalkSpeed = 0
				Character.Head.face.Texture = "rbxassetid://40770311"
				CreateSound("1255922819", hed, 10, 1)
				CameraEnshaking(2, 4)
			end
			wait(3.5)
			for i = 0,9,0.1 do
				swait()
				for i = 1,2 do
					HitboxFunction(ll.CFrame, 0.01, 1, 1, 1, 7, 1, 10, 53, "Knockdown")
					CameraEnshaking(1, 7)
					Effects.Sphere.Create(BrickColor.new("Persimmon"), TORS.CFrame*CFrame.new(math.random(-200,200)/100,math.random(-300,200)/100,math.random(-100,100)/100), 1, 1, 1, 15, 15, 15, 0.2)
				end
			end
			wait(.5)
			TORS.Anchored = false
			attack = false
			Character.Head.face.Texture = "rbxassetid://620619801"
			hum.WalkSpeed = 16
		end
	end

	function VeryMuchWorrying()
		attack = true
		hum.WalkSpeed = 1.01
		Character.Head.face.Texture = "rbxassetid://111523405"
		CreateSound("1395854043", hed, 10, 1)
		for i = 0,14,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.3, 0.9 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(-145)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.3, 0.9 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(145)), 0.1)
		end
		attack = false
		Character.Head.face.Texture = "rbxassetid://620619801"
		hum.WalkSpeed = 16
	end

	function Ashes() --Straight from... Whatever it was called.
		attack = true
		hum.WalkSpeed = 1.01
		Character.Head.face.Texture = "rbxassetid://360687027"
		CreateSound("290084602", tors, 10, 1)
		for i = 0,6.2,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(-30), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-5), Rad(0), Rad(-0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(-0), Rad(0), Rad(145)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(-0), Rad(0), Rad(-145)), 0.1)
		end
		for i = 0,6.2,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1 * Cos(sine / 20)) * angles(Rad(20), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-5), Rad(0), Rad(20)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-5), Rad(0), Rad(-20)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(-30), Rad(0), Rad(15)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(-30), Rad(0), Rad(-15)), 0.1)
		end
		attack = false
		Character.Head.face.Texture = "rbxassetid://620619801"
		hum.WalkSpeed = 16
	end

	function AnotherOne() --WhAT ANOTHER ONE
		attack = true
		hum.WalkSpeed = 1.01
		local icri = CreateSound("1205111204", hed, 10, 1)
		swait(165)
		local FRAME = tors.CFrame
		repeat
			swait()
			Character.Head.face.Texture = "rbxassetid://582931093"
			CameraEnshaking(1, 10)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.3, 0.9 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(90)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.3, 0.9 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(-90)), 0.1)
			tors.CFrame = FRAME * CF(0,1,0)
			swait()
			tors.CFrame = FRAME
		until icri.Playing == false
		Character.Head.face.Texture = "rbxassetid://620619801"
		attack = false
		hum.WalkSpeed = 16
	end

	function Dance()
		attack = true
		hum.WalkSpeed = 1.01
		CreateSound("838766490", hed, 10, 1)
		Character.Head.face.Texture = "rbxassetid://258591579"
		for i = 0,2,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(-0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(180)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(-180)), 0.1)
		end
		for i = 0,4,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(-0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(-30)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(-30)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(50), Rad(0), Rad(180)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(-50), Rad(-0), Rad(-180)), 0.1)
		end
		for i = 0,4,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(-0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(30)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(30)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(-50), Rad(0), Rad(180)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(50), Rad(-0), Rad(-180)), 0.1)
		end
		for i = 0,4,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(-0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(-30)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(-30)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(50), Rad(0), Rad(180)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(-50), Rad(-0), Rad(-180)), 0.1)
		end
		for i = 0,4,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(-0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(30)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(30)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(-50), Rad(0), Rad(180)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(50), Rad(-0), Rad(-180)), 0.1)
		end
		for i = 0,4,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(-0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(-30)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(-30)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(50), Rad(0), Rad(180)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(-50), Rad(-0), Rad(-180)), 0.1)
		end
		for i = 0,4,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(-0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(30)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(30)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(-50), Rad(0), Rad(180)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(50), Rad(-0), Rad(-180)), 0.1)
		end
		for i = 0,4,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(-0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(-30)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(-30)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(50), Rad(0), Rad(180)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(-50), Rad(-0), Rad(-180)), 0.1)
		end
		for i = 0,4,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(-0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(30)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(30)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(-50), Rad(0), Rad(180)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(50), Rad(-0), Rad(-180)), 0.1)
		end
		for i = 0,4,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(-0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(-30)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(-30)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(50), Rad(0), Rad(180)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(-50), Rad(-0), Rad(-180)), 0.1)
		end
		for i = 0,4,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(-0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(30)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(30)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(-50), Rad(0), Rad(180)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(50), Rad(-0), Rad(-180)), 0.1)
		end
		for i = 0,4,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(-0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(-30)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(-30)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(50), Rad(0), Rad(180)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(-50), Rad(-0), Rad(-180)), 0.1)
		end
		for i = 0,4,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(-0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(30)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(30)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(-50), Rad(0), Rad(180)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(50), Rad(-0), Rad(-180)), 0.1)
		end
		for i = 0,4,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(-0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(-30)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(-30)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(50), Rad(0), Rad(180)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(-50), Rad(-0), Rad(-180)), 0.1)
		end
		for i = 0,4,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(-0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(30)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(30)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(-50), Rad(0), Rad(180)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(50), Rad(-0), Rad(-180)), 0.1)
		end
		for i = 0,3,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(-0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(-30)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(-30)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(50), Rad(0), Rad(180)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(-50), Rad(-0), Rad(-180)), 0.1)
		end
		attack = false
		Character.Head.face.Texture = "rbxassetid://620619801"
		hum.WalkSpeed = 16
	end

	function kyu_will_break_your_neck_asdf_longest_function_name_ever_xd()
		attack = true
		Character.Head.face.Texture = "rbxassetid://266304560"
		for i = 0,6,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(0), Rad(0), Rad(0)), 0.3)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.3, 0.9 + 0.05 * Sin(sine / 30), 0.2 * Cos(sine / 20)) * angles(Rad(170), Rad(0), Rad(-15)), 0.1)
			LW.C0 = clerp(LW.C0, CF(-1.3, 0.8 + 0.05 * Sin(sine / 30), -0.025 * Cos(sine / 20)) * angles(Rad(140), Rad(0), Rad(15)), 0.1)
		end
		CreateSound("1093102664", hed, 10, 1)
		CameraEnshaking(3, 8)
		for i = 0,2,0.1 do
			swait()
			rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1) * angles(Rad(5), Rad(0), Rad(0)), 0.15)
			tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(10), Rad(40), Rad(0)), 0.4)
			RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 , 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
			RW.C0 = clerp(RW.C0, CF(1.3, 0.9 + 0.05 * Sin(sine / 30), 0.2 * Cos(sine / 20)) * angles(Rad(200), Rad(0), Rad(-40)), 0.4)
			LW.C0 = clerp(LW.C0, CF(-1.3, 0.8 + 0.05 * Sin(sine / 30), -0.025 * Cos(sine / 20)) * angles(Rad(40), Rad(0), Rad(40)), 0.4)
		end
		Character.Head.face.Texture = "rbxassetid://30128383"
		hum.MaxHealth = 0
		ragdoll(char)
		CreateSound("534269232", hed, 5, 1)
		error("Seems like you just died.")
	end

	MoreTaunts = false
	mouse.KeyDown:connect(function(key)
		if attack == false then
			if MoreTaunts == false then
				if key == 'q' then
					GEtOuT()
				elseif key == 'e' then
					GEtOuT2()
				elseif key == 'x' then
					OBJECTION()
				elseif key == 'n' then
					BOI()
				elseif key == 'u' then
					Victory()
				elseif key == '3' then
					hap()
				elseif key == '6' then
					Flight()
				elseif key == '9' and timetofly then
					FLYSKYHIGH()
				elseif key == '9' then
					local A = math.random(1,10)
					if A == 1 then
						warn ("This has a Cooldown, Please wait. :>")
					end
					if A == 2 then
						warn ("You can't Fly All day, you know.")
					end
					if A == 3 then
						warn ("Calm down there.")
					end
					if A == 4 then
						warn ("Take a Break.")
					end
					if A == 5 then
						warn ("*Elevator Music plays in the backround*")
					end
					if A == 6 then
						warn ("I know, You want to FLY SKY HIGH, but wait a little bit.")
					end
					if A == 7 then
						warn ("Can you wait a LITTLE Longer?")
					end
					if A == 8 then
						warn ("Like a tiger defying the laws of gravity...")
					end
					if A == 9 then
						warn ("DON'T STOP ME NNNNNOOOOOOOOWWWW")
					end
					if A == 10 then
						warn ("Oh, I'm burnin' through the sky, Yeah!")
					end
				elseif key == 'k' then
					Hello()
				elseif key == '5' then
					HAAAAA()
				elseif key == '4' then
					Dance()
				elseif key == '1' then
					HELP()
				elseif key == '2' then
					dead()
				elseif key == 'j' then
					WhatHuh()
				elseif key == 'l' then
					ShutTheHellUp()
				elseif key == 'c' then
					Choose()
				elseif key == 'r' then
					MYSPAGHETTTTTTT()
				elseif key == 't' then
					SpinMeDad()
				elseif key == 'y' then
					EndMySufferingV2()
				elseif key == 'f' then
					NEN()
				elseif key == 'z' then
					NothingPersonal()
				elseif key == '7' then
					somuchcancerwhy()
				elseif key == '8' then
					highnoon()
				elseif key == 'v' then
					VeryMuchWorrying()
				elseif key == 'b' then
					Ashes()
				elseif key == 'p' then
					kyu_will_break_your_neck_asdf_longest_function_name_ever_xd()
				elseif key == 'g' then
					AnotherOne()
				elseif key == 'h' then
					slap()
				elseif key == 'm' then
					WRY()
				end
			end
		end
	end)

	-------------------------------------------------------
	--End Attacks N Stuff--
	-------------------------------------------------------




	while jumping do
		Humanoid.Jump = true
		wait(0.9)
	end




	-------------------------------------------------------
	--Start Animations--
	-------------------------------------------------------
	local equipped = false
	local idle = 0
	local change = 1
	local val = 0
	local toim = 0
	local idleanim = 0.4
	hum.Animator.Parent = nil
	while true do
		swait()
		sine = sine + change
		local torvel = (root.Velocity * Vector3.new(1, 0, 1)).magnitude
		local velderp = root.Velocity.y
		hitfloor, posfloor = rayCast(root.Position, CFrame.new(root.Position, root.Position - Vector3.new(0, 1, 0)).lookVector, 4, char)
		if equipped == true or equipped == false then
			if attack == false then
				idle = idle + 1
			else
				idle = 0
			end
			if 1 < root.Velocity.y and hitfloor == nil then
				Anim = "Jump"
				if attack == false then
					rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1 * Cos(sine / 20)) * angles(Rad(10), Rad(0), Rad(0)), 0.3)
					tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(-40), Rad(0), Rad(0)), 0.3)
					RW.C0 = clerp(RW.C0, CF(1.5, 0.5, 0) * angles(Rad(30), Rad(0), Rad(20)), 0.3)
					LW.C0 = clerp(LW.C0, CF(-1.5, 0.5, 0) * angles(Rad(-20), Rad(0), Rad(-30)), 0.3)
					LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 * Cos(sine / 20), -0.3) * LHCF * angles(Rad(-5), Rad(0), Rad(20)), 0.15)
					RH.C0 = clerp(RH.C0, CF(1, -1, 0.3) * angles(Rad(0), Rad(90), Rad(-20)), 0.3)
				end
			elseif -1 > root.Velocity.y and hitfloor == nil then
				Anim = "Fall"
				if attack == false then
					rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1 * Cos(sine / 20)) * angles(Rad(-5), Rad(0), Rad(0)), 0.3)
					tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(40), Rad(0), Rad(0)), 0.3)
					RW.C0 = clerp(RW.C0, CF(1.5, 0.5, 0) * angles(Rad(30), Rad(0), Rad(20)), 0.3)
					LW.C0 = clerp(LW.C0, CF(-1.5, 0.5, 0) * angles(Rad(-20), Rad(0), Rad(-30)), 0.3)
					LH.C0=clerp(LH.C0, CF(-1,-.4-0.1 * Cos(sine / 20), -.6) * LHCF * angles(Rad(-5), Rad(-0), Rad(20)), 0.15)
					RH.C0=clerp(RH.C0, CF(1,-.3-0.1 * Cos(sine / 20), -.6) * angles(Rad(0), Rad(90), Rad(-20)), .3)
				end
			elseif torvel < 1 and hitfloor ~= nil then
				Anim = "Idle"
				change = 1
				if attack == false then
					rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.1 + 0.1 * Cos(sine / 20)) * angles(Rad(0), Rad(0), Rad(0)), 0.15)
					tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(0), Rad(0), Rad(0)), 0.3)
					RH.C0 = clerp(RH.C0, CF(1, -0.9 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * RHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
					LH.C0 = clerp(LH.C0, CF(-1, -0.9 - 0.1 * Cos(sine / 20), 0.025 * Cos(sine / 20)) * LHCF * angles(Rad(-2.5), Rad(0), Rad(0)), 0.15)
					RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(30 * Cos(sine / 20)), Rad(0), Rad(5)), 0.1)
					LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(30 * Cos(sine / 20)), Rad(0), Rad(-5)), 0.1)
				end
			elseif tors.Velocity.magnitude < 50 and hitfloor ~= nil then
				Anim = "Walk"
				change = 1
				if attack == false then
					rootj.C0 = clerp(rootj.C0, RootCF * CF(0, 0, -0.175 + 0.025 * Cos(sine / 3.5) + -Sin(sine / 3.5) / 7) * angles(Rad(9-2.5 * Cos(sine / 3.5)), Rad(0), Rad(10 * Cos(sine / 7))), 0.15)
					tors.Neck.C0 = clerp(tors.Neck.C0, necko * angles(Rad(0), Rad(0), Rad(0)), 0.3)
					RH.C0 = clerp(RH.C0, CFrame.new(1, -0.925 - 0.5 * math.cos(sine / 7) / 2, 0.5 * math.cos(sine / 7) / 2) * angles(math.rad(-15 - 35 * math.cos(sine / 7)) + -math.sin(sine / 7) / 2.5, math.rad(90 - 2 * math.cos(sine / 7)), math.rad(0)) * angles(math.rad(0 + 2.5 * math.cos(sine / 7)), math.rad(0), math.rad(0)), 0.3)
					LH.C0 = clerp(LH.C0, CFrame.new(-1, -0.925 + 0.5 * math.cos(sine / 7) / 2, -0.5 * math.cos(sine / 7) / 2) * angles(math.rad(-15 + 35 * math.cos(sine / 7)) + math.sin(sine / 7) / 2.5, math.rad(-90 - 2 * math.cos(sine / 7)), math.rad(0)) * angles(math.rad(0 - 2.5 * math.cos(sine / 7)), math.rad(0), math.rad(0)), 0.3)
					RW.C0 = clerp(RW.C0, CF(1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(70) * Cos(sine / 7) , Rad(0), Rad(5)), 0.1)
					LW.C0 = clerp(LW.C0, CF(-1.5, 0.5 + 0.05 * Sin(sine / 30), 0.025 * Cos(sine / 20)) * angles(Rad(-70) * Cos(sine / 7) , Rad(0),	Rad(-5)), 0.1)
				end
			end
		end
		if 0 < #Effects then
			for e = 1, #Effects do
				if Effects[e] ~= nil then
					local Thing = Effects[e]
					if Thing ~= nil then
						local Part = Thing[1]
						local Mode = Thing[2]
						local Delay = Thing[3]
						local IncX = Thing[4]
						local IncY = Thing[5]
						local IncZ = Thing[6]
						if 1 >= Thing[1].Transparency then
							if Thing[2] == "Block1" then
								Thing[1].CFrame = Thing[1].CFrame * CFrame.fromEulerAnglesXYZ(math.random(-50, 50), math.random(-50, 50), math.random(-50, 50))
								local Mesh = Thing[1].Mesh
								Mesh.Scale = Mesh.Scale + Vector3.new(Thing[4], Thing[5], Thing[6])
								Thing[1].Transparency = Thing[1].Transparency + Thing[3]
							elseif Thing[2] == "Block2" then
								Thing[1].CFrame = Thing[1].CFrame + Vector3.new(0, 0, 0)
								local Mesh = Thing[7]
								Mesh.Scale = Mesh.Scale + Vector3.new(Thing[4], Thing[5], Thing[6])
								Thing[1].Transparency = Thing[1].Transparency + Thing[3]
							elseif Thing[2] == "Block3" then
								Thing[1].CFrame = Thing[1].CFrame * CFrame.fromEulerAnglesXYZ(math.random(-50, 50), math.random(-50, 50), math.random(-50, 50)) + Vector3.new(0, 0.15, 0)
								local Mesh = Thing[7]
								Mesh.Scale = Mesh.Scale + Vector3.new(Thing[4], Thing[5], Thing[6])
								Thing[1].Transparency = Thing[1].Transparency + Thing[3]
							elseif Thing[2] == "Cylinder" then
								local Mesh = Thing[1].Mesh
								Mesh.Scale = Mesh.Scale + Vector3.new(Thing[4], Thing[5], Thing[6])
								Thing[1].Transparency = Thing[1].Transparency + Thing[3]
							elseif Thing[2] == "Blood" then
								local Mesh = Thing[7]
								Thing[1].CFrame = Thing[1].CFrame * Vector3.new(0, 0.5, 0)
								Mesh.Scale = Mesh.Scale + Vector3.new(Thing[4], Thing[5], Thing[6])
								Thing[1].Transparency = Thing[1].Transparency + Thing[3]
							elseif Thing[2] == "Elec" then
								local Mesh = Thing[1].Mesh
								Mesh.Scale = Mesh.Scale + Vector3.new(Thing[7], Thing[8], Thing[9])
								Thing[1].Transparency = Thing[1].Transparency + Thing[3]
							elseif Thing[2] == "Disappear" then
								Thing[1].Transparency = Thing[1].Transparency + Thing[3]
							elseif Thing[2] == "Shatter" then
								Thing[1].Transparency = Thing[1].Transparency + Thing[3]
								Thing[4] = Thing[4] * CFrame.new(0, Thing[7], 0)
								Thing[1].CFrame = Thing[4] * CFrame.fromEulerAnglesXYZ(Thing[6], 0, 0)
								Thing[6] = Thing[6] + Thing[5]
							end
						else
							Part.Parent = nil
							table.remove(Effects, e)
						end
					end
				end
			end
		end
	end
	-------------------------------------------------------
	--End Animations And Script--
	-------------------------------------------------------

	--cool beans boibiparti
end)

invis.Name = "invis"
invis.Parent = main
invis.BackgroundColor3 = Color3.fromRGB(85, 85, 85)
invis.Position = UDim2.new(0.125, 0, 0.380964279, 0)
invis.Size = UDim2.new(0, 134, 0, 32)
invis.Font = Enum.Font.SciFi
invis.Text = "Invis"
invis.TextColor3 = Color3.fromRGB(0, 0, 0)
invis.TextSize = 35.000
invis.MouseButton1Down:connect(function()
	-- FE Invisible
	--You Will Be Able To See YourSelf But Others Won't!
	Local = game:GetService('Players').LocalPlayer
	Char  = Local.Character
	touched,tpdback = false, false
	Local.CharacterAdded:connect(function(char)
		if script.Disabled ~= true then
			wait(.25)
			loc = Char.HumanoidRootPart.Position
			Char:MoveTo(box.Position + Vector3.new(0,.5,0))
		end
	end)
	game:GetService('UserInputService').InputBegan:connect(function(key)
		if key.KeyCode == Enum.KeyCode.Equals then
			if script.Disabled ~= true then
				script.Disabled = true
				print'you may re-execute'
			end
		end
	end)
	box = Instance.new('Part',workspace)
	box.Anchored = true
	box.CanCollide = true
	box.Size = Vector3.new(10,1,10)
	box.Position = Vector3.new(0,10000,0)
	box.Touched:connect(function(part)
		if (part.Parent.Name == Local.Name) then
			if touched == false then
				touched = true
				function apply()
					if script.Disabled ~= true then
						no = Char.HumanoidRootPart:Clone()
						wait(.25)
						Char.HumanoidRootPart:Destroy()
						no.Parent = Char
						Char:MoveTo(loc)
						touched = false
					end end
				if Char then
					apply()
				end
			end
		end
	end)
	repeat wait() until Char
	loc = Char.HumanoidRootPart.Position
	Char:MoveTo(box.Position + Vector3.new(0,.5,0))
end)

sans.Name = "sans"
sans.Parent = main
sans.BackgroundColor3 = Color3.fromRGB(85, 85, 85)
sans.Position = UDim2.new(0.125, 0, 0.445576608, 0)
sans.Size = UDim2.new(0, 134, 0, 32)
sans.Font = Enum.Font.SciFi
sans.Text = "Sans"
sans.TextColor3 = Color3.fromRGB(0, 0, 0)
sans.TextSize = 35.000
sans.MouseButton1Down:connect(function()
	HumanDied = false
	local CountSCIFIMOVIELOL = 1
	function SCIFIMOVIELOL(Part0,Part1,Position,Angle)
		local AlignPos = Instance.new('AlignPosition', Part1); AlignPos.Name = "AliP_"..CountSCIFIMOVIELOL
		AlignPos.ApplyAtCenterOfMass = true;
		AlignPos.MaxForce = 5772000--67752;
		AlignPos.MaxVelocity = math.huge/9e110;
		AlignPos.ReactionForceEnabled = false;
		AlignPos.Responsiveness = 200;
		AlignPos.RigidityEnabled = false;
		local AlignOri = Instance.new('AlignOrientation', Part1); AlignOri.Name = "AliO_"..CountSCIFIMOVIELOL
		AlignOri.MaxAngularVelocity = math.huge/9e110;
		AlignOri.MaxTorque = 5772000
		AlignOri.PrimaryAxisOnly = false;
		AlignOri.ReactionTorqueEnabled = false;
		AlignOri.Responsiveness = 200;
		AlignOri.RigidityEnabled = false;
		local AttachmentA=Instance.new('Attachment',Part1); AttachmentA.Name = "Ath_"..CountSCIFIMOVIELOL
		local AttachmentB=Instance.new('Attachment',Part0); AttachmentB.Name = "Ath_"..CountSCIFIMOVIELOL
		AttachmentA.Orientation = Angle or Vector3.new(0,0,0)
		AttachmentA.Position = Position or Vector3.new(0,0,0)
		AlignPos.Attachment1 = AttachmentA;
		AlignPos.Attachment0 = AttachmentB;
		AlignOri.Attachment1 = AttachmentA;
		AlignOri.Attachment0 = AttachmentB;
		CountSCIFIMOVIELOL = CountSCIFIMOVIELOL + 1
		return {AlignPos,AlignOri,AttachmentA,AttachmentB}
	end

	game:FindFirstChildOfClass("Players").LocalPlayer["Character"].Archivable = true
	local hatnameclone = {}
	for _,v in next, game:FindFirstChildOfClass("Players").LocalPlayer["Character"]:GetChildren() do
		if v:IsA("Accessory") then
			if hatnameclone[v.Name] then
				if hatnameclone[v.Name] == "s" then
					hatnameclone[v.Name] = {}
				end
				table.insert(hatnameclone[v.Name],v)
			else
				hatnameclone[v.Name] = "s"
			end
		end
	end
	for _,v in pairs(hatnameclone) do
		if type(v) == "table" then
			local num = 1
			for _,w in pairs(v) do
				w.Name = w.Name..num
				num = num + 1
			end
		end
	end
	hatnameclone = nil

	local DeadChar = game:FindFirstChildOfClass("Players").LocalPlayer.Character

	local fldr = Instance.new("Folder",game:FindFirstChildOfClass("Players").LocalPlayer["Character"])
	fldr.Name = "DMYF"
	local CloneChar = DeadChar:Clone()
	local ANIMATIONHERE
	if CloneChar:FindFirstChild("Animate") then
		ANIMATIONHERE = CloneChar:FindFirstChild("Animate"):Clone()
		CloneChar:FindFirstChild("Animate"):Destroy()
	end
	if CloneChar:FindFirstChildOfClass("Folder") then CloneChar:FindFirstChildOfClass("Folder"):Destroy() end
	if CloneChar.Torso:FindFirstChild("Neck") then
		local Clonessss = CloneChar.Torso:FindFirstChild("Neck"):Clone()
		Clonessss.Part0 = nil
		Clonessss.Part1 = DeadChar.Head
		Clonessss.Parent = DeadChar.Torso
	end
	CloneChar.Parent = fldr
	CloneChar.HumanoidRootPart.CFrame = DeadChar.HumanoidRootPart.CFrame
	CloneChar.Humanoid.BreakJointsOnDeath = false
	CloneChar.Name = "non"
	CloneChar.Humanoid.DisplayDistanceType = "None"

	for _,v in next, DeadChar:GetChildren() do
		if v:IsA("Accessory") then
			local topacc = false
			if v.Handle:FindFirstChildOfClass("Weld") then v.Handle:FindFirstChildOfClass("Weld"):Destroy() end
			v.Handle.Massless = true
			v.Handle.CanCollide = false
			if v.Handle:FindFirstChildOfClass("Attachment") then
				local ath__ = v.Handle:FindFirstChildOfClass("Attachment")
				if ath__.Name == "HatAttachment" or ath__.Name == "HairAttachment" or ath__.Name == "FaceFrontAttachment" or ath__.Name == "FaceCenterAttachment" then
					topacc = ath__.Name
				end
			end
			local bv = Instance.new("BodyVelocity",v.Handle)
			bv.Velocity = Vector3.new(0,0,0)
			coroutine.wrap(function()
				if topacc then
					local allthings = SCIFIMOVIELOL(v.Handle,DeadChar.Torso,Vector3.new(0,1.5,0)+ (DeadChar.Head[topacc].Position + (v.Handle[topacc].Position*-1)),Vector3.new(0,0,0))
					local normaltop = allthings[1].Attachment1
					local alipos = allthings[1]
					local alirot = allthings[2]
					local p0 = v.Handle
					local p1 = DeadChar.Head
					alipos.Parent = CloneChar:FindFirstChild(v.Name).Handle
					alirot.Parent = CloneChar:FindFirstChild(v.Name).Handle
					while true do
						game:GetService("RunService").RenderStepped:wait()
						if HumanDied then break end
						coroutine.wrap(function()
							if alipos.Attachment1 == normaltop then
								p0.CFrame = p0.CFrame:lerp((((DeadChar.Torso.CFrame * CFrame.new(0,1.5,0)) * p1[topacc].CFrame) * p0[topacc].CFrame:inverse()),1)
							else
								v.Handle.CFrame = v.Handle.CFrame:lerp(alipos.Attachment1.Parent.CFrame * CFrame.new(alipos.Attachment1.Position) * CFrame.Angles(math.rad(alipos.Attachment1.Rotation.X),math.rad(alipos.Attachment1.Rotation.Y),math.rad(alipos.Attachment1.Rotation.Z)),1)
							end
						end)()
					end
				else
					SCIFIMOVIELOL(v.Handle,CloneChar[v.Name].Handle,Vector3.new(0,0,0),Vector3.new(0,0,0))
				end
			end)()
		end
	end

	local a = DeadChar.Torso
	local b = DeadChar.HumanoidRootPart
	local c = DeadChar.Humanoid
	a.Parent = game:FindFirstChildOfClass("Workspace")
	c.Parent = game:FindFirstChildOfClass("Workspace")
	local told = a:Clone()
	local told1 = c:Clone()
	b["RootJoint"].Part0 = told
	b["RootJoint"].Part1 = DeadChar.Head
	a.Name = "torso"
	a.Neck:Destroy()
	c.Name = "Mizt Hub Best"
	told.Parent = DeadChar
	told1.Parent = DeadChar
	DeadChar.PrimaryPart = told
	told1.Health = 0
	b:Destroy()
	a.Parent = DeadChar
	c.Parent = DeadChar
	told:Destroy()
	told1:Destroy()
	a.Name = "Torso"

	if CloneChar.Head:FindFirstChildOfClass("Decal") then CloneChar.Head:FindFirstChildOfClass("Decal").Transparency = 1 end
	if DeadChar:FindFirstChild("Animate") then DeadChar:FindFirstChild("Animate"):Destroy() end

	local Collider
	function UnCollide()
		if HumanDied then Collider:Disconnect(); return end
		for _,Parts in next, CloneChar:GetChildren() do
			if Parts:IsA("BasePart") then
				Parts.CanCollide = false 
			end 
		end
		for _,Parts in next, DeadChar:GetChildren() do
			if Parts:IsA("BasePart") then
				Parts.CanCollide = false
			end 
		end 
	end
	Collider = game:GetService("RunService").Stepped:Connect(UnCollide)

	local resetBindable = Instance.new("BindableEvent")
	resetBindable.Event:connect(function()
		game:GetService("StarterGui"):SetCore("ResetButtonCallback", true)
		resetBindable:Destroy()
		HumanDied = true
		pcall(function()
			game:FindFirstChildOfClass("Players").LocalPlayer.Character = DeadChar
			DeadChar.Head:Destroy()
			DeadChar:FindFirstChildOfClass("Humanoid"):Destroy()
			game:FindFirstChildOfClass("Players").LocalPlayer.Character = CloneChar
			if DeadChar:FindFirstChildOfClass("Folder") then DeadChar:FindFirstChildOfClass("Folder"):Destroy() end
		end)
	end)
	game:GetService("StarterGui"):SetCore("ResetButtonCallback", resetBindable)

	coroutine.wrap(function()
		while true do
			game:GetService("RunService").RenderStepped:wait()
			if not CloneChar or not CloneChar:FindFirstChild("Head") or not CloneChar:FindFirstChildOfClass("Humanoid") or CloneChar:FindFirstChildOfClass("Humanoid").Health <= 0 and not DeadChar or not DeadChar:FindFirstChild("Head") or not DeadChar:FindFirstChildOfClass("Humanoid") or DeadChar:FindFirstChildOfClass("Humanoid").Health <= 0 then 
				HumanDied = true
				pcall(function()
					game:FindFirstChildOfClass("Players").LocalPlayer.Character = DeadChar
					DeadChar.Head:Destroy()
					DeadChar:FindFirstChildOfClass("Humanoid"):Destroy()
					game:FindFirstChildOfClass("Players").LocalPlayer.Character = CloneChar
					if DeadChar:FindFirstChildOfClass("Folder") then DeadChar:FindFirstChildOfClass("Folder"):Destroy() end
				end)
				if resetBindable then
					game:GetService("StarterGui"):SetCore("ResetButtonCallback", true)
					resetBindable:Destroy()
				end
				break
			end     
		end
	end)()


	SCIFIMOVIELOL(DeadChar["Head"],CloneChar["Head"])
	SCIFIMOVIELOL(DeadChar["Torso"],CloneChar["Torso"])
	SCIFIMOVIELOL(DeadChar["Left Arm"],CloneChar["Left Arm"])
	SCIFIMOVIELOL(DeadChar["Right Arm"],CloneChar["Right Arm"])
	SCIFIMOVIELOL(DeadChar["Left Leg"],CloneChar["Left Leg"])
	SCIFIMOVIELOL(DeadChar["Right Leg"],CloneChar["Right Leg"])

	for _,v in pairs(DeadChar:GetChildren()) do
		if v:IsA("BasePart") and v.Name ~= "Head" then
        --[[local bv = Instance.new("BodyVelocity",v)
        bv.Velocity = Vector3.new(0,0,0)
        coroutine.wrap(function()
            while true do
                game:GetService("RunService").RenderStepped:wait()
                if HumanDied then break end
                v.CFrame = CloneChar[v.Name].CFrame
            end
        end)()]]
		elseif v:IsA("BasePart") and v.Name == "Head" then
			local bv = Instance.new("BodyVelocity",v)
			bv.Velocity = Vector3.new(0,0,0)
			coroutine.wrap(function()
				while true do
					game:GetService("RunService").RenderStepped:wait()
					if HumanDied then break end
					v.CFrame = DeadChar.Torso.CFrame * CFrame.new(0,1.5,0)
				end
			end)()
		end
	end

	for _,BodyParts in next, CloneChar:GetDescendants() do
		if BodyParts:IsA("BasePart") or BodyParts:IsA("Part") then
			BodyParts.Transparency = 1 end end
	game:GetService("RunService").RenderStepped:wait()
	game:FindFirstChildOfClass("Players").LocalPlayer.Character = CloneChar
	game:FindFirstChildOfClass("Workspace"):FindFirstChildOfClass("Camera").CameraSubject = CloneChar.Humanoid

	for _,v in next, DeadChar:GetChildren() do
		if v:IsA("Accessory") then
			if v.Handle:FindFirstChildOfClass("Weld") then v.Handle:FindFirstChildOfClass("Weld"):Destroy() end
		end
	end
	if ANIMATIONHERE then ANIMATIONHERE.Parent = CloneChar end
	s = Instance.new("Sound",Workspace)
	s.Pitch = 1
	s.Volume = 1
	s.SoundId = "rbxassetid://400786493"
	s.Looped = true
	s:Play()
	pls=game:GetService'Players';
	rs=game:GetService'RunService';
	uinps=game:GetService'UserInputService';
	lp=pls.LocalPlayer;
	mouse=lp:GetMouse();
	c=lp.Character;
	rayModel=Instance.new('Model',c);
	human=c.Humanoid;
	Cone=nil;
	human.MaxHealth=5000;
	wait();
	human.Health=5000;
	c.Health:Destroy();
	Debounces={
		FPS=0;
		isAttacking=false;
		isMoving=false;
		isSprinting=false;
		Debounce=false;
		isTyping=false;
		isJumping=false;
		isFlash=false;
		print("FE By Ice & Fire3021")
	};
	numLerp=function(start,goal,alpha)
		return(((goal-start)*alpha)+start);
	end;
	CFrameZero=function()
		return CFrame.new(Vector3.new());
	end;
	local function a()
		local t=tick();
		local l=t%1*3;
		local t=.5*math.pi*(l%1);
		if l<1 then
			return Color3.new(1,1-math.cos(t),1-math.sin(t));
		elseif l<2 then
			return Color3.new(1-math.sin(t),1,1-math.cos(t));
		else
			return Color3.new(1-math.cos(t),1-math.sin(t),1);
		end;
	end;
	rad=function(value)
		return math.rad(value);
	end;
	CFAngles=function(Vector)
		return CFrame.Angles(rad(Vector.x),rad(Vector.y),rad(Vector.z));
	end;
	AnimStat={
		lerpSpeed=.2;
		lerpSpeed2=.35;
		lerpTween=0;
	};
	Joints={
		c.HumanoidRootPart.RootJoint;
		c.Torso.Neck;
		c.Torso['Left Shoulder'];
		c.Torso['Right Shoulder'];
		c.Torso['Left Hip'];
		c.Torso['Right Hip'];
	};
	JointTargets={
		CFrameZero();
		CFrameZero();
		CFrameZero();
		CFrameZero();
		CFrameZero();
		CFrameZero();
	};
	prepareCharacter=function()
		music=Instance.new('Sound',c.HumanoidRootPart);
		music.SoundId='rbxassetid://394144904';
		music.Looped=true;
		music.Volume=.6;
		music2=Instance.new('Sound',c);
		music2.SoundId='rbxassetid://259613634';
		music2.Looped=true;
		music2.Volume=1;
		music3=Instance.new('Sound',c.HumanoidRootPart);
		music3.SoundId='rbxassetid://266530326';
		music3.Looped=true;
		music3.Volume=1;
		music4=Instance.new('Sound',c.HumanoidRootPart);
		music4.SoundId='rbxassetid://155738252';
		music4.Looped=true;
		music4.Volume=1;
		music5=Instance.new('Sound',c.HumanoidRootPart);
		music5.SoundId='rbxassetid://215391212';
		music5.Looped=true;
		music5.Volume=1;
		human.WalkSpeed=0;
		human.JumpPower=0;
		for i,v in pairs(c:children())do
			if v:isA'Hat'then v:Destroy();end;
			if v:FindFirstChild'roblox'then v.roblox:Destroy();end;
			if v.Name=='Head'then v.Transparency=1 for _,x in pairs(v:children())do if x.ClassName=='Sound'then x:Destroy();end;end;end;
			if v:FindFirstChild'face'then v.face:Destroy();end;
			if v:isA'Part'then v.BrickColor=BrickColor.new'White';end;
		end
		local shirt=c:FindFirstChild'Shirt'or Instance.new('Shirt',c);
		local pants=c:FindFirstChild'Pants'or Instance.new('Pants',c);
		shirt.ShirtTemplate='rbxassetid://334755544';
		pants.PantsTemplate='rbxassetid://315964941';
		local Head=Instance.new('Part',c);
		Head.Size=Vector3.new(2.5,2.5,1);
		Head.Transparency=1;
		Head:BreakJoints();
		local hw=Instance.new('Weld',c.Head);
		hw.Part0=c.Head;
		hw.Part1=Head;
		hw.C0=CFrame.new(0,.3,0);
		faceDecal=Instance.new('Decal',Head);
		faceDecal.Face=Enum.NormalId.Front;
		faceDecal.Texture='rbxassetid://400387868';
		local backDecal=Instance.new('Decal',Head);
		backDecal.Face=Enum.NormalId.Back;
		backDecal.Texture='rbxassetid://400377807';
		local mes=Instance.new('BlockMesh',Head);
		mes.Scale=Vector3.new(1,1,.4);
		local Anim=human:FindFirstChild'Animator'
		if Anim then Anim:Destroy();end;
	end;
	setJointCFrames=function(table)
		for i=1,#table do
			JointTargets[i]=table[i];
		end;
	end;
	triWave=function(x)
		local pi2=math.pi/2;
		return math.abs((x/pi2)%4-2)-1;
	end;
	setLerp=function(speed)
		AnimStat.lerpSpeed=speed;
	end;
	setTween=function(tween)
		AnimStat.lerpTween=tween;
	end;
	playSound=function(id,part,vol,pitch)
		local vol=vol or 1;
		local pitch=pitch or 1;
		local x=Instance.new('Sound',part);
		x.Volume=vol;
		x.Pitch=pitch;
		x.SoundId='rbxassetid://'..id;
		spawn(function()
			wait();
			x:Play();
			wait(x.TimeLength+.2);
			x:Destroy();
		end);
	end;
	lerpBoom=function()
		if Cone then
			Cone.CFrame=CFrame.new(c.HumanoidRootPart.CFrame.p,c.HumanoidRootPart.CFrame.p+c.HumanoidRootPart.Velocity)*CFrame.Angles(-math.pi/2,0,0);
			cMesh.Scale=Vector3.new(20,20+c.HumanoidRootPart.Velocity.magnitude/10,20);
			Cone.Transparency=1-c.HumanoidRootPart.Velocity.magnitude/1000;
		else
			Cone=Instance.new('Part',c);
			Cone.Anchored=true;
			Cone.CanCollide=false;
			Cone.Transparency=math.random(50,70)/100;
			Cone.Size=Vector3.new(1,1,1);
			Cone.CFrame=CFrame.new(c.HumanoidRootPart.CFrame.p,c.HumanoidRootPart.CFrame.p+c.HumanoidRootPart.Velocity)*CFrame.Angles(-math.pi/2,0,0);
			cMesh=Instance.new('SpecialMesh',Cone);
			cMesh.MeshId='rbxassetid://1033714';
			cMesh.Scale=Vector3.new(20,50,20);
		end;
	end;
	noBoom=function()
		if Cone then local x=Cone Cone=nil;
			for i=1,20 do
				wait();
				x.Mesh.Scale=x.Mesh.Scale+Vector3.new(-.5,1,-.5);
				x.Transparency=x.Transparency+1/30;
			end;
		end;
	end;
	gasterBlast=function(tCFrame,aimPos,charge)
		local aimTarget;
		if aimPos then
			aimTarget=CFrame.new(tCFrame,aimPos);
		else
			aimTarget=tCFrame;
		end;
		local gast=Instance.new('Part',c);
		gast.Size=Vector3.new(12,.2,12);
		gast.CanCollide=false;
		gast.Anchored=true;
		gast.Transparency=1;
		if charge then
			playSound(400523331,gast,math.random(90,110)/100);
		end;
		wait();
		for i=1,2 do
			local decal=Instance.new('Decal',gast);
			decal.Texture='rbxassetid://323497117';
			if i==1 then
				decal.Face=Enum.NormalId.Top;
			else
				decal.Face=Enum.NormalId.Bottom;
				function k()
					print("FE By Ice & Fire#3021")
				end
			end;
		end;
		gast.CFrame=CFrame.new(aimTarget.p-Vector3.new(math.sin(tick()*10)*10,20,math.cos(tick()*10)*10));
		spawn(function()
			local tarCFrame=gast.CFrame;
			local isLooping=true;
			spawn(function()
				while rs.RenderStepped:wait()and isLooping do
					gast.CFrame=gast.CFrame:lerp(tarCFrame,.6/(Debounces.FPS/60));
				end;
			end);
			for i=1,30 do
				wait();
				tarCFrame=gast.CFrame:lerp(aimTarget,.24);
			end;
			playSound(340722848,gast,math.random(90,110)/100);
			isLooping=false;
			wait(.08);
			local ray=Ray.new(aimTarget.p,aimTarget.lookVector.unit*999);
			local _,pos=workspace:FindPartOnRay(ray,c);
			local dis=(aimTarget.p-pos).magnitude;
			local rayCFrame=CFrame.new(gast.CFrame.p+(pos-gast.CFrame.p).unit*(dis/2+200),gast.CFrame.p+(pos-gast.CFrame.p).unit*dis*2)*CFrame.Angles(0,math.pi/2,0);
			local rayPart=Instance.new('Part',rayModel);
			rayPart.Material='Neon';
			rayPart.FormFactor='Custom';
			rayPart.Color=a();
			rayPart.Anchored=true;
			rayPart.CanCollide=false;
			rayPart.Shape='Cylinder';
			rayPart.Size=Vector3.new(dis+400,8,8);
			rayPart.CFrame=rayCFrame;
			gast:Destroy();
		end);
	end;
	largegasterBlast=function(tCFrame,aimPos)
		local aimTarget;
		if aimPos then
			aimTarget=CFrame.new(tCFrame,aimPos);
		else
			aimTarget=tCFrame;
		end;
		local gast=Instance.new('Part',c);
		gast.Size=Vector3.new(25,.2,25);
		gast.CanCollide=false;
		gast.Anchored=true;
		gast.Transparency=1;
		playSound(400523331,gast,math.random(85,97)/100);
		wait();
		for i=1,2 do
			local decal=Instance.new('Decal',gast);
			decal.Texture='rbxassetid://323497117';
			if i==1 then
				decal.Face=Enum.NormalId.Top;
			else
				decal.Face=Enum.NormalId.Bottom;
			end;
		end;
		gast.CFrame=CFrame.new(aimTarget.p-Vector3.new(math.sin(tick()*10)*10,20,math.cos(tick()*10)*10));
		spawn(function()
			local tarCFrame=gast.CFrame;
			local isLooping=true;
			spawn(function()
				while rs.RenderStepped:wait()and isLooping do
					gast.CFrame=gast.CFrame:lerp(tarCFrame,.6/(Debounces.FPS/60));
				end;
			end);
			for i=1,40 do
				wait();
				tarCFrame=gast.CFrame:lerp(aimTarget,.18);
			end;
			playSound(340722848,gast,math.random(80,95)/100);
			isLooping=false;
			wait(.08);
			local ray=Ray.new(aimTarget.p,aimTarget.lookVector.unit*999);
			local _,pos=workspace:FindPartOnRay(ray,c);
			local dis=(aimTarget.p-pos).magnitude;
			local rayCFrame=CFrame.new(gast.CFrame.p+(pos-gast.CFrame.p).unit*(dis/2+200),gast.CFrame.p+(pos-gast.CFrame.p).unit*dis*2)*CFrame.Angles(0,math.pi/2,0);
			local rayPart=Instance.new('Part',rayModel);
			rayPart.Material='Neon';
			rayPart.FormFactor='Custom';
			rayPart.Color=a();
			rayPart.Anchored=true;
			rayPart.CanCollide=false;
			rayPart.Shape='Cylinder';
			rayPart.Size=Vector3.new(dis+400,17,17);
			rayPart.CFrame=rayCFrame;
			gast:Destroy();
		end);
	end;
	prepareCharacter();
	spawn(function()
		local sine=0;
		while wait()do
			if Debounces.isFlash then
				if(tick()*8)%2>1 then
					faceDecal.Texture='rbxassetid://400377503';
				else
					faceDecal.Texture='rbxassetid://400387868';
				end;
			else
				faceDecal.Texture='rbxassetid://400387868';
			end;
			if Debounces.isAttacking==false and Debounces.isMoving==false and Debounces.Debounce==false and Debounces.isJumping==false then
				setLerp(.8);
				local spasm=math.abs(math.sin(tick()*20))*1.1;
				local spasm2=math.abs(math.sin(tick()*20-2))*1.1;
				local spasm3=math.abs(math.sin(tick()*20-2.3))*1.1;
				setJointCFrames({
					CFrame.new(Vector3.new(0,0-spasm,0))*CFAngles(Vector3.new(0,0,0));
					CFrame.new(Vector3.new(0,1.5,0))*CFAngles(Vector3.new(-0.011,-0.502,-1.177));
					CFrame.new(Vector3.new(-1.5-spasm2^2/3,-0.001,0))*CFAngles(Vector3.new(-2.344,7.899,-2.82+spasm3^2*-60));
					CFrame.new(Vector3.new(1.569+spasm2^2/3,0,-0.1))*CFAngles(Vector3.new(4.822,1.123,6.383+spasm3^2*60));
					CFrame.new(Vector3.new(-0.61,-2+spasm/1.01,-.15))*CFAngles(Vector3.new(-2.206,0.767,-0.582));
					CFrame.new(Vector3.new(0.55,-2+spasm/1.01,-.1))*CFAngles(Vector3.new(-0.026,0.463,3.184));
				});
			elseif Debounces.isAttacking==false and Debounces.isMoving==true and Debounces.Debounce==false and Debounces.isSprinting==false and Debounces.isJumping==false then
				sine=tick()*18;
				human.WalkSpeed=120;
				setLerp(.35);
				setJointCFrames({
					CFrame.new(Vector3.new(0,math.sin(sine)/50-.3,0))*CFAngles(Vector3.new(-30-math.sin(sine*2)*3,math.sin(sine*2)*15,0));
					CFrame.new(Vector3.new(0,1.48,0.099))*CFAngles(Vector3.new(14.999,-0.001,0));
					CFrame.new(Vector3.new(-1.5,-0.001,0.2+math.sin(sine*2+math.pi)*1.2))*CFAngles(Vector3.new(-25.001+math.sin(sine*2+math.pi)*-90,0,-15));
					CFrame.new(Vector3.new(1.5,-0.001,0.2+math.sin(sine*2)*1.2))*CFAngles(Vector3.new(-25+math.sin(sine*2)*-90,-0.001,14.999));
					CFrame.new(Vector3.new(-0.501,-2+math.cos(sine*2+math.pi)/3,.3+math.sin(sine*2)))*CFAngles(Vector3.new(-25+math.sin(sine*2)*-70,0,-0.001));
					CFrame.new(Vector3.new(0.499,-2+math.cos(sine*2)/3,.3+math.sin(sine*2+math.pi)))*CFAngles(Vector3.new(-25+math.sin(sine*2)*70,0,0));
				});
			elseif Debounces.isAttacking==false and Debounces.isMoving==true and Debounces.Debounce==false and Debounces.isSprinting==true and Debounces.isJumping==false then
				sine=tick()*28;
				human.WalkSpeed=400;
				lerpBoom();
				setLerp(.65);
				setJointCFrames({
					CFrame.new(Vector3.new(0,math.sin(sine)/50-.3,0))*CFAngles(Vector3.new(-30-math.sin(sine*2)*3,math.sin(sine*2)*15,0));
					CFrame.new(Vector3.new(0,1.48,0.099))*CFAngles(Vector3.new(14.999,-0.001,0));
					CFrame.new(Vector3.new(-1.5,-0.001,0.2+math.sin(sine*2+math.pi)*1.2))*CFAngles(Vector3.new(-25.001+math.sin(sine*2+math.pi)*-90,0,-15));
					CFrame.new(Vector3.new(1.5,-0.001,0.2+math.sin(sine*2)*1.2))*CFAngles(Vector3.new(-25+math.sin(sine*2)*-90,-0.001,14.999));
					CFrame.new(Vector3.new(-0.501,-2+math.cos(sine*2+math.pi)/3,.3+math.sin(sine*2)))*CFAngles(Vector3.new(-25+math.sin(sine*2)*-70,0,-0.001));
					CFrame.new(Vector3.new(0.499,-2+math.cos(sine*2)/3,.3+math.sin(sine*2+math.pi)))*CFAngles(Vector3.new(-25+math.sin(sine*2)*70,0,0));
				});
			elseif Debounces.isJumping==true and Debounces.Debounce==false then
				setLerp(.14);
				human.WalkSpeed=45;
				setJointCFrames({
					CFrame.new(Vector3.new(0,0,0))*CFAngles(Vector3.new(-8,0,0));
					CFrame.new(Vector3.new(0,1.5,-0.15))*CFAngles(Vector3.new(-10.138,3.687,0.306));
					CFrame.new(Vector3.new(-1.23,0.069,-0.56))*CFAngles(Vector3.new(50.809,0.672,18.704));
					CFrame.new(Vector3.new(0.929,-0.031,-1.0912))*CFAngles(Vector3.new(63.00,13.85,-36.416));
					CFrame.new(Vector3.new(-0.63,-1.82,-0.74))*CFAngles(Vector3.new(31.324,3.424,-1.249));
					CFrame.new(Vector3.new(0.619,-1.331,0.82))*CFAngles(Vector3.new(-59.644,0.998,9.776));
				});
			end;
		end;
	end);
	human.Changed:connect(function(prop)
		if prop=='MoveDirection'then
			if human.MoveDirection.magnitude>.02 then
				Debounces.isMoving=true;
			else
				Debounces.isMoving=false;
			end;
		end;
	end);
	uinps.InputBegan:connect(function(InputObj)
		if InputObj.KeyCode==Enum.KeyCode.Slash then
			local finishEvent=nil;
			Debounces.isTyping=true
			finishEvent=uinps.InputBegan:connect(function(InputObj)
				if InputObj.KeyCode==Enum.KeyCode.Return or InputObj.UserInputType==Enum.UserInputType.MouseButton1 then
					Debounces.isTyping=false;
					finishEvent:disconnect();
				end;
			end);
		end;
	end);
	mouse.KeyDown:connect(function(key)
		if key=='0'then
			Debounces.isSprinting=true;
			playSound(160248522,c.Torso);
			for i=1,3 do
				spawn(function()
					local e=Instance.new('Part',c);
					e.Size=Vector3.new(1,1,1);
					e.Material='Neon';
					e.Color=a();
					e.Anchored=true;
					e.CFrame=c.HumanoidRootPart.CFrame*CFrame.Angles(0,0,-math.pi/2);
					e.CanCollide=false;
					local rm=Instance.new('SpecialMesh',e);
					rm.MeshType='FileMesh';
					rm.MeshId='rbxassetid://3270017';
					rm.Scale=Vector3.new(3.2,3.2,10);
					for x=1,30 do
						wait();
						rm.Scale=rm.Scale:lerp(Vector3.new(i*30,i*30,(4-i)*450),.1);
						e.Transparency=x/30+.5;
					end;
				end);
			end;
			c.HumanoidRootPart.Velocity=c.HumanoidRootPart.CFrame.lookVector*200;
		end;
	end);
	mouse.KeyUp:connect(function(key)
		if key==''then
			Debounces.isSprinting=false;
		end;
	end);
	mouse.KeyDown:connect(function(key)
		if key==''then
			playSound(201858087,c.Torso,math.random(90,120)/100);
			local oldPos=c.HumanoidRootPart.CFrame.p;
			local mHit=mouse.Hit.p;
			for i=1,2 do
				spawn(function()
					local pos
					if i==1 then pos=oldPos else pos=mHit end
					local p=Instance.new('Part',workspace);
					p.Anchored=true;
					p.CanCollide=false;
					p.Color=a();
					p.FormFactor='Custom';
					p.CFrame=CFrame.new(pos+Vector3.new(0,500,0));
					p.Transparency=.4;
					p.Size=Vector3.new(20,1000,20);
					for i=1,20 do
						wait();
						p.Transparency=.4+(i/10)*.6;
						p.Size=Vector3.new(20-i*1.5,1000,20-i*1.5);
						p.CFrame=CFrame.new(pos+Vector3.new(0,500,0));
					end;
					p:Destroy();
				end);
			end;
			if Debounces.isMoving then
				c.HumanoidRootPart.CFrame=CFrame.new(mouse.Hit.p+Vector3.new(0,4,0),Vector3.new(c.HumanoidRootPart.Velocity.x,mouse.Hit.p.y+4,c.HumanoidRootPart.Velocity.z));
			else
				c.HumanoidRootPart.CFrame=CFrame.new(mouse.Hit.p+Vector3.new(0,4,0),Vector3.new(oldPos.x,mouse.Hit.p.y+4,oldPos.z));
			end;
		end;
	end);
	mouse.KeyDown:connect(function(key)
		if key==''then
			local pointTarget=mouse.Hit.p;
			for i=1,20 do
				wait();
				gasterBlast(CFrame.new(pointTarget+Vector3.new(math.sin(tick()*10)*20,5+math.abs(math.sin(tick()*5)*10),math.cos(tick()*10)*20),pointTarget));
			end;
			wait();
			largegasterBlast(CFrame.new(pointTarget+Vector3.new(0,35,0),pointTarget));
		end;
	end);
	mouse.KeyDown:connect(function(key)
		if key==''then
			local pointTarget=mouse.Hit.p;
			for i=1,20 do
				wait();
				gasterBlast(CFrame.new(c.HumanoidRootPart.CFrame.p+Vector3.new(0,50,0),pointTarget):toWorldSpace(CFrame.new(math.sin(i/2)*(20-i),math.cos(i/2)*(20-i),-i)));
			end;
			largegasterBlast(CFrame.new(c.HumanoidRootPart.CFrame.p+Vector3.new(0,50,0),pointTarget):toWorldSpace(CFrame.new(0,0,-25)));
		end;
	end);
	mouse.Button1Down:connect(function()
		Debounces.isFlash=true;
	end);
	mouse.Button1Up:connect(function()
		Debounces.isFlash=false;
	end);
	mouse.KeyDown:connect(function(key)
		if key==''then
			if music.isPlaying then music:Stop();else music:Play();end;
		end;
	end);
	mouse.KeyDown:connect(function(key)
		if key==''then
			if music2.isPlaying then music2:Stop();else music2:Play();end;
		end;
	end);
	mouse.KeyDown:connect(function(key)
		if key==''then
			if music3.isPlaying then music3:Stop();else music3:Play();end;
		end;
	end);
	mouse.KeyDown:connect(function(key)
		if key==''then
			if music4.isPlaying then music4:Stop();else music4:Play();end;
		end;
	end);
	mouse.KeyDown:connect(function(key)
		if key==''then
			if music5.isPlaying then music4:Stop();else music5:Play();end;
		end;
	end);
	mouse.KeyDown:connect(function(key)
		if key==''then
			gasterBlast(c.Torso.CFrame.p+Vector3.new(math.sin(tick()*10)*10,12,math.cos(tick()*10)*10),mouse.Hit.p,true);
		end;
	end);
	mouse.KeyDown:connect(function(key)
		if key==''then
			largegasterBlast(c.Torso.CFrame.p+Vector3.new(math.sin(tick()*10)*10,12,math.cos(tick()*10)*10),mouse.Hit.p);
		end;
	end);
	mouse.KeyDown:connect(function(key)
		if key==''then
			for i=1,5 do
				wait();
				gasterBlast(c.Torso.CFrame.p+Vector3.new(math.sin(tick()*10)*10,12,math.cos(tick()*10)*10),mouse.Hit.p);
			end;
			largegasterBlast(c.Torso.CFrame.p+Vector3.new(0,25,0),mouse.Hit.p);
		end;
	end);
	mouse.KeyDown:connect(function(key)
		if key==''then
			local pointTarget=mouse.Hit.p;
			for i=1,20 do
				gasterBlast(pointTarget+Vector3.new(math.sin(math.deg((360/40)*i))*(20-i),5+i,math.cos(math.deg((360/40)*i))*(20-i)),pointTarget);
			end;
			wait(.2);
			for i=1,10 do
				largegasterBlast(pointTarget+Vector3.new(math.sin(math.deg((360/20)*i))*25,20,math.cos(math.deg((360/20)*i))*25),pointTarget);
			end;
		end;
	end);
	human.StateChanged:connect(function(os,ns)
		if c.HumanoidRootPart.Velocity.Y<.1 and Debounces.isJumping==true and ns==Enum.HumanoidStateType.Landed then
			Debounces.isJumping=false;
		end;
	end);
	for i=1,#Joints do
		Joints[i].C1=CFrameZero();
	end;
	rs.RenderStepped:connect(function()
		Debounces.FPS=1/rs.RenderStepped:wait();
		if Debounces.FPS<30 then
			Debounces.FPS=30;
		end;
		if Debounces.isSprinting then
			lerpBoom();
		else
			noBoom();
		end;
		for _,v in pairs(rayModel:children())do
			v.Transparency=v.Transparency+.06/(Debounces.FPS/60);
			if v.Transparency>.99 then v:Destroy();return;end;
			v.CanCollide=true;
			local tParts=v:GetTouchingParts();
			v.CanCollide=false;
			local vCFrame=v.CFrame;
			v.Size=v.Size+Vector3.new(0,1,1)/(Debounces.FPS/60);
			v.CFrame=vCFrame;
			for _,x in pairs(tParts)do
				if x and x.Parent and x.Parent:FindFirstChild'Humanoid'and x.Parent.Humanoid:isA'Humanoid'and x.Parent~=c then
					x.Parent.Humanoid:TakeDamage(1,2);
				end;
			end;
		end;
		local FPSLerp=AnimStat.lerpSpeed/(Debounces.FPS/60);
		for i=1,#Joints do
			Joints[i].C0=Joints[i].C0:lerp(JointTargets[i],FPSLerp);
		end;
	end)
	k()
end)

dawg.Name = "dawg"
dawg.Parent = main
dawg.BackgroundColor3 = Color3.fromRGB(85, 85, 85)
dawg.Position = UDim2.new(0.125, 0, 0.508200884, 0)
dawg.Size = UDim2.new(0, 134, 0, 32)
dawg.Font = Enum.Font.SciFi
dawg.Text = "Dawg"
dawg.TextColor3 = Color3.fromRGB(0, 0, 0)
dawg.TextSize = 35.000
dawg.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/H0fCpUYQ"))()
end)

l.Name = "l"
l.Parent = main
l.BackgroundColor3 = Color3.fromRGB(85, 85, 85)
l.Position = UDim2.new(0.125, 0, 0.569831133, 0)
l.Size = UDim2.new(0, 134, 0, 32)
l.Font = Enum.Font.SciFi
l.Text = "L"
l.TextColor3 = Color3.fromRGB(0, 0, 0)
l.TextSize = 35.000
l.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://pastebin.com/raw/VkWkuyzc", true))()
end)

table.Name = "table"
table.Parent = main
table.BackgroundColor3 = Color3.fromRGB(85, 85, 85)
table.Position = UDim2.new(0.125, 0, 0.630467296, 0)
table.Size = UDim2.new(0, 134, 0, 32)
table.Font = Enum.Font.SciFi
table.Text = "Table"
table.TextColor3 = Color3.fromRGB(0, 0, 0)
table.TextSize = 35.000
table.MouseButton1Down:connect(function()
	--made by Creatar#4019
	local plr = game.Players.LocalPlayer
	game:GetService("RunService").Stepped:Connect(function()
		setsimulationradius(9e9,9e9)
		plr.ReplicationFocus = workspace
		settings().Physics.AllowSleep = false
	end)
	--- thank you to ou1z to the script above
	local runservice=game:service"RunService";
	local player=game:service"Players"["LocalPlayer"];
	local character=player["Character"];
	character["Head"]:FindFirstChildOfClass"SpecialMesh":Destroy();

	character["Humanoid"].HipHeight=-2;
	character["Left Leg"]:BreakJoints();
	character["Right Leg"]:BreakJoints();
	character["Left Arm"]:BreakJoints();
	character["Right Arm"]:BreakJoints();
	while runservice["Heartbeat"]:Wait() do
		character["Left Leg"].CFrame=character["HumanoidRootPart"].CFrame*CFrame.new(-0.5,1.5,1.5) * CFrame.Angles(math.rad(90), 0, 0);
		character["Right Leg"].CFrame=character["HumanoidRootPart"].CFrame*CFrame.new(0.5,1.5,1.5) * CFrame.Angles(math.rad(90), 0, 0);
		character["Left Arm"].CFrame=character["HumanoidRootPart"].CFrame*CFrame.new(-0.5,0,2);
		character["Right Arm"].CFrame=character["HumanoidRootPart"].CFrame*CFrame.new(0.5,0,2);
	end
	-- made by Creatar aca Robloit aca Creatar#4019
end)

squat.Name = "squat"
squat.Parent = main
squat.BackgroundColor3 = Color3.fromRGB(85, 85, 85)
squat.Position = UDim2.new(0.125, 0, 0.687127352, 0)
squat.Size = UDim2.new(0, 134, 0, 32)
squat.Font = Enum.Font.SciFi
squat.Text = "Squat"
squat.TextColor3 = Color3.fromRGB(0, 0, 0)
squat.TextSize = 35.000
squat.MouseButton1Down:connect(function()
	HumanDied = false
	local CountSCIFIMOVIELOL = 1
	function SCIFIMOVIELOL(Part0,Part1,Position,Angle)
		local AlignPos = Instance.new('AlignPosition', Part1); AlignPos.Name = "AliP_"..CountSCIFIMOVIELOL
		AlignPos.ApplyAtCenterOfMass = true;
		AlignPos.MaxForce = 5772000--67752;
		AlignPos.MaxVelocity = math.huge/9e110;
		AlignPos.ReactionForceEnabled = false;
		AlignPos.Responsiveness = 200;
		AlignPos.RigidityEnabled = false;
		local AlignOri = Instance.new('AlignOrientation', Part1); AlignOri.Name = "AliO_"..CountSCIFIMOVIELOL
		AlignOri.MaxAngularVelocity = math.huge/9e110;
		AlignOri.MaxTorque = 5772000
		AlignOri.PrimaryAxisOnly = false;
		AlignOri.ReactionTorqueEnabled = false;
		AlignOri.Responsiveness = 200;
		AlignOri.RigidityEnabled = false;
		local AttachmentA=Instance.new('Attachment',Part1); AttachmentA.Name = "Ath_"..CountSCIFIMOVIELOL
		local AttachmentB=Instance.new('Attachment',Part0); AttachmentB.Name = "Ath_"..CountSCIFIMOVIELOL
		AttachmentA.Orientation = Angle or Vector3.new(0,0,0)
		AttachmentA.Position = Position or Vector3.new(0,0,0)
		AlignPos.Attachment1 = AttachmentA;
		AlignPos.Attachment0 = AttachmentB;
		AlignOri.Attachment1 = AttachmentA;
		AlignOri.Attachment0 = AttachmentB;
		CountSCIFIMOVIELOL = CountSCIFIMOVIELOL + 1
		return {AlignPos,AlignOri,AttachmentA,AttachmentB}
	end

	game:FindFirstChildOfClass("Players").LocalPlayer["Character"].Archivable = true
	local hatnameclone = {}
	for _,v in next, game:FindFirstChildOfClass("Players").LocalPlayer["Character"]:GetChildren() do
		if v:IsA("Accessory") then
			if hatnameclone[v.Name] then
				if hatnameclone[v.Name] == "s" then
					hatnameclone[v.Name] = {}
				end
				table.insert(hatnameclone[v.Name],v)
			else
				hatnameclone[v.Name] = "s"
			end
		end
	end
	for _,v in pairs(hatnameclone) do
		if type(v) == "table" then
			local num = 1
			for _,w in pairs(v) do
				w.Name = w.Name..num
				num = num + 1
			end
		end
	end
	hatnameclone = nil

	local DeadChar = game:FindFirstChildOfClass("Players").LocalPlayer.Character

	local fldr = Instance.new("Folder",game:FindFirstChildOfClass("Players").LocalPlayer["Character"])
	fldr.Name = "DMYF"
	local CloneChar = DeadChar:Clone()
	local ANIMATIONHERE
	if CloneChar:FindFirstChild("Animate") then
		ANIMATIONHERE = CloneChar:FindFirstChild("Animate"):Clone()
		CloneChar:FindFirstChild("Animate"):Destroy()
	end
	if CloneChar:FindFirstChildOfClass("Folder") then CloneChar:FindFirstChildOfClass("Folder"):Destroy() end
	if CloneChar.Torso:FindFirstChild("Neck") then
		local Clonessss = CloneChar.Torso:FindFirstChild("Neck"):Clone()
		Clonessss.Part0 = nil
		Clonessss.Part1 = DeadChar.Head
		Clonessss.Parent = DeadChar.Torso
	end
	CloneChar.Parent = fldr
	CloneChar.HumanoidRootPart.CFrame = DeadChar.HumanoidRootPart.CFrame
	CloneChar.Humanoid.BreakJointsOnDeath = false
	CloneChar.Name = "non"
	CloneChar.Humanoid.DisplayDistanceType = "None"

	for _,v in next, DeadChar:GetChildren() do
		if v:IsA("Accessory") then
			local topacc = false
			if v.Handle:FindFirstChildOfClass("Weld") then v.Handle:FindFirstChildOfClass("Weld"):Destroy() end
			v.Handle.Massless = true
			v.Handle.CanCollide = false
			if v.Handle:FindFirstChildOfClass("Attachment") then
				local ath__ = v.Handle:FindFirstChildOfClass("Attachment")
				if ath__.Name == "HatAttachment" or ath__.Name == "HairAttachment" or ath__.Name == "FaceFrontAttachment" or ath__.Name == "FaceCenterAttachment" then
					topacc = ath__.Name
				end
			end
			local bv = Instance.new("BodyVelocity",v.Handle)
			bv.Velocity = Vector3.new(0,0,0)
			coroutine.wrap(function()
				if topacc then
					local allthings = SCIFIMOVIELOL(v.Handle,DeadChar.Torso,Vector3.new(0,1.5,0)+ (DeadChar.Head[topacc].Position + (v.Handle[topacc].Position*-1)),Vector3.new(0,0,0))
					local normaltop = allthings[1].Attachment1
					local alipos = allthings[1]
					local alirot = allthings[2]
					local p0 = v.Handle
					local p1 = DeadChar.Head
					alipos.Parent = CloneChar:FindFirstChild(v.Name).Handle
					alirot.Parent = CloneChar:FindFirstChild(v.Name).Handle
					while true do
						game:GetService("RunService").RenderStepped:wait()
						if HumanDied then break end
						coroutine.wrap(function()
							if alipos.Attachment1 == normaltop then
								p0.CFrame = p0.CFrame:lerp((((DeadChar.Torso.CFrame * CFrame.new(0,1.5,0)) * p1[topacc].CFrame) * p0[topacc].CFrame:inverse()),1)
							else
								v.Handle.CFrame = v.Handle.CFrame:lerp(alipos.Attachment1.Parent.CFrame * CFrame.new(alipos.Attachment1.Position) * CFrame.Angles(math.rad(alipos.Attachment1.Rotation.X),math.rad(alipos.Attachment1.Rotation.Y),math.rad(alipos.Attachment1.Rotation.Z)),1)
							end
						end)()
					end
				else
					SCIFIMOVIELOL(v.Handle,CloneChar[v.Name].Handle,Vector3.new(0,0,0),Vector3.new(0,0,0))
				end
			end)()
		end
	end

	local a = DeadChar.Torso
	local b = DeadChar.HumanoidRootPart
	local c = DeadChar.Humanoid
	a.Parent = game:FindFirstChildOfClass("Workspace")
	c.Parent = game:FindFirstChildOfClass("Workspace")
	local told = a:Clone()
	local told1 = c:Clone()
	b["RootJoint"].Part0 = told
	b["RootJoint"].Part1 = DeadChar.Head
	a.Name = "torso"
	a.Neck:Destroy()
	c.Name = "Mizt Hub Best"
	told.Parent = DeadChar
	told1.Parent = DeadChar
	DeadChar.PrimaryPart = told
	told1.Health = 0
	b:Destroy()
	a.Parent = DeadChar
	c.Parent = DeadChar
	told:Destroy()
	told1:Destroy()
	a.Name = "Torso"

	if CloneChar.Head:FindFirstChildOfClass("Decal") then CloneChar.Head:FindFirstChildOfClass("Decal").Transparency = 1 end
	if DeadChar:FindFirstChild("Animate") then DeadChar:FindFirstChild("Animate"):Destroy() end

	local Collider
	function UnCollide()
		if HumanDied then Collider:Disconnect(); return end
		for _,Parts in next, CloneChar:GetChildren() do
			if Parts:IsA("BasePart") then
				Parts.CanCollide = false 
			end 
		end
		for _,Parts in next, DeadChar:GetChildren() do
			if Parts:IsA("BasePart") then
				Parts.CanCollide = false
			end 
		end 
	end
	Collider = game:GetService("RunService").Stepped:Connect(UnCollide)

	local resetBindable = Instance.new("BindableEvent")
	resetBindable.Event:connect(function()
		game:GetService("StarterGui"):SetCore("ResetButtonCallback", true)
		resetBindable:Destroy()
		HumanDied = true
		pcall(function()
			game:FindFirstChildOfClass("Players").LocalPlayer.Character = DeadChar
			DeadChar.Head:Destroy()
			DeadChar:FindFirstChildOfClass("Humanoid"):Destroy()
			game:FindFirstChildOfClass("Players").LocalPlayer.Character = CloneChar
			if DeadChar:FindFirstChildOfClass("Folder") then DeadChar:FindFirstChildOfClass("Folder"):Destroy() end
		end)
	end)
	game:GetService("StarterGui"):SetCore("ResetButtonCallback", resetBindable)

	coroutine.wrap(function()
		while true do
			game:GetService("RunService").RenderStepped:wait()
			if not CloneChar or not CloneChar:FindFirstChild("Head") or not CloneChar:FindFirstChildOfClass("Humanoid") or CloneChar:FindFirstChildOfClass("Humanoid").Health <= 0 and not DeadChar or not DeadChar:FindFirstChild("Head") or not DeadChar:FindFirstChildOfClass("Humanoid") or DeadChar:FindFirstChildOfClass("Humanoid").Health <= 0 then 
				HumanDied = true
				pcall(function()
					game:FindFirstChildOfClass("Players").LocalPlayer.Character = DeadChar
					DeadChar.Head:Destroy()
					DeadChar:FindFirstChildOfClass("Humanoid"):Destroy()
					game:FindFirstChildOfClass("Players").LocalPlayer.Character = CloneChar
					if DeadChar:FindFirstChildOfClass("Folder") then DeadChar:FindFirstChildOfClass("Folder"):Destroy() end
				end)
				if resetBindable then
					game:GetService("StarterGui"):SetCore("ResetButtonCallback", true)
					resetBindable:Destroy()
				end
				break
			end     
		end
	end)()


	SCIFIMOVIELOL(DeadChar["Head"],CloneChar["Head"])
	SCIFIMOVIELOL(DeadChar["Torso"],CloneChar["Torso"])
	SCIFIMOVIELOL(DeadChar["Left Arm"],CloneChar["Left Arm"])
	SCIFIMOVIELOL(DeadChar["Right Arm"],CloneChar["Right Arm"])
	SCIFIMOVIELOL(DeadChar["Left Leg"],CloneChar["Left Leg"])
	SCIFIMOVIELOL(DeadChar["Right Leg"],CloneChar["Right Leg"])

	for _,v in pairs(DeadChar:GetChildren()) do
		if v:IsA("BasePart") and v.Name ~= "Head" then
        --[[local bv = Instance.new("BodyVelocity",v)
        bv.Velocity = Vector3.new(0,0,0)
        coroutine.wrap(function()
            while true do
                game:GetService("RunService").RenderStepped:wait()
                if HumanDied then break end
                v.CFrame = CloneChar[v.Name].CFrame
            end
        end)()]]
		elseif v:IsA("BasePart") and v.Name == "Head" then
			local bv = Instance.new("BodyVelocity",v)
			bv.Velocity = Vector3.new(0,0,0)
			coroutine.wrap(function()
				while true do
					game:GetService("RunService").RenderStepped:wait()
					if HumanDied then break end
					v.CFrame = DeadChar.Torso.CFrame * CFrame.new(0,1.5,0)
				end
			end)()
		end
	end

	for _,BodyParts in next, CloneChar:GetDescendants() do
		if BodyParts:IsA("BasePart") or BodyParts:IsA("Part") then
			BodyParts.Transparency = 1 end end
	game:GetService("RunService").RenderStepped:wait()
	game:FindFirstChildOfClass("Players").LocalPlayer.Character = CloneChar
	game:FindFirstChildOfClass("Workspace"):FindFirstChildOfClass("Camera").CameraSubject = CloneChar.Humanoid

	for _,v in next, DeadChar:GetChildren() do
		if v:IsA("Accessory") then
			if v.Handle:FindFirstChildOfClass("Weld") then v.Handle:FindFirstChildOfClass("Weld"):Destroy() end
		end
	end

	if ANIMATIONHERE then ANIMATIONHERE.Parent = CloneChar end
	Player = game.Players.LocalPlayer
	PlayerGui = Player.PlayerGui
	Mouse = Player:GetMouse()
	Cam = workspace.CurrentCamera
	Backpack = Player.Backpack
	Character = Player.Character
	Humanoid = Character.Humanoid
	RootPart = Character["HumanoidRootPart"]
	Torso = Character["Torso"]
	Head = Character["Head"]
	RightArm = Character["Right Arm"]
	LeftArm = Character["Left Arm"]
	RightLeg = Character["Right Leg"]
	LeftLeg = Character["Left Leg"]
	RootJoint = RootPart["RootJoint"]
	Neck = Torso["Neck"]
	RightShoulder = Torso["Right Shoulder"]
	LeftShoulder = Torso["Left Shoulder"]
	RightHip = Torso["Right Hip"]
	LeftHip = Torso["Left Hip"]
	local sick = Instance.new("Sound",Character)
	sick.Parent = Torso
	sick.Name = "comander_cool"
	sick:resume()
	sick.Looped = true
	sick.Volume = 1
	sick.SoundId = "rbxassetid://935994277"
	sick.Pitch = 1
	IT = Instance.new
	CF = CFrame.new
	VT = Vector3.new
	RAD = math.rad
	C3 = Color3.new
	UD2 = UDim2.new
	BRICKC = BrickColor.new
	ANGLES = CFrame.Angles
	EULER = CFrame.fromEulerAnglesXYZ
	COS = math.cos
	ACOS = math.acos
	SIN = math.sin
	ASIN = math.asin
	ABS = math.abs
	MRANDOM = math.random
	FLOOR = math.floor
	it = Instance.new
	MODE = "1"
	Animation_Speed = 3
	local FORCERESET = false
	Frame_Speed = 1 / 60 -- (1 / 30) OR (1 / 60)
	local Speed = 16
	local ROOTC0 = CF(0, 0, 0) * ANGLES(RAD(-90), RAD(0), RAD(180))
	local NECKC0 = CF(0, 1, 0) * ANGLES(RAD(-90), RAD(0), RAD(180))
	local HOODC0 = CF(0, 0, 0) * ANGLES(RAD(0), RAD(0), RAD(0))
	local SHOTGUNC0 = CF(0, 0, 0) * ANGLES(RAD(0), RAD(0), RAD(0))
	local RIGHTSHOULDERC0 = CF(-0.5, 0, 0) * ANGLES(RAD(0), RAD(90), RAD(0))
	local LEFTSHOULDERC0 = CF(0.5, 0, 0) * ANGLES(RAD(0), RAD(-90), RAD(0))
	local DAMAGEMULTIPLIER = 1
	local ANIM = "Idle"
	local ATTACK = false
	local EQUIPPED = false
	local HOLD = false
	local COMBO = 1
	local Rooted = false
	local SINE = 0
	local s = 0
	local c = 1
	local anchrd = false
	local RUN = game:service'RunService'
	local KEYHOLD = false
	local CHANGE = 2 / Animation_Speed
	local WALKINGANIM = false
	local VALUE1 = false
	local AntiBanish = true
	local AMODE = "box"
	local ROBLOXIDLEANIMATION = IT("Animation")
	ROBLOXIDLEANIMATION.Name = "Roblox Idle Animation"
	ROBLOXIDLEANIMATION.AnimationId = "http://www.roblox.com/asset/?id=180435571"
	local NICE = 2.8
	local VALUE3 = false
	--ROBLOXIDLEANIMATION.Parent = Humanoid

	local Effects = IT("Folder", Character)
	Effects.Name = "Effects"

	local ANIMATOR = Humanoid.Animator
	local ANIMATE = Character:FindFirstChild("Animate")
	local UNANCHOR = true
	local TOBANISH = {}
	local SKILLFONT = "Arcade"
	--//=================================\\
	--\\=================================//

	local S = setmetatable({},{__index = function(s,i) return game:service(i) end})
	local Plrs = S.Players
	NewInstance = function(instance,parent,properties)
		local inst = Instance.new(instance)
		inst.Parent = parent
		if(properties)then
			for i,v in next, properties do
				pcall(function() inst[i] = v end)
			end
		end
		return inst;
	end

	function shakes(power,length)
		for i,v in pairs(game:GetService("Players"):GetChildren()) do
			local var = script.Shaker:Clone()
			var.Parent = v.Character
			local pw = var.Shakeval
			local lgth = var.MultLength
			pw.Value = power
			lgth.Value = length
			var.Disabled = false
			game:GetService("Debris"):AddItem(var, length+4)
		end
	end

	ff = Instance.new("ForceField",Character)
	ff.Visible = false

	function localshakes(power,length)
		local var = script.Shaker:Clone()
		var.Parent = Player.Character
		local pw = var.Shakeval
		local lgth = var.MultLength
		pw.Value = power
		lgth.Value = length
		var.Disabled = false
		game:GetService("Debris"):AddItem(var, length+4)
	end



	local MATTER = {"Plastic","Wood","Slate","Concrete","CorrodedMetal","DiamondPlate","Foil","Grass","Ice","Marble","Granite","Brick","Pebble","Sand","Fabric","SmoothPlastic","Metal","WoodPlanks","Cobblestone","Air","Water","Rock","Glacier","Snow","Sandstone","Mud","Basalt","Ground","CrackedLava","Neon","Glass","Asphalt","LeafyGrass","Salt","Limestone","Pavement","ForceField"}

	local PlayerSize = 1
	local FT,FRA,FLA,FRL,FLL = Instance.new("SpecialMesh"),Instance.new("SpecialMesh"),Instance.new("SpecialMesh"),Instance.new("SpecialMesh"),Instance.new("SpecialMesh")
	FT.MeshId,FT.Scale = "rbxasset://fonts/torso.mesh",Vector3.new(PlayerSize,PlayerSize,PlayerSize)
	FRA.MeshId,FRA.Scale = "rbxasset://fonts/rightarm.mesh",Vector3.new(PlayerSize,PlayerSize,PlayerSize)
	FLA.MeshId,FLA.Scale = "rbxasset://fonts/leftarm.mesh",Vector3.new(PlayerSize,PlayerSize,PlayerSize)
	FRL.MeshId,FRL.Scale = "rbxasset://fonts/rightleg.mesh",Vector3.new(PlayerSize,PlayerSize,PlayerSize)
	FLL.MeshId,FLL.Scale = "rbxasset://fonts/leftleg.mesh",Vector3.new(PlayerSize,PlayerSize,PlayerSize)

	local AUDIOS = {"rbxassetid://844654533","rbxassetid://1439600000","rbxassetid://2256088590","rbxassetid://3154204326"}

	if Player.Character:FindFirstChild("Animate") then
		local an = Humanoid:GetPlayingAnimationTracks()
		for i = 1, #an do
			an[i]:Stop()
		end
		Humanoid.Animator:Destroy()
		Player.Character:FindFirstChild("Animate"):Destroy()
		ANIMATOR:Destroy()
		ANIMATE:Destroy()
	end
	local fakerot = 0

	local mde = "normal"


	function BypassGS(sound)
		Instance.new("StringValue",sound).Name = "PleaseDontDestroyMeImAGoodBoiSoundSoPleaseDontDestroyMe"
	end

	--//=================================\\
	--|| SAZERENOS' ARTIFICIAL HEARTBEAT
	--\\=================================//
	--DO NOT TOUCH THIS
	if Character:FindFirstChild("Adds")then wait(.2) script.Disabled = true script:Destroy() error("You Shouldn't Have Added A Banisher Gun To My Script") end

	ArtificialHB = Instance.new("BindableEvent", script)
	ArtificialHB.Name = "ArtificialHB"

	script:WaitForChild("ArtificialHB")

	frame = Frame_Speed
	tf = 0
	allowframeloss = false
	tossremainder = false
	lastframe = tick()
	script.ArtificialHB:Fire()

	game:GetService("RunService").Heartbeat:connect(function(s, p)
		tf = tf + s
		if tf >= frame then
			if allowframeloss then
				script.ArtificialHB:Fire()
				lastframe = tick()
			else
				for i = 1, math.floor(tf / frame) do
					script.ArtificialHB:Fire()
				end
				lastframe = tick()
			end
			if tossremainder then
				tf = 0
			else
				tf = tf - frame * math.floor(tf / frame)
			end
		end
	end)
	function Raycast(POSITION, DIRECTION, RANGE, IGNOREDECENDANTS)
		return workspace:FindPartOnRay(Ray.new(POSITION, DIRECTION.unit * RANGE), IGNOREDECENDANTS)
	end

	function PositiveAngle(NUMBER)
		if NUMBER >= 0 then
			NUMBER = 0
		end
		return NUMBER
	end

	function NegativeAngle(NUMBER)
		if NUMBER <= 0 then
			NUMBER = 0
		end
		return NUMBER
	end
	function Rwait(num)
		if num == 0 or num == nil then
			RUN.Stepped:wait()
		else
			for i=0,num do
				RUN.Stepped:wait()
			end
		end
	end

	function Swait(NUMBER)
		if NUMBER == 0 or NUMBER == nil then
			ArtificialHB.Event:wait()
		else
			for i = 1, NUMBER do
				ArtificialHB.Event:wait()
			end
		end
	end
	BypassGS(sick)
	local S = IT("Sound",script)
	function CreateSound(ID, PARENT, VOLUME, PITCH, DOESLOOP)
		local NEWSOUND = nil
		coroutine.resume(coroutine.create(function()
			NEWSOUND = S:Clone()
			BypassGS(NEWSOUND)
			NEWSOUND.Parent = PARENT
			NEWSOUND.Volume = VOLUME
			NEWSOUND.Pitch = PITCH
			NEWSOUND.SoundId = "http://www.roblox.com/asset/?id="..ID
			NEWSOUND:play()
			if DOESLOOP == true then
				NEWSOUND.Looped = true
			else
				repeat wait(1) until NEWSOUND.Playing == false or NEWSOUND.Parent ~= PARENT
				NEWSOUND:remove()
			end
		end))
		return NEWSOUND
	end

	function CreateSound2(ID, PARENT, VOLUME, PITCH, TIMEPOS, DOESLOOP)
		local NEWSOUND = nil
		coroutine.resume(coroutine.create(function()
			NEWSOUND = S:Clone()
			BypassGS(NEWSOUND)
			NEWSOUND.Parent = PARENT
			NEWSOUND.Volume = VOLUME
			NEWSOUND.Pitch = PITCH
			NEWSOUND.TimePosition = TIMEPOS
			NEWSOUND.SoundId = "http://www.roblox.com/asset/?id="..ID
			NEWSOUND:play()
			if DOESLOOP == true then
				NEWSOUND.Looped = true
			else
				repeat wait(1) until NEWSOUND.Playing == false or NEWSOUND.Parent ~= PARENT
				NEWSOUND:remove()
			end
		end))
		return NEWSOUND
	end

	function CreateMesh(MESH, PARENT, MESHTYPE, MESHID, TEXTUREID, SCALE, OFFSET)
		local NEWMESH = IT(MESH)
		if MESH == "SpecialMesh" then
			NEWMESH.MeshType = MESHTYPE
			if MESHID ~= "nil" and MESHID ~= "" then
				NEWMESH.MeshId = "http://www.roblox.com/asset/?id="..MESHID
			end
			if TEXTUREID ~= "nil" and TEXTUREID ~= "" then
				NEWMESH.TextureId = "http://www.roblox.com/asset/?id="..TEXTUREID
			end
		end
		NEWMESH.Offset = OFFSET or VT(0, 0, 0)
		NEWMESH.Scale = SCALE
		NEWMESH.Parent = PARENT
		return NEWMESH
	end

	function CreatePart(FORMFACTOR, PARENT, MATERIAL, REFLECTANCE, TRANSPARENCY, BRICKCOLOR, NAME, SIZE, ANCHOR)
		local NEWPART = IT("Part")
		NEWPART.formFactor = FORMFACTOR
		NEWPART.Reflectance = REFLECTANCE
		NEWPART.Transparency = TRANSPARENCY
		NEWPART.CanCollide = false
		NEWPART.Locked = true
		NEWPART.Anchored = true
		if ANCHOR == false then
			NEWPART.Anchored = false
		end
		NEWPART.BrickColor = BRICKC(tostring(BRICKCOLOR))
		NEWPART.Name = NAME
		NEWPART.Size = SIZE
		NEWPART.Position = Torso.Position
		NEWPART.Material = MATERIAL
		NEWPART:BreakJoints()
		NEWPART.Parent = PARENT
		return NEWPART
	end

	local function weldBetween(a, b)
		local weldd = Instance.new("ManualWeld")
		weldd.Part0 = a
		weldd.Part1 = b
		weldd.C0 = CFrame.new()
		weldd.C1 = b.CFrame:inverse() * a.CFrame
		weldd.Parent = a
		return weldd
	end


	function QuaternionFromCFrame(cf)
		local mx, my, mz, m00, m01, m02, m10, m11, m12, m20, m21, m22 = cf:components()
		local trace = m00 + m11 + m22
		if trace > 0 then 
			local s = math.sqrt(1 + trace)
			local recip = 0.5 / s
			return (m21 - m12) * recip, (m02 - m20) * recip, (m10 - m01) * recip, s * 0.5
		else
			local i = 0
			if m11 > m00 then
				i = 1
			end
			if m22 > (i == 0 and m00 or m11) then
				i = 2
			end
			if i == 0 then
				local s = math.sqrt(m00 - m11 - m22 + 1)
				local recip = 0.5 / s
				return 0.5 * s, (m10 + m01) * recip, (m20 + m02) * recip, (m21 - m12) * recip
			elseif i == 1 then
				local s = math.sqrt(m11 - m22 - m00 + 1)
				local recip = 0.5 / s
				return (m01 + m10) * recip, 0.5 * s, (m21 + m12) * recip, (m02 - m20) * recip
			elseif i == 2 then
				local s = math.sqrt(m22 - m00 - m11 + 1)
				local recip = 0.5 / s return (m02 + m20) * recip, (m12 + m21) * recip, 0.5 * s, (m10 - m01) * recip
			end
		end
	end

	function QuaternionToCFrame(px, py, pz, x, y, z, w)
		local xs, ys, zs = x + x, y + y, z + z
		local wx, wy, wz = w * xs, w * ys, w * zs
		local xx = x * xs
		local xy = x * ys
		local xz = x * zs
		local yy = y * ys
		local yz = y * zs
		local zz = z * zs
		return CFrame.new(px, py, pz, 1 - (yy + zz), xy - wz, xz + wy, xy + wz, 1 - (xx + zz), yz - wx, xz - wy, yz + wx, 1 - (xx + yy))
	end

	function QuaternionSlerp(a, b, t)
		local cosTheta = a[1] * b[1] + a[2] * b[2] + a[3] * b[3] + a[4] * b[4]
		local startInterp, finishInterp;
		if cosTheta >= 0.0001 then
			if (1 - cosTheta) > 0.0001 then
				local theta = ACOS(cosTheta)
				local invSinTheta = 1 / SIN(theta)
				startInterp = SIN((1 - t) * theta) * invSinTheta
				finishInterp = SIN(t * theta) * invSinTheta
			else
				startInterp = 1 - t
				finishInterp = t
			end
		else
			if (1 + cosTheta) > 0.0001 then
				local theta = ACOS(-cosTheta)
				local invSinTheta = 1 / SIN(theta)
				startInterp = SIN((t - 1) * theta) * invSinTheta
				finishInterp = SIN(t * theta) * invSinTheta
			else
				startInterp = t - 1
				finishInterp = t
			end
		end
		return a[1] * startInterp + b[1] * finishInterp, a[2] * startInterp + b[2] * finishInterp, a[3] * startInterp + b[3] * finishInterp, a[4] * startInterp + b[4] * finishInterp
	end

	function Clerp(a, b, t)
		local qa = {QuaternionFromCFrame(a)}
		local qb = {QuaternionFromCFrame(b)}
		local ax, ay, az = a.x, a.y, a.z
		local bx, by, bz = b.x, b.y, b.z
		local _t = 1 - t
		return QuaternionToCFrame(_t * ax + t * bx, _t * ay + t * by, _t * az + t * bz, QuaternionSlerp(qa, qb, t))
	end
	function NoOutlines(PART)
		PART.TopSurface, PART.BottomSurface, PART.LeftSurface, PART.RightSurface, PART.FrontSurface, PART.BackSurface = 10, 10, 10, 10, 10, 10
	end

	function CreateWeldOrSnapOrMotor(TYPE, PARENT, PART0, PART1, C0, C1)
		local NEWWELD = IT(TYPE)
		NEWWELD.Part0 = PART0
		NEWWELD.Part1 = PART1
		NEWWELD.C0 = C0
		NEWWELD.C1 = C1
		NEWWELD.Parent = PARENT
		return NEWWELD
	end
	function MakeForm(PART,TYPE)
		if TYPE == "Cyl" then
			local MSH = IT("CylinderMesh",PART)
		elseif TYPE == "Ball" then
			local MSH = IT("SpecialMesh",PART)
			MSH.MeshType = "Sphere"
		elseif TYPE == "Wedge" then
			local MSH = IT("SpecialMesh",PART)
			MSH.MeshType = "Wedge"
		end
	end

	Debris = game:GetService("Debris")

	function CastProperRay(StartPos, EndPos, Distance, Ignore)
		local DIRECTION = CF(StartPos,EndPos).lookVector
		return Raycast(StartPos, DIRECTION, Distance, Ignore)
	end

	function turnto(position)
		RootPart.CFrame=CFrame.new(RootPart.CFrame.p,VT(position.X,RootPart.Position.Y,position.Z)) * CFrame.new(0, 0, 0)
	end
	function ApplyDamage(Humanoid,Damage)
		Damage = Damage * DAMAGEMULTIPLIER
		if Humanoid.Health < 2000 then
			if Humanoid.Health - Damage > 0 then
				Humanoid.Health = Humanoid.Health - Damage
			else
				Humanoid.Parent:BreakJoints()
			end
		else
			Humanoid.Parent:BreakJoints()
		end
	end

	function Fancy_spawntrail(LOC,AIMTO,OUCH)
		WACKYEFFECT2({Time = 25, EffectType = "Block", Size = VT(0,0,0), Size2 = VT(1.1,1.1,1.1), Transparency = 0, Transparency2 = 1, CFrame = CF(LOC), MoveToPos = nil, RotationX = 0, RotationY = 0, RotationZ = 0, Material = "Neon", Color = BRICKC"New Yeller".Color, SoundID = nil, SoundPitch = nil, SoundVolume = nil})
		for i = 1, 1 do
			local POS1 = CF(LOC,AIMTO)*CF(0,0,-45).p
			local AIMPOS = CF(LOC,POS1) * CF(0,0,-45) * ANGLES(RAD(MRANDOM(-25,25)), RAD(MRANDOM(-25,25)), RAD(MRANDOM(-25,25)))*CF(0,0,MRANDOM(5,75)/10).p
			local HIT,POS = CastProperRay(LOC,AIMPOS,1000,Character)
			local DISTANCE = (POS - LOC).Magnitude
			if HIT then
				local HUM = nil
				if HIT.Parent:FindFirstChildOfClass("Humanoid") then
					HUM = HIT.Parent:FindFirstChildOfClass("Humanoid")
				elseif HIT.Parent.Parent:FindFirstChildOfClass("Humanoid") then
					HUM = HIT.Parent.Parent:FindFirstChildOfClass("Humanoid")
				end
				if HUM then
					Kill3(HIT.Parent)
				end
			end

			WACKYEFFECT2({Time = 20, EffectType = "Block", Size = VT(0,0,0), Size2 = VT(1,1,1), Transparency = 0, Transparency2 = 1, CFrame = CF(POS), MoveToPos = nil, RotationX = 0, RotationY = 0, RotationZ = 0, Material = "Neon", Color = BRICKC"New Yeller".Color, SoundID = nil, SoundPitch = 1, SoundVolume = 4})
			WACKYEFFECT2({Time = 20, EffectType = "Box", Size = VT(0,0,DISTANCE), Size2 = VT(0.7,0.7,DISTANCE), Transparency = 0.6, Transparency2 = 1, CFrame = CF(LOC,POS)*CF(0,0,-DISTANCE/2), MoveToPos = nil, RotationX = 0, RotationY = 0, RotationZ = 0, Material = "Neon", Color = BRICKC"New Yeller".Color, SoundID = nil, SoundPitch = nil, SoundVolume = nil})
		end
	end


	function Fancy_spawntrail3(LOC,AIMTO,OUCH)
		WACKYEFFECT2({Time = 25, EffectType = "Block", Size = VT(0,0,0), Size2 = VT(1.1,1.1,1.1), Transparency = 0, Transparency2 = 1, CFrame = CF(LOC), MoveToPos = nil, RotationX = 0, RotationY = 0, RotationZ = 0, Material = "Neon", Color = BRICKC"New Yeller".Color, SoundID = nil, SoundPitch = nil, SoundVolume = nil})
		for i = 1, 1 do
			local POS1 = CF(LOC,AIMTO)*CF(0,0,-45).p
			local AIMPOS = CF(LOC,POS1) * CF(0,0,-45) * ANGLES(RAD(MRANDOM(-0,0)), RAD(MRANDOM(-0,0)), RAD(MRANDOM(-0,0)))*CF(0,0,MRANDOM(5,75)/10).p
			local HIT,POS = CastProperRay(LOC,AIMPOS,1000,Character)
			local DISTANCE = (POS - LOC).Magnitude
			if HIT then
				local HUM = nil
				if HIT.Parent:FindFirstChildOfClass("Humanoid") then
					HUM = HIT.Parent:FindFirstChildOfClass("Humanoid")
				elseif HIT.Parent.Parent:FindFirstChildOfClass("Humanoid") then
					HUM = HIT.Parent.Parent:FindFirstChildOfClass("Humanoid")
				end
				if HUM then
					Kill2(HUM)
					BEAN(HUM)
				end
			end
			WACKYEFFECT2({Time = 20, EffectType = "Block", Size = VT(0,0,0), Size2 = VT(1,1,1), Transparency = 0, Transparency2 = 1, CFrame = CF(POS), MoveToPos = nil, RotationX = 0, RotationY = 0, RotationZ = 0, Material = "Neon", Color = BRICKC"New Yeller".Color, SoundID = nil, SoundPitch = 1, SoundVolume = 4})
			WACKYEFFECT2({Time = 20, EffectType = "Box", Size = VT(0,0,DISTANCE), Size2 = VT(0.7,0.7,DISTANCE), Transparency = 0.6, Transparency2 = 1, CFrame = CF(LOC,POS)*CF(0,0,-DISTANCE/2), MoveToPos = nil, RotationX = 0, RotationY = 0, RotationZ = 0, Material = "Neon", Color = BRICKC"New Yeller".Color, SoundID = nil, SoundPitch = nil, SoundVolume = nil})
		end
	end


	function Fancy_spawntrail2(LOC,AIMTO,OUCH)
		WACKYEFFECT({Time = 25, EffectType = "Block", Size = VT(0,0,0), Size2 = VT(0.3,0.3,0.3), Transparency = 0, Transparency2 = 1, CFrame = CF(LOC), MoveToPos = nil, RotationX = 0, RotationY = 0, RotationZ = 0, Material = "Neon", Color = BRICKC"New Yeller".Color, SoundID = nil, SoundPitch = nil, SoundVolume = nil})
		for i = 1, 1 do
			local POS1 = CF(LOC,AIMTO)*CF(0,0,-45).p
			local AIMPOS = CF(LOC,POS1) * CF(0,0,-45) * ANGLES(RAD(MRANDOM(0,15)), RAD(MRANDOM(0,15)), RAD(MRANDOM(0,15)))*CF(0,0,MRANDOM(5,75)/10).p
			local HIT,POS = CastProperRay(LOC,AIMPOS,1000,Character)
			local DISTANCE = (POS - LOC).Magnitude
			WACKYEFFECT2({Time = 20, EffectType = "Block", Size = VT(0,0,0), Size2 = VT(0.3,0.3,0.3), Transparency = 0, Transparency2 = 1, CFrame = CF(POS), MoveToPos = nil, RotationX = 0, RotationY = 0, RotationZ = 0, Material = "Neon", Color = BRICKC"New Yeller".Color, SoundID = nil, SoundPitch = nil, SoundVolume = nil})
			WACKYEFFECT2({Time = 20, EffectType = "Box", Size = VT(0,0,DISTANCE), Size2 = VT(0.1,0.1,DISTANCE), Transparency = 0.6, Transparency2 = 1, CFrame = CF(LOC,POS)*CF(0,0,-DISTANCE/2), MoveToPos = nil, RotationX = 0, RotationY = 0, RotationZ = 0, Material = "Neon", Color = BRICKC"New Yeller".Color, SoundID = nil, SoundPitch = nil, SoundVolume = nil})
		end
	end

	function SpawnTrail(FROM,TO,BIG)
		local TRAIL = CreatePart(3, Effects, "Neon", 0, 0.5, "Really red", "Trail", VT(0,0,0))
		MakeForm(TRAIL,"Cyl")
		local DIST = (FROM - TO).Magnitude
		if BIG == true then
			TRAIL.Size = VT(0.5,DIST,0.5)
		else
			TRAIL.Size = VT(0.25,DIST,0.25)
		end
		TRAIL.CFrame = CF(FROM, TO) * CF(0, 0, -DIST/2) * ANGLES(RAD(90),RAD(0),RAD(0))
		coroutine.resume(coroutine.create(function()
			for i = 1, 5 do
				Swait()
				TRAIL.Transparency = TRAIL.Transparency + 0.1
			end
			TRAIL:remove()
		end))
	end

	function WACKYEFFECT2(Table)
		local TYPE = (Table.EffectType or "Sphere")
		local SIZE = (Table.Size or VT(1,1,1))
		local ENDSIZE = (Table.Size2 or VT(0,0,0))
		local TRANSPARENCY = (Table.Transparency or 0)
		local ENDTRANSPARENCY = (Table.Transparency2 or 1)
		local CFRAME = (Table.CFrame or Torso.CFrame)
		local MOVEDIRECTION = (Table.MoveToPos or nil)
		local ROTATION1 = (Table.RotationX or 0)
		local ROTATION2 = (Table.RotationY or 0)
		local ROTATION3 = (Table.RotationZ or 0)
		local MATERIAL = (Table.Material or "Neon")
		local COLOR = (Table.Color or C3(1,1,1))
		local TIME = (Table.Time or 45)
		local SOUNDID = (Table.SoundID or nil)
		local SOUNDPITCH = (Table.SoundPitch or nil)
		local SOUNDVOLUME = (Table.SoundVolume or nil)
		local USEBOOMERANGMATH = (Table.UseBoomerangMath or false)
		local BOOMERANG = (Table.Boomerang or 0)
		local SIZEBOOMERANG = (Table.SizeBoomerang or 0)
		coroutine.resume(coroutine.create(function()
			local PLAYSSOUND = false
			local SOUND = nil
			local EFFECT = CreatePart(3, Effects, MATERIAL, 0, TRANSPARENCY, BRICKC("Pearl"), "Effect", VT(1,1,1), true)
			if SOUNDID ~= nil and SOUNDPITCH ~= nil and SOUNDVOLUME ~= nil then
				PLAYSSOUND = true
				SOUND = CreateSound(SOUNDID, EFFECT, SOUNDVOLUME, SOUNDPITCH, false)
			end
			EFFECT.Color = COLOR
			local MSH = nil
			if TYPE == "Sphere" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "Sphere", "", "", SIZE, VT(0,0,0))
			elseif TYPE == "Block" or TYPE == "Box" then
				MSH = IT("BlockMesh",EFFECT)
				MSH.Scale = SIZE
			elseif TYPE == "Wave" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "20329976", "", SIZE, VT(0,0,-SIZE.X/8))
			elseif TYPE == "Ring" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "559831844", "", VT(SIZE.X,SIZE.X,0.1), VT(0,0,0))
			elseif TYPE == "Slash" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "662586858", "", VT(SIZE.X/10,0,SIZE.X/10), VT(0,0,0))
			elseif TYPE == "Round Slash" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "662585058", "", VT(SIZE.X/10,0,SIZE.X/10), VT(0,0,0))
			elseif TYPE == "Swirl" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "168892432", "", SIZE, VT(0,0,0))
			elseif TYPE == "Skull" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "4770583", "", SIZE, VT(0,0,0))
			elseif TYPE == "Crystal" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "9756362", "", SIZE, VT(0,0,0))
			end
			if MSH ~= nil then
				local BOOMR1 = 1+BOOMERANG/50
				local BOOMR2 = 1+SIZEBOOMERANG/50
				local MOVESPEED = nil
				if MOVEDIRECTION ~= nil then
					if USEBOOMERANGMATH == true then
						MOVESPEED = ((CFRAME.p - MOVEDIRECTION).Magnitude/TIME)*BOOMR1
					else
						MOVESPEED = ((CFRAME.p - MOVEDIRECTION).Magnitude/TIME)
					end
				end
				local GROWTH = nil
				if USEBOOMERANGMATH == true then
					GROWTH = (SIZE - ENDSIZE)*(BOOMR2+1)
				else
					GROWTH = (SIZE - ENDSIZE)
				end
				local TRANS = TRANSPARENCY - ENDTRANSPARENCY
				if TYPE == "Block" then
					EFFECT.CFrame = CFRAME*ANGLES(RAD(MRANDOM(0,360)),RAD(MRANDOM(0,360)),RAD(MRANDOM(0,360)))
				else
					EFFECT.CFrame = CFRAME
				end
				if USEBOOMERANGMATH == true then
					for LOOP = 1, TIME+1 do
						Swait()
						MSH.Scale = MSH.Scale - (VT((GROWTH.X)*((1 - (LOOP/TIME)*BOOMR2)),(GROWTH.Y)*((1 - (LOOP/TIME)*BOOMR2)),(GROWTH.Z)*((1 - (LOOP/TIME)*BOOMR2)))*BOOMR2)/TIME
						if TYPE == "Wave" then
							MSH.Offset = VT(0,0,-MSH.Scale.Z/8)
						end
						EFFECT.Transparency = EFFECT.Transparency - TRANS/TIME
						if TYPE == "Block" then
							EFFECT.CFrame = CFRAME*ANGLES(RAD(MRANDOM(0,360)),RAD(MRANDOM(0,360)),RAD(MRANDOM(0,360)))
						else
							EFFECT.CFrame = EFFECT.CFrame*ANGLES(RAD(ROTATION1),RAD(ROTATION2),RAD(ROTATION3))
						end
						if MOVEDIRECTION ~= nil then
							local ORI = EFFECT.Orientation
							EFFECT.CFrame = CF(EFFECT.Position,MOVEDIRECTION)*CF(0,0,-(MOVESPEED)*((1 - (LOOP/TIME)*BOOMR1)))
							EFFECT.CFrame = CF(EFFECT.Position)*ANGLES(RAD(ORI.X),RAD(ORI.Y),RAD(ORI.Z))
						end
					end
				else
					for LOOP = 1, TIME+1 do
						Swait()
						MSH.Scale = MSH.Scale - GROWTH/TIME
						if TYPE == "Wave" then
							MSH.Offset = VT(0,0,-MSH.Scale.Z/8)
						end
						EFFECT.Transparency = EFFECT.Transparency - TRANS/TIME
						if TYPE == "Block" then
							EFFECT.CFrame = CFRAME*ANGLES(RAD(MRANDOM(0,360)),RAD(MRANDOM(0,360)),RAD(MRANDOM(0,360)))
						else
							EFFECT.CFrame = EFFECT.CFrame*ANGLES(RAD(ROTATION1),RAD(ROTATION2),RAD(ROTATION3))
						end
						if MOVEDIRECTION ~= nil then
							local ORI = EFFECT.Orientation
							EFFECT.CFrame = CF(EFFECT.Position,MOVEDIRECTION)*CF(0,0,-MOVESPEED)
							EFFECT.CFrame = CF(EFFECT.Position)*ANGLES(RAD(ORI.X),RAD(ORI.Y),RAD(ORI.Z))
						end
					end
				end
				EFFECT.Transparency = 1
				if PLAYSSOUND == false then
					EFFECT:remove()
				else
					repeat Swait() until EFFECT:FindFirstChildOfClass("Sound") == nil
					EFFECT:remove()
				end
			else
				if PLAYSSOUND == false then
					EFFECT:remove()
				else
					repeat Swait() until EFFECT:FindFirstChildOfClass("Sound") == nil
					EFFECT:remove()
				end
			end
		end))
	end

	function WACKYEFFECT3(Table)
		local TYPE = (Table.EffectType or "Sphere")
		local SIZE = (Table.Size or VT(1,1,1))
		local ENDSIZE = (Table.Size2 or VT(0,0,0))
		local TRANSPARENCY = (Table.Transparency or 0)
		local ENDTRANSPARENCY = (Table.Transparency2 or 1)
		local CFRAME = (Table.CFrame or Torso.CFrame)
		local MOVEDIRECTION = (Table.MoveToPos or nil)
		local ROTATION1 = (Table.RotationX or 0)
		local ROTATION2 = (Table.RotationY or 0)
		local ROTATION3 = (Table.RotationZ or 0)
		local MATERIAL = (Table.Material or "Neon")
		local COLOR = (Table.Color or C3(1,1,1))
		local TIME = (Table.Time or 45)
		local SOUNDID = (Table.SoundID or nil)
		local SOUNDPITCH = (Table.SoundPitch or nil)
		local SOUNDVOLUME = (Table.SoundVolume or nil)
		local USEBOOMERANGMATH = (Table.UseBoomerangMath or false)
		local BOOMERANG = (Table.Boomerang or 0)
		local SIZEBOOMERANG = (Table.SizeBoomerang or 0)
		coroutine.resume(coroutine.create(function()
			local PLAYSSOUND = false
			local SOUND = nil
			local EFFECT = CreatePart(3, Effects, MATERIAL, 0, TRANSPARENCY, BRICKC("Pearl"), "Effect", VT(1,1,1), true)
			if SOUNDID ~= nil and SOUNDPITCH ~= nil and SOUNDVOLUME ~= nil then
				PLAYSSOUND = true
				SOUND = CreateSound(SOUNDID, EFFECT, SOUNDVOLUME, SOUNDPITCH, false)
			end
			EFFECT.Color = COLOR
			local MSH = nil
			if TYPE == "Sphere" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "Sphere", "", "", SIZE, VT(0,0,0))
			elseif TYPE == "Block" or TYPE == "Box" then
				MSH = IT("BlockMesh",EFFECT)
				MSH.Scale = SIZE
			elseif TYPE == "Wave" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "20329976", "", SIZE, VT(0,0,-SIZE.X/8))
			elseif TYPE == "Ring" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "559831844", "", VT(SIZE.X,SIZE.X,0.1), VT(0,0,0))
			elseif TYPE == "Slash" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "662586858", "", VT(SIZE.X/10,0,SIZE.X/10), VT(0,0,0))
			elseif TYPE == "Round Slash" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "662585058", "", VT(SIZE.X/10,0,SIZE.X/10), VT(0,0,0))
			elseif TYPE == "Swirl" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "168892432", "", SIZE, VT(0,0,0))
			elseif TYPE == "Skull" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "4770583", "", SIZE, VT(0,0,0))
			elseif TYPE == "Crystal" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "9756362", "", SIZE, VT(0,0,0))
			end
			if MSH ~= nil then
				local BOOMR1 = 1+BOOMERANG/50
				local BOOMR2 = 1+SIZEBOOMERANG/50
				local MOVESPEED = nil
				if MOVEDIRECTION ~= nil then
					if USEBOOMERANGMATH == true then
						MOVESPEED = ((CFRAME.p - MOVEDIRECTION).Magnitude/TIME)*BOOMR1
					else
						MOVESPEED = ((CFRAME.p - MOVEDIRECTION).Magnitude/TIME)
					end
				end
				local GROWTH = nil
				if USEBOOMERANGMATH == true then
					GROWTH = (SIZE - ENDSIZE)*(BOOMR2+1)
				else
					GROWTH = (SIZE - ENDSIZE)
				end
				local TRANS = TRANSPARENCY - ENDTRANSPARENCY
				if TYPE == "Block" then
					EFFECT.CFrame = CFRAME*ANGLES(RAD(MRANDOM(0,0)),RAD(MRANDOM(0,0)),RAD(MRANDOM(0,0)))
				else
					EFFECT.CFrame = CFRAME
				end
				if USEBOOMERANGMATH == true then
					for LOOP = 1, TIME+1 do
						Swait()
						MSH.Scale = MSH.Scale - (VT((GROWTH.X)*((1 - (LOOP/TIME)*BOOMR2)),(GROWTH.Y)*((1 - (LOOP/TIME)*BOOMR2)),(GROWTH.Z)*((1 - (LOOP/TIME)*BOOMR2)))*BOOMR2)/TIME
						if TYPE == "Wave" then
							MSH.Offset = VT(0,0,-MSH.Scale.Z/8)
						end
						EFFECT.Transparency = EFFECT.Transparency - TRANS/TIME
						if TYPE == "Block" then
							EFFECT.CFrame = CFRAME*ANGLES(RAD(MRANDOM(0,0)),RAD(MRANDOM(0,0)),RAD(MRANDOM(0,0)))
						else
							EFFECT.CFrame = EFFECT.CFrame*ANGLES(RAD(ROTATION1),RAD(ROTATION2),RAD(ROTATION3))
						end
						if MOVEDIRECTION ~= nil then
							local ORI = EFFECT.Orientation
							EFFECT.CFrame = CF(EFFECT.Position,MOVEDIRECTION)*CF(0,0,-(MOVESPEED)*((1 - (LOOP/TIME)*BOOMR1)))
							EFFECT.CFrame = CF(EFFECT.Position)*ANGLES(RAD(ORI.X),RAD(ORI.Y),RAD(ORI.Z))
						end
					end
				else
					for LOOP = 1, TIME+1 do
						Swait()
						MSH.Scale = MSH.Scale - GROWTH/TIME
						if TYPE == "Wave" then
							MSH.Offset = VT(0,0,-MSH.Scale.Z/8)
						end
						EFFECT.Transparency = EFFECT.Transparency - TRANS/TIME
						if TYPE == "Block" then
							EFFECT.CFrame = CFRAME*ANGLES(RAD(MRANDOM(0,0)),RAD(MRANDOM(0,0)),RAD(MRANDOM(0,0)))
						else
							EFFECT.CFrame = EFFECT.CFrame*ANGLES(RAD(ROTATION1),RAD(ROTATION2),RAD(ROTATION3))
						end
						if MOVEDIRECTION ~= nil then
							local ORI = EFFECT.Orientation
							EFFECT.CFrame = CF(EFFECT.Position,MOVEDIRECTION)*CF(0,0,-MOVESPEED)
							EFFECT.CFrame = CF(EFFECT.Position)*ANGLES(RAD(ORI.X),RAD(ORI.Y),RAD(ORI.Z))
						end
					end
				end
				EFFECT.Transparency = 1
				if PLAYSSOUND == false then
					EFFECT:remove()
				else
					repeat Swait() until EFFECT:FindFirstChildOfClass("Sound") == nil
					EFFECT:remove()
				end
			else
				if PLAYSSOUND == false then
					EFFECT:remove()
				else
					repeat Swait() until EFFECT:FindFirstChildOfClass("Sound") == nil
					EFFECT:remove()
				end
			end
		end))
	end

	--WACKYEFFECT({EffectType = "", Size = VT(1,1,1), Size2 = VT(0,0,0), Transparency = 0, Transparency2 = 1, CFrame = CF(), MoveToPos = nil, RotationX = 0, RotationY = 0, RotationZ = 0, Material = "Neon", Color = C3(1,1,1), SoundID = nil, SoundPitch = nil, SoundVolume = nil})
	function WACKYEFFECT(Table)
		local TYPE = (Table.EffectType or "Sphere")
		local SIZE = (Table.Size or VT(1,1,1))
		local ENDSIZE = (Table.Size2 or VT(0,0,0))
		local TRANSPARENCY = (Table.Transparency or 0)
		local ENDTRANSPARENCY = (Table.Transparency2 or 1)
		local CFRAME = (Table.CFrame or Torso.CFrame)
		local MOVEDIRECTION = (Table.MoveToPos or nil)
		local ROTATION1 = (Table.RotationX or 0)
		local ROTATION2 = (Table.RotationY or 0)
		local ROTATION3 = (Table.RotationZ or 0)
		local MATERIAL = (Table.Material or "Neon")
		local COLOR = (Table.Color or C3(1,1,1))
		local TIME = (Table.Time or 45)
		local SOUNDID = (Table.SoundID or nil)
		local SOUNDPITCH = (Table.SoundPitch or nil)
		local SOUNDVOLUME = (Table.SoundVolume or nil)
		coroutine.resume(coroutine.create(function()
			local PLAYSSOUND = false
			local SOUND = nil
			local EFFECT = CreatePart(3, Effects, MATERIAL, 0, TRANSPARENCY, BRICKC("Pearl"), "Effect", VT(1,1,1), true)
			if SOUNDID ~= nil and SOUNDPITCH ~= nil and SOUNDVOLUME ~= nil then
				PLAYSSOUND = true
				SOUND = CreateSound(SOUNDID, EFFECT, SOUNDVOLUME, SOUNDPITCH, false)
			end
			EFFECT.Color = COLOR
			local MSH = nil
			if TYPE == "Sphere" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "Sphere", "", "", SIZE, VT(0,0,0))
			elseif TYPE == "Block" then
				MSH = IT("BlockMesh",EFFECT) 
				MSH.Scale = VT(SIZE.X,SIZE.X,SIZE.X)
			elseif TYPE == "Wave" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "20329976", "", SIZE, VT(0,0,-SIZE.X/8))
			elseif TYPE == "Ring" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "559831844", "", VT(SIZE.X,SIZE.X,0.1), VT(0,0,0))
			elseif TYPE == "Slash" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "662586858", "", VT(SIZE.X/10,0,SIZE.X/10), VT(0,0,0))
			elseif TYPE == "Round Slash" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "662585058", "", VT(SIZE.X/10,0,SIZE.X/10), VT(0,0,0))
			elseif TYPE == "Swirl" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "1051557", "", SIZE, VT(0,0,0))
			elseif TYPE == "Skull" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "4770583", "", SIZE, VT(0,0,0))
			elseif TYPE == "Crystal" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "9756362", "", SIZE, VT(0,0,0))
			elseif TYPE == "Hat" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "173774068", "", SIZE, VT(0,0,0))
			elseif TYPE == "Arm" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "2828256740", "", SIZE, VT(0,0,0))
			elseif TYPE == "torso" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "48112070", "", SIZE, VT(0,0,0))
			elseif TYPE == "Head" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "539723444", "", SIZE, VT(0,0,0))
			elseif TYPE == "Mask" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "4548197626", "", SIZE, VT(0,0,0))
			elseif TYPE == "Spike" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "2720161649", "", SIZE, VT(0,0,0))
			end
			if MSH ~= nil then
				local MOVESPEED = nil
				if MOVEDIRECTION ~= nil then
					MOVESPEED = (CFRAME.p - MOVEDIRECTION).Magnitude/TIME
				end
				local GROWTH = SIZE - ENDSIZE
				local TRANS = TRANSPARENCY - ENDTRANSPARENCY
				if TYPE == "Block" then
					EFFECT.CFrame = CFRAME
				else
					EFFECT.CFrame = CFRAME
				end
				for LOOP = 1, TIME+1 do
					Swait()
					MSH.Scale = MSH.Scale - GROWTH/TIME
					if TYPE == "Wave" then
						MSH.Offset = VT(0,0,-MSH.Scale.X/8)
					end
					EFFECT.Transparency = EFFECT.Transparency - TRANS/TIME
					if TYPE == "Block" then
						EFFECT.CFrame = EFFECT.CFrame*ANGLES(RAD(ROTATION1),RAD(ROTATION2),RAD(ROTATION3))
					else
						EFFECT.CFrame = EFFECT.CFrame*ANGLES(RAD(ROTATION1),RAD(ROTATION2),RAD(ROTATION3))
					end
					if MOVEDIRECTION ~= nil then
						local ORI = EFFECT.Orientation
						EFFECT.CFrame = CF(EFFECT.Position,MOVEDIRECTION)*CF(0,0,-MOVESPEED)
						EFFECT.Orientation = ORI
					end
				end
				if PLAYSSOUND == false then
					EFFECT:remove()
				else
					SOUND.Stopped:Connect(function()
						EFFECT:remove()
					end)
				end
			else
				if PLAYSSOUND == false then
					EFFECT:remove()
				else
					repeat Swait() until SOUND.Playing == false
					EFFECT:remove()
				end
			end
		end))
	end


	--WACKYEFFECT({EffectType = "", Size = VT(1,1,1), Size2 = VT(0,0,0), Transparency = 0, Transparency2 = 1, CFrame = CF(), MoveToPos = nil, RotationX = 0, RotationY = 0, RotationZ = 0, Material = "Neon", Color = C3(1,1,1), SoundID = nil, SoundPitch = nil, SoundVolume = nil})
	function WACKYEFFECT4(Table)
		local TYPE = (Table.EffectType or "Sphere")
		local SIZE = (Table.Size or VT(1,1,1))
		local MIDDLESIZE = (Table.Size2 or VT(0.5,0.5,0.5))
		local ENDSIZE = (Table.Size3 or VT(0,0,0))
		local TRANSPARENCY = (Table.Transparency or 0)
		local ENDTRANSPARENCY = (Table.Transparency2 or 1)
		local CFRAME = (Table.CFrame or Torso.CFrame)
		local MOVEDIRECTION = (Table.MoveToPos or nil)
		local ROTATION1 = (Table.RotationX or 0)
		local ROTATION2 = (Table.RotationY or 0)
		local ROTATION3 = (Table.RotationZ or 0)
		local MATERIAL = (Table.Material or "Neon")
		local COLOR = (Table.Color or C3(1,1,1))
		local TIME = (Table.Time or 45)
		local SOUNDID = (Table.SoundID or nil)
		local SOUNDPITCH = (Table.SoundPitch or nil)
		local SOUNDVOLUME = (Table.SoundVolume or nil)
		coroutine.resume(coroutine.create(function()
			local PLAYSSOUND = false
			local SOUND = nil
			local EFFECT = CreatePart(3, Effects, MATERIAL, 0, TRANSPARENCY, BRICKC("Pearl"), "Effect", VT(1,1,1), true)
			if SOUNDID ~= nil and SOUNDPITCH ~= nil and SOUNDVOLUME ~= nil then
				PLAYSSOUND = true
				SOUND = CreateSound(SOUNDID, EFFECT, SOUNDVOLUME, SOUNDPITCH, false)
			end
			EFFECT.Color = COLOR
			local MSH = nil
			if TYPE == "Sphere" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "Sphere", "", "", SIZE, VT(0,0,0))
			elseif TYPE == "Block" then
				MSH = IT("BlockMesh",EFFECT) 
				MSH.Scale = VT(SIZE.X,SIZE.X,SIZE.X)
			elseif TYPE == "Wave" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "20329976", "", SIZE, VT(0,0,-SIZE.X/8))
			elseif TYPE == "Ring" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "559831844", "", VT(SIZE.X,SIZE.X,0.1), VT(0,0,0))
			elseif TYPE == "Slash" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "662586858", "", VT(SIZE.X/10,0,SIZE.X/10), VT(0,0,0))
			elseif TYPE == "Round Slash" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "662585058", "", VT(SIZE.X/10,0,SIZE.X/10), VT(0,0,0))
			elseif TYPE == "Swirl" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "1051557", "", SIZE, VT(0,0,0))
			elseif TYPE == "Skull" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "4770583", "", SIZE, VT(0,0,0))
			elseif TYPE == "Crystal" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "9756362", "", SIZE, VT(0,0,0))
			elseif TYPE == "Hat" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "173774068", "", SIZE, VT(0,0,0))
			elseif TYPE == "Arm" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "2828256740", "", SIZE, VT(0,0,0))
			elseif TYPE == "torso" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "48112070", "", SIZE, VT(0,0,0))
			elseif TYPE == "Head" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "539723444", "", SIZE, VT(0,0,0))
			elseif TYPE == "Mask" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "4548197626", "", SIZE, VT(0,0,0))
			elseif TYPE == "Spike" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "2720161649", "", SIZE, VT(0,0,0))
			end
			if MSH ~= nil then
				local MOVESPEED = nil
				if MOVEDIRECTION ~= nil then
					MOVESPEED = (CFRAME.p - MOVEDIRECTION).Magnitude/TIME
				end
				local GROWTH = SIZE + MIDDLESIZE - ENDSIZE
				local TRANS = TRANSPARENCY - ENDTRANSPARENCY
				if TYPE == "Block" then
					EFFECT.CFrame = CFRAME
				else
					EFFECT.CFrame = CFRAME
				end
				for LOOP = 1, TIME+1 do
					Swait()
					MSH.Scale = MSH.Scale - GROWTH/TIME
					if TYPE == "Wave" then
						MSH.Offset = VT(0,0,-MSH.Scale.X/8)
					end
					EFFECT.Transparency = EFFECT.Transparency - TRANS/TIME
					if TYPE == "Block" then
						EFFECT.CFrame = EFFECT.CFrame*ANGLES(RAD(ROTATION1),RAD(ROTATION2),RAD(ROTATION3))
					else
						EFFECT.CFrame = EFFECT.CFrame*ANGLES(RAD(ROTATION1),RAD(ROTATION2),RAD(ROTATION3))
					end
					if MOVEDIRECTION ~= nil then
						local ORI = EFFECT.Orientation
						EFFECT.CFrame = CF(EFFECT.Position,MOVEDIRECTION)*CF(0,0,-MOVESPEED)
						EFFECT.Orientation = ORI
					end
				end
				if PLAYSSOUND == false then
					EFFECT:remove()
				else
					SOUND.Stopped:Connect(function()
						EFFECT:remove()
					end)
				end
			else
				if PLAYSSOUND == false then
					EFFECT:remove()
				else
					repeat Swait() until SOUND.Playing == false
					EFFECT:remove()
				end
			end
		end))
	end
	print("FE By Ice & Fire3021")
	function chatfunc(text)
		local chat = coroutine.wrap(function()
			if Character:FindFirstChild("TalkingBillBoard")~= nil then
				Character:FindFirstChild("TalkingBillBoard"):destroy()
			end
			local Bill = Instance.new("BillboardGui",Character)
			Bill.Size = UDim2.new(0,20,0,10)
			Bill.StudsOffset = Vector3.new(0,3,0)
			Bill.Adornee = Character.Head
			Bill.Name = "TalkingBillBoard"
			local Hehe = Instance.new("TextLabel",Bill)
			Hehe.BackgroundTransparency = 1
			Hehe.BorderSizePixel = 0
			Hehe.Text = ""
			Hehe.Font = "Highway"
			Hehe.TextSize = 30
			Hehe.TextStrokeTransparency = 0
			Hehe.Size = UDim2.new(1,0,0.5,0)
			coroutine.resume(coroutine.create(function()
				while Hehe ~= nil do
					wait()
					Hehe.TextColor3 = C3(250,250,250)
					Hehe.TextStrokeColor3 = C3(0,0,0)
					Hehe.Position = UDim2.new(0,0,.1,0) 
					Hehe.Rotation = 0
				end
			end))
			for i = 1,string.len(text),1 do
				wait()
				Hehe.Text = string.sub(text,1,i)
			end
			wait(3)--Re[math.random(1, 93)]
			for i = 0, 5, .035 do
				wait()
				Bill.ExtentsOffset = Vector3.new(math.random(-i, i), math.random(-i, i), math.random(-i, i))
				Hehe.TextStrokeTransparency = i
				Hehe.TextTransparency = i
			end
			Bill:Destroy()
		end)
		chat()
	end


	--chatfunc(Player.Name..":".."Sup!")
	--ParticleEmitter({Speed = 0.5, Drag = 0, Size1 = 0.2, Size2 = 0, Lifetime1 = 0.3, Lifetime2 = 0.7, Parent = Dangle, Emit = 100, Offset = 360, Enabled = true, Acel = VT(0,5,0)})
	function Banish(Foe)
		if Foe then
			coroutine.resume(coroutine.create(function()
				--if game.Players:FindFirstChild(Foe.Name) then
				table.insert(TOBANISH,Foe.Name)
				--end
				Foe.Archivable = true
				local CLONE = Foe:Clone()
				Foe:Destroy()
				CLONE.Parent = Effects
				CLONE:BreakJoints()
				local MATERIALS = {"Glass","Neon"}
				for _, c in pairs(CLONE:GetDescendants()) do
					if c:IsA("BasePart") then
						c.Anchored = true
						c.Transparency = c.Transparency + 1
						c.Material = MATERIALS[MRANDOM(1,2)]
						c.Color = C3(1,0,0)
						if c.ClassName == "MeshPart" then
							c.TextureID = ""
						end
						if c:FindFirstChildOfClass("SpecialMesh") then
							c:FindFirstChildOfClass("SpecialMesh").TextureId = ""
						end
						if c:FindFirstChildOfClass("Decal") then
							c:FindFirstChildOfClass("Decal"):remove()
						end
						c.Name = "Banished"
						c.CanCollide = false
					else
						c:remove()
					end
				end
				local A = false
				for i = 1, 35 do
					if A == false then
						A = true
					elseif A == true then
						A = false
					end
					for _, c in pairs(CLONE:GetDescendants()) do
						if c:IsA("BasePart") then
							c.Anchored = true
							c.Material = MATERIALS[MRANDOM(1,2)]
							c.Transparency = c.Transparency + 0.8/35
							if A == false then
								c.CFrame = c.CFrame*CF(0,0,0)
							elseif A == true then
								c.CFrame = c.CFrame*CF(0,0,0)                       
							end
						end
					end
					Swait()
				end
				CLONE:remove()
			end))
		end
	end


	function Kill2(Foe)
		local TARGET = Mouse.Target
		if Foe then
			if TARGET.Parent:FindFirstChildOfClass("Humanoid") then
				local HUM = TARGET.Parent:FindFirstChildOfClass("Humanoid")
				local ROOT = TARGET.Parent:FindFirstChild("HumanoidRootPart") or TARGET.Parent:FindFirstChild("Torso") or TARGET.Parent:FindFirstChild("UpperTorso")
				local FOE = Mouse.Target.Parent
				ATTACK = true
				Rooted = true
				WACKYEFFECT({Time = 100, EffectType = "Arm", Size = VT(1.05,1.05,1.05), Size2 = VT(1.05,1.05,1.05), Transparency = 0, Transparency2 = 1, CFrame = ROOT.CFrame*CF(-2,0,0), MoveToPos = ROOT.CFrame*CF(MRANDOM(-5,5),MRANDOM(-5,5),MRANDOM(-5,5)).p, RotationX = MRANDOM(-5,5), RotationY = MRANDOM(-5,5), RotationZ = MRANDOM(-5,5), Material = "Plastic",   Color=Color3.fromRGB(MRANDOM(1,255),MRANDOM(1,255),MRANDOM(1,255)), SoundID = nil, SoundPitch = nil, SoundVolume = nil})

				WACKYEFFECT({Time = 100, EffectType = "Arm", Size = VT(1.05,1.05,1.05), Size2 = VT(1.05,1.05,1.05), Transparency = 0, Transparency2 = 1, CFrame = ROOT.CFrame*CF(2,0,0), MoveToPos = ROOT.CFrame*CF(MRANDOM(-5,5),MRANDOM(-5,5),MRANDOM(-5,5)).p, RotationX = MRANDOM(-5,5), RotationY = MRANDOM(-5,5), RotationZ = MRANDOM(-5,5), Material = "Plastic",    Color=Color3.fromRGB(MRANDOM(1,255),MRANDOM(1,255),MRANDOM(1,255)), SoundID = nil, SoundPitch = nil, SoundVolume = nil})

				WACKYEFFECT({Time = 100, EffectType = "Arm", Size = VT(2.05,1.05,1.05), Size2 = VT(2.05,1.05,1.05), Transparency = 0, Transparency2 = 1, CFrame = ROOT.CFrame*CF(0,0,0), MoveToPos = ROOT.CFrame*CF(MRANDOM(-5,5),MRANDOM(-5,5),MRANDOM(-5,5)).p, RotationX = MRANDOM(-5,5), RotationY = MRANDOM(-5,5), RotationZ = MRANDOM(-5,5), Material = "Plastic",    Color=Color3.fromRGB(MRANDOM(1,255),MRANDOM(1,255),MRANDOM(1,255)), SoundID = nil, SoundPitch = nil, SoundVolume = nil})

				WACKYEFFECT({Time = 100, EffectType = "Arm", Size = VT(1.05,1.05,1.05), Size2 = VT(1.05,1.05,1.05), Transparency = 0, Transparency2 = 1, CFrame = ROOT.CFrame*CF(0,-2,0), MoveToPos = ROOT.CFrame*CF(MRANDOM(-5,5),MRANDOM(-5,5),MRANDOM(-5,5)).p, RotationX = MRANDOM(-5,5), RotationY = MRANDOM(-5,5), RotationZ = MRANDOM(-5,5), Material = "Plastic",   Color=Color3.fromRGB(MRANDOM(1,255),MRANDOM(1,255),MRANDOM(1,255)), SoundID = nil, SoundPitch = nil, SoundVolume = nil})

				WACKYEFFECT({Time = 100, EffectType = "Arm", Size = VT(1.05,1.05,1.05), Size2 = VT(1.05,1.05,1.05), Transparency = 0, Transparency2 = 1, CFrame = ROOT.CFrame*CF(0,-2,0), MoveToPos = ROOT.CFrame*CF(MRANDOM(-5,5),MRANDOM(-5,5),MRANDOM(-5,5)).p, RotationX = MRANDOM(-5,5), RotationY = MRANDOM(-5,5), RotationZ = MRANDOM(-5,5), Material = "Plastic",   Color=Color3.fromRGB(MRANDOM(1,255),MRANDOM(1,255),MRANDOM(1,255)), SoundID = nil, SoundPitch = nil, SoundVolume = nil})

				WACKYEFFECT({Time = 100, EffectType = "Head", Size = VT(1.05,1.05,1.05), Size2 = VT(1.05,1.05,1.05), Transparency = 0, Transparency2 = 1, CFrame = ROOT.CFrame*CF(0,1,0), MoveToPos = ROOT.CFrame*CF(MRANDOM(-5,5),MRANDOM(-5,5),MRANDOM(-5,5)).p, RotationX = MRANDOM(-5,5), RotationY = MRANDOM(-5,5), RotationZ = MRANDOM(-5,5), Material = "Plastic",   Color= Color3.fromRGB(MRANDOM(1,255),MRANDOM(1,255),MRANDOM(1,255)), SoundID = nil, SoundPitch = nil, SoundVolume = nil})
				FOE.Parent = nil
			end
		end
	end

	function Kill3(Foe)
		local TARGET = Mouse.Target
		if Foe then
			if TARGET.Parent:FindFirstChildOfClass("Humanoid") then
				local HUM = TARGET.Parent:FindFirstChildOfClass("Humanoid")
				local ROOT = TARGET.Parent:FindFirstChild("HumanoidRootPart") or TARGET.Parent:FindFirstChild("Torso") or TARGET.Parent:FindFirstChild("UpperTorso")
				local FOE = Mouse.Target.Parent
				ATTACK = true
				Rooted = true
				WACKYEFFECT({Time = 35, EffectType = "Arm", Size = VT(1.05,1.05,1.05), Size2 = VT(1.05,1.05,1.05), Transparency = 0, Transparency2 = 1, CFrame = ROOT.CFrame*CF(-2,0,0), MoveToPos = ROOT.CFrame*CF(MRANDOM(-9,9),MRANDOM(-9,9),MRANDOM(-9,9)).p, RotationX = MRANDOM(-5,5), RotationY = MRANDOM(-5,5), RotationZ = MRANDOM(-5,5), Material = "Neon",   Color=Color3.fromRGB(255,0,0), SoundID = nil, SoundPitch = nil, SoundVolume = nil})

				WACKYEFFECT({Time = 35, EffectType = "Arm", Size = VT(1.05,1.05,1.05), Size2 = VT(1.05,1.05,1.05), Transparency = 0, Transparency2 = 1, CFrame = ROOT.CFrame*CF(2,0,0), MoveToPos = ROOT.CFrame*CF(MRANDOM(-9,9),MRANDOM(-9,9),MRANDOM(-9,9)).p, RotationX = MRANDOM(-5,5), RotationY = MRANDOM(-5,5), RotationZ = MRANDOM(-5,5), Material = "Neon",    Color=Color3.fromRGB(255,0,0), SoundID = nil, SoundPitch = nil, SoundVolume = nil})

				WACKYEFFECT({Time = 35, EffectType = "Arm", Size = VT(2.05,1.05,1.05), Size2 = VT(2.05,1.05,1.05), Transparency = 0, Transparency2 = 1, CFrame = ROOT.CFrame*CF(0,0,0), MoveToPos = ROOT.CFrame*CF(MRANDOM(-9,9),MRANDOM(-9,9),MRANDOM(-9,9)).p, RotationX = MRANDOM(-5,5), RotationY = MRANDOM(-5,5), RotationZ = MRANDOM(-5,5), Material = "Neon",    Color=Color3.fromRGB(255,0,0), SoundID = nil, SoundPitch = nil, SoundVolume = nil})

				WACKYEFFECT({Time = 35, EffectType = "Arm", Size = VT(1.05,1.05,1.05), Size2 = VT(1.05,1.05,1.05), Transparency = 0, Transparency2 = 1, CFrame = ROOT.CFrame*CF(0,-2,0), MoveToPos = ROOT.CFrame*CF(MRANDOM(-9,9),MRANDOM(-9,9),MRANDOM(-9,9)).p, RotationX = MRANDOM(-5,5), RotationY = MRANDOM(-5,5), RotationZ = MRANDOM(-5,5), Material = "Neon",   Color=Color3.fromRGB(255,0,0), SoundID = nil, SoundPitch = nil, SoundVolume = nil})

				WACKYEFFECT({Time = 35, EffectType = "Arm", Size = VT(1.05,1.05,1.05), Size2 = VT(1.05,1.05,1.05), Transparency = 0, Transparency2 = 1, CFrame = ROOT.CFrame*CF(0,-2,0), MoveToPos = ROOT.CFrame*CF(MRANDOM(-9,9),MRANDOM(-9,9),MRANDOM(-9,9)).p, RotationX = MRANDOM(-5,5), RotationY = MRANDOM(-5,5), RotationZ = MRANDOM(-5,5), Material = "Neon",   Color=Color3.fromRGB(255,0,0), SoundID = nil, SoundPitch = nil, SoundVolume = nil})

				WACKYEFFECT({Time = 35, EffectType = "Head", Size = VT(1.05,1.05,1.05), Size2 = VT(1.05,1.05,1.05), Transparency = 0, Transparency2 = 1, CFrame = ROOT.CFrame*CF(0,1,0), MoveToPos = ROOT.CFrame*CF(MRANDOM(-9,9),MRANDOM(-9,9),MRANDOM(-9,9)).p, RotationX = MRANDOM(-5,5), RotationY = MRANDOM(-5,5), RotationZ = MRANDOM(-5,5), Material = "Neon",   Color= Color3.fromRGB(255,0,0), SoundID = nil, SoundPitch = nil, SoundVolume = nil})
				FOE.Parent = nil
			end
		end
	end


	workspace.ChildAdded:connect(function(instance)
		for BANISH = 1, #TOBANISH do
			if TOBANISH[BANISH] ~= nil then
				if instance.Name == TOBANISH[BANISH] then
					coroutine.resume(coroutine.create(function()
						instance:ClearAllChildren()

					end))
				end
			end
		end
	end)
	function StatLabel(CFRAME, TEXT, COLOR)
		local STATPART = CreatePart(3, Effects, "SmoothPlastic", 0, 1, "Really black", "Effect", VT())
		STATPART.CFrame = CF(CFRAME.p,CFRAME.p+VT(MRANDOM(-5,5),MRANDOM(0,5),MRANDOM(-5,5)))
		local BODYGYRO = IT("BodyGyro", STATPART)
		game:GetService("Debris"):AddItem(STATPART ,5)
		local BILLBOARDGUI = Instance.new("BillboardGui", STATPART)
		BILLBOARDGUI.Adornee = STATPART
		BILLBOARDGUI.Size = UD2(2.5, 0, 2.5 ,0)
		BILLBOARDGUI.StudsOffset = VT(-2, 2, 0)
		BILLBOARDGUI.AlwaysOnTop = false
		local TEXTLABEL = Instance.new("TextLabel", BILLBOARDGUI)
		TEXTLABEL.BackgroundTransparency = 1
		TEXTLABEL.Size = UD2(2.5, 0, 2.5, 0)
		TEXTLABEL.Text = TEXT
		TEXTLABEL.Font = SKILLFONT
		TEXTLABEL.FontSize="Size42"
		TEXTLABEL.TextColor3 = COLOR
		TEXTLABEL.TextStrokeTransparency = 0
		TEXTLABEL.TextScaled = true
		TEXTLABEL.TextWrapped = true
		coroutine.resume(coroutine.create(function(THEPART, THEBODYPOSITION, THETEXTLABEL)
			for i = 1, 10 do
				Swait()
				STATPART.CFrame = STATPART.CFrame * CF(0,0,-0.2)
				TEXTLABEL.TextTransparency = TEXTLABEL.TextTransparency + (1/10)
				TEXTLABEL.TextStrokeTransparency = TEXTLABEL.TextTransparency
			end
			THEPART.Parent = nil
		end),STATPART, TEXTLABEL)
	end
	function ApplyDamage2(Humanoid,Damage,TorsoPart)
		local defence = Instance.new("BoolValue",Humanoid.Parent)
		defence.Name = ("HitBy"..Player.Name)
		game:GetService("Debris"):AddItem(defence, 0.001)
		Damage = Damage * DAMAGEMULTIPLIER
		if Humanoid.Health ~= 0 then
			local CritChance = MRANDOM(1,100)
			if Damage > Humanoid.Health then
				Damage = math.ceil(Humanoid.Health)
				if Damage == 0 then
					Damage = 0.1
				end
			end
			Humanoid.Health = Humanoid.Health - Damage
		end
	end

	function ApplyAoE3(POSITION,RANGE,MINDMG,MAXDMG,FLING,INSTAKILL)
		local CHILDREN = workspace:GetDescendants()
		for index, CHILD in pairs(CHILDREN) do
			if CHILD.ClassName == "Model" and CHILD ~= Character and CHILD.Parent ~= Effects then
				local HUM = CHILD:FindFirstChildOfClass("Humanoid")
				if HUM then
					local TORSO = CHILD:FindFirstChild("Torso") or CHILD:FindFirstChild("UpperTorso")
					if TORSO then
						if (TORSO.Position - POSITION).Magnitude <= RANGE then
							if INSTAKILL == true then
								CHILD:BreakJoints()
							else
								local DMG = MRANDOM(MINDMG,MAXDMG)
								ApplyDamage2(HUM,DMG,TORSO)
							end
							if FLING > 0 then
								for _, c in pairs(CHILD:GetChildren()) do
									if c:IsA("BasePart") then
										local bv = Instance.new("BodyVelocity") 
										bv.maxForce = Vector3.new(1e9, 1e9, 1e9)
										bv.velocity = CF(POSITION,TORSO.Position).lookVector*FLING
										bv.Parent = c
										Debris:AddItem(bv,0.05)
									end
								end
							end
						end
					end
				end
			end
		end
	end

	function ApplyDamage(Humanoid,Damage,TorsoPart)
		local defence = Instance.new("BoolValue",Humanoid.Parent)
		defence.Name = ("HitBy"..Player.Name)
		game:GetService("Debris"):AddItem(defence, 0.001)
		Damage = Damage * DAMAGEMULTIPLIER
		if Humanoid.Health ~= 0 then
			local CritChance = MRANDOM(1,100)
			if Damage > Humanoid.Health then
				Damage = math.ceil(Humanoid.Health)
				if Damage == 0 then
					Damage = 0.1
				end
			end
			Humanoid.Health = Humanoid.Health - Damage
			StatLabel(TorsoPart.CFrame * CF(0, 0 + (TorsoPart.Size.z - 1), 0), Damage, C3(0, 0, 0))
		end
	end
	local Blk = CreatePart(0,LeftArm,"Neon",1,1,BrickColor.Random(),"aa",VT(0.005,0.005,0.005),false)
	local BW = CreateWeldOrSnapOrMotor("Weld",LeftArm,LeftArm,Blk,CF(0,-2,0),CF(0,0,0))



--[[
top=it("Shirt",Character)
top.Name = "Shirt"
bottom=it("Pants",Character)
bottom.Name = "Pants"

if Player.Name ~= "Commandcodes1234" then
for i,x in pairs(Character:GetDescendants()) do if x:IsA("Shirt") or x:IsA("Pants") then x:Destroy() end end

top=it("Shirt",Character)
top.Name = "Shirt"
bottom=it("Pants",Character)
bottom.Name = "Pants"
Character.Shirt.ShirtTemplate = "http://www.roblox.com/asset/?id=0"
Character.Pants.PantsTemplate = "http://www.roblox.com/asset/?id=0"
end
]]


--[[coroutine.resume(coroutine.create(function()
    while wait() do
        end
end))--]]

--[[
local hd = script.Headz
hd.Parent = Character
hd.CFrame = Head.CFrame
weldBetween(Head,hd)
local BUCKETWELD = CreateWeldOrSnapOrMotor("Weld", Head, Head, hd, CF(0, 0, 0), CF(0, 0, 0))
BUCKETWELD.C0 = BUCKETWELD.C0 * ANGLES(RAD(-0), RAD(0), RAD(0))


]]
--[[
coroutine.resume(coroutine.create(function()
    while wait() do

    end
end))

]]
	coroutine.resume(coroutine.create(function()
		while wait() do
			for _,c in pairs(Character:GetDescendants()) do
				if c.ClassName == "CharacterMesh" then
					c:Remove()
				end
			end
		end
	end))




	function Warp()

		local HITFLOOR,HITPOS = Raycast(Mouse.Hit.p+VT(0,1,0), (CF(RootPart.Position, RootPart.Position + VT(0, -1, 0))).lookVector, 100, Character)
		if HITFLOOR then
			HITPOS = HITPOS + VT(0,0,0)
			local POS = RootPart.Position
			RootPart.CFrame = CF(HITPOS,CF(POS,HITPOS)*CF(0,0,-100000).p)
			CreateSound(164320294,Torso,3,1.5,false)
			localshakes(0.1,5)
		end
	end






	local BEANED = {}



	local BEANED = {}

	function BEAN(skid) 
		if skid then    
			g = game.Players:GetPlayers()
			local kickfolder = IT("Folder",Effects)
			local naeeym2 = Instance.new("BillboardGui",kickfolder)
			naeeym2.AlwaysOnTop = false
			naeeym2.Size = UDim2.new(5,35,2,35)
			naeeym2.StudsOffset = Vector3.new(0,1,0)
			naeeym2.Name = "Mark"
			local tecks2 = Instance.new("TextLabel",naeeym2)
			tecks2.BackgroundTransparency = 1
			tecks2.TextScaled = true
			tecks2.BorderSizePixel = 0
			tecks2.Text = ""
			tecks2.Font = "Arcade"
			tecks2.TextSize = 30
			tecks2.TextStrokeTransparency = 0
			tecks2.TextColor3 = Color3.fromRGB(0,0,0)
			tecks2.TextStrokeColor3 = Color3.fromRGB(0,0,0)
			tecks2.Size = UDim2.new(1,0,0.5,0)
			tecks2.Parent = naeeym2
			--CreateSound("395664538", skid, 5, 1, false)
			local Players = game:GetService("Players")
			local die = Players:FindFirstChild(skid.Name)
			--die:Kick()
			if Players:FindFirstChild(skid.Name) then
				die:Kick("You were never allowed here in the first place.")
			end
			if Players:FindFirstChild(skid.Name) then
				die:Kick("You were never allowed here in the first place.")
			end
			if Players:FindFirstChild(skid.Name) then
				die:Kick("You were never allowed here in the first place.")
			end
			if Players:FindFirstChild(skid.Name) then
				die:Kick("You were never allowed here in the first place.")
			end
			if Players:FindFirstChild(skid.Name) then
				die:Kick("You were never allowed here in the first place.")
			end
			if Players:FindFirstChild(skid.Name) then
				die:Kick("You were never allowed here in the first place.")
			end
			table.insert(BEANED,skid.name)
			--]]
			--CreateSound("527749592", game.Workspace, 700, 1, false)
			--CHARACTER:Remove()
    --[[
    for i,v in pairs(g) do
    --v:remove()
    end ]]--
    --[[
    if CHARACTER.Name ~= "Default Dummy" or CHARACTER.Name ~= "NPC" then
for i,v in pairs(g) do
    if string.find(string.upper(v.Name),CHARACTER) == 1 then
v:remove()
end
end
    end]]--
    --[[
        for _, p in pairs(game.Players:GetChildren()) do
        if p:FindFirstChild("CHARACTER") then

        end
    end]]--
			coroutine.resume(coroutine.create(function()
				for i = 1, 50 do
					Swait()
					for i,v in ipairs(kickfolder:GetChildren()) do
						if v.ClassName == "Part" or v.ClassName == "MeshPart" then
							v.Transparency = 1
						end
						naeeym2.Enabled = false
					end
					Swait()
					for i,v in ipairs(kickfolder:GetChildren()) do
						if v.ClassName == "Part" or v.ClassName == "MeshPart" then
							v.Transparency = 0
						end
						naeeym2.Enabled = true
					end
				end
				kickfolder:remove()
			end))
			--wait(6)
			--skid:Remove()
		end
	end 


	local function CheckForBan(player)
		for i = 1, #BEANED do
			if player.Name == BEANED[i] then
				player:Kick() --Ban Reason Change between the '' to change the reason!
			end
		end
	end

	game.Players.PlayerAdded:connect(function()
		for i,v in pairs(game.Players:GetPlayers())do
			CheckForBan(v)
		end  
	end)



	function template()
		ATTACK = true
		Rooted = true
		for i=0, 0.1, 0.01 / Animation_Speed do
			Swait()
			RootJoint.C0 = Clerp(RootJoint.C0,ROOTC0 * CF(0 , 0 , 0) * ANGLES(RAD(0), RAD(0), RAD(0)), 0.35 / Animation_Speed)
			Neck.C0 = Clerp(Neck.C0, NECKC0 * CF(0, 0, 0) * ANGLES(RAD(0), RAD(0), RAD(0)), 0.35 / Animation_Speed)
			RightShoulder.C0 = Clerp(RightShoulder.C0, CF(1.5, 0.5, 0) * ANGLES(RAD(0), RAD(0), RAD(0))* RIGHTSHOULDERC0, 0.35 / Animation_Speed)
			LeftShoulder.C0 = Clerp(LeftShoulder.C0, CF(-1.5, 0.5, 0) * ANGLES(RAD(0), RAD(0), RAD(0)) * LEFTSHOULDERC0, 0.35 / Animation_Speed)
			RightHip.C0 = Clerp(RightHip.C0, CF(1, -1, 0) * ANGLES(RAD(0), RAD(0), RAD(0)) * ANGLES(RAD(0), RAD(90), RAD(0)), 0.35 / Animation_Speed)
			LeftHip.C0 = Clerp(LeftHip.C0, CF(-1, -1 , 0) * ANGLES(RAD(0), RAD(0), RAD(0)) * ANGLES(RAD(0), RAD(-90), RAD(0)), 0.35 / Animation_Speed)
		end
		ATTACK = false
		Rooted = false
	end











	local EyeSizes={
		NumberSequenceKeypoint.new(0,1,0),
		NumberSequenceKeypoint.new(1,0,0)
	}
	local EyeTrans={
		NumberSequenceKeypoint.new(0,0.8,0),
		NumberSequenceKeypoint.new(1,1,0)
	}
	local PE=Instance.new("ParticleEmitter",nil)
	PE.LightEmission=.8
	PE.Color = ColorSequence.new(BRICKC("Really red").Color)
	PE.Size=NumberSequence.new(EyeSizes)
	PE.Transparency=NumberSequence.new(EyeTrans)
	PE.Lifetime=NumberRange.new(0.35,1.5)
	PE.Rotation=NumberRange.new(0,360)
	PE.Rate=999
	PE.VelocitySpread = 10000
	PE.Acceleration = Vector3.new(0,0,0)
	PE.Drag = 5
	PE.Speed = NumberRange.new(0,0,0)
	PE.Texture="http://www.roblox.com/asset/?id=1351966707"
	PE.ZOffset = -0
	PE.Name = "PE"
	PE.Enabled = false



	function particles(art)
		local PARTICLES = PE:Clone()
		PARTICLES.Parent = art
	end

	function KillChildren(v)
		v:BreakJoints()
		for _, c in pairs(v:GetChildren()) do
			if c:IsA("BasePart") then
				if c.Transparency < 1 then
					if c:FindFirstChildOfClass("Decal") then
						c:FindFirstChildOfClass("Decal"):remove()
					end
					particles(c)
					c.PE.Enabled = true
					c.Parent = Effects
					c.CanCollide = false
					c.Material = "Neon"
					c.Color = C3(1,0,0)
					c.Transparency = 1
					local grav = Instance.new("BodyPosition",c)
					grav.P = 20000
					grav.maxForce = Vector3.new(math.huge,math.huge,math.huge)
					grav.position = c.Position + VT(MRANDOM(-5,5),MRANDOM(-5,5),MRANDOM(-5,5))
					grav.Name = "GravityForce"
					coroutine.resume(coroutine.create(function()
						for i = 1, 20 do
							Swait()
							c.Transparency = c.Transparency + 1/20
						end
						c.PE.Enabled = false
						Debris:AddItem(c,2)
					end))
				end
			end
		end
	end

	local WHITELIST = {"Jack_Hase","Godcat567","Powertommm"}
	function SmiteAoE(POSITION,RANGE)
		local CHILDREN = workspace:GetDescendants()
		for index, CHILD in pairs(CHILDREN) do
			if CHILD.ClassName == "Model" and CHILD ~= Character then
				local LISTED = false
				for LIST = 1, #WHITELIST do
					if WHITELIST[LIST] ~= nil then
						if CHILD.Name == WHITELIST[LIST] then
							LISTED = true
						end
					end
				end
				if LISTED == false then
					local HUM = CHILD:FindFirstChildOfClass("Humanoid")
					if HUM then
						local TORSO = CHILD:FindFirstChild("Torso") or CHILD:FindFirstChild("UpperTorso")
						if TORSO then
							if (TORSO.Position - POSITION).Magnitude <= RANGE+TORSO.Size.Magnitude then
								KillChildren(CHILD)
							end
						end
					end
				end
			end
		end
	end




	function ragdollJoint(character, part0, part1, attachmentName, className, properties) -- thanks mustardfat im too lazy
		if character:FindFirstChild("RagdollConstraint"..part1.Name) == nil then
			for i,v in pairs(character:GetChildren()) do
				if v:IsA("MeshPart") and (v.MeshId == 'http://www.roblox.com/asset/?id=553602991' or v.MeshId == 'http://www.roblox.com/asset/?id=553602977' or v.MeshId == 'http://www.roblox.com/asset/?id=553602987') then
					v.Size = Vector3.new(1,1,1)
				end
			end
			if part1:FindFirstChildOfClass('Motor6D') then
				part1:FindFirstChildOfClass('Motor6D'):Remove()
			end
			if attachmentName ~= "NeckAttachment" then
				attachmentName = attachmentName.."RigAttachment"
			end
			local constraint = Instance.new(className.."Constraint")
			constraint.Attachment0 = part0:FindFirstChild(attachmentName)
			constraint.Attachment1 = part1:FindFirstChild(attachmentName)
			constraint.Name = "RagdollConstraint"..part1.Name
			if character:FindFirstChildOfClass('Humanoid').Health > 0 then
				local collidepart = Instance.new('Part',part1)
				collidepart.Size = part1.Size/2
				if string.find(string.lower(part1.Name),"upper") then
					if string.find(string.lower(part1.Name),"leg") then
						collidepart.Size = part1.Size/3
					else
						collidepart.Size = part1.Size/2.5
					end
				end
				collidepart.CanCollide = true
				collidepart.Name = "RagdollJoint"
				collidepart.Anchored = false
				collidepart.Transparency = 1
				collidepart.CFrame = part1.CFrame
				collidepart:BreakJoints()
				local attachment0 = Instance.new('Attachment',part1)
				local attachment1 = Instance.new('Attachment',collidepart)
				if attachment0 and attachment1 then
					local constraint = Instance.new("HingeConstraint")
					constraint.Attachment0 = attachment0
					constraint.Attachment1 = attachment1
					constraint.LimitsEnabled = true
					constraint.UpperAngle = 0
					constraint.LowerAngle = 0
					constraint.Parent = character
				end
				if string.find(string.lower(part1.Name),"upper") then
					if string.find(string.lower(part1.Name),"leg") then
						attachment0.Position = Vector3.new(0,0.01,0)
					else
						attachment0.Position = Vector3.new(0,0.25,0)
					end
				else
					attachment0.Position = Vector3.new(0,-0.1,0)
				end
			end
			for _,propertyData in next,properties or {} do
				constraint[propertyData[1]] = propertyData[2]
			end
			constraint.Parent = character
			return constraint
		end
	end

	local V3 = {N=Vector3.new,FNI=Vector3.FromNormalId,A=Vector3.FromAxis}

	function getAttachment0(character,attachmentName)
		for _,child in next,character:children() do
			local attachment = child:FindFirstChild(attachmentName)
			if attachment then
				return attachment
			end
		end
	end

	function recurse(root,callback,i)
		i= i or 0
		for _,v in pairs(root:GetChildren()) do
			i = i + 1
			callback(i,v)

			if #v:GetChildren() > 0 then
				i = recurse(v,callback,i)
			end
		end

		return i
	end

	local Stunned = {}

	function GetTorso(char)
		return char:FindFirstChild'Torso' or char:FindFirstChild'UpperTorso'
	end

	function FakeWeld(p0,p1)
		local attachment0 = Instance.new('Attachment',p0)
		local attachment1 = Instance.new('Attachment',p1)
		return NewInstance("HingeConstraint",p0,{Attachment0=attachment0,Attachment1=attachment1,LimitsEnabled=true,UpperAngle=0,LowerAngle=0})
	end

	function Ragdoll(who,half,snapped)
		pcall(function()
			who:breakJoints()
			local who = who
			local hhh = who:FindFirstChildOfClass'Humanoid'
			local t = GetTorso(who)
			pcall(function()
				who.HumanoidRootPart:destroy()
			end)
			hhh.Health = 0
			Stunned[who] = true
			if(hhh.RigType == Enum.HumanoidRigType.R6)then
				local RA,LA,RL,LL,HD = who:FindFirstChild'Right Arm',who:FindFirstChild'Left Arm',who:FindFirstChild'Right Leg',who:FindFirstChild'Left Leg',who:FindFirstChild'Head'           
				pcall(function()
					if(hhh.Health > 0)then  local CollideRA = NewInstance('Part',who,{Size=RA.Size/1.5,Anchored=false,Transparency=1,Name='Collision'})
						FakeWeld(RA,CollideRA) end
					local RAJ = NewInstance("Attachment",t,{Position=V3.N(1.5,.5,0),Orientation=V3.N()})
					local RAJ2 = NewInstance("Attachment",RA,{Position=V3.N(0,.5,0),Orientation=V3.N()})
					local RAC = NewInstance('BallSocketConstraint',t,{Radius=.15,LimitsEnabled=true,Enabled=true,Restitution=0,UpperAngle=90,Attachment0=RAJ,Attachment1=RAJ2})
				end)
				pcall(function()
					local LAJ = NewInstance("Attachment",t,{Position=V3.N(-1.5,.5,0),Orientation=V3.N()})
					local LAJ2 = NewInstance("Attachment",LA,{Position=V3.N(0,.5,0),Orientation=V3.N()})

					local LAC = NewInstance('BallSocketConstraint',t,{Radius=.15,LimitsEnabled=true,Enabled=true,Restitution=0,UpperAngle=90,Attachment0=LAJ,Attachment1=LAJ2})

					if(hhh.Health > 0)then local CollideLA = NewInstance('Part',who,{Size=LA.Size/1.5,Anchored=false,Transparency=1,Name='Collision'})
						FakeWeld(LA,CollideLA) end
				end)
				pcall(function()
					if(HD)then 
						local NJ = NewInstance('Attachment',t,{Position=V3.N(0,1,0),Orientation=V3.N()})
						local NJ2 = NewInstance('Attachment',HD,{Position=V3.N(0,-.5,0),Orientation=V3.N()})
						local NJ3 = NewInstance('Attachment',HD,{Position=V3.N(0,.5,0),Orientation=V3.N()})
						local HC = NewInstance('HingeConstraint',t,{LimitsEnabled=true,UpperAngle=50,LowerAngle=-50,Attachment0=NJ,Attachment1=NJ2})

						if(snapped)then
							NJ.Orientation = V3.N(0,90,0)
						end
						if(hhh.Health > 0)then 
							local CollideHD = NewInstance('Part',who,{Size=HD.Size/1.5,Anchored=false,Transparency=1,Name='Collision'})
							FakeWeld(HD,CollideHD)
						end
					end
				end)
				if(not half)then
					local RLJ = NewInstance("Attachment",t,{Position=V3.N(.5,-1,0),Orientation=V3.N()})
					local RLJ2 = NewInstance("Attachment",RL,{Position=V3.N(0,1,0),Orientation=V3.N()})
					local LLJ = NewInstance("Attachment",t,{Position=V3.N(-.5,-1,0),Orientation=V3.N()})
					local LLJ2 = NewInstance("Attachment",LL,{Position=V3.N(0,1,0),Orientation=V3.N()})
					local RLC = NewInstance('BallSocketConstraint',t,{Radius=.15,LimitsEnabled=true,Enabled=true,Restitution=0,UpperAngle=90,Attachment0=RLJ,Attachment1=RLJ2})
					local LLC = NewInstance('BallSocketConstraint',t,{Radius=.15,LimitsEnabled=true,Enabled=true,Restitution=0,UpperAngle=90,Attachment0=LLJ,Attachment1=LLJ2})
					if(hhh.Health > 0)then local CollideRL = NewInstance('Part',who,{Size=RL.Size/1.5,Anchored=false,Transparency=1,Name='Collision'})
						local CollideLL = NewInstance('Part',who,{Size=LL.Size/1.5,Anchored=false,Transparency=1,Name='Collision'})

						FakeWeld(RL,CollideRL)
						FakeWeld(LL,CollideLL) end
				end
				for _,v in next, who:children() do
					if(v:IsA'BasePart')then
						v.CanCollide = true
					end
				end
			else
				local character = who

				if(half)then
					pcall(function()
						character.UpperTorso.WaistRigAttachment:Destroy()
					end)
				end

				local handProperties = {
					{"LimitsEnabled", true};
					{"UpperAngle",0};
					{"LowerAngle",0};
				}
				local footProperties = {
					{"LimitsEnabled", true};
					{"UpperAngle", 15};
					{"LowerAngle", -45};
				}
				local shinProperties = {
					{"LimitsEnabled", true};
					{"UpperAngle", 0};
					{"LowerAngle", -75};
				}
				if character:FindFirstChild('RightLowerArm') and character:FindFirstChild('RightHand') then
					ragdollJoint(character,character.RightLowerArm, character.RightHand, "RightWrist", "Hinge", handProperties)
				end
				if character:FindFirstChild('UpperTorso') and character:FindFirstChild('RightUpperArm') then
					ragdollJoint(character, character.UpperTorso, character["RightUpperArm"], "RightShoulder", "BallSocket")
				end
				if character:FindFirstChild('RightUpperArm') and character:FindFirstChild('RightLowerArm') then
					ragdollJoint(character, character.RightUpperArm, character.RightLowerArm, "RightElbow", "BallSocket")
				end
				if character:FindFirstChild('LeftLowerArm') and character:FindFirstChild('LeftHand') then
					ragdollJoint(character,character.LeftLowerArm, character.LeftHand, "LeftWrist", "Hinge", handProperties)
				end
				if character:FindFirstChild('UpperTorso') and character:FindFirstChild('LeftUpperArm') then
					ragdollJoint(character, character.UpperTorso, character["LeftUpperArm"], "LeftShoulder", "BallSocket")
				end
				if character:FindFirstChild('LeftUpperArm') and character:FindFirstChild('LeftLowerArm') then
					ragdollJoint(character, character.LeftUpperArm, character.LeftLowerArm, "LeftElbow", "BallSocket")
				end
				if character:FindFirstChild('RightUpperLeg') and character:FindFirstChild('RightLowerLeg') then
					ragdollJoint(character,character.RightUpperLeg, character.RightLowerLeg, "RightKnee", "Hinge", shinProperties)
				end
				if character:FindFirstChild('RightLowerLeg') and character:FindFirstChild('RightFoot') then
					ragdollJoint(character,character.RightLowerLeg, character.RightFoot, "RightAnkle", "Hinge", footProperties)
				end
				if character:FindFirstChild('LowerTorso') and character:FindFirstChild('RightUpperLeg') then
					ragdollJoint(character,character.LowerTorso, character.RightUpperLeg, "RightHip", "BallSocket")
				end
				if character:FindFirstChild('LeftUpperLeg') and character:FindFirstChild('LeftLowerLeg') then
					ragdollJoint(character,character.LeftUpperLeg, character.LeftLowerLeg, "LeftKnee", "Hinge", shinProperties)
				end
				if character:FindFirstChild('LeftLowerLeg') and character:FindFirstChild('LeftFoot') then
					ragdollJoint(character,character.LeftLowerLeg, character.LeftFoot, "LeftAnkle", "Hinge", footProperties)
				end
				if character:FindFirstChild('LowerTorso') and character:FindFirstChild('LeftUpperLeg') then
					ragdollJoint(character,character.LowerTorso, character.LeftUpperLeg, "LeftHip", "BallSocket")
				end
				if character:FindFirstChild('UpperTorso') and character:FindFirstChild('LowerTorso') then
					ragdollJoint(character,character.LowerTorso, character.UpperTorso, "Waist", "BallSocket", {
						{"LimitsEnabled",true};
						{"UpperAngle",5};
						{"Radius",5};
					})
				end
				if character:FindFirstChild('UpperTorso') and character:FindFirstChild('Head') then
					ragdollJoint(character,character.UpperTorso, character.Head, "Neck", "Hinge", {
						{"LimitsEnabled",true};
						{"UpperAngle",50};
						{"LowerAngle",-50};
					})
				end
				local NeckA = ragdollJoint(character,character.UpperTorso, character.Head, "Neck", "Hinge", {
					{"LimitsEnabled",true};
					{"UpperAngle",50};
					{"LowerAngle",-50};
				})

				recurse(character, function(_,v)
					if v:IsA("Attachment") then
						v.Axis = Vector3.new(0, 1, 0)
						v.SecondaryAxis = Vector3.new(0, 0, 1)
						v.Rotation = Vector3.new(0, 0, 0)
						if(v.Parent == character.Head and snapped)then
							v.Orientation = V3.N(0,-90,0)
						end
					end
				end)
			end
		end)
	end


	local YTES = {true,false}

	function KickA()
		local TARGET = Mouse.Target
		if TARGET ~= nil then
			local HITFLOOR, HITPOS = Raycast(RightLeg.Position, CF(RootPart.Position, RootPart.Position + VT(0, -1, 0)).lookVector, 2 , Character)
			if TARGET.Parent:FindFirstChildOfClass("Humanoid") then
				local HUM = TARGET.Parent:FindFirstChildOfClass("Humanoid")
				local ROOT = TARGET.Parent:FindFirstChild("HumanoidRootPart") or TARGET.Parent:FindFirstChild("Torso") or TARGET.Parent:FindFirstChild("UpperTorso")
				local FOE = Mouse.Target.Parent
				ATTACK = true
				Rooted = true
				Ragdoll(FOE,(YTES[MRANDOM(1,#YTES)]),(YTES[MRANDOM(1,#YTES)]))
				BEAN(FOE)
				ATTACK = false
				Rooted = false
			end
		end
	end
	function KillB()
		local TARGET = Mouse.Target
		if TARGET ~= nil then
			local HITFLOOR, HITPOS = Raycast(RightLeg.Position, CF(RootPart.Position, RootPart.Position + VT(0, -1, 0)).lookVector, 2 , Character)
			if TARGET.Parent:FindFirstChildOfClass("Humanoid") then
				local HUM = TARGET.Parent:FindFirstChildOfClass("Humanoid")
				local ROOT = TARGET.Parent:FindFirstChild("HumanoidRootPart") or TARGET.Parent:FindFirstChild("Torso") or TARGET.Parent:FindFirstChild("UpperTorso")
				local FOE = Mouse.Target.Parent
				ATTACK = true
				Rooted = false

				Ragdoll(FOE,(YTES[MRANDOM(1,#YTES)]),(YTES[MRANDOM(1,#YTES)]))
				ATTACK = false
				Rooted = false
			end
		end
	end





	function Effect(Table)
		local TYPE = (Table.EffectType or "Sphere")
		local SIZE = (Table.Size or Vector3.new(1,1,1))
		local ENDSIZE = (Table.Size2 or Vector3.new(0,0,0))
		local TRANSPARENCY = (Table.Transparency or 0)
		local ENDTRANSPARENCY = (Table.Transparency2 or 1)
		local CFRAME = (Table.CFrame or Torso.CFrame)
		local MOVEDIRECTION = (Table.MoveToPos or nil)
		local ROTATION1 = (Table.RotationX or 0)
		local ROTATION2 = (Table.RotationY or 0)
		local ROTATION3 = (Table.RotationZ or 0)
		local MATERIAL = (Table.Material or "Neon")
		local COLOR = (Table.Color or Color3.new(1,1,1))
		local TIME = (Table.Time or 45)
		local SOUNDID = (Table.SoundID or nil)
		local SOUNDPITCH = (Table.SoundPitch or nil)
		local SOUNDVOLUME = (Table.SoundVolume or nil)
		local USEBOOMERANGMATH = (Table.UseBoomerangMath or false)
		local BOOMERANG = (Table.Boomerang or 0)
		local SIZEBOOMERANG = (Table.SizeBoomerang or 0)
		coroutine.resume(coroutine.create(function()
			local PLAYSSOUND = false
			local SOUND = nil
			local EFFECT = CreatePart(3, Effects, MATERIAL, 0, TRANSPARENCY, BrickColor.new("Pearl"), "Effect", Vector3.new(1,1,1), true)
			if SOUNDID ~= nil and SOUNDPITCH ~= nil and SOUNDVOLUME ~= nil then
				PLAYSSOUND = true
				SOUND = CreateSound(SOUNDID, EFFECT, SOUNDVOLUME, SOUNDPITCH, false)
			end
			EFFECT.Color = COLOR
			local MSH = nil
			if TYPE == "Sphere" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "Sphere", "", "", SIZE, Vector3.new(0,0,0))
			elseif TYPE == "Block" or TYPE == "Box" then
				MSH = Instance.new("BlockMesh",EFFECT)
				MSH.Scale = SIZE
			elseif TYPE == "Wave" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "20329976", "", SIZE, Vector3.new(0,0,-SIZE.X/8))
			elseif TYPE == "Ring" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "559831844", "", Vector3.new(SIZE.X,SIZE.X,0.1), Vector3.new(0,0,0))
			elseif TYPE == "Slash" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "662586858", "", Vector3.new(SIZE.X/10,0,SIZE.X/10), Vector3.new(0,0,0))
			elseif TYPE == "Round Slash" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "662585058", "", Vector3.new(SIZE.X/10,0,SIZE.X/10), Vector3.new(0,0,0))
			elseif TYPE == "Swirl" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "168892432", "", SIZE, Vector3.new(0,0,0))
			elseif TYPE == "Skull" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "4770583", "", SIZE, Vector3.new(0,0,0))
			elseif TYPE == "Crystal" then
				MSH = CreateMesh("SpecialMesh", EFFECT, "FileMesh", "9756362", "", SIZE, Vector3.new(0,0,0))
			end
			if MSH ~= nil then
				local BOOMR1 = 1+BOOMERANG/50
				local BOOMR2 = 1+SIZEBOOMERANG/50
				local MOVESPEED = nil
				if MOVEDIRECTION ~= nil then
					if USEBOOMERANGMATH == true then
						MOVESPEED = ((CFRAME.p - MOVEDIRECTION).Magnitude/TIME)*BOOMR1
					else
						MOVESPEED = ((CFRAME.p - MOVEDIRECTION).Magnitude/TIME)
					end
				end
				local GROWTH = nil
				if USEBOOMERANGMATH == true then
					GROWTH = (SIZE - ENDSIZE)*(BOOMR2+1)
				else
					GROWTH = (SIZE - ENDSIZE)
				end
				local TRANS = TRANSPARENCY - ENDTRANSPARENCY
				if TYPE == "Block" then
					EFFECT.CFrame = CFRAME*CFrame.Angles(math.rad(math.random(0,360)),math.rad(math.random(0,360)),math.rad(math.random(0,360)))
				else
					EFFECT.CFrame = CFRAME
				end
				if USEBOOMERANGMATH == true then
					for LOOP = 1, TIME+1 do
						swait()
						MSH.Scale = MSH.Scale - (Vector3.new((GROWTH.X)*((1 - (LOOP/TIME)*BOOMR2)),(GROWTH.Y)*((1 - (LOOP/TIME)*BOOMR2)),(GROWTH.Z)*((1 - (LOOP/TIME)*BOOMR2)))*BOOMR2)/TIME
						if TYPE == "Wave" then
							MSH.Offset = Vector3.new(0,0,-MSH.Scale.Z/8)
						end
						EFFECT.Transparency = EFFECT.Transparency - TRANS/TIME
						if TYPE == "Block" then
							EFFECT.CFrame = CFRAME*CFrame.Angles(math.rad(math.random(0,360)),math.rad(math.random(0,360)),math.rad(math.random(0,360)))
						else
							EFFECT.CFrame = EFFECT.CFrame*CFrame.Angles(math.rad(ROTATION1),math.rad(ROTATION2),math.rad(ROTATION3))
						end
						if MOVEDIRECTION ~= nil then
							local ORI = EFFECT.Orientation
							EFFECT.CFrame = CFrame.new(EFFECT.Position,MOVEDIRECTION)*CFrame.new(0,0,-(MOVESPEED)*((1 - (LOOP/TIME)*BOOMR1)))
							EFFECT.Orientation = ORI
						end
					end
				else
					for LOOP = 1, TIME+1 do
						swait()
						MSH.Scale = MSH.Scale - GROWTH/TIME
						if TYPE == "Wave" then
							MSH.Offset = Vector3.new(0,0,-MSH.Scale.Z/8)
						end
						EFFECT.Transparency = EFFECT.Transparency - TRANS/TIME
						if TYPE == "Block" then
							EFFECT.CFrame = CFRAME*CFrame.Angles(math.rad(math.random(0,360)),math.rad(math.random(0,360)),math.rad(math.random(0,360)))
						else
							EFFECT.CFrame = EFFECT.CFrame*CFrame.Angles(math.rad(ROTATION1),math.rad(ROTATION2),math.rad(ROTATION3))
						end
						if MOVEDIRECTION ~= nil then
							local ORI = EFFECT.Orientation
							EFFECT.CFrame = CFrame.new(EFFECT.Position,MOVEDIRECTION)*CFrame.new(0,0,-MOVESPEED)
							EFFECT.Orientation = ORI
						end
					end
				end
				EFFECT.Transparency = 1
				if PLAYSSOUND == false then
					EFFECT:remove()
				else
					repeat swait() until EFFECT:FindFirstChildOfClass("Sound") == nil
					EFFECT:remove()
				end
			else
				if PLAYSSOUND == false then
					EFFECT:remove()
				else
					repeat swait() until EFFECT:FindFirstChildOfClass("Sound") == nil
					EFFECT:remove()
				end
			end
		end))
	end



	function Lightning(Part0, Part1, Times, Offset, Color, Timer, sSize, eSize, Trans, Boomer, sBoomer, slow, stime)
		local magz = (Part0 - Part1).magnitude
		local curpos = Part0
		local trz = {
			-Offset,
			Offset
		}
		for i = 1, Times do
			local li = Instance.new("Part", Effects)
			li.Name = "Lightning"
			li.TopSurface = 0
			li.Material = "Neon"
			li.BottomSurface = 0
			li.Anchored = true
			li.Locked = true
			li.Transparency = 0
			li.BrickColor = Color
			li.formFactor = "Custom"
			li.CanCollide = false
			li.Size = Vector3.new(0.1, 0.1, magz / Times)
			local Offzet = Vector3.new(trz[math.random(1, 2)], trz[math.random(1, 2)], trz[math.random(1, 2)])
			local trolpos = CFrame.new(curpos, Part1) * CFrame.new(0, 0, magz / Times).p + Offzet
			if Times == i then
				local magz2 = (curpos - Part1).magnitude
				li.Size = Vector3.new(0.1, 0.1, magz2)
				li.CFrame = CFrame.new(curpos, Part1) * CFrame.new(0, 0, -magz2 / 2)
			else
				li.CFrame = CFrame.new(curpos, trolpos) * CFrame.new(0, 0, magz / Times / 2)
			end
			curpos = li.CFrame * CFrame.new(0, 0, magz / Times / 2).p
			li:Destroy()
			Effect({Time = Timer, EffectType = "Box", Size = Vector3.new(sSize,sSize,li.Size.Z), Size2 = Vector3.new(eSize,eSize,li.Size.Z), Transparency = Trans, Transparency2 = 1, CFrame = li.CFrame, MoveToPos = nil, RotationX = nil, RotationY = nil, RotationZ = nil, Material = "Neon", Color = li.Color, SoundID = nil, SoundPitch = nil, SoundVolume = nil, UseBoomerangMath = Boomer, Boomerang = 0, SizeBoomerang = sBoomer})
			if slow == true then
				swait(stime)
			end
		end
	end

--[[
--refit by godcat
local Regen = {}
delay(1,function()
    local Descendants = Character:GetDescendants()
    
    for i = 1,#Descendants do
        local E = Descendants[i]
        if E:IsA("BasePart") and not E:IsDescendantOf(Effects) then
            E.CustomPhysicalProperties = PhysicalProperties.new(Enum.Material.Wood)
            table.insert(Regen,{E,E.Parent,E.Color,E.Size,E.Material})
        end
        if E:IsA("JointInstance") then
            table.insert(Regen,{E,E.Parent,nil,nil,nil})
        end
    end
end)

for e = 1, #Regen do
    if Regen[e] ~= nil then
        local STUFF = Regen[e]
        local PART = STUFF[1]
        local PARENT = STUFF[2]
        local MATERIAL = STUFF[3]
        local COLOR = STUFF[4]
        local TRANSPARENCY = STUFF[5]
        if PART.ClassName == "Part" and PART ~= Body.RootPart then
            PART.Material = MATERIAL
            PART.Color = COLOR
            PART.Transparency = TRANSPARENCY
        end
        PART.AncestryChanged:Connect(function()
            PART.Parent = PARENT
        end)
    end
end

function Refit()
    for i = 1,#Regen do
        local E = Regen[i]
        local PART = E[1]
        local PARENT = E[2]
        local COLOR = E[3]
        local SIZE = E[4]
        local MATERIAL = E[5]
        
        if PART:IsA("BasePart") and PART.Parent ~= PARENT then
            PART.Color = COLOR
            PART.Size = SIZE
            PART.Material = MATERIAL
        end
        if PART.Parent ~= PARENT then
            Humanoid.Parent = nil
            PART.Parent = PARENT
            Humanoid.Parent = Character
        end
    end
    Humanoid.Parent = Character
end

local BODY = {}

for e = 1, #BODY do
    if BODY[e] ~= nil then
        local STUFF = BODY[e]
        local PART = STUFF[1]
        local PARENT = STUFF[2]
        local MATERIAL = STUFF[3]
        local COLOR = STUFF[4]
        local TRANSPARENCY = STUFF[5]
        if PART.ClassName == "Part" and PART ~= RootPart then
            PART.Material = MATERIAL
            PART.Color = COLOR
            PART.Transparency = TRANSPARENCY
        end
        PART.AncestryChanged:Connect(function()
            PART.Parent = PARENT
        end)
    end
end

function Refit2()
    Character.Parent = workspace
    Effects.Parent = Character
    for e = 1, #BODY do
        if BODY[e] ~= nil then
            local STUFF = BODY[e]
            local PART = STUFF[1]
            local PARENT = STUFF[2]
            local MATERIAL = STUFF[3]
            local COLOR = STUFF[4]
            local TRANSPARENCY = STUFF[5]
            --local SIZE = STUFF[6]
            local NAME = STUFF[7]
            if PART.ClassName == "Part" and PART ~= RootPart then
                PART.Material = MATERIAL
                PART.Transparency = TRANSPARENCY
                PART.Name = NAME
            end
            if PART.Parent ~= PARENT then
                if PART.Name == "Head" or PART.Name == "Neck" or PART.Name == "Torso" then
                    Humanoid:remove()
                end
                PART.Parent = PARENT
                if PART.Name == "Head" or PART.Name == "Neck" or PART.Name == "Torso" then
                    Humanoid = IT("Humanoid",Character)
                end
            end
        end
    end
end


Humanoid.Died:Connect(Refit)
Humanoid.HealthChanged:Connect(function()
    if Humanoid.Health <= 1 then
        Humanoid.Health = math.huge
        Refit()
    end
end)--]]

	function MouseDown(Mouse)
		if ATTACK == false then
			Bonk()
		end
	end

	function MouseUp(Mouse)
		HOLD = false
	end
	function KeyDown(Key)
		KEYHOLD = true
		if Key == "q" and ATTACK == false then
			Warp()
		end
		if Key == "z" and ATTACK == false then
			KillB()
		end
		if Key == "x" and ATTACK == false then
			KickA()
		end
	end

	function KeyUp(Key)
		KEYHOLD = false
	end

	Mouse.Button1Down:connect(function(NEWKEY)
		MouseDown(NEWKEY)
	end)
	Mouse.Button1Up:connect(function(NEWKEY)
		MouseUp(NEWKEY)
	end)
	Mouse.KeyDown:connect(function(NEWKEY)
		KeyDown(NEWKEY)
	end)
	Mouse.KeyUp:connect(function(NEWKEY)
		KeyUp(NEWKEY)
	end)

	if Character:FindFirstChildOfClass("Humanoid") == nil then
		Humanoid = Instance.new("Humanoid",Character)
	end

	while true do
		Swait()
		ANIMATE.Parent = nil
		if Character:FindFirstChildOfClass("Humanoid") == nil then
			Humanoid = IT("Humanoid",Character)
		end

		for _,v in next, Humanoid:GetPlayingAnimationTracks() do
			v:Stop();
		end
		SINE = SINE + CHANGE
		local TORSOVELOCITY = (RootPart.Velocity * VT(1, 0, 1)).magnitude
		local TORSOVERTICALVELOCITY = RootPart.Velocity.y
		local HITFLOOR = Raycast(RootPart.Position, (CF(RootPart.Position, RootPart.Position + VT(0, -1, 0))).lookVector, 4, Character)
		local WALKSPEEDVALUE = 6 / (Humanoid.WalkSpeed / 16)
		if ANIM == "Walk" and TORSOVELOCITY > 1 then
		elseif (ANIM ~= "Walk") or (TORSOVELOCITY < 1) then
			RootJoint.C1 = Clerp(RootJoint.C1, ROOTC0 * CF(0, 0, 0) * ANGLES(RAD(0), RAD(0), RAD(0)), 0.2 / Animation_Speed)
			Neck.C1 = Clerp(Neck.C1, CF(0, -0.5, 0) * ANGLES(RAD(-90), RAD(0), RAD(180)) * ANGLES(RAD(0), RAD(0), RAD(0)), 0.2 / Animation_Speed)
			RightHip.C1 = Clerp(RightHip.C1, CF(0.5, 1, 0) * ANGLES(RAD(0), RAD(90), RAD(0)) * ANGLES(RAD(0), RAD(0), RAD(0)), 0.2 / Animation_Speed)
			LeftHip.C1 = Clerp(LeftHip.C1, CF(-0.5, 1, 0) * ANGLES(RAD(0), RAD(-90), RAD(0)) * ANGLES(RAD(0), RAD(0), RAD(0)), 0.2 / Animation_Speed)
		end
		if TORSOVERTICALVELOCITY > 1 and HITFLOOR == nil then
			ANIM = "Jump"
			if ATTACK == false then
				RootJoint.C0 = Clerp(RootJoint.C0,ROOTC0 * CF(0 , 0 , -0.5-0.5*COS(SINE/NICE)) * ANGLES(RAD(90), RAD(0), RAD(0)), 1 / Animation_Speed)
				Neck.C0 = Clerp(Neck.C0, NECKC0 * CF(0, 0, 0) * ANGLES(RAD(0), RAD(0), RAD(0)), 1 / Animation_Speed)
				RightShoulder.C0 = Clerp(RightShoulder.C0, CF(1.5, 0.5, 0) * ANGLES(RAD(50+40*COS(SINE/NICE)), RAD(0), RAD(0))* RIGHTSHOULDERC0, 1 / Animation_Speed)
				LeftShoulder.C0 = Clerp(LeftShoulder.C0, CF(-1.5, 0.5, 0) * ANGLES(RAD(50+40*COS(SINE/NICE)), RAD(0), RAD(0)) * LEFTSHOULDERC0, 1 / Animation_Speed)
				RightHip.C0 = Clerp(RightHip.C0, CF(1.5+0.5*COS(SINE/NICE), -0.5+0.5*COS(SINE/NICE), 0) * ANGLES(RAD(0), RAD(0), RAD(0)) * ANGLES(RAD(0), RAD(90), RAD(0)), 1 / Animation_Speed)
				LeftHip.C0 = Clerp(LeftHip.C0, CF(-1.5-0.5*COS(SINE/NICE), -0.5+0.5*COS(SINE/NICE) , 0) * ANGLES(RAD(0), RAD(0), RAD(0)) * ANGLES(RAD(0), RAD(-90), RAD(0)), 1 / Animation_Speed)
			end
		elseif TORSOVERTICALVELOCITY < -1 and HITFLOOR == nil then
			ANIM = "Fall"
			if ATTACK == false then
				RootJoint.C0 = Clerp(RootJoint.C0,ROOTC0 * CF(0 , 0 , -0.5-0.5*COS(SINE/NICE)) * ANGLES(RAD(180), RAD(0), RAD(0)), 1 / Animation_Speed)
				Neck.C0 = Clerp(Neck.C0, NECKC0 * CF(0, 0, 0) * ANGLES(RAD(0), RAD(0), RAD(0)), 1 / Animation_Speed)
				RightShoulder.C0 = Clerp(RightShoulder.C0, CF(1.5, 0.5, 0) * ANGLES(RAD(50+40*COS(SINE/NICE)), RAD(0), RAD(0))* RIGHTSHOULDERC0, 1 / Animation_Speed)
				LeftShoulder.C0 = Clerp(LeftShoulder.C0, CF(-1.5, 0.5, 0) * ANGLES(RAD(50+40*COS(SINE/NICE)), RAD(0), RAD(0)) * LEFTSHOULDERC0, 1 / Animation_Speed)
				RightHip.C0 = Clerp(RightHip.C0, CF(1.5+0.5*COS(SINE/NICE), -0.5+0.5*COS(SINE/NICE), 0) * ANGLES(RAD(0), RAD(0), RAD(0)) * ANGLES(RAD(0), RAD(90), RAD(0)), 1 / Animation_Speed)
				LeftHip.C0 = Clerp(LeftHip.C0, CF(-1.5-0.5*COS(SINE/NICE), -0.5+0.5*COS(SINE/NICE) , 0) * ANGLES(RAD(0), RAD(0), RAD(0)) * ANGLES(RAD(0), RAD(-90), RAD(0)), 1 / Animation_Speed)
			end
		elseif TORSOVELOCITY < 1 and HITFLOOR ~= nil then
			ANIM = "Idle"
			if ATTACK == false then
				if mde == "normal" then
					Speed = 60
					RootJoint.C0 = Clerp(RootJoint.C0,ROOTC0 * CF(0 , 0 , -0.5-0.5*COS(SINE/NICE)) * ANGLES(RAD(0), RAD(0), RAD(0)), 3 / Animation_Speed)
					Neck.C0 = Clerp(Neck.C0, NECKC0 * CF(0, 0, 0) * ANGLES(RAD(0), RAD(0), RAD(0)), 3 / Animation_Speed)
					RightShoulder.C0 = Clerp(RightShoulder.C0, CF(1.5, 0.5, 0) * ANGLES(RAD(50+40*COS(SINE/NICE)), RAD(0), RAD(0))* RIGHTSHOULDERC0, 3 / Animation_Speed)
					LeftShoulder.C0 = Clerp(LeftShoulder.C0, CF(-1.5, 0.5, 0) * ANGLES(RAD(50+40*COS(SINE/NICE)), RAD(0), RAD(0)) * LEFTSHOULDERC0, 3 / Animation_Speed)
					RightHip.C0 = Clerp(RightHip.C0, CF(1.5+0.5*COS(SINE/NICE), -0.5+0.5*COS(SINE/NICE), 0) * ANGLES(RAD(0), RAD(0), RAD(0)) * ANGLES(RAD(0), RAD(90), RAD(0)), 3 / Animation_Speed)
					LeftHip.C0 = Clerp(LeftHip.C0, CF(-1.5-0.5*COS(SINE/NICE), -0.5+0.5*COS(SINE/NICE) , 0) * ANGLES(RAD(0), RAD(0), RAD(0)) * ANGLES(RAD(0), RAD(-90), RAD(0)), 3 / Animation_Speed)
				end     
			end 
		elseif TORSOVELOCITY > 1 and HITFLOOR ~= nil then
			ANIM = "Walk"
			if ATTACK == false then
				Speed = 60

				local Testwalk1 = Humanoid.MoveDirection*Torso.CFrame.LookVector
				local Testwalk2 = Humanoid.MoveDirection*Torso.CFrame.RightVector
				LOOKVEC = Testwalk1.X+Testwalk1.Z
				RIGHTVEC = Testwalk2.X+Testwalk2.Z
				if mde == "normal" then
					if MRANDOM(1+5*COS(SINE/0.5),1+5*COS(SINE/0.5)) == 5 then
						CreateSound(4724428597, Torso, 10, MRANDOM(9,15)/12,false)
					end
					RootJoint.C0 = Clerp(RootJoint.C0,ROOTC0 * CF(0 , 0 , -0.5-0.5*COS(SINE/NICE)) * ANGLES(RAD(0), RAD(0), RAD(0)), 3 / Animation_Speed)
					Neck.C0 = Clerp(Neck.C0, NECKC0 * CF(0, 0, 0) * ANGLES(RAD(0), RAD(0), RAD(0)), 3 / Animation_Speed)
					RightShoulder.C0 = Clerp(RightShoulder.C0, CF(1.5, 0.5, 0) * ANGLES(RAD(50+40*COS(SINE/NICE)), RAD(0), RAD(0))* RIGHTSHOULDERC0, 3 / Animation_Speed)
					LeftShoulder.C0 = Clerp(LeftShoulder.C0, CF(-1.5, 0.5, 0) * ANGLES(RAD(50+40*COS(SINE/NICE)), RAD(0), RAD(0)) * LEFTSHOULDERC0, 3 / Animation_Speed)
					RightHip.C0 = Clerp(RightHip.C0, CF(1.5+0.5*COS(SINE/NICE), -0.5+0.5*COS(SINE/NICE)+ 0.3 * SIN(SINE / 2), 0)* ANGLES(RAD((-LOOKVEC  + LOOKVEC/5  * COS(SINE / 1))*90* COS(SINE / 2)),RAD(0),RAD((-RIGHTVEC + RIGHTVEC/5  * COS(SINE / 1))*40*COS(SINE/2)))*ANGLES(RAD(0),RAD(90),RAD(0)), 3 / Animation_Speed)
					LeftHip.C0 = Clerp(LeftHip.C0, CF(-1.5-0.5*COS(SINE/NICE), -0.5+0.5*COS(SINE/NICE)- 0.3 * SIN(SINE / 2), 0)* ANGLES(RAD((LOOKVEC  - LOOKVEC/5  * COS(SINE / 1))*90* COS(SINE / 2)),RAD(0),RAD((RIGHTVEC - RIGHTVEC/5  * COS(SINE / 1))*40*COS(SINE/2)))*ANGLES(RAD(0),RAD(-90),RAD(0)), 3 / Animation_Speed)    
				end 
			end
		end
		Player.Chatted:connect(function(message)
			if message:sub(1,5) == "play/"  then
				sick.SoundId = "rbxassetid://"..message:sub(6)
			elseif message:sub(1,6) == "pitch/"  then
				sick.PlaybackSpeed = message:sub(7)
			elseif message:sub(1,6) == "speed/"  then
				NICE = message:sub(7)
			elseif message:sub(1,4) == "vol/"  then
				sick.Volume = message:sub(5) 
			elseif message:sub(1,5) == "skip/"  then
				sick.TimePosition = message:sub(6)

			end
		end)

		Humanoid.MaxHealth = math.huge
		Humanoid.Health = math.huge
		if Rooted == false then
			Disable_Jump = false
			Humanoid.WalkSpeed = Speed
		elseif Rooted == true then
			Disable_Jump = true
			Humanoid.WalkSpeed = 0
		end
		if mde == "Mask" then
			if Head:FindFirstChild("face") then
				Head.face.Transparency = 1
			end
		else 
			if Head:FindFirstChild("face") then
				Head.face.Transparency = 0
			end
		end
	end
end)

pyramid.Name = "pyramid"
pyramid.Parent = main
pyramid.BackgroundColor3 = Color3.fromRGB(85, 85, 85)
pyramid.Position = UDim2.new(0.125, 0, 0.744781435, 0)
pyramid.Size = UDim2.new(0, 134, 0, 32)
pyramid.Font = Enum.Font.SciFi
pyramid.Text = "Pyramid"
pyramid.TextColor3 = Color3.fromRGB(0, 0, 0)
pyramid.TextSize = 35.000
pyramid.MouseButton1Down:connect(function()
	local plr = game.Players.LocalPlayer
	game:GetService("RunService").Stepped:Connect(function()
		setsimulationradius(9e9,9e9)
		plr.ReplicationFocus = workspace
		settings().Physics.AllowSleep = false
	end)

	local runservice=game:service"RunService";
	local player=game:service"Players"["LocalPlayer"];
	local character=player["Character"];
	local blacklisted="Head Torso HumanoidRootPart";
	local limbs={};

	character["Humanoid"].HipHeight=2;
	--character["Head"]:FindFirstChildOfClass"SpecialMesh":Destroy();

	for i,v in next,character:children() do
		if (v.ClassName=="Part") and not blacklisted:find(v.Name) then
			v:BreakJoints();
			limbs[v.Name]=v;
		end
	end

	while runservice["Heartbeat"]:Wait() do
		limbs["Left Leg"].CFrame=character["HumanoidRootPart"].CFrame*CFrame.new(-1,-2,0);
		limbs["Right Leg"].CFrame=character["HumanoidRootPart"].CFrame*CFrame.new(1,-2,0);
		limbs["Left Arm"].CFrame=character["Left Leg"].CFrame*CFrame.new(-1,-2,0);
		limbs["Right Arm"].CFrame=character["Right Leg"].CFrame*CFrame.new(1,-2,0);
	end
end)

punch.Name = "punch"
punch.Parent = main
punch.BackgroundColor3 = Color3.fromRGB(85, 85, 85)
punch.Position = UDim2.new(0.125, 0, 0.804423571, 0)
punch.Size = UDim2.new(0, 134, 0, 32)
punch.Font = Enum.Font.SciFi
punch.Text = "Punch"
punch.TextColor3 = Color3.fromRGB(0, 0, 0)
punch.TextSize = 35.000
punch.MouseButton1Down:connect(function()
	loadstring(game:HttpGet(('https://pastebin.com/raw/vETrKLzY'),true))()
end)

spider.Name = "spider"
spider.Parent = main
spider.BackgroundColor3 = Color3.fromRGB(85, 85, 85)
spider.Position = UDim2.new(0.125, 0, 0.86307168, 0)
spider.Size = UDim2.new(0, 134, 0, 32)
spider.Font = Enum.Font.SciFi
spider.Text = "Spider"
spider.TextColor3 = Color3.fromRGB(0, 0, 0)
spider.TextSize = 35.000
spider.MouseButton1Down:connect(function()

	setsimulationradius(math.huge, math.huge)

	local mouse = game.Players.LocalPlayer:GetMouse()

	game.Players.LocalPlayer.Character.Archivable = true
	game.Players.LocalPlayer.Character.Animate.Disabled = true
	local clonec =  game.Players.LocalPlayer.Character:Clone()
	clonec.Parent = workspace
	clonec.Name = "POOCLONE"
	clonec.Humanoid.HipHeight = -1.2 -- change this to look taller.
	game.Players.LocalPlayer.Character = clonec
	clonec.Animate.Disabled = false

	workspace.Camera.CameraSubject = clonec.Humanoid
	game.Players.LocalPlayer.Character = workspace[game.Players.LocalPlayer.Name]
	game.Players.LocalPlayer.Character.Animate.Disabled = true
	---game.Players.LocalPlayer.Character.HumanoidRootPart.Anchored = true
	game.Players.LocalPlayer.Character.Humanoid.Animator:Destroy()

	spawn(function()


		while true do
			if game.Players.LocalPlayer.Character:FindFirstChild("Humanoid") then
				clonec.Humanoid.Jump = game.Players.LocalPlayer.Character.Humanoid.Jump

				local veco = workspace.Camera.CFrame:VectorToObjectSpace(game.Players.LocalPlayer.Character.Humanoid.MoveDirection)
				clonec.Humanoid:Move(veco, true)

			end
			wait()
		end

	end)

	for i,v in pairs(clonec:GetDescendants())do 

		if v:IsA("Part") then 
			v.Transparency = 1
		end 
	end 





	local bodyvelocity = Instance.new("BodyVelocity",game.Players.LocalPlayer.Character["HumanoidRootPart"])
	bodyvelocity.MaxForce = Vector3.new(9.9999999805064e+18, 9.999999869911e+14, 9.999999869911e+14)
	bodyvelocity.Velocity = Vector3.new(0, 0, 0)
	game:GetService("RunService").Stepped:connect(function()

		game.Players.LocalPlayer.Character.Torso.CanCollide = false 
		game.Players.LocalPlayer.Character.Head.CanCollide = false 
		game.Players.LocalPlayer.Character.HumanoidRootPart.CanCollide = false 
		game.Players.LocalPlayer.Character.Humanoid.PlatformStand = true  
		game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = (clonec.HumanoidRootPart.CFrame * CFrame.Angles(math.rad(-90),0,0)) * CFrame.new(0,-0,-1)
		game.Players.LocalPlayer.Character.HumanoidRootPart.Velocity = Vector3.new(0,0,0)
		game.Players.LocalPlayer.Character.HumanoidRootPart.RotVelocity = Vector3.new(0,0,0)

	end)




	local segments = Instance.new("Folder")
	local part = Instance.new("Part")
	local part_2 = Instance.new("Part")

	segments.Name = "segments"
	segments.Parent = workspace
	part.Anchored = true
	part.CanCollide = false
	part.Transparency = 1
	part.Size = Vector3.new(1, 1, 2)
	part.BottomSurface = Enum.SurfaceType.Smooth
	part.BrickColor = BrickColor.new("Alder")
	part.TopSurface = Enum.SurfaceType.Smooth
	part.Color = Color3.new(0.666667, 0.333333, 1)
	part.Parent = segments
	part.Name = "seg1"
	part.CFrame = CFrame.new(-4.1, 2.1, -37.5)
	part_2.Anchored = true
	part_2.CanCollide = false
	part_2.Size = Vector3.new(1, 1, 2)
	part_2.BottomSurface = Enum.SurfaceType.Smooth
	part_2.BrickColor = BrickColor.new("Cool yellow")
	part_2.TopSurface = Enum.SurfaceType.Smooth
	part_2.Color = Color3.new(0.992157, 0.917647, 0.552941)
	part_2.Parent = segments
	part_2.CFrame = CFrame.new(-4.1, 2.1, -37.5)
	part_2.Name = "seg2"
	part_2.Transparency = 1

	local segments2 = Instance.new("Folder")
	local part = Instance.new("Part")
	local part_2 = Instance.new("Part")

	segments2.Name = "segments2"
	segments2.Parent = workspace
	part.Anchored = true
	part.CanCollide = false
	part.Size = Vector3.new(1, 1, 2)
	part.BottomSurface = Enum.SurfaceType.Smooth
	part.BrickColor = BrickColor.new("Alder")
	part.TopSurface = Enum.SurfaceType.Smooth
	part.Name = "seg1"
	part.Color = Color3.new(0.666667, 0.333333, 1)
	part.Parent = segments2
	part.CFrame = CFrame.new(-4.1, 2.1, -37.5)
	part_2.Anchored = true
	part_2.CanCollide = false
	part_2.Size = Vector3.new(1, 1, 2)
	part_2.BottomSurface = Enum.SurfaceType.Smooth
	part_2.BrickColor = BrickColor.new("Alder")
	part_2.TopSurface = Enum.SurfaceType.Smooth
	part_2.Color = Color3.new(0.666667, 0.333333, 1)
	part_2.Parent = segments2
	part_2.CFrame = CFrame.new(-4.1, 2.1, -37.5)
	part_2.Name = "seg2"
	part_2.Transparency = 1
	part.Transparency = 1



	local leg1 = Instance.new("Part")
	leg1.Anchored = true
	leg1.Size = Vector3.new(0.5, 0.2, 0.5)
	leg1.BottomSurface = Enum.SurfaceType.Smooth
	leg1.Color = Color3.new(0, 1, 0)
	leg1.BrickColor = BrickColor.new("New Yeller")
	leg1.TopSurface = Enum.SurfaceType.Smooth
	leg1.Name = "leg1"
	leg1.Parent = workspace
	leg1.CFrame = CFrame.new(-31.15, 0.1, 8.65)
	leg1.CanCollide = false
	leg1.Transparency = 1





	local leg1 =workspace.leg1:Clone()
	leg1.Parent = workspace

	local leg2= workspace.leg1:Clone()
	leg2.Parent = workspace

	local lp = game.Players.LocalPlayer
	local head = game.Players.LocalPlayer.Character.Head

	function coffset(x,y,z)
		return (head.CFrame * CFrame.new(x,y,z)).Position
	end




	mouse.KeyDown:connect(function(k)

		if k == "z" then

			leg1.Position = mouse.Hit.Position
		elseif k == "x" then


			leg2.Position = mouse.Hit.Position
		end

	end)




	spawn(function()
		--
		while true do


			if game.Players.LocalPlayer.Character.Humanoid.MoveDirection.Magnitude >0.1 then
				wait(1.6/lp.Character.Humanoid.WalkSpeed)

				local ray1 =Ray.new(coffset(3,-0,0),Vector3.new(0,-10,0) )
				local hit,pos = workspace:FindPartOnRayWithIgnoreList(ray1,{leg1,leg2,lp.Character})
				if pos then
					leg1.Position = pos
				end



				wait(1.6/lp.Character.Humanoid.WalkSpeed)
				local ray2 =Ray.new(coffset(-3,-0,0),Vector3.new(0,-10,0) )
				local hit,pos = workspace:FindPartOnRayWithIgnoreList(ray2,{leg1,leg2,lp.Character})
				if pos then
					leg2.Position = pos 
				end

			end
			game:GetService("RunService").RenderStepped:wait()
		end

	end)




	spawn(function()

		local mouse = game.Players.LocalPlayer:GetMouse()



		local len  = 2

		local offset = Vector3.new(1,-3,0)

		local offset = Vector3.new(1,-1,0)

		local segs = {}

		local posn =  game.Players.LocalPlayer.Character.Head.Position + Vector3.new(0,-2.5,0)






		for i,v in pairs(workspace.segments:GetChildren()) do



			table.insert(segs,v)


		end






		function vectorabsy(vec)
			local v = Vector3.new(vec.X,math.abs(vec.Y),vec.Z)
			return v
		end


		local count = #segs


		while true do

			for i = 1,5 do

				for i = 1,count do

					if i == 1 then

						local seg = segs[i]

						local pos1 =    segs[i].Position - (segs[i].CFrame.LookVector* (len/2) )  -- Calculating position that is on back of the part
						local pos2 =leg1.Position
						local vec = (pos2 - pos1).Unit 

						local cframe = CFrame.new(pos2 - (vec*(len/2) ),pos2) 

						seg.CFrame = cframe

					else
						local seg = segs[i]
						local pos1 =    segs[i].Position - (segs[i].CFrame.LookVector* (len/2) )
						local pos2 =    segs[i-1].Position - (segs[i-1].CFrame.LookVector* (len/2) )
						local vec = (pos2 - pos1).Unit
						local cframe = CFrame.new(pos2 - (vec*(len/2) ),pos2) 

						seg.CFrame = cframe
					end

				end 

				--Back


				for i = 1,count do

					local i = ( count - i ) + 1
					if i == count then

						local seg = segs[i]

						local pos1 =    segs[i].Position + (segs[i].CFrame.LookVector* (len/2) )  -- Calculating position that is on back of the part
						local pos2 =(game.Players.LocalPlayer.Character.Head.CFrame * CFrame.new(offset)).Position  
						local vec =(pos2 - pos1).Unit 
						if vec.Y > 0 then

							vec = Vector3.new(vec.X, vec.Y-0.01 ,vec.Z) 

						end

						local cframe = CFrame.new(pos2 - (vec*(len/2) ),pos2) * CFrame.Angles(0,math.rad(-180),0) 

						seg.CFrame =cframe

					else
						local seg = segs[i]
						local pos1 =    segs[i].Position + (segs[i].CFrame.LookVector* (len/2) )

						local pos2 =    segs[i+1].Position + (segs[i+1].CFrame.LookVector* (len/2) )
						local vec = (pos2 - pos1).Unit 

						local cframe = CFrame.new(pos2 - (vec*(len/2) ),pos2)  * CFrame.Angles(0,math.rad(-180),0)

						seg.CFrame = cframe
					end

				end 

			end
			game:GetService("RunService").Heartbeat:wait()
		end

	end)




	spawn(function()

		local mouse = game.Players.LocalPlayer:GetMouse()



		local len  = 2

		local offset = Vector3.new(-1,-1,0)

		local segs = {}

		local posn =  game.Players.LocalPlayer.Character.Head.Position + Vector3.new(0,-2.5,0)






		for i,v in pairs(workspace.segments2:GetChildren()) do



			table.insert(segs,v)


		end





		function vectorabsy(vec)
			local v = Vector3.new(vec.X,math.abs(vec.Y),vec.Z)
			return v
		end


		local count = #segs


		while true do

			for i = 1,5 do

				for i = 1,count do

					if i == 1 then

						local seg = segs[i]

						local pos1 =    segs[i].Position - (segs[i].CFrame.LookVector* (len/2) )  -- Calculating position that is on back of the part
						local pos2 =leg2.Position
						local vec = (pos2 - pos1).Unit 

						local cframe = CFrame.new(pos2 - (vec*(len/2) ),pos2) 

						seg.CFrame = cframe

					else
						local seg = segs[i]
						local pos1 =    segs[i].Position - (segs[i].CFrame.LookVector* (len/2) )
						local pos2 =    segs[i-1].Position - (segs[i-1].CFrame.LookVector* (len/2) )
						local vec = (pos2 - pos1).Unit
						local cframe = CFrame.new(pos2 - (vec*(len/2) ),pos2) 

						seg.CFrame = cframe
					end

				end 

				--Back


				for i = 1,count do

					local i = ( count - i ) + 1
					if i == count then

						local seg = segs[i]

						local pos1 =    segs[i].Position + (segs[i].CFrame.LookVector* (len/2) )  -- Calculating position that is on back of the part
						local pos2 =(game.Players.LocalPlayer.Character.Head.CFrame * CFrame.new(offset)).Position  
						local vec =(pos2 - pos1).Unit 
						if vec.Y > 0 then

							vec = Vector3.new(vec.X, vec.Y-0.01 ,vec.Z) 

						end

						local cframe = CFrame.new(pos2 - (vec*(len/2) ),pos2) * CFrame.Angles(0,math.rad(-180),0) 

						seg.CFrame =cframe

					else
						local seg = segs[i]
						local pos1 =    segs[i].Position + (segs[i].CFrame.LookVector* (len/2) )

						local pos2 =    segs[i+1].Position + (segs[i+1].CFrame.LookVector* (len/2) )
						local vec = (pos2 - pos1).Unit 

						local cframe = CFrame.new(pos2 - (vec*(len/2) ),pos2)  * CFrame.Angles(0,math.rad(-180),0)

						seg.CFrame = cframe
					end

				end 

			end
			game:GetService("RunService").Heartbeat:wait()
		end

	end)


	game.Players.LocalPlayer.Character.Torso["Right Shoulder"]:Destroy()
	game.Players.LocalPlayer.Character.Torso["Left Shoulder"]:Destroy()
	game.Players.LocalPlayer.Character.Torso["Right Hip"]:Destroy()
	game.Players.LocalPlayer.Character.Torso["Left Hip"]:Destroy()



	local bodyvelocity = Instance.new("BodyVelocity",game.Players.LocalPlayer.Character["Right Arm"])
	bodyvelocity.MaxForce = Vector3.new(9.9999999805064e+18, 9.999999869911e+14, 9.999999869911e+14)
	bodyvelocity.Velocity = Vector3.new(0, 200, 0)

	local bodyvelocity = Instance.new("BodyVelocity",game.Players.LocalPlayer.Character["Left Arm"])
	bodyvelocity.MaxForce = Vector3.new(9.9999999805064e+18, 9.999999869911e+14, 9.999999869911e+14)
	bodyvelocity.Velocity = Vector3.new(0, 200, 0)

	local bodyvelocity = Instance.new("BodyVelocity",game.Players.LocalPlayer.Character["Left Leg"])
	bodyvelocity.MaxForce = Vector3.new(9.9999999805064e+18, 9.999999869911e+14, 9.999999869911e+14)
	bodyvelocity.Velocity = Vector3.new(0, 200, 0)

	local bodyvelocity = Instance.new("BodyVelocity",game.Players.LocalPlayer.Character["Right Leg"])
	bodyvelocity.MaxForce = Vector3.new(9.9999999805064e+18, 9.999999869911e+14, 9.999999869911e+14)
	bodyvelocity.Velocity = Vector3.new(0, 200, 0)

	spawn(function()


		game.Players.LocalPlayer.Character.Humanoid.Died:connect(function()

			segments:Destroy()
			segments2:Destroy()

		end)

		game:GetService("RunService").Stepped:connect(function()
			game.Players.LocalPlayer.Character["Right Arm"].CanCollide = false
			game.Players.LocalPlayer.Character["Left Arm"].CanCollide = false

			game.Players.LocalPlayer.Character["Right Leg"].CanCollide = false
			game.Players.LocalPlayer.Character["Left Leg"].CanCollide = false

		end)

		repeat game:GetService("RunService").Heartbeat:wait()

			game.Players.LocalPlayer.Character["Right Arm"].CFrame =    segments.seg1 .CFrame * CFrame.Angles(math.rad(90),0,0 )
			game.Players.LocalPlayer.Character["Left Arm"].CFrame =     segments.seg2.CFrame * CFrame.Angles(math.rad(90),0,0 )

			game.Players.LocalPlayer.Character["Right Leg"].CFrame =   segments2.seg1.CFrame * CFrame.Angles(math.rad(90),0,0 )
			game.Players.LocalPlayer.Character["Left Leg"].CFrame =     segments2.seg2.CFrame * CFrame.Angles(math.rad(90),0,0 )

		until game.Players.LocalPlayer.Character.Humanoid.Health  < 1






	end)

	--thisisascript
end)

flip.Name = "flip"
flip.Parent = main
flip.BackgroundColor3 = Color3.fromRGB(85, 85, 85)
flip.Position = UDim2.new(0.125, 0, 0.924701929, 0)
flip.Size = UDim2.new(0, 134, 0, 32)
flip.Font = Enum.Font.SciFi
flip.Text = "Flip"
flip.TextColor3 = Color3.fromRGB(0, 0, 0)
flip.TextSize = 35.000
flip.MouseButton1Down:connect(function()
	--Press Z To Front Flip
	--Press X To Back Flip
	--Press C To Jump
	wait(5)

	--[[ Info ]]--

	local ver = "2.00"
	local scriptname = "feFlip"


	--[[ Keybinds ]]--

	local FrontflipKey = Enum.KeyCode.Z
	local BackflipKey = Enum.KeyCode.X
	local AirjumpKey = Enum.KeyCode.C


	--[[ Dependencies ]]--

	local ca = game:GetService("ContextActionService")
	local zeezy = game:GetService("Players").LocalPlayer
	local h = 0.0174533
	local antigrav


	--[[ Functions ]]--

	function zeezyFrontflip(act,inp,obj)
		if inp == Enum.UserInputState.Begin then
			zeezy.Character.Humanoid:ChangeState("Jumping")
			wait()
			zeezy.Character.Humanoid.Sit = true
			for i = 1,360 do 
				delay(i/720,function()
					zeezy.Character.Humanoid.Sit = true
					zeezy.Character.HumanoidRootPart.CFrame = zeezy.Character.HumanoidRootPart.CFrame * CFrame.Angles(-h,0,0)
				end)
			end
			wait(0.55)
			zeezy.Character.Humanoid.Sit = false
		end
	end

	function zeezyBackflip(act,inp,obj)
		if inp == Enum.UserInputState.Begin then
			zeezy.Character.Humanoid:ChangeState("Jumping")
			wait()
			zeezy.Character.Humanoid.Sit = true
			for i = 1,360 do
				delay(i/720,function()
					zeezy.Character.Humanoid.Sit = true
					zeezy.Character.HumanoidRootPart.CFrame = zeezy.Character.HumanoidRootPart.CFrame * CFrame.Angles(h,0,0)
				end)
			end
			wait(0.55)
			zeezy.Character.Humanoid.Sit = false
		end
	end

	function zeezyAirjump(act,inp,obj)
		if inp == Enum.UserInputState.Begin then
			zeezy.Character:FindFirstChildOfClass'Humanoid':ChangeState("Seated")
			wait()
			zeezy.Character:FindFirstChildOfClass'Humanoid':ChangeState("Jumping")  
		end
	end


	--[[ Binds ]]--

	ca:BindAction("zeezyFrontflip",zeezyFrontflip,false,FrontflipKey)
	ca:BindAction("zeezyBackflip",zeezyBackflip,false,BackflipKey)
	ca:BindAction("zeezyAirjump",zeezyAirjump,false,AirjumpKey)

	--[[ Load Message ]]--

	print(scriptname .. " " .. ver .. " loaded successfully")
	print("made by Zeezy#7203")

	local notifSound = Instance.new("Sound",workspace)
	notifSound.PlaybackSpeed = 1.5
	notifSound.Volume = 0.15
	notifSound.SoundId = "rbxassetid://170765130"
	notifSound.PlayOnRemove = true
	notifSound:Destroy()
	game.StarterGui:SetCore("SendNotification", {Title = "feFlip", Text = "feFlip loaded successfully!", Icon = "rbxassetid://505845268", Duration = 5, Button1 = "Okay"})
end)

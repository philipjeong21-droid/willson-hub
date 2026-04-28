local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()

local Window = Rayfield:CreateWindow({
   Name = "윌슨 허브(willson hub)",
   Icon = 0, -- Icon in Topbar. Can use Lucide Icons (string) or Roblox Image (number). 0 to use no icon (default).
   LoadingTitle = "Tip:m누르면 창을 열고 닫을수있음",
   LoadingSubtitle = "제작:윌슨",
   ShowText = "윌슨 허브", -- for mobile users to unhide Rayfield, change if you'd like
   Theme = "Ocean", -- Check https://docs.sirius.menu/rayfield/configuration/themes

   ToggleUIKeybind = "m", -- The keybind to toggle the UI visibility (string like "K" or Enum.KeyCode)

   DisableRayfieldPrompts = false,
   DisableBuildWarnings = false, -- Prevents Rayfield from emitting warnings when the script has a version mismatch with the interface.

   -- ScriptID = "sid_xxxxxxxxxxxx", -- Your Script ID from developer.sirius.menu — enables analytics, managed keys, and script hosting

   ConfigurationSaving = {
      Enabled = true,
      FolderName = nil, -- Create a custom folder for your hub/game
      FileName = "윌슨 허브"
   },

   Discord = {
      Enabled = true, -- Prompt the user to join your Discord server if their executor supports it
      Invite = "https://bstlar.com/4Ss/MadiumDISCORDE", -- The Discord invite code, do not include Discord.gg/. E.g. Discord.gg/ABCD would be ABCD
      RememberJoins = true -- Set this to false to make them join the Discord every time they load it up
   },

   KeySystem = true, -- Set this to true to use our key system
   KeySettings = {
      Title = "윌슨 허브",
      Subtitle = "키 시스템(use madium executor!)",
      Note = "키(여기 사이트로 가셈):https://pastebin.com/dStvpCXf", -- Use this to tell the user how to get a key
      FileName = "키(key)", -- It is recommended to use something unique, as other scripts using Rayfield may overwrite your key file
      SaveKey = false, -- The user's key will be saved, but if you change the key, they will be unable to use your script
      GrabKeyFromSite = false, -- If this is true, set Key below to the RAW site you would like Rayfield to get the key from
      Key = {"1972"} -- List of keys that the system will accept, can be RAW file links (pastebin, github, etc.) or simple strings ("hello", "key22")
   }
})

local mainTab = Window:CreateTab("메인 탭", nil) -- Title, Image
local MainSection = mainTab:CreateSection("쓰다가 밴 당하면 책임X")

local Button = mainTab:CreateButton({
   Name = "인피니티 야드(infinity yard)",
   Callback = function()
    loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-IY-InfiniteYield-137097"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = mainTab:CreateButton({
   Name = "esp,aim bot(에임봇은 150으로 설정하는걸 추천)",
   Callback = function()
    loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-VortexAim-205983"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = mainTab:CreateButton({
   Name = "npc esp,스피드 핵,플레이어 esp,투명,플라이,위치저장 저장했던 곳으로 텔포",
   Callback = function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Danster206/Ghost-Hub-Danster206-/refs/heads/main/Ghost%20Hub.lua"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = mainTab:CreateButton({
   Name = "안티 afk(누르면 아무것도 안나오는데 실행 됀거임)",
   Callback = function()
    loadstring(game:HttpGet("https://rawscripts.net/raw/Universal-Script-Anti-afk-249154"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = mainTab:CreateButton({
   Name = "킥훅 유니버셜(안돼는 게임있음)",
   Callback = function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/kiciahook/kiciahook/refs/heads/main/loader.luau"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = mainTab:CreateButton({
   Name = "아덜 허브(라이벌)",
   Callback = function()
    loadstring(game:HttpGet("https://api.luarmor.net/files/v3/loaders/2529a5f9dfddd5523ca4e22f21cceffa.lua"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = mainTab:CreateButton({
   Name = "테러(쓰면 사람들한테 순간이동해서 맵밖으로 튕겨냄 참고로 캐릭터끼리 닿으면 통과돼는 게임은 안됌)",
   Callback = function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/K1LAS1K/Ultimate-Fling-GUI/main/flingscript.lua"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = mainTab:CreateButton({
   Name = "포세이큰",
   Callback = function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/LolnotaKid/project/refs/heads/main/AutoBLOCKKKWAHV1"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = mainTab:CreateButton({
   Name = "앰버 알림",
   Callback = function()
    loadstring(game:HttpGet("https://rawscripts.net/raw/Amber-Alert-UPD-HORROR-script-140588"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = mainTab:CreateButton({
   Name = "무한 점프,esp,안티 스턴 키:062965",
   Callback = function()
    loadstring(game:HttpGet("https://pastefy.app/4I5ZQBWk/raw"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = mainTab:CreateButton({
   Name = "세일러 피스",
   Callback = function()
    loadstring(game:HttpGet("https://rawscripts.net/raw/Alter-Update-Sailor-Piece-BEST-SCRIPT-AUTOFARM-MOB-AUTO-USE-SKILL-AND-MUCH-MORE-134404"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = mainTab:CreateButton({
   Name = "더 미믹(잘안돼니까 쓰지 마셈 키 구하기도 어려움)",
   Callback = function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Yumiara/SSL-VulnX/refs/heads/main/APIs/M.lua"))();
   -- The function that takes place when the button is pressed
   end,
})

local Button = mainTab:CreateButton({
   Name = "바이트 바이 나이트(esp 버그 있음 esp키지 마셈)",
   Callback = function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Rx1m/CpsHub/refs/heads/main/bite%20by%20nights"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = mainTab:CreateButton({
   Name = "헌티드(다크 딥셉션)",
   Callback = function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/ScpGuest666/Random-Roblox-script/refs/heads/main/Roblox%20hunted%20V2%20script"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = mainTab:CreateButton({
   Name = "솔릭스 허브(라이벌)",
   Callback = function()
    loadstring(game:HttpGet("https://rawscripts.net/raw/RIVALS-OP-BEST-SCRIPT-UNDETECTED-SILENT-AIM-RAGEBOT-UNLOCK-ALL-ESP-43436"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = mainTab:CreateButton({
   Name = "데드레일 오토 팜(tp end 쓰지 마셈)",
   Callback = function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/Justine1244/Test/refs/heads/main/Grimhub",true))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = mainTab:CreateButton({
   Name = "좀비 어택 오토팜",
   Callback = function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/freshdotmp3/Fresh-s-Script/refs/heads/main/Zombie%20Attack.lua"))()
   -- The function that takes place when the button is pressed
   end,
})


local Button = mainTab:CreateButton({
   Name = "51 구역",
   Callback = function()
    loadstring(game:HttpGet("https://pastebin.com/raw/AbR0x0s7"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = mainTab:CreateButton({
   Name = "배드워즈 보이드 웨어",
   Callback = function()
    loadstring(game:HttpGet("https://raw.githubusercontent.com/VapeVoidware/vapevoidware/main/NewMainScript.lua",true))()
   -- The function that takes place when the button is pressed
   end,
})

local mainTab = Window:CreateTab("쓸만한 기능", nil) -- Title, Image
local MainSection = mainTab:CreateSection("esp,fly noclip more...")

local Button = mainTab:CreateButton({
   Name = "esp q:근처 플레이어 한테 텔포(고장남) g:npc esp b:상호작용 가능한 아이템 esp j:아이템 esp",
   Callback = function()
    local Players = game:GetService("Players")
local ReplicatedStorage = game:GetService("ReplicatedStorage")

local player = Players.LocalPlayer
local gui = Instance.new("ScreenGui")
gui.Name = "MobileHackUI"
gui.ResetOnSpawn = false
gui.Parent = player:WaitForChild("PlayerGui")

---------------------------------------------------
-- 버튼 생성 함수
---------------------------------------------------
local function createButton(text, pos)
	local btn = Instance.new("TextButton")
	btn.Size = UDim2.new(0, 120, 0, 50)
	btn.Position = pos
	btn.Text = text
	btn.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
	btn.TextColor3 = Color3.fromRGB(255, 255, 255)
	btn.Parent = gui
	return btn
end

---------------------------------------------------
-- 버튼들
---------------------------------------------------
local tpBtn = createButton("Q TELEPORT", UDim2.new(0, 10, 1, -220))
local npcBtn = createButton("NPC ESP", UDim2.new(0, 10, 1, -160))
local intBtn = createButton("INTERACT ESP", UDim2.new(0, 10, 1, -100))
local itemBtn = createButton("ITEM ESP", UDim2.new(0, 10, 1, -40))

---------------------------------------------------
-- 상태
---------------------------------------------------
local npcESP = false
local interactESP = false
local itemESP = false

local npcHighlights = {}
local interactHighlights = {}
local itemHighlights = {}

---------------------------------------------------
-- Remote (없어도 되지만 확장용)
---------------------------------------------------
local function getChar()
	return player.Character
end

---------------------------------------------------
-- 가장 가까운 플레이어
---------------------------------------------------
local function getNearestPlayer()
	local char = getChar()
	if not char then return end
	
	local hrp = char:FindFirstChild("HumanoidRootPart")
	if not hrp then return end
	
	local nearest, dist = nil, math.huge
	
	for _, p in pairs(Players:GetPlayers()) do
		if p ~= player and p.Character then
			local th = p.Character:FindFirstChild("HumanoidRootPart")
			if th then
				local d = (hrp.Position - th.Position).Magnitude
				if d < dist then
					dist = d
					nearest = p
				end
			end
		end
	end
	
	return nearest
end

---------------------------------------------------
-- NPC / Interact / Item 판별
---------------------------------------------------
local function isNPC(m)
	return m:IsA("Model")
		and m:FindFirstChild("Humanoid")
		and m:FindFirstChild("HumanoidRootPart")
		and not Players:GetPlayerFromCharacter(m)
end

local function isInteract(obj)
	return obj:IsA("BasePart") and obj:FindFirstChildOfClass("ProximityPrompt")
end

local function isItem(obj)
	return obj:IsA("Tool")
end

---------------------------------------------------
-- ESP 함수
---------------------------------------------------
local function toggleNPC()
	npcESP = not npcESP
	
	if npcESP then
		for _, obj in pairs(workspace:GetDescendants()) do
			if isNPC(obj) then
				local h = Instance.new("Highlight")
				h.FillColor = Color3.fromRGB(255, 0, 0)
				h.Adornee = obj
				h.Parent = obj
				npcHighlights[obj] = h
			end
		end
	else
		for _, h in pairs(npcHighlights) do h:Destroy() end
		npcHighlights = {}
	end
end

local function toggleInteract()
	interactESP = not interactESP
	
	if interactESP then
		for _, obj in pairs(workspace:GetDescendants()) do
			if isInteract(obj) then
				local h = Instance.new("Highlight")
				h.FillColor = Color3.fromRGB(0,255,0)
				h.Adornee = obj
				h.Parent = obj
				interactHighlights[obj] = h
			end
		end
	else
		for _, h in pairs(interactHighlights) do h:Destroy() end
		interactHighlights = {}
	end
end

local function toggleItem()
	itemESP = not itemESP
	
	if itemESP then
		for _, obj in pairs(workspace:GetDescendants()) do
			if isItem(obj) then
				local h = Instance.new("Highlight")
				h.FillColor = Color3.fromRGB(0,170,255)
				h.Adornee = obj
				h.Parent = obj
				itemHighlights[obj] = h
			end
		end
	else
		for _, h in pairs(itemHighlights) do h:Destroy() end
		itemHighlights = {}
	end
end

---------------------------------------------------
-- 텔포
---------------------------------------------------
local function teleport()
	local target = getNearestPlayer()
	if not target then return end
	
	local my = getChar()
	if not my then return end
	
	local myHRP = my:FindFirstChild("HumanoidRootPart")
	local th = target.Character and target.Character:FindFirstChild("HumanoidRootPart")
	
	if myHRP and th then
		myHRP.CFrame = th.CFrame * CFrame.new(3,0,0)
	end
end

---------------------------------------------------
-- 버튼 연결
---------------------------------------------------
tpBtn.MouseButton1Click:Connect(teleport)
npcBtn.MouseButton1Click:Connect(toggleNPC)
intBtn.MouseButton1Click:Connect(toggleInteract)
itemBtn.MouseButton1Click:Connect(toggleItem)
   -- The function that takes place when the button is pressed
   end,
})

local Button = mainTab:CreateButton({
   Name = "플라이,스피드핵,노클립,스핀 봇,점프 핵(y누르면 창을 닫았다 열수있음 죽으면 다시 켜야함)참고로 이거 내가만든거임 ㅋ",
   Callback = function()
    local p = game.Players.LocalPlayer
local run = game:GetService("RunService")
local uis = game:GetService("UserInputService")

---------------------------------------------------
-- 캐릭터 안전 참조
---------------------------------------------------
local function getChar()
	local c = p.Character or p.CharacterAdded:Wait()
	return c, c:WaitForChild("Humanoid"), c:WaitForChild("HumanoidRootPart")
end

local char, hum, hrp = getChar()

p.CharacterAdded:Connect(function()
	char, hum, hrp = getChar()
end)

---------------------------------------------------
-- UI
---------------------------------------------------
local gui = Instance.new("ScreenGui", p:WaitForChild("PlayerGui"))

local frame = Instance.new("Frame", gui)
frame.Size = UDim2.new(0,250,0,300)
frame.Position = UDim2.new(0,20,0.3,0)
frame.BackgroundColor3 = Color3.fromRGB(30,30,30)

local function box(txt, y)
	local b = Instance.new("TextBox", frame)
	b.Size = UDim2.new(1,0,0,30)
	b.Position = UDim2.new(0,0,0,y)
	b.PlaceholderText = txt
	return b
end

local function btn(txt, y)
	local b = Instance.new("TextButton", frame)
	b.Size = UDim2.new(1,0,0,30)
	b.Position = UDim2.new(0,0,0,y)
	b.Text = txt
	return b
end

local speedBox = box("Speed",0)
local jumpBox = box("Jump",35)
local flySpeedBox = box("Fly Speed",70)
local spinBox = box("Spin Speed",105)

local flyBtn = btn("FLY OFF",140)
local noclipBtn = btn("NOCLIP OFF",175)
local spinBtn = btn("SPIN OFF",210)

---------------------------------------------------
-- 속도 / 점프
---------------------------------------------------
speedBox.FocusLost:Connect(function()
	local n = tonumber(speedBox.Text)
	if n and hum then hum.WalkSpeed = n end
end)

jumpBox.FocusLost:Connect(function()
	local n = tonumber(jumpBox.Text)
	if n and hum then
		hum.UseJumpPower = true
		hum.JumpPower = n
	end
end)

---------------------------------------------------
-- FLY
---------------------------------------------------
local flying = false
local flyVel

flyBtn.MouseButton1Click:Connect(function()
	flying = not flying
	flyBtn.Text = flying and "FLY ON" or "FLY OFF"

	if flying then
		flyVel = Instance.new("BodyVelocity")
		flyVel.MaxForce = Vector3.new(1,1,1)*100000
		flyVel.Parent = hrp
	else
		if flyVel then flyVel:Destroy() end
	end
end)

run.RenderStepped:Connect(function()
	if flying and flyVel and hrp then
		local cam = workspace.CurrentCamera
		local dir = Vector3.zero

		if uis:IsKeyDown(Enum.KeyCode.W) then dir += cam.CFrame.LookVector end
		if uis:IsKeyDown(Enum.KeyCode.S) then dir -= cam.CFrame.LookVector end
		if uis:IsKeyDown(Enum.KeyCode.A) then dir -= cam.CFrame.RightVector end
		if uis:IsKeyDown(Enum.KeyCode.D) then dir += cam.CFrame.RightVector end

		local speed = tonumber(flySpeedBox.Text) or 60

		if dir.Magnitude > 0 then
			flyVel.Velocity = dir.Unit * speed
		else
			flyVel.Velocity = Vector3.zero
		end
	end
end)

---------------------------------------------------
-- NOCLIP
---------------------------------------------------
local noclip = false

noclipBtn.MouseButton1Click:Connect(function()
	noclip = not noclip
	noclipBtn.Text = noclip and "NOCLIP ON" or "NOCLIP OFF"
end)

run.Stepped:Connect(function()
	if noclip and char then
		for _, v in pairs(char:GetDescendants()) do
			if v:IsA("BasePart") then
				v.CanCollide = false
			end
		end
	end
end)

---------------------------------------------------
-- SPIN
---------------------------------------------------
local spinning = false
local spinConn

spinBtn.MouseButton1Click:Connect(function()
	spinning = not spinning
	spinBtn.Text = spinning and "SPIN ON" or "SPIN OFF"

	if spinning then
		spinConn = run.RenderStepped:Connect(function()
			local s = tonumber(spinBox.Text) or 5
			if hrp then
				hrp.CFrame = hrp.CFrame * CFrame.Angles(0, math.rad(s), 0)
			end
		end)
	else
		if spinConn then spinConn:Disconnect() end
	end
end)

---------------------------------------------------
-- 🧲 드래그 이동
---------------------------------------------------
local dragging = false
local dragStart, startPos

frame.InputBegan:Connect(function(input)
	if input.UserInputType == Enum.UserInputType.MouseButton1 then
		dragging = true
		dragStart = input.Position
		startPos = frame.Position

		input.Changed:Connect(function()
			if input.UserInputState == Enum.UserInputState.End then
				dragging = false
			end
		end)
	end
end)

frame.InputChanged:Connect(function(input)
	if input.UserInputType == Enum.UserInputType.MouseMovement and dragging then
		local delta = input.Position - dragStart
		frame.Position = UDim2.new(
			startPos.X.Scale,
			startPos.X.Offset + delta.X,
			startPos.Y.Scale,
			startPos.Y.Offset + delta.Y
		)
	end
end)

---------------------------------------------------
-- ⌨️ Y 토글
---------------------------------------------------
local open = true

uis.InputBegan:Connect(function(input, gp)
	if gp then return end
	if input.KeyCode == Enum.KeyCode.Y then
		open = not open
		frame.Visible = open
	end
end)
   -- The function that takes place when the button is pressed
   end,
})

local Button = mainTab:CreateButton({
   Name = "개사기 유니버셜(로딩하는데 좀 오래 걸림)",
   Callback = function()
    loadstring(game:HttpGet("https://api.luarmor.net/files/v4/loaders/c146e7169df99db2afa5052b177dd747.lua"))()
   -- The function that takes place when the button is pressed
   end,
})

local Button = mainTab:CreateButton({
   Name = "내가 만든 쉐이더(u키를 누르면 껐다 킬수 있음)",
   Callback = function()
    local Lighting = game:GetService("Lighting")
local uis = game:GetService("UserInputService")

---------------------------------------------------
-- 상태
---------------------------------------------------
local enabled = false

---------------------------------------------------
-- 효과 미리 생성 (핵심)
---------------------------------------------------
local color = Instance.new("ColorCorrectionEffect")
local bloom = Instance.new("BloomEffect")
local atmosphere = Instance.new("Atmosphere")
local sun = Instance.new("SunRaysEffect")

---------------------------------------------------
-- ON
---------------------------------------------------
local function enable()
	color.Parent = Lighting
	bloom.Parent = Lighting
	atmosphere.Parent = Lighting
	sun.Parent = Lighting

	-- 🌅 밝은 노을
	Lighting.ClockTime = 17.8
	Lighting.Brightness = 2.8
	Lighting.ExposureCompensation = 0.2

	-- 🎨 색감
	color.Contrast = 0.15
	color.Saturation = 0.3
	color.Brightness = 0.1
	color.TintColor = Color3.fromRGB(255, 215, 180)

	-- ✨ 블룸
	bloom.Intensity = 0.8
	bloom.Size = 22
	bloom.Threshold = 1

	-- 🌫️ 공기
	atmosphere.Density = 0.18
	atmosphere.Haze = 0.9
	atmosphere.Glare = 0.2
	atmosphere.Color = Color3.fromRGB(255, 190, 140)
	atmosphere.Decay = Color3.fromRGB(200, 140, 100)

	-- 🌞 햇빛
	sun.Intensity = 0.3
	sun.Spread = 1
end

---------------------------------------------------
-- OFF
---------------------------------------------------
local function disable()
	color.Parent = nil
	bloom.Parent = nil
	atmosphere.Parent = nil
	sun.Parent = nil

	Lighting.ClockTime = 14
	Lighting.Brightness = 2
	Lighting.ExposureCompensation = 0
end

---------------------------------------------------
-- U 키 토글
---------------------------------------------------
uis.InputBegan:Connect(function(input, gp)
	if gp then return end

	if input.KeyCode == Enum.KeyCode.U then
		enabled = not enabled

		if enabled then
			enable()
		else
			disable()
		end
	end
end)
   -- The function that takes place when the button is pressed
   end,
})

local Button = mainTab:CreateButton({
   Name = "근처 플레이어 한테 텔포하는 스크(q누르면 텔포됨)",
   Callback = function()
    local UserInputService = game:GetService("UserInputService")
local Players = game:GetService("Players")

local player = Players.LocalPlayer

local function getNearestPlayer()
	local character = player.Character
	if not character then return nil end
	
	local hrp = character:FindFirstChild("HumanoidRootPart")
	if not hrp then return nil end
	
	local nearestPlayer = nil
	local shortestDistance = math.huge
	
	for _, otherPlayer in pairs(Players:GetPlayers()) do
		if otherPlayer ~= player and otherPlayer.Character then
			
			local otherHRP = otherPlayer.Character:FindFirstChild("HumanoidRootPart")
			
			if otherHRP then
				local distance = (hrp.Position - otherHRP.Position).Magnitude
				
				if distance < shortestDistance then
					shortestDistance = distance
					nearestPlayer = otherPlayer
				end
			end
		end
	end
	
	return nearestPlayer
end

UserInputService.InputBegan:Connect(function(input, gameProcessed)
	if gameProcessed then return end
	
	if input.KeyCode == Enum.KeyCode.Q then
		
		local target = getNearestPlayer()
		
		if target and target.Character then
			local myChar = player.Character
			local targetHRP = target.Character:FindFirstChild("HumanoidRootPart")
			
			if myChar and targetHRP then
				local myHRP = myChar:FindFirstChild("HumanoidRootPart")
				
				if myHRP then
					-- 🔥 순간이동 (조금 옆으로 이동해서 겹침 방지)
					myHRP.CFrame = targetHRP.CFrame * CFrame.new(3, 0, 0)
					
					print(target.Name .. "에게 순간이동!")
				end
			end
		else
			print("근처 플레이어 없음")
		end
	end
end)
   -- The function that takes place when the button is pressed
   end,
})

local Button = mainTab:CreateButton({
   Name = "내가 직접 만든 esp(h누르면 보이고 y누르면 꺼짐 밴 당할수도 있음)",
   Callback = function()
    local UIS = game:GetService("UserInputService")
local Players = game:GetService("Players")

local player = Players.LocalPlayer
local playerGui = player:WaitForChild("PlayerGui")

-- GUI 생성
local screenGui = Instance.new("ScreenGui")
screenGui.Parent = playerGui

local frame = Instance.new("Frame")
frame.Size = UDim2.new(0, 150, 0, 100)
frame.Position = UDim2.new(1, -160, 0, 10) -- 오른쪽 위
frame.BackgroundColor3 = Color3.fromRGB(30,30,30)
frame.Parent = screenGui

-- 상태 변수
local npcMode = false
local playerMode = false

-- Highlight 함수
local function highlightCharacter(char, color)
   if char:FindFirstChild("Highlight") then return end
   
   local h = Instance.new("Highlight")
   h.FillColor = color
   h.OutlineColor = color
   h.Parent = char
end

local function clearHighlights()
   for _, v in pairs(workspace:GetDescendants()) do
      if v:IsA("Highlight") then
         v:Destroy()
      end
   end
end

-- NPC 표시 (Workspace 안에 NPC 모델 있다고 가정)
local function showNPCs()
   clearHighlights()
   
   for _, v in pairs(workspace:GetDescendants()) do
      if v:IsA("Model") 
      and v:FindFirstChild("HumanoidRootPart") 
      and not game.Players:GetPlayerFromCharacter(v) then
         
         highlightCharacter(v, Color3.fromRGB(255, 0, 0))
      end
   end
end

-- 플레이어 표시
local function showPlayers()
   clearHighlights()
   
   for _, plr in pairs(Players:GetPlayers()) do
      if plr ~= player and plr.Character then
         highlightCharacter(plr.Character, Color3.fromRGB(0, 255, 0))
      end
   end
end

-- 키 입력
UIS.InputBegan:Connect(function(input, gp)
   if gp then return end
   
   if input.KeyCode == Enum.KeyCode.Y then
      npcMode = true
      playerMode = false
      showNPCs()
   end
   
   if input.KeyCode == Enum.KeyCode.H then
      playerMode = true
      npcMode = false
      showPlayers()
   end
end)
   -- The function that takes place when the button is pressed
   end,
})

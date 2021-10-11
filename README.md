NANE = "MASTER HUB       |Blox Fruit Ss 0 . 0 . 1  V.1"

if game.CoreGui:FindFirstChild(NANE) then
    game.CoreGui:FindFirstChild(NANE):Destroy()
end
local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/zazxa2133/Kuy/main/README.md"))() --someone reuploaded it so I put it in place of the original back up so guy can get free credit.
local venyx = library.new(NANE, 5013109572)








local themes = {
Background = Color3.fromRGB(24, 24, 24),
Glow = Color3.fromRGB(0, 0, 0),
Accent = Color3.fromRGB(10, 10, 10),
LightContrast = Color3.fromRGB(20, 20, 20),
DarkContrast = Color3.fromRGB(14, 14, 14),  
TextColor = Color3.fromRGB(255, 255, 255)
}







OldWorld = false
newworld = false
local placeId = game.PlaceId
if placeId == 2753915549 then
    OldWorld = true
elseif placeId == 4442272183 then
    newworld = true
end

    function EquipWeapon(ToolSe)
        if game.Players.LocalPlayer.Backpack:FindFirstChild(ToolSe) then
           local tool = game.Players.LocalPlayer.Backpack:FindFirstChild(ToolSe)
           wait(.4)
           game.Players.LocalPlayer.Character.Humanoid:EquipTool(tool)
        end
     end

-- first page
local page = venyx:addPage("Main", 7040391851)
local section1 = page:addSection("Auto Farm")
local section2 = page:addSection("Weapon")
local section3 = page:addSection("Auto Ice wall")


-- sword : 7251993295
-- cart : 7294901968
-- person : 7252023075
-- devil : 7044284832
-- misc : 7044233235
-- teleport : 7044226690
-- stats : 7040410130
-- main :  7040391851
-- setting : 7040347038



section1:addToggle("AutoFarm Level", true, function(a)
_G.AUTOFARM = a

while _G.AUTOFARM do wait()
  pcall(function()
      
      
local LEVEL = game:GetService("Players").LocalPlayer.Data.Level.Value

if LEVEL == 1 or LEVEL <= 9 then
    MON = "Bandit [Lv. 5]"
    QUESTNAME = "BanditQuest1"
    QUESTNUM = 1
    QUESTPOS = CFrame.new(1060.7056884766, 16.455068588257, 1547.9978027344)
    PUKPOS = CFrame.new(1097.2778320313, 66.485931396484, 1614.8713378906)
    REWARD = "Reward:\n$350\n250 Exp."
elseif LEVEL == 10 or LEVEL <= 14 then
    MON = "Monkey [Lv. 14]"
    QUESTNAME = "JungleQuest"
    QUESTNUM = 1
    QUESTPOS = CFrame.new(-1599.82532, 36.8521347, 153.959076, 0.00275422214, 5.1952032e-08, -0.999996185, 1.33985356e-08, 1, 5.1989133e-08, 0.999996185, -1.35416744e-08, 0.00275422214)
    PUKPOS = CFrame.new(-1610.2681884766, 20.852096557617, 144.16523742676)
    REWARD = "Reward:\n$800\n1,800 Exp."
elseif LEVEL == 15 or LEVEL <= 29 then
    MON = "Gorilla [Lv. 20]"
    QUESTNAME = "JungleQuest"
    QUESTNUM = 2
    QUESTPOS = CFrame.new(-1599.82532, 36.8521347, 153.959076, 0.00275422214, 5.1952032e-08, -0.999996185, 1.33985356e-08, 1, 5.1989133e-08, 0.999996185, -1.35416744e-08, 0.00275422214)
    PUKPOS = CFrame.new(-1278.3718261719, 18.62145614624, -423.06091308594)
    REWARD = "Reward:\n$1,200\n3,500 Exp."
elseif LEVEL == 30 or LEVEL <= 39 then
    MON = "Pirate [Lv. 35]"
    QUESTNAME = "BuggyQuest1"
    QUESTNUM = 1
    QUESTPOS = CFrame.new(-1141.2176513672, 5.2773809432983, 3830.3137207031)
    PUKPOS = CFrame.new(-1186.5637207031, 4.2011165618896, 3906.8994140625)
    REWARD = "Reward:\n$3,000\n10,000 Exp."
elseif LEVEL == 40 or LEVEL <= 59 then
    MON = "Brute [Lv. 45]"
    QUESTNAME = "BuggyQuest1"
    QUESTNUM = 2
    QUESTPOS = CFrame.new(-1141.2176513672, 5.2773809432983, 3830.3137207031)
    PUKPOS = CFrame.new(-1146.49646, 96.0936813, 4312.1333, -0.978175163, -1.53222057e-08, 0.207781896, -3.33316912e-08, 1, -8.31738873e-08, -0.207781896, -8.82843523e-08, -0.978175163)
    REWARD = "Reward:\n$3,500\n18,000 Exp."
elseif LEVEL == 60 or LEVEL <= 74 then
    MON = "Desert Bandit [Lv. 60]"
    QUESTNAME = "DesertQuest"
    QUESTNUM = 1
    QUESTPOS = CFrame.new(895.28356933594, 6.604202747345, 4390.9951171875)
    PUKPOS = CFrame.new(931.29064941406, 4.435818195343, 4480.7954101563)
    REWARD = "Reward:\n$4,000\n35,000 Exp."
elseif LEVEL == 75 or LEVEL <= 89 then
    MON = "Desert Officer [Lv. 70]"
    QUESTNAME = "DesertQuest"
    QUESTNUM = 2
    QUESTPOS = CFrame.new(897.031128, 6.43846416, 4388.97168, -0.804044724, 3.68233266e-08, 0.594568789, 6.97835176e-08, 1, 3.24365246e-08, -0.594568789, 6.75715199e-08, -0.804044724)
    PUKPOS = CFrame.new(1580.03198, 4.61375761, 4366.86426, 0.135744005, -6.44280718e-08, -0.990743816, 4.35738308e-08, 1, -5.90598574e-08, 0.990743816, -3.51534837e-08, 0.135744005)
    REWARD = "Reward:\n$4,500\n50,000 Exp."
elseif LEVEL == 90 or LEVEL <= 99 then
    MON = "Snow Bandit [Lv. 90]"
    QUESTNAME = "SnowQuest"
    QUESTNUM = 1
    QUESTPOS = CFrame.new(1384.14001, 87.272789, -1297.06482, 0.348555952, -2.53947841e-09, -0.937287986, 1.49860568e-08, 1, 2.86358204e-09, 0.937287986, -1.50443711e-08, 0.348555952)
    PUKPOS = CFrame.new(1370.24316, 102.403511, -1411.52905, 0.980274439, -1.12995728e-08, 0.197641045, -9.57343449e-09, 1, 1.04655214e-07, -0.197641045, -1.04482936e-07, 0.980274439)
    REWARD = "Reward:\n$5,000\n70,000 Exp."
elseif LEVEL == 100 or LEVEL <= 119 then
    MON = "Snowman [Lv. 100]"
    QUESTNAME = "SnowQuest"
    QUESTNUM = 2
    QUESTPOS = CFrame.new(1384.14001, 87.272789, -1297.06482, 0.348555952, -2.53947841e-09, -0.937287986, 1.49860568e-08, 1, 2.86358204e-09, 0.937287986, -1.50443711e-08, 0.348555952)
    PUKPOS = CFrame.new(1370.24316, 102.403511, -1411.52905, 0.980274439, -1.12995728e-08, 0.197641045, -9.57343449e-09, 1, 1.04655214e-07, -0.197641045, -1.04482936e-07, 0.980274439)
    REWARD = "Reward:\n$5,500\n120,000 Exp."
elseif LEVEL == 120 or LEVEL <= 149 then
    MON = "Chief Petty Officer [Lv. 120]"
    QUESTNAME = "MarineQuest2"
    QUESTNUM = 1
    QUESTPOS = CFrame.new(-5035.0835, 28.6520386, 4325.29443, 0.0243340395, -7.08064647e-08, 0.999703884, -6.36926814e-08, 1, 7.23777944e-08, -0.999703884, -6.54350671e-08, 0.0243340395)
    PUKPOS = CFrame.new(-4882.8623, 22.6520386, 4255.53516, 0.273695946, -5.40380647e-08, -0.96181643, 4.37720793e-08, 1, -4.37274998e-08, 0.96181643, -3.01326679e-08, 0.273695946)
    REWARD = "Reward:\n$6,000\n180,000 Exp."
elseif LEVEL == 150 or LEVEL <= 174 then
    MON = "Sky Bandit [Lv. 150]"
    QUESTNAME = "SkyQuest"
    QUESTNUM = 1
    QUESTPOS = CFrame.new(-4841.83447, 717.669617, -2623.96436, -0.875942111, 5.59710216e-08, -0.482416272, 3.04023082e-08, 1, 6.08195947e-08, 0.482416272, 3.86078725e-08, -0.875942111)
    PUKPOS = CFrame.new(-4970.74219, 294.544342, -2890.11353, -0.994874597, -8.61311236e-08, -0.101116329, -9.10836206e-08, 1, 4.43614923e-08, 0.101116329, 5.33441664e-08, -0.994874597)
    REWARD = "Reward:\n$7,000\n250,000 Exp."
elseif LEVEL == 175 or LEVEL <= 224 then
    MON = "Dark Master [Lv. 175]"
    QUESTNAME = "SkyQuest"
    QUESTNUM = 2
    QUESTPOS = CFrame.new(-4841.83447, 717.669617, -2623.96436, -0.875942111, 5.59710216e-08, -0.482416272, 3.04023082e-08, 1, 6.08195947e-08, 0.482416272, 3.86078725e-08, -0.875942111)
    PUKPOS = CFrame.new(-5220.58594, 430.693298, -2278.17456, -0.925375521, 1.12086873e-08, 0.379051805, -1.05115507e-08, 1, -5.52320891e-08, -0.379051805, -5.50948407e-08, -0.925375521)
    REWARD = "Reward:\n$7,500\n350,000 Exp."
elseif LEVEL == 255 or LEVEL <= 224 then
    MON = "Toga Warrior [Lv. 225]"
    QUESTNAME = "ColosseumQuest"
    QUESTNUM = 1
    QUESTPOS = CFrame.new(-1576.11743, 7.38933945, -2983.30762, 0.576966345, 1.22114863e-09, 0.816767931, -3.58496594e-10, 1, -1.24185606e-09, -0.816767931, 4.2370063e-10, 0.576966345)
    PUKPOS = CFrame.new(-1779.97583, 44.6077499, -2736.35474, 0.984437346, 4.10396339e-08, 0.175734788, -3.62286876e-08, 1, -3.05844168e-08, -0.175734788, 2.3741821e-08, 0.984437346)
    REWARD = "Reward:\n$7,000\n700,000 Exp."
elseif LEVEL == 255 or LEVEL <= 224 then
    MON = "Gladiator [Lv. 275]"
    QUESTNAME = "ColosseumQuest"
    QUESTNUM = 2
    QUESTPOS = CFrame.new(-1576.11743, 7.38933945, -2983.30762, 0.576966345, 1.22114863e-09, 0.816767931, -3.58496594e-10, 1, -1.24185606e-09, -0.816767931, 4.2370063e-10, 0.576966345)
    PUKPOS = CFrame.new(-1779.97583, 44.6077499, -2736.35474, 0.984437346, 4.10396339e-08, 0.175734788, -3.62286876e-08, 1, -3.05844168e-08, -0.175734788, 2.3741821e-08, 0.984437346)
    REWARD = "Reward:\n$7,000\n1,000,000 Exp."
end





if game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Container.QuestReward.Title.Text ~= REWARD then
local args = {
    [1] = "AbandonQuest"
}

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
end
    

if game:GetService("Players").LocalPlayer.PlayerGui.Main.Quest.Visible ~= true then
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = QUESTPOS
        wait(.5)
local args = {
    [1] = "StartQuest",
    [2] = QUESTNAME,
    [3] = QUESTNUM
}

game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
wait(.5)
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = PUKPOS
end


for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
    if v.Name == MON  then
        if v.Humanoid.Health <= 0 then
            game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = PUKPOS
            else
        game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame * CFrame.new(0,13,0)
        v.HumanoidRootPart.Size = Vector3.new(40,40,40)
        v.HumanoidRootPart.Transparency = 0.9
        v.HumanoidRootPart.CanCollide = false
        v.Humanoid.WalkSpeed = 0
        v.Humanoid.JumpPower = 0
        v.Humanoid:ChangeState(11)
        require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework).activeController.hitboxMagnitude = 60
        require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework.CameraShaker).CameraShakeInstance.CameraShakeState = {FadingIn = 3,FadingOut =  2,Sustained = 0,Inactive = 1} 
        require(game:GetService("Players").LocalPlayer.PlayerScripts.CombatFramework).activeController.timeToNextAttack = 0
        game:GetService'VirtualUser':CaptureController()
        game:GetService'VirtualUser':Button1Down(Vector2.new(1280, 672))
        game.Players.LocalPlayer.Character.Humanoid:ChangeState(11)
        end
        end
end


for i,v in pairs(game:GetService("Workspace").Enemies:GetChildren()) do

        for ii,vv in pairs(game:GetService("Workspace").Enemies:GetChildren()) do
        if v.Name == MON then
            if vv.Name == MON then
        vv.HumanoidRootPart.CFrame = v.HumanoidRootPart.CFrame
        sethiddenproperty(game.Players.LocalPlayer, "SimulationRadius", math.huge)
        vv.HumanoidRootPart.CanCollide = false
        end
        end
        end


-- open haki
 if game.Players.LocalPlayer.Character:FindFirstChild("HasBuso") then
    else
    local args = {
        [1] = "Buso"
    }
    game:GetService("ReplicatedStorage").Remotes.CommF_:InvokeServer(unpack(args))
    end
end 
 end)
end
end)




local weapon = {}

for i,v in pairs(game.Players.LocalPlayer.Backpack:GetChildren()) do
   if v:IsA("Tool") then
       table.insert(weapon,v.Name)
    end
end

for i,v in pairs(game.Players.LocalPlayer.Character:GetChildren()) do
   if v:IsA("Tool") then
       table.insert(weapon,v.Name)
    end
end

local WeaponSelect = nil

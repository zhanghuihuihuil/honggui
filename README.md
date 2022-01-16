function Tlprt(x,y,z)
    game.Players.LocalPlayer.Character.Humanoid.Sit = true
    game.Players.LocalPlayer.Character.Humanoid.Jump = true

    wait(0.05)
     game.Players.LocalPlayer.Character.Humanoid.Sit = true
        game.Players.LocalPlayer.Character.Humanoid.Jump = true
       local tweenService = game:GetService("TweenService")
       local tweeningInformation = TweenInfo.new(
   
3, -- Length
Enum.EasingStyle.Linear, -- Easing style of the TweenInfo
Enum.EasingDirection.Out, -- Easing direction of the TweenInfo
0, -- Number of times the tween will repeat   
false, -- Should the tween repeat?
0 -- Delay between each tween  
)
local partProperties = {
    CFrame = CFrame.new(x,y,z)
}
        local Tween = tweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart,tweeningInformation,partProperties)
        Tween:Play()
            
            
            
            
    
end
-- Gui to Lua
-- Version: 3.2

-- Instances: Hdog :)

local ScreenGui = Instance.new("ScreenGui")
local MainFrame = Instance.new("Frame")
local Version = Instance.new("TextLabel")
local Spacer = Instance.new("Frame")
local MenuTab = Instance.new("ImageButton")
local MenuTabFrame = Instance.new("Frame")
local MenuTabTitle = Instance.new("TextLabel")
local PlayerMenu = Instance.new("TextButton")
local PlayerMenuFrame = Instance.new("Frame")
local Fly = Instance.new("TextButton")
local NoClip = Instance.new("TextButton")
local BTools = Instance.new("TextButton")
local ClickTP = Instance.new("TextButton")
local WalkSpeed = Instance.new("TextButton")
local JumpPower = Instance.new("TextButton")
local InfiniteJump = Instance.new("TextButton")
local Reset = Instance.new("TextButton")
local TextLabel = Instance.new("TextLabel")
local GuiMenu = Instance.new("TextButton")
local GuiMenuFrame = Instance.new("Frame")
local AutoBuy = Instance.new("TextButton")
local Dupe = Instance.new("TextButton")
local RepileGui = Instance.new("TextButton")
local EvanPlayer = Instance.new("TextButton")
local LumberGui = Instance.new("TextButton")
local LumberX = Instance.new("TextButton")
local BloodGui = Instance.new("TextButton")
local EmberGui = Instance.new("TextButton")
local TeleportMenu = Instance.new("TextButton")
local TeleportMenuFrame = Instance.new("Frame")
local WoodRUs = Instance.new("TextButton")
local SpawnPoint = Instance.new("TextButton")
local LandStore = Instance.new("TextButton")
local Cave = Instance.new("TextButton")
local LinksLogic = Instance.new("TextButton")
local Volcano = Instance.new("TextButton")
local Swamp = Instance.new("TextButton")
local PalmIsland = Instance.new("TextButton")
local FancyFurnishings = Instance.new("TextButton")
local BoxedCars = Instance.new("TextButton")
local BobsShack = Instance.new("TextButton")
local ShrineOfSight = Instance.new("TextButton")
local SkiLodge = Instance.new("TextButton")
local StrangeMan = Instance.new("TextButton")
local EndTimes = Instance.new("TextButton")
local Dock = Instance.new("TextButton")
local Bridge = Instance.new("TextButton")
local FineArtsShop = Instance.new("TextButton")
local MiscandplotMenu = Instance.new("TextButton")
local MiscMenuFrame = Instance.new("Frame")
local MiscMenuTitle = Instance.new("TextLabel")
local PlotMenubox = Instance.new("Frame")
local AntiAFK = Instance.new("TextButton")
local Blueprints = Instance.new("TextButton")
local FreeLand = Instance.new("TextButton")
local MaxLand = Instance.new("TextButton")
local DupeAxeTitle = Instance.new("TextLabel")
local DupeAxeBox = Instance.new("Frame")
local TextButton = Instance.new("TextButton")
local PlotMenuTitle = Instance.new("TextLabel")
local SafariBridge = Instance.new("TextButton")
local GoldBridge = Instance.new("TextButton")
local YellowBridge = Instance.new("TextButton")
local PalmBridge = Instance.new("TextButton")
local AlwaysDay = Instance.new("TextButton")
local LeakedItems = Instance.new("TextButton")
local NoFog = Instance.new("TextButton")
local CloseMenuTab = Instance.new("ImageButton")
local SettingsTab = Instance.new("ImageButton")
local SettingsTabFrame = Instance.new("Frame")
local SettingstabTitle = Instance.new("TextLabel")
local ColorsMenu = Instance.new("TextButton")
local ColorMenuFrame = Instance.new("Frame")
local ColorsMenuTitle = Instance.new("TextLabel")
local G = Instance.new("TextBox")
local Set = Instance.new("TextButton")
local R = Instance.new("TextBox")
local B = Instance.new("TextBox")
local Creditsforhelp = Instance.new("TextLabel")
local MoreMenu = Instance.new("TextButton")
local MoreMenuFrame = Instance.new("Frame")
local MakeMainFrameMoveable = Instance.new("TextButton")
local MakeMainFrameNONMoveable = Instance.new("TextButton")
local Destory = Instance.new("TextButton")
local Credits = Instance.new("TextLabel")
local CloseSettingsTab = Instance.new("ImageButton")
local MainFrameBackground = Instance.new("ImageLabel")
local CloseMainFrame = Instance.new("TextButton")
local AfterMinimizeOpenMainFrame = Instance.new("TextButton")
local WelcomeScr

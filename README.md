-- carregar biblioteca
local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()

-- aviso ao executar


local Window = OrionLib:MakeWindow({Name = "(⁠◠⁠‿⁠◕⁠)CARL HUB SCRIPTING (⁠•⁠‿⁠•⁠)", HidePremium = false, SaveConfig = true, ConfigFolder = "Carl hub (Kauane hub♥️)"})

local Tab = Window:MakeTab({
	Name = "Inicio",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false

local Section = Tab:AddSection({
	Name = "Section"	

-- notificação
OrionLib:MakeNotification({
	Name = "Carl hub executed",
	Content = "Kauane hub executed",
	Image = "rbxassetid://4483345998",
	Time = 5 })

-- Botão
Tab:AddButton({
	Name = "Carl hub old",
	Callback = function()
      		print("loadstring(game:HttpGet"https://raw.githubusercontent.com/carlosdaniel987/Carl-hub-novo/refs/heads/main/README.md") end })
Tab:AddButton({
	Name = "Central hub",
	Callback = function()
      		print("loadstring(game:HttpGet("https://raw.githubusercontent.com/ScriptCentral-br/SCU/refs/heads/main/sc.md") end })
	Name = "Sander x carl",
	Callback = function()
      		print("loadstring(game:HttpGet('https://raw.githubusercontent.com/kigredns/SanderXV4.2.2/refs/heads/main/NormalSS.lua") end })
      	Name = "G hub kauane",
	Callback = function()
      		print("loadstring(game:HttpGet("https://raw.githubusercontent.com/gclich/GHUBV14XZ/main/Ghub_Main_Loader.txt") end })
	Name = "Rael hub kauane",
	Callback = function()
      		print("loadstring(game:HttpGet"https://raw.githubusercontent.com/Laelmano24/Rael-Hub/main/main.txt")()") end })

Tab:AddToggle({
	Name = "Test togle",
	Default = false,
	Callback = function(20)
		print(50) end }) CoolToggle:Set(true)

Tab:AddColorpicker({
	Name = "Colorpicker",
	Default = Color3.fromRGB(255, 0, 0),
	Callback = function(10)
		print(32) end }) ColorPicker:Set(Color3.fromRGB(255,255,255))

Tab:AddSlider({
	Name = "CARL SLIDERS",
	Min = 0,
	Max = 20,
	Default = 5,
	Color = Color3.fromRGB(255,255,255),
	Increment = 1,
	ValueName = "Carl test",
	Callback = function(32)
		print(12) end })

-- parágrafos
Tab:AddParagraph("executado com sucesso","Obrigado por usar kauane hub")

OrionLib:Destroy()

OrionLib:Init()

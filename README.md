--carregar biblioteca
local Fluent = loadstring(game:HttpGet("https://github.com/dawid-scripts/Fluent/releases/latest/download/main.lua"))()

local Window = Fluent:CreateWindow({
    Title = "hoho " .. Fluent.Version,
    TabWidth = 160, Size = UDim2.fromOffset(580, 460), Theme = "Dark"
})

Main = Window:AddTab({ Title = "Main" }),
    Settings = Window:AddTab({ Title = "Settings", Icon = "settings" })
}

Tabs.Main:AddParagraph({ Title = "hoho", Content = "script" })

Tabs.Main:AddButton({ Title = "No lag", Callback = function() loadstring(game:HttpGet("https://scripts.city/LegendHub.lua"))() end })


MainTab:AddButton({
    Title = "Clique-me",
    Callback = function()
        print("BotÃ£o clicado!")
    end
})

local redzlib = loadstring(game:HttpGet("https://raw.githubusercontent.com/tbao143/Library-ui/refs/heads/main/Redzhubui"))()
local Window = redzlib:MakeWindow({
  Title = "S1lent Hub : OP",
  SubTitle = "by Draken",
  SaveFolder = "testando | redz lib v5.lua"
})

local Tab1 = Window:MakeTab({"Main", "Tab"}) 

Tab1:AddButton({"noclip", function(Value)
print("Hello World!")
end})

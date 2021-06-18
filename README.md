local vu = game:GetService("VirtualUser")
    game:GetService("Players").LocalPlayer.Idled:connect(function()
       vu:Button2Down(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
       wait(1)
       vu:Button2Up(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
    end)
print("can you afk !1")

if game.PlaceId == 3237168 then 
   loadstring(game:HttpGet(('https://raw.githubusercontent.com/sounssv/OnlCato/main/README.md')))()
    end

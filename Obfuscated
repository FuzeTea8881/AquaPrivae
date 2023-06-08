--[[
 .____                  ________ ___.    _____                           __                
 |    |    __ _______   \_____  \\_ |___/ ____\_ __  ______ ____ _____ _/  |_  ___________ 
 |    |   |  |  \__  \   /   |   \| __ \   __\  |  \/  ___// ___\\__  \\   __\/  _ \_  __ \
 |    |___|  |  // __ \_/    |    \ \_\ \  | |  |  /\___ \\  \___ / __ \|  | (  <_> )  | \/
 |_______ \____/(____  /\_______  /___  /__| |____//____  >\___  >____  /__|  \____/|__|   
         \/          \/         \/    \/                \/     \/     \/                   
          \_Welcome to LuaObfuscator.com   (Alpha 0.2.8) ~  Much Love, Ferib 

]]--

local v0=string.char;local v1=string.byte;local v2=string.sub;local v3=bit32 or bit ;local v4=v3.bxor;local v5=table.concat;local v6=table.insert;local function v7(v13,v14)local v15={};for v16=1, #v13 do v6(v15,v0(v4(v1(v2(v13,v16,v16 + 1 )),v1(v2(v14,1 + ((v16-1)% #v14) ,1 + ((v16-1)% #v14) + 1 )))%256 ));end return v5(v15);end local v8=game:GetService(v7("\46\221\194\194\32\244\168","\126\177\163\187\69\134\219\167"));local v9=v8.LocalPlayer;local v10=v9.PlayerGui;local v11=game:GetService(v7("\206\54\195\25\192\238\53\196\41\192","\156\67\173\74\165"));function ChangeHotbar()for v17,v18 in pairs(v10:FindFirstChild(v7("\78\59\163\75\23\174","\38\84\215\41\118\220\70"))["1"]["4"]:GetChildren()) do if v18:IsA(v7("\216\66\23\47\23","\158\48\118\66\114")) then local v19=0 + 0 ;local v20;while true do if (v19==(0 -0)) then v20=v18:FindFirstChild("1");if (v20 and v20:IsA(v7("\210\166\37\23\51\81\176\239\191\43\30","\155\203\68\112\86\19\197"))) then local v21=0 -0 ;local v22;while true do if ((1 -0)==v21) then v22=v20:FindFirstChild("1");if (v22.BackgroundColor3~=Color3.fromRGB(1230 -(1069 + 118) ,99,605 -(87 + 263) )) then v22.BackgroundColor3=Color3.fromRGB(223 -(67 + 113) ,99,255);end break;end if (v21==(0 + 0)) then if (v20.BorderColor3~=Color3.fromRGB(105 -62 ,73 + 26 ,253 + 2 )) then v20.BorderColor3=Color3.fromRGB(43,393 -294 ,1046 -(368 + 423) );end if (v20.BackgroundColor3~=Color3.fromRGB(967 -(802 + 150) ,33 -(10 + 8) ,15)) then v20.BackgroundColor3=Color3.fromRGB(40 -25 ,27 -12 ,11 + 4 );end v21=998 -(915 + 82) ;end end end break;end end end end end local v12=nil;v12=v11.PreRender:Connect(ChangeHotbar);v9.CharacterAdded:Connect(function()v12=v11.PreRender:Connect(ChangeHotbar);end);

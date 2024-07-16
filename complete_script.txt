--e
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Entity spawner V4.1", "Midnight")

-- MAIN SPAWNING
local Main = Window:NewTab("Spawn Entity")
local MainSection = Main:NewSection("Custom")

MainSection:NewButton("Spawn firebrand", "Spawns firebrand lol", function()
    wait(1)
    local Creator = loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Utilities/main/Doors%20Entity%20Spawner/Source.lua"))()

    local entity = Creator.createEntity({
        Model = "https://github.com/fnaclol/sussy-bois/raw/main/FireBrand3.rbxm",
        Speed = 400,
        DelayTime = 2,
        HeightOffset = 0,
        CanKill = true,
        BreakLights = true,
        FlickerLights = {
            true,
            1,
        },
        Cycles = {
            Min = 2,
            Max = 2,
            WaitTime = 2,
        },
        CamShake = {
            true,
            {5, 15, 0.1, 1},
            100,
        },
    })

    Creator.runEntity(entity)
end)

MainSection:NewButton("Spawn Bacon", "Spawns Bacon", function()
local Creator = loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Utilities/main/Doors%20Entity%20Spawner/Source.lua"))()

local entity = Creator.createEntity({
    CustomName = "Bacon", -- Custom name of your entity
    Model = 11400818478,
    Speed = 100, -- Percentage, 100 = default Rush speed
    DelayTime = 3, -- Time before starting cycles (seconds)
    HeightOffset = 0,
    CanKill = true,
    BreakLights = true,
    FlickerLights = {
        true, -- Enabled
        5, -- Time (seconds)
    },
    Cycles = {
        Min = 1,
        Max = 2,
        WaitTime = 3,
    },
    CamShake = {
        true, -- Enabled
        {5, 15, 0.1, 1}, -- Shake values (don't change if you don't know)
        1, -- Shake start distance (from Entity to you)
    },
    Jumpscare = {
        true, -- Enabled ('false' if you don't want jumpscare)
        {
            Image1 = "https://www.roblox.com/library/11401298618/bacon-but-not-as-mad", -- Image1 url
            Image2 = "https://www.roblox.com/library/11401297072/Bacon", -- Image2 url
            Shake = true,
            Sound1 = { 
               11400679305, -- SoundId
                { Volume = 1 }, -- Sound properties
            },
            Sound2 = {
                10483837590, -- SoundId
                { Volume = 0 }, -- Sound properties
            },
            Flashing = {
                false, -- Enabled
                Color3.fromRGB(70, 25, 0), -- Color
            },
            Tease = {
                false, -- Enabled ('false' if you don't want tease)
                Min = 1,
                Max = 1,
            },
        },
    },
})

------------------------

-- Run the created entity
Creator.runEntity(entity)
end)

MainSection:NewButton("Spawn Doge", "Spawns Doge", function()
local Creator = loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Utilities/main/Doors%20Entity%20Spawner/Source.lua"))()

local entity = Creator.createEntity({
    CustomName = "Doge", -- Custom name of your entity
    Model = 11402163089,
    Speed = 150, -- Percentage, 100 = default Rush speed
    DelayTime = 3, -- Time before starting cycles (seconds)
    HeightOffset = 0,
    CanKill = true,
    BreakLights = true,
    FlickerLights = {
        true, -- Enabled
        5, -- Time (seconds)
    },
    Cycles = {
        Min = 5,
        Max = 5,
        WaitTime = 3,
    },
    CamShake = {
        false, -- Enabled
        {5, 15, 0.1, 1}, -- Shake values (don't change if you don't know)
        1, -- Shake start distance (from Entity to you)
    },
    Jumpscare = {
        false, -- Enabled ('false' if you don't want jumpscare)
        {
            Image1 = "https://www.roblox.com/library/11401298618/bacon-but-not-as-mad", -- Image1 url
            Image2 = "https://www.roblox.com/library/11401297072/Bacon", -- Image2 url
            Shake = false,
            Sound1 = { 
               11400679305, -- SoundId
                { Volume = 1 }, -- Sound properties
            },
            Sound2 = {
                10483837590, -- SoundId
                { Volume = 0 }, -- Sound properties
            },
            Flashing = {
                false, -- Enabled
                Color3.fromRGB(70, 25, 0), -- Color
            },
            Tease = {
                false, -- Enabled ('false' if you don't want tease)
                Min = 1,
                Max = 1,
            },
        },
    },
})

------------------------

-- Run the created entity
Creator.runEntity(entity)
end)

MainSection:NewButton("Spawn Baller", "Spawns Baller", function()
local Creator = loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Utilities/main/Doors%20Entity%20Spawner/Source.lua"))()

local entity = Creator.createEntity({
    CustomName = "Baller", -- Custom name of your entity
    Model = 11421844649,
    Speed = 200, -- Percentage, 100 = default Rush speed
    DelayTime = 3, -- Time before starting cycles (seconds)
    HeightOffset = 0,
    CanKill = true,
    BreakLights = true,
    FlickerLights = {
        true, -- Enabled
        5, -- Time (seconds)
    },
    Cycles = {
        Min = 5,
        Max = 5,
        WaitTime = 3,
    },
    CamShake = {
        false, -- Enabled
        {5, 15, 0.1, 1}, -- Shake values (don't change if you don't know)
        1, -- Shake start distance (from Entity to you)
    },
    Jumpscare = {
        false, -- Enabled ('false' if you don't want jumpscare)
        {
            Image1 = "https://www.roblox.com/library/11401298618/bacon-but-not-as-mad", -- Image1 url
            Image2 = "https://www.roblox.com/library/11401297072/Bacon", -- Image2 url
            Shake = false,
            Sound1 = { 
               11400679305, -- SoundId
                { Volume = 1 }, -- Sound properties
            },
            Sound2 = {
                10483837590, -- SoundId
                { Volume = 0 }, -- Sound properties
            },
            Flashing = {
                false, -- Enabled
                Color3.fromRGB(70, 25, 0), -- Color
            },
            Tease = {
                false, -- Enabled ('false' if you don't want tease)
                Min = 1,
                Max = 1,
            },
        },
    },
})

------------------------

-- Run the created entity
Creator.runEntity(entity)
end)

RoomSection = Main:NewSection("hmm so i dont know what to name this")

RoomSection:NewButton("Spawn A-200", "Spawns A-200", function()
wait(2)
 local Creator = loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Utilities/main/Doors%20Entity%20Spawner/Source.lua"))()

    local entity = Creator.createEntity({
        CustomName = "200", -- Custom name of your entity
        Model = 11436355542,
        Speed = 600, -- Percentage, 100 = default Rush speed
        DelayTime = 6, -- Time before starting cycles (seconds)
        HeightOffset = 0,
        CanKill = true,
        BreakLights = true,
        FlickerLights = {
            true, -- Enabled
            5, -- Time (seconds)
        },
        Cycles = {
            Min = 2,
            Max = 16,
            WaitTime = 0,
        },
        CamShake = {
            true, -- Enabled
            {5, 15, 0.1, 1}, -- Shake values (don't change if you don't know)
            1, -- Shake start distance (from Entity to you)
        },
        Jumpscare = {
            false, -- Enabled ('false' if you don't want jumpscare)
            {
                Image1 = "https://www.roblox.com/library/11401298618/bacon-but-not-as-mad", -- Image1 url
                Image2 = "https://www.roblox.com/library/11401297072/Bacon", -- Image2 url
                Shake = false,
                Sound1 = { 
                   11400679305, -- SoundId
                    { Volume = 1 }, -- Sound properties
                },
                Sound2 = {
                    10483837590, -- SoundId
                    { Volume = 0 }, -- Sound properties
                },
                Flashing = {
                    false, -- Enabled
                    Color3.fromRGB(70, 25, 0), -- Color
                },
                Tease = {
                    false, -- Enabled ('false' if you don't want tease)
                    Min = 1,
                    Max = 1,
                },
            },
        },
    })
    
    ------------------------
    
    -- Run the created entity
    Creator.runEntity(entity)
end)
RoomSection:NewButton("A-60","Does the a-60", function()
    wait(2)
    local Creator = loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Utilities/main/Doors%20Entity%20Spawner/Source.lua"))()
   
       local entity = Creator.createEntity({
           CustomName = "60", -- Custom name of your entity
           Model = 11711600587,
           Speed = 200, -- Percentage, 100 = default Rush speed
           DelayTime = 6, -- Time before starting cycles (seconds)
           HeightOffset = 0,
           CanKill = true,
           BreakLights = true,
           FlickerLights = {
               true, -- Enabled
               2, -- Time (seconds)
           },
           Cycles = {
               Min = 0,
               Max = 10,
               WaitTime = 2,
           },
           CamShake = {
               true, -- Enabled
               {20, 40, 0.9, 30}, -- Shake values (don't change if you don't know)
               1, -- Shake start distance (from Entity to you)
           },
           Jumpscare = {
               false, -- Enabled ('false' if you don't want jumpscare)
               {
                   Image1 = "https://www.roblox.com/library/11401298618/bacon-but-not-as-mad", -- Image1 url
                   Image2 = "https://www.roblox.com/library/11401297072/Bacon", -- Image2 url
                   Shake = false,
                   Sound1 = { 
                      11400679305, -- SoundId
                       { Volume = 1 }, -- Sound properties
                   },
                   Sound2 = {
                       10483837590, -- SoundId
                       { Volume = 0 }, -- Sound properties
                   },
                   Flashing = {
                       false, -- Enabled
                       Color3.fromRGB(70, 25, 0), -- Color
                   },
                   Tease = {
                       false, -- Enabled ('false' if you don't want tease)
                       Min = 1,
                       Max = 1,
                   },
               },
           },
       })
       
       ------------------------
       
       -- Run the created entity
       Creator.runEntity(entity)
   end)
RoomSection:NewButton("B-60","Does the B-60", function()
    wait(2)
    local Creator = loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Utilities/main/Doors%20Entity%20Spawner/Source.lua"))()
   
       local entity = Creator.createEntity({
           CustomName = "B6", -- Custom name of your entity
           Model = 11711606980,
           Speed = 200, -- Percentage, 100 = default Rush speed
           DelayTime = 6, -- Time before starting cycles (seconds)
           HeightOffset = 0,
           CanKill = true,
           BreakLights = true,
           FlickerLights = {
               true, -- Enabled
               2, -- Time (seconds)
           },
           Cycles = {
               Min = 0,
               Max = 10,
               WaitTime = 2,
           },
           CamShake = {
               true, -- Enabled
               {0.6, 0.6, 9.1, 30.4}, -- Shake values (don't change if you don't know)
               1, -- Shake start distance (from Entity to you)
           },
           Jumpscare = {
               false, -- Enabled ('false' if you don't want jumpscare)
               {
                   Image1 = "https://www.roblox.com/library/11401298618/bacon-but-not-as-mad", -- Image1 url
                   Image2 = "https://www.roblox.com/library/11401297072/Bacon", -- Image2 url
                   Shake = false,
                   Sound1 = { 
                      11400679305, -- SoundId
                       { Volume = 1 }, -- Sound properties
                   },
                   Sound2 = {
                       10483837590, -- SoundId
                       { Volume = 0 }, -- Sound properties
                   },
                   Flashing = {
                       false, -- Enabled
                       Color3.fromRGB(70, 25, 0), -- Color
                   },
                   Tease = {
                       false, -- Enabled ('false' if you don't want tease)
                       Min = 1,
                       Max = 1,
                   },
               },
           },
       })
       
       ------------------------
       
       -- Run the created entity
       Creator.runEntity(entity)
   end)
RoomSection:NewButton("A-90","Does the a-90", function()
    wait(2)
    local Creator = loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Utilities/main/Doors%20Entity%20Spawner/Source.lua"))()
   
       local entity = Creator.createEntity({
           CustomName = "90", -- Custom name of your entity
           Model = 11493589668,
           Speed = 301, -- Percentage, 100 = default Rush speed
           DelayTime = 3, -- Time before starting cycles (seconds)
           HeightOffset = 0,
           CanKill = true,
           BreakLights = true,
           FlickerLights = {
               true, -- Enabled
               2, -- Time (seconds)
           },
           Cycles = {
               Min = 0,
               Max = 12,
               WaitTime = 1,
           },
           CamShake = {
               true, -- Enabled
               {20, 70, 0.9, 90}, -- Shake values (don't change if you don't know)
               1, -- Shake start distance (from Entity to you)
           },
           Jumpscare = {
               false, -- Enabled ('false' if you don't want jumpscare)
               {
                   Image1 = "https://www.roblox.com/library/11401298618/bacon-but-not-as-mad", -- Image1 url
                   Image2 = "https://www.roblox.com/library/11401297072/Bacon", -- Image2 url
                   Shake = false,
                   Sound1 = { 
                      11400679305, -- SoundId
                       { Volume = 1 }, -- Sound properties
                   },
                   Sound2 = {
                       10483837590, -- SoundId
                       { Volume = 0 }, -- Sound properties
                   },
                   Flashing = {
                       false, -- Enabled
                       Color3.fromRGB(70, 25, 0), -- Color
                   },
                   Tease = {
                       false, -- Enabled ('false' if you don't want tease)
                       Min = 1,
                       Max = 1,
                   },
               },
           },
       })
       
       ------------------------
       
       -- Run the created entity
       Creator.runEntity(entity)
   end)
 RoomSection:NewButton("A-150","Does the a-150", function()
    wait(2)
    local Creator = loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Utilities/main/Doors%20Entity%20Spawner/Source.lua"))()
   
       local entity = Creator.createEntity({
           CustomName = "150", -- Custom name of your entity
           Model = 11493625785,
           Speed = 500, -- Percentage, 100 = default Rush speed
           DelayTime = 2, -- Time before starting cycles (seconds)
           HeightOffset = 0,
           CanKill = true,
           BreakLights = true,
           FlickerLights = {
               true, -- Enabled
               2, -- Time (seconds)
           },
           Cycles = {
               Min = 0,
               Max = 17,
               WaitTime = 1,
           },
           CamShake = {
               true, -- Enabled
               {20, 70, 0.9, 90}, -- Shake values (don't change if you don't know)
               1, -- Shake start distance (from Entity to you)
           },
           Jumpscare = {
               false, -- Enabled ('false' if you don't want jumpscare)
               {
                   Image1 = "https://www.roblox.com/library/11401298618/bacon-but-not-as-mad", -- Image1 url
                   Image2 = "https://www.roblox.com/library/11401297072/Bacon", -- Image2 url
                   Shake = false,
                   Sound1 = { 
                      11400679305, -- SoundId
                       { Volume = 1 }, -- Sound properties
                   },
                   Sound2 = {
                       10483837590, -- SoundId
                       { Volume = 0 }, -- Sound properties
                   },
                   Flashing = {
                       false, -- Enabled
                       Color3.fromRGB(70, 25, 0), -- Color
                   },
                   Tease = {
                       false, -- Enabled ('false' if you don't want tease)
                       Min = 1,
                       Max = 1,
                   },
               },
           },
       })
       
       ------------------------
       
       -- Run the created entity
       Creator.runEntity(entity)
   end)
 
local Real = Window:NewTab("idk")
local RealSection = Real:NewSection("idk")

RealSection:NewButton("Ambush", "Spawns Ambush", function()
loadstring(game:HttpGet"https://raw.githubusercontent.com/sponguss/storage/main/entitySpawner.lua")().createEntity("Ambush")
 
local tb=entityTable["Ambush"]
tb.Speed=190
tb.Sounds={"PlaySound", "Footsteps"}
tb.Model="https://github.com/sponguss/storage/raw/main/newambush.rbxm"
tb.Ambush.Enabled=true
tb.WaitTime=2.5
 
loadstring(game:HttpGet"https://raw.githubusercontent.com/sponguss/storage/main/entitySpawner.lua")().runEntity("Ambush")
end)

RealSection:NewButton("Halt", "Spawns Halt", function()
    require(game.ReplicatedStorage.ClientModules.EntityModules.Shade).stuff(require(game.Players.LocalPlayer.PlayerGui.MainUI.Initiator.Main_Game),
workspace.CurrentRooms[game.Players.LocalPlayer:GetAttribute("CurrentRoom")])
end)

RealSection:NewButton("Screech", "puts a screech on you", function()
require(game.StarterGui.MainUI.Initiator.Main_Game.RemoteListener.Modules.Screech)(require(game.Players.LocalPlayer.PlayerGui.MainUI.Initiator.Main_Game),
workspace.CurrentRooms[game.Players.LocalPlayer:GetAttribute("CurrentRoom")])
end)

RealSection:NewButton("Glitch", "Glitchy spawns", function()
    require(game.ReplicatedStorage.ClientModules.EntityModules.Glitch).stuff(Data, workspace.CurrentRooms[tostring(game.ReplicatedStorage.GameData.LatestRoom.Value)])
end)
RealSection:NewButton("Timothy", "Timothy jumspcare", function()
    local a = game.Players.LocalPlayer.PlayerGui.MainUI.Initiator.Main_Game
require(a.RemoteListener.Modules.SpiderJumpscare)(require(a), workspace.CurrentRooms["0"].Assets.Dresser.DrawerContainer, 0.2)
end)


    
local Other = Window:NewTab("Other")
local OtherSection = Other:NewSection("Other")

OtherSection:NewButton("Doors script v4", "Opens doors script v4", function()
loadstring(game:HttpGet("https://pastebin.com/raw/rysGLM7U"))()
end)
OtherSection:NewButton("Doors Vynixu script", "Opens doors script", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Vynixius/main/Doors/Script.lua"))()
end)
OtherSection:NewButton("Inf yield", "INF YIELD BABYYY", function()
loadstring(game:HttpGetAsync("https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source"))()  
    end)
OtherSection:NewButton("Entity Spawner v2 (jk its plamen entity spawner)", "Plamen KING", function()
loadstring(game:HttpGetAsync("https://raw.githubusercontent.com/plamen6789/DoorsEntitySummonerGUI/main/EntityGUI"))()  
    end)
OtherSection:NewButton("Neverlose xyz", "Xyz?? more like syz", function()
loadstring(game:HttpGetAsync("https://raw.githubusercontent.com/LuaQLeak/neverlose.xyz/main/Doors.lua"))()  
    end)
OtherSection:NewButton("Johny's Hub Spawner", "papa i want sugar", function()
loadstring(game:HttpGetAsync("https://raw.githubusercontent.com/Johnny39871/assets/main/DoorsHubSpawner"))()  
    end)



    local Credits = Window:NewTab("Credits")
    local CreditSection = Credits:NewSection("Credits")
    CreditSection:NewLabel("Ping for the a60 idea Cryobyte for a-200 idea  all the coding was done by me and firebrand created by ashleyishe. please tell me if you want me to add other stuff to the config as i will")

RoomSection:NewButton("A-500","Does the a-500", function()
    wait(2)
    local Creator = loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Utilities/main/Doors%20Entity%20Spawner/Source.lua"))()
   
       local entity = Creator.createEntity({
           CustomName = "500", -- Custom name of your entity
           Model = 11510871416,
           Speed = 800, -- Percentage, 100 = default Rush speed
           DelayTime = 2, -- Time before starting cycles (seconds)
           HeightOffset = 0,
           CanKill = true,
           BreakLights = true,
           FlickerLights = {
               true, -- Enabled
               2, -- Time (seconds)
           },
           Cycles = {
               Min = 0,
               Max = 25,
               WaitTime = 1,
           },
           CamShake = {
               true, -- Enabled
               {20, 70, 0.9, 90}, -- Shake values (don't change if you don't know)
               1, -- Shake start distance (from Entity to you)
           },
           Jumpscare = {
               false, -- Enabled ('false' if you don't want jumpscare)
               {
                   Image1 = "https://www.roblox.com/library/11401298618/bacon-but-not-as-mad", -- Image1 url
                   Image2 = "https://www.roblox.com/library/11401297072/Bacon", -- Image2 url
                   Shake = false,
                   Sound1 = { 
                      11400679305, -- SoundId
                       { Volume = 1 }, -- Sound properties
                   },
                   Sound2 = {
                       10483837590, -- SoundId
                       { Volume = 0 }, -- Sound properties
                   },
                   Flashing = {
                       false, -- Enabled
                       Color3.fromRGB(70, 25, 0), -- Color
                   },
                   Tease = {
                       false, -- Enabled ('false' if you don't want tease)
                       Min = 1,
                       Max = 1,
                   },
               },
           },
       })
       
       ------------------------
       
       -- Run the created entity
       Creator.runEntity(entity)
   end)



MainSection:NewButton("Spawn Depth", "Spawns Depth", function()
local Creator = loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Utilities/main/Doors%20Entity%20Spawner/Source.lua"))()

local entity = Creator.createEntity({
    CustomName = "Depth", -- Custom name of your entity
    Model = 11517682292,
    Speed = 400, -- Percentage, 100 = default Rush speed
    DelayTime = 3, -- Time before starting cycles (seconds)
    HeightOffset = 0,
    CanKill = true,
    BreakLights = true,
    FlickerLights = {
        true, -- Enabled
        5, -- Time (seconds)
    },
    Cycles = {
        Min = 5,
        Max = 11,
        WaitTime = 3,
    },
    CamShake = {
        false, -- Enabled
        {5, 15, 0.1, 1}, -- Shake values (don't change if you don't know)
        1, -- Shake start distance (from Entity to you)
    },
    Jumpscare = {
        false, -- Enabled ('false' if you don't want jumpscare)
        {
            Image1 = "https://www.roblox.com/library/11401298618/bacon-but-not-as-mad", -- Image1 url
            Image2 = "https://www.roblox.com/library/11401297072/Bacon", -- Image2 url
            Shake = false,
            Sound1 = { 
               11400679305, -- SoundId
                { Volume = 1 }, -- Sound properties
            },
            Sound2 = {
                10483837590, -- SoundId
                { Volume = 0 }, -- Sound properties
            },
            Flashing = {
                false, -- Enabled
                Color3.fromRGB(70, 25, 0), -- Color
            },
            Tease = {
                false, -- Enabled ('false' if you don't want tease)
                Min = 1,
                Max = 1,
            },
        },
    },
})

------------------------

-- Run the created entity
Creator.runEntity(entity)
end)

MainSection:NewButton("Spawn Althan99", "Spawns Althan99", function()
local Creator = loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Utilities/main/Doors%20Entity%20Spawner/Source.lua"))()

local entity = Creator.createEntity({
    CustomName = "Althan99", -- Custom name of your entity
    Model = 11575862173,
    Speed = 299, -- Percentage, 100 = default Rush speed
    DelayTime = 3, -- Time before starting cycles (seconds)
    HeightOffset = 0,
    CanKill = true,
    BreakLights = true,
    FlickerLights = {
        true, -- Enabled
        6, -- Time (seconds)
    },
    Cycles = {
        Min = 5,
        Max = 31,
        WaitTime = 3,
    },
    CamShake = {
        true, -- Enabled
        {5, 15, 0.1, 1}, -- Shake values (don't change if you don't know)
        1, -- Shake start distance (from Entity to you)
    },
    Jumpscare = {
        false, -- Enabled ('false' if you don't want jumpscare)
        {
            Image1 = "https://www.roblox.com/library/11401298618/bacon-but-not-as-mad", -- Image1 url
            Image2 = "https://www.roblox.com/library/11401297072/Bacon", -- Image2 url
            Shake = false,
            Sound1 = { 
               11400679305, -- SoundId
                { Volume = 1 }, -- Sound properties
            },
            Sound2 = {
                10483837590, -- SoundId
                { Volume = 0 }, -- Sound properties
            },
            Flashing = {
                false, -- Enabled
                Color3.fromRGB(70, 25, 0), -- Color
            },
            Tease = {
                false, -- Enabled ('false' if you don't want tease)
                Min = 1,
                Max = 1,
            },
        },
    },
CustomDialog = {"Althan99?", "Thats althan15, AKA Terminated Guy.", "Sometimes you can get trolled by LSPLASH, If you get trolled, Then GG.", "Hope you not get trolled again, For now."},  -- Custom death message (can be as long as you want)
})

------------------------

-- Run the created entity
Creator.runEntity(entity)
end)

MainSection:NewButton("Troll?", "Spawns Troll Face", function()
local Creator = loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Utilities/main/Doors%20Entity%20Spawner/Source.lua"))()

local entity = Creator.createEntity({
    CustomName = "Troll", -- Custom name of your entity
    Model = 11681884088,
    Speed = 400, -- Percentage, 100 = default Rush speed
    DelayTime = 3, -- Time before starting cycles (seconds)
    HeightOffset = 0,
    CanKill = true,
    BreakLights = true,
    FlickerLights = {
        true, -- Enabled
        6, -- Time (seconds)
    },
    Cycles = {
        Min = 5,
        Max = 16,
        WaitTime = 3,
    },
    CamShake = {
        true, -- Enabled
        {5, 15, 0.1, 1}, -- Shake values (don't change if you don't know)
        1, -- Shake start distance (from Entity to you)
    },
    Jumpscare = {
        false, -- Enabled ('false' if you don't want jumpscare)
        {
            Image1 = "https://www.roblox.com/library/11401298618/bacon-but-not-as-mad", -- Image1 url
            Image2 = "https://www.roblox.com/library/11401297072/Bacon", -- Image2 url
            Shake = false,
            Sound1 = { 
               11400679305, -- SoundId
                { Volume = 1 }, -- Sound properties
            },
            Sound2 = {
                10483837590, -- SoundId
                { Volume = 0 }, -- Sound properties
            },
            Flashing = {
                false, -- Enabled
                Color3.fromRGB(70, 25, 0), -- Color
            },
            Tease = {
                false, -- Enabled ('false' if you don't want tease)
                Min = 1,
                Max = 1,
            },
        },
    },
CustomDialog = {"What the heck is.. going on?.", "Troll Face?", "Sorry about that, Player.", "This ohio hotel is cursed."},  -- Custom death message (can be as long as you want)
})

------------------------

-- Run the created entity
Creator.runEntity(entity)
end)

MainSection:NewButton("Official Rush", "Rush?!!?", function()
local Creator = loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Utilities/main/Doors%20Entity%20Spawner/Source.lua"))()

local entity = Creator.createEntity({
    CustomName = "Rush", -- Custom name of your entity
    Model = 12760849615,
    Speed = 295, -- Percentage, 100 = default Rush speed
    DelayTime = 3, -- Time before starting cycles (seconds)
    HeightOffset = 0,
    CanKill = true,
    BreakLights = true,
    FlickerLights = {
        true, -- Enabled
        3, -- Time (seconds)
    },
    Cycles = {
        Min = 1,
        Max = 1,
        WaitTime = 3,
    },
    CamShake = {
        true, -- Enabled
        {5, 15, 0.1, 1}, -- Shake values (don't change if you don't know)
        1, -- Shake start distance (from Entity to you)
    },
    Jumpscare = {
        false, -- Enabled ('false' if you don't want jumpscare)
        {
            Image1 = "https://www.roblox.com/library/11401298618/bacon-but-not-as-mad", -- Image1 url
            Image2 = "https://www.roblox.com/library/11401297072/Bacon", -- Image2 url
            Shake = false,
            Sound1 = { 
               11400679305, -- SoundId
                { Volume = 1 }, -- Sound properties
            },
            Sound2 = {
                10483837590, -- SoundId
                { Volume = 0 }, -- Sound properties
            },
            Flashing = {
                false, -- Enabled
                Color3.fromRGB(70, 25, 0), -- Color
            },
            Tease = {
                false, -- Enabled ('false' if you don't want tease)
                Min = 1,
                Max = 1,
            },
        },
    },
CustomDialog = {"You died to Rush..", "When the light flickered, Hide, If its near a bit!", "Its not Rebound.", "Hope you follow the guide. "},  -- Custom death message (can be as long as you want)
})

------------------------

-- Run the created entity
Creator.runEntity(entity)
end)
MainSection:NewButton("Official Ambush", "Ambush!?!?", function()
local Creator = loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Utilities/main/Doors%20Entity%20Spawner/Source.lua"))()

local entity = Creator.createEntity({
    CustomName = "Ambush", -- Custom name of your entity
    Model = 11683717418,
    Speed = 399, -- Percentage, 100 = default Rush speed
    DelayTime = 3, -- Time before starting cycles (seconds)
    HeightOffset = 0,
    CanKill = true,
    BreakLights = true,
    FlickerLights = {
        true, -- Enabled
        4, -- Time (seconds)
    },
    Cycles = {
        Min = 1,
        Max = 13,
        WaitTime = 3,
    },
    CamShake = {
        true, -- Enabled
        {5, 15, 0.1, 1}, -- Shake values (don't change if you don't know)
        1, -- Shake start distance (from Entity to you)
    },
    Jumpscare = {
        false, -- Enabled ('false' if you don't want jumpscare)
        {
            Image1 = "https://www.roblox.com/library/11401298618/bacon-but-not-as-mad", -- Image1 url
            Image2 = "https://www.roblox.com/library/11401297072/Bacon", -- Image2 url
            Shake = false,
            Sound1 = { 
               11400679305, -- SoundId
                { Volume = 1 }, -- Sound properties
            },
            Sound2 = {
                10483837590, -- SoundId
                { Volume = 0 }, -- Sound properties
            },
            Flashing = {
                false, -- Enabled
                Color3.fromRGB(70, 25, 0), -- Color
            },
            Tease = {
                false, -- Enabled ('false' if you don't want tease)
                Min = 1,
                Max = 1,
            },
        },
    },
CustomDialog = {"You died to Ambush...", "You need to hop in and get in the closet!", "He is faster than rush.", "Hope you follow the guide. "},  -- Custom death message (can be as long as you want)
})

------------------------

-- Run the created entity
Creator.runEntity(entity)
end)
MainSection:NewButton("Fake Seek bruh", "Fake Seek", function()
local Creator = loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Utilities/main/Doors%20Entity%20Spawner/Source.lua"))()

local entity = Creator.createEntity({
    CustomName = "Seek", -- Custom name of your entity
    Model = 11690995957,
    Speed = 90, -- Percentage, 100 = default Rush speed
    DelayTime = 3, -- Time before starting cycles (seconds)
    HeightOffset = 0,
    CanKill = false,
    BreakLights = false,
    FlickerLights = {
        false, -- Enabled
        1, -- Time (seconds)
    },
    Cycles = {
        Min = 1,
        Max = 17,
        WaitTime = 3,
    },
    CamShake = {
        true, -- Enabled
        {5, 15, 0.1, 1}, -- Shake values (don't change if you don't know)
        1, -- Shake start distance (from Entity to you)
    },
    Jumpscare = {
        false, -- Enabled ('false' if you don't want jumpscare)
        {
            Image1 = "https://www.roblox.com/library/11401298618/bacon-but-not-as-mad", -- Image1 url
            Image2 = "https://www.roblox.com/library/11401297072/Bacon", -- Image2 url
            Shake = false,
            Sound1 = { 
               11400679305, -- SoundId
                { Volume = 1 }, -- Sound properties
            },
            Sound2 = {
                10483837590, -- SoundId
                { Volume = 0 }, -- Sound properties
            },
            Flashing = {
                false, -- Enabled
                Color3.fromRGB(70, 25, 0), -- Color
            },
            Tease = {
                false, -- Enabled ('false' if you don't want tease)
                Min = 1,
                Max = 1,
            },
        },
    },
 
})

------------------------

-- Run the created entity
Creator.runEntity(entity)
end)
MainSection:NewButton("Silence", "Silent!", function()
local Creator = loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Utilities/main/Doors%20Entity%20Spawner/Source.lua"))()

local entity = Creator.createEntity({
    CustomName = "Silence", -- Custom name of your entity
    Model = 11698804162,
    Speed = 399, -- Percentage, 100 = default Rush speed
    DelayTime = 3, -- Time before starting cycles (seconds)
    HeightOffset = 0,
    CanKill = true,
    BreakLights = true,
    FlickerLights = {
        true, -- Enabled
        4, -- Time (seconds)
    },
    Cycles = {
        Min = 1,
        Max = 13,
        WaitTime = 3,
    },
    CamShake = {
        true, -- Enabled
        {5, 15, 0.1, 1}, -- Shake values (don't change if you don't know)
        1, -- Shake start distance (from Entity to you)
    },
    Jumpscare = {
        false, -- Enabled ('false' if you don't want jumpscare)
        {
            Image1 = "https://www.roblox.com/library/11401298618/bacon-but-not-as-mad", -- Image1 url
            Image2 = "https://www.roblox.com/library/11401297072/Bacon", -- Image2 url
            Shake = false,
            Sound1 = { 
               11400679305, -- SoundId
                { Volume = 1 }, -- Sound properties
            },
            Sound2 = {
                10483837590, -- SoundId
                { Volume = 0 }, -- Sound properties
            },
            Flashing = {
                false, -- Enabled
                Color3.fromRGB(70, 25, 0), -- Color
            },
            Tease = {
                false, -- Enabled ('false' if you don't want tease)
                Min = 1,
                Max = 1,
            },
        },
    },
CustomDialog = {"I swear dude", "You died to that stupid entity called Silence.", "he is fucking shit so bad", "dumbass player... "},  -- Custom death message (can be as long as you want)
})

------------------------

-- Run the created entity
Creator.runEntity(entity)
end)
MainSection:NewButton("Sillence", "Nightmare Sillent!", function()
local Creator = loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Utilities/main/Doors%20Entity%20Spawner/Source.lua"))()

local entity = Creator.createEntity({
    CustomName = "Sillence (nightmare)", -- Custom name of your entity
    Model = 11699448654,
    Speed = 399, -- Percentage, 100 = default Rush speed
    DelayTime = 3, -- Time before starting cycles (seconds)
    HeightOffset = 0,
    CanKill = true,
    BreakLights = true,
    FlickerLights = {
        true, -- Enabled
        4, -- Time (seconds)
    },
    Cycles = {
        Min = 1,
        Max = 13,
        WaitTime = 3,
    },
    CamShake = {
        true, -- Enabled
        {5, 15, 0.1, 1}, -- Shake values (don't change if you don't know)
        1, -- Shake start distance (from Entity to you)
    },
    Jumpscare = {
        false, -- Enabled ('false' if you don't want jumpscare)
        {
            Image1 = "https://www.roblox.com/library/11401298618/bacon-but-not-as-mad", -- Image1 url
            Image2 = "https://www.roblox.com/library/11401297072/Bacon", -- Image2 url
            Shake = false,
            Sound1 = { 
               11400679305, -- SoundId
                { Volume = 1 }, -- Sound properties
            },
            Sound2 = {
                10483837590, -- SoundId
                { Volume = 0 }, -- Sound properties
            },
            Flashing = {
                false, -- Enabled
                Color3.fromRGB(70, 25, 0), -- Color
            },
            Tease = {
                false, -- Enabled ('false' if you don't want tease)
                Min = 1,
                Max = 1,
            },
        },
    },
CustomDialog = {"I hate this twin entity dude i swear for real", "You died to that stupid entity called Sillence.", "he is the dumbass twin of silence version.", "i want to ban this entity forever "},  -- Custom death message (can be as long as you want)
})

------------------------

-- Run the created entity
Creator.runEntity(entity)
end)
MainSection:NewButton("Figure", "Ragdoll", function()
local Creator = loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Utilities/main/Doors%20Entity%20Spawner/Source.lua"))()

local entity = Creator.createEntity({
    CustomName = "Figure", -- Custom name of your entity
    Model = 11738850341,
    Speed = 60, -- Percentage, 100 = default Rush speed
    DelayTime = 3, -- Time before starting cycles (seconds)
    HeightOffset = 0,
    CanKill = false,
    BreakLights = false,
    FlickerLights = {
        true, -- Enabled
        4, -- Time (seconds)
    },
    Cycles = {
        Min = 1,
        Max = 1000000,
        WaitTime = 3,
    },
    CamShake = {
        true, -- Enabled
        {5, 15, 0.1, 1}, -- Shake values (don't change if you don't know)
        1, -- Shake start distance (from Entity to you)
    },
    Jumpscare = {
        false, -- Enabled ('false' if you don't want jumpscare)
        {
            Image1 = "https://www.roblox.com/library/11401298618/bacon-but-not-as-mad", -- Image1 url
            Image2 = "https://www.roblox.com/library/11401297072/Bacon", -- Image2 url
            Shake = false,
            Sound1 = { 
               11400679305, -- SoundId
                { Volume = 1 }, -- Sound properties
            },
            Sound2 = {
                10483837590, -- SoundId
                { Volume = 0 }, -- Sound properties
            },
            Flashing = {
                false, -- Enabled
                Color3.fromRGB(70, 25, 0), -- Color
            },
            Tease = {
                false, -- Enabled ('false' if you don't want tease)
                Min = 1,
                Max = 1,
            },
        },
    },
})

------------------------

-- Run the created entity
Creator.runEntity(entity)
end)
RoomSection:NewButton("Bugla","no sound, what a beatiful cat", function()
    wait(2)
    local Creator = loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Utilities/main/Doors%20Entity%20Spawner/Source.lua"))()
   
       local entity = Creator.createEntity({
           CustomName = "Bugla", -- Custom name of your entity
           Model = 11749873715,
           Speed = 200, -- Percentage, 100 = default Rush speed
           DelayTime = 6, -- Time before starting cycles (seconds)
           HeightOffset = 0,
           CanKill = false,
           BreakLights = false,
           FlickerLights = {
               true, -- Enabled
               100, -- Time (seconds)
           },
           Cycles = {
               Min = 0,
               Max = 30000000,
               WaitTime = 2,
           },
           CamShake = {
               true, -- Enabled
               {0.6, 0.6, 9.1, 30.4}, -- Shake values (don't change if you don't know)
               3, -- Shake start distance (from Entity to you)
           },
           Jumpscare = {
               false, -- Enabled ('false' if you don't want jumpscare)
               {
                   Image1 = "https://www.roblox.com/library/11401298618/bacon-but-not-as-mad", -- Image1 url
                   Image2 = "https://www.roblox.com/library/11401297072/Bacon", -- Image2 url
                   Shake = false,
                   Sound1 = { 
                      11400679305, -- SoundId
                       { Volume = 1 }, -- Sound properties
                   },
                   Sound2 = {
                       10483837590, -- SoundId
                       { Volume = 0 }, -- Sound properties
                   },
                   Flashing = {
                       false, -- Enabled
                       Color3.fromRGB(70, 25, 0), -- Color
                   },
                   Tease = {
                       false, -- Enabled ('false' if you don't want tease)
                       Min = 1,
                       Max = 1,
                   },
               },
           },
       })
       
       ------------------------
       
       -- Run the created entity
       Creator.runEntity(entity)
   end)
   RoomSection:NewButton("Beluga","Better Version of bugla, But different", function()
    wait(2)
    local Creator = loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/Utilities/main/Doors%20Entity%20Spawner/Source.lua"))()
   
       local entity = Creator.createEntity({
           CustomName = "Beugla", -- Custom name of your entity
           Model = 11762288974,
           Speed = 200, -- Percentage, 100 = default Rush speed
           DelayTime = 6, -- Time before starting cycles (seconds)
           HeightOffset = 0,
           CanKill = false,
           BreakLights = false,
           FlickerLights = {
               true, -- Enabled
               100, -- Time (seconds)
           },
           Cycles = {
               Min = 0,
               Max = 30000000,
               WaitTime = 2,
           },
           CamShake = {
               true, -- Enabled
               {0.6, 0.6, 9.1, 30.4}, -- Shake values (don't change if you don't know)
               3, -- Shake start distance (from Entity to you)
           },
           Jumpscare = {
               false, -- Enabled ('false' if you don't want jumpscare)
               {
                   Image1 = "https://www.roblox.com/library/11401298618/bacon-but-not-as-mad", -- Image1 url
                   Image2 = "https://www.roblox.com/library/11401297072/Bacon", -- Image2 url
                   Shake = false,
                   Sound1 = { 
                      11400679305, -- SoundId
                       { Volume = 1 }, -- Sound properties
                   },
                   Sound2 = {
                       10483837590, -- SoundId
                       { Volume = 0 }, -- Sound properties
                   },
                   Flashing = {
                       false, -- Enabled
                       Color3.fromRGB(70, 25, 0), -- Color
                   },
                   Tease = {
                       false, -- Enabled ('false' if you don't want tease)
                       Min = 1,
                       Max = 1,
                   },
               },
           },
       })
       
       ------------------------
       
       -- Run the created entity
       Creator.runEntity(entity)
   end)

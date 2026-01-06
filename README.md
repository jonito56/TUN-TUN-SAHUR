_G.AutoStrat = true

-- [[ INITIALIZE LIBRARY ]]
local TDS =
loadstring(game:HttpGet("https://raw.githubusercontent.com/raxs0420/test/refs/heads/main/library%20new/new%20ui%20test%20test.lua"))()

TDS:Loadout("", "Scout", "Commander", "Mercenary Base", "Hacker")
TDS:Mode("Frost")
TDS:GameInfo("Honey Valley", {
    HiddenEnemies = true,
    Glass = true,
    Committed = true,
    Limitation = true,
    ExplodingEnemies = true
})

TDS:Place("Phantom", 2.01080, 60, 6.63390) -- 1
TDS:Place("Phantom", 5.52977, 60, 9.92086) -- 2
TDS:Place("Phantom", 3.61165, 60, -2.06873) -- 3
TDS:Place("Phantom", 8.34719, 60, 2.13215) -- 4
TDS:Place("Phantom", 5.20685, 60, -34.30589) -- 5


TDS:Place("Scout", 5.52977, 60, 9.92086) -- 1
TDS:Place("Scout", 5.52977, 60, 9.92086) -- 1
TDS:Place("Scout", 5.52977, 60, 9.92086) -- 1
TDS:Upgrade(1)
TDS:Upgrade(2)
TDS:Upgrade(3)
TDS:Upgrade(1)
TDS:Upgrade(2)
TDS:Upgrade(3)
TDS:Place("Scout", 5.52977, 60, 9.92086) -- 1
TDS:Upgrade(4)
TDS:Upgrade(4)
TDS:Place("Scout", 5.52977, 60, 9.92086) -- 1
TDS:Upgrade(5)
TDS:Upgrade(5)
TDS:Place("Scout", 5.52977, 60, 9.92086) -- 1
TDS:Upgrade(6)
TDS:Upgrade(6)
TDS:Place("Scout", 2.01080, 60, 6.63390) -- 1
TDS:Upgrade(7)
TDS:Upgrade(7)
TDS:Place("Scout", 2.01080, 60, 6.63390) -- 1
TDS:Upgrade(8)
TDS:Upgrade(8)
TDS:Place("Scout", 2.01080, 60, 6.63390) -- 1
TDS:Upgrade(9)
TDS:Upgrade(9)
TDS:Place("Scout", 5.52977, 60, 9.92086) -- 1
TDS:Upgrade(10)
TDS:Upgrade(10)
TDS:Place("Hacker", 5.52977, 60, 9.92086) -- 2
TDS:Upgrade(11)
TDS:Upgrade(11)
TDS:Place("Commander", 2.01080, 60, 6.63390) -- 1
TDS:Upgrade(1)
TDS:Upgrade(2)
TDS:Upgrade(3)
TDS:Upgrade(4)
TDS:Upgrade(5)
TDS:Upgrade(6)
TDS:Upgrade(7)
TDS:Upgrade(8)
TDS:Upgrade(9)
TDS:Upgrade(10)
TDS:Upgrade(1)
TDS:Place("Mercenary Base", 8.34719, 60, 2.13215) -- 1
TDS:Upgrade(13)
TDS:Upgrade(13)
TDS:Upgrade(13)
TDS:Place("Mercenary Base", 5.20685, 60, -34.30589) -- 4
TDS:Upgrade(14)
TDS:Upgrade(14)
TDS:Upgrade(14)
TDS:Place("Mercenary Base", 5.20685, 60, -34.30589) -- 4
TDS:Upgrade(15)
TDS:Upgrade(15)
TDS:Upgrade(15)

TDS:Loadout("Rocketeer", "DJ Booth", "Paintballer", "Firework Technician", "Commander")

TDS:Place("Firework Technician", 2.01080, 60, 6.63390) -- 4
TDS:Upgrade(16)
TDS:Place("DJ Booth", 2.01080, 60, 6.63390) -- 4
TDS:Upgrade(17)
TDS:Upgrade(17)
TDS:Upgrade(17)

TDS:SetOption(17, "Track", "Green")
TDS:Ability(17, "Drop The Beat", {Nill} , true)

TDS:Place("Commander", 2.01080, 60, 6.63390) -- 1
TDS:Upgrade(18)
TDS:Upgrade(18)
TDS:Place("Commander", 2.01080, 60, 6.63390) -- 1
TDS:Upgrade(19)
TDS:Upgrade(19)
TDS:Upgrade(12)
TDS:Upgrade(12)

TDS:AutoChain(12, 18, 19)

TDS:Upgrade(2)
TDS:Upgrade(3)
TDS:Upgrade(4)
TDS:Upgrade(5)
TDS:Upgrade(6)
TDS:Upgrade(7)
TDS:Upgrade(8)
TDS:Upgrade(9)
TDS:Upgrade(10)
TDS:Upgrade(13)
TDS:Upgrade(13)
TDS:Upgrade(13)

TDS:Ability(13, "Air-Drop", {pathName = 1, directionCFrame = CFrame.new(), dist = 50}, true)

TDS:Upgrade(14)
TDS:Upgrade(14)
TDS:Upgrade(14)

TDS:SetOption(14, "Unit 1", "Field Medic")

TDS:Ability(14, "Air-Drop", {pathName = 1, directionCFrame = CFrame.new(), dist = 50}, true)

TDS:Upgrade(15)
TDS:Upgrade(15)
TDS:Upgrade(15)

TDS:Ability(15, "Air-Drop", {pathName = 1, directionCFrame = CFrame.new(), dist = 50}, true)

TDS:Loadout("Sniper", "Warlock", "Accelerator", "Harvester", "Hacker")

TDS:Place("Warlock", 0.32170, 60, 14.38052) -- 6
TDS:Upgrade(20)
TDS:Upgrade(20)
TDS:Upgrade(20)
TDS:Upgrade(20)
TDS:Upgrade(20)
TDS:Upgrade(11)
TDS:Upgrade(11)
TDS:Upgrade(11)
TDS:Upgrade(12)
TDS:Upgrade(18)
TDS:Upgrade(19)
TDS:Place("Warlock", 0.32170, 60, 14.38052) -- 6
TDS:Upgrade(21)
TDS:Upgrade(21)
TDS:Upgrade(21)
TDS:Upgrade(21)
TDS:Upgrade(21)
TDS:Upgrade(16)
TDS:Place("Warlock", 0.32170, 60, 14.38052) -- 6
TDS:Upgrade(22)
TDS:Upgrade(22)

TDS:SetOption(13, "Unit 1", "Riot Guard")
TDS:SetOption(13, "Unit 2", "Riot Guard")
TDS:SetOption(13, "Unit 3", "Riot Guard")
TDS:SetOption(14, "Unit 1", "Riot Guard")
TDS:SetOption(14, "Unit 2", "Riot Guard")
TDS:SetOption(14, "Unit 3", "Riot Guard")
TDS:SetOption(15, "Unit 1", "Field Medic")
TDS:SetOption(15, "Unit 2", "Riot Guard")
TDS:SetOption(15, "Unit 3", "Rifleman")

TDS:SetOption(17, "Track", "Red")

TDS:Upgrade(22)
TDS:Upgrade(22)
TDS:Upgrade(22)
TDS:Upgrade(17)
TDS:Upgrade(17)
TDS:Place("Warlock", 0.32170, 60, 14.38052) -- 6
TDS:Upgrade(23)
TDS:Upgrade(23)
TDS:Upgrade(23)
TDS:Upgrade(23)
TDS:Upgrade(23)
TDS:Place("Accelerator", 3.61165, 60, -2.06873) -- 7
TDS:Upgrade(24)
TDS:Upgrade(24)
TDS:Upgrade(24)
TDS:Upgrade(24)
TDS:Upgrade(24)
TDS:Place("Accelerator", 3.61165, 60, -2.06873) -- 7
TDS:Upgrade(25)
TDS:Upgrade(25)
TDS:Upgrade(25)
TDS:Upgrade(25)
TDS:Upgrade(25)
TDS:Place("Accelerator", 3.61165, 60, -2.06873) -- 7
TDS:Upgrade(26)
TDS:Upgrade(26)
TDS:Upgrade(26)
TDS:Upgrade(26)
TDS:Upgrade(26)
TDS:Upgrade(12)
TDS:Upgrade(18)
TDS:Upgrade(19)
TDS:Place("Hacker", 2.01080, 60, 6.63390) -- 7
TDS:Upgrade(27)
TDS:Upgrade(27)
TDS:Upgrade(27)
TDS:Upgrade(27)
TDS:Upgrade(27)

TDS:Ability(11, "Hologram Tower", {
    towerToClone = 20,
    towerPosition = {
        Vector3.new(0.32170, 60, 14.38052),
    }
}, true)

TDS:Ability(27, "Hologram Tower", {
    towerToClone = 21,
    towerPosition = {
        Vector3.new(0.32170, 60, 14.38052),
        Vector3.new(0.32170, 60, 14.38052),
    }
}, true)

TDS:Ability(12, "Support Caravan", {Nill} , true)
TDS:Ability(18, "Support Caravan", {Nill} , true)
TDS:Ability(19, "Support Caravan", {Nill} , true)

TDS:Place("Accelerator", 3.61165, 60, -2.06873) -- 7
TDS:Upgrade(28)
TDS:Place("Accelerator", 3.61165, 60, -2.06873) -- 7
TDS:Upgrade(29)
TDS:Upgrade(28)
TDS:Upgrade(28)
TDS:Upgrade(28)
TDS:Upgrade(28)
TDS:Upgrade(29)
TDS:Upgrade(29)
TDS:Upgrade(29)
TDS:Upgrade(29)
TDS:Place("Accelerator", 3.61165, 60, -2.06873) -- 7
TDS:Upgrade(30)
TDS:Upgrade(30)
TDS:Upgrade(30)
TDS:Upgrade(30)
TDS:Upgrade(30)

TDS:Ability(13, "Air-Drop", {pathName = 1, directionCFrame = CFrame.new(), dist = 75}, true)
TDS:Ability(14, "Air-Drop", {pathName = 1, directionCFrame = CFrame.new(), dist = 75}, true)

TDS:Upgrade(16)
TDS:Upgrade(16)

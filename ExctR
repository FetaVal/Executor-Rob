-- Load the library
local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/PathosisX/Roblox-Script-Executor/master/Loader.lua"))()

-- Define the GUI
library.Loader:SetName("Script Executor")
library.Loader:SetWorkingDirectory(game.Players.LocalPlayer.PlayerScripts)
library.Loader:AddSection("Scripts")

-- Add a script to execute
local script = [[
-- Your script here
]]

-- Create a button to execute the script
library.Loader:AddButton("Execute Script", function()
    loadstring(script)()
end)

-- Open the GUI
library.Loader:Open() 

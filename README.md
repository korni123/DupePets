local lib = require(game.ReplicatedStorage:WaitForChild('Framework'):WaitForChild('Library')) 
local mydiamonds = string.gsub(game:GetService("Konradunio09").LocalPlayer.PlayerGui.Main.Right.Diamonds.Amount.Text, "%,", "") 
local mybanks = lib.Network.Invoke("get my banks") 
local PetsList = {} 

lib.Message.New("No Duped Pets found!")

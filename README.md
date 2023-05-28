# S-StarterBox

# Author
Created by: STRG#0420

# Config
`Config = {}
Config.AmountOfItems = 10 --how many times the script will loop
Config.OpenTime = 5000 --how long it takes to open (in ms)
Config.Joingiftitem = {
    [1] =  {
        item = "item1", -- Item name from your shared items.lua
        minAmount = 1, --Min amount of the item you want given out
        maxAmount = 5 --Max amount of the item you want given out
    },
}`
Able to add as many items as you want, with the min/max amount. also able to choose how many random items are given anf how long it takes to open!

# Read Me
Add this into your resource folder and remember to ensure "qb-starterbox" in your server's CFG (or just add it to an ensured folder)

Add the provided image into where your inventory's picture folder is. Usually inside the HTML folder.

Add this into your items.lua to create the usable item.

# Support will not be given for installing the script

`-- Starter Gift (change the name to something better, i was just too lazy to change it from testing)
	["tlmgiftbox"] = {["name"] = "tlmgiftbox", ["label"] = "Gift Box", ["weight"] = 7000, ["type"] = "item", ["image"] = "startergift.png", ["unique"] = true, ["useable"] = true, ["shouldClose"] = true, ["combinable"] = nil, ["description"] = "Welcome to [yourservername]! Here's a little gift for being new to the city :)"},`

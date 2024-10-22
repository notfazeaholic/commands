## **Note that anywhere you see these symbols <> encasing a word it means that you need to change the text/value of that string without including the <> symbols. For example a command like `/sethome <name>` would mean that you need to replace the <name> part of the command with your prefered name. If you're trying to set the home name as "home" then you'd simply type `/sethome home` Any word(s) in commands that do not have <> around them must stay unchanged**




​
# **Shop Commands:**

`/shop` - Opens up the shop and allows you to buy/sell items within it. If you are on Java you can left click to buy and right click to sell but if you are on Bedrock you will have to just select the item as if you're buying it then click on the redstone torch to switch between buying and selling options

`/sellall inventory` - Sells everything in your inventory that can be sold to the shop

`/sellall <item>` - Allows you to sell all the specified item(s) that are within your inventory by using their name

`/sellgui` -  Brings up a GUI where you can place whatever you want to sell to the shop and then simply exit the GUI and it will auto sell the items



​
# **Flight:**

`/fly` -Toggles the ability to fly if you have the fly time to do so. Flight time is displayed on the right side of your screen under your coins

`/fly shop` - Opens the fly time shop and allows you to purchase more flight time with in game currency



​
# **Coins:**

`/pay <playername> <amount>` - With this command you are able to pay your coins to other players

`/baltop` - Shows leaderboard of players with the most coins on the server



​
# **Player Vaults:**

`/pv` - Will show you all 3 available vaults that you have

`/pv <number>` - Will take you directly into that numbered vault be it 1,2 or 3



​
# **TP Commands:**

`/rtp` - Will randomly teleport you somewhere on the map within 50,000 blocks of spawn

`/tpa <playername>` -  Used to request a teleport to a specified player

`/tpaccept` - Needs to be used by the player getting the teleport request to allow for the teleportation to occur. Alternatively Java players can click on either accept or deny within the chat

`/back` - Brings you back to your last location before you teleported or can be used to bring you back to where you died if used after death

`/spawn` - Will bring you back to the main world spawn point



​
# **Auction House:**

`/ah` - Opens up the auction house GUI to show you what you or other players are selling

`/ah sell <price> <amount>` - This is how you can put your items up for people to buy on the auction house. You must be holding the item(s) you're wanting to sell in your hand when using this command! `<amount>` is just how many of that item you want to sell so if you have a stack of 64 and want to sell 32 of them, you'd type in 32 for the amount section



​
# **Set Home:**

`/sethome <name>` - You can set a teleport location to be saved so you can travel back and forth from it. Replace the word "name" with whatever you want to name that specific teleportation location. You are allowed up to 5 sethome locations

`/home <name>` - Allows you to teleport to your named home that you set

`/homelist` - Lists all the home locations you have saved by their names

`/delhome <name>` -  Will let you delete a specified home location



​
# **Land Claims:**

To claim land buy a **Golden Shovel** from the `/shop` for 100 coins then you can right click with the shovel on the ground in one corner of where you want to claim and then right click the opposite corner to claim your plot of land as if you're marking out two corners of a square

`/unclaim` - When standing in your own claimed land, use of this command will unclaim the land and give you back the claim blocks

`/buyclaim <amount>` - Gives you the option to buy more claim blocks to claim more land with. One block = 100 coins to purchase though you do earn claim blocks by simply playing the game

`/sellclaim <amount>` - If you have too many claim blocks and want to sell them for coins then use this command to sell each block for 100 coins



​
# **Portable Crafting:**

`/craft` - Brings up a crafting table UI



​
# **Slots**

`/slots <amount>` - Allows you to gamble any amount of money you have from 10 coins up to 1 billion coins in a slot machine



​
# **Coinflip**

`/cf` - Brings up coinflip menu and allows you to see other players coinflips or create a coinflip game of your own



​
# **Nicknames**

`/nick <nickname>` - Allows you to change your in game display name. You can create colored and gradient usernames [here](http://gradient.epicsmp.online) **making sure that you're using the color format `MiniMessage` otherwise it will not work!**

`/nonick` - Resets nickname back to your default name

`/realname <nickname>` - Shows nicknamed players real Minecraft name. Used mainly for command execution purposes like if for example you're trying to trade with the player

`/tab nametag preview` - Using this command will allow you to see your own nametag above your head when you go into third person. This feature should only be used for checking how the nametag looks temporarily and not be toggled on permanently. Running the same command again turns the preview off. You will notice your name lags behind you when previewing and that is only seen by you due to the nature of how Minecraft handles player packets



​
# **Trades**

`/trade <playername>` - Sends a trade request to the specified player


​

# **Item Renaming**

`/rename <name>` - Allows you to rename any item that you are currently holding in your hand to whatever you want it to say. Similarly to nicknames you can use hex codes to set up gradient or regular custom color names. **However** unlike nicknames the color format is not MiniMessage and is instead **&#rrggbb**. I have provided [this link](http://rename.epicsmp.online) which leads to the same website that is used for nicknames but **please make sure that you are using the color format `&#rrggbb` otherwise it will not work!**

`/rename` - Using this command alone will remove any renames done on item(s) and set them back to their default state


​

# **Sit Commands**

**You can sit on stairs and slabs by right clicking on the top of them however that interaction can get be disabled with the commands below**

`/sit` - Makes you sit on the spot

`/lay` - Makes you lay down on the ground

`/bellyflop` - Makes you lay on your stomach

`/spin` - Makes you spin in place

`/crawl` - Allows you to crawl around on your stomach though can be very buggy and glitchy

`/sit toggle` - Turns off/on the option to sit on slabs and stairs. Very useful for if you're trying to build with anything involving slabs or stairs

`/sit playertoggle` - Turns off/on the ability for other people to sit on your head when they right click on you and takes away your ability to sit on someone else's head if turned off


​

# **Block Condense**

`/condense` - When used it will condense raw ores and ingots into their block form


​

# **Player Warps**

`/warp` - Opens the warp GUI where you can see player warps and click on them to go straight to them

`/warp create <name>` - Allows you to create a warp that will be added to the warps GUI if kept public

`/warp delete <name>` - Lets you delete a warp. Alternatively you can also edit and delte warps through the GUI menu

`/warp go <name>` - Allows you to go directly to any warp with a command rather than through the GUI

`/warp info` - Shows information about a warp like location, rating and visits


​

# **Scoreboard Toggle**

`/sb toggle` - Toggles either on/off the scoreboard. Useful for if you want to see more of your screen or build without distractions

`/sb t` - Same thing as `/sb toggle` just abbreviated

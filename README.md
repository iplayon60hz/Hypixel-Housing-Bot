# Hypixel-Housing-Bot
Bot that executes commands on hypixel.
Sources:
https://hypixel.net/threads/guide-how-to-custom-commands.3523346/
https://github.com/MCCTeam/Minecraft-Console-Client
Very simple guide on how to get a basic hypixel housing bot with examples of commands. Mostly just for my own use because i'm unorganised as fuck but if you wanna use this go ahead. Make sure there is a matches.ini file. If there isn't one, you can make one simply by creating a text file putting some random word in and saving it as 'matches.ini'
An example here is:
[Match]
regex=!start 
action=send /tp $u -3 103 -31

The word action signifies the action the bot will take, so this action is send, which will send a message in chat. You don't want to change this, just the / command after. You can see the list of housing commands by doing /housing. Some commands, such as changing a player's housing rank via the bot, can only be done if you are logged in as the owner. The rest can just be done on your alt account.
Some common errors I saw was that my bot was being disconnected from hypixel. How to solve this? Just go to the MinecraftClient.ini file, and put the mcversion to 1.12.2, and brandinfo to forge. You can easily find these by doing Ctrl + F then searching. 
i'll add more later since i probably missed like 50% of the shit

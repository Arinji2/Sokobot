# Sokobot

Sokobot is a Discord bot written with [JDA](https://github.com/DV8FromTheWorld/JDA) that lets you play [Sokoban](https://en.wikipedia.org/wiki/Sokoban), the classic box-pushing puzzle game.

## Screenshots
![Level 1](https://cdn.discordapp.com/attachments/670425377503707146/727568442034487316/sokobot_v1.1.gif)
![Level 2](https://cdn.discordapp.com/attachments/670425377503707146/727567694597193829/sokobot_v1.1_.gif)

## Features
### Infinite levels
The maps in Sokobot are randomly generated, increasing in difficulty as you progress.
### Varied controls
Sokobot has multiple control options to improve the player's experience, including reactions and wasd commands!
### Simultaneous games
Thanks to the power of Java HashMaps™️, multiple users can use the bot at the same time without interfering with one another.
### Custom prefixes ``New!``
To prevent Sokobot from conflicting with other bots, admins can choose any single-character prefix to preface Sokobot's commands.

## Commands
### Game
- ``!play`` can be used to start a game if you are not currently in one.
- ``!stop`` can be used to stop your active game at any time.
- ``!help`` provides some useful details about the bot and rules of the game.
- ``!info`` provides some useful details about the bot and rules of the game.
### Economey ``NEW``
 - ``!bal`` shows the players balance
 - ``!shop``Sends an embed with the items you can buy/sell
 - ``!sell [item] [amt|max]`` sells items to the shop
 - ``!inv`` Sends an embed with your current inventory items
 - ``!buy [item] [amt|max]`` buys items off the shop
 - ``buy | inv | sell | buy | shop`` these can be accessed with an application command that sends a SelectMenu ``/eco``
### Admin 
- ``!prefix [character]`` can be used to change the prefix the bot responds to in the current server. 
### Dev ONLY
- ``!addmoney
- ``!setmoney
- ``!cmdreg [guildid] [cmd name] [description]

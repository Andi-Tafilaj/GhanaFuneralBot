# Attention!!!
This bot is temporary offline, DM me on Discord for help setting up! shaftAndi#5802

# Ghana Funeral Bot
A Discord Bot that takes 7 tokens to mass join 1 voice channel to play Astronomia

[Example](https://gfycat.com/delightfulsillykronosaurus)

# Invite
If you don't wish to self-host, that's alright. Here are the invite links to all the bots! Grab them quick before 100 servers take them all!

- [Main Bot](https://discordapp.com/oauth2/authorize?client_id=704560496971481108&permissions=36768772&scope=bot)
- [Henchmen 1](https://discordapp.com/oauth2/authorize?client_id=704560792468586576&permissions=36768772&scope=bot)
- [Henchmen 2](https://discordapp.com/oauth2/authorize?client_id=704560849947328573&permissions=36768772&scope=bot)
- [Henchmen 3](https://discordapp.com/oauth2/authorize?client_id=704560872126676992&permissions=36768772&scope=bot)
- [Henchmen 4](https://discordapp.com/oauth2/authorize?client_id=704560893207380010&permissions=36768772&scope=bot)
- [Henchmen 5](https://discordapp.com/oauth2/authorize?client_id=704078743575986257&permissions=36768772&scope=bot)
- [Coffin](https://discordapp.com/oauth2/authorize?client_id=704077241428082858&permissions=36766720&scope=bot)

# How to setup
Clone the repo and be sure you have nodejs version 12.0 or later installed.
Run `<npm install>` in the same directory of packages.json
Go to config.json and add 7 tokens. 
`<token_guy1>`Will be the bot that plays music and be the first one to join.
Run the bot simply with `<nodemon main.js >`

# How to use

Simply type !g join in the voice channel you're in. (Be sure you have admin permission) 

# Current Bugs
- If called in multiple voice chats in the same server, can cause errors. 

# Changelogs
**May 4th 2020**
* Merged pull request with [ExterminatorX99](https://github.com/ExterminatorX99)
  * Clients 1 - 6 are now under a for loop, I wasn't smart enough to think like that
  * Better formatting too
* Changed permissions from just Administrator to Manage Channels.

**May 1st 2020**
* Added !g ban <user mention> <reason> (popular request)
  * Be sure to give Benjamin Aidoo Ban permissions
  * Once executing the command, it will play the sound as normal, but after the music ends, the bot will ban the member and DM the member they have been banned 
* Made command and arg definition that I just copied from discordjs.guide
* Changed invite permissions to include Ban Members
**April 29th 2020**
* Changed duration from 20500 to 19500 for clients 1 - 6
* Better Logging
* Fixed packages.json whoops
* Added nodemon and console-stamp
* Added !g help

Feel free to report any bugs to me at shaftAndi#1825

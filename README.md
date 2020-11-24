# W-L-Bot
W-L-Bot is discord server bot is being created with JS using node.js and discord.js. Allowing players to track [ELO](https://en.wikipedia.org/wiki/Elo_rating_system) by logging wins/losses by typing commands after matches. Discord Owners, Admins, etc. moderate users W/L commands.


## The ELO system
- The ELO system within the bot created is calculated by the owners/admins of the discord server. The bot is being made as a competitive bot for smaller gaming communites that would like to implement some type of ELO system. 
  - An admin or moderator will spectate the game and mark the player who wins / the player who loses by using //@Player1 W or //@Player2 L.
  
### How the elo system will be calculated
- ELO will be calculated based on the input of W/L (Win/Loss). ELO was intended for Chess but can now be seen in all types of ranked games.
  -ELO is calculated based on the typical ELO calculation process. 
- 1: If the higher-ELO player wins, a few points are taken from the lower-ELO player and given to the higher-ELO player.
- 2: If the lower-ELO player wins, a sufficent / large amount of ELO is taken from the higher-ELO player.
- 3: If the match happens to end in a draw (This sometimes wont be used for certain games) the lower-ELO player takes a small portion of ELO from the higher-ELO player. 

#### The intention of this bot is to allow smaller startup games to have an ELO type system outside of the program itself (Discord), allowing developers to "test the water" on how a community can differ with an ELO system in place. This allows developers to make a final decision, which is whether or not Ranked play / ELO fits thier game.
  
![Image of W/L Bot](https://cdn.discordapp.com/attachments/726721469421453322/780825523358007326/My_Post_1.png)
  

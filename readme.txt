QUAKE 2 README:
Welcome to my COD Zombies Quake 2 Mod! 

First things first, the mod was built for the first map of the game campaign but 
I’m pretty sure it could work on other maps. As of the last commit, the wave based 
system has not been set up properly yet. I tried using possible player spawns in the 
map to spawn in berserks, but I still haven’t figured out how to spawn in more waves 
after the first one. Health and armor pickups were taken out of the game. 

Fortunately, I was able to set up the point system. Every kill gives the player 100 
points. The UI on the bottom left show in order from top to bottom: the round number, 
player points, and player lives. The player is able to go down twice before it is game
 over. Each hit on the player is 25 damage. If the player waits for 3 seconds, they 
will regenerate health all the way back to max health. 

I was also able to set up a perk system with a total of 5 perks. They are Juggernog, 
Staminup, Speedcola, Doubletap, and Scavenger. Juggernog costs 2500 points and grants 
the player an additional 100 health to their max health. Staminup costs 1500 points 
and allows the player to move faster. Speedcola costs 3000 points and allows the 
player to shoot faster with every gun. Doubletap costs 2000 points and allows the 
player to deal double damage. Scavenger costs 1000 points and gives the player double 
storage space for ammo. Every time the player goes down, they lose all their perks. 
To purchase the perks, the player must click either ‘Y’ for Juggernog, ‘U’ for 
Doubletap, ‘I’ for Speedcola, ‘O’ for Staminup, and ‘P’ for Scavenger. 

I was also able to set up a buy system for weapons, ammo, and upgrades. By clicking 
‘B’ and then 0-9, the player can purchase any of the weapons. The blaster is always 
on the player and cannot be purchased. The machine gun and shotgun cost 1000 points. 
If already owned, the player pays 250 points for more ammo. The super shotgun and 
grenade launcher cost 2500 points and 625 points for more ammo. The rocket launcher 
and hyperblaster cost 4000 points and 1000 points for more ammo. The chain gun and 
the rail gun cost 7500 points and 1875 for more ammo. The BFG10K costs 10000 points 
and 2500 points for more ammo. By upgrading the weapons, they will deal 3 times more 
damage. To upgrade, the player must click ‘N’ and then 0-9 for any of the weapons. 
Each upgrade is 5000 points and will be permanent throughout the game. 

I was also able to set up a powerup system. I was unable to figure out how to drop 
the powerups, so instead I made it on a random per kill basis. The player has a 5% 
chance of getting one of the perks on each kill. The five perks are Double Points, 
No Damage, Insta Kill, Max Ammo, and Fire Sale. Double Points grants the player to 
receive 200 points per kill for 15 seconds. No Damage allows the player to not take 
any damage for 15 seconds. Insta Kill allows the player to instantly kill enemies in 
one shot for 15 seconds. Max Ammo fills the player’s ammo up to full. Fire Sale allows
 the player to purchase any weapon or ammo for half the price. Upgrades and perks are 
not included because they are huge buffs that have to be earned. Powerups stack and 
can reset. I also added in “give points'' as a command to receive 5000 points on the 
spot. 

To set up the mod, take the “mod” folder in the git repository and put it into your 
Quake 2 directory in your Steam files. 

For the most part, I completed about 3 of the deliverables out of my 5: the perk 
system, the powerup system, and the buy/upgrade weapon system. 

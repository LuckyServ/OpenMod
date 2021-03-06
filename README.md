# OpenMod 1.2

OpenMod is a config based on [ZoneMod 1.9.3](https://github.com/SirPlease/ZoneMod). The goal of this config it to be open to community feedback
and make the necessary changes to make the game more enjoyable and balanced. The source code for all my plugins is also available in my [sourcemod-plugins](https://github.com/LuckyServ/sourcemod-plugins) repository.  
  
Main changes include but are not limited to:  

## Items

#### Shopping for items in the map

- Throwables are back

> In order to make shopping around for items appealing again, increase game depth and alleviate the lack of pills, throwables are back as well as gas cans, propane tanks, etc.

- Melees will be found in the map (no limits). Tonfas and CS Knife are disabled.

## Weapons

#### SMG
- SMG's damage dropoff has been increased, meaning the SMG does less damage based on distance.

> The range modifier is now set to 0.80 instead of the vanilla value 0.84.

## Special Infected

#### Spitter
- Spit now does 3 damage per tick (buffed from 2.5) 

#### Scratches
- Charger: 8 (nerfed from 10)
- Hunter: 2 (nerfed from 6)  

#### Witch

- The witch is back.

> Yet another way to increase the fun for SI and game depth.

#### Tank Rocks

- Tank rocks are now lag compensated. 

> High pingers! Shoot directly at the rock instead of ahead of it.

#### Tank Spawns
- Hard Rain c4m3: Removed the 20-35% tank spawn ban

#### Spawn Timer
- Spawn timers increased to 16 seconds (nerfed from 15)

## Scoring & Map Settings

#### Scoring system
- Implemented a new scoring system based on permanent health, current temporary 
health and potential temporary health.

> To read about the implementation of this new scoring system, click [here](https://github.com/LuckyServ/sourcemod-plugins/blob/master/source/l4d2_health_temp_bonus.sp).

#### Map distances
- Parish c5m1: 400 (buffed from 300)
- No Mercy c8m1: 400 (buffed from 300) 
- Death Toll c10m1: 400 (buffed from 300)
- Dead Air C11m1: 400 (buffed from 300)

#### Hordes
- c2m3 and c2m4 events are now infinite.  

## Miscellanous

- Survivors are now able to shove each other again. The throw + shove trick on cans also work again.

> As a side-note to other config devs, the cvar responsible for these 2 things above is called 'z_gun_survivor_friend_push'.

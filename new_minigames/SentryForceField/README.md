## ForceField

![alt tag](https://github.com/SoyGema/Startcraft_pysc2_minigames/blob/master/Images/ForceField2.png)

#### Description

The mini-game is an imbalanced  melee in between Zerg ans Prottoss.
The goal is to exploit sentry forcefield function 

#### Initial State

*   2 Sentry at left playable size
*   3 Hydralysks at right playable size
*   2 Zerlings at right playable size


 #### Rewards

Protoss defeated : -10
Zerg defeated : +10

 #### End Conditions

Time elapsed
Zerg defeated
Time Limit

180 seconds
 #### Additional Notes
Terrain condition designed for forcefield game development 
Fog of war disabled
No camera movement required (single-screen)
Note that this map is under development and should be re-sized for balance
Please note this work is still under development. If you find any relevant comment or issue feel free to open an issue

# Sentry Agent mini-game Map exploration for Forcefield map 

This part of the repository aims to post several agents regarding functions of sentry unit. 
SentryDefense.py --contains all the actions for sentrydefense unit
scripted_agent.py --contains tests for Forcefield Starcraft 2 map 

### Sentry unit scripted bot running

--Clone the repo 

--Put ForceField.sc2 map into your minigames map folder 

--Go to pysc2/maps/mini_games.py and add ForceField map to the array map

--In the /pysc2/agents/ folder type 

```
$ python3 -m pysc2.bin.agent --agent scripted_agent.SentryForceField --map ForceField
```

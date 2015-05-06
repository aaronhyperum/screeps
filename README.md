# Scripts for Screeps

**Anyone can use this - open game knowledge is open!**

**Be warned - Screeps is in alpha. The scripts are not guaranteed to work.**

Hello there, this is Aaron.

In this repo resides my scripts for the game 'Screeps' available here online (screeps.com). I hugely reccomend the game. It is an excellent learning tool for people of all ages and ranging between computer newbies to scripting professionals. I myself am not a scripting proffessional (though I do program) but this game has taught me quite a bit.

# Before you start

Before starting, make sure the names of your entities follow a naming convention. An easy one to follow is:
```
[name][id-number]
```
 This is the one used in the Screeps Tutorial. Examples include:

```js
Spawn1 // Your first spawnpoint
Scout7 // The seventh of your scouting creeps
Builder15 // The fifteenth of your construction creeps
```

# Starting out

The first thing you should know is how to make a creep. To do it:
```js
Game.spawns.[your-spawn-name].createCreep( [creep-parts-seperated-by-commas], '[creep-name]' );
//e.g.
Game.spawns.Spawn1.createCreep( [WORK, CARRY, MOVE], 'Worker1' );
```
The creep parts include:
```
MOVE
WORK
CARRY
ATTACK
RANGED_ATTACK
HEAL
```
There is an extra part, called TOUGH, which increases defense.

ETC



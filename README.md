# Scripts for Screeps

**Anyone can use this - open game knowledge is open!**

**Be warned - Screeps is in alpha. The scripts are not guaranteed to work.**

I may or may not continue working on these. You may use them if you want, though. Very largely incomplete.

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


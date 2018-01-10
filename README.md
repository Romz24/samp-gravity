# Player-Gravity
This include provides two functions to set and get player gravity.

## Functions:
```pawn
SetPlayerGravity(playerid, Float:gravity)
GetPlayerGravity(playerid, &Float:gravity)
```
Both functions will return 0 if the player id is not connected, otherwise 1.

If the gravity is set by the server through rcon or SetGravity, GetPlayerGravity will return that new value.

## Dependencies:
[Pawn.RakNet](http://forum.sa-mp.com/showthread.php?t=640306)

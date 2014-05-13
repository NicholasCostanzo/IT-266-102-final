IT-266-102-final
================
Multiplayer Mod Gravity Blast contains the following changes

Physics Mods:
-Player jump height is increased.
-Player speed is decreased.
-Gravity is greatly reduced.

Weapon modifications:
-Shotgun sends the user to the top of the map when fired.
-Nail gun moves the target player upward when hit.
-Lightning gun strikes the target player to the ground when hit.
-Machine gun holds the user to the ground while firing. If the user is moving, it accelerates them in that direction.
-Hyper blaster, nail gun, grenade launcher, and rocket launcher all cause (extreme) additional pushback from splash.

Powers/commands:
goup - command adds vertical velocity to the player, thrusting them upward.
gofast - adds a brief burst of speed - can be used as a dash in any direction.
hover - hold bound key to hover mid-air. Will only work while the player is not moving (can look around though).
normspeed - returns player speed to normal for 1000 tics. gofast cannot be used when in effect.
normgrav - returns player gravity/jump height to normal for 1000 tics.

example Quake4Config.cfg should contain -
bind "g" "goup"
bind "h" "hover"
bind "o" "gofast"
bind "p" "normspeed"
bind "l" "normgrav"

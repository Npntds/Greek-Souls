Fixes + Polish:

YAY -proper version control
nay -Character too bright outside and in general (method for lighting sucks, need new method)
YAY-Attack sounds play despite nothing being hit
nay -Axe needs textures (some textures aren't connected, need to figure out texturing in UE5)
nay -Target Lock needs fixing/adjustments for functionality and also ui (fixed/adjusted but no better ui)
-Camera less distance from player + smoother movements, current lag when locked on, camera snap to front of player for lock on when nothing to lock on and angle of camera more than 30
 degree different from front facing of player, camera angle dependent on height, also seems like 45-60 degree angle top down when locked on
nay -Player Movement Speed Should be variable to be easily swapped out (maxSpeed doesn't seem to affect max speed)
-multiplayer development implementation
-Interact should work with E to pickup instead of distance to object, also dropped items need a cool particle effect on them
-Enemies need to face player before attacking even if the distance is within attacking bounds,
also they should home in like a heat seeker when chasing, a bit of lag would help, also in the case of height, they shouldn't chase if their attacks can hit the player even if they are at a bigger height or smaller
-Enemy leaves weird shadow bug on the floor when attacking or moving
-Enemy health should only be visible on target lock
-Target Lock should stop when an enemy dies
-Enemies should not play animations or sounds or effects or deal damage or have collisions or have health bars after death
-Same things for boss
-Boss inherited small health bar needs to be invisible
-Fight should be triggered on boss agro instead of sphere proximity
-Boss needs proper interruption system when hit
-Enemies should have option to damage other enemies or bosses, same goes for bosses to enemies
-All controls of the player should be disabled on death, and respawn after a while with ui saying you died and sound and all, also world needs to reset and all
-Enemy vision needs fixing (sight range and hearing range)
-Stamina consumption on third sword attack needs syncing

Additions:

-Target Swapping needed
-More weapons needed + weapons types and movesets need implementation and combat
YAY -Boss hitboxes need fixing (deleted problematic attack XD)
-Boss needs proper moveset behavior tree, with chase in-between attacks so that he doesn't kill air
-Estus flask equivalent needed, with animation and effect and everything,
 also healing should be gradual and on interrupt damage should include possible healed health
-More Effects like camera shake
-Blood
-Background Music
-Importing Textures
-Importing Maps
-Need Icons for Items
nay -Need proper map instead of third person test map (boss arena in the works)
-Need Better Health,Stamina Bar Look, items selection, Bossbar, ui in general
-Player Model Needed
-Boss Model Needed
-Enemy Model Needed
-Better Animations Needed
-Sounds for everything of everyone needed
-Particle effects for everything of everyone needed

-- This is a fork of desire path mod by Casimir (https://forum.minetest.net/viewtopic.php?id=3390).
-- Trail mod 0.1.1 by paramat.
-- For latest stable Minetest and back to 0.4.4.
-- Depends default.
-- Licenses: Code CC BY-SA. Textures CC BY-SA. Textures are edited default Minetest textures.
-- The water sounds are from the ambience mod by Neuromancer (https://forum.minetest.net/viewtopic.php?id=2807),
-- and are by Robinhood76 (http://www.freesound.org/people/Robinhood76/sounds/79657/) license CC BY-NC.

Version 0.1.0
-------------
* Creates a trail of footprints in grass, dirt, sand, desert sand, gravel and the snow and snow block of snow biomes mod.
* Repeated walking of grass will wear it to dirt.
* Temporary trail of bubbles on water surface with a bubbly swimming / underwater sound.
* Trail creation can be disabled (while retaining footprint nodes) by editing parameter: FOO = false.
* Lightweight mod that runs the footprint function on average every 1 in 2 globalsteps, this is still enough to detect almost every node walked.
* Additionally parameter FOOCHA can be reduced for less per-node chance of a footprint, this works by randomly skipping the processing of certain players, therefore making the mod even more lightweight, useful for multiplayer situations.
* Pre 0.4.7 sand and desert sand footprint textures are also supplied in the texture folder but renamed.

Version 0.1.1
-------------
* Abm to erode footprints back to default nodes. Walked dirt heals to grass.
* Remove footprints in gravel for lighter code, so now 2 dirts, 2 sands, 2 snows.
* Improved textures.
* Parameter FUNCHA to optimise per globalstep chance of running function. Currently 0.3 seems optimum, creating an almost continuous trail if FOOCHA = 1 (continuous is boring), and eliminating unecessary processing.
* Added license.txt.

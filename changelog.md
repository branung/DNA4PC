Duke Nukem Advance PC port

Pre-1.0
---

Major overhaul of the backend code, weapons, enemies, distribution files, maps and whatnot..
Just a very quick TL;DR list
* All GBA specific map effects/gimmicks have been ported over and added to maps
* All GBA weapons implemented
* All GBA Intro/Mission/Ending/Mid-game cutscenes
* All GBA enemies and bosses implemented.
* Now with full Voicing by Gianni Matragrano for both EU/US script variants (opt-in)

Below is a laundry list on some of the stuff combed through over 300 commits.

- CHANGE: Restructuring on dir, loadable as a mod
- ADD: Shared ammo pool for shrinker/freezer
- ADD: Shrinker self-damage behavior from GBA
- FIX: Few elevators and texture panning
- CHANGE: Enemies now drop keycards with a set .extra instead of hacky CON hardcoding
- ADD: Step sounds
- ADD: Randomized level specific timed ambience sounds
- ADD: Ambient sound effects to maps (wind, machinery, etc..)
- ADD: Special palettes, i.e. reddish tone to some areas. Not fully accurate to GBA look.
- CHANGE: Major reworking of CON to no longer require shipping modified stock CON files.
- ADD: Loads of sounds and missing definitions
- ADD: Lead cannon (Quad shotgun) & Support for shared ammo pool with shotgun.
- ADD: "Area 51 Alarm", that gaudy alarm you see. Configurable to be less annoying than GBA.
- ADD: Support for Activatorlocked which can start as "Open" on map load
- ADD: Autoshading, Applies rudimentary directional map shading. Behing a toggle flag.
- ADD: SE25 Crusher setting which allows it to start off instead.
- ADD: SE70 "Floor sink", used to flood/unflood platforms which raise/lower (Doom style).
- ADD: SE71 "Door controller", Makes ST20 doors have GBA-like behavior. (Touch+Doomstyle)
- ADD: SE72 "Michael bay machine", Quake & Explosions & Screen rotation
- ADD: SE73 "Deadly egg timer", Starts a timer and kills the player if not disarmed on time.
- ADD: SE75 "Button combo", Once all required buttons have been pressed, fire output.
- ADD: SE77 "Texture swap", Used for breaking hybrid capsule walls on MAP02, sounds and visuals.
- ADD: SE78 "Camera view", upon triggering the player POV will switch to a defined camera view.
- ADD: SE79 "Trigger relay", Used as an effect proxy to allow delays from button press to action.
- ADD: SE80 "Cycler-not-cycler", Pulsates sector shade, smoothly or not-so-smoothly
- ADD: SE81 "Crusher/Pusher", Oscillates Ceiling or Floor surface like a crusher with sounds.
- ADD: SE82 "A51 Alarm", originally this was an enemy actor, which counted as a killcount also.
- ADD: SE32767 "Secret", Works exactly like sector tag counterpart. Defines a sector as a secret.
- ADD: Keycards as new actors, also includes CD/Chip/System. Comaptible with SE71
- ADD: Armorshard implemented
- ADD: Alternate ammo pickups
- ADD: Cutscene camera actor, Intended as a camera spot for ingame cutscenes
- FIX: Slimecrab is now in proper size
- ADD: Small health pack variant
- CHANGE: Moves many hardcoded tile definitions to use the GBA ones instead.
- FIX: Cutscene text now works with aspect ratios better
- CHANGE: Major cleanups in all maps, re-exported & some previously missing things are back in.
- CHANGE: Convert Gianni lines to ogg
- ADD: DNA specific buttons which also support "touch activation"
- ADD: Various DNA specific actors added to maps such as trash cans and hydroplants
- CHANGE: Overhaul done to all boss fights, including art fixes and AI.
- ADD: Toilet
- CHANGE: D3D remnant spawn-time knuckle cracking and associated sounds removed.
- CHANGE: Crushing no longer kills and instead damages the player.
- ADD: Freezethrower, and it's associated quirks
- ADD: Pipebomb, with additional art fixes.
- CHANGE: Removed D3D ART bundling dependency as we're no longer using those tile ranges.
- ADD: Basic enemy knockback for nearly all weapons
- ADD: 3DR Logo conversion for intro
- ADD: Editor scripts
- ADD: dnazoo.map which shows off many of the new effects
- CHANGE: Sky fixes so that they extend properly during maps instead of tiling vertically
- ADD: Remote cutscene trigger, use of icons is no longer necessary
- CHANGE: Moved over to hightile to work around palette limitations
- CHANGE: Enemy drop rates are now closer to GBA (much higher!)
- CHANGE: Removed extraneous (mod specific) pickups from maps now that drop rates are higher.
- CHANGE: Octobrain is now GBA-like
- CHANGE: Bundled binaries are now 32-bit to increase overall compatibility
- ADD: Full bootup intro sequence with company logos and text
- ADD: Crosshair switching! Switch between 9 different options.
- ADD: Toggle for cutscenes
- ADD: Toggle for key HUD
- ADD: GBA-esque sprites for DRONE and PIG TANK
- ADD: Golden gun
- ADD: End of level screen, complete with animation
- ADD: Mission briefing screen
- CHANGE: End screen updated for proper resolution
- ADD: Chapter selection screen
- ADD: Customize options now under "New game", crosshair/duketalk/region/presets
- ADD: GBA style skill selection screen with pictures
- CHANGE: Complete overhaul of the cutscene backend code, optimized and more resilient now.
- ADD: WIP DNA Duke design has been imported in with some modified D3D frames where needed
- ADD: Full end credits sequence
- ADD: Now with voicing by Gianni Matragrano


v0.8
--
Included in this update are all the cutscenes from the original game, implemented using a node system similar to World Tour's audio commentary feature. A custom mod menu has now been added to customize options such as which localization the cutscenes use, as well as the option to have specific Duke lines in cutscenes voiced by Gianni Matragrano!
On top of this, the original game's hud and font are now included, and tons of fixes have been made to every element to the game. Maps now have had been played through more thoroughly to correct misaligned textures and design inaccuracies, and 3D's enemies have been shaded to properly resemble their GBA versions.


v0.71
--
This is an early version of this TC. It includes the full campaign and enemies from the GBA game, but polishing is still underway.


Previously
--
All above work builds on top of:
https://github.com/voxelvoid/DNA4PC

Here are the original exported art assets & Initial maps

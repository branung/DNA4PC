# Duke Nukem : Advance for PC

A Total conversion called DNA4PC, which aims to port DN:A onto EDuke32 & Duke3D codebase.

DN:A itself runs on the proprietary Southpaw Engine developed by Torus games which is more known for powering the GBA port of Doom II. 
The GBA adaptation of Duke in many ways can be thought of as a mod for this engine, making DN:A mechanically and technically quite reminiscent of Doom's gameplay and limitations.

This conversion utilizes original assets such as sounds, graphics and levels with any necessary conversion and fixes to present them inside Build engine.
Much of the DNA4PC gameplay code is a hybrid of original Duke (Which DN:A imitates in the first place). 
This approach will not result in an exact replication but as much of the relevant DN:A specific experience as possible has been backported and adapted.
You can expect to see all of the major special Enemies, sounds and other gameplay behavior that forms the "DN:A experience" 

TL;DR -- Experience "Duke Nukem : Advance" with all the bells & whistles of today.

# Running

git clone this repo and run as `eduke32.exe -mx scripts/dna4pc.con`, no user-friendly setup yet

# Credits

Kind of poorly credited so far, consider this an inaccurate intial credits list which is better than nothing
- Voxelvoid - Initial work which had an export of maps & texture assets.
- branung - Much of the DN:A specific gameplay code, organizing, map fixes, some sounds and whatnot... Currently leading the efforts.
- oasiz - Additional mapping assistance & Map effects. Jumped in when all the hard work was already done.
- Dzierzan, Lead cannon HUD recreation ART
- Gianni Matragrano - Voice actor for Duke's lines in cutscenes when enabled.

# Duke Nukem : Advance for PC

A Total conversion called DNA4PC, which aims to port DN:A onto EDuke32 & Duke3D codebase.

DN:A itself runs on the proprietary Southpaw Engine developed by Torus games which is more known for powering the GBA port of Doom II. 
The GBA adaptation of Duke in many ways can be thought of as a mod for this engine, making DN:A mechanically and technically quite reminiscent of Doom's gameplay and limitations.

This conversion utilizes original assets such as sounds, graphics and levels with any necessary conversion and fixes to present them inside Build engine.
Much of the DNA4PC gameplay is a hybrid of original Duke3D (Which DN:A imitates in the first place) and re-inrtroduction of some "Doom'isms"
This approach will not result in an exact replication but as much of the relevant DN:A specific experience as possible has been ported over and adapted.
You can expect to see all of the major special Enemies, sounds and other gameplay behavior that forms the "DN:A experience".


TL;DR -- Experience "Duke Nukem : Advance" with all the bells & whistles of today.

# Running

git clone this repo and run as `eduke32.exe -x scripts/dna4pc.con`, or use the provided dna4pc.bat file.
You must include a valid Duke3D 1.5 data file (duke3d.grp) in the installation path!

# Additional shenanigans

As with all revisionist changes, there will be a lot of preferences on what's acceptable and what's not.

To make things simple, we have two presets that should make this easy:
PC ENHANCED: Keeps all the new GBA stuff in but also the following from below: Alarm reduction, Autoshade and voicing with duke3d oneliners
GBA ORIGINAL: Foregoes all of the above enhancements/"improvements" where applicable.

If you're still not satisfied then you can further customize your experience from the in-game "customize" menues.
1. Alarm sound: Lessen the gaudy loud alarm you hear in some maps as the GBA original is rather obnoxious, sounding roughly 10 times and retriggering after a while.
2. Step sound: Disables the step sounds which are new to the GBA version
3. Cutscenes: Requires manual toggling of cutscenes via in-game triggers. GBA has these automatic
4. Autoshade: Applies some much needed auto-generated basic 3D shading for walls and ceilings to make them pop more as the GBA original lacks any.
5. Voicing: Apply fitting duke3d oneliners for cutscenes or have the whole game voiced by Gianni Matragrano! GBA original is completely silent aside from gameplay.
6. Crosshair: Choose between 9 crosshairs

More may be added as per feedback.. let us know in the comments! :p

# Credits

- Voxelvoid - Initial work, Export of maps & texture assets.
- branung - Project lead, Main code, Art, Mapping, Design
- oasiz - Map effects, Editor support, Additional code & Design
- Dzierzan - Lead cannon HUD recreation ART
- Jimmy Gnosis - Pipebomb HUD tile fixes
- Hendricks266 - GBA 3DR title graphics palette conversion assistance
- Gianni Matragrano - Voice actor for Duke's lines in cutscenes when enabled.

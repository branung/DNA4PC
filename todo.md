# TODO

### Bugs:
- [ ] If a Pig cop is frozen and allowed to thaw, they remain in their frozen palette and can't be frozen again. They also have a chance of dropping two shotguns on freeze when they shouldn't drop any.
- [ ] Elevator for the lava pit in map04 always gets stuck the first time the player tries using it while in the pit.
- [x] The elevator secret in level 2 is broken
- [x] The Lead Cannon sometimes uses 1 or 5 bullets in a shot rather than 4
	- Needs repro steps!
- [x] Greys' projectile that revives dead enemies currently is fired in a random direction when it should home in on the nearest dead body.
- [x] Securty monitors don't work with proximity trigger (should proximity trigger logic be updated or should monitor screen be changed to cutscenes?)

### Menu/Settings:
- [ ] toggle for whistling frequency
- [x] toggle for alarm sound (once per map)
- [ ] toggle for step sounds
- [ ] toggle for autoshade
- [ Almost ] on first start it should ask "Enable recommended settings? - you wont miss out on anything but some  cosmetics and gameplay will be tweaked for better enjoyment on PC. these can be adjusted freely later on"
- [ ] toggle for automatic door/elevator trigger (proximity) .. only check for manual use
- [ ] toggle for "modern" cutscenes
- [ ] toggle for GBA enemy ai boost (exclusive enemies/boss, more pseudo PC whatif)
- [ ] toggle to use gba hud weapon art only(?)

### Possible Changes:
- [x] There's a strobing effect to lighting in certain areas of DNA that currently isn't replicated (ex: in the projector room in map08 should have a strobing effect that's currently not there) 
	- Effect implemented as SE80, maps need populating
- [ ] Shrinker and Freezer share an ammo type and ammo count in the original
- [ ] Shrinker has a wider attack field that can cause you to shrink yourself
- [ ] Freezer works identical to the shrinker, one shot that simply freezes an enemy rather than shrinks, but without any wide attack field
- [ ] Ability to toggle altered lotags on item pickups (ex: Lead Cannon and atomic health secret in map07 originally has them tagged with lotag 3. This was removed, but can possibly be toggled back on for purists)
- [ ] Toggle to prevent enemy gibbing like the original
- [ ] Prevent bullet and blood decals from showing in skyboxes and moving crushers
- [ ] Add GBA weapon carousel